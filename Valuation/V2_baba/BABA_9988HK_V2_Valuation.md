# V2 STOCK VALUATION — ALIBABA GROUP HOLDING LIMITED (9988.HK)

```
TICKER:         9988.HK / BABA (NYSE ADR, 1 ADS = 8 ordinary shares)
COMPANY:        Alibaba Group Holding Limited
CURRENT PRICE:  HK$118.5 per ordinary share (~US$121.9/ADS)
ANALYSIS DATE:  April 4, 2026
FISCAL YEAR:    Ends March 31 (FY2026 = April 2025 – March 2026)
CURRENCY:       RMB primary; HKD/USD = 7.78; CNY/USD = 7.25
SECTOR SCORE:   14/25 WATCH (China Internet / Tech Conglomerates)
```

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency

| Method | Required Data | Status | Flag |
|--------|--------------|--------|------|
| Forward DCF | ≥8Q revenue + FCF, guidance, consensus, shares, net debt | ✓ Available | 9M FY2026 FCF negative; Q4 FY2026 not yet reported |
| Reverse DCF | Current EV, revenue base, terminal assumptions | ✓ Available | |
| Trading Comps | Peer multiples from sector handoff | ✓ Available | 15-company peer set from R2 |
| M&A Comps | Recent transaction multiples | ⚠ Limited | Few large-cap Chinese internet M&A transactions; Alibaba too large for outright takeout |
| Sum-of-Parts | Segment revenue breakdown | ✓ Available | 4-segment reporting since Q1 FY2026 |
| PE/LBO Floor | FCF, debt capacity, EV | ⚠ Modified | Traditional LBO inapplicable at ~$300B EV; using growth equity / sovereign fund framing |

**Key data gaps:** FY2028 consensus estimates (paywalled), precise GMV figures (company stopped disclosing), Q3 FY2026 AIDC and Cloud segment EBITA individually (not disclosed), NTM non-GAAP EPS consensus.

### Check 2: Fiscal Year Alignment

Alibaba's fiscal year ends **March 31**. FY2026 = April 2025 – March 2026. Most Chinese internet peers report on calendar year (December 31). All peer comparisons are aligned to the nearest trailing-twelve-month basis. Consensus estimates are mapped to Alibaba's March-ending fiscal year.

### Check 3: Share Count Reconciliation

| Metric | Shares (Mn) | Source |
|--------|------------|--------|
| Basic ordinary shares (Dec 31, 2025) | ~18,570 | SEC 6-K filing |
| Diluted average ADS (Q3 FY2026) | ~2,365 | Derived from NI/EPS |
| Diluted ordinary equivalent | ~18,920 | 2,365 × 8 |
| If-converted (0.50% conv. notes, Jun 2031) | ~47.6M ADS | At $105.04/ADS |
| If-converted (zero coupon conv. notes, Sep 2032) | ~16.4M ADS | At $193.15/ADS |
| **Fully diluted ADS** | **~2,429M** | Used for all per-share calculations |
| **Fully diluted ordinary** | **~19,432M** | Used for HKD per-share calculations |

Note: The $193.15 convertible is well out of the money (current ADR ~$122). Capped call on 2032 notes raises effective conversion to $235.46/ADS. Including it in fully diluted count is conservative. Buyback pace has slowed significantly (~$250-400M/quarter in FY2026 vs $11.9B in FY2025).

### Check 4: SBC Materiality Assessment

| Period | SBC (RMB B) | Revenue (RMB B) | SBC % Rev |
|--------|------------|-----------------|-----------|
| Q1 FY2026 | ~3.2 | 247.7 | 1.3% |
| Q2 FY2026 | 3.3 | 247.8 | 1.3% |
| Q3 FY2026 | ~2.9 | 284.8 | 1.0% |
| TTM estimate | ~9.4 | ~1,017 | **0.9%** |

**SBC is 0.9% of TTM revenue — well below the 15% materiality threshold.** No SBC-adjusted dual-track FCF presentation is required. This is a structural advantage vs. US SaaS peers (CRWD 22.8%, NET 22.6%, ZS 27%) and reflects Chinese accounting practices where equity compensation is less prevalent.

---

## METHOD 1: REVERSE DCF

**Purpose:** What growth rate is the market implying at HK$118.5?

```
REVERSE DCF RESULTS
━━━━━━━━━━━━━━━━━━
Current EV: RMB 1,848B (US$255B)
Starting Revenue (FY2026E): RMB 1,060B
Assumptions: Terminal FCF margin ramping to 18% over 10 years,
             terminal perpetuity growth 3%, WACC 11%

Implied revenue CAGR: 2.9%
Current like-for-like revenue growth: ~9-10%
Consensus FY2027E revenue growth: 10.4%
Management long-term growth guidance: None formal; CEO targets $100B/yr cloud+AI revenue

GAP ANALYSIS:
Market implies 2.9% growth vs. ~10% actual/guided
→ Market is pricing in SIGNIFICANT DECELERATION below GDP growth
→ This is a potential UNDERVALUATION signal

Sensitivity:
| WACC \ Terminal FCF Margin | 15%  | 18%  | 20%  | 23%  |
|----------------------------|------|------|------|------|
| 10%                        | 3.0% | 0.9% | -0.2%| -1.8%|
| 11% (base)                 | 5.0% | 2.9% | 1.7% | 0.1% |
| 12%                        | 6.8% | 4.7% | 3.4% | 1.8% |
| 13%                        | 8.6% | 6.4% | 5.1% | 3.4% |
```

**Interpretation:** At every plausible WACC/margin combination, the market implies revenue growth well below Alibaba's current like-for-like rate of ~10% and well below consensus. The base case (11% WACC, 18% terminal FCF margin) implies only 2.9% CAGR — essentially sub-GDP stagnation. This suggests the market is either (a) heavily discounting geopolitical risk, (b) pricing in permanent margin destruction from the subsidy war and AI capex, or (c) genuinely underpricing the company.

The key question is whether the market's pessimism on margins is justified. With FCF currently negative and RMB 380B ($53B) in committed AI capex, margin recovery is not guaranteed. However, FY2023-FY2025 FCF margins of 16.5% → 13% → 7.5% show the company was a strong cash generator before the capex cycle began.

---

## METHOD 2: FORWARD DCF (3-SCENARIO)

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|------------|------|------|------|
| Yr 1-2 Rev CAGR | 12% | 10% | 5.5% |
| Yr 3-5 Rev CAGR | 10% → 9% | 8% → 6% | 4% → 3% |
| Yr 6-7 Rev CAGR | 8% → 7% | 6% → 5% | 3% |
| Terminal FCF Margin | 20% | 16% | 11% |
| Terminal Growth Rate | 3% | 3% | 2.5% |
| WACC | 10.5% | 11% | 12% |

**What must go right (Bull):** Cloud sustains 30%+ growth for 3+ years as AI adoption accelerates; quick commerce achieves profitability by FY2028; CMR stabilizes with Quanzhantui AI ad tool driving take rate recovery; food delivery regulatory ceasefire holds; AI capex generates measurable ROI; Ant Group IPO unlocks additional value.

**Most likely path (Base):** Cloud growth decelerates to 20% range by FY2028; quick commerce remains a drag for 2-3 more years; CMR grows low-single-digits; capex normalizes by FY2028-29 allowing FCF recovery; international commerce stagnates under tariff pressure.

**What could go wrong (Bear):** AI capex fails to generate returns (DeepSeek-style commoditization); food delivery war escalates further; CMR continues to decelerate toward flat/negative as Douyin captures share; US tariffs cripple AIDC; geopolitical event triggers ADR delisting; macro weakness extends; management investment discipline erodes.

### Base Case Revenue Projection

| Year | Revenue (RMB B) | YoY Growth | FCF Margin | FCF (RMB B) | Discount Factor | PV of FCF |
|------|----------------|------------|------------|-------------|-----------------|-----------|
| 1 (FY2027) | 1,170 | 10.4% | 1.0% | 11.7 | 0.901 | 10.5 |
| 2 (FY2028) | 1,276 | 9.0% | 4.0% | 51.0 | 0.812 | 41.4 |
| 3 (FY2029) | 1,378 | 8.0% | 7.0% | 96.4 | 0.731 | 70.5 |
| 4 (FY2030) | 1,474 | 7.0% | 10.0% | 147.4 | 0.659 | 97.1 |
| 5 (FY2031) | 1,563 | 6.0% | 12.0% | 187.5 | 0.593 | 111.3 |
| 6 (FY2032) | 1,656 | 6.0% | 14.0% | 231.9 | 0.535 | 124.0 |
| 7 (FY2033) | 1,739 | 5.0% | 16.0% | 278.2 | 0.482 | 134.0 |
| Terminal | | | | 3,582 | | 1,725.5 |

### Valuation Summary

| | Bull | Base | Bear |
|---|------|------|------|
| PV of Cash Flows (RMB B) | 880.7 | 588.8 | 249.4 |
| PV of Terminal Value (RMB B) | 2,792.3 | 1,725.5 | 748.6 |
| Enterprise Value (RMB B) | 3,673 | 2,314 | 998 |
| Net Cash (RMB B) | +297.5 | +297.5 | +297.5 |
| Equity Value (RMB B) | 3,971 | 2,612 | 1,296 |
| Fully Diluted Shares (Mn Ord.) | 19,432 | 19,432 | 19,432 |
| **Per Share Value (HKD)** | **HK$219** | **HK$144** | **HK$72** |
| Upside / (Downside) | +85% | +22% | -40% |
| TV as % of Total | 76% ⚠️ | 75% ⚠️ | 75% ⚠️ |

**⚠️ Terminal value exceeds 70% of total value in ALL scenarios.** This is characteristic of companies in investment cycles where near-term FCF is suppressed. The valuation is heavily dependent on the assumption that margins recover to historical levels after the capex cycle. If AI capex continues indefinitely at current rates, the bear case is more likely.

**Round-trip check:** Base case implies EV of RMB 2,314B on NTM revenue of RMB 1,170B = 1.98x EV/NTM Revenue. Current multiple is 1.58x. Implied premium of ~25% is reasonable for a company at an inflection point between investment trough and margin recovery. Passes the sanity check.

---

## METHOD 3: TRADING COMPS

### Peer Set

| Company | EV ($B) | Rev Growth | Op Margin | FCF Margin | Fwd P/E | EV/NTM Rev | Growth-Adj |
|---------|---------|------------|-----------|------------|---------|------------|------------|
| **ALIBABA** | **255** | **+10%** | **8.2%** | **~4%** | **17x** | **1.58x** | **0.158** |
| Tencent | 556 | +14% | 37% | 24% | 20x | 5.50x | 0.393 |
| PDD | 82 | +10% | 24% | 25% | 8x | 1.10x | 0.110 |
| JD.com | 21 | +13% | 0.7% | 0.5% | 10x | 0.11x | 0.008 |
| NetEase | 48 | +7% | 35% | 42% | 13x | 2.80x | 0.400 |
| Meituan | 45 | +8% | -6.9% | Neg. | N/M | 0.90x | 0.113 |
| Kuaishou | 17 | +12% | 14% | 13% | 11x | 1.00x | 0.083 |
| Trip.com | 23 | +21% | 27% | 27% | 13x | 2.70x | 0.129 |
| Bilibili | 8.1 | +13% | 8% | 20% | 18x | 2.00x | 0.154 |

### Target Company Positioning

- **Growth rank:** Mid-pack at ~10% like-for-like (4th of 9, behind Trip.com, Tencent, JD/Bilibili)
- **Profitability rank:** Below average at 8.2% adj. EBITA margin (6th of 9, compressed by investment)
- **Current multiple vs. peer median:** EV/NTM Rev of 1.58x vs. median 2.00x = **21% discount**
- **Growth-adjusted ratio:** 0.158 vs. peer median 0.129 = slight premium, justified by scale and net cash

### Fair Value Estimate

**Method:** Blend of EV/NTM Revenue and forward P/E, applying a modest re-rating from current levels

**EV/Revenue approach:**
- Fair EV/NTM Revenue: 1.7x (midpoint between current 1.58x and peer median 2.0x)
- Alibaba deserves a discount to Tencent (lower margins, more competitive risk) but premium to JD/Meituan (stronger cash position, cloud growth)
- NTM Revenue (FY2027E): RMB 1,170B
- Implied EV: RMB 1,989B → Equity: RMB 2,286B → **HK$126/share (+7%)**

**P/E cross-check:**
- FY2027E GAAP EPS: RMB 7.86/ord. share = HK$8.44/share
- Current FY2027 P/E: 14.0x
- Peer median fwd P/E: 13x (excl. Meituan/Baidu)
- At 13x: **HK$110** (-7%)
- At 15x (modest premium for cloud growth): **HK$127** (+7%)

**Comps base case: HK$126** (EV/Revenue method) with HK$110-127 range from P/E.

---

## METHOD 4: PRECEDENT M&A COMPS

### Comparable Transactions (Chinese Internet, 2020-2026)

| Date | Target | Acquirer | EV ($B) | EV/Rev | Target Growth |
|------|--------|----------|---------|--------|---------------|
| 2020 | 58.com | PE consortium | 8.7 | 2.5x | ~5% |
| 2023 | Hollysys | PE consortium | 1.8 | 2.5x | ~10% |
| 2024 est. | Ant Group (secondary) | Secondary mkt | 75 | ~3.5x | ~15% |
| 2025 | Ceconomy (by JD) | JD.com | 2.6 | 0.1x | ~2% |
| 2026 est. | ByteDance (pvt mkt) | Secondary mkt | 330 | ~3.5x | ~30% |

### Takeout Valuation

- Applicable multiple range: 1.5-2.5x TTM Revenue
- TTM Revenue: RMB 1,017B
- Implied EV range: RMB 1,526-2,542B
- After control premium discount (25%): Equity RMB 1,367-2,130B
- **Implied share price range: HK$76-118**
- Midpoint: **HK$97**

**Probability-weighted note:** An outright acquisition of Alibaba is effectively impossible at ~$300B market cap. The CCP would not approve a foreign takeover of a strategic platform, and no domestic buyer has the scale. This method serves only as a floor/ceiling reference. A partial breakup (spinning off cloud, AIDC, or Ant Group stake) is more plausible and could unlock value — the SoP analysis captures this better.

---

## METHOD 5: SUM-OF-PARTS

| Segment | FY2026E Rev (RMB B) | Growth | Comparable | Multiple | Implied EV (RMB B) |
|---------|---------------------|--------|------------|----------|---------------------|
| China E-commerce | 557 | +6% | JD.com/PDD blend | 1.5x | 836 |
| Cloud Intelligence | 148 | +36% | US cloud @ China discount | 4.0x | 592 |
| AIDC (International) | 142 | +4% | Cross-border e-comm | 0.8x | 114 |
| All Others | 213 | -10% | Cainiao/Freshippo/Health | 0.5x | 106 |
| Ant Group (33% stake) | — | — | Secondary market at ~$75B | — | 181 |
| **Total EV** | | | | | **1,829** |
| **+ Net Cash** | | | | | **+298** |
| **Equity Value** | | | | | **2,127** |

**Per Share: HK$117 (-1%)**

### Segment Multiple Rationale

- **China E-commerce (1.5x):** Core CMR growing only +1% in Q3 FY2026. Quick commerce adds high growth but negative EBITA. The 88VIP membership (59M, double-digit growth) provides a floor. 1.5x reflects a mature marketplace with structurally declining take rates offset by quick commerce optionality.

- **Cloud Intelligence (4.0x):** The jewel. 36% revenue growth with triple-digit AI revenue growth for 10 consecutive quarters. #1 in China (35.8% share). Apple China AI partnership. At 4.0x, this values cloud at roughly 60% of what US peers (AWS-implied ~8x, Azure ~10x) trade at, which reflects the China/geopolitical discount. If cloud maintains 30%+ growth, 5-6x would be defensible, adding HK$8-15/share.

- **AIDC (0.8x):** Growth decelerated sharply to +4% in Q3 from +14% a year ago. US tariff headwinds on AliExpress cross-border volumes. Turned marginally profitable in Q2 FY2026. 0.8x reflects a low-growth, low-margin international business facing structural headwinds.

- **All Others (0.5x):** Declining revenue due to Sun Art/Intime disposals. Mix of Cainiao (logistics, deconsolidated), Freshippo, Ali Health, Amap, DingTalk. Individual pieces range from high-value (Ali Health at 2.1x EV/Rev as publicly traded) to restructuring/disposal candidates. 0.5x is a conservative blended multiple.

**HIDDEN VALUE FLAG:** The market may be undervaluing Cloud Intelligence. At current prices, stripping out net cash (HK$16.4/share) and Ant Group (HK$10.0/share), the remaining business trades at an implied EV of ~RMB 1,551B. Cloud at 4.0x revenue accounts for 38% of that. If the market begins to separately value Alibaba's cloud business as AI narrative takes hold — as happened with AWS within Amazon — significant re-rating potential exists.

---

## METHOD 6: PE / LBO FLOOR

**Framing:** Traditional LBO is inapplicable (too large). Using a growth equity / sovereign wealth fund model with no incremental leverage, pure equity return.

### Entry Assumptions
- Entry EV: RMB 2,033B (current EV + 10% premium)
- Debt: RMB 0B (no incremental leverage)
- Equity invested: RMB 2,331B (implied market cap at entry)

### 5-Year Projection (Base Case)

| Year | Revenue (RMB B) | FCF (RMB B) | Cumulative FCF |
|------|----------------|-------------|----------------|
| 1 | 1,170 | 11.7 | 11.7 |
| 2 | 1,276 | 51.0 | 62.7 |
| 3 | 1,378 | 96.4 | 159.2 |
| 4 | 1,474 | 147.4 | 306.6 |
| 5 | 1,563 | 187.5 | 494.1 |

### Exit Assumptions
- Exit multiple: 1.5x NTM Revenue (vs. 1.58x entry)
- Year 6 Revenue: RMB 1,656B
- Exit EV: RMB 2,484B
- Exit Equity: RMB 3,276B (EV + net cash + cumulative FCF)
- MOIC: 1.41x
- Implied IRR: 7.0%

### Floor Price

| IRR Target | Max Entry Price (HKD) | vs. Current |
|------------|-----------------------|-------------|
| 20% (PE) | HK$72.7 | -39% |
| 15% (Sovereign fund) | HK$89.9 | -24% |
| 10% (Infrastructure fund) | HK$112.6 | -5% |

**REALITY CHECK:** At a 20% IRR hurdle, a financial buyer would need to pay ~HK$73/share — 39% below current price. This is a hard downside floor: even highly demanding return targets produce a floor above HK$70. The net cash per share of HK$16.4 plus Ant Group value of HK$10.0 provides additional downside protection (combined HK$26.4 = 22% of current price is pure asset backing).

---

## DELIVERABLE 1: VALUATION SUMMARY & CONVICTION SCORE

```
━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━
TICKER: 9988.HK
CURRENT PRICE: HK$118.5
ANALYSIS DATE: April 4, 2026

METHOD RESULTS:
| Method         | Bear    | Base     | Bull     | Weight | Confidence |
|----------------|---------|----------|----------|--------|------------|
| Reverse DCF    | —       | Mkt implies 2.9% vs 10% actual: UNDERPRICED signal | — | — | M |
| Forward DCF    | HK$72   | HK$144   | HK$219   | 35%    | M          |
| Trading Comps  | —       | HK$126   | —        | 30%    | M-H        |
| M&A Comps      | —       | HK$97    | —        | 5%     | L          |
| Sum-of-Parts   | —       | HK$117   | —        | 20%    | M          |
| PE/LBO Floor   | HK$73   | —        | —        | 10%    | L          |

TRIANGULATED PRICE TARGET:
- Bear case:  HK$79  (-33%)   [US$81/ADS]
- Base case:  HK$122 (+3%)    [US$126/ADS]
- Bull case:  HK$174 (+47%)   [US$179/ADS]

CONVICTION SCORE: 3.5 / 5
- 5 = Highest conviction, all methods converge, clear mispricing
- 4 = High conviction, most methods agree, minor data gaps
- 3 = Moderate conviction, methods diverge, valuation roughly fair
- 2 = Low conviction, significant data gaps or method disagreement
- 1 = No conviction, insufficient data or stock is uninvestable

CONVICTION RATIONALE:
The reverse DCF signals clear undervaluation (market pricing in sub-3% growth
vs ~10% actual), and the forward DCF base case supports 22% upside. However,
the trading comps and SoP methods converge near current price, suggesting the
market is approximately correctly pricing the stock when adjusting for near-term
margin destruction from AI capex and the food delivery war. Conviction is capped
at 3.5 by: (1) three consecutive quarters of consensus misses, (2) negative FCF
trajectory with unknowable duration, (3) binary geopolitical risk (HFCAA, tariffs,
military blacklist), and (4) absence of management guidance on investment phase
duration or ROI timeline.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### Weighting Rationale

- **Forward DCF (35%):** Highest weight because Alibaba has predictable recurring revenue (CMR, cloud contracts, subscriptions) and the margin trajectory, while uncertain, follows a knowable capex cycle. However, terminal value dominance (75%) and current negative FCF reduce confidence.

- **Trading Comps (30%):** Well-defined 15-company Chinese internet peer set with consistent reporting. Comps suggest Alibaba is trading roughly in-line on growth-adjusted metrics. Moderate-high confidence.

- **Sum-of-Parts (20%):** Meaningful because Alibaba's segments have genuinely different value profiles (cloud at 36% growth vs. AIDC at 4% growth). The segment-level view reveals cloud as the primary value driver and highlights potential hidden value. However, exact segment economics are not fully disclosed.

- **PE/LBO Floor (10%):** Provides a hard downside reference. Not primary because a takeout is unrealistic.

- **M&A Comps (5%):** Lowest weight. Few relevant transactions exist at Alibaba's scale. Primarily a floor/ceiling reference.

---

## DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━
TICKER: 9988.HK
COMPANY: Alibaba Group Holding Limited
SECTOR: Chinese Internet / Tech Conglomerates
VALUATION DATE: April 4, 2026

PRICE TARGET: HK$122 base case (range: HK$79 bear — HK$174 bull)
CURRENT PRICE: HK$118.5
UPSIDE TO BASE: +3%
CONVICTION: 3.5 / 5

WHEEL STRATEGY IMPLICATIONS:

- SELL PUTS: CONDITIONAL
  - Rationale: Stock is approximately at base case fair value — selling
    puts at current levels offers limited margin of safety. Wait for
    post-earnings pullback or entry at bear-case levels.
  - Suggested strike zone: HK$71-79 (at or below bear case)
  - Why this zone: HK$73 = PE/LBO floor (20% IRR). HK$79 = triangulated
    bear case. Puts at these levels would be assigned only at prices
    offering 35-40% upside to base case.
  - Avoid puts above: HK$100 (above this, risk/reward inverts)
  - Conditional trigger: If stock pulls back to HK$90-100 post-Q4 FY2026
    earnings (May 14), reassess for put-selling at HK$80-90 zone.

- COVERED CALLS (if assigned):
  - Cost basis assumption: HK$71-79 (put strike zone)
  - Minimum call strike: HK$71-79 (cost basis floor per cc_min_strike=1.0x)
  - Suggested call strike zone: HK$100-120 (between cost basis and base PT)
  - Do NOT sell calls above: HK$140+ (approaching DCF base case — let it run)

- CONCENTRATED LONG CANDIDATE: NO
  - Rationale: Conviction 3.5 < 4 threshold; upside to base case +3% < 30%
    threshold. Both conditions fail. Alibaba is a WATCH, not a conviction long.
  - Re-evaluation trigger: If Q4 FY2026 earnings show (a) FCF turning
    positive, (b) Cloud EBITA expanding, and (c) CMR growth recovering
    to mid-single-digits → re-run valuation for potential upgrade.

KEY DATES TO AVOID (earnings, catalysts):
- May 14-15, 2026: Q4 FY2026 + full year results + FY2027 strategy update
  ⚠ CRITICAL — FCF trajectory and Cloud EBITA turn are key tests
  ⚠ Do NOT have open options positions across this date
- Ongoing: US-China geopolitical (HFCAA audit, tariff policy, 1260H list)
  → Creates persistent binary tail risk unquantifiable in models
- H1 CY2026: Potential new AI capex plan announcement (beyond RMB 380B)
  → Could extend the investment phase and further delay FCF recovery

SECTOR CONTEXT:
- Sector score from analysis: 14/25 WATCH
- Relative ranking in sector: 5th of 7 Internet Conglomerates
  (behind Tencent 20, PDD/NetEase/JD.com all at 16)
- Upgrade trigger: Cloud EBITA turning positive at 30%+ rev growth by FY2026 Q4
- Sector-level risk flag: Food delivery war (RMB 80B+ combined subsidy
  destruction); AI capex returns uncertainty; geopolitical binary risk
- Cross-sector comparison: NU (fintech, 4/5 conviction, 37% upside) and
  Bilibili (entertainment, 4/5, 36% upside) are higher-conviction Chinese
  equity opportunities from current research pipeline
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## KEY TAKEAWAYS

**1. Alibaba is approximately fairly valued at HK$118.5.** The base case target of HK$122 implies only +3% upside, though the reverse DCF suggests the market may be too pessimistic on long-term growth (pricing in 2.9% vs. 10% actual).

**2. The investment creates a wide fair value range.** Bear (HK$79) to bull (HK$174) spans a 2.2x range, reflecting genuine uncertainty about the AI capex cycle's duration and ROI. This is not a precision-valuation stock — it's a scenario-dependent bet.

**3. Cloud Intelligence is the key value driver.** At 36% growth with AI tailwinds, cloud accounts for 32% of SoP equity value on only 14% of revenue. A re-rating of this segment (from 4.0x to 5-6x revenue) could add HK$8-15/share. This is the bull case catalyst.

**4. The downside is well-protected.** Net cash of HK$16.4/share + Ant Group HK$10.0/share = 22% of current price is pure asset backing. The PE floor at HK$73 suggests limited downside below that level.

**5. Not a conviction opportunity — yet.** At 3.5/5 conviction, Alibaba does not meet the concentrated long threshold (requires ≥4 conviction AND ≥30% upside). The stock warrants monitoring for a re-entry opportunity if FCF turns positive, Cloud EBITA expands, or the stock pulls back to HK$90-100.
