# V2 STOCK VALUATION — XD INC (2400.HK)

**Ticker:** 2400.HK | **Company:** XD Inc | **Sector:** Chinese Digital Entertainment (Gaming + Platform)
**Current Price:** HK$60.85 | **Analysis Date:** April 4, 2026

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency

| Method | Data Available | Gaps | Usable? |
|---|---|---|---|
| **Reverse DCF** | FY2023–2025 revenue, FY2024–25 FCF, consensus FY2026–27E, share count, net cash | FY2025 detailed cash flow statement single-source | ✅ Yes |
| **Forward DCF** | 3-year revenue history, 2-year FCF, consensus projections, terminal margin benchmarks from sector handoff | FY2028+ estimates not found; FY2025 OpEx breakdown missing | ✅ Yes |
| **Trading Comps** | Full peer multiples for 7 comparables from sector analysis + R2 | Some peer FCF data estimated | ✅ Yes |
| **M&A Comps** | 5 recent Chinese gaming/entertainment transactions from R1 | Most deal values undisclosed; limited gaming-specific M&A | ⚠️ Usable with lower confidence |
| **Sum-of-Parts** | FY2024 full segment breakdown, H1 2025 segment data; FY2025 estimated split | FY2025 segment P&L not available at line-item level | ✅ Yes |
| **PE/LBO Floor** | FCF, balance sheet, EV all available | Debt capacity moot (zero debt company) | ✅ Yes |

### Check 2: Fiscal Year Alignment
XD Inc's fiscal year ends **December 31** — calendar year. All peers in the comp set also report on calendar fiscal years. No alignment issues.

### Check 3: Share Count Reconciliation

| Measure | Shares (M) | Source |
|---|---|---|
| Basic shares | 480.1 | MarketScreener (FY2025) |
| Diluted shares (treasury method) | ~500 | Estimated from FY2024 diluted count + option grants |
| Fully diluted (incl. all options/RSUs) | ~495–500 | LOW confidence — annual report needed for exact figure |

**Using 500M fully diluted shares for all per-share calculations.** This is conservative (higher share count = lower per-share values). Annual dilution is negligible at <0.5% and trending negative (buyback > issuance in FY2025).

### Check 4: SBC Materiality Assessment
**SBC = CNY 69M = 1.2% of FY2025 revenue.** This is well below the 15% threshold. No dual-track FCF/FCF-ex-SBC presentation required. XD's SBC is immaterial — the company uses minimal stock-based compensation, a rarity among growth-stage tech companies and a positive for shareholders.

---

## METHOD 1: REVERSE DCF

**Purpose:** What growth rate does the market currently price in?

```
REVERSE DCF RESULTS
━━━━━━━━━━━━━━━━━━

Current EV:                     CNY 24,241M
Base Revenue (FY2025):          CNY 5,764M
Current FCF Margin:             30.6%
Assumptions:                    Terminal FCF margin 30%, terminal growth 3%, WACC 12%

Implied revenue CAGR:           5.9%
Current actual revenue growth:  +15.0% (FY2025)
Consensus NTM revenue growth:   +13.7% (FY2026E)
H2 2025 revenue growth:         -3.9% YoY (sharp deceleration)
Management guidance:            None issued (floor-only guidance historically)

GAP ANALYSIS:
Market implies 5.9% growth vs. 13–15% actual/consensus
→ Market is pricing in BELOW-CONSENSUS growth — potential UNDERVALUATION signal

However, context matters: the H2 2025 revenue cliff (-3.9% YoY) and >20% decline in online game 
MAU/MPU explain the market's skepticism. The 5.9% implied CAGR is closer to what the organic run-rate 
might be WITHOUT a successful Ragnarok 2 launch. The market is effectively discounting the next hit 
cycle entirely — reasonable given the binary nature of gaming launches.
```

**Sensitivity: Implied Revenue CAGR (%)**

| WACC \ Terminal FCF Margin | 20% | 25% | 30% | 35% |
|---|---|---|---|---|
| **10%** | 6.4% | 4.1% | 2.3% | 0.7% |
| **11%** | 8.3% | 6.0% | 4.1% | 2.5% |
| **12%** | **10.1%** | **7.8%** | **5.9%** | **4.2%** |
| **13%** | 11.8% | 9.5% | 7.5% | 5.9% |

At a more aggressive 10% WACC and 20% terminal FCF margin, the implied growth rate rises to 6.4% — still well below consensus. This suggests the stock has a margin of safety embedded in price relative to consensus expectations.

---

## METHOD 2: FORWARD DCF (3-SCENARIO)

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|---|---|---|---|
| **Yr 1–2 Rev CAGR** | 15.0% | 13.7–13.9% | 10–8% |
| **Yr 3–5 Rev CAGR** | 12–8% | 10–6% | 5–2% |
| **Yr 6–7 Rev CAGR** | 6–5% | 5–4% | 1% |
| **Terminal FCF Margin** | 35% | 32% | 28% |
| **Terminal Growth Rate** | 3.0% | 3.0% | 2.5% |
| **WACC** | 11.0% | 12.0% | 13.0% |

**What must go right (Bull):** Ragnarok: Love at First Sight 2 is a major hit (>CNY 2B first-year gross bookings), TapTap ad ARPU continues expanding double-digit, and at least one additional title in the pipeline (Xindong Town International or TapTap Maker AI) contributes meaningful revenue by FY2028.

**Most likely path (Base):** Ragnarok 2 performs adequately but doesn't replicate the GoGo Muffin/Sword of Convallaria cycle. TapTap grows modestly. Margins hold near current levels due to high operating leverage. Revenue follows consensus for 2 years then decelerates toward the sector's 5–7% mature growth rate.

**What could go wrong (Bear):** Ragnarok 2 underperforms or slips past mid-2026. Online game MAU/MPU decline accelerates below 10M MAU. TapTap ad monetization hits a ceiling at ~44M MAU. The company becomes a slowly declining cash cow with shrinking user engagement and no growth catalyst.

### Base Case Revenue Projection

| Year | Revenue (CNY M) | YoY Growth | FCF Margin | FCF (CNY M) | Discount Factor | PV of FCF |
|---|---|---|---|---|---|---|
| 1 (FY2026) | 6,553 | 13.7% | 29.0% | 1,900 | 0.8929 | 1,697 |
| 2 (FY2027) | 7,464 | 13.9% | 30.0% | 2,239 | 0.7972 | 1,785 |
| 3 (FY2028) | 8,211 | 10.0% | 30.0% | 2,463 | 0.7118 | 1,753 |
| 4 (FY2029) | 8,868 | 8.0% | 31.0% | 2,749 | 0.6355 | 1,747 |
| 5 (FY2030) | 9,400 | 6.0% | 31.0% | 2,914 | 0.5674 | 1,653 |
| 6 (FY2031) | 9,870 | 5.0% | 32.0% | 3,158 | 0.5066 | 1,600 |
| 7 (FY2032) | 10,264 | 4.0% | 32.0% | 3,285 | 0.4523 | 1,486 |
| **Terminal Value** | | | | 37,590 | 0.4523 | **17,004** |

### Valuation Summary

| | Bull | Base | Bear |
|---|---|---|---|
| **PV of Cash Flows** | CNY 13,770M | CNY 11,721M | CNY 8,153M |
| **PV of Terminal Value** | CNY 24,501M | CNY 17,004M | CNY 8,952M |
| **Enterprise Value** | CNY 38,270M | CNY 28,725M | CNY 17,105M |
| **Net Cash** | CNY 3,750M | CNY 3,750M | CNY 3,750M |
| **Equity Value** | CNY 42,020M | CNY 32,475M | CNY 20,855M |
| **Fully Diluted Shares** | 500M | 500M | 500M |
| **Per Share (CNY)** | CNY 84.04 | CNY 64.95 | CNY 41.71 |
| **Per Share (HKD)** | **HK$91.35** | **HK$70.60** | **HK$45.34** |
| **Upside / (Downside)** | **+50.1%** | **+16.0%** | **-25.5%** |
| **TV as % of Total EV** | 64.0% | 59.2% | 52.3% |

Terminal value is 52–64% of total EV across all scenarios — within acceptable range (below the 70% warning threshold). The valuation is grounded in near-term cash flows, not speculative terminal assumptions.

### Round-Trip Check (Base Case)
Base case EV of CNY 28,725M implies:
- EV/NTM Revenue: 4.4x (current: 3.7x) — reasonable for a 14% grower with 30% FCF margins
- Forward P/E: 16.8x (current: 14.5x) — modest premium to current, within the China gaming P/E range of 7–23x

✅ Round-trip check passes. The implied multiples are within the peer range and internally consistent.

---

## METHOD 3: TRADING COMPS

### Peer Set

| Company | Ticker | EV/NTM Rev | P/E Fwd | Growth % | GM % | FCF % | Growth-Adj Ratio |
|---|---|---|---|---|---|---|---|
| NetEase | 9999.HK | 3.0x | 13.0x | +6.9% | 64.3% | 43% | 43.5x |
| Bilibili | 9626.HK | 1.7x | 23.0x | +13.0% | 36.6% | 20% | 13.1x |
| Sanqi Interactive | 002555.SZ | 2.5x | 11.2x | -7.2% | 76.8% | 20% | N/M |
| Century Huatong | 002602.SZ | 2.9x | 19.0x | +75.3% | 69.3% | 23% | 3.9x |
| Perfect World | 002624.SZ | 3.7x | N/M | +29.0% | 57.3% | N/A | 12.8x |
| Giant Network | 002558.SZ | 11.0x | 28.0x | +41.7% | 89.2% | 49% | 26.4x |
| Kingsoft | 3888.HK | 0.9x | 21.0x | -6.0% | 81.2% | 15% | N/M |
| **XD Inc (target)** | **2400.HK** | **3.7x** | **14.5x** | **+13.7%** | **72.0%** | **31%** | **27.0x** |

### Target Company Positioning
- **Growth rank:** 4 of 7 peers (mid-tier growth, behind Century Huatong, Giant Network, and Perfect World)
- **Profitability rank (FCF margin):** 3 of 7 peers (behind only NetEase at 43% and Giant Network at 49%)
- **Current EV/NTM Rev:** 3.7x vs. Tier A peer median of 3.3x — trading at a **12% premium**

XD deserves a slight premium to the peer median because: (1) its 30.6% FCF margin is top-3 in the peer set, (2) TapTap provides a non-gaming revenue stream with 83.6% gross margins, and (3) the zero-debt balance sheet with 10–12% of market cap in net cash provides downside protection. However, the premium should be limited because (1) the company is small-cap with high title concentration risk, (2) TapTap MAU growth has stalled, and (3) the H2 2025 revenue cliff signals vulnerability.

### Fair Value Estimate

**Method A — EV/NTM Revenue:** Fair multiple of 3.5x (above-median for platform quality and FCF leadership). Implied EV: CNY 22,925M → Equity: CNY 26,675M → **HK$58.00/share.**

**Method B — Forward P/E:** Fair multiple of 16x (discount to BILI's 23x for smaller scale; premium to NetEase's 13x for faster growth). Implied equity: CNY 30,960M → **HK$67.30/share.**

**Blended: HK$62.65 (+3.0% from current)**

The comps suggest XD is approximately fairly valued, with modest upside if the market re-rates toward the P/E-implied value.

---

## METHOD 4: PRECEDENT M&A COMPS

### Comparable Transactions (Chinese Gaming/Entertainment, 2024–2026)

| Date | Target | Acquirer | EV ($B) | EV/Rev | Target Profile |
|---|---|---|---|---|---|
| Nov 2024 | Kuro Games (37→51%) | Tencent | ~$1.7 | ~8x | High-growth gacha gaming |
| Mar 2024 | ByteDance gaming studios | Tencent | N/D | N/D | Talent/IP acquisition |
| Mar 2025 | Ubisoft Vantage (26%) | Tencent | ~$5.0 | ~3x | Mature AAA franchises |
| Jun 2025 | Ximalaya (audio) | TME | ~$2.4 | ~5x | Platform/audio content |
| Feb 2025 | YY Live | Baidu | ~$2.1 | ~2.5x | Declining live-stream |

From the sector handoff, applicable benchmarks: growth-stage targets (15–30% growth) typically transact at 6–10x revenue; high-growth targets (>30%) at 10–15x. XD at 15% growth with a platform asset fits the 5–8x range.

### Takeout Valuation

- Applicable EV/Revenue range: 5–8x
- Target Revenue (FY2025): CNY 5,764M
- Implied EV range: CNY 28,818M — CNY 46,110M
- After 25% control premium discount: CNY 21,614M — CNY 34,582M
- **Implied share price range: HK$55.14 — HK$83.33**
- **Midpoint: HK$69.23**

**Is a takeout realistic?** Plausible but not base case. TapTap's distribution platform would be strategically valuable to Tencent (60%+ mobile gaming market share + distribution monopoly ambitions) or a global gaming conglomerate seeking China access. At ~$3.9B market cap, XD is within the acquisition range. However, founder Huang Yimeng's 34% stake creates a blocking position — any deal requires his consent, and the founder-led culture suggests low willingness to sell.

---

## METHOD 5: SUM-OF-PARTS

### Segment Breakdown

| Segment | Revenue (CNY M) | Growth | Comparable | Multiple | Implied EV (CNY M) |
|---|---|---|---|---|---|
| **Game Operations** | ~3,870 (67%) | ~15% | Mid-cap gaming peers (Sanqi, Century Huatong) | 3.5x | 13,545 |
| **TapTap Platform** | ~1,894 (33%) | ~20% | High-quality ad-tech platforms | 6.0x | 11,364 |
| **Total EV** | | | | | **24,909** |
| **+ Net Cash** | | | | | +3,750 |
| **Equity Value** | | | | | **28,659** |
| **Per Share** | | | | | **HK$62.30** |
| **Upside / (Downside)** | | | | | **+2.4%** |

### Hidden Value Analysis

TapTap accounts for **46% of SoP enterprise value** despite contributing only 33% of revenue — reflecting its dramatically higher margins (83.6% gross margin vs. 68% for games) and higher-quality revenue profile (recurring ad platform vs. hit-driven gaming).

At the current consolidated EV of CNY 24,241M:
- If TapTap is valued at 6x revenue, the Game segment is implicitly valued at only 3.3x — slightly below peer averages
- If Games are valued at 3.5x, TapTap is implicitly valued at 5.6x — below fair value for a high-margin ad platform

**The market is not overpaying for either segment individually**, which supports the "approximately fairly valued" thesis from other methods.

---

## METHOD 6: PE / LBO FLOOR

### Growth Equity Approach (no leverage — XD has zero debt)

**Entry Assumptions:**
- Entry EV: CNY 27,877M (current EV + 15% control premium)
- Debt: CNY 0
- Equity invested: CNY 27,877M

**5-Year FCF Projection:**

| Year | Revenue (CNY M) | FCF (CNY M) | Cumulative FCF |
|---|---|---|---|
| 1 | 6,553 | 1,900 | 1,900 |
| 2 | 7,464 | 2,239 | 4,140 |
| 3 | 8,211 | 2,463 | 6,603 |
| 4 | 8,868 | 2,749 | 9,352 |
| 5 | 9,400 | 2,914 | 12,266 |

**Exit Assumptions:**
- Exit multiple: 3.5x NTM Revenue
- Exit EV: CNY 34,543M
- Equity at exit: CNY 46,809M (EV + cumulative FCF)
- MOIC: 1.68x
- Implied IRR: 10.9%

**Floor Price:**
- Max entry price for 20% IRR: **HK$49.05/share**
- Max entry price for 25% IRR: **HK$41.50/share**
- Current price HK$60.85 is 24% above the 20%-IRR PE floor

**Reality check:** PE interest is plausible given XD's fortress balance sheet, 30%+ FCF margins, and dual-asset model. At ~$3.9B market cap, it's within typical growth equity range. However, the founder's 34% controlling stake, HK listing, and VIE structure add deal complexity. A PE exit would likely require a strategic acquirer or IPO in a different market — neither straightforward.

---

## ━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━

**TICKER:** 2400.HK
**CURRENT PRICE:** HK$60.85
**ANALYSIS DATE:** April 4, 2026

### Method Results

| Method | Bear | Base | Bull | Weight | Confidence |
|---|---|---|---|---|---|
| **Reverse DCF** | — | 5.9% implied CAGR (below consensus) | — | — | H |
| **Forward DCF** | HK$45 | HK$71 | HK$91 | 40% | M-H |
| **Trading Comps** | — | HK$63 | — | 30% | M |
| **M&A Comps** | — | HK$69 | — | 10% | L-M |
| **Sum-of-Parts** | — | HK$62 | — | 15% | M |
| **PE/LBO Floor** | HK$42 | — | — | 5% | M |

### Triangulated Price Target

| Scenario | Price Target | vs. Current |
|---|---|---|
| **Bear case** | **HK$46** | **-24%** |
| **Base case** | **HK$65** | **+7%** |
| **Bull case** | **HK$84** | **+38%** |

### Conviction Score: 3.5 / 5

**Conviction Rationale:** Methods converge reasonably around HK$62–71 for the base case, confirming the stock is approximately fairly valued at HK$60.85. The Reverse DCF reveals the market is pricing in only ~6% sustained growth — well below consensus of 13–14% — which suggests embedded skepticism about the H2 2025 revenue cliff is providing a modest margin of safety. Conviction is capped at 3.5 because: (1) gaming revenue is inherently hit-driven and Ragnarok 2 is a binary catalyst with unknown timing and outcome, (2) TapTap MAU growth has stalled at ~44M with international MAU actively declining, creating uncertainty about the platform's long-term trajectory. Offsetting positives — fortress balance sheet (zero debt, CNY 3.75B net cash = 13% of market cap), negligible SBC dilution (1.2%), and above-peer 30.6% FCF margins — provide meaningful downside protection and make this a quality name for income-oriented strategies.

**Weighting Rationale:** Forward DCF receives the highest weight (40%) because XD's predictable FCF profile and clear margin trajectory make discounted cash flow the most appropriate primary method. Trading Comps receive 30% — the peer set is well-defined and XD trades roughly in-line on a growth/profitability-adjusted basis. Sum-of-Parts receives 15% because the two-segment structure (games + TapTap) reveals genuine valuation information about hidden value. M&A Comps receive 10% with lower confidence due to limited comparable gaming transactions with disclosed prices. PE/LBO Floor receives 5% as a downside reference.

---

## ━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━

```
TICKER: 2400.HK
COMPANY: XD Inc
SECTOR: Chinese Digital Entertainment (Gaming + Platform)
VALUATION DATE: April 4, 2026

PRICE TARGET: HK$65 base case (range: HK$46 bear — HK$84 bull)
CURRENT PRICE: HK$60.85
UPSIDE TO BASE: +7%
CONVICTION: 3.5 / 5

WHEEL STRATEGY IMPLICATIONS:

  SELL PUTS: CONDITIONAL
    Rationale: Stock is roughly fairly valued at base case HK$65. Limited
    upside (~7%) means selling puts at-the-money carries risk of assignment
    near fair value. Risk/reward improves materially at or below bear case,
    where net cash cushion (CNY 3.75B = HK$8.15/share) provides a floor.
    Suggested strike zone: HK$45–52 (at or below bear case valuation)
    Avoid puts above: HK$58 (approaching current price with limited margin of safety)
    ⚠️ Condition: Wait for clarity on Ragnarok 2 launch timing/early reception
    before initiating positions. The launch is a binary catalyst.

  COVERED CALLS (if assigned): YES
    Cost basis assumption: HK$48 (midpoint of put strike zone)
    Minimum call strike: HK$48 (cost basis floor per cc_min_strike_pct=1.0)
    Suggested call strike zone: HK$58–68 (between cost basis and base case PT)
    Do NOT sell calls above: HK$75 (approaching bull case — let it run)

  CONCENTRATED LONG CANDIDATE: NO
    Rationale: Conviction 3.5 < 4 threshold. Upside to base +7% < 30% threshold.
    Both conditions fail. This is a quality name for wheel income generation,
    not aggressive long positioning.

KEY DATES TO AVOID (earnings, catalysts):
  Mid-2026 (TBD):     Ragnarok: Love at First Sight 2 launch — binary game catalyst
  June 4, 2026:       HK$400M automatic buyback program expires
  August 2026 (est.): H1 2026 interim results
  March 2027 (est.):  FY2026 annual results

SECTOR CONTEXT:
  Sector score from analysis: 18/25
  Relative ranking in sector: 5 of 6 PASS-rated names
  Sector-level risk flag: Regulatory tail risk (permanent overhang);
    H2 2025 revenue deceleration signals potential transition from growth
    to value/income story; China discount of 40–60% vs. US entertainment
    peers is structural and unlikely to narrow near-term
```

---

## Key Analytical Findings

**1. The market is pricing in a "prove it" discount.** The Reverse DCF shows the market embedding only 5.9% growth — roughly half of consensus. This isn't irrational: H2 2025 revenue declined 3.9% YoY after H1 grew 39%, and online game MAU/MPU both fell >20%. The stock is priced as if the current game cycle has peaked and no successor has materialized. If Ragnarok 2 launches successfully, this discount unwinds toward the bull case (~HK$90). If it doesn't, the bear case (~HK$45) is the likely destination.

**2. TapTap is the hidden asset — but its growth story is fading.** The SoP analysis attributes 46% of enterprise value to TapTap despite only 33% of revenue, reflecting its 83.6% gross margins and ad pricing power (+36% ARPU growth in H1 2025). However, TapTap China MAU growth decelerated from +23% in FY2024 to +0.9% in H1 2025, and international MAU is declining double-digit. If TapTap is approaching its ~44M MAU ceiling, the platform valuation thesis shifts from growth multiple to cash-flow multiple — still valuable, but the premium compression would weigh on the stock.

**3. The balance sheet provides a hard floor.** Zero debt, ~CNY 3.75B net cash (13% of market cap), 1.2% SBC dilution, and an actively executing HK$400M buyback create meaningful downside protection. Even in the bear case, the per-share net cash of ~HK$8.15 limits absolute downside. This makes XD a suitable name for options wheel strategies where assignment at low strikes creates a favorable cost basis.
