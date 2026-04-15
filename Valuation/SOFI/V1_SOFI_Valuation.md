# V1 STOCK VALUATION: SoFi Technologies (SOFI)

**Analyst Date:** April 4, 2026 | **Current Price:** $15.79 | **Sector Score:** 19/25 (PASS)

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency
All six valuation methods have sufficient data. R1 provides 12 quarters of P&L history, a detailed balance sheet, segment breakdown, consensus estimates through FY2028, and a fully reconciled share count. The sector handoff provides calibrated peer multiples and M&A transaction data. **One critical modeling note:** SoFi is a bank holding company. GAAP CFO includes $36.4B in loan originations and is deeply negative — it does not reflect operating cash generation. All "FCF" references in this report use Net Income or EBITDA-minus-CapEx as proxies, consistent with bank valuation methodology.

### Check 2: Fiscal Year Alignment
✓ SoFi's fiscal year ends December 31. All peer data from R2 is Q4 2025 / December 2025. No alignment issues. Affirm's fiscal year ends June 30 — its FQ2'26 data (Dec 2025) is used for comparability.

### Check 3: Share Count Reconciliation

| Component | Shares (M) |
|-----------|:----------:|
| Basic outstanding (Dec 31, 2025) | 1,271 |
| Diluted weighted avg (Q4 2025) | 1,346 |
| If-converted: 2029 Notes ($862.5M at $9.45) | ~91 |
| If-converted: 2026 Notes (~$530M at $22.41) | ~23 |
| RSUs/PSUs/Options (estimated) | ~30–40 |
| **Fully diluted (all-in)** | **~1,390** |

**Using 1,390M** for all per-share calculations. The 2029 Notes are in-the-money at $15.79 (above the $14.54 capped call ceiling, contributing dilution). The 2026 Notes at $22.41 conversion are out-of-the-money and likely to be refinanced at maturity (October 15, 2026). Annual dilution was 16% in FY2025 — the single largest investor concern alongside Muddy Waters.

### Check 4: SBC Materiality Assessment
SBC: $262M / $3,613M revenue = **7.3%**. Below the 15% threshold — dual-track FCF valuation not required. SBC has compressed from 13.1% (FY2023) to 7.3% (FY2025) as revenue scales, a positive trajectory. In per-share terms, SBC is $0.19/share, consuming 38% of FY2025 adjusted EPS of $0.39 — still material for earnings quality but not the "SaaS SBC problem" seen in cybersecurity names.

---

## CAPITAL STRUCTURE SUMMARY

| Metric | Value |
|--------|------:|
| Market Cap (fully diluted) | $21,948M |
| Cash & Equivalents | $4,929M |
| Total Debt | $1,815M |
| Net Cash | $3,114M |
| **Enterprise Value** | **$18,834M** |
| TBV | $8,908M ($6.41/share) |
| Equity | $10,489M ($7.55/share) |
| P/TBV | 2.46x |
| EV/NTM Revenue ($4.77B) | 3.95x |
| P/E FY2026E ($0.62) | 25.5x |
| P/E FY2027E ($0.84) | 18.8x |
| EV/FY2026E EBITDA ($1.6B) | 11.8x |

---

## VALUATION METHOD 1: REVERSE DCF

**Purpose:** What growth rate is the market pricing in at $15.79?

**Methodology:** Start from current EV of $18.8B. Assume terminal state in Year 10: 20% net income margin (mature high-quality bank/fintech), 3% terminal growth, 10% WACC. NI margin ramps linearly from current 13.3% to terminal. Solve for the constant revenue CAGR that equates to current EV.

```
REVERSE DCF RESULTS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Current EV: $18.8B
Assumptions: Terminal NI margin 20%, terminal growth 3%, WACC 10%

Implied revenue CAGR: 11.5%
Current actual revenue growth (FY2025): 35%
Consensus NTM revenue growth: 32%
Management long-term revenue CAGR target: 30% (through 2028)

GAP ANALYSIS:
Market implies 11.5% growth vs. 30% management target
→ Market is pricing in SEVERE DECELERATION to below half of current growth
```

**Sensitivity: Implied Revenue CAGR by WACC and Terminal NI Margin**

| WACC | NI 15% | NI 18% | NI 20% | NI 22% | NI 25% |
|-----:|-------:|-------:|-------:|-------:|-------:|
| 9% | 12.4% | 10.4% | 9.2% | 8.1% | 6.7% |
| **10%** | **14.8%** | **12.7%** | **11.5%** | **10.4%** | **9.0%** |
| 11% | 17.0% | 14.9% | 13.6% | 12.5% | 11.1% |
| 12% | 19.1% | 16.9% | 15.7% | 14.5% | 13.0% |

**Interpretation:** At the base case assumptions (10% WACC, 20% terminal NI margin), the market is pricing SoFi to grow revenue at just 11.5% CAGR over the next decade — roughly one-third of management's stated 30% CAGR target. Even at the most conservative terminal assumptions (15% NI margin, 12% WACC), the implied CAGR is 19.1% — still well below SoFi's guided trajectory. **This is a mispricing signal, conditional on execution continuing at or near current levels.**

The gap is wider than what we saw for the cybersecurity names because consumer fintech stocks are in the deepest valuation trough since 2022, with the median stock down 25–30% YTD despite broadly excellent earnings.

---

## VALUATION METHOD 2: FORWARD DCF (3-SCENARIO)

**Methodology:** Project revenue for 7 years, apply net income margins ramping to terminal, discount at WACC. Terminal value = Year 7 NI × (1 + g) / (WACC − g). Using net income as the FCF proxy (appropriate for bank model where GAAP CFO is distorted by loan origination flows).

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|:-----------|:----:|:----:|:----:|
| Yr 1–2 Rev CAGR | 35% / 30% | 32% / 23% | 28% / 18% |
| Yr 3–5 Rev CAGR | 27% / 24% / 21% | 20% / 18% / 16% | 14% / 12% / 10% |
| Yr 6–7 Rev CAGR | 18% / 15% | 14% / 12% | 8% / 6% |
| Terminal NI Margin | 25% | 20% | 17% |
| Terminal Growth Rate | 3% | 3% | 3% |
| WACC | 10% | 10% | 11% |
| What must go right/wrong | Products/member > 2.5, MW rebutted, LPB scales to $20B+/yr | Consensus execution, moderate NIM compression, steady credit quality | Credit cycle spike (NCO > 5%), MW partially validated, dilution continues |

### Base Case Revenue & Earnings Projection

| Year | Revenue ($M) | YoY Growth | NI Margin | NI ($M) | Disc. Factor | PV of NI |
|------|:--------:|:----------:|:---------:|:-------:|:------------:|:--------:|
| 1 | 4,769 | 32% | 15% | 715 | 0.9091 | 650 |
| 2 | 5,866 | 23% | 17% | 997 | 0.8264 | 824 |
| 3 | 7,039 | 20% | 18% | 1,267 | 0.7513 | 952 |
| 4 | 8,306 | 18% | 19% | 1,578 | 0.6830 | 1,078 |
| 5 | 9,635 | 16% | 20% | 1,927 | 0.6209 | 1,197 |
| 6 | 10,984 | 14% | 20% | 2,197 | 0.5645 | 1,240 |
| 7 | 12,302 | 12% | 20% | 2,460 | 0.5132 | 1,263 |
| Terminal | | | | | | 18,579 |

### Valuation Summary

| | Bull | Base | Bear |
|:--|:----:|:----:|:----:|
| PV of Net Income | $10,460M | $7,204M | $4,777M |
| PV of Terminal Value | $30,950M | $18,579M | $9,250M |
| Enterprise Value | $41,411M | $25,782M | $14,027M |
| Net Cash | $3,114M | $3,114M | $3,114M |
| Equity Value | $44,525M | $28,896M | $17,141M |
| Fully Diluted Shares | 1,390M | 1,390M | 1,390M |
| **Per Share Value** | **$32.03** | **$20.79** | **$12.33** |
| Upside / (Downside) | +103% | +32% | −22% |
| TV as % of Total | 75% ⚠️ | 72% ⚠️ | 66% |

⚠️ **Terminal value exceeds 70% of total in both Bull and Base cases.** This is typical for high-growth companies with margins still ramping — the valuation is driven by the long-term earnings power, not near-term cash flows. This means the DCF is heavily sensitive to terminal margin assumptions. A 2-point swing in terminal NI margin (18% vs. 22%) moves the base case ±$3/share.

**Round-trip check:** Base case EV of $25.8B on NTM revenue of $4.77B implies 5.4x EV/NTM Rev — reasonable for a 30%+ growth fintech bank with expanding margins. Base case P/E on Y1 NI ($715M ÷ 1,390M = $0.51) is ~40x, which is elevated but consistent with a company transitioning from growth to profitability with a 30%+ topline CAGR.

---

## VALUATION METHOD 3: TRADING COMPS

### Peer Set

| Company | EV/NTM Rev | Growth | EBITDA Margin | NI Margin | Growth-Adj Ratio |
|:--------|:----------:|:------:|:-------------:|:---------:|:----------------:|
| NU | 2.75x | 45% | 18% | 18% | 6.11x |
| CHYM | 2.90x | 25% | 10% | neg. | 11.60x |
| LC | 1.50x | 23% | N/A | 16% | 6.52x |
| HOOD | 8.00x | 27% | 60% | 47% | 29.63x |
| SQ | 3.50x | 24% | 33% | 18% | 14.58x |
| AFRM | 3.30x | 30% | 30% | 4% | 11.00x |
| DAVE | 1.20x | 62% | 41% | 40% | 1.94x |
| **SOFI** | **3.95x** | **32%** | **31%** | **13%** | **12.34x** |

### Target Company Positioning
- **Growth rank:** 3 of 7 peers (32%, behind NU 45% and DAVE 62%)
- **Profitability rank:** 2 of 7 on adjusted EBITDA margin (31%)
- **Rule of 40:** 1 of 7 peers (**68** — best in group by a wide margin)
- **Current multiple vs. peer median:** Premium of +40% vs. median 2.83x (ex-HOOD)
- **Growth-adjusted ratio:** 12.34x vs. bank-charter peer median of 6.32x — SoFi trades at a premium to NU/LC

### Fair Value Estimate

**Tier 1 (Bank-charter neobanks — most comparable):** NU at 2.75x with 45% growth and LC at 1.50x with 23% growth. Linear interpolation for SoFi at 32% growth yields 2.01x. Applying a 15% premium for the unique tech platform moat (Galileo) and best-in-class Rule of 40: **2.31x fair EV/NTM.**

**Growth-adjusted median (ex-HOOD):** 8.76x × 32% growth = **2.80x fair EV/NTM.**

**Blended (50/50):** 2.56x EV/NTM → EV of $12.2B → equity of $15.3B → **$11.02/share.**

**P/TBV approach:** For a growing bank with 30%+ revenue growth, 22.8% CET1, and improving ROE, 2.5x TBV is appropriate (LC at ~1.3x with 23% growth, NU ROE 33% with higher multiples). 2.5x × $6.41 = **$16.02/share.**

**Blended (50% EV/Rev + 50% P/TBV):** **$13.52/share** (−14% from current)

**Critical context:** The comps approach yields a below-current-price fair value because the entire consumer fintech sector is in a valuation trough — median stock down 25-30% YTD. Using trough multiples as "fair value" inherently produces conservative estimates. If the sector re-rates to even 3-month-ago levels, the comps-based fair value would be 30-40% higher.

---

## VALUATION METHOD 4: PRECEDENT M&A COMPS

### Comparable Transactions

| Date | Target | Acquiror | EV ($B) | EV/Rev | Growth | Premium |
|:-----|:-------|:---------|:-------:|:------:|:------:|:-------:|
| May 2025 | Discover Financial | Capital One | $35.3B | ~2.0x | ~5% | ~25% |
| Jan 2026 | Brex | Capital One | $5.15B | ~5-7x | ~30% | N/A |
| H2 2024 | Nuvei | Advent (PE) | $6.3B | ~5.5x | ~15% | ~56% |
| Q4 2024 | Envestnet | Bain (PE) | $4.5B | ~3.5x | ~8% | ~40% |
| 2024 | MoneyLion | Gen Digital | $0.6B | ~2.3x | ~30% | ~20% |

Sector handoff benchmarks: High-growth targets (>30%): 8–20x revenue. Growth-stage (15–30%): 3–8x. Bank charter premium: +0.5–1.0x TBV. Neobank M&A settled at 2–4x revenue.

### Takeout Valuation
- **Revenue approach:** 4–6x FY2025 revenue ($3.6B) = $14.5–21.7B EV. After 25% control premium discount: $10.8–16.3B → **$10.04–$13.94/share**
- **P/TBV approach:** 1.5–2.5x TBV ($6.41/share) → **$9.61–$16.02/share**
- **Blended mid-point:** **$12.40/share**

**Probability note:** A takeout at $22B+ market cap is unlikely near-term. SoFi is too large for most PE funds as a single position, and BHC regulations require Fed approval for any 10%+ acquisition. However, the bank charter + Galileo tech stack are genuinely scarce strategic assets. The most realistic acquirers would be JPMorgan or a large bank seeking digital transformation — but the political optics of a megabank acquiring a consumer neobank are poor. This method sets a floor reference, not a likely outcome.

---

## VALUATION METHOD 5: SUM-OF-PARTS

### Segment Breakdown and Multiples

| Segment | FY2025 Rev ($M) | Growth | Comparable | Bear Mult | Base Mult | Bull Mult |
|:--------|:---------------:|:------:|:-----------|:---------:|:---------:|:---------:|
| Lending | 1,849 | 24% | LC (1.5x), bank peers | 1.5x | 2.0x | 2.5x |
| Financial Services | 1,542 | 88% | PYPL fee rev, HOOD Gold | 4.0x | 6.0x | 8.0x |
| Technology Platform | 450 | 14% | MQ, fintech infra (8-12x) | 5.0x | 7.5x | 10.0x |

### Implied Valuations

| | Bear | Base | Bull |
|:--|:----:|:----:|:----:|
| Lending | $2,774M | $3,698M | $4,622M |
| Financial Services | $6,168M | $9,252M | $12,336M |
| Technology Platform | $2,250M | $3,375M | $4,500M |
| **Total EV** | **$11,192M** | **$16,325M** | **$21,458M** |
| + Net Cash | $3,114M | $3,114M | $3,114M |
| **Per Share** | **$10.29** | **$13.98** | **$17.68** |
| Upside/(Downside) | −35% | −11% | +12% |

**Hidden Value Flag:** The Financial Services segment grew 88% YoY and is transitioning SoFi from a lending company to a capital-light fee platform. At the current consolidated 3.95x EV/NTM, the market implicitly values FinServices at ~3-4x — materially below comparable fee-based financial businesses (PayPal's fee revenue, Robinhood Gold subscription revenue). At 6x, this segment alone is worth $9.3B, versus the entire current EV of $18.8B.

The Technology Platform (Galileo/Technisys) at 7.5x = $3.4B is also likely undervalued. As a standalone B2B fintech infrastructure business with 39% contribution margins, 128M+ enabled accounts, and the US Treasury Direct Express contract, it would likely command 8–12x revenue in a standalone context. The large-client departure in Q4 2025 actually improved margins (to 39% from 31%), suggesting the departing client was low-margin.

---

## VALUATION METHOD 6: PE / LBO FLOOR

**Framing:** Growth equity (no leverage) — BHC regulations constrain traditional LBO structures. Target: 20% IRR over 5 years, pure equity.

### 5-Year Projection (Base Case)

| Year | Revenue ($M) | NI Margin | NI ($M) | Cumulative NI |
|:----:|:-----------:|:---------:|:-------:|:-------------:|
| 1 | 4,769 | 15% | 715 | 715 |
| 2 | 5,866 | 17% | 997 | 1,713 |
| 3 | 7,039 | 18% | 1,267 | 2,980 |
| 4 | 8,306 | 19% | 1,578 | 4,558 |
| 5 | 9,635 | 20% | 1,927 | 6,485 |

### Floor Price

| Metric | Value |
|:-------|------:|
| Exit multiple (EV/NTM Rev) | 3.5x (vs. 3.95x entry) |
| Exit EV | $36,422M |
| Exit Equity Value | $41,481M |
| Max entry price for 20% IRR | **$11.99/share** |
| Max entry price for 25% IRR | $9.78/share |
| IRR at current price ($15.79) | **13.6%** |
| Downside to 20% IRR floor | −24% |

**Reality check:** The 13.6% IRR at current price is below PE return thresholds but above long-term equity market returns. This suggests the stock is not "cheap enough" for a pure financial buyer, but has reasonable return potential for a long-only investor. The $11.99 floor price (−24%) provides a reference for downside protection — meaningful further downside from here would attract growth equity interest.

---

## TRIANGULATION & DELIVERABLE 1: PRICE TARGET RANGE

```
━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
TICKER: SOFI
CURRENT PRICE: $15.79
ANALYSIS DATE: April 4, 2026

METHOD RESULTS:
Method            Bear      Base      Bull    Weight  Confidence
─────────────────────────────────────────────────────────────
Reverse DCF        —    Implies 11.5% CAGR     —       —       HIGH
Forward DCF     $12.33   $20.79   $32.03      35%     HIGH
Trading Comps      —     $13.52      —        30%     HIGH
M&A Comps          —     $12.40      —        10%     LOW
Sum-of-Parts    $10.29   $13.98   $17.68      15%     MED-HIGH
PE/LBO Floor    $11.99      —        —        10%     MED

TRIANGULATED PRICE TARGET:
  Bear case: $11.65 (−26%)
  Base case: $15.87 (+1%)
  Bull case: $24.83 (+57%)

CONVICTION SCORE: 3.5 / 5

CONVICTION RATIONALE:
SoFi is a structurally unique asset — the only US fintech with a bank charter,
proprietary B2B tech infrastructure, and a consumer super-app all under one
roof. Fundamental execution is excellent (Rule of 40 = 68, 9 quarters of GAAP
profitability, 35% revenue growth). Three factors cap conviction at 3.5:
(1) the unresolved Muddy Waters short report allegations create binary risk
until Q1 earnings on April 29; (2) serial dilution of 16% in FY2025 has
destroyed per-share value despite aggregate earnings growth; and (3) the sector
is in a deep valuation trough that compresses all comps-based methods. The
base case lands at essentially current price, reflecting the tension between
a discounted DCF ($20.79) and trough-multiple comps ($13.52). The Reverse DCF
clearly shows the market is pricing in severe deceleration (11.5% CAGR vs. 30%
guided) — if SoFi executes anywhere near management targets, the stock is
meaningfully undervalued. If credit quality deteriorates or MW is vindicated,
the bear case of $11.65 is the destination.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### Weighting Rationale

- **Forward DCF at 35%:** Highest weight because SoFi has predictable, growing revenue across three segments with improving margins and a clear guidance framework. Net income is the appropriate cash flow proxy for a bank model.
- **Trading Comps at 30%:** Well-defined peer set with both EV/Revenue and P/TBV approaches. Confidence is HIGH for the methodology but results are depressed by the sector-wide valuation trough. I am deliberately not adjusting upward for "normalized" multiples — trough multiples are today's reality.
- **Sum-of-Parts at 15%:** SoFi's three segments have meaningfully different growth profiles and deserve separate multiples. The Financial Services segment's hidden value is the primary insight from this method.
- **M&A Comps at 10%:** Low weight because (a) SoFi is too large for most acquirers, (b) BHC regulatory constraints, and (c) fintech M&A multiples have compressed to 2-4x from historical 5-10x levels.
- **PE/LBO Floor at 10%:** Downside reference. Growth equity framing is most appropriate; 13.6% IRR at current price suggests moderate but not compelling financial buyer interest.

### Key Disagreement Between Methods

The forward DCF ($20.79 base) diverges significantly from comps ($13.52) and SoP ($13.98). This is not a modeling error — it reflects a fundamental tension:

1. **The DCF values future earnings power.** If SoFi grows at 20-30% for 5+ years with expanding NI margins toward 20%, the intrinsic value is ~$20/share.
2. **The comps value where the market trades today.** The entire consumer fintech sector is in a trough — NU at 2.75x with 45% growth, LC at 1.50x with 23% growth. These multiples reflect maximum pessimism.
3. **Resolution:** The stock is near fair value on a multiples basis *at current trough multiples* but meaningfully undervalued on a DCF basis *if management executes.* The key variable is whether the Muddy Waters overhang clears and whether the sector re-rates from trough levels.

---

## DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━━━━━━━━━━
TICKER: SOFI
COMPANY: SoFi Technologies Inc.
SECTOR: Consumer Fintech / Neobanking
VALUATION DATE: April 4, 2026

PRICE TARGET: $15.87 base case (range: $11.65 bear — $24.83 bull)
CURRENT PRICE: $15.79
UPSIDE TO BASE: +1%
CONVICTION: 3.5/5

WHEEL STRATEGY IMPLICATIONS:

  SELL PUTS: YES — CONDITIONAL
    Rationale: Base case is approximately fair value, but bear case of
    $11.65 and TBV floor of $6.41/share provide meaningful downside
    margin of safety at lower strikes. The DCF-based fair value of $20.79
    suggests the stock is undervalued if fundamentals hold.
    Suggested strike zone: $12.00–$14.00 (near or below bear case)
    Avoid puts above: $16.00 (at or above current price = limited edge)
    CONDITIONAL on: Waiting until AFTER April 29 Q1 2026 earnings.
    Pre-earnings put selling carries elevated binary event risk from
    the Muddy Waters overhang. If Q1 earnings validate reported metrics,
    selling May/June puts in the $12-$14 zone is attractive.

  COVERED CALLS (if assigned):
    Cost basis assumption: $13.00 (mid put strike zone)
    Minimum call strike: $13.00 (cost basis floor per cc_min_strike_pct=1.0)
    Suggested call strike zone: $16.00–$19.00 (between cost basis and DCF)
    Do NOT sell calls above: $25.00 (approaching bull case — let it run)

  CONCENTRATED LONG CANDIDATE: NO
    Rationale: Conviction 3.5 < 4.0 threshold. MW overhang and dilution
    risk preclude concentrated positioning. Re-evaluate after April 29
    if: (a) MW allegations conclusively addressed, (b) products/member
    crosses 1.55+, and (c) management announces buyback program. If all
    three conditions are met, conviction could rise to 4.0.

KEY DATES TO AVOID (earnings, catalysts):
  April 29, 2026: Q1 2026 earnings — CRITICAL first post-MW report
  October 15, 2026: 2026 Convertible Notes maturity (~$530M, dilution risk)
  Late July 2026: Q2 2026 earnings

SECTOR CONTEXT:
  Sector score from analysis: 19/25
  Relative ranking in sector: 2 of 12 (behind NU at 23/25)
  Sector-level risk flag: Consumer credit cycle is the macro tail risk.
    Personal loan NCO at 2.80% are benign but a move to 5%+ would impair
    the lending segment and validate MW's credit quality concerns. Fed
    rate path is the second-order risk — cuts help lending demand but
    compress NIM.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## VALUATION CROSS-CHECKS

| Metric | Value | Context |
|:-------|------:|:--------|
| P/E on FY2026E EPS ($0.62) | 25.5x | Reasonable for 30%+ growth |
| P/E on FY2027E EPS ($0.84) | 18.8x | Attractive if execution holds |
| P/E on FY2028E EPS ($1.02) | 15.5x | Deep value territory |
| EV/EBITDA (FY2026E guide $1.6B) | 11.8x | In-line with fintech peers |
| P/TBV | 2.46x | Premium vs. LC (1.3x), discount vs. NU ROE-adjusted |
| Price/NTM Revenue | 4.60x | Slightly above peer median |
| Dilution-adjusted EPS growth (FY2025) | 0% | Flat — $0.39 in both FY2024 and FY2025 due to 16% dilution |
| Revenue per share growth (FY2025 vs. FY2024) | +19% | Better than EPS but still eroded by dilution |

### The Dilution Problem in One Number
FY2024 GAAP NI: $499M → FY2025 GAAP NI: $481M. Net income actually declined slightly. But even adjusting for the FY2024 DTA one-time benefit ($272M), underlying NI grew ~$254M→$481M (+89%). Yet GAAP EPS was flat at $0.39 because shares outstanding grew from 1,101M to 1,252M (+14%). **SoFi must either stop diluting or grow fast enough to overcome dilution — at 16%/year dilution, the company needs 16%+ NI growth just to keep EPS flat.** The FY2026 guide of $0.60 EPS (+54%) on an assumed ~1.35B share count implies management expects dilution to slow dramatically. This is the single most important assumption to monitor.

---

*Report generated April 4, 2026. All models use fully diluted share count of 1,390M. WACC of 10% for base case, 11% for bear. Net income used as FCF proxy (bank model). All figures in USD millions unless otherwise noted.*
