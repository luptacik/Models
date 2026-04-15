# Dynatrace, Inc. (DT) — V2 Stock Valuation

**TICKER:** DT | **CURRENT PRICE:** $37.69 | **ANALYSIS DATE:** April 4, 2026

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency

| Method | Status | Notes |
|--------|--------|-------|
| DCF | ✓ | 12 quarters of revenue + FCF, guidance, consensus, share count, net cash |
| Trading Comps | ✓ | DDOG, ESTC, PD, NTCT from sector handoff |
| M&A Comps | ✓ | SWI ($6.7x), New Relic ($6.5B), Sumo Logic ($1.7B), Splunk ($28B) |
| Sum-of-Parts | PARTIAL | DT does not disclose segment-level revenue; estimates used |
| PE/LBO | ✓ | FCF, debt capacity, EV all available |

### Check 2: Fiscal Year Alignment

Dynatrace fiscal year ends **March 31**. FY2026 = Apr 2025 – Mar 2026. NTM from April 2026 = FY2027E (Apr 2026 – Mar 2027). FY2027E consensus revenue: $2,350M. FY2028E: ~$2,680M. All projections aligned to March year-end.

### Check 3: Share Count Reconciliation

| Metric | Shares (M) |
|--------|-----------|
| Basic outstanding (Dec 31, 2025) | 299.6 |
| Diluted weighted average (Q3 FY2026) | 304.0 |
| Unvested RSU/PSU pool | ~11.9 |
| Convertible notes | 0 (no converts) |
| **Fully diluted estimate (treasury method)** | **~305.0** |

All per-share calculations use **305.0M shares**. The $1B buyback at ~$37 could retire ~27M shares over 2–3 years, meaning net dilution is likely negative going forward.

### Check 4: SBC Materiality Assessment

| Metric | Value |
|--------|-------|
| TTM SBC | $297.2M |
| TTM Revenue | $1,932M |
| **SBC as % of Revenue** | **15.4%** |
| FCF (TTM) | $462.5M (24.0% margin) |
| FCF ex-SBC (TTM) | $165.3M (8.6% margin) |

**⚠️ SBC at 15.4% triggers the dual-track FCF requirement.** SBC consumes ~64% of reported FCF. All FCF-based methods present both standard and ex-SBC versions.

### Key Valuation Inputs

| Metric | Value |
|--------|-------|
| Market Cap | $11,495M |
| Net Cash | $1,247M |
| Enterprise Value | $10,249M |
| EV/NTM Revenue (FY2027E $2,350M) | 4.4x |
| EV/TTM FCF | 22.2x |

---

## METHOD 1: REVERSE DCF

**Purpose:** What growth rate is the market pricing in?

```
REVERSE DCF RESULTS
━━━━━━━━━━━━━━━━━━
Current EV: $10,249M
Assumptions: Terminal FCF margin 27%, terminal growth 3%, WACC 10%

Implied revenue CAGR: 6.5%
Current actual revenue growth: 18.2% (reported)
Constant-currency ARR growth: 16%
Consensus NTM revenue growth: ~15%
Management long-term growth: ~15% (implied by consensus trajectory)

GAP ANALYSIS:
Market implies 6.5% growth vs. 15–16% CC actual/guided
→ Market is pricing in DECELERATION to 6.5% — WELL BELOW consensus
→ STRONG UNDERPRICING SIGNAL if DT maintains 14–16% growth
```

### Sensitivity: Implied Revenue CAGR (%)

| WACC \ Terminal FCF Margin | 20% | 25% | 30% | 35% |
|----------------------------|-----|-----|-----|-----|
| 9% | 7.5% | 5.2% | 3.3% | 1.7% |
| **10%** | **9.7%** | **7.3%** | **5.4%** | **3.7%** |
| 11% | 11.7% | 9.3% | 7.3% | 5.7% |
| 12% | 13.7% | 11.2% | 9.2% | 7.5% |

**Interpretation:** Even at 12% WACC and a conservative 20% terminal FCF margin, the market only prices in 13.7% growth — still below DT's current 16% CC rate. At the base case (10% WACC, 27% terminal FCF margin), implied growth of 6.5% is less than *half* of actual growth. This is the strongest mispricing signal in the analysis.

---

## METHOD 2: FORWARD DCF (3-SCENARIO)

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|------------|------|------|------|
| Yr 1–2 Rev CAGR | 17% | 14.5% | 12% |
| Yr 3–5 Rev CAGR | 14–16% | 11–13% | 8–10% |
| Yr 6–7 Rev CAGR | 12–13% | 10% | 6–7% |
| Terminal FCF Margin | 33% | 30% | 27% |
| Terminal Growth Rate | 3% | 3% | 3% |
| WACC | 9.5% | 10.0% | 11.0% |

**BULL — What must go right:** NRR inflects above 113%, log management consumption continues 50%+ growth, DPS drives broader platform adoption, AI agent monitoring becomes material revenue, $1B buyback maximally accretive at depressed prices.

**BASE — Most likely path:** Consensus trajectory with 14–15% growth decelerating gradually, steady margin expansion, NRR stable at 110–112%, buyback offsets dilution. DT executes its beat-and-raise cadence through FY2027.

**BEAR — What could go wrong:** Datadog takes enterprise share aggressively, OTel production adoption crosses 20% reducing switching costs, NRR falls below 108%, consumption model underperforms expectations, macro headwinds lengthen enterprise sales cycles.

### Base Case Revenue Projection

| Year | Revenue ($M) | YoY Growth | FCF Margin | FCF ($M) | Disc Factor | PV ($M) |
|------|-------------|------------|------------|----------|-------------|---------|
| 1 | 2,309 | 15.0% | 27.0% | 623 | 0.9091 | 567 |
| 2 | 2,632 | 14.0% | 27.0% | 711 | 0.8264 | 587 |
| 3 | 2,974 | 13.0% | 28.0% | 833 | 0.7513 | 626 |
| 4 | 3,331 | 12.0% | 28.0% | 933 | 0.6830 | 637 |
| 5 | 3,697 | 11.0% | 29.0% | 1,072 | 0.6209 | 666 |
| 6 | 4,067 | 10.0% | 29.0% | 1,179 | 0.5645 | 666 |
| 7 | 4,474 | 10.0% | 30.0% | 1,342 | 0.5132 | 689 |
| Terminal Value | — | — | 30.0% | — | — | 10,134 |

### Valuation Summary

| | Bull | Base | Bear |
|---|------|------|------|
| PV of Cash Flows | $5,314M | $4,437M | $3,573M |
| PV of Terminal Value | $14,653M | $10,134M | $6,192M |
| Enterprise Value | $19,967M | $14,571M | $9,765M |
| Net Cash | $1,247M | $1,247M | $1,247M |
| Equity Value | $21,214M | $15,817M | $11,011M |
| Fully Diluted Shares | 305M | 305M | 305M |
| **Per Share Value** | **$69.55** | **$51.86** | **$36.10** |
| Upside/(Downside) | +84.5% | +37.6% | -4.2% |
| TV as % of Total | 73.4% | 69.5% | 63.4% |

⚠️ **Bull case:** Terminal value is 73% of total — valuation dominated by long-term assumptions.

### FCF ex-SBC Dual Track

| | Bull | Base | Bear |
|---|------|------|------|
| Per Share (ex-SBC) | $46.03 | $31.89 | $20.50 |
| vs. Standard FCF | -33.8% | -38.5% | -43.2% |

The SBC adjustment reduces per-share value by 34–43%. The "true" economic value to equity holders — accounting for the real dilution cost of SBC — sits between the standard FCF and ex-SBC figures. The base case standard FCF value of $51.86 and ex-SBC value of $31.89 bracket a realistic range of ~$38–48 for a fully SBC-conscious investor.

### Round-Trip Check

Base case implies EV of $14,571M. At FY2027E revenue of $2,350M → implied EV/NTM Rev = 6.2x. For a 14–15% grower with 30% non-GAAP operating margins, Rule of 40 at 44, and zero debt, 6.2x is **reasonable and within the sector handoff's 4–10x range** for 15–30% growers. ✓ Pass.

---

## METHOD 3: TRADING COMPS

### Peer Set

| Company | EV/NTM Rev | Growth | Growth-Adj | FCF Margin | Rule of 40 | EV/NTM FCF |
|---------|------------|--------|------------|------------|------------|------------|
| DDOG | 9.2x | 20% | 0.46x | 26.7% | 55 | 34.4x |
| **DT** | **4.4x** | **15%** | **0.29x** | **26.0%** | **44** | **16.8x** |
| ESTC | 2.2x | 15% | 0.15x | 15.3% | 33 | 14.7x |
| PD | 0.9x | 0% | N/M | 20.9% | 26 | 4.5x |
| NTCT | 1.9x | 5% | 0.37x | 27.0% | 32 | 6.9x |

### Target Company Positioning

- **Growth rank:** 2 of 5 (15% NTM growth, behind DDOG's 20%)
- **FCF margin rank:** 3 of 5 (26%, comparable to DDOG)
- **Rule of 40 rank:** 2 of 5 (44, significantly ahead of ESTC/PD/NTCT)
- **Current multiple vs. peer median:** DT trades at a premium to ESTC/PD/NTCT but deep discount to DDOG

### Fair Value Estimate

**Method:** Growth-adjusted regression positioning DT between DDOG (0.46x) and ESTC (0.15x).

DT deserves a **premium to ESTC** (sector score 21/25 vs. 16/25, zero debt, higher margins, stronger moat, better execution, lower insider selling risk) and a **discount to DDOG** (slower growth, narrower platform, lower NRR at 111% vs. 120%).

However, the growth-adjusted multiple at 0.29x is already near the midpoint — suggesting the current trading comp valuation is approximately fair on a peer-relative basis. The sector-wide multiple compression (SaaSpocalypse) has compressed all observability names, and DT is trading in line with its quality-adjusted position.

**Alternative approach:** The sector handoff benchmarks show 15–20% growers in observability trading at a median of 5–8x EV/NTM Rev historically. At the midpoint (5.5x), DT would be worth **$46.46** (+23.3%). The current 4.4x is below the historical low end for DT's growth/margin profile, reflecting the sector-wide de-rating.

- **Comps-implied price (growth-adjusted):** $36.45 (-3.3%)
- **Comps-implied price (historical median):** $46.46 (+23.3%)
- **Midpoint:** ~$41.50 (+10.1%)

---

## METHOD 4: PRECEDENT M&A COMPS

### Comparable Transactions

| Date | Target | Acquirer | EV ($B) | EV/Rev | Growth | Premium |
|------|--------|----------|---------|--------|--------|---------|
| Apr 2025 | SolarWinds | Turn/River Capital | $5.3B | 6.7x | 5% | 35% to VWAP |
| Nov 2023 | New Relic | Francisco Partners + TPG | $6.5B | 6.8x | 3% | 55% |
| May 2023 | Sumo Logic | Francisco Partners | $1.7B | 5.2x | 5% | 37% |
| Mar 2024 | Splunk | Cisco | $28.0B | 7.4x | 8% | 31% |
| 2025 | Chronosphere | Palo Alto Networks | $3.4B | 20.9x | 100% | N/A (private) |
| Dec 2025 | Catchpoint | LogicMonitor | $0.3B | 5.0x | 10% | N/A (private) |

### Takeout Valuation

DT falls in the **"Growth-stage (15–30%)"** tier from the sector handoff: 6–10x ARR. With a quality premium for zero debt, 15-year Gartner Leadership, and causal AI differentiation: applicable range is **7–9x ARR**.

| Metric | Value |
|--------|-------|
| Target ARR | $1,972M |
| Applicable multiple range | 7–9x ARR |
| Implied EV range | $13,804M – $17,748M |
| After control premium discount (25%) | $10,353M – $13,311M |
| **Implied share price range** | **$38.03 – $47.73** |
| **Midpoint** | **$42.88 (+13.8%)** |

**Probability assessment:** MODERATE. DT at ~$11B market cap is within range for large strategics (IBM, ServiceNow) or PE mega-funds (KKR, Apollo, Vista). Most plausible scenario: IBM (combining Instana + DT for enterprise observability leadership) or PE take-private. Cisco is unlikely post-Splunk. Thoma Bravo fully exited in 2024.

---

## METHOD 5: SUM-OF-PARTS

⚠️ **LOW CONFIDENCE** — DT does not disclose segment revenue. Estimates derived from log management disclosure ($100M+), product mix commentary, and residual allocation.

| Segment | Revenue ($M) | Growth | Comparable | Multiple | Implied EV ($M) |
|---------|-------------|--------|------------|----------|----------------|
| Core APM / Infra / AIOps | 1,550 | 14% | DT core platform | 5.0x | 7,750 |
| Log Management (Grail) | 110 | 100% | High-growth log analytics | 12.0x | 1,320 |
| Security (RASP/Vuln) | 140 | 25% | Cloud security (CNAPP) | 8.0x | 1,120 |
| DEM (RUM/Synthetic) | 120 | 12% | DEM point solutions | 4.0x | 480 |

| Metric | Value |
|--------|-------|
| Total EV | $10,670M |
| Net Cash | $1,247M |
| Equity Value | $11,917M |
| **Per Share** | **$39.07** |
| Upside/(Downside) | +3.7% |

**HIDDEN VALUE FLAG:** Log management at >100% growth and $110M+ annualized run rate is valued at $1,320M here. A standalone log analytics business at this growth rate would command 15–20x revenue — at 15x that's $1,650M, adding $1.08/share. The market assigns zero premium for DT's consumption-model optionality embedded in the Grail data lakehouse.

---

## METHOD 6: PE / LBO FLOOR

### Entry Assumptions

| Metric | Value |
|--------|-------|
| Current EV | $10,249M |
| Entry premium | 20% |
| Entry EV | $12,299M |
| EBITDA proxy (Non-GAAP OI) | $585M |
| Debt | $2,048M (3.5x EBITDA) |
| Equity invested | $10,251M |

### 5-Year Projection

| Year | Revenue ($M) | FCF ($M) | Cumulative FCF ($M) |
|------|-------------|----------|-------------------|
| 1 | 2,309 | 623 | 623 |
| 2 | 2,632 | 711 | 1,334 |
| 3 | 2,974 | 833 | 2,167 |
| 4 | 3,331 | 933 | 3,099 |
| 5 | 3,697 | 1,072 | 4,171 |

### Exit & Returns

| Metric | Value |
|--------|-------|
| Exit NTM Revenue | $4,067M |
| Exit multiple | 5.0x NTM Revenue |
| Exit EV | $20,335M |
| MOIC | 2.25x |
| Implied IRR | 17.6% |

### Floor Price

| Metric | Value |
|--------|-------|
| Target IRR | 20% → Required MOIC 2.49x |
| **Max entry price for 20% IRR** | **$35.02 per share** |
| Current price | $37.69 |
| Downside to PE floor | +7.6% |

**Reality check:** PE interest is realistic. DT generates $500M+ annual FCF, has zero debt, 82% gross margins, and a sticky enterprise base. SWI went private at $5.4B EV, New Relic at $6.5B. At ~$10B EV, DT is within range for mega-fund PE.

---

## DELIVERABLE 1: VALUATION SUMMARY & CONVICTION SCORE

```
━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━
TICKER: DT
CURRENT PRICE: $37.69
ANALYSIS DATE: April 4, 2026

METHOD RESULTS:
Method                    Bear     Base     Bull   Weight  Conf
───────────────────────────────────────────────────────────────
Reverse DCF                —    6.5% implied CAGR   —      —     H
Forward DCF             $36.10  $51.86  $69.55     40%     H
  (FCF ex-SBC track)    $20.50  $31.89  $46.03     ref     —
Trading Comps              —    $36–46     —       25%     H
M&A Comps                  —    $42.88     —       15%     M
Sum-of-Parts               —    $39.07     —       10%     L
PE/LBO Floor            $35.02     —       —       10%     M

TRIANGULATED PRICE TARGET:
  Bear case: $35.56 (-5.7%)
  Base case: $43.70 (+15.9%)
  Bull case: $57.29 (+52.0%)

FCF ex-SBC reality check (base): $34.62
SBC drag on per-share value: $9.07 (21%)

CONVICTION SCORE: 4 / 5

CONVICTION RATIONALE:
DT is a Gartner-leading enterprise observability platform with 16% CC
growth, 30% operating margins, zero debt, and $1.25B net cash — trading
at 4.4x EV/NTM Rev. The Reverse DCF reveals the market prices in only
6.5% growth vs. 15–16% actual/consensus — the widest implied-vs.-actual
growth gap in the current portfolio. Five of six methods indicate upside.
The CCO insider buy at $35.75 and $1B buyback provide floor support.
Deduction from 5: NRR flat at 111% for 3 quarters limits expansion
confidence; SBC at 15.4% creates a real 21% drag on per-share value;
and FX tailwind (~$49M) flatters reported growth vs. CC reality.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### Weighting Rationale

- **Forward DCF at 40%:** DT has predictable recurring revenue (96% subscription), clear margin trajectory (29–30% non-GAAP OI expanding), and 7 consecutive quarters of beat-and-raise guidance. High confidence in projection inputs.
- **Trading Comps at 25%:** Peer set is well-defined (DDOG, ESTC direct comparables). DT's growth-adjusted multiple of 0.29x is near the peer median. Some tension between current-market-relative and historical-median approaches.
- **M&A Comps at 15%:** Robust transaction set (SWI, New Relic, Splunk). DT is a plausible takeout target. Control premium discount of 25% is conservative.
- **Sum-of-Parts at 10%:** Reduced from standard weight due to estimated (not disclosed) segment revenue. Directionally supportive but not precise.
- **PE/LBO Floor at 10%:** DT is a realistic PE target. Floor of $35.02 provides downside reference.

---

## DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━
TICKER: DT
COMPANY: Dynatrace, Inc.
SECTOR: Cloud Observability / Monitoring
VALUATION DATE: April 4, 2026

PRICE TARGET: $43.70 base case (range: $35.56 bear — $57.29 bull)
CURRENT PRICE: $37.69
UPSIDE TO BASE: +15.9%
CONVICTION: 4/5

WHEEL STRATEGY IMPLICATIONS:

  SELL PUTS: YES
    Rationale: Stock is 16% below base case PT with 4/5 conviction.
    PE floor at $35.02 and bear case at $35.56 provide hard downside
    reference. Selling puts at/below the bear case captures premium
    with meaningful margin of safety.
    Strike zone: $30.00–$33.00 (at or below bear case)
    Avoid puts above: $38.00 (near current price, limited margin)

  COVERED CALLS (if assigned): YES
    Cost basis assumption: $31.50 (midpoint of put strike zone)
    Minimum call strike: $31.50 (cost basis floor)
    Suggested call strike zone: $40.00–$45.00
    Do NOT sell calls above: $57 (approaching bull case — let it run)

  CONCENTRATED LONG CANDIDATE: CONDITIONAL
    Conviction ≥ 4: ✓ (4/5)
    Upside to base ≥ 30%: ✗ (16%)
    Does NOT meet 30% upside threshold at current price
    Becomes concentrated long if price dips below $33.61

KEY DATES TO AVOID (earnings, catalysts):
  May 20, 2026: Q4 FY2026 / Full-year earnings + FY2027 guidance
    → HIGH impact. $2B ARR milestone, FY2027 outlook critical.
    → Avoid opening new put positions 2 weeks before.
  Aug 2026 (est.): Q1 FY2027 earnings
  Nov 2026 (est.): Q2 FY2027 earnings

SECTOR CONTEXT:
  Sector score: 21/25
  Ranking: 2 of 5 (behind DDOG at 22/25)
  Sector risk: SaaSpocalypse multiple compression ongoing;
    OTel production adoption at 11% rising ~5pp/yr;
    telemetry cost crisis (96% of teams reducing spend)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```
