# V1 VALUATION REPORT — NU HOLDINGS LTD. (NYSE: NU)

**Analysis Date:** April 4, 2026
**Current Price:** $14.21
**Analyst:** V1 Stock Valuation Engine (Buy-Side Equity)

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency — ✅ GOOD (with caveats)

| Method | Data Available? | Notes |
|--------|:-:|-------|
| Reverse DCF | ✅ | 12 quarters of revenue + NI history, consensus estimates through FY2028 |
| Forward DCF | ✅ | Full P&L, balance sheet, consensus projections. Adapted for bank model (NI replaces FCF) |
| Trading Comps | ✅ | Sector handoff provides 8-company peer set with multiples |
| M&A Comps | ⚠️ | Limited direct comps for $70B+ LatAm neobanks. Using broad fintech M&A and bank transaction data |
| Sum-of-Parts | ⚠️ | NU does **not disclose segment-level revenue** — geographic breakdown is estimated (~85% Brazil, ~10% Mexico, ~4% Colombia). Weight reduced in triangulation |
| PE/LBO Floor | ✅ | NI projections and exit multiples available. Company too large for LBO; growth equity model used |

**Bank model adaptation note:** NU is a deposit-funded financial institution under IFRS. Traditional FCF metrics are not comparable to non-financial companies. All DCF models use **net income** as the primary cash flow proxy, which is standard for bank valuation. The bank's GAAP CFO ($3.5B FY2025) includes deposit inflows and credit portfolio changes within operating activities.

### Check 2: Fiscal Year Alignment — ✅ CONFIRMED

Nu Holdings fiscal year ends **December 31** (calendar year). All peer comparisons are aligned to calendar Q4 2025 reporting. IFRS reporting in USD. The "Managerial P&L" framework introduced in Q4 2025 reclassifies certain items (adds ~3-4% to top-line vs. IFRS) but net income is identical under both frameworks. **This analysis uses Managerial Revenue ($16.3B) for consistency with management's primary metric.**

### Check 3: Share Count Reconciliation — ✅ CONFIRMED

| Metric | Shares (M) | Source |
|--------|---:|--------|
| Basic Shares Outstanding (Dec 31, 2025) | 4,839 | 20-F Filing |
| Diluted Shares (FY2025 weighted avg, treasury method) | 4,907 | 20-F Filing |
| Fully Diluted (incl. all options, RSUs, if-converted) | 4,990 | 20-F + Module 7 |

**Using fully diluted shares (4,990M) for all per-share calculations.** This is conservative and appropriate given NU's active equity compensation program. No convertible notes or hybrid instruments outstanding. Dilution rate is running at <0.6% annually — extremely low for a high-growth company.

**Dual-class structure:** David Vélez controls ~76% of voting power via Class B shares (20 votes each). This is relevant for M&A analysis — effective takeover defense.

### Check 4: SBC Materiality Assessment — ✅ NOT MATERIAL

| Metric | Value |
|--------|-------|
| FY2025 SBC Expense | $272M |
| SBC as % of Revenue (Managerial) | **1.67%** |
| SBC as % of Revenue (IFRS) | 1.72% |
| Trend | Declining: 2.88% (FY23) → 2.36% (FY24) → 1.67% (FY25) |

**SBC is well below the 15% materiality threshold.** No dual-track FCF/FCF-ex-SBC analysis is required. This is in stark contrast to the cybersecurity sector (ZS ~27%, CRWD ~23%, NET ~23%, RBRK ~25%) and is a structural positive for NU's valuation quality. Revenue scale is growing faster than equity compensation.

---

## KEY METRICS DASHBOARD

| Metric | Value | Context |
|--------|-------|---------|
| Market Cap (fully diluted) | $70.9B | |
| Enterprise Value | ~$61.1B | MC - net cash ($9.8B) |
| FY2025 Revenue (Managerial) | $16.3B | +45% YoY (FXN) |
| FY2025 Net Income | $2.87B | +46% YoY |
| FY2025 EPS (Diluted) | $0.58 | |
| ROE (Q4 2025) | 33% | Adjusted: 35% |
| Efficiency Ratio | 19.9% | Record low; ~3x better than incumbents |
| Customers | 131M | 83% activity rate |
| ARPAC (Monthly) | $15.00 | +27% YoY; mature cohorts at ~$27 |
| Credit Portfolio | $32.7B | +40% YoY FXN |
| Deposits | $41.9B | +29% YoY |
| Book Value/Share | $2.27 | P/BV = 6.3x |
| Tangible Book Value/Share | $2.07 | P/TBV = 6.9x |
| NTM P/E | 15.4x | FY26E EPS $0.92 |
| EV/NTM Revenue | 2.9x | NTM Rev ~$21B |
| TTM P/E | 24.5x | |
| SBC % of Revenue | 1.67% | ✅ Not material |

---

## METHOD 1: REVERSE DCF (Bank-Adapted)

### Purpose
What earnings growth rate is the current market price implying? This is the primary mispricing detection tool.

### Methodology
Instead of solving for revenue CAGR via FCF (standard for SaaS), this bank-adapted reverse DCF solves for the **net income CAGR** that justifies the current market capitalization. The terminal state is defined by a P/E multiple rather than a FCF margin.

### Assumptions
- Current Market Cap: $70.9B
- FY2025 Net Income: $2.87B
- Terminal state in Year 10: company reaches mature-bank valuation
- Cost of Equity (base): 12% (risk-free 4.5% + 1.4 beta × 5.5% ERP; LatAm premium embedded)
- Terminal P/E: 13x (mature high-quality EM bank)
- Terminal Growth: 3% (embedded in P/E, not modeled separately)

### Results

```
REVERSE DCF RESULTS
━━━━━━━━━━━━━━━━━━
Current Market Cap: $70.9B
FY2025 Net Income: $2.87B
Current TTM P/E: 24.7x

SENSITIVITY TABLE — Implied 10-Year NI CAGR:

          CoE →      10%       11%       12%       13%
Terminal P/E ↓
  10x              13.0%     14.0%     15.0%     16.1%
  12x              11.6%     12.6%     13.6%     14.6%
  14x              10.4%     11.4%     12.4%     13.4%
  16x               9.3%     10.3%     11.3%     12.3%

BASE CASE (12% CoE, 13x Terminal P/E):
  Implied NI CAGR: ~13%
  Consensus FY25-28 EPS CAGR: ~34%
  Consensus FY25-27 Revenue CAGR: ~26%
  Management long-term ROE guidance: 25%+ (floor)
```

### GAP ANALYSIS

**The market is pricing in ~13% earnings CAGR over 10 years — roughly one-third of the consensus near-term growth rate.** This implies the market expects either: (a) a dramatic deceleration in growth far beyond consensus, (b) a material FX-driven haircut to USD earnings, or (c) a structural compression in profitability. Even in the most conservative scenario (13% CoE, 10x terminal P/E), the implied growth is only 16.1%.

At 13% NI CAGR for 10 years, NU would earn $9.7B in Year 10 on ~$49B in revenue (assuming 20% NI margin). This would represent a $49B revenue company growing at low-teens from 131M+ customers — a plausible but highly conservative scenario that ignores Mexico acceleration, US charter, and ARPAC expansion.

**Conclusion: The market is materially under-pricing NU's growth trajectory relative to consensus and management signals.** The implied growth gap (13% priced vs. 26-34% consensus) is among the widest we've seen in a high-quality franchise.

---

## METHOD 2: FORWARD DCF / EARNINGS DISCOUNT MODEL (3-Scenario)

### Methodology
Standard SaaS DCF is not appropriate for bank stocks. This model projects revenue → applies net income margins → discounts earnings at cost of equity → adds terminal value at a P/E multiple. This is the standard bank earnings power valuation approach.

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|---|---|---|---|
| Yr 1-2 Rev CAGR | 33% | 28% | 20% |
| Yr 3-5 Rev CAGR | 22% | 19% | 12% |
| Yr 6-7 Rev CAGR | 17% | 13% | 7% |
| Terminal NI Margin | 23% | 20% | 18% |
| Terminal P/E | 16x | 14x | 11x |
| Cost of Equity | 11% | 12% | 13% |

**What must go right (Bull):** Mexico reaches profitability inflection in 2027, US charter opens successfully by mid-2027, Selic cuts boost NIM, ARPAC converges toward $27 mature cohort level across the base, credit quality remains stable, BRL appreciates modestly.

**Most likely path (Base):** Brazil execution continues with gradual ARPAC expansion, Mexico grows rapidly but takes longer to reach profitability, US charter is early-stage with minimal revenue contribution by Year 7, Selic cuts offset by portfolio yield compression, credit quality stable.

**What could go wrong (Bear):** BRL depreciates 15-20% vs. USD over 2-3 years, Brazil consumer credit cycle deteriorates (unemployment spike), Mexico growth stalls due to regulatory or competitive pressure, Brazil Selic stays elevated longer than expected, competitive intensity from Itaú digital/MercadoLibre/Amazon erodes market position.

### BASE CASE Revenue & Earnings Projection

| Year | Revenue ($M) | YoY Growth | NI Margin | NI ($M) | Disc Factor | PV of NI |
|---|---:|---:|---:|---:|---:|---:|
| 1 | 21,216 | 30.0% | 18.0% | 3,819 | 0.8929 | 3,410 |
| 2 | 26,520 | 25.0% | 19.0% | 5,039 | 0.7972 | 4,017 |
| 3 | 32,354 | 22.0% | 19.0% | 6,147 | 0.7118 | 4,376 |
| 4 | 38,178 | 18.0% | 20.0% | 7,636 | 0.6355 | 4,853 |
| 5 | 44,287 | 16.0% | 20.0% | 8,857 | 0.5674 | 5,026 |
| 6 | 50,487 | 14.0% | 20.0% | 10,097 | 0.5066 | 5,116 |
| 7 | 56,545 | 12.0% | 20.0% | 11,309 | 0.4523 | 5,116 |
| TV | — | — | — | 11,648 | — | 73,766 |

### Valuation Summary

| | Bull | Base | Bear |
|---|---:|---:|---:|
| PV of Earnings | $42.9B | $31.9B | $21.4B |
| PV of Terminal Value | $129.9B | $73.8B | $33.0B |
| Total Equity Value | $172.7B | $105.7B | $54.4B |
| Per Share | **$34.62** | **$21.18** | **$10.90** |
| Upside/(Downside) | +144% | +49% | -23% |
| TV as % of Total | 75% ⚠️ | 70% | 61% |

**⚠️ Bull case terminal value exceeds 70% — that scenario is speculative and dependent on long-term assumptions.**

### Round-Trip Check (Base Case)
- Implied P/NTM Revenue at base case valuation: 4.0x (vs. current 3.4x) — reasonable for a 25%+ grower with 33% ROE
- Implied NTM P/E at base case: 21x (vs. current 15.4x) — reasonable premium for elite bank franchise
- **Round-trip check passes.** No contortion of assumptions needed.

---

## METHOD 3: TRADING COMPS

### Peer Set

| Company | Rev Growth | NI Margin | ROE | P/Rev | NTM P/E | EV/NTM Rev | Growth-Adj |
|---|---:|---:|---:|---:|---:|---:|---:|
| **★ NU** | **45%** | **18.2%** | **33%** | 4.3x | 15.4x | 2.9x | **0.10** |
| SOFI | 37% | 17.0% | 15% | 4.7x | 28.1x | 3.4x | 0.13 |
| MELI | 45% | 6.4% | 25% | 2.9x | 20.0x | 5.0x | 0.07 |
| SE | 38% | 6.9% | 12% | 1.4x | 17.3x | 2.0x | 0.04 |
| SQ/XYZ | 24% | 18.0% | 18% | 1.7x | 15.6x | 3.5x | 0.07 |
| HOOD | 27% | 42.0% | 25% | 8.9x | 25.0x | 8.0x | 0.33 |
| LC | 23% | 16.0% | 12% | 2.2x | 7.9x | 1.5x | 0.10 |
| CHYM | 29% | Negative | Neg. | 3.4x | N/A | 2.9x | 0.12 |

### NU Positioning
- **Growth rank:** #1 of 8 (tied with MELI at 45%)
- **Profitability rank:** #1 NI margin among neobanks (18.2%), #1 ROE (33%)
- **Current multiple vs. peer median:** Significant discount — NU's 2.9x EV/NTM Rev is below the median of ~3.4x despite being the highest-quality franchise

### Fair Value Estimate

**EV/Revenue Method:**
- NU's combination of 45% growth, 18% NI margin, and 33% ROE is best-in-class in the peer set
- The LatAm/FX discount is real but appears excessive given the franchise quality
- Fair EV/NTM Revenue: 3.5x (range: 3.0x — 4.0x)
- Implied share price: **$16.70**
- Upside: +18%

**P/E Method:**
- Among profitable, high-growth fintech peers, NTM P/E ranges from 15-28x
- NU at 15.4x is at the bottom despite having the best growth + ROE combination
- Fair NTM P/E: 20x (range: 18x — 25x)
- Implied share price: **$18.40**
- Upside: +29%

**Blended Comps Value: $17.55 (+23%)**

The comps-based value is the most conservative of the methods because it anchors to current sector multiples, which are themselves compressed ~25-30% YTD across fintech. If sector multiples normalize, the comps-implied value rises proportionally.

---

## METHOD 4: PRECEDENT M&A COMPS

### Comparable Transactions

| Date | Target | Acquirer | EV ($B) | EV/Rev | P/TBV | Target Growth |
|---|---|---|---:|---|---|---|
| Feb 2024 | Discover (DFS) | Capital One | 35.3 | 1.4x | 1.9x | ~8% |
| Q4 2024 | Nuvei | Advent Intl (PE) | 6.3 | 5.4x | N/A | ~15% |
| Jan 2026 | Brex | Capital One | 5.15 | ~12x | N/A | ~35% |
| Nov 2025 | GoCardless | Mollie | 1.5 | ~5x | N/A | ~20% |
| 2025 Pvt | Revolut | Private Val | 75.0 | ~19x | N/A | 72% |
| Jun 2025 | Chime (IPO) | Public Market | 7.4 | ~3.4x | N/A | 29% |

### Takeout Valuation
- Applicable multiple range: 5x — 10x NTM Revenue
- NTM Revenue: $21B
- Base case EV at 7x: $147B
- After 25% control premium discount: $110B
- **Implied share price: $24.06** (+69%)

### Probability Assessment
A takeover of NU is **highly unlikely** for three reasons: (1) at ~$71B market cap, NU is too large for most strategic acquirers or PE firms; (2) the dual-class structure gives David Vélez 76% voting control, making hostile acquisition impossible; (3) management's strategic vision (US expansion, platform consolidation) suggests no interest in selling. The M&A analysis is most useful as a theoretical ceiling / validation that the franchise value exceeds the current stock price. On a P/TBV basis, bank M&A would imply 2.0-2.5x TBV ($4.13-$5.17) — well below the current price, but this reflects NU's premium growth profile that standard bank M&A multiples don't capture.

---

## METHOD 5: SUM-OF-PARTS

### Segment Breakdown (Estimated — NU does not disclose segment revenue)

| Segment | FY25 Rev ($M) | NTM Rev ($M) | Growth | Comparable | Multiple | Implied EV ($M) |
|---|---:|---:|---|---|---:|---:|
| Brazil | 14,035 | 16,800 | ~25% | Mature EM neobank | 3.5x | 58,800 |
| Mexico | 1,632 | 2,940 | ~80% | High-growth neobank | 6.0x | 17,640 |
| Colombia | 653 | 1,260 | ~50% | Early-stage neobank | 4.0x | 5,040 |
| US Charter | $0 | $0 | Pre-revenue | Optionality | — | 0 |
| **Total** | **16,320** | **21,000** | | | | **81,480** |

- Total EV: $81.5B
- Plus Net Cash: $9.8B
- Equity Value: $91.3B
- **Per Share: $18.30** (+29%)

### Hidden Value Flags

**US charter optionality is valued at $0 in base case.** The OCC conditional approval (January 2026) with Cristina Junqueira as CEO, Roberto Campos Neto (former BCB governor) as board chair, and a July 2027 opening deadline represents the most credible neobank US entry attempt to date. If NU captures even 1-5M US customers at $500+ ARPU (well below US bank industry average of $350/year but above NU's current $180), the US segment alone could be worth $5-15B. In the bull SoP including $5B US optionality and higher Mexico multiples, the implied value rises to **$22.41 per share**.

**Mexico is potentially undervalued.** At 14-15M customers growing 80%+ YoY with a banking license just secured, Mexico is approaching the inflection point where profitability becomes visible. CEO Vélez stated Mexico could already be profitable "at the push of a button" — the company is deliberately investing. If Mexico reaches profitability in 2027 at a similar multiple to Brazil's early profitable years, the segment value could double.

---

## METHOD 6: PE / LBO FLOOR (Growth Equity Model)

### Why Growth Equity, Not LBO
NU is a ~$71B market cap company with a deposit-funded bank model — traditional leveraged buyout is neither feasible nor appropriate. Instead, this analysis uses a **growth equity framework**: all-equity entry, targeting 20-25% IRR over 5 years, modeling earnings trajectory and exit valuation.

### 5-Year Net Income Projection

| Year | NI Growth | Net Income ($M) | Cumulative ($M) |
|---:|---:|---:|---:|
| 1 | 55% | 4,452 | 4,452 |
| 2 | 38% | 6,143 | 10,595 |
| 3 | 25% | 7,679 | 18,274 |
| 4 | 20% | 9,215 | 27,489 |
| 5 | 15% | 10,597 | 38,086 |

### Exit Assumptions
- Exit P/E: 14x (mature high-growth bank)
- Year 5 Net Income: $10.6B
- Exit Equity Value: $148.4B
- Cumulative Earnings: $38.1B

### Floor Price

| Target IRR | Max Entry (per share) | vs. Current |
|---:|---:|---:|
| 20% | **$15.02** | +6% above current |
| 25% | **$12.24** | -14% below current |

**The growth equity floor at 20% IRR ($15.02) is almost exactly at the current price** — meaning a sophisticated growth equity investor could buy NU today and achieve ~20% IRR if consensus earnings materialize. At 25% IRR, the floor is $12.24 — 14% below current price. This confirms the stock is priced attractively for long-term holders.

### P/TBV Downside Anchor
- Current TBV: $2.07/share
- At 2.0x TBV (distressed bank floor): $4.13
- At 3.0x TBV: $6.20
- Current P/TBV: 6.9x

The high P/TBV reflects NU's extraordinary ROE (33%) — the TBV floor is academic and would only apply in a severe financial distress scenario. For context, traditional Brazilian banks trade at 1.0-1.5x TBV with 15-20% ROE.

---

## TRIANGULATION & DELIVERABLE 1: PRICE TARGET & CONVICTION

```
━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
TICKER: NU
COMPANY: Nu Holdings Ltd.
CURRENT PRICE: $14.21
ANALYSIS DATE: April 4, 2026

METHOD RESULTS:
Method              Bear      Base      Bull    Weight  Confidence
────────────────────────────────────────────────────────────────────
Reverse DCF          —     Implied 13% NI CAGR   —       —      —
Forward DCF        $10.90    $21.18    $34.62    40%      H
Trading Comps        —       $17.55      —       25%     M-H
M&A Comps            —       $24.06      —       10%      L
Sum-of-Parts         —       $18.30    $22.41    15%      M
PE/LBO Floor       $12.24    $15.02      —       10%      M

TRIANGULATED PRICE TARGET:
  ► Bear case:  $10.90  (-23%)
  ► Base case:  $19.51  (+37%)
  ► Bull case:  $28.24  (+99%)

CONVICTION SCORE: 4 / 5

CONVICTION RATIONALE:
Most methods converge on substantial upside (30-60% to base case) from a
stock that has de-rated primarily on FX/macro concerns rather than
fundamental deterioration. The reverse DCF shows the market is pricing in
only ~13% earnings CAGR — well below the ~34% consensus — implying
meaningful mispricing. The LatAm FX risk is real and unhedgeable, which
prevents a 5/5 score, but the quality of the franchise (33% ROE, 19.9%
efficiency ratio, 131M customers, declining SBC at 1.67%) creates a wide
margin of safety. Four of six methods produce base cases above $17. The
growth equity floor at 20% IRR ($15.02) is essentially at the current
price — confirming the market is pricing NU for a return that barely
exceeds its cost of equity, despite elite fundamentals.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### Weighting Rationale
- **Forward DCF (40%):** Highest weight. NU has predictable, recurring revenue (interest income + fees from 131M customers with 83% activity rate) and a clear margin trajectory. 12 quarters of data support the model.
- **Trading Comps (25%):** Well-defined peer set across fintech neobanks and LatAm platforms. Multiple methods (P/E and EV/Rev) converge. Sector multiples are themselves compressed, making this a conservative anchor.
- **Sum-of-Parts (15%):** Provides geographic decomposition but relies on estimated segment revenue (NU doesn't disclose). Useful for sizing Mexico and US optionality.
- **M&A Comps (10%):** Low weight due to impracticality of acquisition. Useful as theoretical ceiling only.
- **PE/LBO Floor (10%):** Confirms current price is near the 20% IRR floor. Downside anchor.

---

## DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━━━━━━━━━━━━━━━━━━━━
TICKER: NU
COMPANY: Nu Holdings Ltd.
SECTOR: Consumer Fintech / LatAm Neobanking
VALUATION DATE: April 4, 2026

PRICE TARGET: $19.51 base case (range: $10.90 bear — $28.24 bull)
CURRENT PRICE: $14.21
UPSIDE TO BASE: +37%
CONVICTION: 4/5

WHEEL STRATEGY IMPLICATIONS:

- SELL PUTS: YES
  Rationale: Stock is 37% below base case PT. Selling puts at or near
  bear case levels offers favorable risk/reward backed by an elite
  franchise (33% ROE, 19.9% efficiency ratio, 131M customers). This is
  not a speculative growth name — NU earned $2.87B in FY2025 net income.
  The growth equity model confirms ~20% IRR is achievable at current
  price levels.
  Suggested strike zone: $11.50 — $13.00 (at or below bear case)
  Avoid puts above: $15.00 (limited premium above current price)

- COVERED CALLS (if assigned): YES
  Cost basis assumption: $12.00–$13.00 (put strike zone)
  Minimum call strike: $12.00–$13.00 (cost basis floor per cc_min_strike_pct=1.0)
  Suggested call strike zone: $16.00 — $18.00 (between cost basis and base PT)
  Do NOT sell calls above: $19.50 (approaching base case — let it run)

- CONCENTRATED LONG CANDIDATE: YES (CONDITIONAL)
  Rationale: Conviction 4/5 with 37% upside to base case. The LatAm
  FX risk creates volatility that rewards patient, long-term capital.
  Position sizing note: 3-5% portfolio weight recommended. FX tail risk
  limits sizing below full Kelly despite high conviction. Consider
  scaling in over 2-3 tranches around Q1 2026 earnings (May 14).
  BRL/USD at ~5.38 with forecasts of ~5.50 by year-end — a further
  2-3% FX headwind is in the consensus base case.

KEY DATES TO AVOID (earnings, catalysts):
  - May 14, 2026: Q1 2026 earnings (expected, post-market)
  - ~H1 2026: Mexico full operational banking approval (binary catalyst)
  - ~H2 2026: Brazil SCD-to-SFI banking license conversion
  - ~Jan 2027: US charter full capitalization deadline
  - ~Jul 2027: US bank opening deadline

SECTOR CONTEXT:
  - Sector score from analysis: 23/25 (highest in universe of 12 names)
  - Relative ranking: #1 of 12 companies analyzed
  - Sector-level risk flags:
    → LatAm FX/macro (BRL at ~5.38/USD, volatile)
    → Brazil Selic at 14.75% (cutting cycle beginning — net positive)
    → Consumer credit cycle risk if LatAm macro deteriorates
    → Competitive intensity: Itaú digital transformation, MercadoLibre
      fintech, Amazon-Nubank partnership dynamics
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## APPENDIX: KEY ANALYTICAL OBSERVATIONS

### 1. Why NU is different from previous cybersecurity valuations

The four prior V1 valuations (ZS, NET, CRWD, RBRK) were all SaaS/subscription models where SBC materiality was a dominant analytical theme (15-27% of revenue). NU's bank model fundamentally differs: SBC at 1.67% of revenue is immaterial, net income is real cash earnings (not obscured by SBC), and the primary valuation metrics are P/E and P/TBV rather than EV/Revenue. NU is also already highly profitable (33% ROE, $2.87B net income) vs. the cybersecurity names where profitability was aspirational.

### 2. The FX discount is the core analytical tension

NU generates ~85-90% of revenue in BRL but reports in USD. The stock's decline from $17+ to $14 largely reflects BRL weakness, not fundamental deterioration. Each 10% BRL depreciation reduces reported USD revenue by ~8-9%. The market appears to be applying a permanent discount for this structural exposure, but the Selic cutting cycle (first cut March 2026, consensus to ~11.5-12.25% by year-end) could strengthen BRL as carry trade dynamics shift. This FX tension is why conviction is 4/5 rather than 5/5 — the fundamentals deserve a 5, but the unhedgeable FX risk constrains the score.

### 3. The ARPAC trajectory is the embedded growth engine

NU's current ARPAC of $15/month vs. mature cohort ARPAC of $27/month represents an embedded 80% revenue upside from the existing customer base, with zero marginal customer acquisition cost. This is analogous to a SaaS company's net revenue retention dynamic — Nu's "NRR equivalent" is running well above 120%. As the 118M+ existing customers age into higher ARPAC cohorts through deeper product adoption (credit → personal loans → insurance → investments), revenue growth can persist even if net new customer adds decelerate to zero.

### 4. US charter is a free option

At $14.21, the market is pricing the US charter at approximately $0 of value. The conditional OCC approval, appointment of a former BCB governor to the US board, and $3.0B unrestricted parent cash available for capitalization suggest this is a credible venture — not aspirational. Even a modest success (2-5M US customers over 5-7 years) would represent $3-10B in value creation. The Inter Miami stadium naming rights (opening April 4, 2026) and Mercedes F1 partnership signal serious brand-building commitment.

---

*Report generated April 4, 2026. All figures from R1 Company Research Dossier, R2 Standardized Metrics Table, R3 Catalyst Sweep, and Consumer Fintech Sector Analysis. Fully diluted share count of 4,990M used for all per-share calculations.*
