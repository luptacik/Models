# V1 STOCK VALUATION — ZSCALER, INC. (ZS)

**Ticker:** ZS
**Company:** Zscaler, Inc.
**Current Price:** $132.00
**Analysis Date:** March 29, 2026
**Fiscal Year End:** July 31
**Sub-sector:** SASE / Zero Trust / SSE
**Sector Score:** 22/25 — PASS (#1 rank in cybersecurity peer set)

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency — ALL METHODS RUNNABLE

| Method | Required Data | Status | Notes |
|--------|--------------|--------|-------|
| Reverse DCF | Revenue history, FCF, EV, guidance | ✅ Complete | 12 quarters of revenue + FCF history available |
| Forward DCF | Consensus estimates, margins, share count | ✅ Complete | Consensus through FY2028E; management guide through FY2026 |
| Trading Comps | Peer multiples | ✅ Complete | Full sector handoff with 16 cybersecurity peers |
| M&A Comps | Transaction multiples | ⚠️ Partial | Sector handoff provides ranges; no pure-play SASE M&A transaction at ZS's scale. Using sector benchmarks + comparable deals |
| Sum-of-Parts | Segment revenue | ⚠️ Limited | ZS does not disclose product-level revenue (ZIA, ZPA, ZDX). AI Security ARR ($500M+) and Red Canary (~$130M ARR) are the only separately quantified components. Method will rely on estimated segment mix. **Reduced weight in triangulation** |
| PE/LBO Floor | FCF, debt capacity, EV | ✅ Complete | Strong FCF history, clean balance sheet |

### Check 2: Fiscal Year Alignment — CONFIRMED

Zscaler's fiscal year ends **July 31**. All data is mapped to Zscaler's fiscal calendar:
- Most recent quarter: Q2 FY2026 (ended January 31, 2026)
- Current period: Q3 FY2026 (February 1 – April 30, 2026)
- FY2026 = August 2025 – July 2026
- FY2027E = August 2026 – July 2027

Peer alignment note: CRWD and RBRK share the July 31 / January 31 fiscal calendar. PANW ends July 31. FTNT and CHKP use calendar year. All comps data has been aligned to NTM (next twelve months from analysis date) to normalize timing.

### Check 3: Share Count Reconciliation

| Component | Shares (M) | Source |
|-----------|-----------|--------|
| Basic shares outstanding (Jan 31, 2026) | 161.0 | 10-Q |
| GAAP weighted-avg diluted (Q2 FY2026) | 159.7 | Earnings release (uses basic due to GAAP net loss) |
| Non-GAAP weighted-avg diluted (Q2 FY2026) | 166.4 | Earnings release |
| Dilutive equity awards (options/RSUs/PSUs) | 2.8 | 10-Q |
| Convertible note shares (if-converted at $439.52) | 3.9 | 10-Q |
| **Estimated fully diluted (all awards + converts)** | **~174** | Calculated |
| FY2026 guidance diluted shares | ~169 | Management guidance |

**Using 174M fully diluted shares for all per-share calculations.** Rationale: the convertible notes are deeply out-of-the-money (conversion at $439.52 vs. $132 stock price) and will almost certainly be settled in cash at maturity (July 2028). However, including the 3.9M if-converted shares provides the most conservative per-share values. The ~169M guidance figure reflects the Non-GAAP treasury stock method, which is appropriate for earnings calculations but understates true potential dilution. Annual dilution runs ~3-4% with no buyback program.

### Check 4: SBC Materiality Assessment — ⚠️ CRITICAL FLAG

| Period | SBC ($M) | Revenue ($M) | SBC % of Revenue |
|--------|---------|-------------|-----------------|
| FY2023 | $457.8 | $1,617.0 | **28.3%** |
| FY2024 | $549.1 | $2,167.8 | **25.3%** |
| FY2025 | $685.5 | $2,673.1 | **25.6%** |
| H1 FY2026 | $414.2 | $1,603.9 | **25.8%** |
| LTM (est.) | ~$828 | ~$3,001 | **~27.6%** |

**SBC exceeds 15% of revenue by a wide margin.** All FCF-based valuations in this report present BOTH standard FCF and FCF-ex-SBC. This is the single most important analytical decision in this valuation — the gap between the two measures is approximately $100/share in the forward DCF base case.

| Metric | Standard FCF | FCF ex-SBC | Δ |
|--------|-------------|-----------|---|
| LTM FCF | $873.8M (29.1% margin) | ~$137M (4.6% margin) | **-$737M** |
| FY2025 FCF | $726.7M (27.2%) | $65.3M (2.4%) | **-$661M** |
| H1 FY2026 FCF | $582.4M (36.3%) | $168.2M (10.5%) | **-$414M** |

Zscaler has **no share repurchase program** and has never repurchased shares. The ~3-4% annual dilution from SBC-funded equity is entirely unmitigated. This is the highest SBC-to-revenue ratio among profitable cybersecurity companies in the peer set (CRWD 22.8%, RBRK 22%, OKTA 18.6%, PANW 14%, FTNT 4.1%).

---

## ENTERPRISE VALUE CALCULATION

| Component | Value |
|-----------|-------|
| Stock Price | $132.00 |
| Fully Diluted Shares | 174M |
| **Market Capitalization** | **$22,968M** |
| Cash + Short-Term Investments | $3,512.8M |
| Convertible Notes (due July 2028) | ($1,702.7M) |
| **Net Cash** | **$1,810.1M** |
| **Enterprise Value** | **$21,158M ($21.2B)** |

Current implied multiples:
- EV/NTM Revenue ($3.86B): **5.5x**
- EV/LTM Revenue ($3.0B): **7.1x**
- EV/NTM FCF (est. ~$1.0B): **~21x**
- NTM P/E (Non-GAAP $4.49): **29.4x**
- EV/ARR ($3,359M): **6.3x**

---

## VALUATION METHOD 1: REVERSE DCF

### Purpose
What revenue growth rate is the current $132 stock price implying? This is the primary mispricing detection tool.

### Methodology
Starting from the current enterprise value of $21.2B, I solve for the constant 10-year revenue CAGR that produces the current EV under these terminal assumptions.

### Assumptions

| Parameter | Value | Rationale |
|-----------|-------|-----------|
| Starting Revenue (TTM) | $3,001M | LTM through Q2 FY2026 |
| Terminal FCF Margin | 30% | Sector handoff: 25-35% at $3B+ ARR scale. ZS currently at 29%, with 22% Non-GAAP op margin expanding. QLYS/CHKP show 40-45% ceiling at low growth. 30% is conservative for a company at scale |
| Terminal Growth Rate | 3.0% | GDP-like perpetuity growth |
| WACC (Discount Rate) | 10.0% | Standard for high-growth SaaS; ZS is profitable, pure-play, minimal leverage |
| FCF Margin Ramp | Linear from 27% to 30% over 10 years | FY2025 clean annual FCF margin was 27.2%; terminal at 30% |
| Projection Horizon | 10 years | Standard |

### Results

```
REVERSE DCF RESULTS
━━━━━━━━━━━━━━━━━━
Current EV: $21.2B
Assumptions: Terminal FCF margin 30%, terminal growth 3%, WACC 10%

Implied revenue CAGR: ~9.5%
Current actual revenue growth: 26% (Q2 FY2026 YoY)
Consensus NTM revenue growth: ~20%
Management long-term aspiration: $5B ARR → $10B ARR (implying 15-20% multi-year CAGR)

GAP ANALYSIS:
Market implies ~9.5% growth vs. 20-26% actual/guided
→ Market is pricing in SEVERE DECELERATION from 26% to high-single-digits
→ Implied growth is roughly HALF the current consensus rate

This means the stock is priced as if Zscaler decelerates to ~15%
growth within 2-3 years and reaches mid-single-digit growth by
Year 7-8, far below any current estimate or historical trend.
```

### Sensitivity — Implied Revenue CAGR at Various Assumptions

| WACC \ Terminal FCF Margin | 20% | 25% | 30% | 35% |
|----------------------------|-----|-----|-----|-----|
| 9% | 12.8% | 11.0% | 9.8% | 8.9% |
| 10% | 14.2% | 12.3% | **9.5%** | 8.5% |
| 11% | 15.7% | 13.6% | 12.1% | 10.9% |
| 12% | 17.3% | 15.0% | 13.4% | 12.2% |

### SBC-Adjusted Reverse DCF

Using FCF ex-SBC (terminal margin assumption: 15%, assuming SBC normalizes from 27% to 15% of revenue at scale):

**Implied revenue CAGR on FCF ex-SBC basis: ~18-20%**

This inverts the conclusion: on an SBC-adjusted basis, the market is pricing in growth roughly in line with consensus. The stock is NOT cheap if you fully expense SBC as a real cost. This is the key tension in ZS's valuation — the answer to "is it cheap?" depends entirely on how you treat $800M+ in annual stock-based compensation.

---

## VALUATION METHOD 2: FORWARD DCF (3-SCENARIO)

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|------------|------|------|------|
| Yr 1-2 Revenue CAGR | 22%/21% | 20%/18% | 15%/12% |
| Yr 3-5 Revenue CAGR | 18%→15%→12% | 15%→13%→11% | 8%→5%→3% |
| Yr 6-7 Revenue CAGR | 10%→8% | 9%→7% | 2%→2% |
| Terminal FCF Margin | 35% | 32% | 28% |
| Terminal Growth Rate | 3.5% | 3.0% | 2.5% |
| WACC | 9.5% | 10.0% | 11.0% |

**Bull — What Must Go Right:**
- AI security ($500M+ ARR, growing 80%+) sustains hypergrowth and becomes a $2B+ business by Year 5
- Zero Trust Everywhere (550+ enterprises) expands to 2,000+, driving 2-3x ARR uplift per customer
- PANW/Microsoft bundling fails to materially displace ZS in enterprise SASE
- SBC declines as a percentage of revenue to ~18% by Year 5 as growth investment moderates
- CMMC 3.0 (October 2026) and federal mandates create a $500M+ government tailwind

**Base — Most Likely Path:**
- Revenue follows consensus for Years 1-2 ($4.08B, $4.80B), then decelerates to sector average
- FCF margins expand modestly from 29% to 32% as scale benefits offset continued investment
- SBC remains elevated at 20-22% of revenue, limiting true economic profitability
- Competition from PANW/MSFT caps expansion rates but does not erode installed base
- Organic net new ARR growth sustains at ~5-10% (below recent +10% acceleration)

**Bear — What Could Go Wrong:**
- DBNRR discontinuation was a tell — net retention falls below 110%, signaling churn acceleration
- Microsoft E7 Frontier Suite gains traction in enterprise SASE, capping new logo wins
- SBC remains at 25%+ of revenue indefinitely; no buyback program implemented
- SASE market consolidates around PANW/FTNT bundles; ZS loses share in mid-market
- Convertible note cash repayment ($1.7B in July 2028) depletes cash buffer

### Base Case Revenue Projection

| Year | Revenue ($M) | YoY Growth | FCF Margin | FCF ($M) | Discount Factor (10%) | PV of FCF ($M) |
|------|-------------|------------|------------|----------|----------------------|----------------|
| 0 (FY26E) | 3,410 | +28% | — | — | — | — |
| 1 (FY27E) | 4,092 | +20% | 29.4% | 1,203 | 0.909 | 1,094 |
| 2 (FY28E) | 4,829 | +18% | 29.9% | 1,444 | 0.826 | 1,193 |
| 3 | 5,553 | +15% | 30.3% | 1,683 | 0.751 | 1,264 |
| 4 | 6,275 | +13% | 30.7% | 1,926 | 0.683 | 1,316 |
| 5 | 6,965 | +11% | 31.1% | 2,166 | 0.621 | 1,345 |
| 6 | 7,592 | +9% | 31.6% | 2,399 | 0.564 | 1,353 |
| 7 | 8,123 | +7% | 32.0% | 2,599 | 0.513 | 1,333 |
| **Terminal** | | +3.0% | 32.0% | 2,677 | | **19,631** |

*Terminal Value = $2,599M × 1.03 / (0.10 – 0.03) = $38,253M; PV = $38,253M × 0.513 = $19,631M*

### SBC-Adjusted Base Case (FCF ex-SBC)

| Year | Revenue ($M) | SBC % Rev | SBC ($M) | FCF ($M) | FCF ex-SBC ($M) | FCF ex-SBC Margin | PV of FCF ex-SBC ($M) |
|------|-------------|----------|---------|----------|----------------|-------------------|----------------------|
| 1 | 4,092 | 26% | 1,064 | 1,203 | 139 | 3.4% | 126 |
| 2 | 4,829 | 25% | 1,207 | 1,444 | 237 | 4.9% | 196 |
| 3 | 5,553 | 24% | 1,333 | 1,683 | 350 | 6.3% | 263 |
| 4 | 6,275 | 22% | 1,381 | 1,926 | 546 | 8.7% | 373 |
| 5 | 6,965 | 21% | 1,463 | 2,166 | 703 | 10.1% | 436 |
| 6 | 7,592 | 19% | 1,442 | 2,399 | 957 | 12.6% | 540 |
| 7 | 8,123 | 18% | 1,462 | 2,599 | 1,137 | 14.0% | 583 |
| **Terminal** | | | | | 1,171 | 14.0% | **8,539** |

*SBC-adjusted TV = $1,137M × 1.03 / 0.07 = $16,735M; PV = $16,735M × 0.513 = $8,585M*

### Valuation Summary

| | Bull | Base | Bear |
|---|------|------|------|
| PV of Cash Flows ($M) | 10,618 | 8,898 | 6,123 |
| PV of Terminal Value ($M) | 29,229 | 19,631 | 8,683 |
| **Enterprise Value ($M)** | **39,847** | **28,529** | **14,806** |
| Net Cash ($M) | 1,810 | 1,810 | 1,810 |
| **Equity Value ($M)** | **41,657** | **30,339** | **16,616** |
| Fully Diluted Shares (M) | 174 | 174 | 174 |
| **Per Share Value** | **$239** | **$174** | **$95** |
| Upside / (Downside) | +81% | +32% | (28%) |
| TV as % of Total | **73%** ⚠️ | 69% | 59% |

**SBC-Adjusted Per Share Values:**
| | Bull | Base | Bear |
|---|------|------|------|
| **Per Share (FCF ex-SBC)** | **$143** | **$73** | **$48** |

⚠️ **Terminal Value Warning:** Bull case TV at 73% of total exceeds the 70% threshold. This means the bull case valuation is dominated by long-term assumptions (Year 8+), not near-term fundamentals. Treat with appropriate skepticism.

⚠️ **SBC Gap Warning:** The standard base case ($174) and SBC-adjusted base case ($73) differ by **$101/share**. At the current $132 price, ZS is 24% below fair value on standard FCF but 81% ABOVE fair value on FCF-ex-SBC. This is the central valuation tension — investors must decide how much of the ~$830M annual SBC to treat as a real cost versus a non-cash item.

### Round-Trip Check
Base case EV of $28.5B on NTM revenue of $3.86B implies **7.4x NTM Revenue**. For a 20% grower with 29% FCF margins, Rule of 40 at 55, this is reasonable — consistent with the 6-16x range for 20-30% growers in the sector handoff, and modestly above ZS's current 5.5x which reflects the selloff discount.

---

## VALUATION METHOD 3: TRADING COMPS

### Peer Set — Cybersecurity Platforms (Tier 1: Direct Competitors; Tier 2: Growth Peers)

| Company | Sub-sector | EV/NTM Rev | NTM Growth | Growth-Adj Ratio | FCF Margin | Rule of 40 | SBC % Rev | NRR |
|---------|-----------|-----------|-----------|-----------------|-----------|-----------|----------|------|
| **CRWD** | Endpoint/XDR | **15.7x** | +24% | 0.65 | 25.7% | 48 | 22.8% | 115% |
| **PANW** | Network/Platform | **8.1x** | +33%* | 0.25* | 36% | 51 | 14.0% | ~119% |
| **FTNT** | Network/SASE | **8.9x** | +14% | 0.64 | 32.5% | 47 | 4.1% | N/D |
| **NET** | Connectivity/AI | **26.4x** | +30% | 0.88 | 12.0% | 42 | 20.8% | 120% |
| **RBRK** | Cyber Resilience | **5.3x** | +34%** | 0.16 | 18.1% | 52 | 22% | >120% |
| **OKTA** | Identity | **3.6x** | +11% | 0.33 | 30% | 42 | 18.6% | 106% |
| **S** | Endpoint/XDR | **3.5x** | +22% | 0.16 | 5% | 27 | 29.7% | 109% |
| **NTSK** | SASE (direct) | **3.3x** | +31% | 0.11 | 1.7% | 34 | ~75%*** | N/D |
| **ZS** | **SASE/Zero Trust** | **6.0x** | **+25%** | **0.24** | **29%** | **55** | **27%** | **~114%** |

*PANW uses NGS ARR growth (+33%); total revenue growth is +15%*
**RBRK uses subscription ARR growth; total revenue growth is +46%*
***NTSK SBC is temporary IPO artifact*

### Peer Median Statistics

| Metric | Peer Median (ex-outliers) | ZS | ZS vs. Median |
|--------|--------------------------|-----|--------------|
| EV/NTM Revenue | 5.5x | 6.0x | +9% premium |
| NTM Revenue Growth | +24% | +25% | In-line |
| Growth-Adjusted Ratio | 0.33 | 0.24 | **27% cheaper** |
| FCF Margin | 25.7% | 29% | +330bps better |
| Rule of 40 | 47 | **55** | **+8 pts, best-in-class** |
| SBC % Revenue | 20.8% | 27% | +620bps worse |

### Target Company Positioning

- **Growth rank:** 4th of 9 peers (behind RBRK +34%, PANW NGS +33%, NTSK +31%; above CRWD +24%)
- **Profitability rank (FCF):** 4th of 9 (behind PANW 36%, FTNT 32.5%, OKTA 30%)
- **Rule of 40 rank:** **1st of 9** (tied with QLYS at 55, but QLYS grows at only 10%)
- **Current multiple vs. peer median:** +9% premium on raw EV/Revenue, but **27% discount** on growth-adjusted basis
- **SBC rank:** 8th of 9 (only S at 29.7% is worse among profitable companies)

### Fair Multiple Determination

**Method: Growth-Adjusted Peer Calibration**

ZS's growth-adjusted ratio (0.24) is virtually identical to PANW's (0.25 on NGS ARR growth). PANW trades at 8.1x NTM revenue. However, ZS deserves a discount to PANW for:
1. Higher SBC intensity (27% vs. 14%) — reduces true economic profitability
2. Narrower platform (SASE-focused vs. PANW's triple-platform breadth post-CyberArk)
3. DBNRR disclosure discontinued — reduced investor visibility

Offsetting premium factors:
1. Best-in-class Rule of 40 (55 vs. PANW's 51)
2. Higher recurring revenue mix (~97% vs. PANW's 80%)
3. Stronger RPO growth (+31% vs. PANW's +23%)

**Net adjustment: 15-20% discount to PANW's 8.1x = 6.5-6.9x NTM revenue**

The most comparable company on all dimensions is RBRK (similar growth-adjusted ratio of 0.16 vs. ZS's 0.24, similar SBC burden, both PASS-ranked at 22/25). RBRK trades at 5.3x. ZS deserves a small premium over RBRK for proven profitability (29% FCF margin vs. 18%) and larger scale ($3.4B ARR vs. $1.5B).

**Fair EV/NTM Revenue: 6.8x (midpoint of calibrated range)**

```
TRADING COMPS — FAIR VALUE ESTIMATE
━━━━━━━━━━━━━━━━━━

Method: Growth-adjusted peer calibration (PANW-anchored with SBC discount)
Fair EV/NTM Revenue: 6.8x (current: 5.5x)
NTM Revenue: $3,860M
Implied EV: $26,248M
Plus Net Cash: $1,810M
Implied Equity: $28,058M
Implied Share Price: $161
Upside: +22%

Sensitivity:
| Multiple | Implied EV ($B) | Per Share | Upside/(Downside) |
|----------|----------------|----------|-------------------|
| 5.5x (current) | $21.2 | $132 | 0% |
| 6.0x | $23.2 | $144 | +9% |
| 6.5x | $25.1 | $155 | +17% |
| 6.8x (fair) | $26.2 | $161 | +22% |
| 7.5x | $28.9 | $177 | +34% |
| 8.0x | $30.9 | $188 | +42% |
```

---

## VALUATION METHOD 4: PRECEDENT M&A COMPS

### Comparable Transactions — Cybersecurity (2024–2026)

| Date | Target | Acquirer | EV ($B) | EV/Rev | EV/ARR (est.) | Target Growth | Premium |
|------|--------|----------|---------|--------|---------------|---------------|---------|
| Mar 2026 | Wiz | Google | $32.0 | ~32x | ~28x | ~100%+ | Strategic (private) |
| Feb 2026 | CyberArk | PANW | $25.0 | ~35x | ~12x | +33% ARR | ~40% |
| Jan 2026 | SGNL | CRWD | $0.75 | N/A | N/A | Private | Private |
| Jan 2026 | Seraphic | CRWD | $0.42 | N/A | N/A | Private | Private |
| Nov 2025 | Chronosphere | PANW | $3.35 | ~17x | N/A | ~30%+ | ~35% |
| Oct 2025 | Darktrace | Thoma Bravo | $5.3 | ~9x | ~8x | +25% | ~30% |
| Sep 2025 | SolarWinds | Turn/River | $4.4 | ~5x | N/A | ~5% | ~25% |
| Aug 2025 | Red Canary | Zscaler | $0.675 | ~5x | ~5x | ~30% | Private |
| Feb 2025 | Secureworks | Sophos/TB | $0.86 | ~1.5x | ~1.5x | ~5% | ~25% |

### Applicable Range for Zscaler

Per sector handoff M&A benchmarks:
- Growth-stage targets (15-30% growth): **6-10x ARR**
- Strategic scarcity premium: **+2-4x**

ZS qualifies for the **high end** of the growth-stage range plus scarcity premium because:
- #1 SSE market share globally (4-year Gartner Leader)
- The only pure-play SASE platform at this scale ($3.4B ARR)
- 80% gross margins, 29% FCF margins — clean financial profile
- Deep enterprise penetration (45% of Fortune 500)

The Darktrace deal at 8x ARR for a 25%-growth AI security company is the closest public comp. CyberArk at ~12x ARR was a higher-growth identity asset with strategic premium to PANW.

```
M&A COMPS — TAKEOUT VALUATION
━━━━━━━━━━━━━━━━━━

Applicable multiple range: 8-11x ARR
(Growth-stage 6-10x + strategic scarcity premium of +1-2x)

Current ARR: $3,359M (Q2 FY2026)
FY2026E ARR (guide mid): $3,738M

TAKEOUT SCENARIO:
| | Conservative (8x) | Mid (9.5x) | Aggressive (11x) |
|---|-------------------|-----------|------------------|
| ARR Applied | $3,738M (guided) | $3,738M | $3,738M |
| Implied EV | $29.9B | $35.5B | $41.1B |
| After 25% control premium discount | $22.4B | $26.6B | $30.8B |
| Plus Net Cash | $1.8B | $1.8B | $1.8B |
| Implied Equity | $24.2B | $28.4B | $32.6B |
| Per Share | $139 | $163 | $188 |

Central Estimate (after control premium discount): $163/share

PROBABILITY-WEIGHTED NOTE:
A takeout is LOW-TO-MODERATE probability. ZS's $21B+ EV makes this
a mega-deal requiring either (a) a PE consortium (Thoma Bravo + partners),
(b) a strategic acquirer like Cisco, Google, or even PANW once current
integrations settle, or (c) a take-private by sovereign wealth. CEO
Jay Chaudhry controls ~17-26% of shares, which provides both leverage
and veto power over any deal. Chaudhry has shown no interest in selling.

The takeout floor (conservative case at $139) sets a reasonable downside
reference — it would be irrational for the stock to trade materially
below where a strategic or PE buyer would bid.
```

---

## VALUATION METHOD 5: SUM-OF-PARTS

### Applicability Assessment

Zscaler does **not** disclose product-level revenue or ARR for ZIA, ZPA, ZDX, or Data Protection individually. This limits the SoP method to estimated segment splits based on qualitative management commentary and observable data points. **Confidence: LOW — reduced weight in triangulation.**

### Estimated Segment Breakdown

| Segment | Est. ARR ($M) | Est. Growth | Comparable | Multiple Applied | Implied EV ($M) |
|---------|--------------|-------------|-----------|-----------------|----------------|
| ZIA (Internet Access) — core SSE | ~1,500 | ~15% | FTNT sub (8-9x), CHKP (5.8x) | 6.0x ARR | 9,000 |
| ZPA (Private Access) — ZTNA | ~800 | ~25% | ZS overall (6x), OKTA (3.6x) | 7.5x ARR | 6,000 |
| AI Security + Data Protection | ~500 | ~80% | RBRK (5.3x rev on 34% growth) | 12.0x ARR | 6,000 |
| ZDX + Zero Trust Branch + Other | ~430 | ~30% | SAIL (5.2x), NTSK (3.3x) | 6.0x ARR | 2,580 |
| Red Canary (MDR) | ~130 | ~25% | Acquired at ~5x ARR | 5.0x ARR | 650 |

**Total Implied EV: $24,230M ($24.2B)**

Less: Net Debt / Plus: Net Cash: +$1,810M
Equity Value: $26,040M
Per Share: **$150**
Upside: +14%

### Hidden Value Flag

**AI Security at $500M ARR growing 80%+ is the embedded option.** At a standalone AI security multiple (12x ARR), this segment alone is worth ~$6B, or roughly **$34/share** — yet the market is assigning ZS's overall business only 6x blended ARR, implying the AI security business is getting little to no premium in the bundled stock. If AI security were a separate public company at these growth rates, it would likely command 15-20x ARR (comparable to RBRK's trajectory). The hidden value could be $3-5B or $17-29 per share above what I've modeled.

**Caveat:** These segment estimates are directional only. Zscaler's integrated platform model means segments are not truly separable — customer value comes from the cross-platform bundle, not individual products. The SoP overstates value if customers would not pay standalone prices for individual components.

---

## VALUATION METHOD 6: PE / LBO FLOOR

### Entry Assumptions

ZS is a profitable high-growth SaaS company with $874M LTM FCF. A leverage recapitalization model applies, though debt capacity is limited by the existing $1.7B convertible notes maturing July 2028.

| Parameter | Value | Rationale |
|-----------|-------|-----------|
| Entry EV | $21.2B (current) | No premium |
| Additional Debt | $2,600M | ~3x LTM FCF; secured against recurring revenue |
| Equity Required | $18,600M | EV minus debt |
| Target IRR | 20% | Standard PE hurdle |
| Investment Horizon | 5 years | Standard PE hold period |

### 5-Year Projection (Base Case Cash Flows)

| Year | Revenue ($M) | YoY Growth | FCF Margin | FCF ($M) | Cumulative FCF ($M) |
|------|-------------|------------|------------|----------|---------------------|
| 1 (FY27) | 4,092 | +20% | 29% | 1,187 | 1,187 |
| 2 (FY28) | 4,829 | +18% | 30% | 1,449 | 2,636 |
| 3 | 5,553 | +15% | 31% | 1,721 | 4,357 |
| 4 | 6,275 | +13% | 32% | 2,008 | 6,365 |
| 5 | 6,965 | +11% | 33% | 2,298 | 8,663 |

### Exit Assumptions

| Scenario | Exit Multiple | NTM Rev at Exit | Exit EV ($B) | Exit Equity ($B) | MOIC | IRR |
|----------|-------------|----------------|-------------|-----------------|------|-----|
| Conservative | 5.0x | $7.6B | $38.0 | $44.1 | 2.37x | 18.8% |
| Base | 6.0x | $7.6B | $45.6 | $51.7 | 2.78x | 22.6% |
| Optimistic | 7.0x | $7.6B | $53.2 | $59.3 | 3.19x | 26.1% |

*Exit Equity = Exit EV − Remaining Debt + Cumulative FCF*
*Note: Assumes convert repaid from operating cash; new debt remains outstanding*

```
PE / LBO FLOOR
━━━━━━━━━━━━━━━━━━

FLOOR PRICE (Max entry for 20% IRR):
- At 5x exit multiple: $127/share ← absolute floor
- At 6x exit multiple: $144/share ← realistic floor
- At 7x exit multiple: $162/share

Current price: $132
- At 6x exit: Downside to floor = (9%) — current price is BELOW the PE floor
- At 5x exit: Downside to floor = 4% — modest downside in extreme case

REALITY CHECK:
PE interest is REALISTIC for Zscaler. Thoma Bravo manages ~$58B in
cyber company enterprise value and is the most active PE buyer in the
sector. However, at ~$23B EV, ZS would be one of the largest-ever
cybersecurity take-privates (comparable to SolarWinds at $4.4B,
Darktrace at $5.3B). This would require a consortium of 2-3 PE firms
or a strategic-PE partnership. Chaudhry's controlling stake adds
complexity. Probability: ~10-15% within 18 months.

The PE floor does confirm that current prices offer PE-grade returns
(20%+ IRR) with reasonable exit assumptions — a strong downside
support signal.
```

---

## TRIANGULATION & FINAL OUTPUT

---

### DELIVERABLE 1: PRICE TARGET RANGE & CONVICTION SCORE

```
━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━
TICKER: ZS
CURRENT PRICE: $132.00
ANALYSIS DATE: March 29, 2026

METHOD RESULTS:
| Method              | Bear  | Base  | Bull  | Weight | Confidence |
|---------------------|-------|-------|-------|--------|------------|
| Reverse DCF         | —     | Mkt implies 9.5% CAGR vs. 20-26% actual | — | —   | H |
| Forward DCF         | $95   | $174  | $239  | 35%    | H          |
| Forward DCF (SBC-adj)| $48  | $73   | $143  | (memo) | M          |
| Trading Comps       | $132  | $161  | $188  | 30%    | H          |
| M&A Comps           | $139  | $163  | $188  | 10%    | M          |
| Sum-of-Parts        | $130  | $150  | $175  | 10%    | L          |
| PE/LBO Floor        | $127  | $144  | $162  | 15%    | M          |

TRIANGULATED PRICE TARGET:
- Bear case: $118  (11% downside)
- Base case: $161  (22% upside)
- Bull case: $203  (54% upside)

CONVICTION SCORE: 4 / 5
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

**Weighting Rationale:**
- Forward DCF at 35%: ZS has highly predictable recurring revenue (~97% subscription), clear margin trajectory, and good consensus estimates through FY2028. DCF is well-suited for this business.
- Trading Comps at 30%: Peer set is well-defined and comprehensive (sector handoff provides 16 calibrated comparables). Growth-adjusted analysis gives a reliable relative value anchor.
- PE/LBO Floor at 15%: Elevated because PE interest in cybersecurity is historically high (Thoma Bravo's $58B portfolio), and the floor price provides actionable downside support for an options-focused strategy.
- M&A Comps at 10%: No pure-play SASE M&A transaction at ZS's scale exists. Benchmarks are interpolated from adjacent deals. Lower confidence.
- Sum-of-Parts at 10%: Segment revenue is estimated, not disclosed. Method adds directional value (especially the AI security hidden value flag) but cannot be relied upon for precision.
- SBC-adjusted DCF is presented as a memo item, not weighted into the triangulation. Rationale: the market convention for SaaS valuation uses standard FCF, not FCF-ex-SBC. However, the $73 SBC-adjusted base case serves as a critical reality check — it shows the stock is NOT a screaming bargain when SBC dilution is fully internalized.

**Conviction Rationale:**
Score of 4 reflects **high conviction** that ZS is undervalued at $132. Five of six methods produce base case values above the current price ($144-$174 range). The reverse DCF shows the market pricing in ~10% revenue CAGR — roughly half the consensus estimate and well below any credible growth scenario for the next 3-5 years. The stock trades at a historically anomalous discount (6.0x NTM revenue vs. 5-year average well above that level) despite accelerating organic net new ARR (+10%), best-in-class Rule of 40 (55), and AI security momentum ($500M+ ARR). The bear case ($118, 11% downside) is relatively contained, supported by the PE floor and $1.8B net cash.

**What prevents a score of 5:** The SBC issue is real and unresolved. At 27% of revenue with no buyback program, ZS has the highest dilution burden among profitable cybersecurity companies. The SBC-adjusted DCF at $73 shows that if the market begins fully pricing SBC as a real cost (as it increasingly does in a higher-rate environment), the downside is severe. Additionally, the DBNRR discontinuation at 114% removes a key transparency metric, and the competitive risk from PANW/Microsoft in SASE is genuine even if not yet visible in metrics.

---

### DELIVERABLE 2: FULL VALUATION REPORT

[The complete output of all six methods above constitutes Deliverable 2. All tables, assumptions, sensitivity analyses, and round-trip checks are included in the body of this document.]

**Key Analytical Findings:**

1. **The market is too pessimistic on growth.** The reverse DCF implies ~10% revenue CAGR — a rate ZS has never come close to in its history. Even the bear case consensus estimate for FY2028 (~$4.4B) implies ~13% CAGR from current TTM, well above what the stock prices in. Unless you believe ZS faces near-term revenue stagnation (no evidence supports this), the stock is cheap on growth.

2. **SBC is the elephant in the room.** The $101/share gap between standard DCF ($174) and SBC-adjusted DCF ($73) is the widest for any company I've valued in this sector. ZS's annual SBC of ~$830M is roughly equal to its entire reported FCF. Without a buyback program, the 3-4% annual dilution compounds meaningfully over a 5-7 year holding period. An investor buying at $132 today and holding for 5 years faces ~15-20% cumulative dilution, which materially erodes returns.

3. **AI security is the hidden catalyst.** At $500M+ ARR growing 80%+, ZS's AI security business is one of the fastest-growing product lines in cybersecurity. This business alone could be worth $6-10B at standalone comps — yet the overall stock implies only 6.3x blended ARR. If ZS provided segment disclosure or spun off AI security, the re-rating potential is significant.

4. **The PE floor provides downside support.** At $132, a PE buyer achieves 20%+ IRR with conservative assumptions (6x exit multiple, no growth premium). Thoma Bravo's active presence in cybersecurity ($58B portfolio) makes this more than theoretical. The convert maturity in July 2028 could accelerate strategic activity.

5. **The consensus analyst target of ~$265 is too aggressive.** While 37-38 analysts carry a median target of $220-$265, this appears to lag the SBC and competitive dynamics. My base case of $161 is more conservative but more defensible — it reflects a fair multiple (6.8x NTM) calibrated against the SBC-adjusted reality, not a reversion to historical peak multiples.

---

### DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━
TICKER: ZS
COMPANY: Zscaler, Inc.
SECTOR: Cybersecurity (SASE / Zero Trust)
VALUATION DATE: March 29, 2026

PRICE TARGET: $161 base case (range: $118 bear — $203 bull)
CURRENT PRICE: $132
UPSIDE TO BASE: +22%
CONVICTION: 4/5

WHEEL STRATEGY IMPLICATIONS:

- SELL PUTS: YES
  - Rationale: Stock is 22% below base case price target with PE
    floor support at $127-$144. Selling puts at or below bear case
    offers favorable risk/reward — the PE floor limits downside,
    and assignment would occur at valuations where even the SBC-
    adjusted DCF shows reasonable value.
  - Suggested strike zone: $115–$125 (at or below bear case of $118)
  - Avoid puts above: $155 (approaches base case — negative EV)

- COVERED CALLS (if assigned):
  - Cost basis assumption: $120 (put strike)
  - Minimum call strike: $120 (cost basis floor per cc_min_strike_pct=1.0)
  - Suggested call strike zone: $145–$160 (between cost basis and
    base case PT of $161)
  - Do NOT sell calls above: $180 (approaching bull case — let it run)

- CONCENTRATED LONG CANDIDATE: NO
  - Rationale: Conviction is 4 but upside to base case is only +22%.
    Concentrated longs require conviction ≥ 4 AND upside ≥ 30%.
    ZS at $132 is modestly undervalued, not deeply mispriced.
    The SBC-adjusted DCF at $73 injects genuine uncertainty about
    true intrinsic value. The wheel strategy (selling puts, potentially
    owning at lower cost basis) is the superior risk-adjusted approach.

KEY DATES TO AVOID (earnings, catalysts):
- May 28, 2026: Q3 FY2026 earnings (confirmed) — the pivotal print.
    Watch organic net new ARR growth (must sustain +10% or better),
    Red Canary integration milestones, and AI security ARR trajectory.
    Historical beat pattern suggests ~$852-855M actual vs. $835M guide.
- October 1, 2026: CMMC 3.0 mandatory in DoD contracts — government
    revenue catalyst for ZS (14 of 15 Cabinet-level agencies, FedRAMP High)
- Late Calendar 2026: Analyst Day (planned) — potential catalyst for
    long-term margin framework and SBC normalization timeline
- July 15, 2028: Convertible note maturity ($1,725M at $439.52
    conversion price — will require cash repayment)

SECTOR CONTEXT:
- Sector score from analysis: 22/25 (#1 rank)
- Relative ranking in sector: 1 of 16
- Sector-level risk flags:
  (1) Microsoft E7 Frontier Suite bundling creates $0 marginal cost
      competition in SASE — HIGH severity
  (2) Anthropic "Claude Mythos" AI commoditization fears — triggered
      4.5% sector ETF drop on March 27 — MEDIUM severity
  (3) SaaS valuation regime reset (iShares Software ETF −30% from
      Sep 2025 peak) may have further to run — MEDIUM severity
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```
