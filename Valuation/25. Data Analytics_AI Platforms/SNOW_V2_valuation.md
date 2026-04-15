# SNOW — V2 Stock Valuation

**Ticker:** SNOW (NYSE)
**Company:** Snowflake Inc.
**Sector:** Data Analytics / AI Platforms
**Current price:** $121.11
**Analysis date:** April 12, 2026
**Fiscal year end:** January 31 (FY26 = year ended Jan 31, 2026)

---

## PRE-MODEL CHECKS

**Data sufficiency:** R1 dossier provides full FY26 actuals, Q4 print, FY27 guide, and consensus estimates. Sector handoff provides peer multiples calibrated as of early April. Method weights are adjusted downward for M&A comps and LBO where the $45B+ scale makes acquirer scenarios structurally unrealistic.

**Fiscal year alignment:** SNOW reports on a Jan 31 fiscal year end. All peer multiples from the sector handoff (DDOG, NOW, MDB, VEEV) have been cross-referenced. "NTM" here means the forward 12 months from the report date, which maps almost exactly to FY27 (Feb 2026 – Jan 2027).

**Share count reconciliation:**
- Basic shares (Q4 FY26 wt avg): 342.3M
- GAAP diluted (= basic, as company is in GAAP net loss): 342.3M
- **Non-GAAP fully diluted incl. if-converted convertibles: 376M** (per FY27 company guide footnote; includes ~12M dilutive shares from the two $1.15B 0% converts with $157.50 strikes; offset by capped call mechanics)
- **Used throughout this valuation:** 376M fully diluted shares. This is the economically correct share count and avoids flattering per-share math.

**SBC materiality:** FY26 SBC = $1,599.55M = **34.1% of revenue** — more than double the 15% threshold and the highest in the entire Data Analytics / AI Platforms sector peer set. Dual-track FCF presentation is mandatory.

| Metric | FY26 Value |
|---|---|
| Reported Adj FCF | $1,192.7M (25.5% margin) |
| GAAP FCF | $1,120.3M (23.9% margin) |
| **FCF ex-SBC** | **−$479.2M (−10.2% margin)** |
| FY26 buybacks (offset) | $873.5M (offsets only ~55% of cash SBC) |

This is the defining analytical tension for SNOW: the company appears highly cash-generative on a reported basis but is destroying economic value when stock-based comp is treated as a real expense. Both views are presented below.

**EV calculation (at $121.11):**
- Market cap: 376M × $121.11 = **$45.54B**
- Less: cash + investments ($4,785M) − convert face ($2,280M) = net cash $2,505M
- **Enterprise value: $43.03B**
- **EV / NTM Revenue (FY27 $5.93B consensus): 7.26x** — notably below the sector handoff's 8.3x reference point. The ~$50 price decline from $172 (Feb 26) to $121 (Apr 12) has taken ~1.1 turns off the multiple.

---

## METHOD 1 — REVERSE DCF

**Purpose:** What growth rate is the market pricing in at $121.11? Primary mispricing diagnostic.

**Assumptions:**
- Starting revenue: $4,684M (FY26 actual)
- Terminal FCF margin: 30% (mature SaaS benchmark; sector handoff cites 25–35% for mature CRM/NOW/VEEV/FICO)
- Terminal growth: 3% (GDP perpetuity)
- WACC: 10%
- FCF margin ramps linearly from current 25.5% to 30% terminal over 10 years
- Enterprise value solved: $43.03B

**Result: Implied 10-year revenue CAGR = 13.2%**

Compare this to:
- FY26 actual growth: +29%
- FY27 consensus / company guide: +27%
- Sector handoff typical sector-winner range: 20–30% sustained
- Databricks growing 55% as direct competitor

**Sensitivity — Implied 10yr CAGR:**

| WACC \ Term FCF Margin | 20% | 25% | 30% | 35% |
|---|---|---|---|---|
| 9% | 15.4% | 12.9% | 10.9% | 9.1% |
| 10% | 17.9% | 15.3% | **13.2%** | 11.5% |
| 11% | 20.1% | 17.5% | 15.4% | 13.6% |
| 12% | 22.3% | 19.6% | 17.4% | 15.6% |

**Interpretation:** Even under aggressive assumptions (12% WACC, 20% terminal margin), the market implies no better than 22% CAGR — and the center case around 10% WACC / 30% terminal implies ~13%. This is materially below consensus NTM growth and implies a very fast deceleration from 29% to single digits within a few years. The reverse DCF is the cleanest mispricing signal of the six methods: **on a reported-FCF basis, SNOW at $121 is pricing in a sharp structural deceleration that is not supported by the RPO growth of +42% YoY, the seven 9-figure Q4 deals, or the 125% NRR.**

**Critical caveat:** If you believe FCF must be adjusted for SBC, the terminal margin assumption collapses to ~12–15% (30% gross FCF margin minus 18% mature SBC %), which would imply a much higher required CAGR. Under that harsher framing, the market's implied growth at $121 is more reasonable. This is the core reason conviction is not higher than 3.5.

---

## METHOD 2 — FORWARD DCF (3 SCENARIOS)

**Scenario assumptions:**

| Assumption | Bull | Base | Bear |
|---|---|---|---|
| Yr 1-2 Rev growth | 27% / 25% | 27% / 25% | 24% / 20% |
| Yr 3-5 Rev CAGR | 22 / 18 / 15 | 21 / 17 / 14 | 16 / 12 / 10 |
| Yr 6-7 Rev CAGR | 12% / 10% | 11% / 9% | 8% / 6% |
| Terminal FCF margin | 34% | 30% | 27% |
| Terminal growth | 3.5% | 3.0% | 2.5% |
| WACC | 9.5% | 10.0% | 11.0% |

**Base case revenue walk:**

| Year | Revenue ($M) | YoY | FCF Margin | FCF ($M) | PV ($M) |
|---|---|---|---|---|---|
| FY27 | 5,949 | 27.0% | 23.0% | 1,368 | 1,244 |
| FY28 | 7,436 | 25.0% | 25.0% | 1,859 | 1,536 |
| FY29 | 8,997 | 21.0% | 27.0% | 2,429 | 1,825 |
| FY30 | 10,527 | 17.0% | 28.0% | 2,948 | 2,013 |
| FY31 | 12,001 | 14.0% | 29.0% | 3,480 | 2,161 |
| FY32 | 13,321 | 11.0% | 30.0% | 3,996 | 2,256 |
| FY33 | 14,519 | 9.0% | 30.0% | 4,356 | 2,235 |
| **Terminal** | | | | | **32,890** |

**Valuation summary (reported-FCF basis):**

| | Bear | Base | Bull |
|---|---|---|---|
| PV of explicit FCF ($M) | 9,935 | 13,270 | 14,958 |
| PV of terminal value ($M) | 17,882 | 32,890 | 47,124 |
| Enterprise value ($M) | 27,817 | 46,160 | 62,083 |
| + Net cash ($M) | 2,505 | 2,505 | 2,505 |
| Equity value ($M) | 30,322 | 48,665 | 64,587 |
| Fully diluted shares (M) | 376 | 376 | 376 |
| **Per-share value** | **$80.64** | **$129.43** | **$171.78** |
| Upside / (downside) | (33.4%) | +6.9% | +41.8% |
| TV % of total | 64% | **71% ⚠️** | 76% ⚠️ |
| Implied EV/NTM multiple | 4.7x | 7.8x | 10.5x |

**⚠️ Terminal value flag:** Base case TV concentration is 71%, above the 70% threshold. Bull case is 76%. The valuation is dominated by long-term assumptions. This is typical for a 25%-grower with a long runway but should lower confidence — if the terminal FCF margin is one turn lower (27% instead of 30%), the base case falls by ~$18.

**Round-trip check:** Base case implies EV/NTM Revenue of **7.8x** — almost exactly where the stock currently trades. This is a sobering result: the base case DCF implies a fair value only ~7% above spot. The forward DCF does not independently support a strong long thesis at reported-FCF margins; it says the stock is roughly fair.

**SBC-adjusted sensitivity (ex-SBC base case):**
With SBC declining from 34% → 18% of revenue over 7 years and FCF margins recalculated as margin-minus-SBC%, the base-case per-share value collapses to **$45.67** (−62% from spot). This is the brutal honest view: on pure cash economics, SNOW is expensive at $121. The gap between the two base cases ($129 reported vs. $46 ex-SBC) quantifies the SBC distortion — roughly $84/share of the reported valuation comes from treating SBC as a non-cash charge that shareholders tolerate indefinitely. Reality lies somewhere in between and depends on whether SNOW can (a) reduce SBC % of revenue meaningfully over time and (b) continue buying back stock to offset dilution.

---

## METHOD 3 — TRADING COMPS

**Peer set (from sector handoff, early April 2026):**

| Ticker | NTM Growth | EV/NTM Rev | FCF Margin | Rule of 40 | Growth-Adj |
|---|---|---|---|---|---|
| PLTR | 70% | 35.0x | 53% | 127 | 0.50 |
| NOW | 21% | 10.7x | 33% | 55 | 0.51 |
| DDOG | 29% | 9.8x | 27% | 55 | 0.34 |
| **SNOW (handoff ref)** | **30%** | **8.3x** | **23%** | **53** | **0.28** |
| **SNOW (current)** | **27%** | **7.26x** | **23%** | **53** | **0.27** |
| VEEV | 16% | 7.2x | 35% | 51 | 0.45 |
| MDB | 27% | 6.1x | 19% | 42 | 0.23 |
| CRM | 12% | 5.3x | 35% | 45 | 0.44 |
| ESTC | 18% | 2.8x | 12% | 30 | 0.16 |

**Positioning:**
- **Direct peers (DDOG, NOW, MDB) median EV/NTM:** 9.8x
- **SNOW positioning:** 27% growth is in-line with DDOG (29%) and above NOW (21%). RPO +42% is the best forward visibility in the group. Rule of 40 of 53 is middle-of-pack. The critical negative: SBC at 36% of revenue is the worst in the peer set and meaningfully exceeds DDOG (24%) or NOW (14%).
- **Fair multiple judgment:** SNOW should trade roughly in-line with DDOG (9.8x) minus a 5-10% SBC discount = ~8.5–9.0x. Current 7.26x is a discount to fair.

**Fair value ranges:**

| Mult | Implied EV | Equity | Per share | vs. Spot |
|---|---|---|---|---|
| 7.5x (bear) | $44.5B | $47.0B | **$125** | +3.2% |
| **9.0x (base)** | **$53.4B** | **$55.9B** | **$149** | **+22.7%** |
| 11.0x (bull) | $65.2B | $67.7B | $180 | +48.7% |

Trading comps are the highest-confidence method for this name — the peer set is well-defined, multiples have been stress-tested through the Q1 2026 sector drawdown, and SNOW's growth profile fits cleanly within the data platform cluster. This is where the undervaluation signal is cleanest: SNOW has slipped below the peer median for no reason specific to SNOW's fundamentals.

---

## METHOD 4 — PRECEDENT M&A COMPS

**Reference transactions (from sector handoff):**
- Splunk / Cisco: ~$28B at ~7x ARR (2023, mature 15% grower)
- Confluent / IBM: $11B at ~11x ARR (Dec 2025, 25% grower)
- Informatica / Salesforce: $8B at ~8x NTM revenue
- Sector rule: 10-15x ARR for high growth (>30%), 6-10x ARR for 15-30% growers

**SNOW ARR (estimated):** ~$4.74B (Q4 FY26 product revenue annualized × seasonal adjustment)

| Scenario | Mult | Gross EV | Takeout/share | After 25% premium discount → floor |
|---|---|---|---|---|
| Low (mature precedent) | 8.0x | $37.9B | $108 | $82 |
| Base | 10.0x | $47.4B | $133 | **$101** |
| High (growth premium) | 12.0x | $56.9B | $158 | $120 |

**Reality check:** A $45B+ acquisition is near the upper limit of what any strategic acquirer can absorb. Plausible buyers: Microsoft (antitrust risk with Fabric), Alphabet (no precedent for deals this size), Oracle (possible but unlikely), IBM (already digesting Confluent). No plausible PE scenario. The probability of a takeout inside 24 months is low; this method serves as a floor reference only and is assigned 10% weight. **Base case M&A floor: ~$101**, roughly 17% below spot — the "no-upside" downside anchor.

---

## METHOD 5 — SUM-OF-PARTS

SNOW does not disclose segment-level economics; SoP is approximate.

| Segment | NTM Revenue ($M) | Multiple | EV ($M) |
|---|---|---|---|
| Core data cloud | 5,143 | 8.5x | 43,717 |
| Cortex AI (hyper-growth) | 447 | 20.0x | 8,945 |
| Other / acquired (Crunchy, Observe, TensorStax) | 174 | 6.0x | 1,047 |
| **Total EV** | | | **53,708** |
| + Net cash | | | 2,505 |
| Equity value | | | 56,213 |
| **Per share** | | | **$149.50** (+23.4%) |

This matches the trading comps base case almost exactly ($149 vs. $149), which isn't coincidence — the bulk of SNOW's value is in the core data platform, and segmenting out Cortex AI doesn't materially change the aggregate since Cortex is already implicitly priced into the core multiple. SoP offers limited independent information for this name; weight: 10%.

---

## METHOD 6 — PE / LBO FLOOR

**Framing:** Growth equity, no leverage (SNOW is too big and still near break-even on GAAP to support a traditional LBO). Target IRR: 20% over 5 years.

**Assumptions:**
- PE buyer assumed to aggressively cut SBC and restructure cost base
- Revenue: 27% → 22% → 18% → 14% → 11% growth path
- FCF margin: 25% → 30% over 5 years
- Exit multiple: 6.0x NTM revenue (conservative exit for a maturing grower)

**5-year projection:**

| Year | Revenue ($M) | FCF ($M) |
|---|---|---|
| Y1 | 5,949 | 1,487 |
| Y2 | 7,257 | 1,959 |
| Y3 | 8,564 | 2,398 |
| Y4 | 9,763 | 2,831 |
| Y5 | 10,836 | 3,251 |
| Cum FCF | | 11,927 |

Exit equity = Year-5 revenue × 6x + cum FCF = $65B + $12B = **$77B**

Max entry equity for 20% IRR = $77B / (1.2)⁵ = **$30.9B**
**Max entry price = $82.24** (−32% from spot)

**Reality check:** A >$40B LBO is essentially impossible for current PE. The method serves strictly as a downside reference. What it tells us: if growth decelerates faster than the base case and multiple compression occurs, the stock could rationally see $80 before a financial buyer would find the risk/reward attractive. This broadly aligns with the forward DCF bear case of $81. Weight: 5%.

---

## TRIANGULATION & PRICE TARGET

| Method | Bear | Base | Bull | Weight | Confidence |
|---|---|---|---|---|---|
| Reverse DCF | — | signals undervalued (reported FCF) / signals overvalued (ex-SBC) | — | — | — |
| Forward DCF (reported FCF) | $81 | $129 | $172 | 35% | M |
| Trading Comps | $125 | $149 | $180 | 40% | H |
| M&A Comps | — | $101 | — | 10% | L |
| Sum-of-Parts | — | $150 | — | 10% | L |
| LBO Floor | $82 | — | — | 5% | L |

**Triangulated targets:**
- **Bear case: $103** (−15.0%) — anchored to forward DCF bear + LBO floor + below-peer trading comp
- **Base case: $137** (+12.8%) — center of trading comps/SoP ($149) and forward DCF ($129), dragged down by M&A comp reality check
- **Bull case: $176** (+45.5%) — converged forward DCF bull and trading comps bull

---

## CONVICTION SCORE: 3.5 / 5

**Rationale:** Four of five price-producing methods point to undervaluation, with trading comps (highest-confidence) showing the clearest signal at ~22% upside to base. The reverse DCF confirms the market is pricing in unrealistic deceleration on a reported-FCF basis. However, three factors prevent a 4+ score:

1. **SBC reality.** On a true cash-economic basis (FCF ex-SBC), SNOW generated −$479M in FY26. The 34% SBC load is the worst in the sector and the dual-track valuation gap is ~$84/share. If SBC does not decline materially, the reported-FCF valuation is overstated.
2. **Terminal value concentration.** Base case forward DCF has 71% of value in the terminal (above the 70% flag); the valuation is dominated by 2030+ assumptions, not near-term fundamentals.
3. **Databricks IPO overhang.** A 2026 Databricks S-1 is explicitly flagged by the sector handoff as a binary event that could reset public comps in either direction. Until that event clears, any multiple-based signal is provisional.

The base case upside of +13% does not meet the ≥30% threshold for concentrated long candidacy. This is a moderate long at best — and a good put-selling candidate.

---

## DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━
TICKER: SNOW
COMPANY: Snowflake Inc.
SECTOR: Data Analytics / AI Platforms
VALUATION DATE: 2026-04-12

PRICE TARGET: $137 base (range: $103 bear — $176 bull)
CURRENT PRICE: $121.11
UPSIDE TO BASE: +12.8%
CONVICTION: 3.5 / 5

WHEEL STRATEGY IMPLICATIONS:

- SELL PUTS: YES
  - Rationale: Stock trades ~12% below base-case fair value of $137 and
    ~7.3x NTM revenue vs. 8.5-9x peer-calibrated fair multiple. Reverse DCF
    confirms the market is pricing in unrealistic deceleration on reported
    FCF. Put-selling at or below current price offers favorable risk/reward
    so long as SBC-adjusted view is not the correct lens.
  - Suggested strike zone: $100 – $115 (at or below current; above bear PT $103)
  - Preferred strikes: $105 – $110 (10-13% below spot; lands near M&A floor
    and LBO floor for downside protection)
  - Avoid puts above: $125 (approaches base case — negative expected value)

- COVERED CALLS (if assigned): CONDITIONAL
  - Cost basis assumption: put strike (e.g., $105-$110)
  - Minimum call strike: cost basis (cc_min_strike_pct = 1.0)
  - Suggested call strike zone: $130 – $150 (between base case PT and
    halfway to bull case)
  - Do NOT sell calls above: $165 (approaching bull case $176 — let it run)

- CONCENTRATED LONG CANDIDATE: NO
  - Rationale: Upside to base (+13%) fails the ≥30% threshold; conviction
    3.5 fails the ≥4 threshold. SBC reality + Databricks IPO overhang +
    71% TV concentration prevent higher conviction. Standard sized long
    or put-selling only.
  - Position sizing note: Normal sizing. Do not oversize ahead of
    Databricks S-1 (unknown date, 2026).

KEY DATES TO AVOID:
- April 27, 2026: Class-action lead plaintiff deadline (headline risk only;
  subject matter not yet disclosed in retrieved sources)
- ~May 27, 2026: Q1 FY27 earnings report (binary)
- 2026 (date TBD): Databricks S-1 filing — binary multiple-reset event
- October 1, 2027: $1.15B convert due; in-the-money at $157.50 — refinance
  or share-settle decision

SECTOR CONTEXT:
- Sector score: 20/25 (Tier 1 PASS)
- Relative ranking in sector: tied for #1 (with PLTR, DDOG, NOW, VEEV, ZETA)
- Sector-level risk flag: (1) AI monetization skepticism compressing the
  whole cluster; (2) Databricks IPO expected 2026 will reset benchmarks;
  (3) Sector-wide SBC dilution problem — SNOW is the worst offender
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## KEY ANALYTICAL TENSIONS TO MONITOR

1. **Cortex AI as % of total credits consumed.** If this crosses 5% in any reported quarter, the AI monetization thesis is confirmed and the multiple should re-rate toward DDOG/NOW (9.8-10.7x). Sector R3 flagged this as the key operational variable.

2. **FY27 adjusted FCF margin vs. 23% guide.** The guide implies ~250bps deceleration vs. FY26 actual 25.5%. If Q1 FY27 prints in line or better, it validates the margin trajectory in the base case. If it misses, the forward DCF bear case becomes the center.

3. **Databricks S-1 valuation.** If Databricks files at an implied EV/Revenue multiple above SNOW's current 7.3x while growing 55%, SNOW's multiple should re-rate upward. If Databricks files below SNOW, the sector handoff's "+1.2x Databricks" SNOW multiple scenario produces materially lower price targets.

4. **SBC trajectory.** The single most important multi-year variable. FY26 at 34%; FY27 guide implicitly has SBC declining to ~31-32% of revenue (back-solved from 12.5% non-GAAP op margin vs. -25-28% GAAP). If SBC continues to decline 200-300bps/year, the ex-SBC view becomes less punitive over time and the reported-FCF valuation becomes the right anchor.
