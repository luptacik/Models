# ZETA GLOBAL — V2 SUPPLEMENTAL ANALYSIS

**Companion to ZETA_V2_Valuation.md**  |  **Analysis Date:** April 12, 2026  
**Current Price:** $14.60

This document runs four deep-dives that sharpen — and in some places temper — the core V2 conclusions: (1) SBC-adjusted dual-track DCF, (2) forward dilution modeling, (3) peer regression fair value, (4) Q1'26 earnings scenario sensitivity, (5) Athena real-option valuation.

**Headline finding:** The core thesis (undervalued, conviction 4/5) survives the stress tests, but with important caveats. The SBC-adjusted DCF cuts the reported base case in half, and the ex-APP peer regression collapses to approximately the current price. The honest conclusion is that ZETA is cheap on reported numbers and fair on economic numbers — the upside depends on the SBC trajectory continuing to improve AND the market re-rating the multiple, both of which require Q1'26 execution.

---

## 1. SBC-ADJUSTED DUAL-TRACK DCF

**Why it matters:** FY25 SBC was 13.6% of revenue — below the 15% dual-track threshold but high enough that the reported vs economic FCF gap is material. FY25 FCF was $164.7M reported but only −$13.1M after SBC. Terminal value assumptions amplify this gap over a 7-year DCF.

### SBC Trajectory Assumption

Management has not explicitly guided to an SBC glide-path, so I assume a gradual decline from 13.6% in FY25 to 8% in Year 7, reflecting (a) maturation of stock grants, (b) reduced M&A-related grants post-Marigold, (c) rising cash compensation as the business scales. This is consistent with typical SaaS SBC normalization.

### Dual-Track Projection (Base Case)

| Year | Revenue | Reported FCF% | SBC % | Adj FCF% | Rep FCF | Adj FCF |
|---|---|---|---|---|---|---|
| 1 | $1,755M | 13.2% | 12.0% | 1.2% | $232M | $21M |
| 2 | $2,044M | 14.0% | 11.0% | 3.0% | $286M | $61M |
| 3 | $2,341M | 14.8% | 10.0% | 4.8% | $346M | $112M |
| 4 | $2,622M | 15.5% | 9.5% | 6.0% | $406M | $157M |
| 5 | $2,884M | 16.0% | 9.0% | 7.0% | $461M | $202M |
| 6 | $3,115M | 16.5% | 8.5% | 8.0% | $514M | $249M |
| 7 | $3,301M | 17.0% | 8.0% | 9.0% | $561M | $297M |

### Valuation — Dual Track

| Track | EV ($M) | Per Share | Upside/(Downside) |
|---|---|---|---|
| **Reported FCF** (term mgn 17%) | 6,087 | **$25.35** | **+74%** |
| **SBC-Adjusted FCF** (term mgn 9%) | 2,924 | **$12.43** | **−15%** |
| **Midpoint (50/50 blend)** | 4,506 | **$18.89** | **+29%** |

### Interpretation

The $12.91/sh gap between tracks — roughly 88% of the current price — is the single most important sensitivity in the ZETA valuation. Three observations:

- **The reported track is only credible if you believe SBC will decline meaningfully.** FY25 showed exactly this (13.6% vs 19.4% prior year), but the path from here is not guaranteed. Post-Marigold retention grants could push SBC back up in FY26.

- **The SBC-adjusted track is unforgiving.** Even under a base-case growth trajectory, SBC-adjusted FCF only turns meaningfully positive in Year 3 and the terminal 9% economic FCF margin is below SaaS peer benchmarks.

- **The honest midpoint is $18.89 — +29% upside.** This is still a good return, but it is not the +60% implied by taking reported FCF at face value. This figure should arguably replace the pure-reported base case in the triangulation for investors who weight SBC heavily.

---

## 2. FORWARD DILUTION MODELING

**Why it matters:** FY25 diluted shares grew +18.7% YoY. Even backing out the one-time Marigold $100M equity issuance (~4% of share count), underlying SBC-driven dilution runs ~5-6% gross, ~3-4% net of buybacks. Over a 5-year DCF horizon, this materially compresses per-share value.

### Assumed Forward Dilution Path

Assumption: dilution decelerates as SBC normalizes and buyback continues (management has $200M authorization from Aug 2025 plus residual from Nov 2024).

| Year | Shares (M) | YoY dilution | Cumulative vs today |
|---|---|---|---|
| Now | 245.0 | — | — |
| Y1 | 254.8 | 4.0% | +4.0% |
| Y2 | 262.4 | 3.0% | +7.1% |
| Y3 | 269.0 | 2.5% | +9.8% |
| Y4 | 275.7 | 2.5% | +12.5% |
| Y5 | 281.2 | 2.0% | +14.8% |
| Y6 | 286.9 | 2.0% | +17.1% |
| Y7 | 292.6 | 2.0% | +19.4% |

### Impact on Base Case PT

Holding base case DCF equity value constant at $6,210M:

| Time | Shares | Per-share | Drag |
|---|---|---|---|
| Today | 245.0M | $25.35 | — |
| Y3 | 269.0M | $23.09 | −9% |
| Y5 | 281.2M | $22.08 | −13% |

**Dilution drag: ~10-13% of base case PT over 5 years.** This is a genuine economic cost that investors should price in. Even aggressive buyback assumptions (net dilution of 1-2%) only reduce the 5-year drag to ~10%.

**Adjusted base case incorporating dilution drag: $22.50/sh (+54% upside)** — still meaningfully undervalued but ~10% below the static $25.35 figure.

---

## 3. PEER REGRESSION — EV/NTM Rev vs NTM Growth

**Why it matters:** The core report applied judgment-anchored trading comps multiples (2-4x NTM Rev). A formal regression tests whether the peer relationship between growth and multiple supports those numbers.

### Full Regression (APP included)

```
Regression: EV/NTM Rev = −4.24 + 0.443 × Growth(%)
R² = 0.896 (strong fit, but driven by APP outlier)

ZETA at 34.6% growth → fair mult 11.09x → $79.93/sh (+447%)
```

**This is not credible.** The R² is high only because APP's 47% / 17.8x combo anchors the top-right of the scatter. Removing APP shows the truth:

### Ex-APP Regression (ZETA-relevant peers only)

```
Regression: EV/NTM Rev = 2.22 − 0.010 × Growth(%)
R² = 0.004 (essentially no relationship)

ZETA fair mult = 1.87x → $13.89/sh (−5% vs current)
```

### Interpretation — The Regression Is a Problem for the Bull Case

The ex-APP regression tells an uncomfortable truth: **within the independent AdTech peer set, there is no growth premium.** TTD at 18% growth trades at 2.8x; MGNI at 11% growth trades at 2.6x; ROKU at 16% trades at 2.3x. The market is essentially paying the same multiple regardless of growth rate — because the multiples are set by sector-level factors (ad cyclicality, Google antitrust, SBC overhang) rather than company-specific growth.

**This means ZETA needs a specific catalyst to re-rate** — not just demonstrate growth. Continuing to deliver 30%+ growth quarter after quarter will NOT mechanically lift the multiple if the sector stays de-rated. The catalysts that could break this:

- Google ad-tech antitrust remedy (sector-wide re-rate)
- Ad recession fears lifting (macro)
- ZETA-specific: Athena/OpenAI RFP data validating AI agent thesis
- M&A interest emerging (strategic or PE)

**The original 3.0x base case trading comps multiple assumes re-rating happens.** If the sector stays at 2.0x, ZETA's fair trading-comps value is $14.83 — approximately the current price. This validates the bear case trading-comps number and suggests the trading-comps weight in the triangulation may be too generous to the bull side.

---

## 4. Q1'26 EARNINGS SCENARIO SENSITIVITY — Apr 30, 2026

**Why it matters:** Q1'26 is the single largest near-term binary. It is the first full quarter of Marigold consolidation and the first data point on Athena AI GA adoption. Management guide: $370M revenue (+39% headline, +22% ex-political/Marigold) and $61.5M Adj EBITDA.

### Four Scenarios

| Scenario | Q1 Rev | FY26 Guide Δ | Mult Δ | Implied Price | Move vs $14.60 |
|---|---|---|---|---|---|
| **Miss (−3%)** | $359M | −2% (lowered) | −25% | **$10.88** | **−26%** |
| **Inline** | $370M | 0% | 0% | **$14.62** | **+0%** |
| **Small beat (+3%)** | $381M | +1% | +10% | **$16.18** | **+11%** |
| **Strong beat (+5%)** | $388M | +2% | +25% | **$18.50** | **+27%** |

### Near-Term Risk/Reward Is NOT Favorable

Probability-weighted near-term (my estimates):

| Scenario | Probability | Price | Contribution |
|---|---|---|---|
| Miss | 15% | $10.88 | $1.63 |
| Inline | 25% | $14.62 | $3.66 |
| Small beat | 45% | $16.18 | $7.28 |
| Strong beat | 15% | $18.50 | $2.78 |
| **Weighted** | 100% | — | **$15.34** |

**Expected move: +5%** — modest. The 18-quarter beat streak makes a small beat the base case, but 15% miss probability is material. The downside of a miss (−26%) is larger than the upside of a strong beat (+27%), and historical ZETA post-earnings moves have been volatile.

**Implication for options positioning:** Consider selling puts BEFORE April 30 at deep strikes ($12-12.50) to collect pre-earnings vol, but size carefully. The concentrated long entry should split 50% before the print, 50% after — capturing any confirmation move while protecting against a tail miss.

---

## 5. ATHENA / OPENAI REAL OPTIONALITY

**Why it matters:** ZETA's Athena AI agent reached GA on March 24, 2026, powered by the OpenAI strategic collaboration announced at CES (Jan 5, 2026). Management has cited 'RFP volume more than doubled YoY' and 'holiday platform usage +153%' as early indicators. None of this is in the base case — the DCF uses mgmt's 2028 guidance which includes only organic+Marigold growth.

### Upside Sizing

Scenario: Athena drives $500M incremental FY28 revenue beyond base case (vs. Marigold's ~$190M contribution for context — Athena would need to be ~2.5x Marigold in impact).

| Input | Value |
|---|---|
| Incremental FY28 revenue | $500M |
| Applied multiple (AI agent premium) | 5.0x |
| Gross incremental EV | $2,500M |
| Probability of success | 30% |
| **Probability-weighted EV** | **$750M** |
| **Per share (245M shares)** | **$3.06** |

### Current Pricing of Athena in Multiple

The market currently values ZETA at a growth-adjusted multiple of 0.057x — essentially the same as CRTO at 2% growth. This means zero Athena premium is priced in. If Q1'26 RFP conversion data validates even a modest Athena contribution, the option value becomes real and could contribute $3/share ($750M of EV) to the thesis — roughly 20% of the base case upside.

**This is also why the bull case ($33/sh) is not insane.** It requires both (a) the base case growth trajectory AND (b) the Athena option to be realized.

---

## REVISED TRIANGULATION (Incorporating Deep-Dives)

| Method | Original V2 | Stress-Tested | Change |
|---|---|---|---|
| Forward DCF (reported) | $25.35 | $25.35 | — |
| Forward DCF (SBC-adj midpoint) | — | **$18.89** | new |
| Forward DCF (dilution-adj) | — | **$22.08** | new |
| Trading Comps (base 3.0x) | $22.00 | $22.00 | assumes re-rate |
| Trading Comps (ex-APP regression) | — | **$13.89** | new — no re-rate |
| M&A Comps base | $27.25 | $27.25 | — |
| LBO Floor | $17.55 | $17.55 | — |
| Athena optionality | $0 | **+$3.06** | new |

### Stress-Tested Weighted PT

Using the more conservative readings where available:

- DCF: $18.89 (SBC-adj midpoint, includes dilution drag implicitly)
- Comps: $18.00 (blend of judgment-anchored $22 and ex-APP regression $13.89)
- M&A: $27.25 (unchanged)
- LBO: $17.55 (unchanged)
- Athena option: +$3.06

**Stress-tested base case: ~$21-22/sh (+45-50% upside).** Still compelling, but materially below the original $23.40 weighted base.

### Revised Conviction: **3.5 / 5**

The original 4/5 assumed the reported FCF track and the peer comp multiples at face value. The stress tests reveal:

- The base case is heavily dependent on SBC continuing to decline
- There is no mechanical peer-multiple re-rating — it requires a catalyst
- Q1'26 earnings has asymmetric near-term risk (miss = −26%, beat = +11%)
- 10-13% dilution drag over 5 years is a real per-share tax

However, the core mispricing signal remains robust:

- Reverse DCF still implies 4% CAGR vs 21% consensus — this gap doesn't shrink
- LBO floor of $17.55 provides meaningful downside support
- Multiple independent methods all point above current price
- The 18-quarter beat streak is a real track record, not a narrative

**Verdict:** Still a buy, but with reduced conviction and staged entry. The 'cheap' version of the thesis (SBC-adjusted, no re-rate) gets you to ~$18-19. The 'optimistic' version ($25-27) requires the reported FCF track to hold AND the market to re-rate. Both are plausible, neither is guaranteed.

---
## REVISED OPTIONS WHEEL POSITIONING

```
━━━ REVISED WHEEL HANDOFF (Post Deep-Dive) ━━━━━━
TICKER: ZETA
REVISED PT: $21-22 base case (was $23.40)
REVISED CONVICTION: 3.5/5 (was 4/5)
CONCENTRATED LONG: YES, but STAGED entry

ENTRY STAGING:
- 40% position pre-Apr 30 earnings (sell puts $12-13 strikes)
- 40% position post-earnings if beat or inline ($15-16 levels)
- 20% reserve for any dip below $13 (add via puts or direct)

PUT SELLING — REVISED:
- Primary strikes: $12.00 and $12.50 (18-36 DTE)
- NOT $13.50 — too close to current given miss risk
- Hard ceiling: $15.00 (do not sell puts above)
- Avoid expiries crossing Apr 30 earnings unless very deep OTM

COVERED CALLS (if assigned):
- Minimum strike: cost basis
- Preferred range: $17-20 (above LBO floor, below base PT)
- Hold until base case realized or 30 DTE

KEY NEAR-TERM EVENTS:
- Apr 30, 2026: Q1'26 earnings — biggest single event
- Q2'26 print (late Jul): first full Marigold quarter
- Ongoing: Google antitrust remedy ruling (sector catalyst)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---
## APPENDIX: KEY SENSITIVITIES RANKED BY IMPACT

| Sensitivity | Bear impact | Bull impact | Notes |
|---|---|---|---|
| SBC trajectory | −$12.90/sh | 0 | By far the largest swing factor |
| Market re-rating | −$8.00/sh | +$5.00/sh | Requires catalyst |
| Dilution path | −$3.00/sh | +$1.00/sh | Buyback-dependent |
| Q1'26 print | −$3.80/sh | +$3.90/sh | Binary near-term |
| Athena optionality | 0 | +$3.06/sh | Currently priced at $0 |
| WACC (±1%) | −$3.50/sh | +$4.00/sh | Standard DCF sensitivity |
| Terminal FCF margin (±2%) | −$3.00/sh | +$3.50/sh | |