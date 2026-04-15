# RUBRIK, INC. (RBRK) — INVESTMENT-GRADE VALUATION

**Analysis Date:** March 29, 2026
**Current Price:** $48.00
**Sector:** Cybersecurity / Data Security / Cyber Resilience
**Fiscal Year End:** January 31

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency

| Method | Required Data | Status | Notes |
|--------|--------------|--------|-------|
| DCF | ≥8 quarters revenue + FCF, guidance, consensus, shares, net debt | ✅ COMPLETE | 12 quarters of revenue; FY2025–FY2026 FCF; FY2027 guidance and consensus through FY2028 |
| Trading Comps | Peer multiples | ✅ COMPLETE | Full sector handoff with 16 companies scored and benchmarked |
| M&A Comps | Transaction multiples | ⚠️ PARTIAL | Sector handoff provides M&A ranges and recent deals; no direct data protection M&A within last 12 months at comparable scale |
| Sum-of-Parts | Segment-level revenue | ⚠️ PARTIAL | RBRK does not report segments; estimated from NRR contribution disclosure (45% from security products) |
| LBO | FCF, debt capacity, EV | ✅ COMPLETE | FCF trajectory clear; growth equity framing used given pre-GAAP-profit status |

### Check 2: Fiscal Year Alignment

Rubrik's fiscal year ends **January 31**. FY2026 = Feb 1, 2025 – Jan 31, 2026. FY2027 = Feb 1, 2026 – Jan 31, 2027. All data is mapped to Rubrik's fiscal year convention. Peers CrowdStrike (Jan 31) and SentinelOne (Jan 31) are aligned; Palo Alto (Jul 31), Zscaler (Jul 31), and Cloudflare (Dec 31) are offset. Comp multiples use NTM estimates regardless of FY-end to ensure comparability.

### Check 3: Share Count Reconciliation

| Component | Shares (M) |
|-----------|-----------|
| Basic shares outstanding (Jan 31, 2026) | 200.1 |
| Dilutive stock options + RSUs + ESPP | ~13.6 |
| Convertible note if-converted shares | ~9.2 |
| Non-GAAP diluted shares (Q4 FY2026 reported) | 223.6 |
| Estimated fully diluted (incl. all unvested) | ~227–232 |
| **Used for all per-share calculations** | **230.0** |

Rationale: Using 230M fully diluted shares aligns with FY2027 guided diluted share count of ~232M. This captures all potential dilution from options, RSUs, ESPP, and convertible notes (despite conversion price of ~$125 being far above current price, the if-converted method is the conservative standard). The capped call structure mitigates actual dilution from converts between $125 and $175.

### Check 4: SBC Materiality Assessment

| Metric | FY2024 | FY2025 | FY2026 |
|--------|--------|--------|--------|
| SBC Expense | $5.7M | $913.9M | $329.4M |
| SBC % of Revenue | 0.9% | 103.1% | 25.0% |
| FCF | ($24.5M) | $21.6M | $237.8M |
| FCF ex-SBC | ($30.2M) | ($892.3M) | ($91.6M) |

**⚠️ SBC FLAG TRIGGERED: 25% of revenue exceeds 15% threshold.** All FCF-based valuations present BOTH FCF and FCF-ex-SBC versions. The $329.4M gap between reported FCF ($237.8M) and FCF-ex-SBC (−$91.6M) is the single most important number in this valuation. Under FCF, RBRK appears to be generating 18.1% margins; under FCF-ex-SBC, it is still consuming cash. SBC is expected to decline as a percentage of revenue (FY2025's $913.9M was an IPO artifact), but at 25%, it remains materially elevated. For context, the sector median is ~20%, and genuinely capital-efficient peers like Fortinet (4.1%) and Check Point (5.9%) show how wide the gap can be.

---

## VALUATION METHOD 1: REVERSE DCF

**Purpose:** What growth rate is the current market price implying?

### Setup

| Input | Value | Source |
|-------|-------|--------|
| Current Enterprise Value | $9,079M | Market cap ($48 × 200.1M) − net cash ($526M) |
| Base Year Revenue | $1,316.2M | FY2026 actual |
| Current FCF Margin | 18.1% | FY2026 actual |
| Terminal FCF Margin | 30.0% | Sector benchmark: scaled SaaS at $3B+ ARR achieve 25–35% (PANW 36%, ZS 29%, OKTA 30%) |
| Terminal Growth Rate | 3.0% | GDP-like perpetuity |
| WACC | 10.0% | Standard for high-growth SaaS; pre-profit stage adds risk |
| Time to Terminal State | 10 years | Standard |
| FCF Margin Ramp | Linear from 18.1% → 30.0% | |

### Results

**Implied Revenue CAGR: ~10%**

| Comparison | Growth Rate |
|------------|-------------|
| **Market-implied CAGR** | **~10%** |
| FY2026 actual revenue growth | 48% |
| FY2026 subscription ARR growth | 34% |
| Consensus FY2027 revenue growth | 24.6% |
| Management FY2027 guidance (normalized) | 27–28% |
| Management long-term ARR growth target | 25%+ |

**GAP ANALYSIS:** The market is pricing in ~10% revenue CAGR vs. 25–28% actual/guided. This implies the market expects growth to decelerate *dramatically* — from 48% today to roughly 10% on average over the next decade. While deceleration is inevitable as the base scales, the magnitude of the gap is extreme. Even the most bearish scenario in which growth halves every two years yields a 10-year CAGR well above 10%. The market is either pricing in (a) severe competitive destruction from Cohesity-Veritas or hyperscaler-native backup, (b) a structural inability to sustain margins, or (c) a general SaaS multiple compression that has nothing to do with RBRK's fundamentals.

→ **Market is pricing in excessive deceleration. The stock appears meaningfully undervalued on a reverse DCF basis.**

### Sensitivity: Implied Revenue CAGR by WACC and Terminal FCF Margin

| WACC \ Terminal FCF Margin | 20% | 25% | 30% | 35% |
|----------------------------|-----|-----|-----|-----|
| 9% | 12.3% | 9.8% | 7.8% | 6.1% |
| **10%** | **14.7%** | **12.1%** | **10.0%** | **8.3%** |
| 11% | 16.9% | 14.3% | 12.1% | 10.4% |
| 12% | 19.0% | 16.3% | 14.1% | 12.3% |

Even at a punitive 12% WACC and pessimistic 20% terminal FCF margin, the market only implies ~19% revenue CAGR — still below current consensus. At reasonable assumptions, the implied growth is far below any credible projection.

---

## VALUATION METHOD 2: FORWARD DCF (3-SCENARIO)

**Purpose:** Estimate intrinsic value under bull, base, and bear assumptions.

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|------------|------|------|------|
| Yr 1–2 Revenue CAGR | 28% / 26% | 25% / 22% | 20% / 16% |
| Yr 3–5 Revenue CAGR | 24% → 20% | 19% → 15% | 13% → 9% |
| Yr 6–7 Revenue CAGR | 18% → 16% | 13% → 12% | 8% → 7% |
| Terminal FCF Margin | 34% | 30% | 25% |
| Terminal Growth Rate | 3.5% | 3.0% | 3.0% |
| WACC | 9.5% | 10.0% | 11.0% |
| SBC ramp (% of rev) | 23% → 12% | 23% → 12% | 23% → 12% |

**What must go right (Bull):** Subscription ARR growth sustains above 25% for 3+ years. Identity product ($900+ customers) becomes a $500M+ ARR business by FY2029. SAGE (AI governance) opens new TAM. Cohesity-Veritas integration stumbles. FCF margins reach top-quartile by Year 5. Macro stays supportive.

**What could go wrong (Bear):** Cohesity-Veritas IPO succeeds and wins share aggressively. Hyperscaler-native backup (Azure Backup, AWS Backup) commoditizes the core product. CRO transition disrupts sales execution. Growth decelerates faster than guided as the ~$52M material rights revenue tailwind falls off. SBC remains elevated, preventing real economic profitability.

### Revenue Projection — Base Case

| Year | Revenue ($M) | YoY Growth | FCF Margin | FCF ($M) | SBC % | FCF ex-SBC ($M) |
|------|-------------|------------|------------|----------|-------|-----------------|
| 1 (FY2027) | $1,645 | 25% | 18% | $296 | 23% | ($82) |
| 2 (FY2028) | $2,007 | 22% | 20% | $401 | 21% | ($20) |
| 3 (FY2029) | $2,389 | 19% | 23% | $549 | 19% | $96 |
| 4 (FY2030) | $2,795 | 17% | 25% | $699 | 17% | $224 |
| 5 (FY2031) | $3,214 | 15% | 27% | $868 | 15% | $386 |
| 6 (FY2032) | $3,632 | 13% | 29% | $1,053 | 13% | $581 |
| 7 (FY2033) | $4,067 | 12% | 30% | $1,220 | 12% | $732 |

Note: Year 1 base case revenue of $1,645M is closely aligned with consensus ($1,640M), reflecting management's conservative guidance history (5 consecutive quarters of 7–11% revenue beats).

### Valuation Summary

| | Bull | Base | Bear |
|---|------|------|------|
| PV of Cash Flows | $4,337M | $3,250M | $2,169M |
| PV of Terminal Value | $16,390M | $9,214M | $4,488M |
| Enterprise Value | $20,727M | $12,464M | $6,656M |
| Net Cash | $526M | $526M | $526M |
| Equity Value | $21,253M | $12,990M | $7,182M |
| Fully Diluted Shares | 230M | 230M | 230M |
| **Per Share Value (FCF)** | **$92.40** | **$56.48** | **$31.23** |
| **Per Share Value (FCF ex-SBC)** | **$56.24** | **$31.00** | **$14.20** |
| Upside / (Downside) from $48 | +92.5% | +17.7% | −34.9% |
| TV as % of Total | 79.1% | 73.9% | 67.4% |

**⚠️ Terminal Value Warning:** TV exceeds 70% of total value in both bull (79.1%) and base (73.9%) cases. This means the valuation is dominated by long-term assumptions about growth sustainability and margin expansion, not near-term fundamentals. The bear case (67.4%) is the only scenario where near-term cash flows contribute meaningfully.

**⚠️ SBC Warning — The FCF-vs-FCF-ex-SBC Gap Is Enormous:**
- Bull: $92.40 (FCF) vs. $56.24 (ex-SBC) — a 39% haircut
- Base: $56.48 (FCF) vs. $31.00 (ex-SBC) — a 45% haircut
- Bear: $31.23 (FCF) vs. $14.20 (ex-SBC) — a 55% haircut

If you treat SBC as a real cost (which it is — it dilutes shareholders), the base case drops from $56 to $31. This is the central tension in RBRK's valuation: the FCF-based story is compelling, but the economic reality of 25% SBC-to-revenue tells a much more cautious tale.

### Round-Trip Check

| Case | Implied EV | EV / NTM Revenue |
|------|-----------|-----------------|
| Bull | $20,727M | 12.6x |
| Base | $12,464M | 7.6x |
| Bear | $6,656M | 4.1x |

Reasonableness: Base case implies 7.6x NTM revenue. For a company growing 25% with improving FCF margins and a Rule of 40 score of 52, 7.6x is in line with high-quality cybersecurity peers (PANW at 8.1x with 33% NGS ARR growth, ZS at 6.0x with 25% ARR growth). Bull case at 12.6x would require RBRK to trade closer to CRWD territory (15.7x) — possible only with sustained 25%+ growth and proven profitability. Bear case at 4.1x prices RBRK like a low-growth value play (comparable to QLYS at 4.1x with 10% growth). All three pass the reasonableness test.

---

## VALUATION METHOD 3: TRADING COMPS

**Purpose:** Where does RBRK sit relative to peers on a multiples basis?

### Peer Set

| Company | EV/NTM Rev | NTM Growth | Growth-Adj Ratio | Rule of 40 | FCF Margin | NRR |
|---------|------------|------------|-------------------|------------|------------|-----|
| CRWD | 15.7x | 24% | 0.65 | 48 | 25.7% | 115% |
| NET | 26.4x | 30% | 0.88 | 42 | 12.0% | 120% |
| PANW | 8.1x | 33%* | 0.25 | 51 | 36.0% | ~119% |
| ZS | 6.0x | 25% | 0.24 | 55 | 29.0% | ~114% |
| SAIL | 5.2x | 28% | 0.19 | 46 | 4.9% | 113% |
| NTSK | 3.3x | 31% | 0.11 | 34 | 1.7% | N/D |
| S | 3.5x | 22% | 0.16 | 27 | 5.0% | 109% |
| **RBRK** | **5.3x** | **34%** | **0.16** | **52** | **18.1%** | **>120%** |

*PANW growth uses NGS ARR growth rate, which is the operationally relevant metric.

### Target Company Positioning

- **Growth rank:** 1st of 8 peers (34% sub ARR growth; 48% revenue growth)
- **Profitability rank (Rule of 40):** 3rd of 8 (52, behind ZS at 55 and PANW at 51)
- **FCF Margin rank:** 4th of 8 (18.1%, behind PANW 36%, ZS 29%, CRWD 25.7%)
- **Current multiple vs. peer median:** 5.3x vs. median of ~5.6x — roughly in line
- **Growth-adjusted ratio vs. peer median:** 0.16 vs. median of ~0.24 — **cheapest in peer set tied with S**

### Assessment

RBRK has the highest growth rate in the peer set and a top-3 Rule of 40 score, yet trades at a growth-adjusted ratio (0.16) tied for the lowest in the group. The market is applying a discount for: (1) pre-GAAP profitability, (2) convertible debt overhang, (3) recent IPO with limited public track record, and (4) sub-sector perception (data protection < endpoint/SASE in investor narrative). 

RBRK **deserves a premium** to the low-growth value names (TENB, QLYS, OKTA) but a **discount** to platform leaders (CRWD, PANW) given shorter public history and narrower competitive moat. Fair range: 7.0–9.0x NTM revenue, based on growth-adjusted regression against peers with comparable growth and profitability profiles.

### Fair Value Estimate

| Method | Fair EV/NTM Rev | Implied EV ($M) | Implied Share Price | Upside/(Downside) |
|--------|----------------|-----------------|--------------------|--------------------|
| Peer median (at RBRK's growth-adj) | 7.0x | $11,480 | $52.20 | +8.8% |
| **Growth-weighted fair value** | **8.0x** | **$13,120** | **$59.33** | **+23.6%** |
| Premium tier (PANW-comparable) | 9.0x | $14,760 | $66.46 | +38.5% |

Using 8.0x NTM revenue as fair value (between ZS at 6.0x with 25% growth and PANW at 8.1x with 33% growth — RBRK's 34% growth justifies at least parity with PANW), the implied share price is **$59.33**, representing 23.6% upside.

---

## VALUATION METHOD 4: PRECEDENT M&A COMPS

**Purpose:** What would a strategic or financial acquirer pay?

### Comparable Transactions

| Date | Target | Acquirer | EV ($B) | EV/Rev | EV/ARR | Target Growth | Premium |
|------|--------|----------|---------|--------|--------|---------------|---------|
| Feb 2026 | CyberArk | PANW | $25.0B | ~39x | ~32x | ~23% | ~29% |
| Mar 2026 | Wiz | Google | $32.0B | ~64x | ~40x | ~50%+ | N/A (private) |
| 2025 | Securiti | Veeam | $1.7B | ~17x | ~15x | ~50%+ | N/A (private) |
| 2024 | Splunk | Cisco | $28.0B | ~7.6x | N/A | ~9% | ~31% |
| 2025 | SailPoint | IPO | $12.8B | ~12x | ~11x | ~28% | N/A (IPO) |
| 2025 | Secureworks | Sophos/TB | $0.86B | ~1.6x | N/A | ~2% | ~28% |
| 2024 | Lacework | Fortinet | Undiscl. | N/A | N/A | N/A | N/A |

### Takeout Valuation

RBRK's profile: $1,462M subscription ARR growing 34%, with cloud ARR at 88%, NRR >120%, and FCF margin of 18.1%. This places it firmly in the **high-growth (>30%) tier: 10–15x ARR**.

The sector handoff calibrates M&A multiples at:
- High-growth targets (>30%): 10–15x ARR
- Strategic scarcity premium: +2–4x

Rubrik occupies a unique position as the leading independent cyber resilience platform. Post the Cohesity-Veritas merger, Rubrik is the only remaining pure-play cloud-native data protection vendor at scale. Potential acquirers: PANW (expanding CyberArk + data security), Cisco (Splunk + data), Microsoft (Azure Backup adjacency), or PE (Thoma Bravo pattern).

| Multiple | Raw EV ($M) | After 25% Control Premium Discount | Equity ($M) | Per Share |
|----------|------------|-------------------------------------|-------------|-----------|
| 10x ARR | $14,621 | $10,966 | $11,492 | **$49.96** |
| 12x ARR | $17,545 | $13,159 | $13,685 | **$59.50** |
| 15x ARR | $21,932 | $16,449 | $16,975 | **$73.80** |

**Probability-weighted note:** A takeout is *plausible but not imminent*. RBRK is likely too large ($9.6B market cap) for most PE buyers absent significant leverage, and the dual-class share structure gives founders/VCs blocking control. A strategic acquisition by PANW, Cisco, or Microsoft would be feasible at 12–15x ARR. The Cohesity-Veritas merger and Google/Wiz deal establish that data security assets command premium multiples. However, management appears committed to independence given the founder-CEO structure and recent IPO. Takeout probability in the next 12 months: ~10–15%.

---

## VALUATION METHOD 5: SUM-OF-PARTS

**Purpose:** Are security products being undervalued when bundled with the core backup business?

### Segment Estimation

Rubrik does not report separate segments, but the Q4 FY2026 disclosure that **45% of subscription NRR comes from cross-selling security products** (up from 34% a year ago) provides a basis for estimation.

Applying this ratio to subscription ARR:
- Security products (ransomware recovery, data classification, identity resilience): ~45% × $1,462M = ~$658M ARR, estimated 50%+ growth
- Core data protection (backup/recovery, cloud migration): ~55% × $1,462M = ~$804M ARR, estimated ~20% growth

| Segment | ARR ($M) | Est. Growth | Comparable | Multiple Applied | Implied EV ($M) |
|---------|----------|------------|------------|------------------|-----------------|
| Core Data Protection | ~$804 | ~20% | Commvault (CVLT), Cohesity, Veeam | 5x ARR | $4,020 |
| Security Products | ~$658 | ~50%+ | DSPM peers (Cyera at 9B on ~$400M ARR), identity security | 10x ARR | $6,580 |
| **Total** | **$1,462** | | | | **$10,600** |

| | Value ($M) |
|---|-----------|
| Total EV | $10,600 |
| Plus: Net Cash | $526 |
| Equity Value | $11,126 |
| Per Share | **$48.37** |
| Upside / (Downside) | +0.8% |

### Hidden Value Flag

The SoP analysis reveals that the **security products business is being valued at $0** in the current stock price. The core data protection business alone, at 5x ARR, accounts for the entire current EV of ~$9.1B (plus a modest premium). This means the market is assigning zero value to:

- Identity resilience product (900+ customers, fastest-growing product in company history)
- Ransomware recovery warranty ($10M guarantee, never paid)
- Data classification / DSPM capabilities (comparable to Cyera at $9B valuation)
- SAGE AI governance engine (launched at RSA 2026)

If the security products segment achieves even half the valuation density of Cyera (~$9B on ~$400M ARR = ~23x), the implied EV contribution would be $7.5B+ — adding ~$33/share to the stock price.

### Limitations

This method has **low confidence** for RBRK because the company does not report segment-level economics, and the 45% NRR contribution ratio is an imperfect proxy for actual ARR split. The security products may have higher gross margins but also higher sales costs. Use directionally, not as a primary valuation tool.

---

## VALUATION METHOD 6: PE / LBO FLOOR

**Purpose:** What would a private equity buyer pay? This sets the downside floor.

### Framing

RBRK is pre-GAAP-profit with substantial SBC. Traditional LBO mechanics (leveraged buyout with 3–4x EBITDA debt) do not apply. Instead, this uses a **growth equity framework**: all-equity entry, 25% IRR target over 5 years.

### Entry Assumptions

| | Value |
|---|------|
| Entry EV | $10,895M (current EV × 1.20, reflecting 20% control premium) |
| Debt | $0 (growth equity, no leverage) |
| Equity Invested | $10,895M |

### 5-Year Projection (Base Case Cash Flows)

| Year | Revenue ($M) | Growth | FCF Margin | FCF ($M) | Cumulative FCF |
|------|-------------|--------|-----------|----------|----------------|
| 1 | $1,645 | 25% | 18% | $296 | $296 |
| 2 | $2,007 | 22% | 20% | $401 | $698 |
| 3 | $2,389 | 19% | 23% | $549 | $1,247 |
| 4 | $2,795 | 17% | 25% | $699 | $1,946 |
| 5 | $3,214 | 15% | 27% | $868 | $2,813 |

### Exit Assumptions

| | Value |
|---|------|
| Exit Multiple | 7.0x NTM Revenue (vs. 5.5x entry EV/NTM Rev) |
| Year 5 Revenue | $3,214M |
| NTM Revenue (Year 6 est.) | $3,599M (12% growth assumed) |
| Exit EV | $25,196M |
| Equity at Exit (EV + Cum FCF) | $28,010M |
| Implied IRR | 20.8% |

### Floor Price

| | Value |
|---|------|
| Max Entry EV for 25% IRR | $9,178M |
| Implied Floor Per Share | **$42.19** |
| Current Price | $48.00 |
| Downside to Floor | **−12.1%** |

**Reality Check:** PE interest in RBRK is realistic but constrained. The $9.6B market cap is at the upper end of growth equity check sizes. Thoma Bravo (which owns ~23 cybersecurity companies worth ~$58B EV) is the most likely PE buyer — but they already own Sailpoint in the adjacent identity governance space and might view RBRK as competitive overlap. Vista Equity Partners or Hellman & Friedman are alternatives. The dual-class structure would require founder consent for any take-private.

The floor price of $42.19 suggests **limited additional downside** from current levels — the stock has already priced in significant pessimism.

---

## TRIANGULATION & FINAL OUTPUT

---

### DELIVERABLE 1: PRICE TARGET RANGE & CONVICTION SCORE

```
━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
TICKER: RBRK
CURRENT PRICE: $48.00
ANALYSIS DATE: March 29, 2026

METHOD RESULTS:
┌────────────────────┬────────┬────────┬────────┬────────┬────────┐
│ Method             │  Bear  │  Base  │  Bull  │ Weight │ Confid │
├────────────────────┼────────┼────────┼────────┼────────┼────────┤
│ Reverse DCF        │   —    │ 10% implied vs 25%+ guided │  —  │   —    │   H    │
│ Forward DCF        │ $31.23 │ $56.48 │ $92.40 │  40%   │   H    │
│ Forward DCF ex-SBC │ $14.20 │ $31.00 │ $56.24 │  (ref) │   H    │
│ Trading Comps      │   —    │ $59.33 │   —    │  25%   │   H    │
│ M&A Comps          │ $49.96 │ $59.50 │ $73.80 │  15%   │   M    │
│ Sum-of-Parts       │   —    │ $48.37 │   —    │  10%   │   L    │
│ PE/LBO Floor       │ $42.19 │   —    │   —    │  10%   │   M    │
└────────────────────┴────────┴────────┴────────┴────────┴────────┘

TRIANGULATED PRICE TARGET:
  Bear case: $35 (−27% downside)
  Base case: $57 (+19% upside)
  Bull case: $88 (+83% upside)

CONVICTION SCORE: 3.5 / 5

CONVICTION RATIONALE: Methods converge on a base case of
$55–60, above the current $48 price, indicating moderate
undervaluation. However, the enormous gap between FCF-based
and FCF-ex-SBC valuations ($56 vs. $31 base case) creates
genuine uncertainty about whether the company is creating or
destroying economic value for shareholders. The reverse DCF
strongly signals mispricing, but the SBC problem prevents a
higher conviction score. Score would rise to 4 if SBC declines
below 20% of revenue with sustained 25%+ ARR growth.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

**Weighting Rationale:**
- **Forward DCF at 40%:** Highest weight because RBRK has predictable recurring revenue (96.6% subscription), clear margin trajectory, and a well-documented guidance beat history. FCF trajectory is the primary value driver.
- **Trading Comps at 25%:** High weight because the peer set is well-defined and RBRK's growth-adjusted discount to peers is the clearest signal of relative mispricing.
- **M&A Comps at 15%:** Standard weighting. Provides a floor/ceiling reference. Reduced slightly from 20% because no direct data protection M&A at comparable scale has occurred recently (Cohesity-Veritas was a merger, not an acquisition).
- **Sum-of-Parts at 10%:** Reduced from standard 15–20% because RBRK does not report segment-level economics, making the split estimation speculative.
- **PE/LBO Floor at 10%:** Standard downside reference. The floor of $42 is within 12% of current price, confirming limited additional downside.

**Weighted Base Case Calculation:**
- Forward DCF: $56.48 × 40% = $22.59
- Trading Comps: $59.33 × 25% = $14.83
- M&A Comps: $59.50 × 15% = $8.93
- Sum-of-Parts: $48.37 × 10% = $4.84
- PE/LBO Floor: $42.19 × 10% = $4.22
- **Weighted average: $55.41 → rounded to $55–57 base case**

**Critical Caveat — The SBC Elephant in the Room:**

The base case price target of ~$57 uses standard FCF-based valuation, which treats SBC as a non-cash item added back to operating cash flow. This is the convention that Wall Street analysts use, and it produces the most favorable picture.

If instead you use FCF-ex-SBC (treating SBC as a real cost of doing business — which it is, because it dilutes your ownership):
- Bear: $14, Base: $31, Bull: $56
- The weighted base case drops to approximately **$33–35**

The truth is somewhere in between. SBC at 25% of revenue will decline over time (management is guiding contribution margin expansion), but it will not disappear. A reasonable middle-ground valuation that partially expenses SBC would yield a base case of **$42–48** — essentially where the stock trades today. This is why conviction is 3.5 rather than 4 or 5: the market may actually be efficient in pricing RBRK once you account for the real cost of equity compensation.

---

### DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━━━━━
TICKER: RBRK
COMPANY: Rubrik, Inc.
SECTOR: Cybersecurity / Data Security / Cyber Resilience
VALUATION DATE: March 29, 2026

PRICE TARGET: $57 base case (range: $35 bear — $88 bull)
CURRENT PRICE: $48.00
UPSIDE TO BASE: +19%
CONVICTION: 3.5 / 5

WHEEL STRATEGY IMPLICATIONS:

SELL PUTS: YES — CONDITIONAL
  Rationale: Stock is ~16% below base case PT with a 
  PE/LBO floor at $42 providing downside support. The 
  massive analyst consensus (24 Buy / 1 Hold, avg PT $87-93) 
  creates buying pressure. However, SBC-adjusted valuation 
  suggests the stock is closer to fair value. Sell puts only
  at or below the bear case / LBO floor.
  
  Suggested strike zone: $38–$42 (at or below PE floor)
  Avoid puts above: $50 (above current price, negative EV)
  Ideal expiry: 30–45 DTE, avoid earnings window

COVERED CALLS (if assigned): YES
  Cost basis assumption: $40 (put strike)
  Minimum call strike: $40 (cost basis floor per 
  cc_min_strike_pct = 1.0 rule)
  Suggested call strike zone: $48–$55 (between cost 
  basis and base case PT)
  Do NOT sell calls above: $70 (approaching bull case — 
  let it run on fundamental re-rating)

CONCENTRATED LONG CANDIDATE: NO
  Rationale: Conviction at 3.5 is below the ≥4 threshold.
  The SBC-adjusted valuation gap creates too much uncertainty
  for a concentrated position. Better suited as a defined-risk
  wheel income trade until SBC trends are clearer.

KEY DATES TO AVOID (earnings, catalysts):
  June 16, 2026: Q1 FY2027 earnings (after close) — 
    the single most important catalyst; will confirm or deny 
    the normalized growth trajectory
  Late June 2026: Russell reconstitution — potential index 
    inclusion as profitability materializes
  Late Sep/Oct 2026: Q2 FY2027 earnings (est.)
  RSA 2026 already passed (late March) — no near-term 
    product catalyst expected

SECTOR CONTEXT:
  Sector score from analysis: 22/25 (PASS — rank 2 of 16)
  Relative ranking in sector: #2 behind ZS (tied at 22/25)
  Sector-level risk flags: 
    - Microsoft bundling escalation (HIGH severity)
    - AI commoditization of security moats (HIGH severity)
    - SaaS valuation regime shift (-30% from Sep 2025 peak)
    - Cohesity-Veritas merger creates #1 data protection player 
      with $1.5B ARR and NVIDIA backing; IPO planned 2026
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## APPENDIX: KEY ASSUMPTIONS LOG

| Assumption | Value | Justification |
|-----------|-------|---------------|
| WACC (base) | 10.0% | Standard for high-growth SaaS; reflects pre-GAAP-profit risk premium. Sector range: 9–12% |
| Terminal FCF margin | 30.0% | Sector benchmark: PANW 36%, ZS 29%, OKTA 30% at $3B+ ARR. RBRK's 83.7% gross margin supports 30%+ FCF at scale |
| Terminal growth | 3.0% | GDP-like perpetuity; cyber resilience market growing ~18% CAGR through 2030, but terminal rate reflects secular maturation |
| Base case revenue CAGR (7-yr) | ~18.3% | Consensus-anchored for Yr 1–2, then decelerating to sector average; reflects material rights revenue headwind in FY2027 |
| SBC trajectory | 25% → 12% over 7 years | FY2025 was IPO artifact (103%); FY2026 normalized to 25%; sector-efficient peers (FTNT, CHKP) run 4–6% but RBRK is earlier stage |
| Fully diluted shares | 230M | Aligns with FY2027 guidance (~232M); includes all options, RSUs, ESPP, and if-converted share count from $1.15B convertible notes |
| Net cash | $525.8M | Cash + investments ($1,675.8M) less convertible debt principal ($1,150M). Converts mature June 2030; no near-term liquidity risk |
| Annual dilution | ~5% | FY2026 actual was 5.4%; expected to moderate as SBC declines but offset by ESPP and RSU vesting |
| NRR | >120% | Reported consistently; 45% of NRR from security cross-sell, up from 34% YoY. Conservative assumption: stays at 120% (no expansion assumed) |
| Guidance beat pattern | 8–10% | Five consecutive quarters of 7–11% revenue beats. Street consensus already embeds ~$40M above FY2027 guide midpoint |

---

## SUPPLEMENTAL ANALYSIS A: SBC TRAJECTORY — WHEN DOES FCF-EX-SBC BREAK EVEN?

This is the single most important question for determining whether RBRK is genuinely creating shareholder value or using equity dilution to subsidize apparent profitability.

Under base case revenue growth (25% → 12% over 7 years) and FCF margins (18% → 30%):

| SBC Decline Scenario | SBC Yr 1 | SBC Yr 7 | FCF-ex-SBC Breakeven | Yr 7 FCF-ex-SBC Margin |
|---------------------|----------|----------|---------------------|----------------------|
| Aggressive (→15%) | 23% | 15% | **Year 3 (FY2029)** | 15.0% |
| Moderate (→18%) | 24% | 18% | **Year 3 (FY2029)** | 12.0% |
| Slow (→20%) | 24% | 20% | **Year 3 (FY2029)** | 10.0% |

**Key finding:** FCF-ex-SBC reaches breakeven in Year 3 (FY2029) under all three SBC trajectory scenarios. This is because the expanding FCF margin (from 18% to 23% by Year 3) eventually overtakes even slowly declining SBC. The critical cross-over point is when FCF margin exceeds SBC-as-%-of-revenue.

However, the magnitude matters. Under the slow decline scenario, FCF-ex-SBC margin is only 10% in Year 7 — meaning nearly two-thirds of the company's apparent FCF is actually shareholder dilution. Under aggressive decline, Year 7 margin reaches 15%, which is a more respectable (if still below-peer) level of genuine economic value creation.

**Implication for valuation:** The base case DCF target of $57 assumes SBC declines to 12% by Year 7. If SBC sticks at 18–20% (which is still above the sector median of ~20%), the FCF-ex-SBC-based value drops from $31 to $24–28. The SBC trajectory is the highest-leverage assumption in the model.

---

## SUPPLEMENTAL ANALYSIS B: GROWTH DECELERATION SENSITIVITY

What happens if growth decelerates faster than consensus?

| Scenario | Yr 1–2 Growth | Yr 7 Growth | 7-Yr CAGR | Implied EV | Per Share | vs. $48 |
|----------|--------------|------------|-----------|-----------|----------|---------|
| Consensus (base) | 25% / 22% | 12% | 17.5% | $12,464M | **$56.48** | +17.7% |
| Moderate deceleration | 22% / 18% | 9% | 13.9% | $10,251M | **$46.86** | −2.4% |
| Sharp deceleration | 20% / 15% | 6% | 11.0% | $8,752M | **$40.34** | −16.0% |
| Cliff (Cohesity wins) | 18% / 12% | 3% | 7.9% | $7,331M | **$34.16** | −28.8% |

**Key finding:** The stock breaks even on the DCF at "moderate deceleration" ($46.86 ≈ $48), which corresponds to growth declining from 22% in Year 1 to 9% by Year 7. This is well below consensus and management guidance, but not unreasonable if the Cohesity-Veritas merger proves more disruptive than expected or if hyperscaler-native backup gains meaningful traction.

The "cliff" scenario — growth collapsing to single digits within 3 years — would require a fundamental competitive disruption. Even then, the downside is ~29%, suggesting the stock has already absorbed considerable pessimism.

---

## SUPPLEMENTAL ANALYSIS C: GROWTH-ADJUSTED VALUATION REGRESSION

Running a simple linear regression of EV/NTM Revenue against NTM growth rate across 11 cybersecurity peers produces:

**EV/NTM Revenue = 3.10 + 0.136 × Growth%**

At RBRK's 34% ARR growth, the regression predicts a fair multiple of **7.7x NTM Revenue**. RBRK currently trades at 5.3x — a **31% discount to the regression line**.

### Peer Residual Analysis (sorted cheapest to most expensive)

| Peer | Growth | Actual | Predicted | Residual | Status |
|------|--------|--------|-----------|----------|--------|
| NTSK | 31% | 3.3x | 7.3x | −4.0x | CHEAP (lock-up selling) |
| **RBRK** | **34%** | **5.3x** | **7.7x** | **−2.4x** | **CHEAP** |
| S | 22% | 3.5x | 6.1x | −2.6x | CHEAP |
| SAIL | 28% | 5.2x | 6.9x | −1.7x | CHEAP |
| ZS | 25% | 6.0x | 6.5x | −0.5x | Fair |
| PANW | 33% | 8.1x | 7.6x | +0.5x | Fair |
| FTNT | 15% | 8.9x | 5.1x | +3.8x | EXPENSIVE |
| CRWD | 24% | 15.7x | 6.4x | +9.3x | EXPENSIVE |

RBRK is the 2nd cheapest name vs. the regression (behind only NTSK, which is distorted by lock-up selling). The regression confirms the trading comps analysis: RBRK is being valued as if it were a ~15% grower, not a 34% grower.

**Caveat:** A simple growth regression ignores profitability and moat depth. CRWD's 9.3x premium to regression reflects its 97% gross retention rate and platform moat, which justifies a non-linear premium. RBRK's discount partially reflects its shorter public history, pre-GAAP-profit status, and narrower competitive moat vs. CRWD/PANW. However, a 31% discount is still excessive given RBRK's Rule of 40 score of 52 (top 3 in peer set) and >120% NRR.

---

## SUPPLEMENTAL ANALYSIS D: FY2027 REVENUE BRIDGE — THE MATERIAL RIGHTS HEADWIND

This is the #1 source of investor confusion in the RBRK story:

| | Reported | Normalized (ex-material rights) |
|---|---------|-------------------------------|
| FY2026 Revenue | $1,316.2M | $1,264.2M (less ~$52M material rights) |
| FY2027 Revenue (guide mid) | $1,602.0M | $1,598.0M (less ~$4M) |
| **YoY Growth** | **+21.7%** | **+26.4%** |
| Street consensus FY2027 | $1,640M | Normalized: +29.7% |

The ~$52M of "material rights" revenue in FY2026 came from customers exercising or forfeiting subscription credits during the cloud transition. This was a one-time benefit that drops to ~$4M in FY2027. The optical deceleration from "48% growth" to "22% growth" is dramatically overstated — the real deceleration is from ~40% to ~26%, which is a normal and healthy trajectory for a company scaling past $1.5B in ARR.

Investors who screen RBRK at face-value FY2027 growth of 22% will systematically undervalue it relative to peers. The normalized growth of 26–30% places it firmly in the premium growth tier.

---

## SUPPLEMENTAL ANALYSIS E: DILUTION-ADJUSTED INVESTOR RETURNS

At 5.4% annual share dilution, what are the real returns?

| Scenario | Raw Return | 3-Year Dilution Drag | Dilution-Adjusted Value | Real Return |
|----------|-----------|---------------------|------------------------|-------------|
| Base ($57 target) | +18.8% | −15.3% | $48.26 | **+0.5%** |
| Bull ($88 target) | +83.3% | −15.3% | $74.50 | **+55.2%** |

**Sobering reality:** If RBRK reaches the $57 base case target, a buy-and-hold investor's return after 3 years of dilution is approximately **zero**. The stock price appreciation is almost entirely offset by the dilution from ~5.4% annual share issuance. Only in the bull case ($88) does the investment meaningfully compensate for dilution.

This reinforces why the wheel strategy is more appropriate than a concentrated long position at current prices: the income from selling options provides the return that dilution-adjusted price appreciation may not.
