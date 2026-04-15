# V2 STOCK VALUATION — JD.COM (9618.HK)

```
TICKER:         9618.HK / JD (NASDAQ ADR, 1 ADS = 2 ordinary shares)
COMPANY:        JD.com, Inc.
CURRENT PRICE:  HK$112 per ordinary share (~US$28.8/ADS)
ANALYSIS DATE:  April 4, 2026
SECTOR:         Chinese Internet / E-commerce (1P model)
```

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency

| Method | Data Status | Notes |
|--------|------------|-------|
| DCF | ✓ SUFFICIENT | 12 quarters revenue + FCF; consensus FY26-28E; share count; net debt confirmed |
| Trading Comps | ✓ SUFFICIENT | 15-company Chinese internet peer set from sector handoff with multiples |
| M&A Comps | ⚠️ PARTIAL | No comparable-scale Chinese e-commerce M&A. Ceconomy (JD as buyer), Dada take-private used as proxies. Weight reduced. |
| Sum-of-Parts | ✓ SUFFICIENT | 3 segments with revenue + operating income breakdowns |
| PE/LBO Floor | ✓ SUFFICIENT | FCF trajectory, normalized EBITDA, debt capacity, EV confirmed |

### Check 2: Fiscal Year Alignment

**Fiscal year-end: December 31** — calendar year. All Chinese internet peers in the sector handoff also report on a calendar year basis. Alibaba's March FY is mapped to its December quarter (Q3 FY2026) for comparability. No alignment issues.

### Check 3: Share Count Reconciliation

| Metric | Count (millions) | Notes |
|--------|-----------------|-------|
| Class A ordinary shares | ~2,478 | Post-FY2025 buybacks (183.2M cancelled) |
| Class B ordinary shares (Liu) | ~322.5 | Supervoting (20:1); stable |
| **Basic ordinary shares** | **~2,800** | |
| Stock options + RSUs | 88.6 | Options at $16.70/share (ITM), RSUs vesting 4yr |
| US$2.0B convertible notes | 87.5 ordinary | Converts at $45.70/ADS (57% OTM); treasury method: ~0 dilution |
| **Fully diluted (if-converted)** | **2,976** | **Used for all per-share calculations** |
| ADS equivalent | 1,488 | 1 ADS = 2 ordinary shares |

Rationale for if-converted basis: While the convertible is significantly out of the money, using if-converted provides the most conservative per-share estimate. This adds ~3% dilution. The convertible matures June 2029, and conversion becomes relevant only above ~HK$178/ordinary share.

### Check 4: SBC Materiality Assessment

| Year | SBC (RMB M) | % of Revenue |
|------|-------------|-------------|
| FY2022 | 7,548 | 0.72% |
| FY2023 | 4,804 | 0.44% |
| FY2024 | 2,999 | 0.26% |
| FY2025 | ~5,500 | ~0.42% |

**SBC is 0.42% of revenue — WELL BELOW the 15% materiality threshold.** SBC-adjusted FCF presentation is NOT required. JD's SBC is among the lowest of any major global tech company. Critically, JD is a **net share reducer**: share count declined 3.8% in FY2025 and 7.3% in FY2024, driven by $3B+ annual buybacks that massively exceed SBC issuance. This is the structural opposite of US tech SBC dilution.

---

## KEY STRUCTURAL NOTE: JD IS NOT A SaaS COMPANY

JD.com is a **first-party (1P) e-commerce retailer** with an integrated logistics network. This fundamentally changes the valuation framework compared to previous names in this pipeline:

- **Gross margins are structurally low** (~16%) because JD books full inventory sales as revenue (unlike marketplace models like Alibaba/PDD which book commissions)
- **FCF margins are structurally in the 2-5% range** at maturity — not 20-30% like SaaS
- **Revenue scale is enormous** (RMB 1.3T / US$181B) — the highest in the Chinese internet universe, generating massive absolute FCF even at thin margins
- **EV/Revenue is the wrong primary valuation metric** — P/E and EV/Operating Income are more informative for a 1P retailer
- **Net cash position (RMB 151B / US$21B = 52% of market cap)** is the dominant balance sheet feature

---

## METHOD 1: REVERSE DCF

**Purpose:** What growth rate is the current market price implying?

```
REVERSE DCF RESULTS
━━━━━━━━━━━━━━━━━━
Current EV: RMB 141B (US$19.4B)
Current Revenue: RMB 1,309B
Current FCF Margin: 0.5% (FY2025 — depressed by food delivery)
Normalized FCF Margin: 3.8% (FY2024 — pre-food delivery)

Assumptions: Terminal growth 3%, 10-year horizon
Starting FCF margin: 0.5% (ramps linearly to terminal)
```

**Implied Revenue CAGR Sensitivity:**

| WACC \ Terminal FCF Margin | 2% | 3% | 4% | 5% |
|----------------------------|-----|-----|-----|-----|
| 10% | -6.7% | <-10% | <-10% | <-10% |
| 11% | -5.0% | -9.4% | <-10% | <-10% |
| 12% | -3.4% | -7.9% | <-10% | <-10% |
| 13% | -1.9% | -6.5% | -9.8% | <-10% |

**GAP ANALYSIS:**

The reverse DCF produces an extraordinary finding: **under any reasonable terminal assumption, the current price implies negative revenue growth for the next decade.** At the base case (11% WACC, 4% terminal FCF margin), the market is implying a revenue CAGR of effectively <-10% — revenue would need to *shrink* to justify the current valuation.

This compares to:
- FY2025 actual revenue growth: **+13.0%**
- Consensus FY2026 growth: **+5.5-8%**
- Management guidance: **"high single-digit"**
- Consensus FY2027-28 growth: **+5-6%**

**Interpretation:** The current price is not pricing in any particular growth rate. It is pricing in the **net cash position (HK$55/share = 49% of price) plus a de minimis operating business premium**. The implied operating business value is just RMB 141B — roughly 2.7x JD Retail's annual operating income and 0.11x revenue. The market is effectively treating the operating business as if it will generate negligible free cash flow in perpetuity, presumably because of food delivery losses.

This is the single strongest mispricing signal in the model.

---

## METHOD 2: FORWARD DCF (3-SCENARIO)

**Critical modeling note:** JD's FY2025 FCF was artificially depressed by (a) ~RMB 25-30B food delivery operating losses, (b) ~RMB 10-15B trade-in program receivables, and (c) higher fulfillment/marketing costs. Normalized FCF (pre-food delivery, FY2024) was RMB 43.7B at 3.8% margin. The DCF models a recovery trajectory from the current trough.

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|------------|------|------|------|
| Yr 1-2 Rev CAGR | 9-10% | 6-7% | 3-4% |
| Yr 3-5 Rev CAGR | 6-8% | 5-6% | 2-3% |
| Yr 6-7 Rev CAGR | 4-5% | 4% | 2% |
| Terminal FCF Margin | 5.5% | 4.2% | 3.0% |
| Terminal Growth Rate | 3.0% | 3.0% | 2.0% |
| WACC | 10.0% | 11.0% | 12.0% |

**What must go right (Bull):** Food delivery losses halve in 2026 and reach breakeven by 2028. JD Retail margin expands to 7%+ (management's "high single-digit" target). Joybuy Europe gains early traction. General merchandise share grows at the expense of PDD.

**Most likely path (Base):** Food delivery losses moderate ~50% in 2026 per management guidance, further in 2027, minimal by 2029. Revenue growth decelerates from 13% to mid-single digits as trade-in subsidy effects fade. FCF margin recovers to 3-4% (pre-food-delivery levels).

**What could go wrong (Bear):** Food delivery war continues through 2027 as Meituan/Alibaba refuse to de-escalate. Douyin erodes JD's general merchandise share. European expansion burns cash with no returns. Macro weakness suppresses consumer spending.

### Base Case Revenue & FCF Projection (RMB Billions)

| Year | Revenue | YoY Growth | FCF Margin | FCF | Discount Factor | PV of FCF |
|------|---------|-----------|-----------|-----|-----------------|-----------|
| 1 | 1,401 | 7.0% | 2.0% | 28.0 | 0.9009 | 25.2 |
| 2 | 1,485 | 6.0% | 2.8% | 41.6 | 0.8116 | 33.7 |
| 3 | 1,574 | 6.0% | 3.3% | 51.9 | 0.7312 | 38.0 |
| 4 | 1,653 | 5.0% | 3.8% | 62.8 | 0.6587 | 41.4 |
| 5 | 1,735 | 5.0% | 4.0% | 69.4 | 0.5935 | 41.2 |
| 6 | 1,805 | 4.0% | 4.2% | 75.8 | 0.5346 | 40.5 |
| 7 | 1,877 | 4.0% | 4.2% | 78.8 | 0.4817 | 38.0 |
| Terminal | — | — | — | — | — | 488.8 |

### Valuation Summary

| | Bull | Base | Bear |
|---|------|------|------|
| PV of Cash Flows | RMB 366B | RMB 258B | RMB 116B |
| PV of Terminal Value | RMB 872B | RMB 489B | RMB 219B |
| Enterprise Value | RMB 1,238B | RMB 747B | RMB 335B |
| + Net Cash | RMB 151B | RMB 151B | RMB 151B |
| Equity Value | RMB 1,390B | RMB 898B | RMB 486B |
| Fully Diluted Shares | 2,976M | 2,976M | 2,976M |
| **Per Share (HKD)** | **HK$501** | **HK$324** | **HK$175** |
| Upside/(Downside) | +347% | +189% | +57% |
| TV as % of Total | 70.4% ⚠️ | 65.5% ✓ | 65.2% ✓ |

**Terminal value flag:** The bull case TV is 70.4% of total value — marginally above the 70% speculative threshold. This is typical for low-margin businesses where near-term FCF contribution is small. The base and bear cases pass the test.

**Round-trip check:** The base case implies an EV/NTM revenue of 0.53x at Year 1 — reasonable for a 1P retailer with recovering margins, and well within the range of global peers (Amazon retail ~0.5-0.7x, Walmart 0.7-0.8x before China discount). Current 0.11x is the extreme anomaly.

---

## METHOD 3: TRADING COMPS

### Peer Set — Chinese Internet Universe

| Company | EV/NTM Rev | Fwd P/E | Growth% | FCF Margin% | GM% | Growth-Adj EV/Rev |
|---------|-----------|---------|---------|------------|-----|------------------|
| Tencent | 5.50x | 20x | 14% | 24.3% | 56% | 39.3x |
| NetEase | 2.80x | 13x | 7% | 42.0% | 64% | 40.0x |
| Bilibili | 2.00x | 18x | 8% | 20.0% | 37% | 25.0x |
| Alibaba | 1.50x | 17x | 9% | 4.0% | 41% | 16.7x |
| PDD | 1.10x | 8x | 10% | 25.0% | 55% | 11.0x |
| Kuaishou | 1.00x | 11x | 12% | 13.0% | 55% | 8.3x |
| Meituan | 0.90x | N/M | 8% | Neg. | 29% | 11.2x |
| JD Logistics | 0.35x | 9x | 19% | 3.5% | 9% | 1.8x |
| Vipshop | 0.24x | 6x | -2% | 5.1% | 23% | N/M |
| **JD.com** | **0.10x** | **7.8x** | **7%** | **0.5%** | **16%** | **1.4x** |

### Target Company Positioning

- **Growth rank:** 5 of 9 peers (7% FY2026E — mid-pack)
- **Profitability rank:** 8 of 9 (0.5% FCF margin — but temporarily depressed; normalized 3.8%)
- **Current EV/NTM Rev:** 0.10x — **cheapest in the entire Chinese internet universe by far**
- **Current Fwd P/E:** 7.8x — 2nd cheapest (only Vipshop at 6x is lower)
- **Growth-adjusted EV/Rev:** 1.4x — cheapest in universe (vs. median ~16x)

JD's structurally lower gross margin (16% vs. 29-64% for marketplace/platform peers) justifies a lower EV/Revenue multiple. However, the current 0.10x is **not explainable by business model differences alone** — Vipshop, also a 1P-heavy retailer with declining revenue, trades at 0.24x (2.4x JD's multiple). The discount reflects food delivery losses and geopolitical risk premia, not structural economics.

### Fair Value Estimation

**Approach 1 — Normalized P/E (60% weight):**

JD Retail operating income: RMB 51.4B. JD Logistics operating income: RMB 5.3B. Less unallocated costs: -RMB 7.3B. Normalized operating income (ex-food delivery): RMB 49.4B. After ~18% effective tax: **Normalized net income ≈ RMB 40.5B**.

| P/E Multiple | Rationale | Implied Equity (incl. net cash) | Per Share (HKD) | Upside |
|-------------|-----------|-------------------------------|----------------|--------|
| 8x | Conservative — Vipshop/PDD range | RMB 475B | HK$171 | +53% |
| 10x | Mid — sector median for mature names | RMB 556B | HK$201 | +79% |
| 12x | Premium — reflects logistics moat | RMB 638B | HK$230 | +105% |

**Approach 2 — EV/Revenue for 1P Retailers (40% weight):**

Global benchmarks: Walmart 0.7-0.8x, Amazon (retail) 0.5-0.7x. Applying a 40-60% China/VIE discount: fair range 0.20-0.40x.

| EV/NTM Rev | Implied EV | Per Share (HKD) | Upside |
|-----------|-----------|----------------|--------|
| 0.20x | RMB 281B | HK$156 | +39% |
| 0.30x | RMB 422B | HK$207 | +84% |
| 0.40x | RMB 562B | HK$257 | +130% |

**Blended Trading Comps Fair Value: HK$203 (+81%)**
Method: 60% P/E (10x normalized) + 40% EV/Rev (0.30x NTM)

---

## METHOD 4: PRECEDENT M&A COMPS

### Comparable Transactions

| Date | Target | Acquirer | EV ($B) | EV/Rev | Growth | Premium |
|------|--------|----------|---------|--------|--------|---------|
| Nov 2025 | Ceconomy (59.8%) | JD.com | ~€3.7B | ~0.11x | ~0% | ~42% |
| Apr 2024 | Delivery Hero 5% | Meituan | ~€1.5B | ~0.3x | ~10% | ~20% |
| Jan 2024 | Dada (take-private) | JD.com | ~$2.7B | ~3.4x | ~12% | ~60% |
| 2023 | Various CN e-com stakes | Various | <$5B | 0.5-2x | Varies | 20-40% |

### Takeout Valuation

- Applicable multiple range: 0.2-0.4x Revenue (Chinese 1P e-commerce)
- After control premium discount (25%): Effective range 0.15-0.30x
- Implied share price range: **HK$125-196**
- Midpoint: **HK$161 (+44%)**

**Reality check:** A takeout of JD is **effectively impossible**. At US$40B market cap, it is too large for private equity. Richard Liu controls 71.7% of voting power through dual-class shares — no hostile bid is feasible. VIE structure and PRC regulatory restrictions preclude foreign strategic acquisitions. This method is a theoretical floor/ceiling reference only. **Confidence: LOW.**

---

## METHOD 5: SUM-OF-PARTS

This is the most informative method for JD because it isolates the value destruction from food delivery.

### Segment Valuation

| Segment | Revenue (RMB B) | Growth | Op Income | Comparable | Multiple | Implied EV (RMB B) |
|---------|----------------|--------|-----------|------------|----------|-------------------|
| **JD Retail** | 1,126.4 | +10.9% | 51.4B (4.6% margin) | BABA domestic, Vipshop | 10x OP / 0.35x Rev blend | **454** |
| **JD Logistics (63.5%)** | 217.1 | +18.8% | 5.3B (2.4% margin) | 2618.HK market cap | Stake × market value | **51** |
| **New Businesses** | 49.3 | +157% | -46.6B | NPV of loss taper | 2yr losses discounted | **(31)** |
| **Corporate Overhead** | — | — | -7.3B | 8x capitalized annual | — | **(58)** |
| **TOTAL EV** | | | | | | **416** |
| + Net Cash | | | | | | **151** |
| **EQUITY VALUE** | | | | | | **568** |
| **Per Share** | | | | | | **HK$205 (+83%)** |

### Hidden Value Analysis

**JD Retail alone** — at RMB 51.4B operating income growing 25% YoY, valued at 10x operating income = RMB 514B. Adding net cash: RMB 665B = HK$240/share. **JD Retail by itself, valued modestly, exceeds the current market cap by more than 2x.**

**The market is assigning deeply negative value** to: JD Logistics (worth ~RMB 51B on a standalone basis as a public company), the net cash position beyond what's needed to fund food delivery losses, and any optionality from food delivery/Joybuy/Ceconomy. This is rational only if food delivery losses are permanent and expanding — which contradicts both management guidance and regulatory trajectory (SAMR intervention in Aug 2025).

---

## METHOD 6: PE / LBO FLOOR

### Entry Assumptions

- Entry EV: RMB 162B (current RMB 141B + 15% premium)
- Debt: RMB 128B (2.0x normalized EBITDA)
- Equity invested: RMB 34B

### 5-Year Projection (RMB Billions)

| Year | Revenue | FCF | Cumulative FCF |
|------|---------|-----|----------------|
| 1 | 1,401 | 28.0 | 28.0 |
| 2 | 1,485 | 44.5 | 72.6 |
| 3 | 1,574 | 55.1 | 127.6 |
| 4 | 1,653 | 66.1 | 193.7 |
| 5 | 1,735 | 72.9 | 266.6 |

### Exit Assumptions

- Exit multiple: 0.30x NTM Revenue (vs. ~0.11x entry)
- Exit EV: RMB 547B
- Equity at exit: RMB 724B
- **MOIC: 21.3x | Implied IRR: 84%**

### Floor Price (20% IRR Target)

- Required MOIC: 2.49x over 5 years
- Max entry EV: RMB 419B
- **Max entry price for 20% IRR: HK$206**
- Current price: HK$112
- **Current price is 46% BELOW the PE floor**

**Reality check:** A full buyout is structurally impossible (see M&A section). However, the PE math confirms that current pricing offers extraordinary return potential even under conservative assumptions. A PE buyer could pay almost double the current price and still achieve 20% annualized returns. **Confidence: MEDIUM-LOW (theoretical).**

---

## TRIANGULATION & FINAL OUTPUT

### DELIVERABLE 1: PRICE TARGET RANGE & CONVICTION SCORE

```
━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━
TICKER: 9618.HK (JD.com)
CURRENT PRICE: HK$112 per ordinary share (~US$28.8/ADS)
ANALYSIS DATE: April 4, 2026

METHOD RESULTS:
| Method          | Bear     | Base     | Bull     | Weight | Confidence |
|-----------------|----------|----------|----------|--------|------------|
| Reverse DCF     | —        | Mkt implies <0% CAGR vs 6-8% cons. | — | — | HIGH |
| Forward DCF     | HK$175   | HK$324   | HK$501   | 25%    | MEDIUM     |
| Trading Comps   | HK$140   | HK$203   | HK$260   | 35%    | HIGH       |
| M&A Comps       | HK$125   | HK$161   | HK$196   | 5%     | LOW        |
| Sum-of-Parts    | HK$160   | HK$205   | HK$280   | 25%    | HIGH       |
| PE/LBO Floor    | HK$206   | —        | —        | 10%    | MED-LOW    |

TRIANGULATED PRICE TARGET:
  Bear case:  HK$151 (+35% upside)
  Base case:  HK$232 (+107% upside)
  Bull case:  HK$301 (+169% upside)

  Base case in USD/ADS: ~US$59.6/ADS (vs. current ~US$28.8)

CONVICTION SCORE: 4 / 5

CONVICTION RATIONALE: All six valuation methods converge on significant
undervaluation — the stock offers upside even in the bear case. The core
JD Retail business alone justifies a price well above HK$112, with the
market assigning near-zero or negative value to the logistics franchise,
net cash surplus, and food delivery optionality. Conviction is capped at
4/5 (not 5/5) due to: (1) food delivery cash burn trajectory uncertainty
— management says 2025 was peak investment, but this is contingent on
competitive rationalization; (2) European expansion (Joybuy + Ceconomy)
introduces new execution risk with no track record; (3) VIE/geopolitical
discount may persist or widen under the current political environment;
(4) catalyst timing uncertainty — the market may take 12-18 months to
reprice even if fundamentals improve as expected.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### Weighting Rationale

| Method | Weight | Rationale |
|--------|--------|-----------|
| Forward DCF | 25% | FCF trajectory highly uncertain; food delivery losses cloud near-term. Terminal value sensitive to margin assumptions. Reduced from typical 35-45%. |
| Trading Comps | 35% | Best calibrated method. Well-defined peer set. P/E and EV/Revenue both informative. Highest weight. |
| M&A Comps | 5% | Minimal weight. No comparable-scale transactions. JD is un-acquirable. Theoretical only. |
| Sum-of-Parts | 25% | Highly informative — isolates the value destruction from food delivery and reveals hidden value in JD Retail. Elevated weight. |
| PE/LBO Floor | 10% | Confirms deep value but impractical for execution. Floor reference. |

---

### DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━
TICKER: 9618.HK (also JD on NASDAQ)
COMPANY: JD.com, Inc.
SECTOR: Chinese Internet / E-commerce (1P)
VALUATION DATE: April 4, 2026

PRICE TARGET: HK$232 base case (range: HK$151 bear — HK$301 bull)
CURRENT PRICE: HK$112
UPSIDE TO BASE: +107%
CONVICTION: 4/5

NOTE ON OPTIONS INSTRUMENT: JD trades as ordinary shares on HKEX
(9618.HK) and as ADSs on NASDAQ (JD). US-listed options on JD ADSs
(~US$28.8/ADS) are more liquid. Base case in ADS terms: ~US$60/ADS.
Bear case: ~US$39/ADS. The handoff below is denominated in USD/ADS
for options execution purposes.

WHEEL STRATEGY IMPLICATIONS:

- SELL PUTS: YES
  Rationale: Stock is 107% below base case PT with 35% upside even
  in the bear case. Net cash of US$21.6B (52% of market cap) provides
  an extraordinary downside floor. Risk/reward is highly favorable for
  put-selling at current levels.
  Suggested strike zone: $22-25/ADS
    → $22 = ~HK$86 per ordinary share (23% below current; below net
      cash per share of ~HK$55 + minimal operating value)
    → $25 = ~HK$98 (12% below current; approaching bear case floor)
  Avoid puts above: $30/ADS (above current price; no margin of safety)

- COVERED CALLS (if assigned):
  Cost basis assumption: $23-25/ADS (put strike)
  Minimum call strike: $23-25 (cost basis floor)
  Suggested call strike zone: $35-45/ADS
    → This captures a meaningful portion of the base case upside
      without capping below the $60 base case target
  Do NOT sell calls above: $55/ADS (approaching bull case)

- CONCENTRATED LONG CANDIDATE: YES
  Rationale: Conviction ≥ 4/5 AND upside to base case ≥ 30% (107%).
  Both thresholds met with substantial margin.
  Position sizing note: At 4/5 conviction and 107% base case upside,
  a Kelly-informed framework suggests 15-25% of portfolio allocation
  is mathematically justified. In practice, China single-stock risk
  warrants a cap of 8-12% of portfolio. The net cash position
  (52% of market cap) provides balance-sheet downside protection that
  is rare for a concentrated long.

KEY DATES TO AVOID (do not initiate options positions around):
- May 12, 2026: Q1 2026 earnings (first food delivery loss trajectory
  data — THE key catalyst for re-rating)
- Q2-Q3 2026: Ceconomy deal closure (Austrian FDI approval pending)
- June 2026: 618 Shopping Festival (volume/user engagement data)
- August 2026: Q2 2026 earnings (second food delivery data point)
- November 2026: Singles Day / 11.11 festival
- June 2029: US$2.0B convertible notes maturity

SECTOR CONTEXT:
- Sector score from analysis: 16/25 (WATCHLIST)
- Relative ranking in sector: #4 of 7 internet conglomerates
- Sector-level risk flags:
  (1) Food delivery war (~RMB 100B combined industry losses in 2025);
      SAMR regulatory intervention is the key catalyst for margin recovery
  (2) VIE/geopolitical discount — 30-50% vs. US peers
  (3) Chinese macro weakness — consumer spending subdued
  (4) JD-specific: European expansion execution risk (Joybuy + Ceconomy)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## WHAT MAKES THIS VALUATION DIFFERENT

JD.com presents the most extreme valuation anomaly in the Chinese internet pipeline to date. The key insight is that the market is treating a **temporary, management-guided, regulatory-incentivized reduction in food delivery spending** as if it were a **permanent structural impairment** to the business. At 0.11x EV/Revenue — the cheapest multiple in the entire 53-ticker Chinese tech universe — the stock prices in no growth, no margin recovery, and no value for RMB 151B in net cash beyond a liquid asset floor.

The analogy is Amazon in 2014-2015, when heavy investment in AWS, Prime, and logistics suppressed reported profitability and the market assigned a low multiple to the retail business. The difference is that JD's investment cycle is shorter and more visible (food delivery), the competitive dynamics are being actively regulated by SAMR, and the balance sheet provides a structural floor that Amazon never had.

The bear case risk is real: if food delivery losses persist at RMB 40B+ annually for multiple years, the net cash position erodes and the investment thesis collapses. But this requires competitive escalation in direct defiance of regulatory guidance — a scenario that, while possible, contradicts the revealed actions of all three players (Meituan, JD, Alibaba all publicly pledged subsidy rationalization in August 2025).

Q1 2026 earnings on **May 12, 2026** will be the decisive catalyst. If food delivery losses are materially below the Q4 2025 run rate (RMB ~14.8B/quarter), the re-rating begins.

---

*Valuation compiled April 4, 2026. All six methods run programmatically. Data sourced from V1 research dossier (SEC 6-K filings, earnings releases, IR materials) and 53-ticker sector handoff. Exchange rates: CNY/USD 7.25, HKD/USD 7.78.*
