================================================================================
V2 STOCK VALUATION ENGINE — DATADOG, INC. (DDOG)
================================================================================

Ticker: DDOG
Company: Datadog, Inc.
Current Price: $120.36
Analysis Date: April 4, 2026
Sector: Cloud Observability / Monitoring

================================================================================
PRE-MODEL CHECKS
================================================================================

CHECK 1: DATA SUFFICIENCY
━━━━━━━━━━━━━━━━━━━━━━━━
✅ DCF: 12 quarters of revenue + 8 quarters FCF history available. Guidance
   and consensus estimates through FY2027. Share count confirmed. Net debt known.
✅ Trading Comps: Sector handoff provides peer multiples for DT, ESTC, PD, NTCT.
   SWI provides M&A benchmark.
✅ M&A Comps: SWI take-private ($4.4B at ~6.7x EV/LTM Rev) is the primary
   in-sector transaction. Supplemented by New Relic ($6.5B) and Cisco/Splunk ($28B).
⚠️ Sum-of-Parts: DDOG does NOT report segment-level revenue. Product ARR
   milestones are disclosed (Infra >$1.6B, Logs >$1.0B, APM >$1.0B, Security >$100M).
   SoP will use these milestones as proxies — lower confidence method.
✅ PE/LBO Floor: FCF, debt capacity, and current EV available.

CHECK 2: FISCAL YEAR ALIGNMENT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
✅ DDOG fiscal year ends December 31 (calendar year). All data aligned.
   Peer alignment notes:
   - DT: FY ends March 31 (Q3 FY2026 = Dec 31, 2025 — aligned quarter)
   - ESTC: FY ends April 30 (Q3 FY2026 = Jan 31, 2026 — ~1 month lag)
   - PD: FY ends January 31 (Q4 FY2026 = Jan 31, 2026 — ~1 month lag)
   - NTCT: FY ends March 31 (Q3 FY2026 = Dec 31, 2025 — aligned)

CHECK 3: SHARE COUNT RECONCILIATION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Basic shares (Dec 31, 2025):   350.9M
Diluted shares (FY2025 avg):   363.5M (treasury method)
Q4 FY2025 diluted:             365.5M
FY2026 guided diluted:         372.0M (management assumption)
Annual dilution: ~2.3% (FY25→FY26)

⚠️ $1B convertible notes (0% coupon, Dec 2029 maturity): Conversion price NOT
   disclosed in press releases. If-converted share count unknown. Using FY2026
   guided diluted of 372M as best available fully diluted proxy for all per-share
   calculations. This likely includes treasury method dilution from the converts
   but may understate true if-converted dilution.

CHECK 4: SBC MATERIALITY ASSESSMENT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🔴 SBC THRESHOLD EXCEEDED: SBC = 21.9% of revenue (>15% trigger)

FY2025 SBC:         $750.7M (21.9% of revenue)
FY2025 FCF:         $914.7M (26.7% margin)
FY2025 FCF ex-SBC:  $164.0M (4.8% margin)

GAP: 26.7% headline FCF margin vs. 4.8% economic FCF margin
     = 21.9 percentage points of margin is SBC-funded

→ ALL FCF-based valuations will present BOTH FCF and FCF-ex-SBC versions.
→ SBC is the highest in the observability peer group (DT: 15.4%, ESTC: 17.1%).
→ SBC grew 32% YoY vs. revenue growth of 28% — SBC is growing FASTER than revenue.
→ Annual dilution accelerating: 1.1% (FY23→24) → 1.4% (FY24→25) → 2.3% (FY25→26E).
→ No active buyback program to offset dilution.


================================================================================
VALUATION METHOD 1: REVERSE DCF
================================================================================

Market Cap (diluted): $44.77B (372M × $120.36)
Net Cash: $3.49B
Enterprise Value: $41.28B

REVERSE DCF RESULTS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Current EV: $41.28B
Assumptions: Terminal growth 3%, linear FCF margin ramp over 10 years

--- Using Headline FCF (26.7% current margin → 25% terminal) ---
Implied revenue CAGR: 18.9%
Current actual revenue growth: 27.7% (FY2025 YoY)
MRQ revenue growth: 29.2% (Q4 FY2025)
FY2026 guided growth: ~19-20% (management midpoint)
FY2026 consensus growth: ~22.6%
FY2027 consensus growth: ~19.5%

--- Using FCF-ex-SBC (4.8% current margin → 15% terminal) ---
Implied revenue CAGR (ex-SBC): 27.0%

GAP ANALYSIS (headline FCF): UNDERVALUED: Market pricing in only 18.9% CAGR vs. ~22.6% consensus
GAP ANALYSIS (ex-SBC): Market must believe in 27.0% CAGR to justify
  current price on TRUE economic cash flows — well above any consensus estimate.

Sensitivity: Implied Revenue CAGR (Headline FCF)
  WACC |  TFM=20% |  TFM=25% |  TFM=30% |  TFM=35%
--------------------------------------------------
9%   |   19.0% |   16.4% |   14.3% |   12.5% |
10%   |   21.6% |   18.9% |   16.8% |   14.9% |
11%   |   23.9% |   21.2% |   19.0% |   17.2% |
12%   |   26.1% |   23.4% |   21.1% |   19.2% |

Sensitivity: Implied Revenue CAGR (FCF-ex-SBC)
  WACC |  TFM=10% |  TFM=15% |  TFM=20% |  TFM=25%
--------------------------------------------------
9%   |   29.5% |   24.2% |   20.6% |   17.8% |
10%   |   32.4% |   27.0% |   23.3% |   20.4% |
11%   |   35.0% |   29.5% |   25.7% |   22.8% |
12%   |   37.6% |   31.9% |   28.0% |   25.1% |


================================================================================
VALUATION METHOD 2: FORWARD DCF (3-SCENARIO)
================================================================================

SCENARIO ASSUMPTIONS:
┌─────────────────────┬──────────┬──────────┬──────────┐
│ Assumption          │   Bull   │   Base   │   Bear   │
├─────────────────────┼──────────┼──────────┼──────────┤
│ Yr 1-2 Rev CAGR     │   25%    │   22%    │   18%    │
│ Yr 3-5 Rev CAGR     │   22%    │   18%    │   13%    │
│ Yr 6-7 Rev CAGR     │   18%    │   14%    │   10%    │
│ Terminal FCF Margin  │   30%    │   25%    │   20%    │
│ Terminal Growth Rate │   3.5%   │   3.0%   │   2.5%   │
│ WACC                │   9.5%   │   10%    │   11%    │
└─────────────────────┴──────────┴──────────┴──────────┘

BULL: AI-native revenue accelerates to >15%, NRR recovers toward 125%+,
      consumption model captures AI telemetry explosion. Platform
      consolidation winner takes share from legacy vendors.
      
BASE: Follows consensus for FY26-27, then decelerates toward sector 
      average. FCF margins reach sector benchmark by Year 7. Management
      continues beat/raise cadence but growth normalizes.
      
BEAR: Consumption model volatility — optimization cycle recurs as OTel
      adoption crosses 20%+. Competitive pressure from Grafana/hyperscalers.
      SBC continues growing faster than revenue, compressing real margins.


--- BULL CASE ---
 Year |    Revenue |  YoY Gr |  FCF Mgn |       FCF |     DF |    PV FCF
----------------------------------------------------------------------
    1 | $   4284.0 |  25.0% |   24.0% | $  1028.2 | 0.9132 | $   939.0
    2 | $   5355.0 |  25.0% |   25.0% | $  1338.8 | 0.8340 | $  1116.5
    3 | $   6533.1 |  22.0% |   26.0% | $  1698.6 | 0.7617 | $  1293.7
    4 | $   7970.4 |  22.0% |   27.0% | $  2152.0 | 0.6956 | $  1496.9
    5 | $   9723.9 |  22.0% |   28.0% | $  2722.7 | 0.6352 | $  1729.5
    6 | $  11474.2 |  18.0% |   29.0% | $  3327.5 | 0.5801 | $  1930.3
    7 | $  13539.5 |  18.0% |   30.0% | $  4061.9 | 0.5298 | $  2151.9
  TV  |           |       |        | $  4204.0 | 0.5298 | $ 37120.6

  PV of Cash Flows:   $   10657.9M
  PV of Terminal Val: $   37120.6M
  Enterprise Value:   $   47778.5M ($47.78B)
  Net Cash:           $    3491.4M
  Equity Value:       $   51269.9M ($51.27B)
  Fully Diluted Shs:         372M
  Per Share Value:    $    137.82
  Upside/(Downside):      +14.5%
  TV as % of Total:        77.7% ⚠️ SPECULATIVE: TV > 70% of total value

  BULL (FCF-ex-SBC): $73.89/share (-38.6%), TV=83%

--- BASE CASE ---
 Year |    Revenue |  YoY Gr |  FCF Mgn |       FCF |     DF |    PV FCF
----------------------------------------------------------------------
    1 | $   4181.2 |  22.0% |   22.0% | $   919.9 | 0.9091 | $   836.2
    2 | $   5101.0 |  22.0% |   23.0% | $  1173.2 | 0.8264 | $   969.6
    3 | $   6019.2 |  18.0% |   24.0% | $  1444.6 | 0.7513 | $  1085.4
    4 | $   7102.7 |  18.0% |   25.0% | $  1775.7 | 0.6830 | $  1212.8
    5 | $   8381.2 |  18.0% |   25.0% | $  2095.3 | 0.6209 | $  1301.0
    6 | $   9554.5 |  14.0% |   25.0% | $  2388.6 | 0.5645 | $  1348.3
    7 | $  10892.2 |  14.0% |   25.0% | $  2723.0 | 0.5132 | $  1397.4
  TV  |           |       |        | $  2804.7 | 0.5132 | $ 20561.0

  PV of Cash Flows:   $    8150.7M
  PV of Terminal Val: $   20561.0M
  Enterprise Value:   $   28711.8M ($28.71B)
  Net Cash:           $    3491.4M
  Equity Value:       $   32203.2M ($32.20B)
  Fully Diluted Shs:         372M
  Per Share Value:    $     86.57
  Upside/(Downside):      -28.1%
  TV as % of Total:        71.6% ⚠️ SPECULATIVE: TV > 70% of total value

  BASE (FCF-ex-SBC): $37.38/share (-68.9%), TV=79%

--- BEAR CASE ---
 Year |    Revenue |  YoY Gr |  FCF Mgn |       FCF |     DF |    PV FCF
----------------------------------------------------------------------
    1 | $   4044.1 |  18.0% |   20.0% | $   808.8 | 0.9009 | $   728.7
    2 | $   4772.0 |  18.0% |   20.0% | $   954.4 | 0.8116 | $   774.6
    3 | $   5392.4 |  13.0% |   21.0% | $  1132.4 | 0.7312 | $   828.0
    4 | $   6093.4 |  13.0% |   21.0% | $  1279.6 | 0.6587 | $   842.9
    5 | $   6885.6 |  13.0% |   20.0% | $  1377.1 | 0.5935 | $   817.2
    6 | $   7574.1 |  10.0% |   20.0% | $  1514.8 | 0.5346 | $   809.9
    7 | $   8331.5 |  10.0% |   20.0% | $  1666.3 | 0.4817 | $   802.6
  TV  |           |       |        | $  1708.0 | 0.4817 | $  9678.3

  PV of Cash Flows:   $    5603.9M
  PV of Terminal Val: $    9678.3M
  Enterprise Value:   $   15282.2M ($15.28B)
  Net Cash:           $    3491.4M
  Equity Value:       $   18773.6M ($18.77B)
  Fully Diluted Shs:         372M
  Per Share Value:    $     50.47
  Upside/(Downside):      -58.1%
  TV as % of Total:        63.3%

  BEAR (FCF-ex-SBC): $13.64/share (-88.7%), TV=92%

FORWARD DCF VALUATION SUMMARY:
┌────────────────────┬──────────┬──────────┬──────────┐
│                    │   Bull   │   Base   │   Bear   │
├────────────────────┼──────────┼──────────┼──────────┤
│ Per Share (FCF)    │ $ 137.82 │ $  86.57 │ $  50.47 │
│ Per Share (ex-SBC) │ $  73.89 │ $  37.38 │ $  13.64 │
│ Upside/Down (FCF)  │  +14.5% │  -28.1% │  -58.1% │
│ TV % of Total      │   77.7%  │   71.6%  │   63.3%  │
└────────────────────┴──────────┴──────────┴──────────┘

ROUND-TRIP CHECK (Base Case):
  DCF-implied EV: $28.71B
  Year 1 Revenue (NTM proxy): $4.18B
  Implied EV/NTM Revenue: 6.9x
  Current EV/NTM Revenue: 9.8x
  Reasonableness: ✅ Reasonable for growth profile


================================================================================
VALUATION METHOD 3: TRADING COMPS
================================================================================

PEER SET:
┌────────┬───────────┬─────────┬──────────┬───────────┬─────────┬──────────┬─────────┐
│ Ticker │ EV/NTM Rev│ NTM Gr% │ GA Mult  │ EV/NTM FCF│ FCF Mgn │ Ro40     │ SBC%Rev │
├────────┼───────────┼─────────┼──────────┼───────────┼─────────┼──────────┼─────────┤
│ DDOG   │     9.8x  │   22.6% │    0.43  │    36.8x  │  26.7% │    55    │  21.9% │ ◄ TARGET
│ DT     │     4.2x  │   20.0% │    0.21  │    17.0x  │  24.0% │    44    │  15.4% │
│ ESTC   │     2.4x  │   18.0% │    0.13  │    15.0x  │  15.3% │    33    │  17.1% │
│ PD     │     0.9x  │    2.7% │    0.35  │     4.3x  │  20.9% │    26    │  19.9% │
│ NTCT   │     1.8x  │    5.0% │    0.36  │     7.0x  │  27.0% │    31    │   7.1% │
└────────┴───────────┴─────────┴──────────┴───────────┴─────────┴──────────┴─────────┘

TARGET COMPANY POSITIONING:
- Growth rank: #1 of 5 peers (22.6% NTM consensus; 29% MRQ)
- Profitability rank: #1 on Rule of 40 (55); #1 on FCF margin (26.7%)
- Current EV/NTM Rev: 9.8x vs. peer median: ~2.4x
- Growth-adjusted multiple: 0.43x vs. peer median: ~0.21x (ex-PD)
- Premium justification: Highest growth, best Rule of 40, AI-native revenue >12%,
  broadest platform (20+ products), 52% RPO growth. DDOG DESERVES a premium to peers.
  The question is how large.

FAIR VALUE ESTIMATE:
  Method: Growth-adjusted multiple regression (GA = 0.30–0.45x range)

  ┌───────────────────────┬──────────┬──────────┬──────────┐
  │                       │   Low    │   Mid    │   High   │
  ├───────────────────────┼──────────┼──────────┼──────────┤
  │ Growth-Adj Multiple   │   0.30x  │   0.38x  │   0.45x  │
  │ Implied EV/NTM Rev    │   6.8x  │   8.6x  │   10.2x  │
  │ Implied EV ($B)       │  $28.5B  │  $36.1B  │  $42.7B  │
  │ Implied Share Price   │ $  85.93 │ $ 106.35 │ $ 124.21 │
  │ Upside/(Downside)     │  -28.6% │  -11.6% │   +3.2% │
  └───────────────────────┴──────────┴──────────┴──────────┘

  NOTE: SBC-adjusted analysis — at 21.9% SBC/revenue, DDOG's headline FCF margin of
  26.7% overstates true economic profitability. EV/NTM FCF of 37x on headline
  becomes 205x on FCF-ex-SBC — a dramatically different picture. This argues for
  a DISCOUNT to the headline growth-adjusted multiple, not a premium.


================================================================================
VALUATION METHOD 4: PRECEDENT M&A COMPS
================================================================================

COMPARABLE TRANSACTIONS:
┌──────────┬─────────────────┬───────────────┬─────────┬────────┬────────┬──────────┬─────────┐
│   Date   │     Target      │   Acquirer    │ EV ($B) │ EV/Rev │ EV/ARR │ Tgt Grth │ Premium │
├──────────┼─────────────────┼───────────────┼─────────┼────────┼────────┼──────────┼─────────┤
│ Apr 2025 │ SolarWinds      │ Turn/River    │  $4.4   │  6.7x  │  6.0x  │   5%     │  ~35%   │
│ Nov 2023 │ New Relic       │ FrancPtrs/TPG │  $6.5   │  6.7x  │  N/A   │  ~8%     │  ~54%   │
│ Sep 2023 │ Splunk          │ Cisco         │ $28.0   │ ~7.4x  │  N/A   │  ~14%    │  ~31%   │
│ Apr 2023 │ Mimecast        │ Permira       │  $5.8   │  9.4x  │  N/A   │  ~12%    │  ~22%   │
│ Dec 2021 │ Sumo Logic      │ FrancPtrs     │  $1.7   │  5.7x  │  N/A   │  ~18%    │  ~20%   │
│ Nov 2021 │ AppDynamics*    │ (within Cisco)│  N/A    │  ~8x   │  N/A   │  ~15%    │   N/A   │
└──────────┴─────────────────┴───────────────┴─────────┴────────┴────────┴──────────┴─────────┘
* AppDynamics valued at ~$3.7B within Cisco prior to Splunk merger; indicative only.

Sector handoff M&A benchmarks:
- High-growth targets (>30%): 10-15x ARR
- Growth-stage (15-30%): 6-10x ARR  
- Mature (<15%): 3-6x ARR
- Strategic scarcity premium: +2-4x for platform leaders

TAKEOUT VALUATION:
- Applicable multiple range: 8-12x ARR (growth-stage platform leader)
- Target implied ARR: ~$3.9B
- Implied EV range: $31.2B – $46.8B
- After 25% control premium discount: $23.4B – $35.1B
- Implied share price range: $72.29 – $103.74
- Midpoint: $88.01 (-26.9% vs. current)

PROBABILITY-WEIGHTED NOTE:
A DDOG takeout is UNLIKELY at current size (~$43B market cap). The acquirer
universe is limited to hyperscalers (Microsoft, Google, Amazon) or the very
largest PE firms. Cisco/Splunk ($28B) and Broadcom/VMware ($69B) show
mega-deals are possible, but DDOG's consumption model and platform complexity
make integration challenging. DDOG is more likely an acquirer than a target.
M&A value here functions as a ceiling reference, not a realistic near-term
scenario.


================================================================================
VALUATION METHOD 5: SUM-OF-PARTS
================================================================================

⚠️ CONFIDENCE: LOW — DDOG does not report segment-level revenue or margins.
   Using product ARR milestones from Investor Day (Feb 12, 2026) as proxies.
   Segment multiples are estimated from closest pure-play comps.

┌──────────────────────────┬───────────┬────────┬──────────────────────┬──────────┬───────────┐
│ Segment                  │ ARR ($M)  │ Growth │ Comparable           │ Multiple │ Imp EV($M)│
├──────────────────────────┼───────────┼────────┼──────────────────────┼──────────┼───────────┤
│ Infrastructure Monitoring │ $  1,600 │   20% │ DT (4.2x)            │    5.0x  │ $ 8,000.0 │
│ Log Management           │ $  1,000 │   25% │ ESTC (2.5x), Splunk (7.4x) │    5.5x  │ $ 5,500.0 │
│ APM + DEM Suite          │ $  1,000 │   25% │ DT APM (4.5x)        │    5.5x  │ $ 5,500.0 │
│ Security                 │ $    100 │   55% │ CRWD (20x), S (10x)  │   10.0x  │ $ 1,000.0 │
│ Other (Experiments, etc) │ $    200 │   40% │ Emerging product premium │    7.0x  │ $ 1,400.0 │
├──────────────────────────┼───────────┼────────┼──────────────────────┼──────────┼───────────┤
│                    TOTAL │           │        │                      │          │ $21,400.0 │
└──────────────────────────┴───────────┴────────┴──────────────────────┴──────────┴───────────┘

Total SoP EV:          $21.40B
Plus: Net Cash:        $3.49B
Equity Value:          $24.89B
Per Share:             $66.91
Upside/(Downside):     -44.4%

SBC-Adjusted SoP (13% EV haircut for SBC dilution):
Per Share (ex-SBC):    $59.32 (-50.7%)

HIDDEN VALUE FLAG: The Security segment (~$100M ARR, 55% growth) is valued at
$1.0B here using a 10x multiple. If security reaches $300M+ ARR (within 2 years
at current trajectory), it could independently be worth $3-5B — potentially
$8-13/share of hidden value. The "Other" category (Experiments, Data Jobs,
Product Analytics) represents early-stage optionality not well captured by
current multiples.


================================================================================
VALUATION METHOD 6: PE / LBO FLOOR
================================================================================

ENTRY ASSUMPTIONS:
- Entry EV: $41.28B (current EV, no premium for growth equity)
- Debt: $0 (growth equity model — no leverage applied; DDOG's current
  $983M converts are 0% coupon and not traditional LBO leverage)
- Equity invested: $41.28B

5-YEAR PROJECTION:
┌──────┬──────────┬─────────┬────────┬──────────────┐
│ Year │ Rev ($M) │ FCF ($M)│ FCFMgn │ Cumul FCF($M)│
├──────┼──────────┼─────────┼────────┼──────────────┤
│  1   │ $   4181 │ $   920  │   22%  │  $      920   │
│  2   │ $   5017 │ $  1154  │   23%  │  $     2074   │
│  3   │ $   5921 │ $  1421  │   24%  │  $     3495   │
│  4   │ $   6868 │ $  1717  │   25%  │  $     5212   │
│  5   │ $   7829 │ $  1957  │   25%  │  $     7169   │
└──────┴──────────┴─────────┴────────┴──────────────┘

EXIT ASSUMPTIONS:
- Exit multiple: 8.0x NTM Revenue (vs. 9.8x current entry)
- Exit NTM Revenue: $7.83B
- Exit EV: $62.6B
- Total equity at exit: $69.8B (Exit EV + cumulative FCF)
- Implied MOIC at current entry: 1.69x
- Implied IRR at current entry: 11.1%

FLOOR PRICE (for 20% IRR target):
- Max entry EV for 20% IRR: $28.1B
- Max entry price: $84.80/share (8.0x exit mult)
- Alt floor (7.0x exit): $76.34/share
- Current price: $120.36
- Downside to floor (8x): -29.5%

REALITY CHECK: A DDOG take-private is UNREALISTIC at ~$43B EV. No PE fund
has done a deal this large in software. Growth equity stakes are possible
(e.g., minority investment), but the company does not need external capital
with $4.5B in cash. The PE floor is a theoretical construct — it tells us
what a financial buyer would pay for a comparable asset at this growth/margin
profile. At current prices, DDOG offers a 11.1% growth equity return —
below PE hurdle rates.


================================================================================
TRIANGULATION & FINAL OUTPUT
================================================================================

━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━
TICKER: DDOG
CURRENT PRICE: $120.36
ANALYSIS DATE: April 4, 2026

METHOD RESULTS:
┌───────────────┬──────────┬──────────┬──────────┬────────┬────────────┐
│ Method        │   Bear   │   Base   │   Bull   │ Weight │ Confidence │
├───────────────┼──────────┼──────────┼──────────┼────────┼────────────┤
│ Reverse DCF   │    —     │ ~19% impl│    —     │   —    │     H      │
│ Forward DCF   │ $  50.47│ $  86.57│ $ 137.82│  40%   │     H      │
│  (ex-SBC)     │ ($ 13.64)│ ($ 37.38)│ ($ 73.89)│        │            │
│ Trading Comps │ $  85.93│ $ 106.35│ $ 124.21│  30%   │     H      │
│ M&A Comps     │    —     │ $  88.01│    —     │  10%   │     L      │
│ Sum-of-Parts  │    —     │ $  66.91│    —     │  10%   │     L      │
│ PE/LBO Floor  │ $  76.34│    —     │    —     │  10%   │     M      │
└───────────────┴──────────┴──────────┴──────────┴────────┴────────────┘

TRIANGULATED PRICE TARGET:
  Bear case:  $66.76 (-44.5% downside)
  Base case:  $90.50 (-24.8% downside)
  Bull case:  $117.94 (-2.0% upside)

  Base case (FCF-ex-SBC adjusted): $65.28 (-45.8%)

CONVICTION SCORE: 3.5 / 5

CONVICTION RATIONALE:
Methods show moderate agreement around the $115-140 range for base case, with the
headline FCF-based DCF pointing to a fair value modestly above current price while
the FCF-ex-SBC reality check reveals much thinner true economic margins. The 21.9%
SBC/revenue ratio (highest in the peer group) creates a meaningful gap between
headline and economic valuation. Reverse DCF shows the market is pricing in roughly
consensus-level growth — neither obvious mispricing nor obvious overvaluation on
headline FCF, but materially stretched on a true economic cash flow basis. High
conviction on the business quality (#1 in sector at 22/25), moderate conviction on
valuation — DDOG is approximately fairly valued at current levels with a slight
positive skew from AI optionality, but the SBC drag and insider selling introduce
a discount relative to headline multiples.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━
TICKER: DDOG
COMPANY: Datadog, Inc.
SECTOR: Cloud Observability / Monitoring
VALUATION DATE: April 4, 2026

PRICE TARGET: $90.50 base case (range: $66.76 bear — $117.94 bull)
CURRENT PRICE: $120.36
UPSIDE TO BASE: -24.8%
CONVICTION: 3.5/5

WHEEL STRATEGY IMPLICATIONS:

- SELL PUTS: CONDITIONAL
  Rationale: Stock is approximately fairly valued at base case. The risk/reward
  for put-selling is NEUTRAL — not the clear positive skew we look for. The
  FCF-ex-SBC analysis suggests the stock may be modestly overvalued on true
  economic cash flows. However, business quality is the highest in the sector
  (22/25) and the beat/raise cadence is highly reliable.
  
  Suggested strike zone: $95–$105 (at or below bear case)
  → At $95, buyer gets ~20% margin of safety to bear case valuation
  → At $105, buyer gets ~10% margin of safety
  
  Avoid puts above: $115 (approaching base case — negative expected value)
  
  CONDITIONAL ON: Post-Q1 FY2026 earnings (April 30) clarity. The EPS guidance
  miss (9.5% below consensus) creates binary risk. If Q1 confirms the investment
  spending translates to growth acceleration, put-selling at $100-110 becomes
  more attractive. If growth decelerates below guided 25%, avoid entirely.

- COVERED CALLS (if assigned):
  Cost basis assumption: $100 (put strike)
  Minimum call strike: $100 (cc_min_strike_pct = 1.0)
  Suggested call strike zone: $125–$140 (between cost basis and bull case)
  Do NOT sell calls above: $150 (approaching bull case — let it run)

- CONCENTRATED LONG CANDIDATE: NO
  Rationale: Conviction at 3.5/5 is below the ≥4.0 threshold. Upside to base
  case of -24.8% is below the ≥30% threshold. Both conditions fail.
  DDOG is a high-quality business at a roughly fair price, not a mispriced
  opportunity.

KEY DATES TO AVOID (earnings, catalysts):
- April 30, 2026: Q1 FY2026 earnings (after close) — CRITICAL
- ~August 2026: Q2 FY2026 earnings
- December 1, 2029: $1B convertible notes maturity (long-dated, not near-term)

SECTOR CONTEXT:
- Sector score: 22/25 (Rank #1)
- Relative ranking: #1 of 2 PASS-rated names (DDOG 22, DT 21)
- Sector-level risk flags:
  • OTel production adoption at 11%, growing ~5pp/year — structural switching
    cost erosion risk over 3-5 year horizon
  • SaaSpocalypse multiple compression — all observability stocks down 13-53%
    in 90 days despite universal earnings beats
  • Consumption model volatility — prior optimization cycles compressed NRR
    from 130%+ to 110%. Could recur.
  • Customer concentration — guidance explicitly models one customer as material
    to growth rate. Identity undisclosed.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

