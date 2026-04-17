# V2 STOCK VALUATION — MICRON TECHNOLOGY (MU)

**Ticker:** MU (NASDAQ)
**Company:** Micron Technology, Inc.
**Sector:** Semiconductor Memory (DRAM, NAND, HBM)
**Current Price:** $366.24
**Analysis Date:** April 4, 2026
**Sector Score:** 24/25 — Highest in universe

---

## ━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━

| | Value |
|---|---|
| **TICKER** | MU |
| **CURRENT PRICE** | $366.24 |
| **ANALYSIS DATE** | April 4, 2026 |

### METHOD RESULTS

| Method | Bear | Base | Bull | Weight | Confidence |
|--------|------|------|------|--------|------------|
| Reverse DCF | — | 21.3% implied CAGR (reasonable) | — | — | H |
| Forward DCF | $119 | $231 | $368 | 40% | M-H |
| Trading Comps | — | $400 | — | 30% | H |
| M&A Comps | — | $104 | — | 5% | L |
| Sum-of-Parts | — | $345 | — | 15% | M |
| PE/LBO Floor | $138 | — | — | 10% | L |

### TRIANGULATED PRICE TARGET

| Scenario | Price | vs. Current |
|----------|-------|-------------|
| **Bear case** | **$119** | **-67.6%** |
| **Base case** | **$283** | **-22.6%** |
| **Bull case** | **$368** | **+0.6%** |

### CONVICTION SCORE: 3.5 / 5

**Rationale:** Moderate-to-high conviction. Methods converge around fair value being below the current price when properly accounting for cycle risk. On near-term earnings (7x FY26 P/E), MU appears deeply cheap. On through-cycle DCF (which must model a 30-40% revenue decline), the current price embeds near-peak optimism. The stock is a HIGH-QUALITY business at a price that is FAIR on near-term metrics but EXPENSIVE on through-cycle fundamentals. Cycle position (~Month 18 of historical 18-24 month upcycles) is the dominant risk factor.

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency
- ✅ **DCF:** 12 quarters of revenue + FCF history. Guidance through Q3 FY2026. Consensus ~$105-115B FY2026 revenue. Share count and net cash confirmed.
- ⚠️ FY2027+ revenue consensus is being actively revised post-Q2 beat. Only Erste provides FY2027 EPS (~$42). Will use cycle-adjusted estimates.
- ✅ **Trading Comps:** Full peer set from sector handoff (SK Hynix, Samsung, SanDisk, Kioxia, Nanya, Rambus, ALAB).
- ⚠️ **M&A Comps:** Memory M&A is rare at Micron's scale (~$420B market cap). Low confidence.
- ✅ **Sum-of-Parts:** 4-BU segment breakdown with individual margins.
- ✅ **PE/LBO Floor:** FCF, EBITDA, and EV available. Company is too large for realistic LBO.

### Check 2: Fiscal Year Alignment
- ✅ Micron FY ends last Thursday of August (~Aug 28). FY2026 = Sep 2025 – Aug 2026 (53-week year).
- ⚠️ Peers: SK Hynix (Dec FY), Samsung (Dec FY), Kioxia (Mar 31 FY), SanDisk (varies). All peer comparisons use NTM estimates.

### Check 3: Share Count Reconciliation
- Basic shares: 1,126M
- GAAP diluted: 1,142M
- Non-GAAP diluted: **1,149M** ← used for all per-share calculations
- No convertible notes outstanding
- Annual dilution: ~1.3% (CHIPS Act limits buybacks to $350M/quarter)

### Check 4: SBC Materiality Assessment
- SBC ~$1.2B annualized = **1.1% of FY2026 revenue**
- ✅ WELL BELOW 15% threshold. No dual-track required.
- Memory IDMs pay primarily in cash, not stock. Structurally different from SaaS.

---

## MARKET DATA

| Metric | Value |
|--------|-------|
| Market Cap | $420.8B |
| Net Cash | +$6.5B (record) |
| Enterprise Value | $414.3B |
| TTM Revenue | $58.1B |
| FY2026 Revenue Estimate | $108.0B |
| EV/NTM Revenue | 3.84x |
| EV/TTM Revenue | 7.13x |
| Forward P/E (FY2026) | ~7.0x |

---

## METHOD 1: REVERSE DCF

**Purpose:** What growth rate is the market pricing in?

### Setup
- Current EV: $414.3B
- Base revenue (FY2025): $37.4B
- Assumptions: 10-year projection, FCF margin ramps linearly from 15% to terminal, perpetuity growth 3%

### Implied Revenue CAGR Sensitivity

| WACC \ Terminal FCF Margin | 15% | 20% | 25% | 30% |
|----------------------------|-----|-----|-----|-----|
| 9% | 22.3% | 18.8% | 16.1% | 13.9% |
| **10%** | 24.9% | **21.3%** | 18.6% | 16.4% |
| 11% | 27.4% | 23.7% | 20.9% | 18.7% |
| 12% | 29.7% | 26.0% | 23.1% | 20.8% |

### Base Case: Implied CAGR = 21.3% (WACC 10%, Terminal FCF 20%)

**Comparisons:**
- FY2025 actual revenue growth: +48.9%
- FY2026 estimated revenue growth: +189%
- Memory market long-term CAGR: ~10% (Yole 2024-2030)
- HBM sub-segment CAGR: ~33% (2024-2030)
- Micron mid-cycle blended estimate: ~15-20%

### Gap Analysis

The market implies a 21.3% 10-year CAGR vs. a blended mid-cycle estimate of 15-20%. This is **reasonable but not conservative** — it requires Micron to structurally outgrow the total memory market by ~2x for a decade, which is achievable only if HBM mix shift and data center content growth persist. The implied CAGR is NOT pricing in a perpetual supercycle (that would require >30%), but it IS pricing in Micron permanently capturing a premium growth profile via HBM.

**Critical caveat:** The reverse DCF smooths through cycles. Current revenue ($108B FY2026) is near-peak. Revenue could decline 30-40% in a downcycle before resuming growth. The path will be highly volatile even if the endpoint is correct.

---

## METHOD 2: FORWARD DCF (3-SCENARIO)

**Critical context:** Memory semiconductors are deeply cyclical. All scenarios MUST model a downcycle. The question is when and how deep, not whether. Current cycle position: ~Month 18 (historical peak at Month 18-20).

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|------------|------|------|------|
| Yr 1 (FY26) Revenue | $108B | $108B | $100B |
| Yr 2 (FY27) Revenue | $130B (+20%) | $115B (+6%) | $75B (-25%) |
| Yr 3 (FY28) Revenue | $110B (-15%) | $80B (-30%) | $50B (-33%) |
| Yr 4 (FY29) Revenue | $95B (-14%) | $65B (-19%) | $45B (-10%) |
| Yr 5-7 Revenue | Recovery to $145B | Recovery to $115B | Recovery to $85B |
| Terminal FCF Margin | 28% | 23% | 18% |
| Terminal Growth | 3% | 3% | 3% |
| WACC | 10% | 10% | 10% |

**Bull case — what must go right:** AI capex continues 30%+ CAGR through 2028. HBM4/HBM4E demand exceeds capacity additions. Cycle correction is mild (20% revenue decline) and brief (1 year). MU maintains 24%+ HBM share.

**Base case — most likely path:** Cycle peaks FY2027. Meaningful correction FY2028-29 (30% revenue decline, comparable to 2019). Recovery driven by next-gen HBM and data center refresh. Capex remains elevated ($35B+ FY2027) suppressing FCF during correction.

**Bear case — what could go wrong:** AI capex growth decelerates sharply (hyperscaler budget cuts). Google TurboQuant or similar compression technologies materially reduce memory requirements. Classic memory bust with 50% peak-to-trough revenue decline (comparable to 2023). Heavy capex commitments create FCF burn during downturn.

### Revenue Projection — Base Case

| Year | Revenue ($M) | YoY Growth | FCF Margin | FCF ($M) | PV of FCF ($M) |
|------|-------------|------------|------------|----------|----------------|
| 1 (FY26) | 108,003 | +189% | 10.0% | 10,800 | 9,818 |
| 2 (FY27) | 115,000 | +6.5% | 5.0% | 5,750 | 4,752 |
| 3 (FY28) | 80,000 | -30.4% | 8.0% | 6,400 | 4,808 |
| 4 (FY29) | 65,000 | -18.8% | 12.0% | 7,800 | 5,328 |
| 5 (FY30) | 80,000 | +23.1% | 18.0% | 14,400 | 8,941 |
| 6 (FY31) | 100,000 | +25.0% | 22.0% | 22,000 | 12,418 |
| 7 (FY32) | 115,000 | +15.0% | 23.0% | 26,450 | 13,573 |

### Valuation Summary

| | Bull | Base | Bear |
|---|------|------|------|
| PV of Cash Flows | $110,133M | $59,639M | $14,195M |
| PV of Terminal Value | $306,561M | $199,717M | $115,527M |
| Enterprise Value | $416,694M | $259,357M | $129,722M |
| Net Cash | $6,485M | $6,485M | $6,485M |
| Equity Value | $423,179M | $265,842M | $136,207M |
| Fully Diluted Shares | 1,149M | 1,149M | 1,149M |
| **Per Share Value** | **$368** | **$231** | **$119** |
| **Upside/(Downside)** | **+0.6%** | **-36.8%** | **-67.6%** |
| TV as % of Total | 74% ⚠️ | 77% ⚠️ | 89% ⚠️ |

⚠️ **Terminal value exceeds 70% of total value in ALL scenarios.** This is inherent to cyclical businesses where near-term cash flows are volatile and even negative in downturns. The valuation is heavily dependent on long-term assumptions about memory market growth and Micron's competitive position.

### FCF Margin Assumptions — Why They Matter

FCF margins for memory IDMs are structurally suppressed by massive capex. Micron's FY2026 capex is >$25B (~23% of revenue), and FY2027 will "step up meaningfully" with construction capex increasing >$10B YoY. Even at 81% gross margins, FCF margin is only ~10-12% because capex is consuming the cash. As fabs complete (FY2029+), FCF margins should expand materially — this is the key driver of the terminal value.

### Round-Trip Check

Base case DCF implies EV of $259B on NTM revenue of $108B = 2.4x EV/NTM Revenue. This is below the current 3.84x and below SK Hynix's 5.6x. The DCF is producing a CONSERVATIVE estimate because it models a severe cycle correction. On a through-cycle basis, 2.4x is a reasonable trough-to-mid-cycle multiple for a memory IDM.

---

## METHOD 3: TRADING COMPS

### Peer Set

| Company | EV/NTM Rev | Growth | GM | EBITDA M | Growth-Adj | HBM |
|---------|:---:|:---:|:---:|:---:|:---:|:---:|
| SK Hynix | 5.6x | 66% | 60% | 63% | 0.085 | ✅ |
| Samsung (DS) | 3.3x | 24% | 39% | 25% | 0.137 | ✅ |
| SanDisk | 4.0x | 61% | 51% | 30% | 0.066 | ❌ |
| Kioxia | 3.2x | 30% | 26% | 44% | 0.107 | ❌ |
| Nanya | 2.8x | 50% | 49% | 49% | 0.056 | ❌ |
| Rambus | 10.0x | 18% | 80% | 43% | 0.556 | ❌ |
| Astera Labs | 13.6x | 92% | 76% | 40% | 0.148 | ❌ |
| **Micron** | **3.84x** | **196%** | **74%** | **64%** | **0.020** | **✅** |

### Positioning

- Growth rank: **#1** of 8 (196% vs. next-best SK Hynix at 66%)
- Gross margin rank: **#1** among IDMs (74.4%, ahead of SK Hynix at 60%)
- Growth-adjusted multiple: **Cheapest** in entire universe (0.020 vs. median ~0.09)
- Current multiple vs. IDM peer median (3.3x): **+16% premium**
- Current multiple vs. HBM-peer average (4.4x): **-13% discount**

### Fair Value Estimate

Micron deserves a **premium** to IDM peer median on: (1) highest growth in universe, (2) highest gross margins among IDMs, (3) only US-listed HBM producer, (4) CHIPS Act strategic positioning. The premium is partially offset by cycle risk (near peak) and the fact that current growth rates are unsustainable.

- Fair EV/NTM Revenue: **4.2x** (premium to 3.3x IDM median, discount to 5.6x SK Hynix)
- Implied EV: $453.6B → Equity: $460.1B → **Per share: $400** (+9.3%)

### P/E Cross-Check

| Metric | Value |
|--------|-------|
| FY2026 EPS estimate | ~$52 |
| Current P/E (FY2026) | 7.0x |
| At 10x peak P/E | $520 |
| At 12x trough EPS ($8) | $96 (downside floor) |

The 7x P/E on peak earnings is consistent with historical memory valuation discipline — investors correctly refuse to pay high multiples on earnings they know will decline. This is NOT a signal of undervaluation; it's a signal that the market expects earnings normalization.

---

## METHOD 4: PRECEDENT M&A COMPS

### Comparable Transactions

| Date | Target | Acquirer | EV ($B) | EV/Rev | Notes |
|------|--------|----------|---------|--------|-------|
| 2012 | Elpida Memory | Micron | ~$2.5 | 0.4x | Bankruptcy |
| 2016 | SanDisk | WDC | $19.0 | 3.1x | Peak-cycle |
| 2017 | Toshiba Memory | Bain et al. | $18.0 | 1.8x | Distressed |
| 2024 | PSMC P5 fab | Micron | $1.8 | N/A | Asset deal |
| 2025 | Nanya stake (11%) | Consortium | $2.5 | ~2.0x | Minority |

### Takeout Valuation

- Normalized mid-cycle revenue: ~$60B
- M&A multiple range: 2.0-3.0x normalized revenue
- Implied EV range: $120-180B
- After 25% control premium discount: $90-135B
- Implied per-share range: **$84-$123**

**Probability assessment: UNREALISTIC.** At ~$420B market cap, no acquirer can afford Micron. Samsung (~$840B consolidated) and SK Hynix (~$413B) are the only conceivable strategic acquirers, but antitrust barriers are prohibitive given the DRAM triopoly. This method is theoretical only. **Weight: 5% (low confidence).**

---

## METHOD 5: SUM-OF-PARTS

### Segment Breakdown

| Segment | FY26E Rev ($B) | GM | OM | Comparable | Multiple | Implied EV ($B) |
|---------|:-:|:-:|:-:|------------|:-:|:-:|
| **CMBU** (Cloud/HBM) | $32 | 74% | 66% | SK Hynix HBM/Server | 5.0-7.0x | $160-224 |
| **CDBU** (DC NAND) | $20 | 74% | 67% | SanDisk | 3.5-5.0x | $70-100 |
| **MCBU** (Mobile/Client) | $36 | 79% | 76% | Commodity DRAM mix | 2.5-3.5x | $90-126 |
| **AEBU** (Auto/Embedded) | $12 | 68% | 62% | Auto semi peer | 3.0-5.0x | $36-60 |
| **TOTAL** | **$100** | | | | | **$356-510** |

### SoP Valuation

| Component | Value |
|-----------|-------|
| SoP EV (midpoint) | $433B |
| Integration discount (10%) | -$43B |
| Adjusted EV | $390B |
| Net Cash | +$6.5B |
| Equity Value | $396B |
| **Per Share** | **$345** (-5.9%) |

### Hidden Value Flag

The CMBU (Cloud/HBM) segment alone, at SK Hynix-like multiples (6-8x), could be worth $192-224B — more than half the current EV. If the market ever values Micron's HBM business separately (via spin-off speculation or pure-play re-rating), there is significant unlocked value. However, this is speculative and assumes peak-cycle segment revenues are sustainable.

---

## METHOD 6: PE/LBO FLOOR

**Reality check:** At ~$420B EV, Micron is far too large for any realistic LBO. The largest-ever PE buyout was Dell at ~$67B (2013). This is purely theoretical.

### Growth Equity Model (No Leverage, 20% IRR Target)

| Year | Revenue ($B) | FCF ($B) | Cumulative FCF ($B) |
|------|:---:|:---:|:---:|
| 1 (FY26) | $108 | $10.8 | $10.8 |
| 2 (FY27) | $115 | $5.8 | $16.6 |
| 3 (FY28) | $80 | $6.4 | $23.0 |
| 4 (FY29) | $65 | $7.8 | $30.8 |
| 5 (FY30) | $80 | $14.4 | $45.2 |

**Exit:** 3.5x NTM Revenue ($95B) = $332B EV

### Floor Prices

| IRR Target | Max Entry EV | Max Entry Per Share | vs. Current |
|:---:|:---:|:---:|:---:|
| 20% | $152B | **$138** | -62% |
| 25% | $123B | **$113** | -69% |

The PE floor suggests that on a through-cycle basis with cycle-average cash flows, a financial buyer would only pay $113-138 per share. This is consistent with the bear-case DCF of $119 and historical trough valuations.

---

## WEIGHTING RATIONALE

| Method | Weight | Rationale |
|--------|--------|-----------|
| Forward DCF | **40%** | Highest weight — properly models cycle risk, captures both near-term peak and multi-year correction. But high TV% reduces precision. |
| Trading Comps | **30%** | Strong peer set with good comparability. But current comps reflect peak-cycle multiples that will compress in a downturn. |
| Sum-of-Parts | **15%** | Useful for identifying hidden segment value (CMBU/HBM), but segment revenues at peak are not representative of normalized value. |
| PE/LBO Floor | **10%** | Theoretical — Micron is untakeable. But provides useful downside reference consistent with trough analysis. |
| M&A Comps | **5%** | Minimal — no relevant precedents at this scale. Memory M&A historically occurs at trough, not peak. |

---

## TROUGH ANALYSIS

Essential for options positioning. Historical memory troughs:

| Cycle | Peak-to-Trough Revenue | Trough EPS | Stock Decline |
|-------|:---:|:---:|:---:|
| 2008-09 (GFC) | -40% | Deeply negative | -80%+ |
| 2019 (Trade War) | -36% | ~$0 | -50% |
| 2022-23 (Inventory) | -50% | -$5.34 | -55% (to ~$49) |

**Current cycle potential trough:**
- Book value per share: $63
- Historical trough P/B: 0.8-1.2x → implied trough price: $50-76
- Trough EPS (FY2023 analog): -$5 to +$8
- At 12x trough EPS ($8): $96

---

## ━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━

| | |
|---|---|
| **TICKER** | MU |
| **COMPANY** | Micron Technology, Inc. |
| **SECTOR** | Semiconductor Memory (DRAM, NAND, HBM) |
| **VALUATION DATE** | April 4, 2026 |

| | |
|---|---|
| **PRICE TARGET** | $283 base case (range: $119 bear — $368 bull) |
| **CURRENT PRICE** | $366.24 |
| **UPSIDE TO BASE** | -22.6% |
| **CONVICTION** | 3.5/5 |

### WHEEL STRATEGY IMPLICATIONS

**SELL PUTS: CONDITIONAL — NOT at current levels**

Rationale: Stock is 29% ABOVE base case price target. The current price embeds peak-cycle earnings at near-peak multiples. Selling puts here means being willing to own the stock through a potential 30-50% downcycle, which would compress both revenue AND multiples. The risk/reward is unfavorable for put-selling at current levels.

Suggested entry zone for puts: **$180-$230** (at or below base case DCF value)
- $230 = near base case DCF, provides ~35% downside buffer from current
- $180 = between base and bear DCF, provides meaningful cycle buffer
- Strike zone requires a ~38-50% pullback from current — which IS plausible in a memory downcycle

Avoid puts above: $280 (above this, negative expected value on through-cycle basis)

**Conditional trigger:** If MU pulls back to $250-280 range (trough EV/NTM Rev ~2.5x on normalized estimates), begin selective put-selling with 90-120 DTE targeting the $180-230 strike zone.

**COVERED CALLS (if assigned): YES**
- Cost basis assumption: $200 (put strike)
- Minimum call strike: $200 (1.0x cost basis per cc_min_strike_pct rule)
- Suggested call strike zone: $280-$350 (between cost basis and base PT)
- Do NOT sell calls above $350 (approaching bull case — let it run through recovery)

**CONCENTRATED LONG CANDIDATE: NO**
- Conviction: 3.5/5 (below ≥4 threshold)
- Upside to base: -22.6% (fails ≥30% upside threshold)
- The stock DOES NOT meet concentrated long criteria at current price
- Would become a candidate if price declined to ~$180 (conviction 4/5 at that level, upside >50% to base)

### KEY DATES TO AVOID

| Date | Event | Impact |
|------|-------|--------|
| **June 24, 2026** | Q3 FY2026 earnings | HIGH — validates $33.5B rev / 81% GM guide. Binary event. |
| **H2 2026** | SK Hynix ADR listing | MODERATE — creates direct HBM comparable; potential re-rating |
| **Late 2026** | Cycle peak window (Month 20-22) | HIGH — historical inflection point for memory pricing |
| **Q1 2027** | FY2027 guidance cycle | HIGH — first formal look at post-peak revenue trajectory |

### SECTOR CONTEXT

| | |
|---|---|
| Sector score | 24/25 |
| Relative ranking | #1 of 14 in memory universe |
| Sector-level risk | **CYCLE PEAK** — DRAM prices up 80-95% QoQ in Q1 2026, NAND doubled over 6 months. Historical memory cycles peak at Month 18-20; currently at Month ~18. Every indicator (pricing, margins, inventory, capex) is at or near historical extremes. |

### NET ASSESSMENT

Micron is the highest-quality company in the memory sector at the worst possible time to be buying cyclically. The business is extraordinary — only US-listed HBM producer, 74% gross margins, 196% revenue growth, supply sold out, CHIPS Act backing. But the stock at $366 prices in near-peak earnings with minimal margin of safety for the cyclical correction that has occurred in every memory cycle in history.

**The options wheel strategy should WAIT for a pullback.** The entry point for put-selling is $180-230, which requires either a market-wide correction or early signs of the memory cycle turning. If the cycle extends (bull case), MU will continue higher and the puts will never be assigned — that is an acceptable outcome. If the cycle turns (base/bear case), the stock will come to us at attractive levels.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
