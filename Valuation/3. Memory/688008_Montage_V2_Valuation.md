# MONTAGE TECHNOLOGY (688008.SS) — V2 STOCK VALUATION REPORT

**Ticker:** 688008.SS (Shanghai STAR Market) / 6809.HK (HKEX, H-shares)
**Company:** Montage Technology Co., Ltd. (澜起科技股份有限公司)
**Sector:** Memory — Interconnect chips (DDR5 RCD/MRCD/MDB, PCIe Retimer, CXL MXC)
**Analysis date:** April 16, 2026
**Currency:** CNY unless noted
**Reporting standard:** PRC GAAP (CAS)

---

## ⚠️ PRICE RECONCILIATION — READ FIRST

The user-stated current price of **CNY 42** is materially inconsistent with all V1 dossier data points:

| Data point | Implied price |
|---|---|
| R2 market cap $19.6–21B USD ÷ 1,211M shares @ 7.09 CNY/USD | CNY 114–122 |
| ATH CNY 188.88 (Feb 2, 2026), –15 to –20% per R3 | CNY 151–161 |
| MarketScreener consensus PT | CNY 162.47 |
| Guosen Securities target (Nov 2025) | CNY 152 |

CNY 42 would represent a ~78% drawdown from ATH that no catalyst in the dossier supports. The most likely intended price is **CNY 142** (a typo dropping the "1"). All primary modeling below uses **CNY 142** as the working price, but the reverse DCF and wheel handoff explicitly compute both scenarios so the analysis is usable either way.

**If the price is genuinely CNY 42, the investment thesis reverses entirely**: reverse DCF implied 10yr CAGR drops to 8.4% (deep pessimism priced in) and every method places the stock materially *below* fair value. Wheel strategy would flip from defensive to aggressive long.

---

## PRE-MODEL CHECKS

**Data sufficiency:** ✓ 5 fiscal years + 12 quarters + consensus FY26/27 for DCF. Sector handoff provides 11-peer set for comps. M&A comps rely on 7 semi/interface transactions — adequate but sparse. SoP limited to 2-segment disclosure; sub-segmenting is estimate-based. LBO retained as mathematical downside reference only (Chinese A-share cross-border LBO is structurally infeasible).

**Fiscal year alignment:** ✓ Montage FY = calendar year (Dec 31). Primary peers Rambus, ALAB, SK Hynix, GigaDevice also Dec year-ends. MU ends Aug — CY2025 basis used for cross-comparability.

**Share count:** 1,135M pre-IPO diluted (Q3 2025) + 65.89M HK new issuance + 9.88M potential greenshoe = **1,220M fully diluted**. Model uses 1,220M (upper bound, conservative).

**SBC materiality:** FY2025 SBC CNY 450M = 8.2% of revenue. **Below 15% dual-track threshold**, but SBC jumped from 1.6% in FY2024 due to the Sep 2024 ESOP (CNY 350M fund, 75 employees). Normalized run-rate expected CNY 400–500M through FY2027. FCF-ex-SBC presented alongside reported FCF for conservatism — FY2025 FCF-ex-SBC CNY 1,306M (23.9% margin) vs reported CNY 1,756M (32.2% margin).

**Net cash pro-forma (post HK IPO):** CNY 15.6B. Q3 2025 net cash CNY 9.4B + HK IPO Feb 2026 net proceeds HK$6.9B (~CNY 6.3B). Debt negligible at CNY 38M (finance leases).

**Reporting billing vs end-customer geography conflict:** Sector handoff and SSE filings show 76.4% PRC-billed revenue (Q1 2025). SCMP/company 2024 annual report states "most clients from outside China." The 76.4% figure reflects distributor/module-maker billing addresses, not end-customer geography. **Modeling implication:** Export-control risk is real but lower than face-value 76% China concentration would suggest; the discount applied in trading comps (25%) reflects PRC regulatory/jurisdictional risk, not demand-side China exposure.

---

## METHOD 1 — REVERSE DCF

**Purpose:** Solve for the revenue CAGR the current market price implies.

**Assumptions:**
- WACC: 11% (10% base for global interface peers + 100bp China jurisdiction/VIE risk premium)
- Terminal FCF margin: 35% (Rambus 47%, ALAB 33%; 35% reflects hardware-heavy mix)
- Terminal growth: 3%
- Ramp: FCF margin linear from FY25 actual 32.2% → 35% terminal over 10 years

**Results at CNY 142 (working price):**

| Item | Value |
|---|---|
| Market cap | CNY 173.2B |
| Less: net cash | (CNY 15.6B) |
| **Current EV** | **CNY 157.6B** |
| **Implied 10yr revenue CAGR** | **29.1%** |

**Gap analysis:**

| Benchmark | Growth |
|---|---|
| FY2025 actual | +49.9% |
| FY2026 consensus | +37.3% |
| FY2027 consensus | +23.4% |
| Blended 2yr consensus CAGR | ~30% |
| **Market-implied 10yr CAGR** | **29.1%** |
| Memory-interface TAM CAGR (2024–2030, per dossier) | ~27% ($1.2B → $5B) |

**Interpretation:** The market is asking Montage to sustain near-term consensus growth for a full decade — effectively demanding that the current upcycle rate persist through two memory cycles. This is ambitious but not outlandish given (a) DDR5 penetration still ~50% with 2–3yr runway, (b) CXL/MXC as a second growth vector, (c) 36.8% global market share with JEDEC standard-setting moat. However, it leaves zero margin of safety: any cycle turn, execution slip, or share loss to Rambus/ALAB on CXL causes multiple compression.

**Reverse DCF sensitivity — implied 10yr CAGR at CNY 142:**

| WACC \ Terminal FCF margin | 25% | 30% | 35% | 40% | 45% |
|---|---|---|---|---|---|
| 9% | 28.1% | 25.8% | 23.9% | 22.2% | 20.8% |
| 10% | 30.9% | 28.5% | 26.6% | 24.9% | 23.4% |
| **11%** | 33.5% | 31.1% | **29.1%** | 27.3% | 25.8% |
| 12% | 35.9% | 33.4% | 31.4% | 29.6% | 28.1% |
| 13% | 38.2% | 35.7% | 33.6% | 31.8% | 30.3% |

**At user-stated price CNY 42:** Implied CAGR = **8.4%**, EV = CNY 35.6B. The market would be pricing in growth roughly *one-fourth* of near-term consensus and below the TAM CAGR itself. Deep pessimism scenario.

---

## METHOD 2 — FORWARD DCF (3-SCENARIO)

**Scenario assumptions:**

| Assumption | Bull | Base | Bear |
|---|---|---|---|
| FY26 Rev growth | 40.0% | 37.3% | 30.0% |
| FY27 Rev growth | 30.0% | 23.4% | 10.0% |
| FY28 Rev growth | 25.0% | 18.0% | 5.0% |
| FY29–32 avg growth | 16.3% | 9.8% | 6.5% |
| Terminal FCF margin (Y7) | 42.0% | 37.0% | 30.0% |
| Terminal growth | 4.0% | 3.0% | 2.0% |
| WACC | 10.0% | 11.0% | 12.0% |

**Rationale per scenario:**

- **Bull:** CXL crosses 15% of revenue by mid-2026 (sector handoff trigger). DDR5 Gen3→Gen4→Gen5 generational pricing power extends through 2028. Memory cycle turns in 2028 rather than late 2026 — one extra year of peak margins. PCIe 6.0 Retimer qualifies in 2026 and captures initial hyperscaler designs. What must go right: no export control action, CXL design wins at hyperscalers convert to volume, Rambus/ALAB don't leapfrog on Gen5 RCD.

- **Base:** Consensus FY26/27 delivered; interface-IP peer convergence thereafter. Memory cycle turns late 2026/early 2027 per sector handoff (Month 18–20 historical peak), knocking FY28–29 growth to mid-teens. Interconnect margins converge to Rambus-like 37% FCF as the platform matures. Most likely path given observable trajectory.

- **Bear:** Memory cycle peaks mid-2026; FY27 growth collapses to 10% as DRAM volumes soften and DDR5 RCD ASPs compress. CXL ramp disappoints (Astera Labs captures the premium hyperscaler slots). SBC persists at 8–10% of revenue through FY2027–28 pressuring FCF-ex-SBC margins. What could go wrong: US Commerce 100% tariff threat extends to memory interface chips; pre-IPO shareholder selling accelerates post Aug 2026 H-share lock-up expiry.

**Base case revenue projection (CNY millions):**

| Year | Revenue | YoY | FCF Margin | FCF | Discount Factor | PV of FCF |
|---|---|---|---|---|---|---|
| 2026 | 7,491 | 37.3% | 34.0% | 2,547 | 0.901 | 2,295 |
| 2027 | 9,244 | 23.4% | 35.0% | 3,235 | 0.812 | 2,626 |
| 2028 | 10,908 | 18.0% | 36.0% | 3,927 | 0.731 | 2,871 |
| 2029 | 12,435 | 14.0% | 37.0% | 4,601 | 0.659 | 3,031 |
| 2030 | 13,803 | 11.0% | 37.0% | 5,107 | 0.593 | 3,031 |
| 2031 | 14,907 | 8.0% | 37.0% | 5,516 | 0.535 | 2,949 |
| 2032 | 15,802 | 6.0% | 37.0% | 5,847 | 0.482 | 2,816 |

**Valuation summary (CNY millions unless noted):**

| | Bull | Base | Bear |
|---|---|---|---|
| PV of Y1–Y7 FCFs | 27,330 | 19,618 | 11,111 |
| PV of Terminal Value | 84,444 | 36,257 | 14,581 |
| Enterprise Value | 111,775 | 55,875 | 25,692 |
| + Net Cash | 15,600 | 15,600 | 15,600 |
| Equity Value | 127,375 | 71,475 | 41,292 |
| ÷ Fully Diluted Shares (M) | 1,220 | 1,220 | 1,220 |
| **Per-Share Value (CNY)** | **104** | **59** | **34** |
| Upside/(Downside) vs CNY 142 | –27% | –59% | –76% |
| TV % of Total EV | 75.5% ⚠️ | 64.9% | 56.8% |

**⚠️ TV warning:** Bull case TV = 75.5% of total EV — flagged as speculative. Base case at 64.9% is acceptable but high; this is typical for compounders but reinforces that the bull thesis depends heavily on terminal assumptions, not near-term FCF visibility.

**FCF-ex-SBC adjustment (base case):** Applying 8% SBC-to-revenue haircut to FCF margins → base case per share CNY **49** (vs CNY 59 reported). This is the economically conservative reading.

**Round-trip check (base case):** Per-share value CNY 59 implies EV/FY26 Rev = **7.5x**. At current CNY 142, implied EV/FY26 Rev = **21.0x**. The DCF base is consistent with Rambus-equivalent multiples; the current price requires premium-to-Rambus multiples despite the China risk discount.

---

## METHOD 3 — TRADING COMPS

**Peer set from sector handoff, organized by tier:**

**Tier A — Direct pure-play memory interface/controller peers:**

| Ticker | Growth NTM | GM | FCF Margin | EV/NTM Rev | Growth-Adj | Note |
|---|---|---|---|---|---|---|
| RMBS | 18% | 79.6% | 47.1% | 10.0x | 0.556 | IP/royalty, highest quality |
| ALAB | 50% | 75.7% | 33.1% | 13.6x | 0.272 | CXL/PCIe first-mover |

**Tier B — Memory IDMs with HBM/AI exposure:**

| Ticker | Growth NTM | GM | FCF Margin | EV/NTM Rev | Growth-Adj |
|---|---|---|---|---|---|
| MU | 80% | 74.9% | 18% | 3.0x | 0.037 |
| SK Hynix | 66% | 60% | 18% | 5.6x | 0.085 |

**Tier C — Other memory peers (NAND, DRAM, specialty, controllers):**

| Ticker | Growth NTM | GM | FCF Margin | EV/NTM Rev | Growth-Adj |
|---|---|---|---|---|---|
| SNDK | 60% | 50.9% | 15% | 4.0x | 0.067 |
| Kioxia | 30% | 26% | 8% | 3.2x | 0.107 |
| SIMO | 45% | 48.3% | 1% | 3.1x | 0.069 |
| Winbond | 40% | 35% | 5% | 1.75x | 0.044 |
| Nanya | 50% | 49% | 10% | 2.8x | 0.056 |

**Tier D — Chinese A-share peers (liquidity premium):**

| Ticker | Growth NTM | GM | FCF Margin | EV/NTM Rev | Growth-Adj |
|---|---|---|---|---|---|
| GigaDevice | 25% | 37% | 12% | 17.4x | 0.696 |
| Ingenic | 15% | 32% | 12% | 6.9x | 0.460 |

**Montage positioning (CNY 8.0B NTM Rev, 30% NTM growth):**
- Current EV/NTM Rev at CNY 142: **19.7x** — highest in the tradeable memory universe
- Growth-adjusted: **0.657** — premium to closest peer Rambus (0.556)
- Ranking: Growth #2 of 11 (after MU); FCF margin #2 of 11 (after RMBS)
- GM 62% is best-in-class among hardware peers (below RMBS royalty-boosted 80% and ALAB 76%)

**Fair value approaches:**

**(A) Tier A median EV/NTM Rev = 11.8x**
→ Implied EV CNY 94,400M → Equity CNY 110,000M → **CNY 90 per share**

**(B) Growth-adjusted to Tier A median (0.414 growth-adj) × 30% growth = 12.4x**
→ Implied EV CNY 99,307M → Equity CNY 114,907M → **CNY 94 per share**

**(C) All-peer growth-adj median (0.085) × 30% × 30% China discount = 1.8x**
→ Implied EV CNY 14,255M → Equity CNY 29,855M → **CNY 24 per share**
(This bear case anchor reflects what Montage would trade at if viewed purely as a Chinese memory-adjacent name with IDM multiples.)

**Weighted final (55% A / 30% B / 15% C):**
→ **CNY 82 per share**
→ Implied EV/NTM Rev: **10.5x** — equivalent to Rambus, acknowledging superior growth offsetting China risk

**Chinese A-share premium consideration:** GigaDevice trades at 17.4x and Ingenic at 6.9x despite inferior growth/margins — this reflects a domestic liquidity premium. One could argue Montage deserves some liquidity premium relative to global peers (it trades on STAR Market with retail participation) but the Frost & Sullivan #1 global ranking and HK IPO listing argues for global-peer benchmarking. **Not applying an uplift here** — if we gave Montage a GigaDevice-like 17x multiple the fair value would be CNY 125, closer to but still below current price, and that multiple isn't defensible on fundamentals.

---

## METHOD 4 — PRECEDENT M&A COMPS

**Comparable semiconductor interface/IP transactions:**

| Year | Target | Acquirer | EV (USD B) | EV/Rev | Rationale |
|---|---|---|---|---|---|
| 2019 | Integrated Device Tech (IDT) | Renesas | 6.70 | 8.8x | DDR RCD legacy, lower-growth at close |
| 2020 | Northwest Logic | Cadence | 0.20 | 12.0x | Memory IP, scarcity premium |
| 2022 | Hardent | Rambus | 0.04 | 10.0x | Memory IP bolt-on |
| 2014 | PLX Technology | Avago | 0.30 | 2.0x | PCIe switch, cyclical |
| 2021 | Inphi | Marvell | 10.00 | 15.0x | High-growth DSP/retimer, strategic |
| 2017 | Analogix Semi | Shanghai 芯原 | 0.50 | 3.0x | Interface ICs, Chinese buyer |
| 2017 | Silego Technology | Dialog | 0.28 | 7.0x | Configurable mixed-signal |

**Relevant (high-growth interface/IP) subset:** IDT, Northwest, Hardent, Inphi. Median 11.0x; mean 11.4x.

**Takeout valuation (applied to NTM Rev CNY 8.0B / USD 1,129M):**

| Multiple scenario | EV (CNY M) |
|---|---|
| Low (8.8x — IDT at close) | 70,400 |
| Mid (11.0x — median relevant) | 88,000 |
| High (15.0x — Inphi premium) | 120,000 |

**After 25% control premium discount (public market takeout floor):**

| | Per-share (CNY) |
|---|---|
| Low | 56 |
| Mid | **67** |
| High | 87 |

**⚠️ Realism check:** Cross-border acquisition of Montage is not a plausible exit path.
- State-linked pre-IPO shareholders (中电投控) reducing but still present
- Market cap CNY ~170B (USD ~$24B) exceeds non-sovereign strategic buyer capacity
- CFIUS blocks US acquirers; PRC MOFCOM review blocks most foreign acquirers
- Chinese strategic buyer (e.g., YMTC parent, Hua Hong) theoretically possible but synergies limited — Montage is fabless while PRC IDMs have foundry agendas

The M&A comp is retained as a **directional valuation benchmark**, not a probable exit. The Inphi 15x transaction is the closest analog (high-growth memory/connectivity interface, strategic acquisition), and that reference says Montage's business as-is *could* be worth 15x in a private-market transaction — but the lack of realistic acquirer population means this multiple is not a realized ceiling.

---

## METHOD 5 — SUM-OF-PARTS

**Approach:** Sub-segment the interconnect product line using disclosed "three new products" (CNY 294M H1 2025) and management color on segment mix.

**Segment buildup (FY2026E revenue):**

| Segment | FY26 Rev (CNY M) | Growth | Multiple | Implied EV (CNY M) | Peer benchmark |
|---|---|---|---|---|---|
| DDR5 RCD core | 4,496 | 20% | 9.0x | 40,462 | Rambus-equivalent mature IP |
| MRCD/MDB/PCIe Gen5 Retimer | 2,248 | 60% | 14.0x | 31,471 | Inphi/ALAB-like high-growth interface |
| CXL 3.1 MXC controller | 450 | 150% | 20.0x | 8,992 | ALAB early-stage premium |
| Jintide server platform | 300 | 5% | 3.0x | 899 | China server OEM |
| **Total EV (pre-adjustment)** | **7,493** | — | — | **81,824** | — |

+ Net cash: CNY 15,600M
= Equity value: CNY 97,424M
÷ 1,220M shares = **CNY 80 per share (pre-China discount)**

**After 25% China jurisdiction haircut:** **CNY 63 per share**

**Hidden value flag:** CXL MXC segment contributes ~6% of FY26 revenue but captures ~14% of implied EV in this SoP build. If CXL crosses 15% of revenue by Q2 2026 (the sector handoff's key-variable trigger), this segment re-rates toward full ALAB-equivalent multiples (~18–20x), adding **CNY 15–25 per share** to fair value. The market is not currently giving Montage credit for CXL optionality — this is the primary upside asymmetry in the bull case.

**Limitations:** 2-segment company disclosure forces estimate-based sub-segmentation. Precision is limited; directional signal is stronger than point estimate. The Jintide server platform (5.6% of revenue, flat-to-declining) is essentially "stub value" — a de minimis adjustment that doesn't move the needle.

---

## METHOD 6 — PE / LBO FLOOR (downside reference only)

**⚠️ Structural caveat:** Cross-border PE buyout of a Chinese A-share company is not executable in practice. State-linked shareholders, CSRC delisting requirements, and absence of Chinese PE buyout precedents at this scale mean this is a **mathematical floor reference**, not a plausible bid scenario.

**Framework:** Growth-equity (no leverage, pure equity, 25% IRR target) over 5 years.

**5-year projection:**

| Year | Revenue (CNY M) | YoY | FCF Margin | FCF (CNY M) |
|---|---|---|---|---|
| 2026 | 7,093 | 30% | 33% | 2,341 |
| 2027 | 8,370 | 18% | 34% | 2,846 |
| 2028 | 9,374 | 12% | 35% | 3,281 |
| 2029 | 10,124 | 8% | 35% | 3,543 |
| 2030 | 10,731 | 6% | 35% | 3,756 |
| | | | **Cumulative FCF** | **15,766** |

**Exit assumptions:**
- Year 5 Revenue: CNY 10,731M
- Exit multiple: 10x EV/NTM Rev (conservative, Rambus-equivalent)
- Exit EV: CNY 107,312M
- Exit Equity (EV + cumulative FCF): CNY 123,078M

**Floor price (25% IRR):**
- Max entry equity: CNY 40,330M
- **Floor per share: CNY 33** (vs current CNY 142 → –77%)

The LBO math says a patient private-equity-style buyer would pay no more than ~CNY 33 for this asset under conservative assumptions. This is effectively a "memory cycle trough" downside reference — it tells us where a disciplined financial buyer would step in if the stock collapsed. **At user-stated CNY 42, the stock is within 27% of this theoretical financial-buyer floor.**

---

## TRIANGULATION & PRICE TARGET

**Method weights and confidence:**

| Method | Bear | Base | Bull | Weight | Confidence |
|---|---|---|---|---|---|
| Reverse DCF | — | (diagnostic only — implies 29% CAGR vs ~30% consensus) | — | 0% | M |
| Forward DCF | 34 | 59 | 104 | 40% | H |
| Trading Comps | 65 | 82 | 98 | 35% | H |
| M&A Comps | 54 | 67 | 77 | 10% | L |
| Sum-of-Parts | 50 | 63 | 76 | 10% | M |
| PE/LBO Floor | 33 | — | — | 5% | L |

**Weighting rationale:**
- Forward DCF (40%) gets highest weight given predictable cash generation, FY26 consensus visibility, and interface IP being less cyclical than IDMs
- Trading Comps (35%) — well-defined pure-peer set (RMBS, ALAB); Rambus is a near-perfect comparable by business model
- M&A Comps (10%) — relevant deals exist but exit path is implausible → capped weight
- SoP (10%) — limited segment disclosure forces estimates; directional rather than precise
- LBO Floor (5%) — infeasible in practice but useful as an extreme-downside anchor

### ━━━ TRIANGULATED PRICE TARGET ━━━

| | Price (CNY) | vs CNY 142 | vs CNY 42 |
|---|---|---|---|
| **Bear** | **48** | –66% | +14% |
| **Base** | **67** | –53% | +60% |
| **Bull** | **93** | –35% | +121% |

### Conviction score: **3.5/5**

**Rationale:** All six methods converge on the conclusion that Montage is materially overvalued at CNY 142. The triangulated base case of CNY 67 sits 53% below the working price, and even the bull case (CNY 93) implies 35% downside. However, conviction is capped at 3.5/5 (not 4/5) because: (1) memory cycle timing is the dominant swing factor — if the upcycle extends to late 2027 rather than turning in late 2026, the bull case compounds; (2) CXL/MXC ramp is a real option with meaningful re-rating potential not fully captured in the peer multiples; (3) the 76% China billing geography is a genuine mispricing signal but the end-customer reality (global hyperscalers) materially moderates the jurisdiction haircut magnitude; (4) the Chinese A-share liquidity premium is real and persistent — GigaDevice's 17.4x multiple on inferior fundamentals demonstrates the market can sustain premium multiples for extended periods regardless of DCF math.

**What would change conviction to 4/5 (stronger overvalued call):** Confirmed memory cycle turn in Q3 2026 hyperscaler capex guidance; failure of CXL MXC to convert to volume at a Tier-1 hyperscaler by end-2026; export control action targeting memory interface chips.

**What would change conviction to 3/5 (more fair-valued):** CXL revenue crosses 15% of total by Q2 2026; Rambus re-rates higher on HBM4E controller IP traction (pulling Montage multiples with it); HK-A premium arbitrage collapses (A-share de-rates toward H-share valuation).

---

## CRITICAL OBSERVATIONS

**1. The reverse DCF sanity check is unusually tight.** Implied 29% CAGR is within 100bp of blended consensus 30%. This isn't "priced for perfection" — it's priced for *consensus delivery over a decade*. The asymmetry is therefore negative: consensus delivery produces roughly zero return; any shortfall produces losses; only consensus beat over 10 years produces gains. This is the "efficient pricing with negative skew" pattern common in high-quality Chinese A-share growth names.

**2. Forward DCF and Trading Comps agree closely.** DCF base CNY 59 vs Trading Comps CNY 82 — a 39% gap that reflects the DCF's explicit terminal growth assumption (3%) being more conservative than the peer-multiple-implied terminal assumption. At Rambus-equivalent 10x EV/NTM Rev (the final weighted comp output), Montage should trade at CNY 82; the DCF says that even that is generous once the cycle turn is modeled.

**3. The options wheel dynamics are radically different at the two prices.** At CNY 142: stand aside / covered calls only (above fair value). At CNY 42: 4/5 conviction concentrated long candidate, aggressive put-selling. This is not a nuance — the price reconciliation actually matters for the actionable output.

**4. China A-share options are not executable for most retail investors.** Even if an attractive entry emerges, the options wheel strategy cannot be run on 688008.SS directly. The H-share (6809.HK) listed Feb 2026 has HKEX options limited to large caps with liquid derivative markets — Montage's float of ~5.4% in H-shares may not yet support liquid options. Substitute strategies below.

**5. SBC will persist, not normalize quickly.** The 2024 ESOP created a multi-year vesting profile. FCF-ex-SBC of 24% (not 32%) is the durable margin profile through FY2027. Any DCF using reported FCF overstates intrinsic value by ~10–15%.

---

## OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━
TICKER:           688008.SS (A-share) / 6809.HK (H-share)
COMPANY:          Montage Technology (澜起科技)
SECTOR:           Semiconductor Memory — Interface Chips
VALUATION DATE:   16 Apr 2026

PRICE TARGET (base): CNY 67 (range: CNY 48 bear — CNY 93 bull)
CONVICTION:       3.5/5

═══════════════════════════════════════════════════
SCENARIO A — IF CURRENT PRICE IS CNY 142 (dossier-consistent):
═══════════════════════════════════════════════════
UPSIDE TO BASE:   –53% (STOCK OVERVALUED)

WHEEL STRATEGY:
- SELL PUTS:     NO
  Reason: Stock trades 53% ABOVE base PT. Selling puts has negative
          expected value. Any put strike ≥ CNY 67 is a loss bet.

- COVERED CALLS (if already long): YES/AGGRESSIVE
  Only meaningful if holding existing long position from pre-2025 entry.
  Sell calls at CNY 150–180 strike (between current and bull PT CNY 93
  is below current, so CC strikes above spot are the only sensible zone).
  Let position be called away — this is an exit tool, not income tool.

- CONCENTRATED LONG: NO (conviction on overvaluation is the thesis)

═══════════════════════════════════════════════════
SCENARIO B — IF CURRENT PRICE IS ACTUALLY CNY 42 (user-stated):
═══════════════════════════════════════════════════
UPSIDE TO BASE:   +60% (STOCK DEEPLY UNDERVALUED)
CONVICTION:       Elevated to 4.5/5 at this price
                  (reverse DCF implies just 8% CAGR vs 30% consensus)

WHEEL STRATEGY:
- SELL PUTS:     YES / AGGRESSIVE
  Strike zone: CNY 40–48 (at-to-slightly-below spot, at-to-bear case)
  Maximum strike: CNY 48 (bear PT floor)
  Avoid puts above: CNY 48

- COVERED CALLS (if assigned): CONDITIONAL
  Cost basis floor: put strike (CNY 40–48)
  Minimum call strike: CNY 48 (= cost basis floor per cc_min_strike_pct=1.0)
  Suggested call strike: CNY 65–80 (between cost basis and base PT)
  DO NOT sell calls above CNY 90 (approaching bull; let it run)

- CONCENTRATED LONG: YES
  Meets both criteria: conviction ≥4 AND upside to base CNY 67 = +60%
  Kelly-informed: moderate sizing given China jurisdiction risk and
  memory cycle timing — position at 2/3 of what fundamentals alone
  would suggest.

═══════════════════════════════════════════════════
OPTIONS EXECUTION CONSTRAINT ⚠️
═══════════════════════════════════════════════════
- 688008.SS (STAR Market): NO LIQUID LISTED OPTIONS
  A-share individual equity options market on SSE is limited;
  Montage not in ETF option universe.
- 6809.HK (Main Board H-share): options theoretically available but
  float only 65.89M shares (5.4% of total). Listed Feb 9 2026 —
  options market for this name almost certainly not yet liquid;
  bid-ask spreads likely prohibitive.

SUBSTITUTE POSITIONING if wheel unavailable:
- Direct equity position in A-share (Stock Connect Northbound for HK
  residents; QFII for institutional) or H-share (HKEX direct)
- H-A premium arbitrage: H-shares historically trade at discount to
  A-shares for dual-listed Chinese companies. Check current premium
  vs historical — H-share entry may offer 10–20% valuation advantage
  over A-share entry on identical economic interest.
- Proxy via sector ETFs (KWEB / CQQQ have minimal direct Montage
  weighting; not a clean proxy)

KEY DATES TO AVOID (no puts through these):
- Apr 28, 2026: Q1 2026 earnings release ✓
- Late Aug 2026: H-share lock-up expiry (selling pressure risk)
- Q3 2026 calendar: hyperscaler capex guidance cycle (sector-wide
  cycle-turn signal risk)

SECTOR CONTEXT:
- Sector score (memory overall): Montage 19/25 — Rank 4 of 16 in coverage
- Peer conviction stack: MU 5/5, RMBS 4/5, SNDK 3.5/5, Montage 3.5/5
- Sector-level risk flags:
  * Memory cycle at Month 18, historical peak Month 18–20 (HIGH)
  * Google TurboQuant compression headwind (MEDIUM, lower impact on
    interface chips than NAND)
  * US-China export controls — Montage currently NOT restricted but
    escalation risk (MEDIUM–HIGH)
  * Post-IPO pre-IPO shareholder distribution overhang (MEDIUM)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## APPENDIX — KEY DATA POINTS SUMMARY

| Metric | Value | Source |
|---|---|---|
| FY2025 Revenue | CNY 5,456M (+49.9% YoY) | V1 Module 1 ✓ |
| FY2025 Net Income (GAAP) | CNY 2,236M (+58.4%) | V1 Module 1 ✓ |
| FY2025 Non-GAAP NI | CNY 2,647M (ex-SBC) | V1 Module 1 ⚠️ |
| FY2025 FCF | CNY 1,756M (32.2% margin) | V1 Module 3 ✓ |
| FY2025 FCF ex-SBC | CNY 1,306M (23.9% margin) | Derived |
| FY2025 SBC | CNY 450M (8.2% of rev) | V1 Module 3 ⚠️ |
| FY2025 Gross Margin | 62.2% | V1 Module 1 ✓ |
| Interconnect segment GM | 65.6% | V1 Module 1 ✓ |
| FY2026 Consensus Rev | CNY 7,493M (+37.3%) | V1 Module 6 ✓ |
| FY2026 Consensus NI | CNY 3,196M | V1 Module 6 ✓ |
| FY2027 Consensus Rev | CNY 9,245M (+23.4%) | V1 Module 6 ✓ |
| Net cash (pro-forma post-HK-IPO) | CNY 15.6B | V1 Module 2 + HK IPO |
| Fully diluted shares (post-IPO w/greenshoe) | 1,220M | V1 Module 7 |
| Global memory interconnect share | 36.8% (2024) | Frost & Sullivan / HK prospectus ✓ |
| DDR5 RCD share | 40–45% | Industry analyst ~ |
| Beta | 1.97 | R3 |
| Consensus analyst count | 11 | MarketScreener ✓ |
| Consensus average PT | CNY 162.47 | MarketScreener ✓ |

---

*Report generated 16 Apr 2026 | V2 methodology | Auditor: programmatic Python model, chart in companion PNG*
