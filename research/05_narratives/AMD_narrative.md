# AMD — Narrative Map

> Narrative-first companion to [`../03_companies/AMD.md`](../03_companies/AMD.md). Cross-links: [`../01_macro/AI_STACK_WARS.md`](../01_macro/AI_STACK_WARS.md), [`../01_macro/MACRO_SCENARIO_TREE.md`](../01_macro/MACRO_SCENARIO_TREE.md). Research date 2026-06-28.

---

## 1. The sector's narrative weather (AI accelerators)

**The dominant story:** *"AMD is the credible #2 — and inference is the great leveler."* The market has moved AMD from "Nvidia roadkill" to "the second source the whole industry needs." Nvidia's data-centre GPU share has slipped from **~90% (2024) → ~86% (2026)** as **AMD gains specifically in inference** ([Silicon Analysts](https://siliconanalysts.com/analysis/amd-vs-nvidia-ai-gpu-market-share-2026)).

**Percolating sub-narratives:**
1. **★ "Inference vs training split" (the key frame):** AMD **wins on tokens-per-dollar for inference** (MI355X/MI300X ~25–40% cheaper per token; MI455X with 432GB HBM4 matches/exceeds B200/B300 on inference), while **Nvidia still wins training + ecosystem** ([DHLM](https://dhlm-studio.com/blog/nvidia-vs-amd-ai-inference-cost-2026)). As the workload mix shifts from *training* to *serving* (inference), AMD's relevance rises. **This is the single most important AMD narrative.**
2. **"ROCm is catching CUDA"** — ROCm 7 closed most of the PyTorch framework gap; the software moat that protected Nvidia is (slowly) eroding.
3. **"Contracted visibility"** — Meta's **$60bn 5-yr** deal (1GW opening on MI450), Oracle's **50,000 MI450 from Q3 2026**, OpenAI 6GW → revenue visibility into 2027 ([tech-insider](https://tech-insider.org/amd-mi400-series-ai-gpu-data-center-2026/)).
4. **"MI400 first-to-2nm"** — H2 2026 Helios rack (72 MI455X, 31TB HBM4, 2.9 EFLOPS FP4) — the product that could close the *training* gap too.
5. **The share-ceiling debate** — bulls see double-digit share (Nov-2025 Analyst Day target); bears see a **plateau at 20–25%** then stall.

---

## 2. Where AMD sits — the beneficiary of *everyone wanting to escape Nvidia*

AMD's narrative is leveraged to the **"diversify off Nvidia"** wave — but it sits in a **three-body problem**:
- **vs Nvidia:** the second-source trade; benefits from any anti-Nvidia sentiment, allocation tightness, or CUDA-lock-in fatigue.
- **vs custom ASICs (Broadcom/TPU/Trainium):** the *hidden* threat — hyperscaler in-house silicon competes with **both** Nvidia *and* AMD merchant GPUs. If hyperscalers route inference to their own ASICs, AMD's TAM shrinks even as Nvidia's does. (See [`AI_STACK_WARS.md`](../01_macro/AI_STACK_WARS.md) §3 — Broadcom may be the bigger structural winner.)
- **vs open/Chinese models + token-minimising:** ambiguous — cheaper inference = *more* inference volume (Jevons) = more AMD-shaped demand, but also pressure on the whole compute pool if it deflates capex.

---

## 3. Cross-trend web

| Trend | Effect on AMD narrative |
|---|---|
| **Inference shift** (training → serving) | **The core bull** — AMD's tokens/dollar edge matters most in inference; open-model/agent boom = more inference. |
| **AI-capex super-cycle** | The demand; AMD's deals are hyperscaler capex. |
| **AI Reckoning / capex cut (S3)** | High-beta downside — a crowded ~58× momentum long unwinds hard. |
| **Custom ASICs (S14)** | The structural threat — bypasses merchant GPUs entirely. |
| **Nvidia commoditises models** | Neutral-ish for AMD (it's a chip story, not a model story). |
| **China export caps (S13)** | Caps China TAM (MI308); shrinking part of the story. |

---

## 4. ★ Bull narratives that re-rate it UP

1. **★ "Inference share lands"** — tracker data confirms AMD taking real inference share (toward/through double digits) as ROCm matures. *Perception shift:* from "perennial hopeful" to "validated duopoly #2 with a structural growth runway" → the multiple holds/expands even at 58×.
2. **"MI400 wins benchmarks on time"** — Helios ships Q3 2026 and matches Blackwell on *training* too → AMD becomes a full-stack alternative, not just inference. *Catalyst:* MI455X benchmark/ship milestones.
3. **"More mega-deals"** — another hyperscaler signs (Microsoft/Google/Anthropic) → contracted visibility deepens.
4. **"ROCm tipping point"** — developer mindshare visibly shifts; the CUDA moat narrative cracks.

## 5. ★ Bear narratives that re-rate it DOWN

1. **★ "Custom ASICs eat the merchant GPU"** — hyperscalers shift inference to Broadcom-built in-house chips → AMD's TAM plateaus at 20–25% and stalls. *Perception shift:* from "duopoly challenger" to "squeezed-from-both-sides merchant vendor" → de-rate.
2. **"AI capex peaks" (S3)** — a hyperscaler capex cut; AMD's high-beta momentum reverses violently.
3. **"One product slip resets the narrative"** — any MI400 delay or benchmark miss; the bull case requires "three more architecture generations flawlessly" ([Silicon Analysts](https://siliconanalysts.com/analysis/amd-vs-nvidia-ai-gpu-market-share-2026)).
4. **"Software gap persists"** — ROCm still needs heavy kernel engineering; out-of-box utilization lags → hyperscalers stick with CUDA.
5. **"Dilution + valuation"** — the OpenAI/Meta warrants (~20%) + 58× multiple leave no room for a Data-Center miss.

---

## 6. The narrative-shift tells
- **★ Data Center revenue + the inference/training mix** vs consensus — the quarter that matters (Q1-26 beat sent it +16%).
- **AMD GPU share in tracker data** — does the second-source thesis actually show up?
- **ROCm adoption signals** (framework support, developer mindshare).
- **New hyperscaler deals** + MI400/Helios ship milestones (Q3 2026).
- **Nvidia results & Broadcom ASIC newsflow** — read-through both ways.
- **Whether beats keep being rewarded** — same tiring-narrative tell as ASML.

## 7. Scenario read-through
- **S4 (AI Vertical) + inference shift:** AMD is a prime winner — leveraged to both capex *and* share gains. ↑↑
- **S3 (AI Reckoning):** among the highest-beta losers (crowded, 58×, dilution). ↓↓↓
- **S14 (custom ASICs win):** the quiet structural bear — AMD squeezed. ↓
- **S11 (token deflation / Jevons):** ambiguous — could *help* via inference volume, or hurt via capex deflation.
