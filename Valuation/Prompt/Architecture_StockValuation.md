# STOCK VALUATION PIPELINE — ARCHITECTURE & SETUP GUIDE

---

## PIPELINE OVERVIEW

```
┌─────────────────────┐     ┌──────────────────────┐     ┌─────────────────────┐
│  PROJECT: SECTOR    │     │  PROJECT: STOCK      │     │  PROJECT: STOCK     │
│  ANALYSIS           │     │  RESEARCH            │     │  VALUATION          │
│  (per sector)       │     │  (web search ON)     │     │  (web search OFF)   │
│                     │     │                      │     │                     │
│  R1 Landscape       │     │  R1_CompanyResearch   │     │  V1_StockValuation  │
│  R2 Financials      │────▶│  (one run per ticker) │────▶│  (one run per       │
│  R3 Catalysts       │     │                      │     │   ticker)           │
│  A  Analysis        │     │  OUTPUT: 10-module   │     │  OUTPUT:            │
│                     │     │  data dossier        │     │  • Price target     │
│  OUTPUT:            │     │                      │     │  • Full report      │
│  Sector Handoff     │─────┼──────────────────────┼────▶│  • Wheel handoff    │
│  (PASS list +       │     │                      │     │                     │
│   benchmarks)       │     │                      │     │         │           │
└─────────────────────┘     └──────────────────────┘     └─────────┼───────────┘
                                                                   │
                                                                   ▼
                                                         ┌─────────────────────┐
                                                         │  PROJECT: OPTIONS   │
                                                         │  WHEEL              │
                                                         │  (existing)         │
                                                         └─────────────────────┘
```

---

## PROJECT 1: STOCK RESEARCH

**Claude Project Name:** `Stock_Research`  
**Web Search:** ON  
**Purpose:** Produce valuation-grade company data dossiers  

### Project Instructions (paste into project settings)
```
This project produces company research dossiers for stock valuation.
Web search is enabled. Your job is to find accurate, sourced financial data.

RULES:
- You are a data collector, not an analyst. No opinions, no bull/bear framing.
- Source every number. Cross-reference critical metrics against 2+ sources.
- Flag confidence: ✓ (confirmed), ~ (estimated), ⚠️ (single source), [NOT FOUND].
- Use the sector handoff to know which metrics matter most for each company.
- If a number seems wrong or sources conflict, report both values — do not pick one.
- Fiscal year alignment is critical. Confirm FY end month before reporting anything.
```

### Prompt
- **R1_CompanyResearch.md** — paste as the prompt (attached separately)

### Knowledge Files
None required — this project searches the web for everything.

### How to Run
```
TICKER: ZS
COMPANY: Zscaler, Inc.
SECTOR: Cybersecurity
SECTOR HANDOFF:
[paste the full SECTOR ANALYSIS HANDOFF block from your sector analysis output]
```

---

## PROJECT 2: STOCK VALUATION

**Claude Project Name:** `Stock_Valuation`  
**Web Search:** OFF  
**Purpose:** Run 6 valuation methods, produce price targets and wheel handoff  

### Project Instructions (paste into project settings)
```
This project performs stock valuation analysis. Web search is OFF.
You work exclusively from the data provided in each message.

RULES:
- Run ALL 6 valuation methods for every company. No shortcuts.
- Show all math. Every assumption must be stated explicitly.
- Do not anchor to current price. Build from fundamentals up.
- If methods disagree significantly, explain why — don't average away the disagreement.
- SBC-adjusted FCF is mandatory for any company with SBC > 15% of revenue.
- Terminal value > 70% of total DCF = flag as speculative.
- Round-trip check every DCF against implied multiples.
- Produce all 3 deliverables: price target summary, full report, wheel handoff.
```

### Prompt
- **V1_StockValuation.md** — paste as the prompt (attached separately)

### Knowledge Files (recommended)

**1. Valuation_Benchmarks.md** (create and maintain over time)
Contents to build up:
- Historical SaaS EV/Revenue multiple ranges by growth tier
- Historical M&A transaction multiples for the sectors you cover
- WACC benchmarks by company risk profile
- Terminal FCF margin benchmarks by sector
- Rule of 40 score distribution across SaaS universe
- Risk-free rate + ERP assumptions (update quarterly)

**2. Sector Handoff** (pasted per-run, not a knowledge file)
The sector handoff is company-specific context — paste it fresh each run so V1 has the latest sector analysis.

### How to Run
```
TICKER: ZS
COMPANY: Zscaler, Inc.
CURRENT PRICE: $195.50
ANALYSIS DATE: March 29, 2026

R1 RESEARCH DOSSIER:
[paste full R1 output]

SECTOR HANDOFF:
[paste the SECTOR ANALYSIS HANDOFF block]
```

---

## WORKFLOW: END-TO-END FOR ONE COMPANY

### Step 1: Confirm target list
Check the sector analysis PASS list. Pick a ticker.

### Step 2: Run R1 in Stock_Research project
Paste the R1 prompt with the ticker, company name, sector, and sector handoff.
Review the output for completeness. If any critical module came back [NOT FOUND], 
do a follow-up search in the same chat to fill gaps before moving on.

### Step 3: Run V1 in Stock_Valuation project
Paste the V1 prompt with:
- Ticker, company name, current price (look it up right before pasting)
- Full R1 output from Step 2
- Sector handoff block from sector analysis

### Step 4: Review & iterate
- Check: Do the 6 methods roughly converge? If not, why?
- Check: Does the reverse DCF implied growth match your intuition?
- Check: Is the wheel handoff actionable? Strike zones make sense?
- If something looks off, challenge V1 in the same chat — it has all context loaded.

### Step 5: Feed wheel handoff to Options Wheel project
Copy the STOCK VALUATION → OPTIONS WHEEL HANDOFF block into your wheel project.

---

## BATCH WORKFLOW: FULL SECTOR CYCLE

For a sector with 5 PASS names (e.g., ZS, RBRK, CRWD, PANW, NET):

| Step | Project | Runs | Tokens (est.) |
|------|---------|------|---------------|
| Sector R1+R2+R3+A | Sector Analysis | 4 | Heavy |
| R1 × 5 companies | Stock Research | 5 | Medium each |
| V1 × 5 companies | Stock Valuation | 5 | Heavy each |
| **Total** | | **14 runs** | |

Estimated total: 14 runs per sector cycle. For 5 companies, expect ~2-3 hours of active work 
(mostly waiting for outputs + reviewing between runs).

---

## FUTURE UPGRADES

### V2 Auditor (add when you identify recurring failure modes)
Same pattern as your earnings pipeline B auditor:
- Web search ON
- Fed the V1 output
- Checks: Are consensus estimates current? Are M&A comps still valid? 
  Has anything material changed since R1 was run?
- Tags corrections as FACTUAL / JUDGMENT-SOURCED / JUDGMENT-UNSOURCED
- Discard JUDGMENT-UNSOURCED corrections (proven rule from earnings pipeline)

### Valuation Calibration Database
Track accuracy over time (like your Brier score SQLite for earnings):
- Record: ticker, analysis date, base case PT, actual price 3/6/12 months later
- Track which methods were most accurate by sector, by company type
- Use to adjust method weights in the triangulation over time

### Cross-Sector Comparison View
Once you have valuations across cyber, optics, AI infra, etc.:
- Rank all PASS companies across sectors by upside-to-base-case
- Capital allocation tool: "Given $X to deploy, which 3-5 names across all sectors?"
