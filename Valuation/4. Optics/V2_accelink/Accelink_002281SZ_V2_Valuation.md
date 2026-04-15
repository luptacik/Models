# Accelink Technologies (002281.SZ) — V2 Stock Valuation

**Analysis Date:** April 4, 2026  
**Current Price:** ¥90.00  
**Currency:** CNY (millions unless stated)

---

## VERDICT: MODERATELY OVERVALUED

| Metric | Value |
|---|---|
| **Base Case Fair Value** | **¥80** |
| **Bear Case** | ¥25 |
| **Bull Case** | ¥116 |
| **Upside to Base** | **-10.9%** |
| **Conviction** | **3 / 5** |
| **Sell Puts?** | NOT at current levels |
| **Concentrated Long?** | NO |

---

================================================================================
ACCELINK TECHNOLOGIES (002281.SZ) — V2 STOCK VALUATION ENGINE
================================================================================

────────────────────────────────────────────────────────────
PRE-MODEL CHECKS
────────────────────────────────────────────────────────────
Market Cap (diluted): CNY 73,980M = CNY 74.0B
Net Cash: CNY 3,753M
Enterprise Value: CNY 70,227M = CNY 70.2B

CHECK 1 — DATA SUFFICIENCY:
  DCF:      ✓ 8+ quarters revenue, OCF/capex for FY22-24 + 9M25, consensus estimates
  Comps:    ⚠ Limited — R2 has peer data but no EV/NTM Revenue (requires terminal)
            Using available mkt cap, revenue, margin data for Chinese optical peers
  M&A:      ⚠ Sparse — most sector M&A is Western companies. Limited Chinese optical deals.
  SoP:      ✓ Two segments: Data & Access (71%) and Transmission (29%)
  LBO:      ✓ FCF data available; SOE status limits PE buyout realism

CHECK 2 — FISCAL YEAR ALIGNMENT:
  Accelink FY ends December 31 (calendar year) ✓
  All peer Chinese A-shares also calendar-year ✓
  FY2025 annual report expected April 22-23, 2026 (not yet released)

CHECK 3 — SHARE COUNT RECONCILIATION:
  Basic shares:       806.85M
  RSU outstanding:    ~15.07M (2025 plan, vesting 2025-2029)
  Fully diluted:      822M (basic + RSU)
  No convertible bonds ✓
  Directed offering pending: up to 242M new shares (30% dilution)
    → If fully executed at max: 1049M shares
    → Using 822M for base case; 1049M for bear case
  Annual dilution from equity incentives: ~0.5%/year

CHECK 4 — SBC MATERIALITY ASSESSMENT:
  2025 RSU plan: CNY 196.1M amortized over 2025-2029 = ~CNY 39M/year
  SBC as % of FY2024 Revenue: 0.5%
  SBC as % of FY2025E Revenue (~11.45B): 0.3%
  → BELOW 15% threshold — FCF-ex-SBC dual track NOT required
  → Chinese A-share SOE: SBC structurally immaterial (similar to BYD finding)
  ⚠ However, the ~30% dilution from directed offering IS material
    and represents the true equity dilution risk in lieu of large SBC


================================================================================
METHOD 1: REVERSE DCF
================================================================================

Current EV: CNY 70.2B
Base Revenue (FY2025E): CNY 11.4B

Assumptions:
  Terminal FCF margin: sensitivity 8-15%
  Terminal growth: 3%
  WACC: sensitivity 10-13%
  Current FCF margin: ~4% (estimated)
  Years to terminal: 10

  FY2024 actual revenue growth: +36.5%
  9M 2025 revenue growth: +58.6%
  Consensus FY2025E growth: ~38% (from FY2024)
  Consensus FY2026E growth: ~24%
  Consensus FY2027E growth: ~12%

  BASE CASE IMPLIED REVENUE CAGR: 24.5%
  vs. Consensus FY2026-27 growth: ~24% declining to ~12%

  SENSITIVITY TABLE: Implied Revenue CAGR (%)
  WACC \ Term FCF Margin | 8%   | 10%   | 12%   | 15%   |
  ---------------------------------------------------------
  10.0%                   | 26.1% | 23.2% | 20.9% | 18.2% |
  10.5%                   | 27.4% | 24.5% | 22.2% | 19.4% |
  11.5%                   | 29.8% | 26.9% | 24.5% | 21.6% |
  12.0%                   | 31.0% | 28.0% | 25.6% | 22.7% |
  13.0%                   | 33.2% | 30.2% | 27.7% | 24.8% |

  GAP ANALYSIS:
  Market implies ~24.5% revenue CAGR vs:
    Consensus trajectory (weighted avg FY25-27): ~20-25%
    Management incentive floor: ≥6% NI CAGR (deliberately conservative)
  → Market is pricing roughly in line with consensus trajectory


================================================================================
METHOD 2: FORWARD DCF (3-SCENARIO)
================================================================================

SCENARIO ASSUMPTIONS:
Assumption                      Bull       Base       Bear
-------------------------------------------------------
Yr 1-2 Rev CAGR               30-28%     24-18%     18-10%
Yr 3-5 Rev CAGR               25-18%     15-10%       5-3%
Yr 6-7 Rev CAGR               15-12%       8-7%         3%
Terminal FCF Margin              15%        12%         8%
Terminal Growth Rate            3.5%       3.0%       2.5%
WACC                           10.5%      11.5%      13.0%

BASE CASE REVENUE PROJECTION:
Year      Rev (M)    YoY %  FCF Margin   FCF (M)  Disc Factor  PV of FCF
-------------------------------------------------------------------
  1        14,198    24.0%        5.1%       730      1.1150        655
  2        16,754    18.0%        6.3%     1,053      1.2432        847
  3        19,267    15.0%        7.4%     1,431      1.3862      1,032
  4        21,579    12.0%        8.6%     1,850      1.5456      1,197
  5        23,737    10.0%        9.7%     2,306      1.7234      1,338
  6        25,635     8.0%       10.9%     2,783      1.9215      1,448
  7        27,430     7.0%       12.0%     3,292      2.1425      1,536
  TV                                      39,886      2.1425     18,617

VALUATION SUMMARY:
                                       Bull         Base         Bear
------------------------------------------------------------------
              PV of Cash Flows       14,579        8,054        3,551
          PV of Terminal Value       48,688       18,617        5,830
              Enterprise Value       63,267       26,671        9,381
                      Net Cash        3,753        3,753        3,753
                  Equity Value       67,020       30,424       13,134
            Diluted Shares (M)          822          822        1,049
               Per Share Value       ¥81.53       ¥37.01       ¥12.52
           Upside / (Downside)        -9.4%       -58.9%       -86.1%
              TV as % of Total        77.0%        69.8%        62.2%

  ⚠️ Bull case: Terminal value = 77.0% of total EV — SPECULATIVE
     Valuation dominated by long-term assumptions, not near-term fundamentals

  ROUND-TRIP CHECK:
  Base case EV: CNY 26.7B
  NTM Revenue (FY2026E): CNY 14.2B
  Implied EV/NTM Rev: 1.9x
  Current EV/NTM Rev: 4.9x
  Current EV/TTM Rev (11.43B): 6.1x

  BULL CASE — What must go right:
    1. 800G/1.6T volumes sustain 25-30% revenue CAGR for 3+ years
    2. Gross margins expand from 23% to 28%+ as product mix shifts to 1.6T
    3. Directed offering executed at favorable terms, capital deployed productively
    4. Domestic cloud buildout (Alibaba, ByteDance) expands Accelink's wallet share
    5. No Entity List escalation affecting DSP supply

  BEAR CASE — What could go wrong:
    1. Hyperscaler capex cycle peaks mid-2026, optical demand drops 20-30%
    2. Innolight and Eoptolink continue to win at higher margins, compressing Accelink's pricing power
    3. Directed offering fully executes (30% dilution) at low price
    4. Entity List risk materializes — parent FiberHome already listed
    5. CPO transition accelerates, compressing pluggable transceiver TAM earlier than expected


================================================================================
METHOD 3: TRADING COMPS
================================================================================

PEER SET — CHINESE A-SHARE OPTICAL COMPANIES:
Company                         Mkt Cap    TTM Rev   EV/Rev  Rev Grw     GM  NI Margin  GA Ratio
------------------------------------------------------------------------------------------
  Innolight (300308.SZ)           672B     38.2B    17.3x     60%  39.0%      28.3%     0.29x
  Eoptolink (300502.SZ)           465B     16.5B    27.9x    100%  42.0%      33.0%     0.28x
  TFC Optical (300394.SZ)         241B      4.8B    50.0x     53%  45.0%      23.0%     0.94x
  Accelink (002281.SZ)             73B     11.4B     6.0x     61%  23.1%       8.4%     0.10x ← TARGET

TARGET COMPANY POSITIONING:
  Revenue growth rank: 2 of 4 peers
  Gross margin rank: 4 of 4 (LAST — structurally lower)
  Current EV/TTM Rev: 6.0x vs peer median 27.9x (-78% discount)

FAIR VALUE ESTIMATE:
  Method A: Margin-adjusted EV/Rev
    Peer median EV/Rev: 27.9x
    Margin adjustment factor: 0.58 (Accelink GM 23% / peer avg ~40%)
    Fair EV/Rev: 17.7x
    Implied EV: CNY 202.4B → Equity: CNY 206.2B
    Implied share price: ¥250.83
    Upside / (Downside): +178.7%

  Method B: P/Gross Profit comparison
    Innolight P/GP: 45.1x
    Eoptolink P/GP: 67.1x
    Peer avg P/GP: 56.1x
    Accelink TTM GP: CNY 2.6B
    Fair Mkt Cap at peer P/GP (with 30% SOE discount): CNY 103.6B
    Implied share price: ¥126.09
    Upside / (Downside): +40.1%

  BLENDED TRADING COMPS FAIR VALUE: ¥188.46 (+109.4%)

  KEY JUDGMENT: Accelink DESERVES a significant discount to peers because:
    1. Gross margins (23%) are ~half of peer average (~40%)
    2. Net margins (8%) are ~quarter of peer average (~30%)
    3. SOE governance: slower decision-making, state-directed strategy priorities
    4. Entity List parent company creates structural risk premium
    5. 75% domestic exposure limits access to highest-growth global hyperscaler demand


================================================================================
METHOD 4: PRECEDENT M&A COMPS
================================================================================

COMPARABLE TRANSACTIONS:
Date         Target                 Acquirer            EV ($B)  EV/Rev Tgt Growth
--------------------------------------------------------------------------------
  Feb 2025   Infinera             Nokia            $   2.3B  ~1.6x       ~10%
  Oct 2023   Cloud Light          Lumentum         $   0.8B  ~3.8x     ~100%+
  Mar 2025   Spirent Ethernet     VIAVI            $   0.4B  ~2-3x       ~15%
  Jan 2026   CommScope CCS        Amphenol         $  10.5B  ~2.5x        ~5%
  Dec 2025   Celestial AI         Marvell          $   3.2B N/M (pre-rev)        N/A

  APPLICABLE MULTIPLE RANGE:
  Accelink's growth profile (~40%+): 2.5-4.0x revenue
  Adjusted for SOE status (no realistic takeout): -30% discount
  Adjusted for China A-share (limited foreign buyer access): -20% discount
  → Effective range: 1.2-2.2x revenue

  TAKEOUT VALUATION:
  NTM Revenue (FY2026E): CNY 14.2B
  EV range: CNY 17.0B – 31.2B
  Equity range: CNY 20.8B – 35.0B
  Per share range: ¥25.29 – ¥42.57
  Midpoint: ¥33.93 (-62.3%)

  PROBABILITY-WEIGHTED NOTE:
  A takeout is EXTREMELY UNLIKELY for Accelink. As a subsidiary of
  state-owned CICT/FiberHome (SASAC-controlled), the company is a
  'national champion' that would not be sold to a foreign buyer.
  Domestic consolidation is theoretically possible but not signaled.
  M&A comps serve only as a theoretical floor reference.
  CONFIDENCE: LOW — weight this method at minimum


================================================================================
METHOD 5: SUM-OF-PARTS
================================================================================

SEGMENT BREAKDOWN (FY2025E estimated):
Segment                 Revenue (M) % of Total   Growth     GM             Comparable   Multiple  Implied EV (M)
---------------------------------------------------------------------------------------------------------
  Data & Access               8,130        71%  +50-60%  21.7%    Innolight/Eopt disc       5.0x          40,648
  Transmission                3,320        29%   ~5-10%   ~28%         Mature optical       1.5x           4,981
  ---------------------------------------------------------------------------------------------------------
  Total                      11,450       100%                                                            45,628

  Total EV: CNY 45.6B
  Plus Net Cash: CNY 3.8B
  Equity Value: CNY 49.4B
  Per Share: ¥60.07
  Upside / (Downside): -33.3%

  HIDDEN VALUE FLAG:
  The Data & Access segment's rapid growth (+50-60% YoY) and improving margins
  (13% → 22% over 2 years) are partially obscured by the lower-margin Transmission
  segment dragging the blended gross margin to ~23%. If Data & Access were a
  standalone entity with continued margin expansion to ~25-28%, it could command
  a meaningfully higher standalone multiple. However, the 21.7% segment margin
  is still well below pure-play peers (40%+), limiting the magnitude of this effect.


================================================================================
METHOD 6: PE / LBO FLOOR
================================================================================

  ⚠ IMPORTANT CONTEXT: Accelink is a Chinese SOE (SASAC → CICT → FiberHome)
  Traditional LBO is not feasible. Using 'growth equity' framing:
  Pure equity, no leverage, 20% IRR target over 5 years.

  ENTRY ASSUMPTIONS:
  Entry EV: CNY 70.2B (current EV, no premium)
  Debt: CNY 0 (growth equity — no leverage for Chinese SOE)
  Equity invested: CNY 70.2B

  5-YEAR PROJECTION:
  Year      Revenue      FCF  Cumulative FCF
  ----------------------------------------
  1          14,198      710             710
  2          16,754    1,005           1,715
  3          19,267    1,541           3,256
  4          21,579    1,942           5,199
  5          23,737    2,374           7,572

  EXIT ASSUMPTIONS:
  Year 5 Revenue: CNY 23.7B (growing 10%)
  Exit multiple: 4.0x NTM Revenue (vs. 6.1x entry)
  Exit EV: CNY 94.9B
  Equity at exit: CNY 102.5B (EV + cumulative FCF)
  MOIC: 1.46x
  Implied IRR: 7.9%

  FLOOR PRICE:
  Max entry EV for 20% IRR: CNY 33.6B
  Max entry price for 20% IRR: ¥45.48
  Current price: ¥90.00
  Downside to floor: -49.5%

  REALITY CHECK:
  PE/growth equity interest in Accelink is unrealistic given SOE ownership.
  SASAC/CICT controls 38% and would not sell. The floor price is a theoretical
  construct only. However, it confirms that at ¥45, a rational financial
  buyer targeting 20% returns would not invest.


================================================================================
DELIVERABLE 1: PRICE TARGET RANGE & CONVICTION SCORE
================================================================================

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
TICKER: 002281.SZ (Accelink Technologies)
CURRENT PRICE: ¥90.00
ANALYSIS DATE: April 4, 2026
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

METHOD RESULTS:
Method                     Bear       Base       Bull   Weight  Confidence
----------------------------------------------------------------------
Reverse DCF                   — ~26% impl.          —        —           M
Forward DCF                 ¥13        ¥37        ¥82      40%           M
Trading Comps                 —       ¥188          —      25%           M
M&A Comps                     —        ¥34          —       5%           L
Sum-of-Parts                  —        ¥60          —      20%           M
PE/LBO Floor                ¥45          —          —      10%           L

TRIANGULATED PRICE TARGET:
  Bear case: ¥25 (-72.3% downside)
  Base case: ¥80 (-10.9% downside)
  Bull case: ¥116 (+28.7% upside)

CONVICTION SCORE: 3 / 5

CONVICTION RATIONALE:
  Moderate conviction. Valuation methods converge on a base case moderately
  below the current price (~¥80 vs ¥90), with the reverse DCF confirming the
  market is pricing in ~26% long-term CAGR — above consensus trajectory of ~20-24%
  for FY2026-27 and ~12% for FY2027+. The structural margin gap (23% GM vs 40%+
  peers) and SOE governance discount are persistent headwinds that limit multiple
  re-rating potential. Upside case requires sustained 800G/1.6T demand AND margin
  expansion AND no Entity List escalation — a high bar. The stock is trading above
  the analyst consensus target of ¥70.24, suggesting the rally has overshot
  near-term fundamentals. However, the China AI infrastructure buildout provides
  a credible secular tailwind, and the world-first 3.2T NPO milestone at OFC 2026
  demonstrates genuine technology capability.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
STOCK VALUATION → OPTIONS WHEEL HANDOFF
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
TICKER: 002281.SZ
COMPANY: Accelink Technologies (光迅科技)
SECTOR: Optics / Connectivity
VALUATION DATE: April 4, 2026

PRICE TARGET: ¥80 base case (range: ¥25 bear — ¥116 bull)
CURRENT PRICE: ¥90
UPSIDE TO BASE: -10.9%
CONVICTION: 3/5

WHEEL STRATEGY IMPLICATIONS:
  SELL PUTS: CONDITIONAL — NOT AT CURRENT PRICE
    Rationale: Stock is 12% above base case PT. Current price
    embeds optimistic assumptions beyond consensus. Selling puts at ¥90
    would be selling into an overvalued name with negative expected value.
    ONLY sell puts if stock corrects to ¥25-80 range post-earnings.
    Suggested strike zone: ¥25-75 (at or below bear case)
    Avoid puts above: ¥80

  COVERED CALLS (if assigned): YES
    If somehow assigned via put-selling at lower strikes,
    sell calls at ¥80+ to exit at fair value.

  CONCENTRATED LONG CANDIDATE: NO
    Rationale: Conviction is 3/5 (below ≥4 threshold) and base case
    implies -10.9% (below +30% upside threshold).
    Both criteria must be met. Neither is met.

KEY DATES TO AVOID (earnings, catalysts):
  Apr 14, 2026: Section 232 tariff decision deadline
  Apr 22-23, 2026: FY2025 annual report release — THE key catalyst
  ~Oct 2026: Q3 2026 results / potential directed offering execution
  Ongoing: BIS Entity List review cycles (unpredictable)

SECTOR CONTEXT:
  Sector score from analysis: Not scored in PASS framework
    (Chinese A-shares excluded from PASS due to geopolitical/access constraints)
  Relative positioning: #5 globally in optical components (Omdia)
    Lowest-margin among Chinese A-share optical peers
  Sector-level risk flag: Hyperscaler capex cycle could peak 2026-2027;
    22 of 25 companies in sector show net insider selling
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

⚠️ CRITICAL NOTE: Options availability on 002281.SZ
  China A-share individual stock options are limited.
  Shenzhen-listed stocks generally have NO listed options contracts.
  The options wheel strategy may not be directly executable on this name.
  Alternatives: (1) Use as informational input only,
  (2) Express view via sector ETFs, (3) Use OTC structured products.

---

## CRITICAL NOTE: METHOD DIVERGENCE ANALYSIS

The most striking feature of this valuation is the **extreme divergence between methods:**

- **Forward DCF base case: ¥37** — fundamentals-up analysis says the stock is worth less than half its current price
- **Trading comps: ¥188** — relative to (arguably overvalued) peers, Accelink looks cheap
- **Sum-of-parts: ¥60** — segment-level analysis confirms overvaluation but less extreme
- **PE/LBO floor: ¥45** — a rational financial buyer would not pay current price

**Why do the methods diverge so dramatically?**

1. **The Chinese optical peer set is in a speculative bubble.** Innolight at 17x revenue, Eoptolink at 28x, TFC at 50x — these are AI supercycle multiples that assume sustained 40-60% growth and 40%+ margins for years. If the cycle peaks (as 22 of 25 sector insiders seem to believe based on net selling), peer multiples will compress dramatically, pulling comps-derived fair value down toward DCF levels.

2. **Accelink's margins are structurally lower.** At 23% gross margin and 8% net margin vs. peer averages of 40% and 30% respectively, Accelink converts revenue to cash flow at roughly one-quarter the rate of its peers. The DCF captures this reality; the comps method only partially adjusts for it.

3. **The DCF is conservative but honest.** A 12% terminal FCF margin for a hardware/component company with 23% gross margins is reasonable — it requires meaningful margin expansion over 7 years. The base case WACC of 11.5% reflects China risk, SOE governance discount, and Entity List tail risk.

**Resolution:** The weighted base case of ¥80 reflects a judgment that:
- The DCF's fundamental analysis is directionally correct (the stock is overvalued)
- The comps provide a ceiling reference showing Accelink has relative value within its peer group
- The magnitude of overvaluation is moderate (~12%), not extreme
- Post-earnings correction to the ¥70-80 range would represent fair value

---

## KEY RISKS NOT FULLY CAPTURED IN MODELS

1. **Directed share offering (up to 30% dilution)** — pending CSRC registration. If executed at maximum size at a discount to market, per-share values drop ~23% across all methods. The bear case uses max-diluted shares; base case does not.

2. **Entity List escalation** — parent FiberHome is already on the US Entity List. If Accelink itself is added, access to Western DSPs (Broadcom/Marvell) would be cut, crippling 800G+ module production. This is a low-probability, high-impact binary risk not easily modeled.

3. **Inventory impairment** — CNY 6.18B inventory (97 days of COGS) represents aggressive stockpiling. 9M 2025 impairments already reached CNY 237M (+75% YoY). If the cycle turns, additional write-downs could materially impact earnings.

4. **No listed options on 002281.SZ** — Shenzhen-listed stocks generally do not have individual stock options contracts. The options wheel strategy cannot be directly executed on this name.

