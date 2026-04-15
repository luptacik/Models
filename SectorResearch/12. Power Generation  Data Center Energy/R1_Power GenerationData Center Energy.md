# Power Generation / Data Center Energy: R1 Sell-Side Landscape Sweep

**Bottom line: Data center power demand is the defining infrastructure megatrend of this decade.** Global data center electricity consumption will roughly double from ~415 TWh (2024) to ~945 TWh by 2030 (IEA base case), driven by AI workloads that consume **10x the power** of traditional compute per rack. Hyperscaler capex will exceed **$600B in 2026 alone** — 75% AI-related — creating unprecedented demand visibility for power generation, electrical equipment, and cooling companies. The binding constraint has shifted from GPU supply to power infrastructure: transformer lead times exceed **128 weeks**, grid interconnection queues hold **2,600 GW** of backlog, and **$64B in data center projects** have been blocked or delayed by community opposition. Natural gas is the only viable near-term solution (2025–2030); nuclear represents the long-term play (2030+); and equipment suppliers (Vertiv, Eaton, Schneider Electric, GE Vernova) hold pricing power not seen in a generation.

---

## 1. MARKET STRUCTURE

### TAM sizing: Sources diverge by up to 5x but direction is unanimous

**Global data center power demand forecasts:**

| Source | 2024 Baseline | 2030 Forecast | CAGR | Notes |
|--------|--------------|---------------|------|-------|
| **IEA** (Apr 2025) | ~415 TWh | ~945 TWh | ~15% | Base case; widely cited as consensus anchor |
| **Goldman Sachs** | ~59 GW | ~122 GW | ~13% | 165% capacity increase vs. 2023 |
| **McKinsey** | 25 GW (U.S.) | 80+ GW (U.S.) | ~19-22% | $1.7T cumulative DC infrastructure capex by 2030 |
| **S&P Global / 451 Research** | 50.5 GW (U.S.) | 134.4 GW (U.S.) | ~11% (TWh) | U.S. demand to nearly triple |
| **Gartner** (Nov 2025) | 448 TWh | 980 TWh | ~17% | AI-optimized servers: 93→432 TWh |
| **BloombergNEF** (Dec 2025) | ~25 GW (U.S. operating) | 106 GW (U.S. by 2035) | N/A | 36% higher than prior estimate |

**⚠️ MATERIAL DISAGREEMENT:** U.S. 2030 data center electricity consumption estimates range from **200 TWh to over 1,050 TWh** — a 5x spread. Consensus clusters at **300–600 TWh** for U.S. and **945–1,587 TWh** globally. London Economics cautioned that meeting all announced U.S. data center load by 2030 would require **90% of global chip supply** — likely unrealistic.

**Data center power equipment/infrastructure market ($B):**

| Segment | 2025 Size | 2030 Forecast | CAGR | Source |
|---------|-----------|--------------|------|--------|
| DC Power Equipment (UPS, PDU, switchgear, gensets) | $22–35B | $43–51B | 7–13% | MarketsandMarkets, Grand View, Mordor Intelligence |
| DC Cooling Market | $16–22B | $40–56B | 11–16% | MarketsandMarkets, Grand View |
| DC Construction (global) | $228–271B | $388–517B | 7–9% | Multiple |
| Green Data Center Market | $48B | $156B | 26% | MarketsandMarkets |

McKinsey's comprehensive view: **$5.2T total AI data center investment by 2030** — 60% technology/chips ($3.1T), 25% energy/power/cooling ($1.3T), 15% construction ($800B).

### Top 5 growth drivers (quantified)

**1. AI training/inference power demand.** GPU rack power density has exploded: NVIDIA GB200 NVL72 racks draw **132–140 kW** (vs. 8–15 kW traditional). Next-gen Vera Rubin NVL144 targets **~600 kW per rack**. AI workloads will represent **~70% of total data center demand by 2030** (McKinsey). AI-optimized server electricity grows from 93 TWh (2025) to **432 TWh** (2030) — nearly 5x (Gartner).

**2. Hyperscaler capex explosion.** Top 5 hyperscaler capex: **~$256B (2024) → ~$443B (2025) → ~$602B (2026)** (CreditSights, MUFG). Goldman Sachs projects **$1.15T cumulative 2025–2027**. Amazon targets ~$200B in 2026, Alphabet ~$175–185B, Microsoft ~$120B+, Meta ~$115–135B. Hyperscaler capex now equals **2.2% of U.S. GDP**.

**3. Colocation expansion at record pace.** North America vacancy at record low **1.4%** (CBRE H2 2025). Under construction: **35+ GW** with **73–92% preleased**. Asking rents $195.94/kW/month (+6.5% YoY). Texas could overtake Northern Virginia as world's largest data center market by 2030.

**4. Sovereign AI initiatives.** McKinsey estimates sovereign AI market could reach **$500–600B globally by 2030**. France: €109B AI investment. Saudi Arabia: $18B data center strategy, up to $1T total pledge. UAE Stargate: 5 GW campus. Data sovereignty laws create per-country demand multipliers.

**5. Inference distribution driving geographic expansion.** AI inference expected to be **75% of total AI energy demand by 2030** (IEA). Requires geographic distribution for latency reduction, driving expansion into secondary/tertiary markets. 64% of capacity under construction is in frontier markets (JLL).

### Top 3 headwinds

**1. Grid interconnection delays (MOST CRITICAL).** U.S. generation interconnection queue holds **~2,600 GW** — more than 2x total installed capacity. Median time from request to operation: **~5 years** (up from <2 years in 2000s). Only **13% of capacity** entering queues 2000–2019 reached commercial operation. Grid-connection wait times in primary markets **exceed 4 years**; some developers seeing **7-year delays**.

**2. Equipment supply constraints.** Power transformer lead times: **128 weeks (~2.5 years)**; GSU transformers: **144 weeks (~2.8 years)** (Wood Mackenzie). Supply deficit: **30% shortfall** for power transformers, **47% for GSUs**. GSU demand up **274%** since 2019. Gas turbine lead times: **5–7 years** for heavy-duty units. GE Vernova expects sold out through 2030 by end of 2026.

**3. NIMBYism and permitting bottlenecks.** **$64B in U.S. data center projects blocked or delayed** in past two years (Data Center Watch). Only **44% of Americans** would welcome a data center nearby. First time since 2020 that primary-market construction pipeline **shrank**. Water cited in >40% of contested projects. 300+ state data center bills filed across 30+ states in first 6 weeks of 2026.

---

## 2. SUB-SECTOR MAP

### A) Nuclear Power (conventional fleet + SMR/advanced nuclear)

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | Existing fleet: ~$50–60B annual revenue. DC-specific nuclear: ~$460M (2024) → $1.62B by 2031 (19.5% CAGR). SMR market: $5.96B (2025) → $8.77B by 2034 |
| **Growth vs. sector** | **FASTER** — Unprecedented renaissance driven by DC PPAs |
| **Maturity** | **MATURE** (existing fleet) / **EMERGING** (SMR) |
| **Competitive structure** | **CONSOLIDATING** — Constellation dominates after Calpine merger (55 GW) |
| **Platform vs. point** | Constellation (CEG) winning as fleet-scale platform; GE Vernova Hitachi closest SMR platform |

**Top public players:** Constellation Energy (CEG, NASDAQ, ~$100–118B), GE Vernova (GEV, NYSE, ~$230B — also gas turbines), BWX Technologies (BWXT, NYSE, ~$19B), Cameco (CCJ, NYSE, ~$47B), Oklo (OKLO, NYSE, ~$9B), NuScale (SMR, NYSE, ~$3.7B), Talen Energy (TLN, NASDAQ, ~$18B).

**Top private players:** Kairos Power (Google 500 MW PPA), X-energy (Amazon/Dow partnerships), TerraPower (Bill Gates, $3.4B funding), Holtec International, Rolls-Royce SMR Ltd (UK).

**Key DC nuclear PPAs confirmed:** Microsoft-Constellation (835 MW TMI restart, 20-yr), Amazon-Talen (1,920 MW Susquehanna), Meta-Constellation (1.1 GW Clinton), Google-Kairos (500 MW by 2035), Equinix-Oklo (500 MW). **No commercial SMR will be online before ~2029–2030.** HALEU fuel supply is the critical bottleneck.

### B) Natural Gas Power Generation

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | ~$100B+ (equipment + EPC + services). 252 GW gas-fired capacity in U.S. development (~$416B capex). BTM gas for DCs: 56 GW across 46+ identified projects |
| **Growth vs. sector** | **FASTER** — Gas turbine orders at record levels; Siemens sold 194 turbines in 2025 (vs. 100 in 2024) |
| **Maturity** | **GROWTH** — Mature technology, massive new demand wave |
| **Competitive structure** | **OLIGOPOLY** — 3 major OEMs (GE Vernova, Siemens Energy, Mitsubishi Heavy) |
| **Platform vs. point** | GE Vernova winning as platform spanning gas + grid + nuclear |

**Top public players:** GE Vernova (GEV, NYSE, ~$230B, $38B rev, 150B backlog), Siemens Energy (ENR.DE, ~$141B, €146B backlog), Mitsubishi Heavy (7011.T, TSE, ~$102B), Baker Hughes (BKR, NYSE, ~$50B), Bloom Energy (BE, NYSE — fuel cells as gas alternative).

**Key BTM projects:** Oracle/OpenAI Stargate (Abilene, 2.3 GW+), Meta Hyperion (Louisiana, 5 GW), xAI Colossus (Memphis, 500 MW+), Meta Socrates (Ohio, 200 MW). **Gas turbine lead times: 5–7 years** for heavy-duty units.

### C) Renewable Energy / Battery Storage for Data Centers

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | Renewable DC PPAs: ~$6.4B (2024) → $36B by 2033 (18.7% CAGR). DC BESS: ~$1.6–3.4B (2024). Combined: ~$8–10B currently |
| **Growth vs. sector** | **FASTER** — BESS grew 44% in 2024. U.S. BESS 57 GWh in 2025 (+29% YoY) |
| **Maturity** | **GROWTH** (PPAs) / **EMERGING** (BESS for DCs) |
| **Competitive structure** | **FRAGMENTED** (trending consolidating) |
| **Platform vs. point** | NextEra, AES, TotalEnergies evolving into bundled "clean firm power" platforms |

**Top public players:** NextEra Energy (NEE, NYSE, ~$160B), AES Corp (AES, NYSE, ~$10B, 11.1 GW PPA backlog), Tesla (TSLA — energy storage $12.77B rev in 2025), Fluence Energy (FLNC, NASDAQ, ~$2B), First Solar (FSLR, NASDAQ).

**Hyperscaler procurement scale:** Microsoft: 34.7 GW contracted. Amazon: ~35 GW. Meta: 10.24 GW in 2025 alone. Combined: **84+ GW of clean energy** contracted across 29 markets.

### D) Fuel Cells / Distributed Generation

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | $0.5–2B currently → $4–12B by 2030–2034. Goldman Sachs: 6–15% of incremental DC power through fuel cells = 8–20 GW by 2030 |
| **Growth vs. sector** | **FASTER** (significantly) — Bloom Energy grew 37% in 2025, guiding 50%+ in 2026 |
| **Maturity** | **EMERGING → Early GROWTH** |
| **Competitive structure** | **MONOPOLY-ESQUE** — Bloom Energy dominant (~90%+ of commercial FC deployments in U.S. DCs) |
| **Platform vs. point** | Bloom winning as platform with islanded microgrids, heat capture, hydrogen pathway |

**Top public players:** Bloom Energy (BE, NYSE, ~$39B, $2.02B rev, **~$20B total backlog**), FuelCell Energy (FCEL, NASDAQ, ~$500M, $158M rev), Plug Power (PLUG, NASDAQ, ~$2B — financially distressed), Cummins (CMI, NYSE — Accelera segment writing down hydrogen).

**Critical Bloom partnerships:** Brookfield ($5B strategic partnership), AEP (1 GW procurement), Equinix (100+ MW across 19 DCs), Oracle, CoreWeave. Bloom deploys in **90 days** vs. 2–5 years for grid connection — key "time to power" advantage.

### E) Electrical Equipment & Power Distribution

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | $22–35B (2025) → $43–51B (2030). Components: UPS ~$8.8B, PDU ~$2.8B, switchgear ~$2.2–5.6B. Power systems = ~49% of DC auxiliary equipment market |
| **Growth vs. sector** | **FASTER** — UPS 7–15% CAGR, switchgear 8–16% CAGR |
| **Maturity** | **GROWTH** (new architectures emerging: 800V HVDC, SiC UPS) |
| **Competitive structure** | **CONSOLIDATING** — Top 5 hold ~41–43% of DC power market |
| **Platform vs. point** | Schneider (EcoStruxure), Eaton ("chip-to-grid"), Vertiv (NVIDIA partnership) all winning as platforms |

**Top public players:** Eaton (ETN, NYSE, ~$140B, ~$25B rev), Vertiv (VRT, NYSE, ~$100B, $10.2B rev), Schneider Electric (SU.PA, ~$148B), ABB (ABBN.SW, ~$168B), Siemens (SIE.DE, ~$188B), Hubbell (HUBB, NYSE, ~$25B), nVent (NVT, NYSE, ~$19B), SPX Technologies (SPXC, NYSE, ~$10B), Legrand (LR.PA, ~$33B), Powell Industries (POWL, NASDAQ, ~$6.5B).

**Transformer crisis:** **30% supply shortfall** for power transformers. Lead times 128 weeks. Prices up **77%** since 2019. Demand up **274%** for GSUs. **55% of U.S. distribution transformers** past expected service life. $1.8B in announced manufacturing expansions but supply growing 3–4% vs. 7–9% demand growth.

### F) Data Center Cooling

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | Total DC cooling: ~$16–22B (2025) → $40–56B by 2030 (11–16% CAGR). Liquid cooling: ~$3B (2025), **roughly doubled in 2025**, → $7B by 2029 (Dell'Oro) |
| **Growth vs. sector** | **FASTER** — Liquid cooling 20–40% CAGR. Vertiv liquid cooling revenue doubled in Q1 2025 |
| **Maturity** | **MATURE** (air/HVAC) / **EMERGING** (liquid/immersion) |
| **Competitive structure** | **CONSOLIDATING** (rapidly) — Massive M&A wave absorbing independents |
| **Platform vs. point** | Vertiv winning via NVIDIA reference architecture; Eaton (Boyd) creating "chip-to-grid"; Schneider (Motivair) for EcoStruxure integration |

**Top public players:** Vertiv (VRT, NYSE), Schneider Electric (SU.PA), Eaton (ETN — via Boyd Thermal acquisition), Carrier (CARR, NYSE, ~$60B), Johnson Controls (JCI, NYSE, ~$55B), Modine (MOD, NYSE, ~$8B, DC revenue up **119%**), Trane Technologies (TT, NYSE, ~$85B), AAON (AAON, NASDAQ, ~$8B — BASX brand DC cooling up 143%), Munters Group (MNTR.ST, ~$2.5B).

**AI driving liquid cooling:** Air cooling fails above ~15 kW/rack. NVIDIA Blackwell Ultra at 140 kW/rack. Next-gen Vera Rubin: 600 kW+. Liquid cooling reduces energy consumption **30–50%** vs. air. Google: ~1 GW liquid cooling deployed.

### G) Independent Power Producers / Utilities with DC Exposure

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | $20–40B+ annual revenue opportunity at wholesale power prices. Approaching 8–10% of total U.S. electricity market |
| **Growth vs. sector** | **FASTER** — DC power demand ~15% CAGR vs. total electricity 1–2% |
| **Maturity** | **GROWTH** — Sector being reshaped by hyperscaler demand |
| **Competitive structure** | **CONSOLIDATING** — $141.9B in utility deal value in 12 months to Nov 2025 |
| **Platform vs. point** | Constellation winning as "one-stop shop for the global data economy" |

**Top public players:** Constellation Energy (CEG, ~$100–118B, 55 GW fleet), Vistra (VST, NYSE, ~$55B, ~50 GW), Talen Energy (TLN, ~$18B), NRG Energy (NRG, NYSE, ~$25B), **Solaris Energy Infrastructure (SEI, NYSE, ~$4.2B** — BTM gas modular power, 67% of orderbook is xAI, targeting 3.1 GW by 2029), AES (AES, NYSE, ~$10B), NextEra (NEE), Duke Energy (DUK), Dominion (D), Southern Company (SO), Entergy (ETR).

### H) Natural Gas Infrastructure

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | DC-driven gas demand: 3–10+ Bcf/d by 2030 (wide range). DC-specific infrastructure: ~$30–50B+ through 2030. North America needs ~40,000 miles of new pipeline |
| **Growth vs. sector** | **FASTER** — Midstream capex up 61% in 2025 |
| **Maturity** | **GROWTH** (within mature industry) |
| **Competitive structure** | **CONSOLIDATING** — Top 5 hold ~62% of revenue |
| **Platform vs. point** | Williams (WMB) winning with "wellhead-to-watt" model: pipeline + power gen + gas trading |

**Top public players:** Williams Companies (WMB, NYSE, ~$75B, **$5.1B committed to DC power projects**), Kinder Morgan (KMI, NYSE, ~$55B, ~40% of U.S. gas), EQT Corp (EQT, NYSE, ~$25B, largest U.S. gas producer), Energy Transfer (ET, NYSE, ~$60B), Enbridge (ENB, NYSE, ~$95B).

### I) Uranium / Nuclear Fuel Cycle

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | ~$10–12B annual uranium market. Total fuel cycle ~$25–30B. Structural supply deficit: ~50M lbs/yr (28% shortfall) |
| **Growth vs. sector** | **FASTER** — Spot uranium surged to >$100/lb in Jan 2026 |
| **Maturity** | **GROWTH** — Nuclear renaissance driving demand; WNA projects capacity nearly doubling to 746 GWe by 2040 |
| **Competitive structure** | **CONSOLIDATING** (quasi-duopoly at top in mining; near-monopoly for Western enrichment) |

**Top public players:** Cameco (CCJ, NYSE, ~$47.8B), Kazatomprom (KAP.IL, LSE, ~$13B — world's #1 producer), NexGen Energy (NXE, NYSE, ~$5B), Uranium Energy Corp (UEC, NYSE-A, ~$4B), Centrus Energy (LEU, NYSE-A, ~$4B — sole U.S. HALEU producer), Energy Fuels (UUUU, ~$2B), Denison Mines (DNN, ~$3B), Paladin Energy (PDN.AX, ~$3B), BWX Technologies (BWXT — nuclear fuel fabrication).

### J) Power Semiconductors / Power Management ICs

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | Total power semi market: ~$53–57B (2025). DC-specific: ~$534M (2024) → $1.24B by 2031 (11% CAGR). Content per rack: $50K → $105K by 2030 |
| **Growth vs. sector** | **FASTER** — DC power semis 11%+ CAGR; SiC/GaN growing faster still |
| **Maturity** | **GROWTH** — SiC and GaN disrupting incumbent silicon |
| **Competitive structure** | **CONSOLIDATING** — Top 5–6 dominate |

**Top public players:** Infineon (IFX.DE, XETRA, ~$50B — #1 global, partnered with NVIDIA on 800V HVDC), ON Semiconductor (ON, NASDAQ, ~$25B — SiC + emerging V-GaN), Monolithic Power Systems (MPWR, NASDAQ, ~$40B — projected ~70% share on NVIDIA Vera Rubin [UNVERIFIED]), Texas Instruments (TXN, NASDAQ, ~$180B), Analog Devices (ADI, NASDAQ, ~$100B), STMicroelectronics (STM, NYSE, ~$20B), Wolfspeed (WOLF, NYSE, ~$1.5B — pure-play SiC).

### K) EPC / Engineering & Construction

| Attribute | Value |
|-----------|-------|
| **Sub-TAM** | DC construction: $228–271B (2025) → $388–517B by 2030–2034 (7–9% CAGR). U.S. DC construction capital: record $31.5B in 2024 |
| **Growth vs. sector** | **FASTER** — Sterling 125% YoY DC revenue growth; Comfort Systems DC at 45% of revenue |
| **Maturity** | **GROWTH** — Capacity-constrained; labor is the binding constraint |
| **Competitive structure** | **FRAGMENTED** — Top 5 hold only ~12% of global market |

**Top public players:** Quanta Services (PWR, NYSE, ~$60B, $39.2B backlog), EMCOR Group (EME, NYSE, ~$35B, $11.75B backlog), Comfort Systems (FIX, NYSE, ~$55B, **$12B backlog — doubled YoY**), MasTec (MTZ, NYSE, ~$15B), Sterling Infrastructure (STRL, NASDAQ, ~$13B), IES Holdings (IESC, NASDAQ, ~$9B), Fluor (FLR, NYSE, ~$12B), MYR Group (MYRG, NASDAQ, ~$3B).

**Top private:** Bechtel, Black & Veatch, DPR Construction, Turner Construction, Holder Construction, Kiewit.

---

## 3. REGULATORY ENVIRONMENT

| Regulation | Jurisdiction | Status/Effective Date | Impact | Driver/Drag |
|-----------|-------------|----------------------|--------|-------------|
| **NRC SMR Licensing Reform** (ADVANCE Act + EOs) | U.S. Federal | Active; EOs signed May 23, 2025. 18-month licensing mandate | **HIGH** | Budget Driver |
| **FERC Order 2023** (Interconnection Reform) | U.S. Federal | Effective Nov 2023; compliance ongoing | **HIGH** | Mixed |
| **FERC PJM Co-Location Order** | U.S. Federal | Issued Dec 18, 2025 | **HIGH** | Budget Driver |
| **IRA Nuclear PTC (45U)** | U.S. Federal | Preserved through 2032 under OBBBA | **HIGH** | Budget Driver |
| **IRA Clean Electricity PTC/ITC (45Y/48E) — Wind/Solar** | U.S. Federal | Must begin construction by ~July 2026 or placed in service by Dec 2027 (curtailed under OBBBA) | **HIGH** | Mixed |
| **IRA Nuclear/Geo/Battery ITC (48E)** | U.S. Federal | Begin construction by end of 2033; 10% nuclear community adder | **HIGH** | Budget Driver |
| **IRA 45V Clean Hydrogen** | U.S. Federal | Construction before Jan 1, 2028 (shortened from 2032) | **MEDIUM** | Cost Drag (for green H2) |
| **EPA GHG Standards Repeal** | U.S. Federal | Proposed repeal June 2025; Endangerment Finding rescission finalized Feb 2026 | **HIGH** | Budget Driver (for fossil gen) |
| **State DC Moratoriums** | VA, GA, OK, NY, SD, VT, MD, MI, etc. | 300+ bills filed across 30+ states in 2026; no statewide moratorium enacted yet | **MEDIUM-HIGH** | Cost Drag |
| **Virginia Tax Exemption** | Virginia | $1.6B/yr at risk; special budget session Apr 23, 2026 | **HIGH** | Cost Drag (if rolled back) |
| **EU Energy Efficiency Directive** | EU-27 | Reporting active since Sept 2024; Performance Standards Q2 2026 | **MEDIUM** | Cost Drag |
| **NERC Large Load Alert** | U.S./Canada | Level 2 Alert Sept 2025; new reliability standard expected 2026 | **MEDIUM-HIGH** | Mixed |
| **Trump Nuclear EOs** | U.S. Federal | Signed May 23, 2025; goal: 400 GW nuclear by 2050 | **HIGH** | Budget Driver |
| **Texas SB 6** (Large Load) | Texas | 2025 | **MEDIUM** | Mixed |

**Net regulatory effect: MIXED, tilting TAILWIND for power generation; more HEADWIND for pure-play DC operators.** Nuclear regulatory support is the strongest in 50+ years. Fossil generation deregulation improves gas plant economics. But state-level backlash against data centers is accelerating — $4B+ in tax exemptions at risk in Virginia and Georgia alone.

---

## 4. M&A ACTIVITY (April 2024 – April 2026)

### Major Deals

| Acquirer | Target | Price | Date | Strategic Rationale |
|----------|--------|-------|------|---------------------|
| Constellation Energy | Calpine Corp | $26.6B EV | Jan 2025 → closed Jan 2026 | Creates 55 GW national platform (nuclear + gas + geothermal) |
| NRG Energy | LS Power gas portfolio + CPower | ~$12.0B EV | May 2025 | Adds 13 GW gas + 6 GW VPP; doubles NRG capacity |
| Blackstone Infrastructure | TXNM Energy | $11.5B | May 2025 | PE bet on regulated utility in TX/NM for DC load growth |
| Eaton | Boyd Thermal | $9.5B (22.5x EBITDA) | Nov 2025 | "Chip-to-grid" — adds $1.5B liquid cooling revenue |
| GE Vernova | Prolec GE (remaining 50%) | $5.275B | Dec 2025 | Full control of leading North American transformer manufacturer |
| Ecolab | CoolIT Systems | $4.75B (29x NTM EBITDA) | Mar 2026 | Pure-play D2C liquid cooling platform |
| Alphabet/Google | Intersect Power | $4.75B | Dec 2025 | Hyperscaler acquires multi-GW clean energy developer |
| Eaton | Fibrebond Corp | $1.4B | Mar 2025 | Modular power enclosures for hyperscale DC |
| Legrand | Avtron Power | $1.12B | Oct 2025 | Load bank testing for DC power infrastructure |
| Vertiv | PurgeRite | ~$1.0B | Dec 2025 | Fluid management for liquid cooling systems |
| Schneider Electric | Motivair (75% stake) | $850M | Oct 2024 → Sept 2025 | Liquid cooling CDUs and cold plates |
| AWS/Amazon | Talen Cumulus campus | $650M | Mar 2024 | Nuclear-adjacent 960 MW DC campus |
| AIP/BlackRock/GIP/MGX | Aligned Data Centers | $40B | Oct 2025 | Largest-ever data center deal |
| Trane Technologies | LiquidStack + Stellar Energy Digital | Undisclosed | Feb–Dec 2025 | "Central plant to chip" thermal management |
| Daikin | Chilldyne | Undisclosed | Aug 2025 | Direct-to-chip negative-pressure CDU tech |
| Johnson Controls | Alloy Enterprises | Undisclosed | Feb 2026 | Direct liquid cooling components |

### Active acquirers
**Eaton** (most aggressive — ~$12.3B+ deployed), **Legrand** (6+ acquisitions in 24 months), **Constellation Energy** ($26.6B Calpine), **Trane Technologies** (assembling end-to-end cooling platform), **Vertiv** (selective gap-filling).

### Likely next acquisition targets
**Modine Manufacturing** (subscale cooling, logical for Vertiv/Schneider), **nVent Electric** (DC power/cooling, bolt-on for larger platform), **Generac** (backup power), **Bloom Energy** (strategic for utility/hyperscaler), **GRC/Iceotope/Asperitas** (fragmented immersion cooling), **Virginia Transformer/TMC Transformers** (scarce capacity).

---

## 5. PLATFORM CONSOLIDATION DYNAMICS

**Sub-sectors being absorbed into platforms:**

**Liquid cooling** has seen the most dramatic consolidation — nearly every major independent absorbed in 24 months (Boyd→Eaton, Motivair→Schneider, CoolIT→Ecolab, LiquidStack→Trane, Chilldyne→Daikin, JetCool→Flex). Dell'Oro: "The sector grew so rapidly that it attracted too many players. We're now entering a phase where winners emerge and weaker players get absorbed."

**Modular power enclosures** absorbed into electrical equipment platforms (Fibrebond→Eaton). **Dispatchable generation** consolidating into mega-IPPs (Constellation+Calpine = 55 GW, NRG+LS Power).

**Vertical integration examples:**
- **Eaton**: Power distribution + UPS + modular enclosures + liquid cooling (Boyd $9.5B) = "chip-to-grid"
- **Schneider**: UPS + PDUs + switchgear + DCIM software + liquid cooling (Motivair) = "grid-to-chip"
- **Google→Intersect Power**: Hyperscaler backward-integrating into multi-GW energy development
- **GE Vernova→Prolec GE**: Transformer manufacturing vertical integration
- **Williams Companies**: "Wellhead-to-watt" — pipeline + power gen + gas trading for DCs

**Sub-sectors remaining point-solution-dominated:** Nuclear/SMR development (too divergent technically, too regulated), gas turbine OEMs (too large/entrenched), BESS (rapid technology evolution), specialty transformers (extreme supply/demand keeps every producer independent), immersion cooling (still pre-scale).

**Three "one-stop-shop" models emerging:** (1) Power+Cooling Equipment Platform — **Eaton and Schneider winning**; (2) Generation+Customer Platform — **Constellation winning**; (3) Full-Stack Energy Developer — **Google/Intersect emerging**.

Market paying massive premiums: Boyd at 22.5x EBITDA, CoolIT at 29x NTM EBITDA — **2–3x typical industrial valuations**.

---

## 6. MACRO & AI LINKAGES

### Power generation capex in recessions

Regulated electric utilities are broadly **defensive** — S&P 500 Utility Index outperformed broader market in H1 2025 as recession fears emerged. Current U.S. utility capex is in a historic "super-cycle": **$215B in 2025** (+19% YoY), projected **$1.4T from 2025–2030** (Morningstar DBRS) — double the prior 10-year spend. Structural drivers (aging infrastructure, DC demand, electrification) provide a **recession-resistant floor** that did not exist in prior cycles. During 2020 COVID, data center demand **accelerated** counter-cyclically.

**Hyperscaler capex appears recession-resistant** in the near term. Competitive dynamics make pullback "catastrophic" — anyone who stops building loses GPU access, partner relationships, and training capability. However, AI services revenue of ~$25B in 2025 is only ~10% of infrastructure spending; a severe ROI miss could trigger a pullback. BofA notes: "The U.S. would be close to recession this year if it weren't for tech-related spending."

### AI power demand quantification

| Year | Global DC Consumption | Key Data |
|------|----------------------|----------|
| 2024 | ~415 TWh, ~55–59 GW | ~1.5% of global electricity |
| 2026 | ~500+ TWh (est.) | AI = ~20% of DC power |
| 2028 | ~650–750 TWh (est.) | AI = ~40% of DC power [UNVERIFIED] |
| 2030 | **~945 TWh**, ~122 GW capacity | ~3% of global electricity. Equivalent to Japan's total consumption |

**Key AI-driven catalysts:** Stargate Project (10 GW target, $500B, 6+ sites), xAI Colossus (2 GW Memphis), Meta Hyperion (5 GW Louisiana), Google/Intersect (multi-GW), Sovereign AI (UAE 5 GW, Saudi 1.9 GW by 2030).

### Companies that benefit most from AI-driven power demand

**Tier 1 — Highest direct exposure:** Constellation Energy (CEG), GE Vernova (GEV), Vertiv (VRT), Eaton (ETN), Vistra (VST).

**Tier 2 — Critical infrastructure:** Schneider Electric, Bloom Energy (BE), Modine (MOD), Quanta Services (PWR), Comfort Systems (FIX), Cameco (CCJ).

**Tier 3 — Gas/fuel supply:** Williams Companies (WMB), EQT Corp (EQT), Energy Transfer (ET), Solaris Energy (SEI).

---

## 7. COMPREHENSIVE INVESTABLE UNIVERSE

### TIER 1: Pure-Play or >50% DC Energy Exposure, >$500M Market Cap

| Ticker | Company | Primary Sub-Sector | Mkt Cap (~$B) | Exchange | Rev ($B) | Growth | DC Exposure | IBKR |
|--------|---------|-------------------|---------------|----------|----------|--------|-------------|------|
| VRT | Vertiv Holdings | DC Power/Thermal/IT | ~$100 | NYSE | $10.2 | ~28% | Pure-Play | Yes |
| BE | Bloom Energy | Fuel Cells for DC | ~$39 | NYSE | $2.0 | ~37% | Pure-Play | Yes |
| SEI | Solaris Energy Infra | BTM Gas Turbines for DC | ~$4.2 | NYSE | $0.6 | ~99% | Pure-Play | Yes |
| OKLO | Oklo Inc | SMR/Microreactors | ~$9.1 | NYSE | Pre-rev | N/A | Pure-Play | Yes |
| SMR | NuScale Power | SMR Technology | ~$3.7 | NYSE | $0.06 | N/M | Pure-Play | Yes |
| POWL | Powell Industries | Switchgear/Power Control | ~$6.5 | NASDAQ | $1.1 | ~9% | High | Yes |
| MOD | Modine Manufacturing | DC Cooling/Thermal | ~$8.0 | NYSE | $2.7 | ~20% | High (~50%+) | Yes |
| AAON | AAON Inc | DC Precision Cooling (BASX) | ~$8.0 | NASDAQ | $1.2 | ~25% | High (~45%) | Yes |

### TIER 2: Meaningful Exposure (20–50%), >$500M Market Cap

| Ticker | Company | Primary Sub-Sector | Mkt Cap (~$B) | Exchange | Rev ($B) | Growth | DC Exposure | IBKR |
|--------|---------|-------------------|---------------|----------|----------|--------|-------------|------|
| CEG | Constellation Energy | Nuclear IPP / DC PPAs | ~$110 | NASDAQ | $25.5 | ~8% | High | Yes |
| GEV | GE Vernova | Gas Turbines/Grid/Nuclear | ~$230 | NYSE | $35+ | ~10% | High | Yes |
| ETN | Eaton Corp | Electrical Equipment/UPS | ~$140 | NYSE | $25 | ~8% | High | Yes |
| FIX | Comfort Systems USA | DC HVAC/Mechanical Constr | ~$55 | NYSE | $8.5 | ~42% Q4 | High (45% rev) | Yes |
| EME | EMCOR Group | DC Electrical Construction | ~$35 | NYSE | $15 | ~20% | High | Yes |
| TLN | Talen Energy | Nuclear IPP / DC Co-Location | ~$18 | NASDAQ | $4.0 | ~15% | High | Yes |
| STRL | Sterling Infrastructure | DC Site Work/Civil | ~$13 | NASDAQ | $2.2 | ~15% | High | Yes |
| IESC | IES Holdings | DC Electrical Install | ~$9 | NASDAQ | $3.5 | ~25% | High | Yes |
| CCJ | Cameco Corp | Uranium + Westinghouse | ~$48 | NYSE | $2.5 | ~15% | Medium-High | Yes |
| BWXT | BWX Technologies | Nuclear Tech/Components | ~$19 | NYSE | $2.8 | ~12% | Medium-High | Yes |
| MPWR | Monolithic Power Systems | Power Mgmt ICs for DC | ~$40 | NASDAQ | $2.5 | ~34% | Medium-High | Yes |
| NVT | nVent Electric | Power Distrib/Cooling | ~$19 | NYSE | $3.5 | ~10% | Medium-High | Yes |
| LEU | Centrus Energy | Uranium Enrichment/HALEU | ~$4.0 | NYSE-A | $0.45 | ~2% | Medium | Yes |

### TIER 3: Diversified with DC as Growth Driver (<20% but Strategic), >$500M Market Cap

**IPPs / Utilities:**

| Ticker | Company | Mkt Cap (~$B) | Exchange | Rev ($B) | DC Exposure | IBKR |
|--------|---------|---------------|----------|----------|-------------|------|
| VST | Vistra Corp | ~$55 | NYSE | $17.2 | Medium | Yes |
| NRG | NRG Energy | ~$25 | NYSE | $7.0 | Medium | Yes |
| NEE | NextEra Energy | ~$160 | NYSE | $25 | Medium | Yes |
| AES | AES Corp | ~$10 | NYSE | $11 | Medium | Yes |
| DUK | Duke Energy | ~$95 | NYSE | $30 | Medium | Yes |
| D | Dominion Energy | ~$45 | NYSE | $15 | Medium | Yes |
| SO | Southern Company | ~$100 | NYSE | $25 | Medium | Yes |
| ETR | Entergy Corp | ~$35 | NYSE | $13 | Medium | Yes |

**Electrical Equipment / Grid:**

| Ticker | Company | Mkt Cap (~$B) | Exchange | Rev ($B) | DC Exposure | IBKR |
|--------|---------|---------------|----------|----------|-------------|------|
| HUBB | Hubbell Inc | ~$25 | NYSE | $6.0 | Medium | Yes |
| SPXC | SPX Technologies | ~$10 | NYSE | $2.0 | Medium | Yes |
| RRX | Regal Rexnord | ~$10 | NYSE | $6.0 | Low-Medium | Yes |
| APH | Amphenol | ~$90 | NYSE | $17 | Low-Medium | Yes |

**EPC / Construction:**

| Ticker | Company | Mkt Cap (~$B) | Exchange | Rev ($B) | DC Exposure | IBKR |
|--------|---------|---------------|----------|----------|-------------|------|
| PWR | Quanta Services | ~$60 | NYSE | $24 | Medium | Yes |
| MTZ | MasTec Inc | ~$15 | NYSE | $14 | Medium | Yes |
| FLR | Fluor Corp | ~$12 | NYSE | $17 | Medium | Yes |
| MYRG | MYR Group | ~$3 | NYSE | $3.5 | Medium | Yes |

**Cooling / HVAC:**

| Ticker | Company | Mkt Cap (~$B) | Exchange | Rev ($B) | DC Exposure | IBKR |
|--------|---------|---------------|----------|----------|-------------|------|
| CARR | Carrier Global | ~$60 | NYSE | $23 | Low-Medium | Yes |
| TT | Trane Technologies | ~$85 | NYSE | $19 | Medium | Yes |
| JCI | Johnson Controls | ~$55 | NYSE | $24 | Low-Medium | Yes |

**Gensets / Turbines:**

| Ticker | Company | Mkt Cap (~$B) | Exchange | Rev ($B) | DC Exposure | IBKR |
|--------|---------|---------------|----------|----------|-------------|------|
| CAT | Caterpillar | ~$170 | NYSE | $67 | Low-Medium | Yes |
| CMI | Cummins | ~$50 | NYSE | $35 | Low-Medium | Yes |
| GNRC | Generac Holdings | ~$10 | NYSE | $4.0 | Low-Medium | Yes |
| BKR | Baker Hughes | ~$50 | NASDAQ | $28 | Low-Medium | Yes |

**Power Semiconductors:**

| Ticker | Company | Mkt Cap (~$B) | Exchange | Rev ($B) | DC Exposure | IBKR |
|--------|---------|---------------|----------|----------|-------------|------|
| ON | ON Semiconductor | ~$25 | NASDAQ | $7.0 | Medium | Yes |
| TXN | Texas Instruments | ~$180 | NASDAQ | $17 | Low-Medium | Yes |
| ADI | Analog Devices | ~$100 | NASDAQ | $10 | Low-Medium | Yes |
| STM | STMicroelectronics | ~$20 | NYSE | $13 | Low-Medium | Yes |

**Natural Gas Infrastructure:**

| Ticker | Company | Mkt Cap (~$B) | Exchange | Rev ($B) | DC Exposure | IBKR |
|--------|---------|---------------|----------|----------|-------------|------|
| EQT | EQT Corp | ~$25 | NYSE | $6.0 | Low-Medium | Yes |
| WMB | Williams Companies | ~$65 | NYSE | $11 | Medium | Yes |
| KMI | Kinder Morgan | ~$55 | NYSE | $15 | Low-Medium | Yes |
| ET | Energy Transfer | ~$60 | NYSE | $80 | Low-Medium | Yes |
| ENB | Enbridge | ~$95 | NYSE | $35 | Low-Medium | Yes |

**Renewables / Storage:**

| Ticker | Company | Mkt Cap (~$B) | Exchange | Rev ($B) | DC Exposure | IBKR |
|--------|---------|---------------|----------|----------|-------------|------|
| FSLR | First Solar | ~$20 | NASDAQ | $4.5 | Low-Medium | Yes |
| NXT | Nextracker | ~$8 | NASDAQ | $2.5 | Low-Medium | Yes |
| FLNC | Fluence Energy | ~$2 | NASDAQ | $2.7 | Low-Medium | Yes |
| TSLA | Tesla (Energy Storage) | ~$1,200 | NASDAQ | $97 (total) | Low | Yes |

**Uranium / Nuclear Fuel:**

| Ticker | Company | Mkt Cap (~$B) | Exchange | Rev ($B) | DC Exposure | IBKR |
|--------|---------|---------------|----------|----------|-------------|------|
| UEC | Uranium Energy Corp | ~$4.0 | NYSE-A | $0.2 | Medium | Yes |
| NXE | NexGen Energy | ~$5.0 | NYSE | Pre-rev | Medium | Yes |
| DNN | Denison Mines | ~$3.0 | NYSE-A | ~$0.01 | Medium | Yes |
| UUUU | Energy Fuels | ~$2.0 | NYSE-A | $0.3 | Medium | Yes |

**Fuel Cells (non-Bloom):**

| Ticker | Company | Mkt Cap (~$B) | Exchange | Rev ($B) | DC Exposure | IBKR |
|--------|---------|---------------|----------|----------|-------------|------|
| PLUG | Plug Power | ~$2.0 | NASDAQ | $0.6 | Low-Medium | Yes |
| FCEL | FuelCell Energy | ~$0.5 | NASDAQ | $0.16 | Low | Yes |

### TIER 4: Below $500M Market Cap — Watch List

| Ticker | Company | Sub-Sector | Mkt Cap (~$M) | Exchange | Notes | IBKR |
|--------|---------|-----------|---------------|----------|-------|------|
| NNE | NANO Nuclear Energy | Micro-Reactors | ~$800M [UNVERIFIED] | NASDAQ | Pre-revenue; portable/DC nuclear | Yes |
| WOLF | Wolfspeed | SiC Wafers/Devices | ~$1.5B [UNVERIFIED — volatile] | NYSE | $750M CHIPS Act; financial distress risk | Yes |
| NVTS | Navitas Semiconductor | GaN Power ICs | ~$500M | NASDAQ | Revenue collapsed to ~$7M/qtr | Yes |

### INTERNATIONAL NAMES

**European:**

| Ticker | Company | Country | Sub-Sector | Mkt Cap (~$B) | DC Exposure | US ADR | IBKR |
|--------|---------|---------|-----------|---------------|-------------|--------|------|
| SU.PA | Schneider Electric | France | DC Power/Cooling/DCIM | ~$148 | High | SBGSY | Yes (Euronext) |
| ENR.DE | Siemens Energy | Germany | Gas Turbines/Grid | ~$141 | Medium | SMNEY | Yes (XETRA) |
| SIE.DE | Siemens AG | Germany | Switchgear/Automation | ~$188 | Medium | SIEGY | Yes (XETRA) |
| ABBN.SW | ABB Ltd | Switzerland | Electrical Equipment | ~$168 | High | ABB (NYSE) | Yes |
| RR.L | Rolls-Royce Holdings | UK | SMR/Aero Engines | ~$142 | Medium | RYCEY | Yes (LSE) |
| LR.PA | Legrand SA | France | PDUs/Busway/DC Infra | ~$33 | High | LGRDY | Yes (Euronext) |
| MNTR.ST | Munters Group | Sweden | DC Cooling | ~$2.5 | High | None | Yes (OMX) |
| WRT1V.HE | Wärtsilä | Finland | Engines/Power Plants | ~$23 | Low | WRTBY | Yes (Helsinki) |
| PRY.MI | Prysmian Group | Italy | Power Cables | ~$31 | Medium | PRYMY | Yes (MIL) |
| NEX.PA | Nexans SA | France | Power Cables | ~$7 | Medium | NEXXY | Yes (Euronext) |
| ALFA.ST | Alfa Laval | Sweden | Heat Exchangers/Cooling | ~$24 | Medium | ALFVY | Yes (OMX) |
| KAP.IL | Kazatomprom | Kazakhstan | Uranium (#1 global) | ~$13 | Medium | NATKY | Yes (LSE) |

**Japanese:**

| Ticker | Company | Sub-Sector | Mkt Cap (~$B) | DC Exposure | US ADR | IBKR |
|--------|---------|-----------|---------------|-------------|--------|------|
| 7011.T | Mitsubishi Heavy Industries | Gas Turbines/Nuclear | ~$102 | Medium | MHVYF | Yes (TSE) |
| 6501.T | Hitachi Ltd | Grid Equipment/Nuclear | ~$137 | High | HTHIY | Yes (TSE) |
| 6367.T | Daikin Industries | DC Cooling/HVAC | ~$37 | Medium | DKILY | Yes (TSE) |
| 6504.T | Fuji Electric | Power Electronics/UPS | ~$9 | Medium | FELTY | Yes (TSE) |

**Korean:**

| Ticker | Company | Sub-Sector | Mkt Cap (~$B) | DC Exposure | IBKR |
|--------|---------|-----------|---------------|-------------|------|
| 034020.KS | Doosan Enerbility | Nuclear/Gas Turbines | ~$43 | Medium | Yes (KRX) |
| 267260.KS | HD Hyundai Electric | Transformers/Switchgear | ~$18 | High | Yes (KRX) |
| 010120.KS | LS Electric | Switchgear/Power Distrib | ~$6 | Medium | Yes (KRX) |

**Chinese (via Stock Connect or HK):**

| Ticker | Company | Sub-Sector | Mkt Cap (~$B) | DC Exposure | IBKR |
|--------|---------|-----------|---------------|-------------|------|
| 300750.SZ / 3750.HK | CATL | BESS for DCs | ~$275 | Medium | Via Connect / HK Yes |
| 300274.SZ | Sungrow Power | Inverters/BESS | ~$22 | Medium | Via Connect |
| 600089.SS | TBEA Co | Transformers | ~$12 | Medium | Via Connect |
| 600406.SS | Nari Technology | Grid Equipment | ~$14 | Medium | Via Connect |

**Other:**

| Ticker | Company | Country | Sub-Sector | Mkt Cap (~$B) | DC Exposure | IBKR |
|--------|---------|---------|-----------|---------------|-------------|------|
| 2308.TW | Delta Electronics | Taiwan | UPS/Power Supplies | ~$45 | High | Yes (TWSE) |
| PDN.AX | Paladin Energy | Australia | Uranium Mining | ~$3 | Low | Yes (ASX) |

### WALLED GARDEN BENCHMARKS

**Major Utilities (Rate Base):** AEP (AEP, ~$55B), Xcel Energy (XEL, ~$35B), Exelon (EXC, ~$45B), Pinnacle West (PNW, ~$12B), WEC Energy (WEC, ~$30B).

**Hyperscalers with Captive Power:** Amazon/AWS (AMZN — nuclear PPAs, custom solar, SMR exploration), Alphabet/Google (GOOGL — acquired Intersect Power $4.75B, Kairos SMR deal), Microsoft (MSFT — Constellation TMI restart PPA), Meta (META — 1.1 GW nuclear deal, Oklo microreactors, Bloom fuel cells), Oracle (ORCL — Stargate JV, gas-powered campuses).

### Companies from the Irrational Analysis Substack Article (Dec 21, 2025)

All five data center energy plays from "2026 Irrational Ideas" are included above:

- **Constellation Energy (CEG)** — Tier 2. "An IPP that is almost all nuclear." Nuclear fleet ideal for DC baseload.
- **ON Semiconductor (ON)** — Tier 3. Power semis. Author highlights emerging V-GaN technology as asymmetric opportunity while SiC/Tesla weakness suppresses stock.
- **EQT Corp (EQT)** — Tier 3. Largest U.S. gas producer. "Cheapest and claims to be capable of surviving anything" in cyclical gas market. Positioned for DC-driven gas demand.
- **Solaris Energy Infrastructure (SEI)** — Tier 1. "Time to power" play — carts in mobile natural gas generators for rapid DC power deployment.
- **Bloom Energy (BE)** — Tier 1. "Time to power" play — fuel cell solutions deploying in 90 days vs. years for grid connection.

---

## DATA QUALITY FLAGS

### (a) Where data was sparse or unreliable

- **Solaris Energy Infrastructure (SEI)** — Limited public financial history; recently pivoted from oilfield services. Market cap and revenue figures from investor presentations may not reflect current trading.
- **SMR/Advanced nuclear timelines** — Commercial deployment dates from developers are aspirational. No SMR has operated commercially in the U.S. Treat all SMR deployment dates with skepticism.
- **Fuel cell TAM for data centers** — Estimates range from $175M to $3.6B for 2024 depending on scope definition. An order-of-magnitude disagreement across research firms.
- **Liquid cooling market size** — Dell'Oro ($3B in 2025 → $7B by 2029) is the most credible source. Some blog/promotional sources cite $21B by 2032 — likely aggressive.
- **Micro-cap/pre-revenue companies** (OKLO, NuScale, NNE, Wolfspeed, FCEL) — Valuations are speculative; revenue bases too small for reliable financial modeling.
- **Chinese company data** — Market caps and revenue for mainland-listed Chinese companies are approximate; currency conversion and reporting differences add uncertainty.

### (b) Where sources disagreed materially

- **2030 U.S. data center power demand:** IEA base case (~945 TWh global) vs. BCG high case (>1,050 TWh U.S. alone) vs. Grid Strategies (argues utility forecasts of 90 GW are overstated). The **5x spread** in estimates is the single largest data quality issue in this report.
- **Data center power equipment TAM:** MarketsandMarkets ($35.1B), Grand View Research ($22.8B), and Mordor Intelligence ($24.6B) for 2025 — driven by differing scope definitions.
- **Gas demand from data centers by 2030:** S&P Global (3–6 Bcf/d), Bernstein (12 Bcf/d), EQT (10 Bcf/d) — 4x spread.
- **Bloom Energy market cap:** Sources ranged from $39B to $46.8B — extreme recent volatility.
- **Vertiv market cap:** Sources ranged from $90B to $106B.
- **MPWR's ~70% market share claim on NVIDIA Vera Rubin** — sourced from Simply Wall St narrative, not confirmed in company filings [UNVERIFIED].
- **Stargate project execution:** The Information reported significant partner disagreements, Abilene expansion halted, organizational challenges — contrasts with official optimistic announcements.

### (c) What could not be verified

- [UNVERIFIED] Deep Fission/Endeavour Energy's claim of operational borehole SMR by 2026 — extremely aggressive timeline.
- [UNVERIFIED] Fermi America's Project Matador 11 GW projection (from pre-IPO S-1).
- [UNVERIFIED] MPWR 70% share on NVIDIA Vera Rubin platform.
- [UNVERIFIED] Bloom Energy ~90%+ share of commercial fuel cell deployments in U.S. data centers — implied by deployment data but not independently confirmed.
- [UNVERIFIED] Exact timing of EPA power plant GHG repeal final rule — was expected ~Dec 2025 but may not be finalized as of April 2026.
- [UNVERIFIED] DOE pilot reactor criticality target of July 4, 2026 — highly ambitious.
- [UNVERIFIED] Several M&A deal values: Trane/LiquidStack, Trane/Stellar Energy Digital, Daikin/Chilldyne, Johnson Controls/Alloy Enterprises, Submer/Radian Arc — all undisclosed.
- [UNVERIFIED] NRG/LS Power deal timing has conflicting dates across sources.
- [UNVERIFIED] NNE (NANO Nuclear) market cap — limited recent data.
- [UNVERIFIED] Wolfspeed financial viability and exact market cap — company has received CHIPS Act funding but faces financial distress risk.
- [UNVERIFIED] Many sovereign AI project pledges (Saudi $1T, UAE 5 GW campus) are aspirational announcements, not committed capital.
- [UNVERIFIED] Hyperscaler capex figures for 2026 are based on analyst projections and guidance, not actuals.