# RDDT — V2 STOCK VALUATION REPORT

**Ticker:** RDDT (NYSE) | **Company:** Reddit, Inc.
**Sector:** Digital Advertising / AdTech (Walled Gardens & Social sub-bucket)
**Analysis Date:** April 12, 2026
**Current Price:** $139.73
**Fully Diluted Shares:** 206.1M
**Market Cap:** $28,798M | **Net Cash:** $2,477M | **Enterprise Value:** $26,322M
**EV/NTM Revenue (at consensus):** 8.23x
**Analyst Avg PT:** $224.93 (range $75–$320, 27 analysts)

---

## PRE-MODEL CHECKS

### Check 1 — Data Sufficiency ✅

| Method | Input status | Usable? |
|---|---|---|
| Forward DCF | 8 quarters rev + FCF; FY24/FY25 full; Q1'26 guidance; FY26/FY27 consensus | ✅ |
| Reverse DCF | Same; WACC calibratable from peer set | ✅ |
| Trading Comps | Full peer set from sector handoff (8 peers) | ✅ |
| M&A Comps | Sparse — no direct social/ad-platform precedents; LinkedIn and Twitter reference only | ⚠️ Low confidence |
| Sum-of-Parts | Two disclosed segments (Ad, Other/Data Licensing) with rev and growth | ✅ |
| LBO Floor | $845M Adj EBITDA, $684M FCF, zero debt — full inputs | ✅ |

### Check 2 — Fiscal Year Alignment ✅
Reddit's FYE is **December 31**. No calendar misalignment. All comps in the peer set also on calendar year except APP (Dec), META (Dec), GOOGL (Dec) — all aligned. No adjustment required.

### Check 3 — Share Count Reconciliation
- Basic shares FY25 weighted-avg: 186.38M
- Diluted shares FY25 weighted-avg: 202.11M
- **Fully diluted period-end (Dec 31, 2025): 206.1M** ← used throughout
- Zero convertibles outstanding; dual-class (A = 1 vote, B = 10 votes, C unissued)
- YoY dilution (Dec'25 vs Dec'24): **(0.05%) — effectively flat**. $104M of cash RSU withholdings offset new grants.

### Check 4 — SBC Materiality ⚠️ FLAG
- **FY25 SBC: $343.2M = 15.6% of revenue → above 15% threshold**
- Dual FCF presentation required
- **Reported FCF margin: 31.1%**
- **FCF-ex-SBC margin: 15.5%**
- Gap: ~1,560 bps

This is meaningful but not extreme — sector peers range from APP (3%) to PINS/SNAP (17–21%). RDDT sits mid-high. **All DCF scenarios use FCF-ex-SBC (economic FCF)** as primary, with reported FCF shown for reference.

**Note on FY24 distortion:** FY24 SBC was $801.6M (61.7% of rev) but $577.5M was Q1'24 IPO unlock vesting — one-time. Run-rate post-unlock is ~$85–90M/quarter ≈ $340–360M/year, tracking FY25 actual.

---

## VALUATION METHOD 1: REVERSE DCF

**Purpose:** What 10-year revenue CAGR does the current EV of $26,322M imply?

### Assumptions
| Parameter | Value | Rationale |
|---|---|---|
| Starting revenue | $2,202.5M | FY25 actual |
| Starting FCF margin | 15.5% | FY25 FCF-ex-SBC (economic) |
| Terminal FCF margin | 30.0% | Between META (21.7%) and APP software segment; high-GM ad platform should reach this at scale |
| WACC | 10.0% | Base case for high-quality, high-growth ad platform with net cash |
| Terminal growth | 3.0% | GDP-like perpetuity |
| Horizon | 10 years | Standard |
| Margin ramp | Linear 15.5% → 30.0% | Standard |

### Result

**Implied 10-year revenue CAGR: 17.4%**

| Actual/Expected | Growth | Comparison to implied 17.4% |
|---|---|---|
| FY25 actual | +69% | Far above |
| FY26 consensus | +45% | Far above |
| FY27 consensus | +31% | Above |
| Management long-term target | None stated | — |
| Implied 10-yr CAGR to justify current EV | **17.4%** | — |

### Gap analysis
At 17.4% CAGR, FY35 revenue would be ~$11.1B. Actual Q4'25 run-rate is already $2.9B annualized. **The market is pricing in meaningful deceleration** but **not an implausibly low growth rate**. If RDDT compounds at consensus (45% FY26, 31% FY27, then decelerating linearly), it reaches ~$11B before FY32 — suggesting the current price is **mildly overvalued** on economic-FCF basis but not dramatically so.

**Using reported FCF (31% → 35%)**: implied CAGR drops to **14.6%** — in that frame the stock is roughly fairly priced. The gap between the two readings IS the SBC story.

### Sensitivity (implied CAGR)

| WACC \ Terminal FCF-ex-SBC | 22% | 26% | 30% | 34% |
|---|---|---|---|---|
| 9% | 18.6% | 16.6% | 14.9% | 13.4% |
| **10%** | 21.1% | 19.1% | **17.4%** | 15.8% |
| 11% | 23.5% | 21.4% | 19.7% | 18.1% |
| 12% | 25.8% | 23.6% | 21.8% | 20.2% |

**Interpretation:** Across reasonable WACC/terminal-margin combinations, the implied CAGR sits between 14% and 24%. Consensus near-term growth comfortably clears the bottom of this range, but the upper cases (strict SBC treatment + elevated WACC) require growth the street is NOT currently underwriting.

---

## VALUATION METHOD 2: FORWARD DCF (3-Scenario)

All scenarios use **FCF-ex-SBC** (economic FCF). Year 1 = FY2026, Year 2 = FY2027, then modeled deceleration.

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|---|---|---|---|
| Yr1 Rev Growth | +45% | +42% | +35% |
| Yr2 Rev Growth | +35% | +28% | +20% |
| Yr3 Rev Growth | +28% | +22% | +14% |
| Yr4 Rev Growth | +22% | +17% | +10% |
| Yr5 Rev Growth | +17% | +13% | +8% |
| Yr6 Rev Growth | +13% | +10% | +6% |
| Yr7 Rev Growth | +10% | +8% | +5% |
| Yr1→Yr7 FCF-ex-SBC Mgn | 18% → 36% | 17% → 30% | 15% → 23% |
| WACC | 9.5% | 10.5% | 11.5% |
| Terminal Growth | 3.0% | 3.0% | 3.0% |

### Base Case — Full Projection

| Year | Revenue ($M) | Growth | FCF-ex-SBC Margin | FCF ($M) | PV ($M) |
|---|---|---|---|---|---|
| 1 (FY26) | 3,128 | 42% | 17% | 532 | 481 |
| 2 (FY27) | 4,003 | 28% | 20% | 801 | 656 |
| 3 (FY28) | 4,884 | 22% | 23% | 1,123 | 833 |
| 4 (FY29) | 5,714 | 17% | 26% | 1,486 | 997 |
| 5 (FY30) | 6,457 | 13% | 28% | 1,808 | 1,097 |
| 6 (FY31) | 7,103 | 10% | 30% | 2,131 | 1,171 |
| 7 (FY32) | 7,671 | 8% | 30% | 2,301 | 1,144 |
| **Terminal** | | | | 2,370 | 15,711 |

### Valuation Summary

| | Bull | Base | Bear |
|---|---|---|---|
| PV of FCFs (Yr1–7) ($M) | 9,140 | 6,378 | 3,774 |
| PV of Terminal Value ($M) | 29,592 | 15,711 | 6,996 |
| **Enterprise Value ($M)** | **38,732** | **22,089** | **10,770** |
| + Net Cash ($M) | 2,477 | 2,477 | 2,477 |
| **Equity Value ($M)** | **41,208** | **24,566** | **13,247** |
| ÷ Shares (M) | 206.1 | 206.1 | 206.1 |
| **Per Share** | **$199.94** | **$119.20** | **$64.27** |
| Upside / (Downside) | +43.1% | **(14.7%)** | (54.0%) |
| TV % of Total EV | 76.4% ⚠️ | 71.1% ⚠️ | 65.0% |

### ⚠️ Terminal Value Flag
Both bull and base scenarios exceed 70% TV concentration. This is typical for high-growth platforms whose cash flows are back-end-weighted, but it means **the valuation is sensitive to assumptions about the end state, not the near term**. The base case assumes RDDT reaches $7.7B revenue at 30% FCF-ex-SBC margin by FY32 — both achievable but neither guaranteed.

### Round-Trip Check
- Current EV / FY26 Base Revenue: **8.42x**
- Fair EV (base case) / FY26 Revenue: **7.06x**
- Delta: Current multiple is ~20% above the DCF-implied fair multiple → consistent with the 15% per-share downside in the base case.

---

## VALUATION METHOD 3: TRADING COMPS

Peer set from AdTech sector handoff v2 (April 6, 2026). Walled gardens and social platforms are RDDT's most relevant tier; pure-play independents are referenced for context.

### Peer Comparison

| Ticker | MRQ Growth | EV/NTM Rev | FCF Margin | Gross Margin | SBC % | Growth-Adj (Mult ÷ Growth×100) |
|---|---|---|---|---|---|---|
| META | +24% | 5.8x | 21.7% | 82.0% | 10.2% | 0.242 |
| GOOGL | +18% | 7.3x | 18.2% | 59.7% | 6.2% | 0.406 |
| AMZN (full) | +23% | 2.9x | 1.6% | 50.3% | 2.7% | 0.126 |
| **APP** | **+67%** | **17.8x** | **72.1%** | **87.9%** | **3.0%** | **0.266** |
| PINS | +14% | 1.92x | 29.7% | 80.0% | 20.8% | 0.137 |
| SNAP | +10% | 1.17x | 7.4% | 55.0% | 17.1% | 0.117 |
| ZETA | +34% | 2.0x | 15.0% | 60.0% | 8.0% | 0.059 |
| **RDDT** | **+70%** | **8.23x** | **31.1%** | **91.2%** | **15.6%** | **0.118** |

### RDDT Positioning
- **Growth rank: #1** in peer group (70% vs peer median 23%)
- **Gross margin rank: #1** (91.2% vs peer median 60.0%)
- **Reported FCF margin rank: #2** (31.1% vs peer median 18.2%) — behind APP only
- **Growth-adjusted ratio: 0.118** — below peer median 0.137 (i.e., RDDT screens CHEAP per unit of growth)
- **Drawback: SBC 15.6%** — 2nd worst of the group (tied with PINS). This is the primary counterweight to the quality story.

### Fair Multiple Framework
Two framings give different answers:

**Framing A — Growth-adjusted regression.** RDDT at 45% NTM growth and 91% GM should trade at roughly the same growth-adjusted multiple as the high-quality group (META 0.24, APP 0.27). Applying 0.17–0.20 growth-adjusted to 45% growth gives 7.6–9.0x NTM Rev. This roughly matches current 8.2x — **approximately fair**.

**Framing B — Absolute multiples for pure-play ad platforms.** META (24% grower, best-in-class business) trades at 5.8x. RDDT is a 45% NTM grower but on a smaller base with higher risk. Paying 8.2x vs META's 5.8x implicitly prices RDDT at a 41% premium to the highest-quality benchmark. That's defensible only if you believe the growth trajectory holds — which is exactly the debate.

### Price Target — Trading Comps

Applied range centered on growth-adjusted framing, reflecting where RDDT *should* trade for its growth and quality:

| | Multiple (EV/NTM Rev) | EV ($M) | Equity ($M) | Per Share |
|---|---|---|---|---|
| Bear | 5.4x | 17,280 | 19,757 | **$95.86** (-31%) |
| Base | 7.65x | 24,480 | 26,957 | **$130.79** (-6%) |
| Bull | 9.9x | 31,680 | 34,157 | **$165.73** (+19%) |

**Confidence: HIGH** — peer set is well-defined and RDDT's positioning vs. peers is clean.

---

## VALUATION METHOD 4: PRECEDENT M&A COMPS

### Relevant Transactions

Precedents for buying a social media / ad platform at RDDT's scale are sparse. The most relevant reference points:

| Year | Target | Acquirer | EV ($B) | EV/Rev | Notes |
|---|---|---|---|---|---|
| 2016 | LinkedIn | Microsoft | 26.2 | ~7.2x | Platform + data asset, closest analogy |
| 2022 | Twitter | Musk/Take-private | 44 | ~6.9x | Hostile; comparable scale |
| 2014 | WhatsApp | Meta | 19 | N/M | Pre-revenue; not comparable |
| Sector handoff "high-growth >30%" range | — | — | — | 10–15x ARR | Not directly applicable to ad-supported |

### Reddit Takeout Analysis

**Multiple range: 6.0x – 9.0x NTM Revenue**

| Multiple | EV ($M) | Per Share (pre-discount) | Per Share (25% control-premium discount) |
|---|---|---|---|
| 6.0x | 19,200 | $105.18 | **$78.88** (bear) |
| 7.5x | 24,000 | $128.47 | **$96.35** (base) |
| 9.0x | 28,800 | $151.76 | **$113.82** (bull) |

### ⚠️ Realistic Probability of Takeout: LOW
1. **Dual-class voting** — Huffman/Ohanian/Advance (Newhouse) hold Class B at 10x voting. Hostile bid is structurally impossible; friendly deal requires founder consent.
2. **Regulatory risk** — Any Big Tech acquirer (Google, Meta, Amazon, MSFT) would face immediate antitrust block given current environment.
3. **Scale** — $26B EV is beyond most PE funds' single-deal capacity.
4. **Timing** — Acquiring a company at peak growth is the opposite of a typical M&A profile.

**Conclusion:** M&A comps provide a **ceiling reference** rather than a realistic takeout floor. Weight this method at **5%** and use it only to sanity-check that the stock is not below a plausible buyer's walk-away price.

---

## VALUATION METHOD 5: SUM-OF-PARTS

Reddit discloses two revenue lines that warrant distinct treatment:

### Segment 1: Advertising
- FY25 revenue: $2,062.5M (+74% YoY)
- NTM implied (94% of FY26 consensus): **~$3,008M**
- Comparable pure-play ad platforms: META 5.8x, APP 17.8x, PINS 1.92x, SNAP 1.17x
- Applied multiple: **7.0x NTM Rev** — reflects premium to META for faster growth, discount to APP for smaller scale and higher SBC
- **Segment EV: $21,056M**

### Segment 2: Data Licensing / AI Training Data
- FY25 revenue: $140M (+22% YoY)
- NTM implied (~6% of FY26): **~$192M**
- This is a scarce, strategic asset: the largest structured conversational dataset on the open web. 2–3 year contracts with Google (~$60M) and OpenAI (~$70M) — both approaching renewal in 2026–2027
- Applied multiple: **10.0x NTM Rev** — premium reflects scarcity and rising demand for training data, but discounted by contract concentration risk and active litigation (Anthropic, Perplexity)
- **Segment EV: $1,920M**

### Total SoP Valuation

| | EV ($M) |
|---|---|
| Advertising (7.0x × $3,008M) | 21,056 |
| Data Licensing (10.0x × $192M) | 1,920 |
| **Total EV** | **22,976** |
| + Net Cash | 2,477 |
| **Equity Value** | **25,453** |
| ÷ Shares (M) | 206.1 |
| **Per Share** | **$123.50** (-11.6%) |

### SoP Sensitivity

| | Ad Multiple | DL Multiple | Per Share |
|---|---|---|---|
| Bear | 5.5x | 7.0x | $98.81 |
| Base | 7.0x | 10.0x | $123.50 |
| Bull | 9.0x | 15.0x | $157.34 |

### Hidden Value Flag
The data licensing segment carries **optionality** not fully reflected in the base case multiple. If the AI-training-data market matures into a durable, renewable revenue stream (not a one-time licensing boom), a 15–20x multiple on this segment would be defensible. Conversely, if Anthropic/Perplexity lawsuits fail or contracts get repriced downward at renewal, this segment could compress to 5x. This is a genuine call-option embedded in the valuation.

---

## VALUATION METHOD 6: PE / LBO FLOOR

### Entry Assumptions
- Entry premium: 15% on current EV
- Entry EV: $30,270M
- Debt capacity: 4.0x LTM Adj EBITDA = 4.0 × $845M = **$3,380M**
- Equity required: **$26,889M**
- Interest rate: 7.0%, tax shield 21% → $187M/yr net interest burden

### 5-Year Projection (base-case operating assumptions)

| Year | Revenue ($M) | EBITDA ($M) | FCF post-interest ($M) |
|---|---|---|---|
| 1 | 3,128 | 1,251 | 407 |
| 2 | 4,003 | 1,681 | 694 |
| 3 | 4,884 | 2,100 | 1,034 |
| 4 | 5,714 | 2,514 | 1,356 |
| 5 | 6,457 | 2,841 | 1,621 |

### Exit & Return
- Exit NTM revenue (Yr6): $7,103M
- Exit multiple: 7.0x (slight compression from entry ~9x)
- Exit EV: $49,720M
- Exit equity (EV − remaining debt + cumulative FCF): $51,451M
- **IRR at 15% entry premium: 13.9%** — below the 20% PE hurdle

### Floor Price (20% IRR Target)
Solving for maximum entry EV that achieves 20% IRR:
- **Max entry EV: $24,058M (0.91x current EV)**
- **Floor per share: $128.75** (-7.9% from current)

### ⚠️ Reality Check
Reddit is an **unrealistic LBO target**:
1. $27B equity check is beyond virtually all PE funds
2. Dual-class voting blocks hostile approach
3. Growth company at peak trajectory — wrong investment profile for LBO math (PE wants stable cash flows)
4. RDDT's $343M SBC would flow through post-LBO P&L as cash comp, eroding the model returns

Treat $128.75 as a theoretical downside floor only. **Weight: 5%.**

---

## TRIANGULATION & SYNTHESIS

### Method Results Table

| Method | Bear | Base | Bull | Weight | Confidence |
|---|---|---|---|---|---|
| Reverse DCF | — | 17.4% implied CAGR (vs 45% actual NTM) → mildly overvalued | — | — | High |
| Forward DCF | $64.27 | $119.20 | $199.94 | 35% | Medium |
| Trading Comps | $95.86 | $130.79 | $165.73 | 35% | High |
| M&A Comps | $81.90 | $96.35 | $115.62 | 5% | Low |
| Sum-of-Parts | $98.81 | $123.50 | $157.34 | 20% | Medium |
| PE / LBO Floor | $128.75 | $128.75 | $128.75 | 5% | Low |

### Blended Price Target

| Scenario | Blended PT | vs Current ($139.73) |
|---|---|---|
| **Bear** | **$86.34** | **(38.2%)** |
| **Base** | **$123.45** | **(11.7%)** |
| **Bull** | **$171.67** | **+22.9%** |

### Convergence Analysis — The Most Important Observation

Look at the **base case spread across methods**:

| Method | Base PT |
|---|---|
| Forward DCF | $119.20 |
| Trading Comps | $130.79 |
| Sum-of-Parts | $123.50 |
| LBO Floor | $128.75 |
| **Tight cluster** | **$119–$131** |

Four of five meaningful methods converge in a **$119–$131** range. This is **tight convergence** for a growth stock, and the message is clear: **RDDT is trading modestly above fundamental fair value at $139.73**, not dramatically so. The street's $224.93 average PT relies on bull-case assumptions the DCF/comps do not ratify.

### ⚠️ Counter-evidence worth respecting
- Trading comps show RDDT's growth-adjusted multiple (0.118) is BELOW peer median (0.137) — on pure growth-adjusted logic, RDDT screens CHEAP
- The reverse DCF using **reported** FCF (not SBC-adjusted) shows only a 14.6% implied CAGR — easily achievable
- The SoP model does not fully capture the optionality in the data licensing segment
- Q4'25 saw +70% revenue growth, +75% advertiser count growth, +42% ARPU growth — the trajectory is still accelerating, not decelerating

The base case of $119-$131 represents a **disciplined DCF-centric view** but may under-price the momentum and the optionality. The bull case of $172 would require RDDT to re-rate back to ~11x NTM Rev on sustained 40%+ growth — not impossible, but requires continued flawless execution.

### Conviction Score: 3.5 / 5

**Rationale:** Methods converge tightly ($119–$131 base range), giving a clean signal. However:
- The signal says "roughly fair to mildly overvalued" — not an obvious short, not an obvious long
- Base case shows ~12% downside; bull case only +23% — neither side has a dominant expected value
- Growth trajectory is still strong (70% YoY in Q4'25) and could maintain longer than the DCF models assume
- The SBC treatment is the single biggest swing factor: strict (FCF-ex-SBC) = modest overvaluation; lenient (reported FCF) = fair value
- Director Farrell's $8.87M open-market purchase at $148/$132 is an insider conviction signal pointing up; clustered C-suite selling via 10b5-1 is noise

**Conviction = 3.5** reflects genuine method convergence but ambiguous directional signal.

---

## KEY RISKS TO VALUATION

| Risk | Impact | Mitigation in Model |
|---|---|---|
| Google AI Overviews cannibalize logged-out DAU growth | Near-term top-of-funnel compression | Bear case assumes faster deceleration |
| Data licensing contract repricing (Google, OpenAI renewals 2026–2027) | -$50–100M on Other revenue | Immaterial at 6% of total; SoP segment captures range |
| Anthropic/Perplexity litigation adverse ruling | Undermines licensing-revenue moat | Reflected in low DL multiple bear case (5.5x) |
| Macro ad recession | Revenue growth compression across scenarios | Bear case −30pts of growth in Yr1 |
| SBC normalization higher than 15.6% | Worsens economic-FCF math | Already the base assumption |
| Dual-class governance → S&P 500 exclusion risk | Index-flow re-rate delayed/denied | Not in base case; upside optionality only |

---

## DELIVERABLE 3: OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━
TICKER: RDDT
COMPANY: Reddit, Inc.
SECTOR: Digital Advertising / Social Platform
VALUATION DATE: April 12, 2026

PRICE TARGET: $123 base case (range: $86 bear — $172 bull)
CURRENT PRICE: $139.73
UPSIDE TO BASE: (11.7%) [NEGATIVE — current price above base fair value]
CONVICTION: 3.5 / 5

WHEEL STRATEGY IMPLICATIONS:

- SELL PUTS: NO at current price — CONDITIONAL if price drops
  Rationale: Base case fair value ($123) is BELOW current price ($139.73).
  Selling puts above fair value is negative EV by wheel framework rules.
  Wait for spot to trade ≤$125 before initiating put sales.

  Conditional re-engagement thresholds:
  - If spot ≤ $125: Begin selling puts strike $100-$115 (bear to base zone)
  - If spot ≤ $110: Aggressive put-selling, strike $85-$100
  - Do NOT sell puts with strikes above $125 under any condition
  - Avoid short-dated puts through Q1'26 earnings event

- COVERED CALLS (if assigned): CONDITIONAL
  Cost basis assumption: put strike assigned (would be $100-$115 zone)
  Minimum call strike: cost basis × 1.00 (per cc_min_strike_pct=1.0 rule)
  Suggested call strike zone: $125-$150 (at/above base case PT)
  Do NOT sell calls above $170 (approaching bull case — let it run)

- CONCENTRATED LONG CANDIDATE: NO
  Conviction 3.5 < 4.0 threshold
  Base case upside (11.7%) is NEGATIVE, far below 30% threshold
  Both gating criteria fail — do not take concentrated long exposure

KEY DATES TO AVOID:
- Late April / early May 2026: Q1 2026 earnings (Reddit has beat rev by 11% and EBITDA by 29% on average; catalyst is volatile either way)
- June 2026 S&P 500 rebalance announcement: binary inclusion event
- 2026-2027: Google/OpenAI data licensing contract renewals (staged through year)
- January 2026+: Anthropic lawsuit federal court hearing (SF)

SECTOR CONTEXT:
- Sector score from handoff: 22/25 (tied 4th in universe after META 24, APP 23, AMZN 23)
- Relative ranking: Top-quartile quality within AdTech sector
- Sector-level risk flag: AI search disruption (shared with GOOGL), ad recession (sector-wide)
- Peer benchmark: Trades at 8.2x NTM Rev vs META 5.8x (premium justified by 3x growth)
  but vs APP 17.8x (discount appropriate given SBC and scale gap)

SBC SPECIAL NOTE:
- FY25 SBC = 15.6% of revenue (above 15% threshold)
- Base case uses economic (FCF-ex-SBC) margins; if SBC normalizes below 12%,
  base case PT rises ~$15/share toward $138 (near fair at current price)
- If SBC trends higher (dilution creep), base case PT falls toward $105
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## SUMMARY VERDICT

**RDDT at $139.73 is a high-quality business trading modestly above fundamental fair value.** The core tension is real: growth (+70%), margins (91% GM, 31% reported FCF margin), and monetization trajectory (+75% advertisers, +42% ARPU) are best-in-class among ad platforms, but 15.6% SBC erodes economic FCF to ~half of reported, and the DCF methods cluster around $119–$131.

**The stock is not a short** — business quality is too high and growth too durable. But it is **not a concentrated long here** either: base case shows negative upside, bull case upside (+23%) falls short of the 30% threshold, and conviction is only 3.5/5.

**Wheel strategy:** Stand aside until price retraces to the $120–$125 zone, then initiate put selling at strikes below bear case. Do not chase at current levels. Do not write covered calls above $170 if assigned — the bull case is live and the growth narrative could re-rate upward if Q1'26 prints another blowout.

The analyst consensus PT of $224.93 relies on assumptions this model does not ratify. Director Farrell's ~$9M open-market purchase says more about long-term conviction than near-term entry timing.
