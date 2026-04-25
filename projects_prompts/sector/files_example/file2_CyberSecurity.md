# SCORING CALIBRATION GUIDE
*Project knowledge file for Sector Analysis Project (A1 prompt)*
*Prevents score clustering. Read before scoring every run.*

---

## Core Principle

**Force differentiation. If all companies score 3 on a dimension, you have not done the work.**

The distribution across a typical 6–8 company peer group should look roughly like:
- One or two 5s (genuine leaders)
- Two or three 3–4s (solid, competitive)
- One or two 1–2s (structurally challenged or overvalued)

If your scores are clustering 3–4 across the board, you are being diplomatic. Retry.

---

## DIMENSION 1: SUB-SECTOR TAILWIND

*Is this sub-sector growing fast enough and is the company positioned to capture it?*
*This dimension combines the sub-sector's structural health WITH the company's positioning within it.*

| Score | What It Looks Like |
|-------|--------------------|
| **5** | Company is in the highest-growth sub-sector in the space (>25% TAM CAGR) AND is a clear share gainer. Regulatory tailwinds are active and budget-forcing. Demand is non-discretionary. **Example**: CRWD in XDR during cloud migration wave; ZS in SASE with zero-trust mandates. |
| **4** | Strong sub-sector growth (15–25% TAM CAGR) and company is holding or gaining share. One meaningful tailwind driver. |
| **3** | Solid sub-sector growth (10–15%) but company is not a clear share gainer — tracking the market, not beating it. Or: Fast sub-sector but company is #3–4 with no differentiated positioning. |
| **2** | Sub-sector is slowing (<10% growth) OR company is clearly losing share despite reasonable market growth. Signs of commoditization or substitution threat emerging. |
| **1** | Sub-sector is mature/declining or facing structural disruption (e.g. legacy SIEM being replaced by cloud-native). Company is positioned in the shrinking part of the market. **Example**: On-prem firewall vendor with no cloud transition. |

---

## DIMENSION 2: COMPETITIVE MOAT

*Switching costs, network effects, platform breadth, pricing power.*
*Be skeptical. SaaS companies systematically overclaim moats. Require evidence, not assertions.*

| Score | What It Looks Like |
|-------|--------------------|
| **5** | Ripping out this product would require a 6–18 month customer project with multi-team involvement. Multiple integrated modules make partial removal operationally irrational. Gross retention (not net) is 95%+. Platform has documented network effects or data flywheel. Pricing power demonstrated by NRR 125%+. **Example**: CRWD with 10+ Falcon modules deployed; CyberArk PAM deeply embedded in vault infrastructure. |
| **4** | High switching costs in the core product. Customers renew reliably (GRR 90%+) but expansion is not yet compounding from platform breadth. 2–3 integrated modules. Some pricing power. |
| **3** | Moderate switching costs — comparable alternatives exist but migration is painful enough that most customers stay. Single-product or early multi-product. NRR 110–120% range. Pricing power limited by competition. |
| **2** | Point solution with direct substitutes. Customers can and do evaluate alternatives at renewal. NRR around 105–110%. Price sensitive. Competitive displacement wins are offsetting by losses elsewhere. |
| **1** | Commoditizing. Pricing power absent — competing on price. No meaningful lock-in. GRR declining. Active customer churn. Being displaced by a platform player bundling competitive functionality. **Example**: Standalone email security vendor competing against Microsoft bundled Defender. |

**Moat red flags — any of these should cap score at 3:**
- Company refuses to disclose gross retention separately from net retention
- NRR recently declined from 120%+ to sub-115% without clear explanation
- Customers citing the product in competitive loss disclosures
- Microsoft or CrowdStrike announced a competing module in the same space

---

## DIMENSION 3: BUSINESS MODEL QUALITY

*NRR, Rule of 40, gross margins, ARR growth trajectory vs. FCF margin trajectory.*
*This is a purely quantitative dimension. Let the numbers score themselves.*

| Score | What It Looks Like |
|-------|--------------------|
| **5** | NRR 125%+, Rule of 40 >50, gross margins >75%, ARR growth >30% YoY, FCF margin clearly expanding toward 20%+, RPO growth tracking or ahead of ARR growth. Every metric in the top quartile for SaaS. |
| **4** | NRR 115–125%, Rule of 40 35–50, gross margins 70–75%, ARR growth 20–30%, FCF positive and expanding. Strong on most metrics, one area of softness. |
| **3** | NRR 110–115%, Rule of 40 25–35, gross margins 65–75%, ARR growth 15–20%. Solid fundamentals, nothing alarming, nothing exceptional. Typical of a well-run mid-stage SaaS. |
| **2** | NRR 105–110% (expansion slowing), Rule of 40 <25, FCF breakeven or slightly negative with no clear path to improvement, ARR growth decelerating without a clear explanation. One or more metrics in the bottom quartile. |
| **1** | NRR sub-105% (approaching gross churn levels), FCF negative and worsening, SBC > 15% of revenue (dilution alarm), ARR growth below 10% or decelerating sharply. Business model under structural pressure. |

**Specific quantitative thresholds:**

| Metric | 5 | 4 | 3 | 2 | 1 |
|--------|---|---|---|---|---|
| NRR | >125% | 115–125% | 110–115% | 105–110% | <105% |
| Rule of 40 | >50 | 35–50 | 25–35 | 15–25 | <15 |
| Gross Margin | >78% | 73–78% | 68–73% | 63–68% | <63% |
| ARR Growth | >30% | 20–30% | 15–20% | 8–15% | <8% |
| FCF Margin | >20% | 12–20% | 5–12% | 0–5% | Negative |

*If data is missing for a metric, do not estimate. Note the gap and hold the dimension score at 3 maximum.*

---

## DIMENSION 4: MANAGEMENT EXECUTION

*Guidance accuracy, beat cadence, capital allocation quality, strategic coherence.*

| Score | What It Looks Like |
|-------|--------------------|
| **5** | Beats revenue consensus 3 of last 4 quarters. Guidance is conservative and gets raised intra-year (sandbagging pattern). Capital allocated to organic growth + targeted M&A with clear strategic rationale. No major strategic pivots or reversals in last 2 years. Management commentary is specific and data-anchored. **Example**: CRWD consistently guiding conservatively; PANW CEO with clear platformization narrative executed over 3 years. |
| **4** | Beats consistently (2–3 of 4 quarters). Guidance is reliable. One capital allocation decision that raised questions but was explained clearly. No major stumbles. |
| **3** | Mixed beat/miss pattern (2 of 4). Guidance roughly inline with outcomes. No major blunders but also no evidence of conservative guidance discipline. Strategic pivots are explicable if not perfectly executed. |
| **2** | Recent miss(es) with guidance cut. Strategic direction has shifted without clear explanation. Overpaid for M&A or dilutive secondary. Management changes with no clear narrative. |
| **1** | Multiple guidance cuts in last 4 quarters. Strategic reversal or major initiative abandoned. Large dilutive capital raise. CEO departure with no plan. Trust with the market significantly impaired. **Example**: Okta post-breach handling; any company that did a surprise lowered guide in a strong tape. |

**Execution modifiers:**
- +0.5 (round up): Founder-led with long tenure and no secondary selling
- -0.5 (round down): Recent CFO departure + no replacement named

---

## DIMENSION 5: RELATIVE VALUATION

*EV/NTM Revenue adjusted for growth rate. Score 5 = best value in the peer group.*
*This is a RELATIVE score — it only tells you who is cheap vs. expensive vs. peers.*
*It does not tell you if the whole group is cheap or expensive vs. the market.*

| Score | What It Looks Like |
|-------|--------------------|
| **5** | Cheapest in the peer group on growth-adjusted basis. PEG-style: EV/NTM Rev divided by NTM growth rate is at the low end of the peer range AND there is a clear reason the discount may close (catalyst, narrative catch-up). |
| **4** | Below peer median on growth-adjusted EV/Rev. Modest discount to where it should trade given fundamentals. |
| **3** | Trading at or near peer median on growth-adjusted basis. Fair value relative to the group. |
| **2** | Premium to peer median that requires continued perfect execution to justify. Any deceleration would compress the multiple materially. |
| **1** | Most expensive in the group on growth-adjusted basis with the weakest justification for the premium. Priced for perfection with limited margin of error. |

**Practical calculation:**
```
Growth-Adjusted Multiple = EV / NTM Revenue ÷ NTM Revenue Growth %

Example:
  Company A: EV/NTM Rev = 12x, NTM growth = 30% → ratio = 0.40
  Company B: EV/NTM Rev = 8x,  NTM growth = 15% → ratio = 0.53
  Company A is cheaper on a growth-adjusted basis despite higher absolute multiple
```

**Important notes:**
- If a company is mid-transition (like PANW), use ARR growth not total revenue growth
- If NTM estimates appear stale (>60 days since last revision), flag and use with caution
- Do not let a low absolute multiple override this score if growth is also low

---

## PASS/NO PASS THRESHOLDS

| Decision | Criteria |
|----------|----------|
| **PASS TO VALUATION** | Total score ≥ 18/25 **OR** exceptional moat score (5) with total ≥ 15 |
| **WATCHLIST** | Total score 12–17 **with a named catalyst** — not "improving fundamentals" |
| **NO** | Total score < 12 **OR** any single dimension scores 1 |

**The Watchlist catalyst rule is hard.** Examples of acceptable catalysts:
- ✅ "Next earnings (DATE) will clarify NRR trajectory after disclosed methodology change"
- ✅ "Management Day (DATE) expected to provide platformization ARR breakdown"
- ✅ "FedRAMP High authorization pending — if granted, opens $XB federal market"
- ❌ "If growth reaccelerates" — not a catalyst, a hope
- ❌ "Valuation is becoming interesting" — not a catalyst
- ❌ "Management has guided conservatively" — too vague

---

*Last updated: [DATE]*
