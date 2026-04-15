# V2 — GOOGL / ALPHABET INC. | STOCK VALUATION REPORT

**Ticker:** GOOGL
**Company:** Alphabet Inc.
**Current Price:** $317.25
**Analysis Date:** April 12, 2026
**Sector:** Digital Advertising / AdTech (Walled Garden) — Rank 4 of 18, Score 22/25, Tier 1 PASS
**Analyst:** V2 Stock Valuation Engine
**Inputs:** V1 Company Dossier (GOOGL), AdTech Sector Handoff v2 (Apr 6 2026)

---

## EXECUTIVE SUMMARY

```
━━━ VALUATION SUMMARY ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
CURRENT PRICE:          $317.25
MARKET CAP:             $3,880B ($3.88T)
ENTERPRISE VALUE:       $3,800B
EV / NTM REVENUE:       8.35x  (sector handoff Apr 6: 7.3x → +14% re-rating)

TRIANGULATED PRICE TARGET (weighted, 6 methods):
  Bear:   $166  (-47.7%)
  Base:   $203  (-36.0%)
  Bull:   $261  (-17.8%)

CONVICTION SCORE:       4 / 5  (HIGH CONVICTION OVERVALUED)

WHEEL VERDICT: DO NOT SELL PUTS. DO NOT ADD TO LONGS.
            Current price is above the bull case of every method
            except one (Forward DCF bull $268). Every base case is
            materially below spot. This is a structural hold-or-trim,
            not a put-selling candidate.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

**One-line thesis:** Alphabet is a genuinely excellent business — the moat scores 5/5, management 4/5, the business model 5/5 — but at $317 the market is pricing in sustained ~15% revenue CAGR for the next decade against a realistic path of ~11% consensus growth, a doubled capex base that crushes near-term FCF, and a binary antitrust ruling (AdX divestiture) that could arrive any week. This is the Tim Cook / 2018 Apple "great company, wrong price" setup.

---

## PRE-MODEL CHECKS

### Check 1: Data Sufficiency

| Method | Inputs Required | Status |
|---|---|---|
| Reverse DCF | EV, WACC, terminal margin, FCF history | ✅ Complete |
| Forward DCF | 8Q revenue/FCF, consensus, share count, net debt | ✅ Complete |
| Trading Comps | Peer multiples (mega-cap software) | ✅ Complete (sector handoff) |
| M&A Comps | Relevant precedents | ⚠️ N/A — $3.88T cannot be acquired |
| Sum-of-Parts | Segment revenue | ✅ Complete (FY25 segment breakdown) |
| PE/LBO Floor | FCF, debt capacity | ⚠️ N/A at scale — repurposed to 10% IRR floor |

**Flag:** M&A Comps and PE/LBO Floor in their literal form are not executable at $3.88T mega-cap scale. M&A is weighted at 0%. LBO is reframed as a "quality equity floor" and weighted at 5%.

### Check 2: Fiscal Year Alignment
Alphabet fiscal year = calendar year (Dec 31). FY2025 reported Feb 4, 2026. No alignment issues. FY26E consensus ($455B) is directly comparable.

### Check 3: Share Count Reconciliation
Using **fully diluted FY2025 = 12,230M**. Class A/B/C structure with Page/Brin retaining supermajority voting via Class B — governance risk noted, but no share count ambiguity. Diluted shares declined 1.7% YoY from 12,447M (net of $45.7B FY25 buybacks vs. ongoing SBC issuance of $25.0B). Buyback pace slowed in FY25 vs. FY24 ($62.2B) — consistent with capex pivot.

### Check 4: SBC Materiality
FY25 SBC = $24,953M on $402,836M revenue = **6.2%** — **BELOW the 15% threshold**. Single-track FCF presentation is appropriate, but for completeness:

- **FY25 Reported FCF:** $73,266M (18.2% margin)
- **FY25 FCF ex-SBC:** $48,313M (12.0% margin)

The SBC adjustment matters less for GOOGL than for SaaS peers, but the 620bps gap is still meaningful when comparing to META (10.2% SBC) and MSFT (4.0%).

**TV > 70% warning:** Base case TV/Total = 72% → flag applied. Bear 66%, Bull 77%. Bull case explicitly speculative.

---

## METHOD 1 — REVERSE DCF

**Purpose:** Solve for the revenue CAGR implied by the current $3,800B EV.

### Assumptions
| Input | Value | Rationale |
|---|---|---|
| Current EV | $3,800B | Mkt cap $3,880B − net cash $80B |
| WACC | 9.5% | Mega-cap, low beta, but AI/antitrust uncertainty premium |
| Start FCF margin | 20% | Normalize FY25 18.2% against 2026 capex-compressed outlook |
| Terminal FCF margin | 25% | Mature ads+cloud mix; sector handoff ceiling for mega-cap software |
| Terminal growth | 3.0% | GDP-perpetuity |
| Horizon | 10 years (linear margin ramp) |

### Result
```
IMPLIED 10-YEAR REVENUE CAGR:   14.9%
FY25 actual growth:             15.1%
FY26E consensus:                ~13.0%
FY27E consensus:                ~11.4%
Implied 10Y consensus (fade):   ~8.5%
```

**GAP:** Market is pricing in 14.9% CAGR **sustained for a decade** — roughly matching FY25's 15% print. This requires search, YouTube, and Cloud to collectively avoid any meaningful deceleration over ten years. Consensus already has growth fading to 11% by FY27. For the implied 14.9% to be right, Cloud would need to maintain +35% growth through 2030, Search would need to resist AI disruption entirely, and YouTube would need to reaccelerate from its current +9%.

**Assessment: The market is pricing in growth ACCELERATION vs. consensus trajectory.** This is the opposite of what the fundamentals suggest.

### Sensitivity — Implied CAGR Required at $317.25

| WACC \ Terminal FCF Margin | 20% | 25% | 30% |
|---|---|---|---|
| 8.5% | 14.9% | **12.4%** | 10.3% |
| 9.5% | 17.5% | **14.9%** | 12.8% |
| 10.5% | 19.9% | 17.2% | 15.1% |

Even in the most charitable corner (8.5% WACC + 30% terminal margin — both bullish assumptions), the market requires 10.3% CAGR for a decade. In the most realistic corner (9.5% WACC + 25% margin), it requires 14.9%. **There is no reasonable assumption set in which the current price implies fair growth.**

---

## METHOD 2 — FORWARD DCF (3-SCENARIO)

### Scenario Assumptions

| Assumption | Bull | Base | Bear |
|---|---|---|---|
| Yr 1-2 Rev CAGR | 14-15% | 11-13% | 7-10% |
| Yr 3-5 Rev CAGR | 11-13% | 8-10% | 4-5% |
| Yr 6-7 Rev CAGR | 9-10% | 7% | 4% |
| Yr 1 FCF Margin | 15% | 14% | 13% |
| Yr 7 FCF Margin | 27% | 23% | 19% |
| Terminal Growth | 3.5% | 3.0% | 2.5% |
| WACC | 9.0% | 9.5% | 10.0% |
| **Narrative** | AI Overviews monetize at parity; Cloud sustains 30%+; capex normalizes 2027; Waymo becomes material | Consensus fade; 2026 capex surge crushes FCF then recovers; AI Overviews monetize at ~70% of traditional CPC | AdX forced divestiture; search volume contracts per Gartner 25% call; capex stays elevated; cloud grows but doesn't scale margins |

### Base Case — Year-by-Year

| Yr | Revenue ($B) | YoY Growth | FCF Margin | FCF ($B) | Disc. Factor | PV FCF ($B) |
|---|---|---|---|---|---|---|
| 1 | 455 | 13.0% | 14.0% | 63.7 | 0.913 | 58.2 |
| 2 | 505 | 11.0% | 15.0% | 75.8 | 0.834 | 63.2 |
| 3 | 556 | 10.0% | 18.0% | 100.0 | 0.762 | 76.2 |
| 4 | 606 | 9.0% | 20.0% | 121.2 | 0.696 | 84.3 |
| 5 | 654 | 8.0% | 22.0% | 143.9 | 0.635 | 91.4 |
| 6 | 700 | 7.0% | 23.0% | 161.0 | 0.580 | 93.4 |
| 7 | 749 | 7.0% | 23.0% | 172.3 | 0.530 | 91.3 |
| **TV** | | | | **2,730** | | **1,446** |

### Valuation Summary

| | Bull | Base | Bear |
|---|---|---|---|
| PV of Cash Flows ($B) | 719 | 558 | 400 |
| PV of Terminal Value ($B) | 2,472 | 1,446 | 776 |
| Enterprise Value ($B) | 3,191 | 2,004 | 1,177 |
| + Net Cash ($B) | 80 | 80 | 80 |
| Equity Value ($B) | 3,272 | 2,085 | 1,257 |
| Fully Diluted Shares (M) | 12,230 | 12,230 | 12,230 |
| **Per Share Value** | **$268** | **$170** | **$103** |
| Upside / (Downside) vs $317 | -15.6% | -46.4% | -67.5% |
| TV as % of Total | **77% ⚠️** | **72% ⚠️** | 66% |

⚠️ **Terminal value >70% in Base and Bull — flagged as speculative per quality rules.** The bull case is particularly dependent on the Year 8+ extrapolation. Even in the bull case, current price is below fair value.

### Round-Trip Check

Base case DCF implies EV / NTM Revenue = **4.4x** vs. current **8.35x**. This is a massive gap and demands explanation:

- **The fundamental read:** At $455B NTM revenue growing to $749B over 7 years with FCF compressed by 2026 capex, discounted fairly, this business is worth ~$2,000B EV not $3,800B.
- **The counterpoint:** Mega-cap software + AI narrative is supporting a multiple premium that DCF mechanics cannot capture. This is real but is NOT a reason to bend the DCF to fit.

---

## METHOD 3 — TRADING COMPS

Per the sector handoff: walled gardens must be compared to mega-cap software peers (5–10x NTM Rev), NOT to pure-play AdTech (1–5x). Peer set:

### Peer Table

| Peer | NTM Rev Growth | FCF Margin | EV/NTM Rev | Growth-Adj Ratio |
|---|:---:|:---:|:---:|:---:|
| META | 23% | 21.7% | 5.8x | 0.252 |
| MSFT | 12% | 24.0% | 7.8x | 0.650 |
| AMZN (full-co) | 11% | 1.6%* | 2.9x | 0.264 |
| **GOOGL (current)** | **13%** | **18.2%** | **8.35x** | **0.642** |

*AMZN FCF margin depressed by $200B 2026 capex — not clean comp.

**Positioning:** GOOGL growth is 1pt ahead of MSFT, 10pts behind META. FCF margin is below both (META 21.7%, MSFT 24%). Moat quality is top-tier. AI/antitrust overhangs justify a discount, not a premium.

**Peer median (ex-AMZN): 6.8x NTM Rev.** GOOGL currently trades at **8.35x — a 23% premium to peer median despite weaker margins and larger regulatory overhangs.**

### Fair Multiple Range

| Scenario | Multiple | Rationale |
|---|:---:|---|
| Bear | 6.0x | Discount to META, reflecting AI disruption reality + AdX divestiture risk |
| Base | 6.5x | Slight discount to peer median; moat premium offset by overhangs |
| Bull | 7.0x | In-line with peer median if AI Overviews monetize at parity |

### Implied Prices

| Multiple | EV ($B) | Equity ($B) | Per Share | vs. $317.25 |
|---|---|---|---|---|
| 6.0x | 2,730 | 2,810 | **$230** | **-27.6%** |
| 6.5x | 2,958 | 3,038 | **$248** | **-21.7%** |
| 7.0x | 3,185 | 3,265 | **$267** | **-15.8%** |

**Even the bullish 7.0x target implies 16% downside.** Trading comps agree with DCF on direction, disagree on magnitude. The DCF says fundamentals are worth ~$170, the comps say "even a generous peer multiple gets you $267." Both agree the stock is overvalued.

---

## METHOD 4 — PRECEDENT M&A COMPS

**Not applicable.** GOOGL has a $3.88T market cap. The largest technology M&A transaction in history was Microsoft-Activision at ~$69B. No strategic or financial buyer can acquire Alphabet. The only "M&A-adjacent" scenario is **forced antitrust spinoff** of AdX or other segments, which is captured in the Sum-of-Parts method below.

**Weight in triangulation: 0%.**

---

## METHOD 5 — SUM-OF-PARTS

### Segment-by-Segment Valuation

| Segment | FY25 Rev ($B) | Comp / Logic | Multiple | Implied EV ($B) |
|---|---:|---|:---:|---:|
| Google Search & other | 224.5 | META ads comp, discount for AI disruption | 5.5x | 1,234.9 |
| YouTube ads | 40.4 | Premium CTV/brand — ROKU 2.3x floor, NFLX 6x ceiling | 6.0x | 242.2 |
| Google Network | 29.8 | Declining open-web AdTech; MGNI/PUBM comp | 2.5x | 74.5 |
| Subs, Platforms, Devices | 47.1 | Consumer subs + hardware blend | 3.5x | 164.7 |
| Google Cloud | 58.7 | +36% growth, track to profitability, Azure comp | 9.0x | 528.4 |
| Other Bets (Waymo+) | 1.5 | Waymo post-Feb 2026 $16B raise valuation peg | flat | 150.0 |
| **Segment EV total** | | | | **2,394.8** |
| Less: Holdco discount (10%) | | Diversified conglomerate standard | | (239.5) |
| **Net EV** | | | | **2,155.3** |
| Plus net cash | | | | 80.3 |
| **Equity value** | | | | **2,235.6** |
| **Per share** | | | | **$182.8** |
| vs. current | | | | **-42.4%** |

### Hidden Value / Hidden Risk Flags

- **Cloud upside:** 9.0x on $58.7B may be conservative. Azure-only comps trade at 12–15x. If Cloud reaches $80B run-rate in FY26 and merits 11x, add $125B EV = $10/share.
- **Waymo upside:** $150B peg is Alphabet's own February 2026 implied mark. Bulls argue $250B+ if robotaxi scales. Max additional $8/share.
- **Search downside:** 5.5x may still be generous if AI Overviews cannibalize without full monetization. Every 0.5x compression = $112B EV = $9/share.
- **Network downside:** $29.8B segment at 2.5x assumes AdX survives. If Judge Brinkema forces divestiture, value could drop to 1.5x or be effectively orphaned.

Even adding generous Cloud and Waymo upside ($18/share) and discounting the Search/Network downside (flat), SoP still clears only ~$200/share — below the trading comps base case.

---

## METHOD 6 — QUALITY EQUITY FLOOR (LBO PROXY)

**Reframe:** $3.88T cannot be LBO'd. Instead, solve for: "What's the current price that delivers a 10% annualized equity return over 5 years if the base case plays out?"

### Setup
- Base case Year 5 revenue: $654B
- Exit multiple: 6.0x NTM Revenue (in-line with peer median)
- Exit EV: $3,926B
- 5-year cumulative FCF (base case): $505B
- Exit equity value: $4,511B → **$369/share in 5 years**

### Required Entry

| Target IRR | Required Entry Price | Implied (Down)side |
|---|:---:|:---:|
| 8% | $251 | -20.9% |
| **10%** | **$229** | **-27.8%** |
| 12% | $209 | -34.1% |

**Implied 5-year IRR at $317.25: only 3.1%** — well below the risk-free rate. An equity investor at current price is accepting sub-Treasury returns for mega-cap equity risk.

**Floor reference: $229** (10% IRR requirement). Weight: 5%.

---

## TRIANGULATION

### Method Results Table

| Method | Bear | Base | Bull | Weight | Confidence |
|---|---:|---:|---:|:---:|:---:|
| Reverse DCF | — | *14.9% implied CAGR vs 11% consensus = market is pricing acceleration* | — | signal only | H |
| Forward DCF | $103 | $170 | $268 | 45% | H |
| Trading Comps | $230 | $248 | $267 | 40% | H |
| M&A Comps | — | — | — | 0% | N/A |
| Sum-of-Parts | $165 | $183 | $201 | 10% | M |
| Quality Floor (LBO) | $229 | — | — | 5% | M |

### Triangulated Price Target

| Scenario | Price | vs. Current |
|---|:---:|:---:|
| **Bear** | **$166** | **-47.7%** |
| **Base** | **$203** | **-35.9%** |
| **Bull** | **$261** | **-17.8%** |

### Method Disagreement Explained

There is a **$78 gap** between Forward DCF base ($170) and Trading Comps base ($248). This is real and should not be averaged away.

- **DCF says $170:** Reflects the mechanical reality that $175-185B 2026 capex cuts FY26 FCF to ~14% margin, and margin recovery takes 3-4 years. Discounted fairly, near-term cash flow compression is punitive.
- **Comps says $248:** Reflects the reality that mega-cap software peers trade at rich multiples regardless of DCF mechanics. The market pays for optionality, moat, and scale in ways a 7-year DCF cannot capture.

**Both are correct within their frames. Both say the stock is overvalued.** The DCF sets the floor ($170), the comps set the "fair multiple" ceiling ($248-267), and the triangulated base at $203 reflects both.

### Conviction Score

**CONVICTION: 4 / 5** (High conviction overvalued)

**Rationale:**
1. All four working methods (DCF, Comps, SoP, LBO floor) converge on "overvalued" — no method produces a base case above $250.
2. The reverse DCF signal is unambiguous: market implies 14.9% 10Y CAGR vs. ~11% consensus trajectory.
3. The stock has re-rated +15% in six days (7.3x → 8.35x NTM Rev) without a corresponding fundamental catalyst — this is multiple expansion, not earnings revision.
4. Binary downside risk is elevated and near-term: Judge Brinkema AdX remedy ruling is imminent per sector handoff.
5. The reason the score isn't 5: (a) Cloud could genuinely surprise to the upside; (b) Waymo optionality is real and under-modeled; (c) GOOGL has historically rewarded patient holders even at expensive entry points; (d) Q1 2026 earnings (Apr 29) could reset the narrative either direction.

---

## KEY RISKS & CATALYSTS

### Near-term (next 90 days)
| Date / Window | Event | Direction |
|---|---|---|
| **IMMINENT** | Judge Brinkema AdX remedy ruling | Binary — downside if divestiture ordered |
| **April 29, 2026** | Q1 2026 earnings | Two-way volatility; consensus $100.8B rev / $2.62 EPS |
| ~May 2026 | Google I/O (Gemini roadmap) | Upside if Gemini 3 demos surprise |

### Structural risks
- **AI search disruption:** AI Overviews on 48% of queries; 25.5% carry ads (up from 5.2% in early 2025); monetization gap remains
- **DOJ search remedy:** Morgan Stanley $15-25B annual revenue at risk from choice screens
- **2026 capex:** $175-185B guide (~2x FY25) compresses near-term FCF mechanically
- **Apple TAC exposure:** ~$20B/yr Safari default payment at risk
- **Supreme Court search appeal:** 2027-2028 timeline, outcome undefined

### Upside optionality
- **Cloud acceleration:** Q4 +48%, exiting at $70B+ run-rate; path to $100B by 2027
- **Waymo scaling:** $16B February raise at implied $150B+ valuation; robotaxi unit economics improving
- **Gemini integration:** 750M+ Gemini App MAU; pricing power across Workspace/Cloud bundle

---

## OPTIONS WHEEL HANDOFF

```
━━━ STOCK VALUATION → OPTIONS WHEEL HANDOFF ━━━━━━━━━━━━━
TICKER:                 GOOGL
COMPANY:                Alphabet Inc.
SECTOR:                 Digital Advertising / AdTech (Walled Garden)
VALUATION DATE:         April 12, 2026

PRICE TARGET:           $203 base ($166 bear — $261 bull)
CURRENT PRICE:          $317.25
UPSIDE TO BASE:         -36.0% (NEGATIVE)
CONVICTION:             4 / 5 (high conviction OVERVALUED)

WHEEL STRATEGY IMPLICATIONS:

- SELL PUTS:            NO
  Rationale:            Current price is $114 ABOVE base case fair
                        value and $56 above the bull case of the
                        Forward DCF. Selling puts means accepting the
                        risk of assignment near current levels —
                        locking in a cost basis that every valuation
                        method says is overvalued. Negative expected
                        value.
  Strike zone:          DO NOT SELL puts above $205 (base case PT)
                        Acceptable put zone: $200-$220 ONLY IF the
                        stock corrects 30%+ and the sector handoff
                        thesis is re-verified post-correction.

- COVERED CALLS:        YES (if currently long)
  Rationale:            Stock is above every method's base case.
                        Writing calls harvests premium while the
                        market re-rates back toward fair.
  Minimum strike:       Cost basis (if recently acquired)
                        OR $275 (above SoP upside, below bull DCF)
  Suggested zone:       $330-$360 (1-3 months out)
                        Above $360 = let it run for IRS/tax reasons
                        or if you want to keep shares.
  Do NOT sell calls:    Above $400 (roughly bull case +50%)

- CONCENTRATED LONG:    NO
  Rationale:            Requires conviction ≥4 AND upside to base
                        case ≥30%. Conviction passes (4), but upside
                        is NEGATIVE 36%. Disqualified.

KEY DATES TO AVOID (no new positions):
- IMMINENT:  Judge Brinkema ad-tech remedy ruling (binary AdX event)
- April 29:  Q1 2026 earnings
- ~May:      Google I/O (typically mid-May)

SECTOR CONTEXT:
- Sector score:         22/25 (Rank 4 of 18)
- Business quality:     Top-tier — this is a hold-the-business verdict
                        with a wrong-the-price verdict
- Sector-level flag:    Walled gardens must use mega-cap software
                        comps (5-10x NTM Rev). GOOGL at 8.35x is
                        above peer median 6.8x. Re-rated +14% since
                        sector handoff six days ago.
- Antitrust risk:       Both GOOGL and MGNI have direct exposure to
                        the Brinkema ruling — but in opposite
                        directions. MGNI is a PASS long beneficiary;
                        GOOGL is the share-donor.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## APPENDIX — FULL REVERSE DCF SENSITIVITY

**Implied 10-year revenue CAGR required to justify $317.25:**

| WACC \ Terminal FCF Margin | 20% | 25% | 30% | 35% |
|---|:---:|:---:|:---:|:---:|
| 8.5% | 14.9% | 12.4% | 10.3% | 8.7% |
| 9.5% | 17.5% | 14.9% | 12.8% | 11.1% |
| 10.5% | 19.9% | 17.2% | 15.1% | 13.3% |
| 11.5% | 22.1% | 19.3% | 17.1% | 15.3% |

**Only the 8.5% WACC + 35% terminal margin corner (extremely bullish on both axes) produces an implied CAGR (8.7%) below the consensus 10Y fade. Every other corner requires growth well above consensus.**

---

## APPENDIX — KEY DATA SOURCES

| Source | Used For |
|---|---|
| V1 GOOGL Dossier (Apr 12, 2026) | All financials, guidance, share count, segment data |
| AdTech Sector Handoff v2 (Apr 6, 2026) | Peer multiples, moat scoring, sector context, antitrust risk |
| Q4 2025 8-K (filed Feb 4, 2026) | FY25 P&L, balance sheet, cash flow |
| Sector Handoff walled-garden benchmarks | Mega-cap software comp set (META/MSFT/AMZN) |

**V1 gaps flagged that affect this valuation:**
- FY2025 10-K segment detail ⚠️ single-sourced (Bullfincher) — Search/YouTube/Network splits used in SoP should be verified against MD&A
- FY2026/27/28 consensus ⚠️ directional only — point estimates used
- Google Cloud RPO/backlog [NOT FOUND] — would tighten Cloud segment multiple
- Waymo standalone valuation data limited to Feb 2026 $16B raise anchor

These gaps are MEDIUM impact — they affect SoP precision by perhaps $10-15/share, but do not change the direction of the verdict.

---

*End of V2 valuation report. Base case price target $203. Current price $317.25. Conviction 4/5. Do not sell puts. Covered calls on existing positions. No concentrated long entry.*
