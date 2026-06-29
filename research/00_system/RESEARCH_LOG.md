# Research Log

> A running changelog of what's been added to this workspace. Newest at the bottom.

---

## 2026-06-27 — #1 — Set up the system

**Ask:**
- Note all my questions / prompts so you don't forget. Store it in the folder.
- The watchlist: 14 EU stocks + 2 US + China Macro + Iran + Fed.
- This is what we're expected to do (the equity-analyst mandate — see [MANDATE.md](MANDATE.md)). Note and store.
- I'm interpreting the job as a three-layer top-down: model of the world → model of each sector → model of each company, asking the same narrative-driven questions at each layer.
- **List out everything I need.** This is the mental model I should use to really learn my stocks. There are other things too.

**Delivered:**
- Folder structure under `research/`.
- [MANDATE.md](MANDATE.md) — the job captured.
- [COVERAGE_LIST.md](COVERAGE_LIST.md) — the 14 + 2 + 3 extracted from the image.
- [MENTAL_MODEL_FRAMEWORK.md](MENTAL_MODEL_FRAMEWORK.md) — the full "everything I need" checklist across all three layers + the news→range reflex.

---

## 2026-06-27 — #2 — Daily recap system

**Ask:**
- Confirmed the 14 EU tickers: asml, bnp, abbn, ulvr, enel, ibe, carlb, knebv, embracb, mele, zal, bmed, novob, aca.
- Every day I write a **recap** — extremely detailed on *process*, not a diary. It must capture: news that came in, what my expectations were, *why* they were like that, what was wrong, what actually happened, the lesson learned, what I can do better, what I can build on after being wrong, and the day's key takeaways.

**Delivered:**
- `04_recaps/` folder + [`_TEMPLATE.md`](../04_recaps/_TEMPLATE.md) — copy per day as `YYYY-MM-DD.md`.
- [`04_recaps/README.md`](../04_recaps/README.md) — the recap discipline + non-negotiable rules.
- Framed as the calibration loop (framework §4.4): log the prior *before* the outcome, always anchor to "what was priced in," diagnose the error type, write process takeaways not event takeaways.

---

## 2026-06-27 — #3 — Private GitHub repo + first deep research

**Ask:**
- Make a private GitHub for this.
- Do the research now — pick a few stocks, go slow, know *everything*, **everything linked to sources**.

**Delivered:**
- **Repo:** https://github.com/finnjclancy/research (mirrored to GitLab).
- Three deep, fully source-linked company files (different archetypes on purpose):
  - [`ASML.md`](../03_companies/ASML.md) — structural-growth EUV monopoly; trades on net bookings + forward-year confidence.
  - [`NOVO_NORDISK.md`](../03_companies/NOVO_NORDISK.md) — fallen GLP-1 darling; trades on US script share, oral-pill ramp, pipeline, US pricing.
  - [`BNP_PARIBAS.md`](../03_companies/BNP_PARIBAS.md) — eurozone bank archetype; trades on ECB rates, cost of risk, CET1/capital return.
- Layer-1 world view: [`ECB_RATE_REGIME.md`](../01_macro/ECB_RATE_REGIME.md) — the 2026 Iran oil shock → ECB's first hike since 2023 → read-through table across the whole book.

**Key live macro finding:** ECB hiked 25bp in June 2026 (first since 2023), driven by the 2026 Iran war / Strait of Hormuz oil spike (Brent peaked >$120, since falling back). Positive for the 4 banks' NII; negative for utilities (Enel, Iberdrola). Oil is the current "tell," the ECB the transmission.

---

## 2026-06-27 — #4 — Finish the whole book

**Ask:** Keep going, don't stop. In-depth, everything linked to sources, can't miss a single thing.

**Delivered — all 16 names now have full, source-linked Layer-3 files in [`../03_companies/`](../03_companies/):**
- Banks: [BNP](../03_companies/BNP_PARIBAS.md), [Crédit Agricole](../03_companies/CREDIT_AGRICOLE.md), [Banca Mediolanum](../03_companies/BANCA_MEDIOLANUM.md)
- Utilities (rate mirror): [Enel](../03_companies/ENEL.md), [Iberdrola](../03_companies/IBERDROLA.md)
- Semis/AI: [ASML](../03_companies/ASML.md), [AMD](../03_companies/AMD.md), [Melexis](../03_companies/MELEXIS.md) (auto-cyclical, not AI)
- Industrials: [ABB](../03_companies/ABB.md), [Kone](../03_companies/KONE.md)
- Staples: [Unilever](../03_companies/UNILEVER.md), [Carlsberg](../03_companies/CARLSBERG.md)
- Health Care: [Novo Nordisk](../03_companies/NOVO_NORDISK.md)
- Discretionary/e-commerce: [Zalando](../03_companies/ZALANDO.md), [Amazon](../03_companies/AMAZON.md)
- Comm Services (special situation/breakup): [Embracer](../03_companies/EMBRACER.md)
- Plus Layer-1 macro: [ECB rate regime / 2026 oil shock](../01_macro/ECB_RATE_REGIME.md)

**Cross-cutting threads mapped across the book:** (1) AI-capex super-cycle — ASML/AMD/Amazon/ABB/utilities (Amazon's capex is ASML/AMD's demand; data centres drive power demand → utilities). (2) ECB hiking regime — banks ↑ / utilities ↓. (3) China — Kone (property), Carlsberg (consumer), ASML/Melexis (chips). (4) Oil/Iran — input costs for staples, inflation → rates.

**Items flagged "to verify" against primary filings before quoting precisely:** ASML FY2025 China %; Novo live DKK price; Banca Mediolanum & Carlsberg A/B-share price prints; Kone 52-wk range; several current CEO titles. All sourced figures otherwise linked inline.

---

## 2026-06-27 — #5 — The narrative engine + macro→sector→company scenario tree

**Ask:** Map how each stock's sector/story fits in the world (place, necessity, why invest, growth, bull/bear), then the stock within the sector, then the stock. Narrative is the sole thing that matters. Build a decision tree: several ways the macro story may change → for each, how sectors' perception/place changes → for each, how each company's story flips. Plus the psychology & game theory of market participants (politicians, media, CEOs, lobbies, central banks, sell-side, hedge funds, passive, retail) so I can predict how much weight the market puts on a story when it breaks → and deliver "stock — range — reason — follow-up" fast.

**Delivered (the narrative stack):**
- [`NARRATIVE_ENGINE.md`](NARRATIVE_ENGINE.md) — first principles (price = consensus belief × conviction), the 3-layer narrative map, the **6-stage narrative life-cycle** (with where every book name sits today), the **game-theory table of all 9 participant types** and their motives, the decision-tree method, and the **`stock — range — reason — follow-up` output protocol** with worked examples.
- [`../02_sectors/SECTOR_NARRATIVES.md`](../02_sectors/SECTOR_NARRATIVES.md) — all 8 sector blocks: place in world, why necessary, why own, growth, bull, bear, "most levered to," + the 4 meta-narratives wiring the book (AI-capex, rates, China, GLP-1).
- [`../01_macro/MACRO_SCENARIO_TREE.md`](../01_macro/MACRO_SCENARIO_TREE.md) — **10 macro narrative-shift scenarios (S1–S10)**, each branching macro → sector → the most-relevant company + direction, with a live "call sheet" table and a how-to-use-live workflow.

**Key framing to remember:** the same news has *opposite* effects at different life-cycle stages — ASML/AMD/Amazon/ABB are stage-3 (crowded, beats-needed, downside-asymmetric); Novo is stage-4→5 (washed out, good news starting to work); utilities/Kone/Carlsberg are out-of-favour stage-1/2 (waiting on a catalyst). The highest-conviction, fastest money is in **S3 (AI Reckoning — crowded-long break)** and **S9a (GLP-1 relief — washed-out squeeze)**.

---

## 2026-06-28 — #6 — Deep AI/chip/macro narrative & game-theory research (overnight)

**Ask:** Extensive research on the live AI-complex narratives & game theory — the Fable model ban + KYC; open-source/token-minimising; Nvidia vs the labs (Nvidia making its own open models to commoditise labs); neo-lab allocation lock-in (Nvidia equity/IPO leverage to keep them on the Nvidia stack); Chinese chips (Huawei training GLM-5.2 without Nvidia); the Fed possibly being hawkish to let air out without intending to hike; government equity stakes in AI; mega-caps cutting capex to support stocks. Listen to unique perspectives / what people are saying. (Checked /Downloads for a podcast-transcription tool — found image-heavy Bloomberg/Fidelity macro chart notes in /Downloads/Macro, Jan 2026 vintage; no separate transcription tool located.)

**Delivered:** [`../01_macro/AI_STACK_WARS.md`](../01_macro/AI_STACK_WARS.md) — a flagship, fully-sourced narrative + game-theory map across 10 sections, each with a **→ Book** read-through. Plus scenario-tree updates: enriched **S3 (AI Reckoning)** with the loaded 2026 triggers and added **S11 token deflation / S12 AI nationalised / S13 chip Cold War / S14 Nvidia commoditises labs** to [`../01_macro/MACRO_SCENARIO_TREE.md`](../01_macro/MACRO_SCENARIO_TREE.md); added the **Warsh-Fed** section to [`../01_macro/ECB_RATE_REGIME.md`](../01_macro/ECB_RATE_REGIME.md).

**Key 2026 facts established (all sourced in AI_STACK_WARS.md):**
- **Fable 5 & Mythos 5 banned** (Commerce/Lutnick, 12 Jun) for all foreign nationals → Anthropic disabled them worldwide; **KYC (ID + selfie via Persona) from 8 Jul**. Handed the *usable* open-model crown to China.
- **GLM-5.2** (Z.ai, 13 Jun; 744B MoE, MIT, ~1/6th GPT-5.5 cost) tops usable leaderboards — **trained on Huawei Ascend, zero Nvidia**. Chinese models ~60% of OpenRouter tokens; 5–30× cheaper ("token minimising").
- **Nvidia:** ~$40bn circular AI equity (OpenAI $30bn, Anthropic Series G→$380bn, xAI $20bn) + GPU-collateralised debt; **$26bn open-model (Nemotron) bet to commoditise the labs**. Burry's "Cisco/Enron" warning. NVDA ~$81.6bn rev, +85%.
- **Hyperscaler capex ~$725bn 2026; aggregate FCF crosses zero ~Q3 2026** (Amazon crossing now). Market punishing capex (Meta −$175bn after a beat). **→ the "cut capex to save the stock" prisoner's dilemma; the next hyperscaler capex guide (Amazon first) is the cleanest S3 trigger.**
- **Warsh Fed** held 3.50–3.75%, hawkish dot-plot flip — possible "credibility theatre" that breaks dovish once oil rolls over.
- **US govt equity stakes** in AI (Intel 9.9% precedent; OpenAI talks) — the stack is being nationalised (ban + KYC + stakes = one move).

**Most-exposed book names to the AI fault lines:** Amazon (capex epicentre), ASML & AMD (supply-chain), ABB + Enel/Iberdrola (data-centre power leg). The complex is now **reflexive, levered, policy-entangled → narrative leads the numbers; pre-position ranges for triggers.**

---

## 2026-06-28 — #7 — Per-company narrative maps (the percolating stories)

**Ask:** Deep research on each of the 16 names — the narratives percolating in their *sector*, their relation to other trends/potential trends, and the specific narratives that could drive each stock *up* or *down*. Massive task; keep working; don't ask questions.

**Delivered:** [`../05_narratives/`](../05_narratives/) — a **narrative map per name** (16 files) + a [README](../05_narratives/README.md) with the **cross-cutting narrative clusters** (relative-value/pairs view). Each map: sector narrative weather → where the stock sits → cross-trend web → ★ bull narratives (up) → ★ bear narratives (down) → narrative-shift tells → scenario read-through (S1–S14).

**Fresh narrative facts surfaced (all sourced in the files):**
- **Unilever → combining Foods with McCormick** (agreement 31 Mar 2026) — after demerging Ice Cream; sheds GLP-1-exposed food to focus on Beauty/Personal/Home Care. (Explains the McCormick Form 425 seen in /Downloads earlier.)
- **Novo:** CagriSema *failed* its head-to-head (REDEFINE 4) vs Zepbound (−16%, 23 Feb 2026); washed-out fallen-angel; bull hope = **amycretin/zenagamtide (24% weight loss in 36 wks, Phase 3 AMAZE started)**.
- **Iberdrola/utilities:** the **"AI-electricity bottleneck"** re-rating story — Iberdrola taking *equity* in AI data centres (Echelon JV 20%), MSFT PPA; data-centre power could double to ~950 TWh by 2030. Converts bond proxies into AI-infra plays.
- **ABB:** electrification orders +44%, **triple-digit data-centre order growth**; 80% US-domestic (reshoring hedge); sold Robotics to SoftBank.
- **Kone:** Chinese **stimulus ("two new" + treasury bonds) now funds elevator *modernisation*** — turning a China risk into a tailwind (Kunshan: 2,106 units, 96% of tender).
- **Embracer → Fellowship Entertainment** lists Q1 FY26-27; LOTR/Tomb Raider IP "among the most undervalued"; catalysts: Tomb Raider Prime series (early 2027), LOTR Hunt for Gollum film (Dec 2027), new LOTR RPG.
- **Amazon:** AWS forward-demand book **>$364bn** (+Anthropic $100bn+, Trainium >$225bn); advertising ~$70bn trailing — the bull vs the $200bn-capex/FCF bear; **the epicentre + cleanest S3 trigger**.
- **Carlsberg:** GLP-1 "no significant impact yet"; premium beer +4% vs −1.7% volumes; China share gains. **Banks:** consensus "rate-cut → fee pivot" narrative whipsawed by the oil-shock hike (NII second wind); new bear flags = private-credit exposure + "AI disrupts banks".

**Cross-cutting clusters mapped:** AI build-out (ASML/AMD/ABB/Amazon/utilities), the rate axis (banks ↑ vs utilities ↓), China (Kone/Carlsberg/Unilever/ASML/Melexis), GLP-1 (Novo/Unilever/Carlsberg), idiosyncratic diversifiers (Novo/Embracer), reshaping/self-help.

---

## 2026-06-29 — Future narratives (Superforecasting)

**Added:** [`../01_macro/FUTURE_NARRATIVES.md`](../01_macro/FUTURE_NARRATIVES.md) — ~18 forward-looking super-scenarios across 6 clusters (AI build-out resolution, chip/geopolitics, monetary/fiscal regime, energy/climate, demographics/consumption, financial system), applying *Superforecasting* discipline: outside-view base rates, horizon-tagged granular probabilities, falsifiable signposts, book read-throughs, and premortems. Plus a probability×impact map, the correlated "chains" that matter most, and a monthly signpost dashboard. Cross-linked from the scenario tree and index. Grounded with current signposts (Stargate/sovereign AI, the AI power "grid cliff", AI-credit fragility, Taiwan/TSMC).

<!-- Add new prompts below this line, keeping the same format -->
