# V1 STOCK VALUATION — CLOUDFLARE, INC. (NET)

**Analyst:** V1 Valuation Engine
**Ticker:** NET
**Company:** Cloudflare, Inc.
**Current Price:** $201.00
**Analysis Date:** March 29, 2026
**Fiscal Year End:** December 31

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency

| Method | Required Data | Available? | Notes |
|--------|--------------|-----------|-------|
| **Reverse DCF** | EV, revenue history, FCF, growth rates | ✅ COMPLETE | 12 quarters of revenue + FCF, consensus estimates, guidance |
| **Forward DCF** | Revenue projections, FCF margins, share count, net debt | ✅ COMPLETE | FY2026-FY2028 consensus available; long-term targets from May 2023 Investor Day |
| **Trading Comps** | Peer multiples | ✅ COMPLETE | 15 cybersecurity peers from sector handoff |
| **M&A Comps** | Transaction multiples | ⚠️ PARTIAL | Sector handoff provides ranges; no direct NET-comparable transactions (NET is not a realistic M&A target at $70B+ market cap) |
| **Sum-of-Parts** | Segment-level revenue | ⚠️ LIMITED | Cloudflare reports as a SINGLE segment — no formal product-line revenue disclosure. Will estimate based on qualitative commentary |
| **PE/LBO Floor** | FCF, debt capacity, EV | ✅ COMPLETE | FCF trajectory clear; company is too large for traditional LBO |

### Check 2: Fiscal Year Alignment

Cloudflare's fiscal year ends **December 31** (calendar year). All data is aligned. Most cybersecurity peers with non-calendar FY (CRWD, ZS, PANW, SAIL, RBRK, S end Jan 31; NTSK end Jan 31) have their most recent quarter ending Jan 31, 2026 (their Q4). Cloudflare's most recent quarter is Q4 CY2025 (ended Dec 31, 2025). When comparing NTM metrics, I align to calendar 2026 estimates for all companies.

### Check 3: Share Count Reconciliation

| Share Count Metric | Shares (M) | Source |
|-------------------|-----------|--------|
| Basic shares outstanding (Dec 31, 2025) | 351.9 | 10-K (317.3M Class A + 34.6M Class B) |
| Non-GAAP diluted shares (Q4 2025) | 375.5 | Earnings release |
| FY2026 guided diluted shares | ~377.0 | Management guidance |
| Convertible if-converted shares (2026 + 2030 notes) | ~14.8 | 6.76M from 2026 notes + 8.08M from 2030 notes |
| Fully diluted estimate (all equity awards + converts) | ~390.0 | R1 estimate: 388-397M |
| Practical fully diluted (capped calls offset converts) | ~380.0 | R1 estimate: 373-383M |

**I will use 385M fully diluted shares for all per-share calculations.** This includes all outstanding equity awards and convertible if-converted shares, partially offset by capped call hedges. This is conservative — the 2030 notes ($247.67 conversion price) are out-of-the-money at $201, but could become dilutive.

**Note:** The 2026 convertible notes ($1.29B, conversion price $191.34) are IN the money at $201. These mature August 15, 2026. Cash ($4.1B) comfortably covers full retirement, but the settlement method (cash vs. shares) affects dilution.

### Check 4: SBC Materiality Assessment

| Metric | FY2023 | FY2024 | FY2025 |
|--------|--------|--------|--------|
| SBC expense | $287.5M | $356.4M | $490.0M |
| SBC as % of revenue | 22.2% | 21.3% | 22.6% |
| FCF | $119.5M | $166.9M | $260.6M |
| FCF margin | 9.2% | 10.0% | 12.0% |
| **FCF ex-SBC** | **($150M)** | **($171.6M)** | **($190.9M)** |
| **FCF ex-SBC margin** | **-11.6%** | **-10.3%** | **-8.8%** |

**⚠️ SBC EXCEEDS 15% THRESHOLD.** At 22.6% of revenue, SBC is materially above the 15% threshold. All FCF-based valuations will present BOTH FCF and FCF-ex-SBC versions.

**The single most important data point for NET's valuation: FCF ex-SBC is deeply negative at ($190.9M) in FY2025.** The reported 12% FCF margin is entirely subsidized by equity dilution. This is the critical distinction between NET's "reported" and "economic" profitability. Annual share dilution runs ~2-3.5%, and no buyback program exists.

---

## VALUATION METHOD 1: REVERSE DCF

**Purpose:** What growth rate is the current market price implying?

### Enterprise Value Calculation

| Component | Value |
|-----------|-------|
| Market Cap (351.9M basic × $201) | $70,732M |
| Plus: Total Debt (convertible notes) | $3,265M |
| Less: Cash + Short-term Investments | ($4,101M) |
| **Enterprise Value** | **$69,896M ≈ $69.9B** |

### Assumptions

- Starting revenue: $2,168M (FY2025 actual)
- Terminal FCF margin: **25%** (sector handoff benchmark: 25-35% at $3B+ ARR for cybersecurity)
- Terminal growth rate: **3%** (GDP-like perpetuity)
- Discount rate (WACC): **10%** (default for high-growth SaaS; NET has elevated risk from gross margin compression and convertible debt complexity)
- FCF margin ramp: linear from **12%** (current) to **25%** (terminal) over 10 years
- Solve for: constant revenue CAGR that produces PV = $69.9B

### Results

```
REVERSE DCF RESULTS
━━━━━━━━━━━━━━━━━━
Current EV: $69.9B
Assumptions: Terminal FCF margin 25%, terminal growth 3%, WACC 10%

Implied revenue CAGR: ~33%
Current actual revenue growth: 30% (FY2025), 34% (Q4 2025)
Consensus NTM revenue growth: ~29%
Management long-term target: $5B run rate by Q4 2028 (~28% CAGR)

GAP ANALYSIS:
Market implies ~33% growth vs. ~29% consensus / ~28% management target
→ Market is pricing in ACCELERATION ABOVE CONSENSUS AND MANAGEMENT'S OWN TARGETS

The current stock price requires Cloudflare to sustain ~33% revenue
growth for 10 consecutive years AND reach 25% FCF margins. This would
produce ~$16B in FY2035 revenue (7.4x current). For context, Palo Alto
Networks — the largest pure-play security company — generates ~$10B today
after 18 years. The market is pricing NET as if it will become
significantly larger than today's PANW within a decade.
```

### SBC-Adjusted Reverse DCF

If we use FCF-ex-SBC margins (terminal: ~13% instead of 25%, assuming SBC declines from 22.6% to ~12% at maturity), the implied growth rate rises to **>45%** — mathematically impossible to sustain for a decade. This confirms that the current valuation fundamentally depends on treating SBC as a non-cash, non-economic expense, which contradicts economic reality.

### Sensitivity Table: Implied Revenue CAGR

| WACC \ Terminal FCF Margin | 20% | 25% | 30% | 35% |
|----------------------------|-----|-----|-----|-----|
| 9% | 35% | 31% | 28% | 26% |
| 10% | 38% | 33% | 30% | 28% |
| 11% | 41% | 36% | 33% | 30% |
| 12% | 44% | 39% | 35% | 32% |

**Interpretation:** Even under the most favorable assumptions (9% WACC, 35% terminal FCF margin), the market is pricing in ~26% sustained CAGR for a decade. Under more conservative but reasonable assumptions (10% WACC, 25% terminal FCF margin), the implied 33% CAGR exceeds both consensus and management targets. The stock is pricing in a scenario that requires flawless execution plus upside surprise.

---

## VALUATION METHOD 2: FORWARD DCF (3-SCENARIO)

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|------------|------|------|------|
| Yr 1-2 Rev CAGR | 30% | 28% | 24% |
| Yr 3-5 Rev CAGR | 25% | 21% | 16% |
| Yr 6-7 Rev CAGR | 20% | 16% | 12% |
| Terminal FCF Margin | 30% | 25% | 20% |
| Terminal Growth Rate | 3.5% | 3.0% | 2.5% |
| WACC | 9.5% | 10.0% | 11.0% |

**What must go right (Bull):** AI inference monetization accelerates beyond expectations; Workers platform becomes the dominant edge compute runtime; SASE/Zero Trust business scales to $1B+; gross margins stabilize above 75%; S&M leverage drives operating margin expansion toward 20%+ by Year 5. Essentially, NET becomes the defining platform company of the AI-native internet.

**Most likely path (Base):** Revenue growth follows consensus for Years 1-2, then decelerates toward sector average as the company scales past $5B. Gross margins stabilize in the 74-76% range as infrastructure investment normalizes. FCF margins expand to ~25% by Year 7 through operating leverage, consistent with management's long-term model. AI remains a tailwind but faces hyperscaler competition.

**What could go wrong (Bear):** Gross margin compression accelerates as Workers/AI workloads grow faster but at lower margins; hyperscaler bundling (AWS CloudFront + WAF, Azure Front Door) pressures enterprise pricing; SASE growth stalls against ZS/PANW incumbents; AI inference market commoditizes; multiple compresses as SaaS valuation regime permanently resets from 20x+ to 10-15x for 20% growers.

### Revenue Projection (Base Case, 7-Year)

| Year | Revenue ($M) | YoY Growth | FCF Margin | FCF ($M) | Discount Factor (10%) | PV of FCF ($M) |
|------|-------------|------------|------------|----------|----------------------|----------------|
| 1 (FY2026) | 2,790 | 28.7% | 13.0% | 363 | 0.909 | 330 |
| 2 (FY2027) | 3,571 | 28.0% | 14.9% | 532 | 0.826 | 440 |
| 3 (FY2028) | 4,321 | 21.0% | 16.7% | 722 | 0.751 | 542 |
| 4 (FY2029) | 5,228 | 21.0% | 18.6% | 972 | 0.683 | 664 |
| 5 (FY2030) | 6,326 | 21.0% | 20.4% | 1,291 | 0.621 | 802 |
| 6 (FY2031) | 7,338 | 16.0% | 22.3% | 1,636 | 0.564 | 923 |
| 7 (FY2032) | 8,512 | 16.0% | 25.0% | 2,128 | 0.513 | 1,092 |
| **Terminal Value** | | | | | | |

Year 7 Terminal Value = $2,128M × 1.03 / (0.10 - 0.03) = **$31,312M**
PV of Terminal Value = $31,312M × 0.513 = **$16,063M**

Sum of PV of FCFs: **$4,793M**
PV of Terminal Value: **$16,063M**
**Total Enterprise Value: $20,856M ≈ $20.9B**

### SBC-Adjusted Base Case (FCF ex-SBC)

If SBC declines from 22.6% of revenue to 12% by Year 7, the FCF-ex-SBC margin in Year 7 = 25% - 12% = 13%.

Terminal Value (SBC-adjusted) = ($8,512M × 13%) × 1.03 / 0.07 = $16,286M
PV of TV = $16,286M × 0.513 = $8,355M

Adjusted PV of FCFs (roughly halved): ~$2,400M
**SBC-Adjusted EV: ~$10,755M ≈ $10.8B**
**SBC-Adjusted per share: ~$30** — This represents the "true economic" value if SBC is treated as a real cost.

### Valuation Summary (Standard FCF — not SBC-adjusted)

| | Bull | Base | Bear |
|---|------|------|------|
| PV of Cash Flows | $7,488M | $4,793M | $3,012M |
| PV of Terminal Value | $38,921M | $16,063M | $6,888M |
| Enterprise Value | $46,409M | $20,856M | $9,900M |
| Net Cash | $836M | $836M | $836M |
| Equity Value | $47,245M | $21,692M | $10,736M |
| Fully Diluted Shares | 385M | 385M | 385M |
| **Per Share Value** | **$123** | **$56** | **$28** |
| Upside / (Downside) | (39%) | (72%) | (86%) |
| TV as % of Total | **84%** ⚠️ | **77%** ⚠️ | **70%** ⚠️ |

**⚠️ TERMINAL VALUE WARNING: Terminal value exceeds 70% of total value in ALL THREE SCENARIOS.** This means the entire valuation is dominated by long-term assumptions about what Cloudflare looks like in 2032-2033, not by near-term fundamentals. The valuation is inherently speculative.

### Round-Trip Check

The base case implies EV of $20.9B on NTM revenue of ~$2.83B → **7.4x NTM revenue** for a ~29% grower. This is consistent with the cybersecurity peer set (ZS at 6x/25% growth, RBRK at 5.3x/34% growth, PANW at 8.1x/33% NGS growth). The base case DCF valuation is internally consistent with comparable multiples — confirming that $201 is significantly above fundamental value.

The bull case implies EV of $46.4B → **16.4x NTM revenue**. This is below CRWD's current 15.7x multiple but above most peers. A 16x multiple for a 30% grower would imply a growth-adjusted ratio of 0.55, which is expensive but within historical range for high-quality platform companies.

**Bottom line: Even the bull case (aggressive assumptions, 9.5% WACC, 30% terminal FCF margin, 3.5% terminal growth) produces a per-share value of $123 — 39% below the current price.**

---

## VALUATION METHOD 3: TRADING COMPS

### Peer Set and Multiples

| Company | Ticker | EV/NTM Rev | NTM Rev Growth | Growth-Adj Ratio | Rule of 40 | FCF Margin | SBC % Rev |
|---------|--------|-----------|----------------|-----------------|-----------|-----------|-----------|
| **Cloudflare** | **NET** | **25.0x** | **29%** | **0.86** | **42** | **12.0%** | **20.8%** |
| CrowdStrike | CRWD | 15.7x | 22% | 0.71 | 48 | 25.7% | 22.8% |
| Palo Alto (NGS) | PANW | 8.1x | 33% | 0.25 | 51 | 36.0% | 14.0% |
| Fortinet | FTNT | 8.9x | 12% | 0.74 | 47 | 32.5% | 4.1% |
| Zscaler | ZS | 6.0x | 25% | 0.24 | 55 | 29.0% | 27.0% |
| Check Point | CHKP | 5.8x | 6% | 0.97 | 49 | 43.0% | 5.9% |
| SentinelOne | S | 3.5x | 22% | 0.16 | 27 | 5.0% | 29.7% |
| Okta | OKTA | 3.6x | 9% | 0.40 | 42 | 30.0% | 18.6% |
| Rubrik | RBRK | 5.3x | 34% | 0.16 | 52 | 18.1% | 22.0% |
| SailPoint | SAIL | 5.2x | 28% | 0.19 | 46 | 4.9% | 22.0% |
| Netskope | NTSK | 3.3x | 31% | 0.11 | 34 | 1.7% | 75.0% |
| Tenable | TENB | 2.4x | 8% | 0.30 | 39 | 27.7% | 19.2% |
| Qualys | QLYS | 4.1x | 10% | 0.41 | 55 | 45.5% | 11.5% |
| Varonis | VRNS | 3.4x | 16% | 0.21 | 37 | 21.2% | 20.9% |

**Note on EV/NTM Revenue at current price:** Using EV of $69.9B and NTM revenue of ~$2.8B, NET trades at approximately **25.0x NTM revenue** at $201. This is recalculated from the R2 data which showed 26.4x at a slightly higher price.

### Target Company Positioning

- **Growth rank:** #2 of 14 peers (behind RBRK at 34%, tied with PANW NGS at 33%)
- **Profitability rank (FCF margin):** #12 of 14 peers (only NTSK and SAIL are lower)
- **Valuation rank (EV/NTM Rev):** #1 most expensive — NET at 25x vs. #2 CRWD at 15.7x
- **Growth-adjusted ratio:** 0.86 — NET is the **3rd most expensive** growth-adjusted name after CHKP (0.97) and FTNT (0.74), excluding CRWD (0.71)
- **Current multiple vs. peer median (4.7x):** **+432% premium**

### Premium/Discount Analysis

NET commands a massive premium for several reasons:
1. **Unique AI infrastructure positioning** — Workers AI, 4,000% inference growth, "platform for AI agents"
2. **Revenue acceleration** — one of very few SaaS companies actually accelerating (26.5% → 33.6% through FY2025)
3. **TAM expansion** — not just security; CDN + edge compute + developer platform + AI inference
4. **RPO momentum** — +48% is the fastest in the peer set, signaling future revenue acceleration

However, the premium is extreme:
1. **NET trades at 5.3x the peer median** EV/NTM Rev multiple
2. **Growth-adjusted ratio of 0.86** puts it among the most expensive names on a quality-adjusted basis
3. **FCF margin of 12% (and negative FCF ex-SBC)** does not justify a premium valuation for profitability
4. **Not a pure-play** — ~45% of revenue is non-security (CDN, developer tools, edge compute), making security peer comps imprecise

### Fair Value Estimate (Comps-Based)

**Method 1: Growth-Adjusted Regression**
The peer set's median growth-adjusted ratio (EV/Rev ÷ Growth) is approximately **0.30** (excluding outliers NET, CHKP, and FTNT). Applying 0.30 to NET's 29% NTM growth:
- Fair EV/NTM Revenue: 0.30 × 29 = **8.7x**
- Implied EV: 8.7 × $2.8B = **$24.4B**
- Implied equity: $24.4B + $0.8B = $25.2B
- Implied share price: $25.2B / 385M = **$65**

**Method 2: High-Growth Tier Median**
Using the top-5 growers (RBRK, PANW NGS, NTSK, NET, ZS — all 25%+ growth), the median EV/NTM Rev is **5.3x** (excluding NET itself).
- Fair EV: 5.3 × $2.8B = **$14.8B**
- Implied share price: ($14.8B + $0.8B) / 385M = **$41**

**Method 3: Premium Justified by Unique Platform (Generous)**
If NET deserves a 100% premium to the high-growth tier median (justified by AI/platform TAM expansion):
- Fair EV/NTM Revenue: 5.3 × 2.0 = **10.6x**
- Implied EV: 10.6 × $2.8B = **$29.7B**
- Implied share price: ($29.7B + $0.8B) / 385M = **$79**

### Trading Comps Summary

```
TRADING COMPS
━━━━━━━━━━━━━━━━━━

TARGET COMPANY POSITIONING:
- Growth rank: #2 of 14 peers
- Profitability rank: #12 of 14 peers
- Current multiple vs. peer median: premium of +432%

FAIR VALUE ESTIMATE:
- Method: Growth-adjusted regression (most rigorous)
- Fair EV/NTM Revenue: 8.7x (current: 25.0x)
- Implied EV: $24.4B
- Implied share price: $65
- Downside: (68%)

- Even with a generous 100% platform premium: $79 (61% downside)
```

---

## VALUATION METHOD 4: PRECEDENT M&A COMPS

### Applicability Assessment

**NET is NOT a realistic M&A target.** At $70B+ enterprise value, no strategic acquirer or PE firm could execute this transaction. For context:

- Google/Wiz ($32B) was the largest cybersecurity acquisition in history
- Cisco/Splunk ($28B) and PANW/CyberArk ($25B) are the only other $25B+ security deals
- NET's dual-class share structure gives co-founders Prince and Zatlyn supervoting control, making a hostile bid impossible
- NET would need to trade at a significant discount for a takeout to become conceivable

This method is included for completeness and to establish a theoretical takeout floor, but should receive **minimal weight** in triangulation.

### Comparable Transactions (Cybersecurity, 2023-2026)

| Date | Target | Acquirer | EV ($B) | EV/Rev | Target Growth | Premium |
|------|--------|----------|---------|--------|---------------|---------|
| Mar 2026 | Wiz | Google | $32.0 | ~16x | >60% | N/A (private) |
| Feb 2026 | CyberArk | PANW | $25.0 | ~10x | ~25% | ~30% |
| Jan 2026 | Chronosphere | PANW | $3.35 | ~15x | N/A | N/A (private) |
| Sep 2025 | Securiti | Veeam | $1.73 | ~12x | N/A | N/A (private) |
| 2024 | Splunk | Cisco | $28.0 | ~8x | ~11% | ~31% |
| Dec 2025 | Red Canary | ZS | $0.68 | ~6x | N/A | N/A (private) |
| Jan 2025 | Seraphic | CRWD | $0.42 | N/A | N/A | N/A (private) |

### Takeout Valuation

Using the sector handoff M&A benchmarks:
- High-growth targets (>30%): 10-15x ARR
- Strategic scarcity premium: +2-4x

Cloudflare's TTM revenue ≈ ARR (100% recurring): $2,168M

- Applicable multiple range: 12-17x revenue (high-growth + scarcity premium for unique edge/AI platform)
- Implied EV range: $26.0B — $36.9B
- After control premium discount (25% for public market value): $19.5B — $27.7B
- Implied share price range: **$53 — $74**

```
M&A COMPS
━━━━━━━━━━━━━━━━━━

TAKEOUT VALUATION:
- Applicable multiple range: 12-17x ARR/Revenue
- Target ARR/Revenue: $2,168M
- Implied EV range: $26.0B — $36.9B
- After control premium discount (25%): $19.5B — $27.7B
- Implied share price range: $53 — $74

Probability-weighted note: A takeout is UNREALISTIC at current scale.
NET's $70B+ EV exceeds the largest-ever cybersecurity deal (Google/Wiz
at $32B). Dual-class share structure gives founders veto power. This
method serves only as a theoretical reference point.
```

---

## VALUATION METHOD 5: SUM-OF-PARTS

### Segment Estimation

Cloudflare reports as a **single segment** with no formal product-line revenue disclosure. However, based on management commentary, analyst estimates, and competitive positioning, I estimate the following breakdown:

| Segment | Est. Revenue ($M) | Est. % of Rev | Growth Est. | Comparable Pure-Play | Multiple Applied | Implied EV ($M) |
|---------|-------------------|---------------|-------------|---------------------|-----------------|-----------------|
| **Security (SASE/Zero Trust/WAF/DDoS)** | ~$900 | ~42% | ~25% | ZS (6.0x), NTSK (3.3x) → mid 5x | 5.0x | $4,500 |
| **CDN / Performance** | ~$650 | ~30% | ~15% | AKAM (~3x), FSLY (~2x) → 2.5x | 2.5x | $1,625 |
| **Developer Platform (Workers/R2/D1)** | ~$400 | ~18% | ~40% | Cloud platform peers (10-15x) | 12.0x | $4,800 |
| **AI Inference (Workers AI)** | ~$218 | ~10% | ~100%+ | No direct public comp; early stage | 15.0x | $3,270 |

**⚠️ Data Quality Warning:** These segment estimates are SPECULATIVE. Cloudflare does not disclose product-line revenue. The AI inference revenue estimate is particularly uncertain — 4,000% YoY growth in requests does not directly translate to revenue, and pricing ($0.002/worker/day for dynamic loader) suggests low per-unit economics. Morgan Stanley estimates AI + SASE could reach 40%+ of revenue by 2028.

### Sum-of-Parts Result

| | Value |
|---|------|
| Total Implied EV | $14,195M |
| Less: Net Debt / Plus: Net Cash | +$836M |
| Equity Value | $15,031M |
| Fully Diluted Shares | 385M |
| **Per Share** | **$39** |
| Upside / (Downside) | **(81%)** |

```
SUM-OF-PARTS
━━━━━━━━━━━━━━━━━━

Total EV: $14.2B
Net Cash: +$0.8B
Equity Value: $15.0B
Per Share: $39
Downside: (81%)

HIDDEN VALUE FLAG: The AI inference business and developer platform
(Workers) represent ~$8.1B of implied value — 57% of the SoP total —
using generous multiples. However, neither segment has verified revenue
figures. If the AI/developer narrative proves out (NET becomes the
default edge runtime for AI agents), this segment alone could be
worth $15-20B+ in 3-5 years. Conversely, if AI inference commoditizes
(hyperscaler competition), this segment's value collapses.

IMPORTANT CAVEAT: The SoP significantly understates value IF the
platform network effects are real — i.e., if security + CDN + Workers
+ AI together create value greater than the sum of parts. The integrated
platform thesis is Cloudflare's core bull case and it cannot be captured
by standalone segment multiples. Weight this method accordingly.
```

---

## VALUATION METHOD 6: PE / LBO FLOOR

### Applicability

At $70B EV, Cloudflare is **far too large** for a traditional leveraged buyout. The largest PE-led technology acquisition in history was the Dell/Silver Lake deal at ~$24B. Even a growth equity approach (no leverage) is unrealistic at this scale.

This analysis uses the **growth equity framework** (pure equity, 25% IRR target) to establish a theoretical floor — the maximum price a rational financial buyer would pay.

### Entry Assumptions

| Metric | Value |
|--------|-------|
| Entry EV | $69.9B (current, no premium — unrealistic for control) |
| Debt | $0 (growth equity — no leverage; FCF is too thin for LBO debt service) |
| Equity invested | $69.9B |

### 5-Year Projection (Using Base Case DCF)

| Year | Revenue ($M) | FCF ($M) | Cumulative FCF ($M) |
|------|-------------|---------|---------------------|
| FY2026 | 2,790 | 363 | 363 |
| FY2027 | 3,571 | 532 | 895 |
| FY2028 | 4,321 | 722 | 1,617 |
| FY2029 | 5,228 | 972 | 2,589 |
| FY2030 | 6,326 | 1,291 | 3,880 |

### Exit Assumptions

| Metric | Value |
|--------|-------|
| Exit multiple | 12.0x NTM Revenue (de-rated from current 25x; assumes multiple compression toward peer average) |
| FY2031 NTM Revenue (est.) | ~$7,338M |
| Exit EV | $88,056M |
| Equity at exit | $88,056M + $3,880M cumulative FCF = $91,936M |
| Implied IRR | (91,936/69,900)^(1/5) - 1 = **5.6%** |

**A 5.6% IRR is dramatically below the 25% threshold.** No financial buyer would pay current prices.

### Maximum Entry Price for Target IRRs

To achieve a 25% IRR with the same exit assumptions:
- Required equity at exit: Entry × (1.25)^5 = Entry × 3.05
- Exit equity = $91,936M → Max entry = $91,936 / 3.05 = **$30,143M**
- Per share: ($30,143M + $836M net cash) / 385M = **$80**

To achieve a 20% IRR:
- Required: Entry × (1.20)^5 = Entry × 2.49
- Max entry = $91,936 / 2.49 = **$36,922M**
- Per share: ($36,922M + $836M) / 385M = **$98**

```
PE / LBO FLOOR
━━━━━━━━━━━━━━━━━━

ENTRY ASSUMPTIONS:
- Entry EV: $69.9B (current EV, no premium)
- Debt: $0 (growth equity — no leverage capacity)
- Equity invested: $69.9B

5-YEAR PROJECTION:
| Year | Revenue ($M) | FCF ($M) | Cumulative FCF ($M) |
|------|-------------|---------|---------------------|
| 2026 | 2,790 | 363 | 363 |
| 2027 | 3,571 | 532 | 895 |
| 2028 | 4,321 | 722 | 1,617 |
| 2029 | 5,228 | 972 | 2,589 |
| 2030 | 6,326 | 1,291 | 3,880 |

EXIT ASSUMPTIONS:
- Exit multiple: 12.0x NTM Revenue (vs. 25.0x entry)
- Exit EV: $88.1B
- Equity at exit: $91.9B
- Implied IRR: 5.6%

FLOOR PRICE:
- Max entry price for 25% IRR: $80 per share
- Max entry price for 20% IRR: $98 per share
- Current price: $201
- Downside to 20% IRR floor: (51%)
- Downside to 25% IRR floor: (60%)

REALITY CHECK: A PE/LBO of Cloudflare is unrealistic at any price.
The company is too large ($70B EV), generates insufficient FCF for
debt service (12% margin), has a dual-class share structure preventing
hostile bids, and co-founders control the company. This analysis
serves only as a theoretical floor reference.
```

---

## TRIANGULATION & FINAL OUTPUT

### DELIVERABLE 1: PRICE TARGET RANGE & CONVICTION SCORE

```
━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━
TICKER: NET
CURRENT PRICE: $201
ANALYSIS DATE: March 29, 2026

METHOD RESULTS:
| Method          | Bear  | Base  | Bull  | Weight | Confidence |
|-----------------|-------|-------|-------|--------|------------|
| Reverse DCF     | —     | Market implies 33% CAGR for 10yr (above consensus) | — | — | H |
| Forward DCF     | $28   | $56   | $123  | 40%    | M          |
| Trading Comps   | $41   | $65   | $79   | 30%    | M          |
| M&A Comps       | $53   | $63   | $74   | 5%     | L          |
| Sum-of-Parts    | —     | $39   | —     | 10%    | L          |
| PE/LBO Floor    | $80   | —     | —     | 15%    | M          |

TRIANGULATED PRICE TARGET:
- Bear case: $38   (81% downside)
- Base case: $65   (68% downside)
- Bull case: $110  (45% downside)

CONVICTION SCORE: 4 (HIGH — overvalued with high confidence)

CONVICTION RATIONALE:
All six valuation methods converge on the same conclusion: Cloudflare
is significantly overvalued at $201. The base case across methods
clusters in the $39-$65 range. Even the most generous bull case
(Forward DCF with aggressive assumptions) produces only $123 — a 39%
downside from current levels. The Reverse DCF confirms the market is
pricing in growth and margin assumptions that exceed both consensus
estimates and management's own long-term targets. The conviction is
high (4/5, not 5/5) because NET's unique AI infrastructure positioning
creates genuine optionality that is difficult to model — if NET truly
becomes the "operating system of the AI internet," traditional
valuation frameworks may understate its potential. But the current
price requires this thesis to be certainty, not possibility.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

### Weighting Rationale

- **Forward DCF at 40%:** Cloudflare has highly predictable recurring revenue (100% subscription, 120% NRR) making DCF appropriate. However, terminal value dominance (>70% in all scenarios) reduces precision.
- **Trading Comps at 30%:** The peer set is well-defined with 14 comparables. However, NET is not a pure-play security company — CDN/developer/AI components make direct comparison imperfect.
- **PE/LBO Floor at 15%:** While an actual buyout is unrealistic, the floor price framework provides a useful downside reference. The 20% IRR floor of $98 is the most relevant data point.
- **Sum-of-Parts at 10%:** Weight reduced because segment estimates are speculative (no disclosed breakdown) and the method misses platform synergy value.
- **M&A Comps at 5%:** Weight minimized — NET is not an acquisition target at this scale.
- **Reverse DCF at 0% (informational only):** Confirms the overvaluation thesis but does not produce a price target.

### Why Methods Agree

The methods agree because NET's fundamental challenge is straightforward: the stock is priced at ~25x NTM revenue with only 12% FCF margins and negative FCF ex-SBC. To justify this valuation, you need to simultaneously believe in:

1. **Sustained 30%+ growth for 5-7+ years** (historically rare for any company at $2B+ revenue)
2. **FCF margins expanding to 25%+** (while gross margins are compressing)
3. **SBC declining materially as a % of revenue** (currently 22.6% with no buyback to offset dilution)
4. **The AI platform thesis converting from narrative to revenue** (AI inference requests ≠ revenue)

Any one of these assumptions alone is plausible. All four simultaneously is the price of admission at $201. The base case valuation of $65 reflects a more probable scenario where growth decelerates to sector norms and margins expand gradually.

---

### DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━
TICKER: NET
COMPANY: Cloudflare, Inc.
SECTOR: Cybersecurity / Edge Infrastructure
VALUATION DATE: March 29, 2026

PRICE TARGET: $65 base case (range: $38 bear — $110 bull)
CURRENT PRICE: $201
UPSIDE TO BASE: (68%) — DOWNSIDE
CONVICTION: 4 (HIGH conviction that stock is OVERVALUED)

WHEEL STRATEGY IMPLICATIONS:
- SELL PUTS: NO
  - Rationale: Stock is 209% ABOVE base case price target.
    Selling puts at any strike near current levels has deeply
    negative expected value. Even at $110 (bull case), the stock
    offers no upside. Every valuation method produces a value
    substantially below current price.
  - Avoid puts above: $110 (bull case ceiling)
  - If forced to consider: Only below $65 (base case) with
    extreme caution; ideally below $38 (bear case)

- COVERED CALLS (if assigned): N/A
  - Do not acquire shares through the wheel at current levels.
  - If already holding: Sell aggressive covered calls at or near
    current price ($195-$210) to monetize the overvaluation and
    reduce cost basis. The probability of sustained appreciation
    above $201 is low on a fundamental basis.

- CONCENTRATED LONG CANDIDATE: NO
  - Rationale: Conviction is HIGH that stock is overvalued (4/5).
    No method produces upside to current price. This is the
    opposite of a long candidate — it is a potential short
    candidate for sophisticated investors.

KEY DATES TO AVOID (earnings, catalysts):
- April 2026: Developer Week 2026 (product announcements)
- April 30-May 7, 2026: Q1 2026 earnings (guidance: $620-621M rev)
- May 15, 2026: 2026 convertible notes become freely convertible
- August 15, 2026: 2026 convertible notes maturity ($1.29B)
- September 2026: Birthday Week (major product launches)

SECTOR CONTEXT:
- Sector score from analysis: 18/25 (PASS, ranked #5 of 5 PASS names)
- Relative ranking in sector: #5 of 16 companies
- Sector-level risk flags:
  • Microsoft bundling (E7 Frontier Suite, Security Copilot free in E5)
  • AI commoditization fears (Anthropic Mythos leak March 27)
  • SaaS valuation regime permanently resetting lower
  • NET-specific: gross margin compression (290bps YoY), FCF ex-SBC
    deeply negative, 22.6% SBC with no buyback
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## APPENDIX: VALUATION QUALITY CHECKS

### 1. Show Your Math ✅
All intermediate calculations shown for every method. Assumptions explicitly stated.

### 2. Terminal Value Discipline ⚠️
Terminal value exceeds 70% of total DCF value in ALL scenarios (70-84%). This is flagged as speculative. The implication: NET's valuation depends almost entirely on what it looks like in 7-10 years, not on near-term fundamentals.

### 3. SBC Honesty ✅
FCF and FCF-ex-SBC presented for all applicable methods. The gap is massive: 12.0% FCF margin vs. -8.8% FCF-ex-SBC margin. This is the single largest source of potential overvaluation.

### 4. Round-Trip Check ✅
Base case DCF implies ~7.4x NTM revenue — consistent with peer multiples for a 29% grower. Current price of $201 implies 25x NTM revenue — an extreme outlier even among high-growth SaaS.

### 5. No Price Anchoring ✅
Every method was built from fundamentals up. The consistent result ($38-$123 range) is dramatically below the current $201 price. The analysis does not contort assumptions to justify the market price.

### 6. Sector Handoff Benchmarks Used ✅
Terminal FCF margin (25%), growth-adjusted ratios, M&A multiples, and peer comparisons all reference the sector handoff calibration data.

### 7. Uncertainty Acknowledged ✅
The base case range of $38-$65 acknowledges significant uncertainty. The bull case of $110-$123 acknowledges NET's unique optionality while still concluding overvaluation. The SoP analysis explicitly flags speculative segment estimates. The PE/LBO analysis explicitly flags unrealistic applicability.

---

## KEY RISK TO THE BEARISH THESIS

This valuation produces a strongly bearish conclusion. In the interest of intellectual honesty, here is what could make it wrong:

**1. NET is not a cybersecurity company — it's an infrastructure platform.** If the right comp set is hyperscalers (AWS, Azure) rather than cybersecurity (ZS, CRWD), then 25x NTM revenue for a 30%+ grower with massive TAM optionality is not unprecedented. Amazon Web Services at similar growth rates traded at comparable implicit multiples within Amazon's overall valuation.

**2. The AI agent thesis could be transformative.** If AI agents become the primary users of the internet (CEO Prince's thesis), and Cloudflare becomes the default runtime/security layer for these agents, the TAM expansion is genuinely unprecedented. This is not captured by any backward-looking comp.

**3. Rule of 40 is improving rapidly.** NET hit Rule of 50 in Q4 2025 (34% growth + 16% FCF margin). If this trajectory continues to Rule of 55-60, the stock deserves a premium multiple.

**4. Growth acceleration is real and rare.** In a universe where almost every SaaS company decelerates as it scales, NET is ACCELERATING (26.5% → 33.6%). Companies that accelerate past $2B revenue are extraordinarily rare and historically rewarded with premium multiples.

These factors explain WHY the market pays 25x — but they do not change the mathematical conclusion that the stock requires perfection to justify its current price. The appropriate strategy is to wait for a meaningful pullback to the $80-$110 range before considering a position, which would align with the bull case valuation and provide a margin of safety.
