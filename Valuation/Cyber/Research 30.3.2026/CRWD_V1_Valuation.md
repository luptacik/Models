# V1 — CROWDSTRIKE (CRWD) STOCK VALUATION

**TICKER:** CRWD
**COMPANY:** CrowdStrike Holdings, Inc.
**CURRENT PRICE:** $368
**ANALYSIS DATE:** March 29, 2026
**SECTOR:** Cybersecurity — Endpoint / XDR / AI-Powered Security Platform
**SECTOR SCORE:** 21/25 (PASS — Rank #3 of 16)

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency — PASS (All Methods)

| Method | Required Data | Available? | Notes |
|--------|--------------|------------|-------|
| DCF | ≥8 quarters revenue + FCF, guidance, consensus, share count, net debt | ✅ FULL | 12 quarters of detailed revenue + FCF history available |
| Trading Comps | Peer multiples from sector handoff | ✅ FULL | 16 companies with complete multiples from sector analysis |
| M&A Comps | Recent transaction multiples | ✅ MODERATE | Sector handoff provides ranges; specific deals available |
| Sum-of-Parts | Segment-level revenue/ARR | ✅ GOOD | Identity ($520M), SIEM ($585M), Cloud (~$800M) disclosed |
| PE/LBO | FCF, debt capacity, current EV | ✅ FULL | Clean balance sheet, clear FCF trajectory |

All six valuation methods can be run with high or moderate confidence.

### Check 2: Fiscal Year Alignment — January 31

CrowdStrike's fiscal year ends **January 31**. FY2026 ended January 31, 2026. FY2027 is the current fiscal year (ending January 31, 2027). All references below are mapped accordingly. Peers with identical fiscal years: ZS, S, OKTA, SAIL, NTSK. Peers with calendar years: PANW (Jul 31), FTNT (Dec 31), CHKP (Dec 31), NET (Dec 31). Comps are aligned on NTM basis to account for these differences.

### Check 3: Share Count Reconciliation

| Metric | Count (M) | Source |
|--------|-----------|--------|
| Basic shares outstanding (Feb 28, 2026) | 253.6 | SEC filing |
| Non-GAAP diluted shares (FY2026 Q4) | 258.1 | 8-K |
| FY2027 guided diluted shares | 260.0 | Earnings call |
| Fully diluted (incl. all RSUs/PSUs + options) | ~262.4 | Calculated: 253.6 + 7.9 RSU/PSU + 0.9 options |

**Using 260M diluted shares** for all per-share calculations (FY2027 guided, most appropriate for NTM-based valuations). This is conservative — fully diluted count of 262.4M would produce slightly lower per-share values.

### Check 4: SBC Materiality Assessment — CRITICAL FLAG

| Period | SBC ($M) | Revenue ($M) | SBC % Revenue | FCF Margin | SBC-Adj FCF Margin |
|--------|----------|-------------|---------------|-----------|-------------------|
| FY2024 | $632 | $3,056 | 20.7% | 30.7% | 10.0% |
| FY2025 | $861 | $3,954 | 21.8% | 26.9% | 5.2% |
| FY2026 | $1,097 | $4,812 | 22.8% | 25.7% | 2.9% |

**⚠️ SBC EXCEEDS 15% THRESHOLD — SIGNIFICANTLY.** At 22.8% of revenue, CrowdStrike's SBC is among the highest in the cybersecurity peer set (only SentinelOne at 29.7% and ZS at 27% are higher among established companies). SBC-adjusted FCF margin of 2.9% has **collapsed from 10.0% over three years**. All FCF-based valuations below present BOTH reported and SBC-adjusted versions. The gap between reported FCF (25.7% margin) and SBC-adjusted FCF (2.9%) is the single most important valuation variable for CRWD. A buyer paying 15.7x NTM revenue for a company generating 2.9% economic free cash flow margin is paying for a future that must arrive.

---

## VALUATION METHOD 1: REVERSE DCF

### What growth rate is the market implying?

**Setup:**
- Current Enterprise Value: $91.2B (260M shares × $368 + $750M debt − $5,230M cash)
- FY2026 Revenue (Year 0): $4,812M
- Current FCF Margin: 25.7% (reported) / 2.9% (SBC-adjusted)
- Assumptions: FCF margin ramps linearly from current to terminal over 10 years; terminal growth 3%; terminal value via perpetuity method

**REVERSE DCF RESULTS (Using Reported FCF)**

| Parameter | Value |
|-----------|-------|
| Current EV | $91.2B |
| Terminal FCF margin | 30% (sector benchmark for $3B+ ARR) |
| Terminal growth rate | 3.0% |
| WACC | 10.0% |
| **Implied revenue CAGR** | **22.9%** |
| Current actual revenue growth (FY2026) | 21.7% (accelerated to 23.3% in Q4) |
| FY2027 guided revenue growth | ~22.6% |
| Consensus FY2028 growth | ~20% |
| Management long-term implied CAGR ($10B ARR by ~FY2031) | ~14% |

**GAP ANALYSIS:**

The market is pricing in **22.9% sustained revenue growth for a full decade**. This requires CrowdStrike to grow from $4.8B to ~$38B in revenue by FY2036. For context, management's explicit $20B ARR target for FY2036 implies ~$18B in revenue — roughly half what the market is pricing in.

Current growth of ~22-23% is in line with the implied rate, but consensus expects deceleration to ~20% by FY2028 and ~19% by FY2029. The implied 10-year CAGR of 22.9% requires growth to SUSTAIN near current levels — not decelerate — for the entire forecast period. This is possible for a company with CRWD's moat quality and TAM expansion trajectory, but it is aggressive.

→ **Market is pricing in MARGINALLY ABOVE current growth sustained for a decade — a very demanding embedded expectation**

**Sensitivity: Implied Revenue CAGR to Justify Current EV of $91.2B**

| WACC \ Terminal FCF Margin | 20% | 25% | 30% | 35% |
|----------------------------|-----|-----|-----|-----|
| 9% | 25.3% | 22.6% | 20.3% | 18.5% |
| **10%** | 28.0% | 25.2% | **22.9%** | 21.0% |
| 11% | 30.5% | 27.7% | 25.4% | 23.4% |
| 12% | 32.9% | 30.0% | 27.6% | 25.7% |

The most optimistic defensible combination (9% WACC, 35% terminal FCF margin — representing the top end of CRWD's own FY2029 target) still implies 18.5% sustained CAGR. The current price is not "priced for perfection" — it is priced for near-perfection sustained for an uncommonly long period.

---

## VALUATION METHOD 2: FORWARD DCF (3-SCENARIO)

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|------------|------|------|------|
| Yr 1-2 Rev CAGR | 23% / 22% | 22.6% / 20% | 22% / 17% |
| Yr 3-5 Rev CAGR | 20% / 20% / 18% | 18% / 17% / 16% | 14% / 13% / 12% |
| Yr 6-7 Rev CAGR | 17% / 16% | 15% / 14% | 11% / 10% |
| Terminal FCF Margin | 38% | 35% | 30% |
| Terminal Growth Rate | 3.5% | 3.0% | 2.5% |
| WACC | 9.0% | 10.0% | 11.0% |

**What must go right (Bull):** Charlotte AI drives sustained 20%+ growth for 5 years as the agentic security platform standard; FCF margins reach top of management's 34-38% target range; CRWD captures dominant share of the AI security TAM; no multiple compression from WACC.

**Most likely path (Base):** Growth follows consensus for FY2027-28, then gradually decelerates to mid-teens as the law of large numbers applies; margins expand in line with management's FY2029 operating model (28-32% non-GAAP op margin); SBC declines as a percentage of revenue.

**What could go wrong (Bear):** Microsoft bundling (E7 Frontier Suite + free Security Copilot) compresses win rates in enterprise; AI disruption commoditizes traditional security telemetry advantages; NRR continues declining below 110%; SBC remains elevated, preventing real economic margin expansion.

### Revenue Projection — Base Case Detail

| Year | Revenue ($M) | YoY Growth | FCF Margin | FCF ($M) | Discount Factor | PV of FCF ($M) |
|------|-------------|------------|------------|----------|-----------------|-----------|
| 1 (FY2027) | $5,900 | 22.6% | 30.0% | $1,770 | 0.909 | $1,609 |
| 2 (FY2028) | $7,079 | 20.0% | 31.0% | $2,195 | 0.826 | $1,814 |
| 3 (FY2029) | $8,354 | 18.0% | 32.0% | $2,673 | 0.751 | $2,008 |
| 4 (FY2030) | $9,774 | 17.0% | 33.0% | $3,225 | 0.683 | $2,203 |
| 5 (FY2031) | $11,338 | 16.0% | 34.0% | $3,855 | 0.621 | $2,394 |
| 6 (FY2032) | $13,038 | 15.0% | 34.5% | $4,498 | 0.564 | $2,539 |
| 7 (FY2033) | $14,864 | 14.0% | 35.0% | $5,202 | 0.513 | $2,670 |
| Terminal Value | — | 3.0% | 35.0% | — | 0.513 | $39,281 |

### Valuation Summary — All Three Scenarios

| | Bull | Base | Bear |
|---|------|------|------|
| PV of Cash Flows ($M) | $17,927 | $15,236 | $11,784 |
| PV of Terminal Value ($M) | $65,141 | $39,281 | $21,084 |
| Enterprise Value ($M) | $83,068 | $54,517 | $32,868 |
| Net Cash ($M) | $4,480 | $4,480 | $4,480 |
| Equity Value ($M) | $87,548 | $58,997 | $37,348 |
| Fully Diluted Shares (M) | 260 | 260 | 260 |
| **Per Share Value** | **$337** | **$227** | **$144** |
| Upside / (Downside) | (8%) | (38%) | (61%) |
| TV as % of Total | **78%** ⚠️ | **72%** ⚠️ | 64% |
| Round-trip check: Implied EV/NTM Rev | 14.0x | 9.2x | 5.6x |

**⚠️ TERMINAL VALUE WARNING:** In both the Bull (78%) and Base (72%) cases, terminal value exceeds 70% of total value. This means the valuation is dominated by long-term assumptions about growth and margins 7+ years out, not near-term fundamentals. These valuations are inherently speculative.

**Round-trip check:** The base case implies 9.2x NTM revenue — reasonable for a 22% grower with 30%+ FCF margins but a meaningful discount to the current 15.7x. The bull case implies 14.0x — still below the current 15.7x. **The current multiple is above even our bull case DCF-implied multiple.**

### SBC-Adjusted Forward DCF — Base Case

This is the economically honest version. SBC is a real cost to shareholders through dilution. Assuming SBC declines from 21.5% to 15% of revenue over 7 years (aggressive improvement):

| Year | Revenue | Reported FCF Margin | SBC % Rev | SBC-Adj FCF Margin | Adj FCF ($M) |
|------|---------|-------------------|-----------|-------------------|-------------|
| 1 | $5,900 | 30.0% | 21.5% | 8.5% | $501 |
| 2 | $7,079 | 31.0% | 20.0% | 11.0% | $779 |
| 3 | $8,354 | 32.0% | 19.0% | 13.0% | $1,086 |
| 4 | $9,774 | 33.0% | 18.0% | 15.0% | $1,466 |
| 5 | $11,338 | 34.0% | 17.0% | 17.0% | $1,927 |
| 6 | $13,038 | 34.5% | 16.0% | 18.5% | $2,412 |
| 7 | $14,864 | 35.0% | 15.0% | 20.0% | $2,973 |

**SBC-Adjusted Valuation:**

| | Value |
|---|------|
| PV of SBC-Adj Cash Flows | $7,001M |
| PV of Terminal Value (at 20% adj margin) | $22,446M |
| Enterprise Value | $29,447M |
| Equity Value | $33,927M |
| **Per Share** | **$130** |
| **Downside from current** | **(65%)** |

The SBC-adjusted DCF produces a devastating result: $130 per share, or 65% below the current price. Even if SBC drops to 15% of revenue (from 22.8% today — a major improvement), the stock is worth roughly one-third of its current price on an economic free cash flow basis. This is the valuation the market is ignoring. The bull case for CRWD requires believing that SBC will decline dramatically as revenue scales — possible but unproven.

---

## VALUATION METHOD 3: TRADING COMPS

### Peer Set — Cybersecurity Platform Companies

| Company | EV/NTM Rev | NTM Growth | FCF Margin | Rule of 40 | NRR | Growth-Adj Ratio |
|---------|------------|------------|------------|------------|-----|-----------------|
| **NET** | **26.4x** | 30% | 12.0% | 42 | 120% | 0.88 |
| **CRWD** | **15.7x** | 24% | 25.7% | 48 | 115% | **0.65** |
| FTNT | 8.9x | 12% | 32.5% | 47 | N/D | 0.74 |
| PANW | 8.1x | 33% (NGS) | 36.0% | 51 | 119% | 0.25 |
| ZS | 6.0x | 25% | 29.0% | 55 | 114% | 0.24 |
| CHKP | 5.8x | 6% | 43.0% | 49 | N/D | 0.97 |
| RBRK | 5.3x | 34% | 18.1% | 52 | >120% | 0.16 |
| OKTA | 3.6x | 11% | 30.0% | 42 | 106% | 0.33 |
| S | 3.5x | 22% | 5.0% | 27 | 109% | 0.16 |

### Target Company Positioning

- **Growth rank:** 5th of 9 peers (24% ARR growth)
- **Profitability rank:** 4th of 9 peers (25.7% FCF margin)
- **Rule of 40 rank:** 4th of 9 peers (48)
- **Current multiple vs. peer median (5.8x):** **Premium of 171%** (15.7x vs. 5.8x median)
- **Growth-adjusted ratio of 0.65:** 3rd most expensive (only NET at 0.88 and CHKP at 0.97 are worse)

### Moat-Adjusted Analysis

CRWD's premium is partially justified by the strongest competitive moat in cybersecurity: 97% GRR (best in class), 50% on 6+ modules, $1.69B Falcon Flex ARR, and Morningstar's "wide moat" designation. However, the premium's magnitude is extreme.

Comparable moat-quality peers: PANW (8.1x, similar moat breadth but lower growth-adjusted ratio) and ZS (6.0x, strong moat, similar growth). A "moat premium" of 2-4x over the peer median (5.8x) would imply 7.8-9.8x NTM revenue — still far below CRWD's current 15.7x.

### Fair Value Estimates

| Method | Multiple | Implied EV ($B) | Per Share | Upside/(Downside) |
|--------|----------|----------------|-----------|-------------------|
| Peer median | 6.0x | $35.4 | $153 | (58%) |
| Moat-adjusted median | 8.0x | $47.2 | $199 | (46%) |
| Platform leader premium | 10.0x | $59.0 | $244 | (34%) |
| Maximum defensible premium | 12.0x | $70.8 | $289 | (21%) |

**Fair value estimate:** Using 10.0x NTM revenue (a significant premium to all peers except NET, justified by CRWD's moat quality and platform breadth):

- **Implied share price: $244 (34% downside)**

Even at the maximum defensible premium of 12.0x — which would make CRWD the second most expensive security stock behind NET — the stock is 21% overvalued.

---

## VALUATION METHOD 4: PRECEDENT M&A COMPS

### Comparable Transactions (Last 3 Years)

| Date | Target | Acquirer | EV ($B) | EV/Rev | EV/ARR | Target Growth | Premium |
|------|--------|----------|---------|--------|--------|---------------|---------|
| Mar 2026 | Wiz | Google | $32.0 | ~40x+ | ~25-30x | ~100%+ | N/A (private) |
| Feb 2026 | CyberArk | PANW | $25.0 | ~30x | ~25x | ~20% | ~29% |
| Jan 2024 | Splunk | Cisco | $28.0 | ~7.5x | N/A | ~12% | ~31% |
| Jan 2026 | SGNL | CRWD | $0.74 | N/A | N/A | N/A | N/A |
| Jan 2026 | Seraphic | CRWD | $0.42 | N/A | N/A | N/A | N/A |
| Jul 2024 | Secureworks | Sophos/TB | $0.86 | ~1.5x | N/A | ~flat | ~28% |
| 2025 | Securiti | Veeam | $1.73 | N/A | N/A | N/A | N/A |
| 2025 | Red Canary | ZS | $0.68 | N/A | N/A | N/A | N/A |

### Takeout Valuation

**Sector handoff calibration:**
- High-growth targets (>30%): 10-15x ARR
- Growth-stage (15-30%): 6-10x ARR
- Strategic scarcity premium: +2-4x

CRWD at 24% ARR growth falls in the growth-stage range (6-10x). However, CRWD commands a strategic scarcity premium as the dominant pure-play endpoint/XDR platform with the strongest moat metrics in cybersecurity. Applicable range: 10-14x ARR.

| Multiple | Takeout EV ($B) | After 25% Control Premium Discount | Per Share | vs. Current |
|----------|----------------|-------------------------------------|-----------|-------------|
| 8x ARR | $42.0 | $31.5 | $138 | (62%) |
| 10x ARR | $52.5 | $39.4 | $169 | (54%) |
| 12x ARR | $63.0 | $47.3 | $199 | (46%) |
| 14x ARR | $73.5 | $55.1 | $229 | (38%) |

**Is a takeout realistic?** No. At $91B EV, CrowdStrike is too large for PE acquisition and too expensive for strategic buyers. The only potential acquirers at this scale would be Microsoft, Google, Amazon, or Cisco — and antitrust concerns would be severe for the first three. The M&A comp method serves as a theoretical floor rather than a realistic scenario. A takeout is not a credible near-term catalyst.

**Probability-weighted takeout floor:** Using 12x ARR (top end for growth-stage) with 5% probability of takeout and 25% control premium discount: ~$199 per share. This is not actionable.

---

## VALUATION METHOD 5: SUM-OF-PARTS

### Segment Decomposition

CrowdStrike discloses sub-segment ARR for its fastest-growing areas. Total ending ARR of $5,250M can be decomposed:

| Segment | ARR ($M) | YoY Growth | Comparable Pure-Play | Multiple Applied | Implied EV ($B) |
|---------|----------|------------|---------------------|-----------------|-----------------|
| Core Endpoint/XDR | ~$3,345 | ~15% | Legacy endpoint (S, PANW Cortex) | 8.0x ARR | $26.8 |
| Cloud Security (CNAPP) | ~$800 | ~35% | Wiz (pre-acq), PANW Prisma Cloud | 20.0x ARR | $16.0 |
| Identity Security | $520 | 34% | CyberArk/PANW ($25B deal), OKTA | 12.0x ARR | $6.2 |
| Next-Gen SIEM (LogScale) | $585 | 75% | PANW XSIAM, Cisco/Splunk | 15.0x ARR | $8.8 |

**Methodology notes:**
- Core Endpoint/XDR: The mature foundation. Growth has decelerated to ~15% as the installed base matures. Valued at 8.0x (below PANW's 8.1x NTM, appropriate for a lower-growth mature segment).
- Cloud Security: Highest growth sub-segment. Wiz was acquired at ~25-30x ARR but was growing 100%+. At 35% growth, 20x is generous but reflects the strategic value of CNAPP.
- Identity: CyberArk's acquisition at ~25x ARR (by PANW) sets the ceiling. At 34% growth with smaller scale, 12x is conservative.
- NG-SIEM: 75% growth rate is exceptional. Cisco paid ~7.5x revenue for Splunk (low growth). At 75% growth, 15x is aggressive but supported by the competitive positioning.

### Sum-of-Parts Valuation

| Component | Value ($M) |
|-----------|-----------|
| Total Segment EV | $57,760 |
| Plus: Net Cash | $4,480 |
| **Equity Value** | **$62,240** |
| **Per Share** | **$239** |
| **Upside / (Downside)** | **(35%)** |

**Hidden Value Flag:** The NG-SIEM and Identity businesses are growing at 75% and 34% respectively and may be undervalued in the current blended multiple. At standalone pure-play multiples, these segments could be worth $5-10B more. However, even with aggressive segment-level premiums, the sum-of-parts cannot justify the current $91B EV. The Core Endpoint segment, which represents ~64% of ARR, is the anchor dragging the blended valuation down — its growth has decelerated to mid-teens.

---

## VALUATION METHOD 6: PE / LBO FLOOR

### Growth Equity Framework (No Leverage)

CrowdStrike's $91B EV makes a traditional LBO impossible. No PE fund can write a $90B+ equity check. This analysis uses a growth equity framing: pure equity, 25% IRR target, no leverage.

**Entry Assumptions:**
- Entry EV: $100.3B (current EV + 10% control premium)
- Debt: $0 (growth equity, no leverage)
- Equity invested: $100.3B

### 5-Year Projection

| Year | Revenue ($M) | Growth | FCF Margin | FCF ($M) | Cumulative FCF ($M) |
|------|-------------|--------|------------|----------|---------------------|
| 1 | $5,871 | 22% | 30% | $1,761 | $1,761 |
| 2 | $7,045 | 20% | 31% | $2,184 | $3,945 |
| 3 | $8,313 | 18% | 33% | $2,743 | $6,688 |
| 4 | $9,726 | 17% | 34% | $3,307 | $9,995 |
| 5 | $11,282 | 16% | 35% | $3,949 | $13,944 |

**Exit Assumptions:**
- Exit NTM Revenue: ~$12,975M (Year 5 revenue × 1.15)
- Exit multiple: 12.0x NTM Revenue (modest compression from current 15.7x)
- Exit EV: $155.7B
- Total return: 1.69x over 5 years (entry at $100.3B, exit at $155.7B + $13.9B cumulative FCF)
- **Implied IRR: 11.1%** — well below the 20% hurdle rate

### Floor Price Calculation

| Metric | Value |
|--------|-------|
| Required exit value (for 20% IRR) | $249.5B |
| Max entry EV for 20% IRR at projected exit | $68.2B |
| Max entry per share | **$279** |
| Current price | $368 |
| **Downside to PE floor** | **(24%)** |

**REALITY CHECK:** A PE acquisition of CrowdStrike is not realistic at any price near current levels. At $91B EV, it would be the largest technology LBO in history by a factor of 5x. Even the most aggressive growth equity investor cannot achieve target returns at these levels. The PE floor of $279 represents the theoretical maximum a rational financial buyer would pay — the current price exceeds this by 32%.

---

## TRIANGULATION & FINAL OUTPUT

### DELIVERABLE 1: PRICE TARGET RANGE & CONVICTION SCORE

```
━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━
TICKER: CRWD
CURRENT PRICE: $368
ANALYSIS DATE: March 29, 2026

METHOD RESULTS:
| Method              | Bear  | Base  | Bull  | Weight | Confidence |
|---------------------|-------|-------|-------|--------|------------|
| Reverse DCF         | —     | Implies 22.9% 10yr CAGR (aggressive) | — | —   | H |
| Forward DCF         | $144  | $227  | $337  | 40%    | H          |
| Forward DCF (SBC-adj)| —    | $130  | —     | *      | H          |
| Trading Comps       | $153  | $244  | $289  | 25%    | H          |
| M&A Comps           | $138  | $199  | $229  | 10%    | M          |
| Sum-of-Parts        | —     | $239  | —     | 15%    | M          |
| PE/LBO Floor        | $279  | —     | —     | 10%    | L          |

* SBC-adjusted DCF not separately weighted but informs conviction.
  It represents the "economic reality" check on reported FCF.

WEIGHTED TRIANGULATION:
- Forward DCF (40%): $227 base × 0.40 = $90.8
- Trading Comps (25%): $244 base × 0.25 = $61.0
- Sum-of-Parts (15%): $239 × 0.15 = $35.9
- M&A Comps (10%): $199 × 0.10 = $19.9
- PE/LBO Floor (10%): $279 × 0.10 = $27.9

TRIANGULATED PRICE TARGET:
- Bear case: $155 (58% downside)
- Base case: $236 (36% downside)
- Bull case: $330 (10% downside)

CONVICTION SCORE: 4 (High — Overvalued)

All six methods converge on the same conclusion: CrowdStrike is
materially overvalued at $368. Even the bull case ($330-337)
sits below the current price. The methods show remarkable
agreement — the base case clusters around $227-$244 across
DCF, trading comps, and sum-of-parts.

CONVICTION RATIONALE:
CrowdStrike is an exceptional franchise — arguably the strongest
competitive moat in cybersecurity (97% GRR, 50% on 6+ modules,
wide Morningstar moat). But exceptional franchises can still be
overpriced. At 15.7x NTM revenue with a growth-adjusted ratio
of 0.65 (3rd most expensive in the peer set), the market is
pricing in ~23% sustained growth for a decade and ignoring the
22.8% SBC burden that reduces economic FCF margin to 2.9%. The
stock trades above even our most optimistic bull case DCF.
This is not a buy at current levels for a fundamental investor.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### Weight Justification

- **Forward DCF at 40%:** Highest weight because CrowdStrike has highly predictable, recurring revenue (95% subscription), clear margin trajectory (FY2029 target operating model), and 12 quarters of consistent execution. The base case uses consensus estimates for Years 1-2 and reasonable deceleration thereafter. Confidence: HIGH.

- **Trading Comps at 25%:** The peer set is well-defined (16 cybersecurity companies with complete data) and the sector handoff provides calibrated benchmarks. CRWD's premium to peers is measurable and persistent. Confidence: HIGH.

- **Sum-of-Parts at 15%:** CRWD has meaningful segment disclosure (identity, SIEM, cloud each separately reported) and the segments have materially different growth profiles. This method reveals that the high-growth segments (SIEM at 75%, Cloud at 35%) cannot offset the mature endpoint core on a blended basis. Confidence: MEDIUM.

- **M&A Comps at 10%:** Theoretical only — CRWD is too large for a realistic takeout. The method provides a floor reference but low practical applicability. Confidence: MEDIUM.

- **PE/LBO Floor at 10%:** Pure downside reference. At $91B EV, no PE buyer can achieve target returns. Confidence: LOW (for applicability, not methodology).

### Key Disagreements Between Methods

The methods agree more than they disagree. The narrow range of base cases ($199-$244, excluding the PE floor) reflects genuine convergence. The primary source of remaining disagreement is the appropriate moat premium:

- **Trading comps at peer median (6x)** produce $153 — this undervalues CRWD's moat
- **Trading comps with moat premium (10x)** produce $244 — this is closer to fair value
- **DCF at base case** produces $227 — confirming the 10x comps estimate

The SBC-adjusted DCF at $130 is the outlier on the downside. It represents the economic reality that SBC is a real cost, but the market has consistently been willing to ignore SBC in high-growth SaaS valuations. If/when the market re-prices SBC-heavy names (as happened in 2022), the downside is severe.

---

### DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━
TICKER: CRWD
COMPANY: CrowdStrike Holdings, Inc.
SECTOR: Cybersecurity (Endpoint / XDR / AI Platform)
VALUATION DATE: March 29, 2026

PRICE TARGET: $236 base case (range: $155 bear — $330 bull)
CURRENT PRICE: $368
UPSIDE TO BASE: -36% (DOWNSIDE)
CONVICTION: 4 (High conviction that stock is overvalued)

WHEEL STRATEGY IMPLICATIONS:

- SELL PUTS: NO
  Rationale: Stock is 56% ABOVE base case price target. Selling
  puts at current levels means accepting assignment at a price
  well above fair value. Every valuation method — including the
  bull case — says the stock is overvalued here. The risk/reward
  is unfavorable for put sellers.
  
  IF you insist on selling puts:
  - Absolute floor strike: $155 (bear case)
  - Maximum tolerable strike: $200 (near SoP and M&A floor)
  - Avoid puts above: $250 (above base case = negative EV)

- COVERED CALLS (if already own shares): YES — AGGRESSIVELY
  Rationale: If assigned, the stock is reducing from an
  overvalued position. Sell calls at or above cost basis to
  monetize the overvaluation.
  - Minimum call strike: Cost basis (per cc_min_strike_pct=1.0)
  - Suggested call strike zone: $370-$420 (near current price)
  - Aggressive approach justified: selling at $368-$420 is
    selling at 56-78% above base case fair value

- CONCENTRATED LONG CANDIDATE: NO
  Rationale: Conviction ≥ 4 BUT upside to base case is NEGATIVE
  (-36%). This is a sell candidate, not a buy candidate. The
  strongest moat in cybersecurity does not justify paying 15.7x
  NTM revenue when peers with comparable or better growth trade
  at 5-8x.

ENTRY PRICE FOR WHEEL CONSIDERATION:
  At $230-$250: CONDITIONAL — near base case, moat justifies
  engagement but only with strict discipline
  At $200 or below: YES — approaching bear case with significant
  margin of safety; the franchise quality becomes compelling
  At $155 or below: STRONG YES — below bear case; the moat and
  growth profile are significantly undervalued

KEY DATES TO AVOID (earnings, catalysts):
- Early June 2026: Q1 FY2027 earnings
- Late September 2026: Q2 FY2027 earnings
- March 23-26, 2026: RSA Conference (just completed)
- Ongoing: Anthropic Mythos AI disruption narrative

SECTOR CONTEXT:
- Sector score: 21/25 (Rank #3 of 16)
- Sector EV/NTM median: ~5.8x (CRWD at 15.7x = 171% premium)
- Sector-level risk: Microsoft bundling (HIGH), AI disruption
  narrative (MEDIUM), SaaS valuation regime reset (MEDIUM)
- Sector spending growth: +12.5% to $240B (Gartner 2026 forecast)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## APPENDIX: VALUATION QUALITY CROSS-CHECKS

### 1. Round-Trip Multiple Check

| Scenario | Implied EV ($B) | Implied EV/NTM Rev | Peer Context |
|----------|----------------|-------------------|--------------|
| Bull DCF | $83.1 | 14.0x | Still below current 15.7x |
| Base DCF | $54.5 | 9.2x | Between PANW (8.1x) and current |
| Bear DCF | $32.9 | 5.6x | In line with ZS (6.0x) |

The base case DCF-implied multiple of 9.2x is reasonable for a 22% grower with 30% FCF margins. The current 15.7x is not.

### 2. Terminal Value Discipline

| Scenario | TV % of Total | Assessment |
|----------|--------------|------------|
| Bull | 78% | ⚠️ SPECULATIVE — dominated by 7+ year assumptions |
| Base | 72% | ⚠️ SPECULATIVE — marginal fail of 70% threshold |
| Bear | 64% | Acceptable |

The Bull and Base cases are heavily terminal-value-driven. This means the valuation is sensitive to assumptions about events 7+ years in the future. Any investor relying on these valuations should acknowledge this inherent uncertainty.

### 3. SBC Honesty Summary

| Metric | Reported | SBC-Adjusted | Gap |
|--------|----------|-------------|-----|
| FY2026 FCF margin | 25.7% | 2.9% | **22.8pp** |
| Base case per share | $227 | $130 | **43% gap** |
| FY2029 target FCF margin | 34-38% | ~14-18% (if SBC = 20%) | **20pp gap** |

The 22.8 percentage point gap between reported and SBC-adjusted FCF margin is the largest in the cybersecurity peer set and among the largest in all of SaaS. Management guides SBC declining as a percentage of revenue, but it has increased from 20.7% to 22.8% over the past three years. Until SBC actually declines, the reported FCF margin overstates economic reality by a factor of 8.9x (25.7% / 2.9%).

### 4. Analyst Consensus vs. This Analysis

| Metric | Analyst Consensus | This Analysis (Base) |
|--------|------------------|---------------------|
| Average price target | ~$490-$510 | $236 |
| Implied upside | +32-37% | -36% |
| Rating | 38 Buy / 15 Hold / 0 Sell | Overvalued |

The gap between sell-side consensus ($490-510) and this fundamental analysis ($236) is stark. Sell-side analysts are valuing CRWD on reported FCF multiples and momentum, not SBC-adjusted economics. The sell-side consensus of zero Sell ratings on a stock that trades above its own bull case DCF is a strong contrarian signal.

### 5. What Would Make This Wrong

This analysis would be wrong — and CRWD would be fairly valued or undervalued at $368 — if:

1. **SBC drops to 10-12% of revenue within 3 years** (from 22.8% today). This would close the FCF gap and validate reported margins. Evidence needed: declining equity awards, accelerating buybacks, SBC % declining in each quarter.

2. **Revenue growth reaccelerates to 25%+** and sustains above 20% for 5+ years. The current Reverse DCF implies 22.9% — if CRWD demonstrates this is achievable through AI-driven TAM expansion, the implied valuation normalizes.

3. **The cybersecurity TAM expands faster than expected** (15%+ CAGR vs. Gartner's 11%), driven by AI threat escalation and regulatory mandates, allowing CRWD to sustain growth at premium levels for longer.

4. **A takeout materializes** at 14x+ ARR ($73.5B+), which would imply $300+ per share. This requires a ~$100B+ acquisition — conceivable only from Microsoft, Google, or Amazon, and fraught with regulatory risk.

None of these scenarios is impossible, but none should be assumed. The fundamental analysis says: wait for a better price.
