# WINBOND ELECTRONICS (2344.TW) — V2 STOCK VALUATION

**Analysis date:** April 16, 2026
**Current price:** NT$94.40 (V1 dossier, Apr 14, 2026 close)
**Currency:** NT$ (New Taiwan Dollar)
**Shares fully diluted:** 4,500M
**Reporting standard:** IFRS; consolidated (includes Nuvoton 52.06% stake)

---

## ⚠️ PRICE INPUT DISCREPANCY — MUST READ

- **User-provided price:** NT$1,487.00
- **V1 dossier close (Apr 14, 2026):** NT$94.40 ✓
- **52-week range:** NT$15.20 – NT$136.00
- **All-time high:** NT$136.00 (Jan 30, 2026)

The input price of NT$1,487 is inconsistent with all observable data. Most likely a decimal-shift typo (NT$148.70?) or misread. This valuation proceeds using the verified dossier price of **NT$94.40**. If the user intended NT$148.70, the base-case downside conclusion worsens by approximately 57%; if NT$1,487 is somehow literal, every "overvalued" finding below should be scaled up 15x.

**The entire analysis that follows uses NT$94.40 as the reference price.**

---

## PRE-MODEL CHECKS

### Check 1 — Data Sufficiency
| Method | Data Status | Confidence |
|---|---|---|
| Reverse DCF | 12 quarters of revenue + 3 yrs FCF; WACC assumptions transparent | MEDIUM |
| Forward DCF | Full historical; but cyclical volatility means assumptions dominate | MEDIUM |
| Trading Comps | Strong peer set from sector handoff (14 memory names) | MEDIUM-HIGH |
| M&A Comps | Historical multiples; few recent specialty memory deals | LOW-MEDIUM |
| Sum-of-Parts | Segment-level disclosure for Flash / CMS / Logic / Other | MEDIUM |
| PE/LBO Floor | Entrenched ownership makes LBO impractical | LOW |

### Check 2 — Fiscal Year Alignment
Dec 31 calendar year-end. All quarterly and annual data consistent. ✓

### Check 3 — Share Count
4,500M basic = fully diluted. Nuvoton USD 150M convertible bonds issued Jan 2025 convert into **Nuvoton** (TWSE: 4919) shares at NT$118.68, **not Winbond parent** — no parent-level dilution. Aug 2024 capital raise (+320M shares at NT$31) already reflected in share count. ✓

### Check 4 — SBC Materiality
Not separately disclosed in English filings. Taiwan IDMs typically have cash-dominant compensation with minimal stock-based comp. Treating SBC as **immaterial** (<1% of revenue). No SBC-adjusted FCF track required. ✓

### Cyclical Adjustments (sector-specific)
- Memory cycles historically 18–24 months peak-to-peak; sector handoff places current cycle at **Month 18** (historical peak window)
- Trough earnings for memory IDMs typically 30–40% of peak
- Winbond FY25 CapEx (NT$6.5B) is anomalously depressed vs. FY26 guide (NT$42.1B record)
- Through-cycle DCF required; smooth-growth DCF would be misleading

---

## CURRENT METRICS

| Item | Value |
|---|---|
| Market cap | NT$424.8B (~$13.1B USD) |
| Net debt (est.) | NT$28.3B |
| Enterprise Value | NT$453.1B |
| FY25 Revenue | NT$89.4B (+9.6% YoY) |
| EV / TTM Revenue | **5.07x** |
| FY26E Revenue (base) | NT$125.2B |
| EV / NTM Revenue | **3.62x** |
| FY25 EBITDA | NT$18.7B |
| EV / FY26E EBITDA (base) | **12.1x** |
| FY25 EPS | NT$0.88 |
| TTM P/E | **107x** (trough earnings) |
| Forward P/E at JPM FY26E NT$6.30 | 15.0x |

---

## METHOD 1: REVERSE DCF

**Purpose:** What long-term revenue CAGR does the current NT$94.40 price require to justify?

**Assumptions:**
- Horizon: 10 years
- Terminal FCF margin: 15% (mid-cycle IDM; sector handoff 15–25% range)
- Terminal growth: 3%
- WACC: 10%
- FCF margin ramps linearly from current 5.2% → terminal 15% over 10 years

### Results

**Market-implied 10-year revenue CAGR: 15.5%**

### Sensitivity — Implied CAGR (%)

| WACC ↓ / Term FCF Margin → | 10% | 15% | 20% | 25% |
|---|---|---|---|---|
| 9% | 17.9% | 13.1% | 9.7% | 7.2% |
| **10%** | **20.5%** | **15.5%** | **12.1%** | **9.5%** |
| 11% | 22.9% | 17.8% | 14.3% | 11.6% |
| 12% | 25.1% | 20.0% | 16.4% | 13.6% |

### Gap Analysis

| Growth reference | Rate |
|---|---|
| **Market-implied 10-yr CAGR (base assumptions)** | **15.5%** |
| Management FY26 guidance (NT$100B+) | +12% YoY |
| JPMorgan FY26 implied (NT$125B) | +40% YoY (cycle peak) |
| Sector handoff "winners" normalized growth | 15–25% |

**Interpretation:** The 15.5% implied CAGR sits at the bottom of the sector's normalized mid-cycle range. On its own, reverse DCF does NOT indicate the stock is stretched on long-term growth expectations. However, this reconciliation assumes the market will credit terminal FCF margins of 15% sustained through cycles — which is a meaningful execution bet given Winbond's FY25 actual FCF margin of 5.2%. If terminal margins come in at 10% (bear case), the stock implies a 20.5% CAGR, which WOULD be stretched. **The reverse DCF result is margin-dependent, not growth-stretched.**

---

## METHOD 2: FORWARD DCF (3-Scenario, Cyclical Structure)

**Methodology note:** Memory IDMs cannot be modeled with smooth growth. This analysis uses explicit peak → transition → trough → recovery paths over 7 years, with separate EBITDA-margin and CapEx-as-%-of-revenue projections, before deriving FCF.

### Scenario Assumptions

| Year | Bull (g% / EBITDA m%) | Base (g% / EBITDA m%) | Bear (g% / EBITDA m%) |
|---|---|---|---|
| FY2026 | +45% / 35% | +40% / 30% | +30% / 28% |
| FY2027 | +25% / 40% | +15% / 35% | 0% / 22% |
| FY2028 | +5% / 35% | −5% / 25% | −18% / 10% |
| FY2029 (trough) | −10% / 25% | −20% / 12% | −22% / 0% |
| FY2030 | +12% / 28% | +15% / 20% | +5% / 10% |
| FY2031 | +12% / 30% | +10% / 24% | +8% / 15% |
| FY2032 | +8% / 32% | +6% / 26% | +4% / 18% |
| **Terminal FCF margin** | **22%** | **15%** | **10%** |
| Terminal growth | 3.0% | 2.5% | 2.0% |
| WACC | 9.5% | 10.0% | 11.0% |

**CapEx schedule (% of revenue):** FY26 33% (NT$42.1B guided) → FY27 22% → FY28–32 15–18%. Tax rate: 18% (Taiwan corporate).

### Projections (NT$M)

| Year | Rev Bull | FCF Bull | Rev Base | FCF Base | Rev Bear | FCF Bear |
|---|---|---|---|---|---|---|
| FY2026 | 129,639 | −2,308 | 125,168 | −7,360 | 116,228 | −8,740 |
| FY2027 | 162,048 | 21,585 | 143,944 | 13,272 | 116,228 | −5,161 |
| FY2028 | 170,151 | 27,598 | 136,746 | 6,865 | 95,307 | −7,625 |
| FY2029 | 153,136 | 15,344 | 109,397 | −3,282 | 74,339 | −11,151 |
| FY2030 | 171,512 | 17,974 | 125,807 | 3,674 | 78,056 | −3,903 |
| FY2031 | 192,093 | 23,282 | 138,387 | 8,580 | 84,301 | −152 |
| FY2032 | 207,461 | 28,547 | 146,691 | 11,501 | 87,673 | 1,999 |

### Valuation Summary (NT$B)

| Item | Bull | Base | Bear |
|---|---|---|---|
| PV of 7-yr FCF | 87.6 | 20.2 | −26.4 |
| PV of terminal value | 383.2 | 154.3 | 47.9 |
| Enterprise Value | 470.8 | 174.5 | 21.4 |
| Net Debt | (28.3) | (28.3) | (28.3) |
| Equity Value | 442.5 | 146.3 | (6.8) |
| **Per share (NT$)** | **98.34** | **32.50** | **−1.52** |
| Upside vs. NT$94.40 | +4.2% | **−65.6%** | −101.6% |
| TV / Total EV | 81% ⚠️ | 88% ⚠️ | 223% ⚠️ |

### ⚠️ Terminal Value Discipline Flag

**All three scenarios have TV concentration above the 70% threshold.** This is structurally expected for Winbond because (1) FY26 CapEx of NT$42.1B crushes near-term FCF into negative territory, (2) the cycle trough in FY29 (base case) further depresses PV, and (3) the recovery only materializes in FY31–32 before terminal. The DCF is therefore speculative in the formal sense — results are dominated by terminal-margin assumptions, not near-term fundamentals. **Do not treat DCF outputs as precise; treat them as a sanity check on through-cycle earnings power.**

### Round-Trip Check

| Scenario | PT (NT$) | Implied EV (NT$B) | EV / NTM Rev |
|---|---|---|---|
| Bull | 98.34 | 470.8 | 3.63x |
| Base | 32.50 | 174.5 | 1.39x |
| Bear | −1.52 | 21.4 | 0.18x |

Base case implies 1.39x EV/NTM Revenue, which is below the sector handoff's 1.5–2.0x "cheapest in universe" entry point from April 2. This is internally consistent: base-case DCF is saying the stock should trade at a through-cycle, not cycle-peak, multiple.

---

## METHOD 3: TRADING COMPS

### Peer Set (per sector handoff, Apr 2, 2026)

| Company | EV/NTM Rev | NTM Growth | Growth-Adj | GM | EBITDA M |
|---|---|---|---|---|---|
| Micron (MU) | 3.00x | 80% | 0.04x | 74.9% | 64.0% |
| SK Hynix | 5.60x | 50% | 0.11x | 60.0% | 69.0% |
| Samsung | 3.30x | 20% | 0.16x | 47.0% | 25.0% |
| SanDisk (SNDK) | 4.00x | 60% | 0.07x | 50.9% | 35.0% |
| Kioxia (285A) | 3.20x | 30% | 0.11x | 26.0% | 44.0% |
| Nanya (2408.TW) | 2.80x | 50% | 0.06x | 49.0% | 49.0% |
| **Winbond (2344.TW)** | **3.62x** | **40%** | **0.09x** | **34.9%** | **21.0%** |
| Macronix (2337.TW) | 3.25x | 12% | 0.27x | 14.9% | 4.8% |
| Silicon Motion | 3.10x | 45% | 0.07x | 48.3% | 18.0% |
| Phison | 5.50x | 30% | 0.18x | 41.6% | 20.0% |
| Rambus | 10.00x | 18% | 0.56x | 79.6% | 42.7% |
| Montage | 25.00x | 50% | 0.50x | 60.0% | 44.5% |

### Direct Peer Group for Winbond

- **Primary:** Nanya (Taiwan specialty DRAM pureplay), Kioxia (NAND IDM peer on cycle), SanDisk (NAND pureplay), Macronix (Taiwan NOR peer but unprofitable)
- **Adjacent:** Micron, SK Hynix (IDM leaders, but HBM tier-up)

**Direct peer median EV/NTM Rev: 3.23x**
**Direct peer mean: 3.31x**
**Sector handoff benchmark for winners in upcycle: 3–6x (1–2x at trough)**

### Fair Multiple Determination

Winbond is a tier-3 specialty memory name at cycle peak. It deserves:
- **Premium to Macronix and Nanya** on NOR leadership (#1 global) and lower margin volatility
- **Discount to MU / SK Hynix** (no HBM exposure)
- **Growth-adjusted fair** near peer median (~3.5x at 40% growth)

| Scenario | Multiple | Implied PT |
|---|---|---|
| Bear (trough / normalized) | 2.0x EV/NTM Rev | **NT$49.35** |
| Base (mid-upcycle) | 3.5x | **NT$91.07** |
| Bull (upper upcycle, NOR premium) | 4.5x | **NT$118.89** |

### Crosschecks

- **EV/NTM EBITDA (base):** 12.1x vs. memory IDM peak norm 6–10x → Winbond expensive on EBITDA
- **P/E (forward, JPM):** 15.0x at NT$6.30 EPS vs. memory IDM peak norm 8–12x → top of peak range
- **P/E (forward, mid-cycle):** 37.8x at NT$2.50 EPS → expensive if mid-cycle view correct

### Verdict

Trading comps at **base case NT$91** are essentially at the current price. This is the method most aligned with sell-side consensus — analysts crediting the cycle-peak multiple. But note: all sector peers are also at peak multiples, creating valuation-by-reference-to-other-bubbles risk.

---

## METHOD 4: PRECEDENT M&A COMPS

### Relevant Specialty Memory Transactions

| Deal | Year | Multiple (EV/Rev) |
|---|---|---|
| WDC acquires SanDisk | 2016 | ~2.3x trailing |
| Infineon acquires Cypress | 2020 | ~2.0x trailing |
| Bain LBO of Kioxia | 2018 | ~2.0x trailing |
| Memory IDM distressed | various | 1.0–1.5x |
| Memory IDM premium | various | 2.0–3.0x |

**Sector handoff calibration:** "Memory M&A historically at 1–3x trailing revenue."

### Applied to Winbond FY25 Trailing Revenue NT$89.4B

Per V2 methodology, M&A multiples include ~25% control premium — discount applied to derive public-market "takeout floor."

| Scenario | Multiple | EV | Control-Adj Floor PT |
|---|---|---|---|
| Bear (1.5x, distress) | 1.5x | NT$134.1B | **NT$16.07** |
| Base (2.0x, strategic) | 2.0x | NT$178.8B | **NT$23.52** |
| Bull (2.5x, competitive) | 2.5x | NT$223.5B | **NT$30.97** |

### Reality Check — Takeout Probability: LOW

- **Walsin Lihwa holds 22.1% blocking stake** plus Chairman personal 1.53% — entrenched control
- **Cross-holding complex** (Walsin Lihwa + Chin Xin + Chiao family "tong group" structure)
- **Taiwan national security review** would block Chinese acquirers
- **Plausible strategic buyers essentially nil:** Macronix too small/weak; Kioxia-SNDK merger focus is NAND; Samsung/Hynix exiting specialty not entering; private equity thin in Taiwan semis
- **Walsin Lihwa stake increases rather than full takeover** is the most realistic ownership change path

**Probability-weighted M&A PT: meaningful only as extreme downside floor, not as likely realization. Apply heavy weight-tilt down.**

---

## METHOD 5: SUM-OF-PARTS

### Segment Revenue Breakdown (Q4 2025 mix, applied to FY26E Base NT$125.2B)

| Segment | % | FY26E Rev (NT$B) |
|---|---|---|
| Flash (NOR + SLC NAND) | 37% | 46.3 |
| CMS (Specialty DRAM) | 35% | 43.8 |
| Logic IC (Nuvoton 52% owned) | 26% | 32.5 |
| Other (software services) | 2% | 2.5 |

### Segment Multiples and EV

| Segment | Bear M | Base M | Bull M | Bear EV | Base EV | Bull EV |
|---|---|---|---|---|---|---|
| Flash (NOR #1 global, SLC NAND #3) | 2.5x | 3.5x | 4.5x | 115.8 | 162.1 | 208.4 |
| CMS (specialty DRAM, Nanya comp) | 1.8x | 3.0x | 4.0x | 78.9 | 131.4 | 175.2 |
| Logic IC (Nuvoton, loss-making MCU) | 0.8x | 1.5x | 2.0x | 26.0 | 48.8 | 65.1 |
| Other | 1.0x | 2.0x | 3.0x | 2.5 | 5.0 | 7.5 |
| **Total EV** | | | | **223.2** | **347.3** | **456.2** |
| Less: Nuvoton NCI (48% of Logic segment EV) | | | | (12.5) | (23.4) | (31.2) |
| Less: Net Debt | | | | (28.3) | (28.3) | (28.3) |
| **Equity Value** | | | | **182.4** | **295.6** | **396.7** |
| **Per Share (NT$)** | | | | **40.54** | **65.70** | **88.16** |
| vs. NT$94.40 | | | | −57.1% | −30.4% | −6.6% |

### Hidden Value Flags

- **CUBE (3DCaaS custom memory):** Zero explicit value assigned. Management targets "2026 harvest revenue" — if CUBE achieves material wins (e.g., NT$2–5B annual run-rate), could add NT$5–15B to EV (~NT$1–3/share)
- **1.2V NOR for AI accelerators:** Currently embedded in Flash segment at blended multiple. Given AI adjacency (up to $600 NOR content per GB200 NVL72 rack), a pure AI-premium multiple could uplift Flash segment by 0.5–1.0x EV/Rev
- **Combined optionality:** ~10–20% upside bias to SoP, not captured in base case

### Verdict

SoP base case of **NT$65.70** shows the stock is ~30% above fair value even with full credit to Flash leadership and CMS recovery. The gap is driven primarily by Logic IC (Nuvoton) dragging down the blended multiple — at 2.0x EV/Rev, Logic deserves only a mid-teens multiple due to ongoing losses. This is a structural SoP issue: Winbond consolidates a diluted, lower-multiple business into a higher-multiple memory story.

---

## METHOD 6: PE / LBO FLOOR

### LBO Assumptions

- Hold: 5 years
- Normalized EBITDA (5-yr avg FY26–FY30, base case): NT$32.1B
- Exit EBITDA (FY2030 base): NT$25.2B
- Exit multiple: 5.0x EV/EBITDA (through-cycle)
- Exit EV: NT$125.8B
- Cumulative 5-yr FCF (base): NT$13.2B
- Debt: 2.5x normalized EBITDA at entry = NT$80.3B

### Solver Results

| IRR Target | Label | Max Entry EV | Per-Share Floor | vs. NT$94.40 |
|---|---|---|---|---|
| 25% | Aggressive PE | NT$100.0B | **NT$15.94** | −83% |
| 20% | Standard PE | NT$104.0B | **NT$16.83** | −82% |
| 15% | Patient capital | NT$109.5B | **NT$18.05** | −81% |

### Reality Check — Winbond LBO Feasibility: IMPRACTICAL

- **22.1% Walsin Lihwa blocking stake** prevents any hostile or unwanted LBO
- **NT$42.1B FY26 CapEx** means near-term FCF negative — no debt service coverage
- **Taiwan PE market thin**; sovereign considerations complicate foreign PE
- **High balance sheet leverage already** (D/E 0.68) limits incremental debt capacity

**Use LBO floor only as theoretical downside anchor with minimal weight.**

---

## TRIANGULATION & PRICE TARGET

### Method Results Summary (NT$ per share)

| Method | Weight | Bear | Base | Bull | Confidence |
|---|---|---|---|---|---|
| Reverse DCF | — | (diagnostic: 15.5% implied CAGR; within 15–25% mid-cycle band) | | | MEDIUM |
| Forward DCF | 30% | −1.52 | 32.50 | 98.34 | MEDIUM |
| Trading Comps | 40% | 49.35 | 91.07 | 118.89 | MED-HIGH |
| Sum-of-Parts | 20% | 40.54 | 65.70 | 88.16 | MEDIUM |
| M&A Comps | 5% | 16.07 | 23.52 | 30.97 | LOW-MED |
| PE/LBO Floor | 5% | 15.94 | 16.83 | 18.05 | LOW |

### Weighting Rationale

- **Forward DCF 30%:** Cyclical structure modeled explicitly, but TV concentration >80% limits reliability. Reduced from V2-standard 35–45% default.
- **Trading Comps 40%:** Strongest method for cyclicals at peak — peer set well-defined; however, entire peer set is also at peak multiples (reference-class risk).
- **SoP 20%:** Segments are materially different (CMS growing +139%, Nuvoton loss-making) — SoP captures dispersion comps miss.
- **M&A 5%:** Theoretical only; takeout probability <15%.
- **LBO 5%:** Theoretical floor; not realizable given ownership structure.

### Weighted Price Target

| Scenario | Weighted PT | vs. NT$94.40 |
|---|---|---|
| **Bear** | **NT$28.99** | **−69.3%** |
| **Base** | **NT$61.34** | **−35.0%** |
| **Bull** | **NT$97.14** | **+2.9%** |

---

## CONVICTION SCORE: 3.5 / 5 — MODERATE

### Rationale

1. **Methods diverge substantially.** DCF base (NT$33) vs. Trading Comps base (NT$91) vs. SoP base (NT$66). This is the classic signature of a cycle-peak stock — intrinsic methods say "overvalued," relative methods say "in line with peers" because peers are also at peak.
2. **Reverse DCF diagnostic is constructive but margin-dependent.** 15.5% implied 10-year CAGR is within the sector's 15–25% mid-cycle band; market isn't demanding unrealistic growth. But result is conditional on 15% terminal FCF margin — drops to 20.5% CAGR (stretched) if terminal margins come in at 10%.
3. **Price action compression of the sector handoff thesis.** The handoff rated Winbond "5/5 Relative Valuation" at 1.5–2.0x EV/NTM Rev (~NT$110 context). The stock now trades at 3.6x NTM — same company, fundamentally changed risk/reward. Equivalent rating today would be 2.5–3/5.
4. **Structural bull story is real but priced in.** NOR Flash #1 global share, 1.2V NOR for AI accelerators, Samsung SLC NAND exit, CUBE custom memory 2026 harvest, multi-year LTAs to 2030, 16nm CMS ramp — all support PREMIUM multiples vs. trough comps. Current price fully credits these and adds cycle-extension optimism.
5. **Asymmetric risk at Month 18 of upcycle.** Sector handoff explicitly flags Month 18–20 as historical cycle peak window. Bear case (−69%) is severe; bull case (+3%) is modest. Reward/risk profile is poor at this level.
6. **Score of 3.5 (not 3.0)** reflects the richness of the underlying research and the clarity of the direction signal. Score of 4.0 was considered but rejected because methods materially diverge and data gaps on share of revenue by geography / customer concentration remain.

---

## KEY ANALYTICAL OBSERVATIONS

### The Cycle-Peak Multiple Compression Problem

At the sector handoff date (April 2), Winbond traded at 1.5–2.0x EV/NTM Rev. At this valuation analysis date (April 16), it trades at 3.6x NTM — a ~80% multiple expansion in two weeks. The underlying fundamentals haven't materially changed; what changed was sentiment and momentum after the Q4 2025 earnings + FY26 guidance (+90–95% Q1 DRAM price surge) + Morgan Stanley's double-upgrade. **The cheapness that earned the sector's highest relative-valuation score is gone at this price.**

### Why Consensus PTs (NT$142–167) Diverge from This Analysis

- JPMorgan NT$167 PT assumes JPM's FY26E EPS NT$6.30 is realized → at 25x P/E that equates to NT$158. At 26x NT$164. The PT is internally consistent with their EPS view but embeds 25x P/E on peak-cycle earnings.
- MarketScreener NT$163.40 average is from 5 analysts — small sample, all bullish on Taiwan memory thesis.
- Through-cycle modeling produces NT$61 base because it prices FY29 trough earnings (−20% rev, 12% EBITDA margin) and terminal 15% FCF margin — more conservative than consensus.
- **The gap is not analytical error; it's a genuine difference in cycle-duration assumptions.** Consensus credits structural DDR4 scarcity + Samsung SLC NAND exit as multi-year cycle extenders. This analysis applies historical cycle periodicity.

### Asymmetric Entry Opportunity

Entry at NT$94.40 gives roughly 3% upside to bull weighted / 35% downside to base weighted. **Poor asymmetry.** Entry at NT$65–70 would flip this: ~45% upside to bull / 0% downside to base weighted. The name becomes a structural buy candidate on pullback, not at current.

### Data Gaps (Not Fully Addressed)

- Customer concentration (top 10 as % of revenue) — unknown
- Inventory days — unknown
- China revenue % — unknown
- Debt maturity schedule within 18 months — unknown
- SBC disclosure — likely immaterial but unconfirmed

These gaps are individually minor but collectively reduce conviction 0.5 points.

---

## ━━━ OPTIONS WHEEL HANDOFF ━━━

```
TICKER: 2344.TW (Winbond Electronics)
SECTOR: Semiconductor Memory (Specialty DRAM / NOR / SLC NAND IDM)
VALUATION DATE: Apr 16, 2026

PRICE TARGET: NT$61.34 base (range: NT$28.99 bear – NT$97.14 bull)
CURRENT PRICE: NT$94.40
UPSIDE TO BASE: -35.0%  (DOWNSIDE)
CONVICTION: 3.5/5

WHEEL STRATEGY IMPLICATIONS:

- SELL PUTS: NO (at current price)
  Rationale: Stock trades 35% ABOVE base case fair value. Selling puts at
  current levels = committing to buy a deeply overvalued cyclical at
  Month 18 of an 18-20 month historical peak window. Negative expected value.

  Reconsider if stock pulls back to NT$65-75 zone:
  - At NT$65-70: put strikes NT$55-65 become attractive (at/below SoP base,
    near DCF bull-case downside)
  - Monitor cycle signals: hyperscaler capex guidance cuts (Q2-Q3 2026), DRAM
    inventory rebuilding above 12 weeks, ASP declines in spot market

  Avoid puts above: NT$85 (above any defensible base case)

- CONCENTRATED LONG CANDIDATE: NO
  Fails both gating criteria:
    [X] Conviction 3.5 < 4.0 required
    [X] Base case shows -35% DOWNSIDE, not +30% upside

- COVERED CALLS (if somehow assigned): YES
  Cost basis scenario: put strike NT$85 or below (if recommended strike range
    were met via correction)
  Minimum call strike: at least cost basis (cc_min_strike_pct = 1.0)
  Suggested call strike zone: NT$95-110 (between cost basis + base case PT bull)
  Do NOT sell calls above: NT$130 (approaching bull case, cycle extension optionality)

- STAND-ASIDE RECOMMENDATION
  The right position today is no position. Reassess on either (a) 30%+ pullback
  to NT$65-70 zone, or (b) clear cycle-continuation data (Q1 2026 GM >50% confirmed,
  Q2 guidance holding at +90% QoQ, no hyperscaler capex cuts).

KEY DATES / CATALYSTS:
- Q1 2026 Earnings: April 29-30, 2026 (first quarter capturing +90-95%
  DRAM price surge; avoid all short-dated options positions through this event)
- Monthly revenue disclosures: first week of each month (mid-volatility)
- Samsung SLC NAND final shipment: June 2026 (supply shift event)
- Q2 2026 earnings: ~August 2026 (confirms Q2 price guidance)

SECTOR CONTEXT:
- Sector score: 18/25 (PASS TO VALUATION, per sector handoff)
- Relative ranking in memory universe: 6 of 14 tradeable names
- Cycle position: Month 18 of 18-20 month historical peak window (HIGH cycle risk)
- Sector-level risks that apply to 2344.TW specifically:
  * US tariff exposure (100% threat on Taiwan-origin memory — no US manufacturing)
  * Cycle peak risk (highest in sector given recent 521% run)
  * DDR4/DDR5 Big 3 re-entry risk (structural pricing reversal trigger)
  * CXMT Chinese domestic specialty DRAM competition (medium-term share pressure)

OPTIONS AVAILABILITY:
TWSE individual equity options on 2344 ARE traded but liquidity is thin compared
to US names. Alternative wheel vehicles for Taiwan:
  - Direct shares (primary approach): adjust position sizing vs. conviction
  - Equivalent equity sizing at Kelly(conviction=3.5, edge=negative-base-case) = 0
    → Zero allocation is the rigorous answer

FX CONSIDERATION:
NT$/USD exposure: NT$ vs. USD has been stable; no FX hedging adjustment needed
at this time per Winbond Feb 2026 commentary ("FX stabilizing").
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## APPENDIX: PRICE-INPUT SENSITIVITY

If the user-input "1487" was meant literally (NT$1,487 per share):
- This would be 15.75× the dossier price
- Every "overvalued" finding multiplies by 15.75×
- Bear / Base / Bull weighted PTs (same NT$ values): represent −98% / −96% / −93% downside

If the user meant NT$148.70 (decimal typo, possible post-dossier rally):
- Bear / Base / Bull weighted PTs NT$28.99 / NT$61.34 / NT$97.14
- Represent −81% / −59% / −35% vs. NT$148.70
- Base case downside worsens to −59%
- Even bull case is −35%
- **Every signal becomes sharper SELL**

The base analysis at NT$94.40 (dossier-verified) is already sufficient to justify STAND ASIDE. Either alternative interpretation reinforces that conclusion.

---

**END OF VALUATION REPORT**
