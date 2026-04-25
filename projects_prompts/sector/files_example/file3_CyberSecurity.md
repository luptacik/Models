# BENCHMARK REFERENCE SHEET
*Project knowledge file for Sector Analysis Project (A1 prompt)*
*Use to calibrate relative valuation scores and contextualise financial metrics.*
*Update after each earnings season. Benchmarks drift — stale data is worse than no data.*

---

## HOW TO USE THIS FILE

This file provides **anchor ranges** — not precise targets. They tell A1 what "normal" looks like
for different company stages so that scores reflect genuine outliers, not ignorance of base rates.

When a metric falls outside the ranges below, flag it explicitly and explain why
before assigning a score. Do not silently score an outlier as a 3.

---

## SECTION 1: SAAS / CLOUD METRICS BY STAGE

### Net Revenue Retention (NRR / DBNRR)

| Stage | Weak | Acceptable | Strong | Exceptional |
|-------|------|------------|--------|-------------|
| High-Growth SaaS | <105% | 105–115% | 115–125% | >125% |
| Growth SaaS | <103% | 103–110% | 110–120% | >120% |
| Mature SaaS | <100% | 100–107% | 107–115% | >115% |

**Cybersecurity-specific context:**
- Endpoint/XDR leaders (CRWD): historically 120–130%; below 118% is a deceleration signal
- SASE (ZS): historically 125–130%; this is the bar for the sub-sector
- Network/Firewall (PANW, FTNT): 110–120% as transition matures; legacy product NRR is less meaningful
- Identity (CYBR, OKTA): 115–125% typical for enterprise IAM when expansion motion is healthy

---

### Rule of 40 (ARR/Revenue Growth % + FCF Margin %)

| Classification | Rule of 40 Score |
|---------------|-----------------|
| Elite (top-tier valuation justified) | >50 |
| Strong | 35–50 |
| Acceptable | 25–35 |
| Concerning | 15–25 |
| Structurally challenged | <15 |

**Context:** High-growth companies often sacrifice FCF early. A company at 40% ARR growth + -5% FCF = Rule of 35 — still strong. The question is trajectory: is FCF margin expanding 300–500bps per year as growth scales?

---

### Gross Margin by Business Model

| Business Model | Typical Range | Best-in-Class |
|----------------|--------------|---------------|
| Pure SaaS / ARR | 72–80% | >80% |
| Mixed (transitioning) | 60–75% | >75% |
| Hardware + software | 55–70% | >70% |
| Services-heavy | 45–65% | >65% |

**Below-floor flags:**
- Pure SaaS below 68%: investigate cost structure — cloud COGS? Professional services drag?
- Hardware/mixed below 58%: product margin compression, likely competitive or supply chain

---

### ARR Growth Rate Context

| Stage | Typical ARR Growth | Top Quartile | Concern Level |
|-------|-------------------|--------------|---------------|
| High-Growth | 25–45% | >40% | Decel to <20% |
| Growth | 15–25% | >25% | Decel to <12% |
| Mature | 5–15% | >15% | Flat or declining |

---

### FCF Margin Trajectory (what "good" looks like over time)

| ARR Scale | Expected FCF Margin |
|-----------|---------------------|
| <$500M ARR | -10% to +5% (investing mode acceptable) |
| $500M–$1B ARR | 0–15% (must show path) |
| $1B–$3B ARR | 10–20% (scaling evident) |
| >$3B ARR | 15–30%+ (mature model) |

---

### SBC (Stock-Based Compensation) as % of Revenue — Dilution Watch

| Rating | SBC / Revenue |
|--------|--------------|
| Clean | <8% |
| Acceptable | 8–12% |
| Elevated — monitor | 12–18% |
| Alarm — dilution concern | >18% |

---

## SECTION 2: VALUATION MULTIPLES — CYBERSECURITY

### EV / NTM Revenue by Growth Rate
*(Public market comps — update each quarter; ranges compress/expand with risk appetite)*

| NTM Revenue Growth | Low End | Median | High End |
|-------------------|---------|--------|----------|
| >35% | 10x | 14–16x | 20x+ |
| 25–35% | 7x | 10–13x | 17x |
| 15–25% | 4x | 7–9x | 13x |
| 5–15% | 2x | 4–6x | 8x |
| <5% | 1.5x | 2–4x | 5x |

**Market environment note:** These ranges assume a neutral rate environment.
- In a risk-off / high-rate environment: compress all ranges by 20–30%
- In a risk-on / rate-cutting environment: expand high ends by 20–30%
- Current environment: [UPDATE EACH CYCLE — note rate regime]

---

### Growth-Adjusted Valuation (PEG-style for SaaS)

```
Metric: EV/NTM Rev ÷ NTM Revenue Growth Rate (expressed as a whole number)

Cybersecurity benchmarks (current cycle):
  Cheap:        < 0.30
  Fair value:   0.30 – 0.50
  Premium:      0.50 – 0.70
  Expensive:    > 0.70
```

**Example calibration (illustrative, not current):**
- CRWD at 15x NTM Rev, 30% growth = 0.50 ratio → Fair to slightly premium
- FTNT at 6x NTM Rev, 12% growth = 0.50 ratio → Same growth-adjusted value as CRWD

---

## SECTION 3: M&A COMPARABLES — CYBERSECURITY

### Selected Precedent Transactions

| Target | Acquiror | Date | EV | EV/ARR | Notes |
|--------|---------|------|----|--------|-------|
| Splunk | Cisco | Oct 2023 | $28B | ~7x ARR | Largest recent; SIEM/analytics |
| Symantec Enterprise | Broadcom | Nov 2019 | $10.7B | ~4x ARR | Mature endpoint; strategic |
| Carbon Black | VMware | Aug 2019 | $2.1B | ~10x ARR | Endpoint/XDR |
| Demisto | Palo Alto | Feb 2019 | $560M | ~15x ARR | SOAR; high-growth sub-sector premium |
| Phantom | Splunk | 2018 | $350M | ~12x ARR | SOAR |

**Takeaway from precedents:**
- High-growth targets (>30% ARR growth): 10–15x ARR
- Growth-stage targets (15–30%): 6–10x ARR
- Mature/strategic targets (<15% growth): 3–6x ARR
- Strategic scarcity premium (sole platform in a sub-sector): add 2–4x

---

### Likely Acquirors in Current Cycle

| Acquiror | Financial Capacity | Strategic Gap They're Filling | Likely Target Profile |
|----------|-------------------|-------------------------------|----------------------|
| PANW | Large M&A history | Identity, cloud-native CNAPP gaps | CYBR, Wiz-like assets |
| CRWD | Mid-size deals preferred | SOC automation, data security | Tuck-in acquisitions |
| CSCO | Very large capacity post-Splunk | Needs to digest; limited near-term | Pause likely |
| MSFT | Unlimited | Fills gaps opportunistically | Anything strategic |
| PE / Private | Dry powder elevated | Mature, FCF-positive assets | CHKP, TENB, QLYS profile |

---

## SECTION 4: SECTOR-SPECIFIC MODELING CONSIDERATIONS

### When Building Valuation Models (feeds Valuation Project)

**Revenue recognition nuances:**
- PANW: Total revenue is misleading mid-transition. Model on NGFW ARR + cloud ARR; cross-check against RPO
- FTNT: Hardware revenue creates lumpiness; use subscription rev trend, not total rev YoY
- NET: Security revenue (~55% of total) growing faster than CDN; model the segments separately if possible
- OKTA: Auth0 integration created a revenue recognition reset; multi-year comps require adjustment

**Margin expansion timing:**
- XDR/endpoint leaders typically reach 20%+ FCF margins at ~$3–4B ARR scale
- SASE (ZS model) reaches 20%+ FCF at similar scale; cloud delivery cost advantages compound
- Platform-in-transition players (PANW) show temporarily compressed margins during the bundle push,
  then step-change improvement as subscription mix hits ~70%+

**Key leading indicators (model these, not lagging revenue):**
1. RPO growth > ARR growth = pipeline building → bullish
2. RPO growth < ARR growth = pipeline thinning → investigate
3. Large deal count (>$1M TCV) — reported by CRWD, ZS, PANW; rising count = enterprise penetration
4. Module attach rate / platform customers — CRWD reports customers with 5+ / 6+ modules;
   increasing attach = NRR durability signal

**Working capital dynamics:**
- Cybersecurity SaaS is typically cash-collection-positive (annual/multi-year prepaid contracts)
- Deferred revenue growing > ARR growth = billings outpacing revenue recognition → quality signal
- Deferred revenue flat/declining while ARR grows = billing terms shortening → mild concern

---

## SECTION 5: MACRO SENSITIVITY

### How Cybersecurity Spend Behaves in Different Environments

| Environment | Historical Pattern | Key Dynamic |
|-------------|-------------------|-------------|
| Recession / IT budget cuts | Sticky; among last to cut | Security is non-discretionary for compliance-regulated industries |
| Interest rate hikes (2022–23) | Multiple compression, spending held | FCF became the new religion; growth-only stories punished |
| AI acceleration (2024+) | Spend increasing; attack surface expanding | AI threat vectors creating new mandatory spend categories |
| Geopolitical escalation | Accelerant for government + critical infra spending | Nation-state threats drive CISA mandates and FedRAMP urgency |

**Budget priority within IT:**
1. Security (near-first priority — breach cost >> security budget)
2. Cloud infrastructure
3. Collaboration / productivity
4. Everything else

---

*Last updated: [DATE — update quarterly]*
*Market multiple ranges particularly time-sensitive — verify before scoring valuation dimension*
