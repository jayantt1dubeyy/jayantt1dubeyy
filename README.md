<h1 align="center">Hi, I'm Jayant Dubey 👋</h1>

<p align="center">
  B.Tech CSE @ <b>IMS Engineering College</b>, India · BS Computer Science @ <b>University of the People</b><br>
  Working on <b>multi-agent systems</b>, <b>Bayesian inference</b>, small language models, and hardware built from zero
</p>

<p align="center">
  <a href="https://github.com/jayantt1dubeyy/PROVENANCE-AWARE-BELIEF-AGGREGATION"><img src="https://img.shields.io/badge/📄_Research_Paper-Provenance--Aware_Belief_Aggregation-blue?style=flat-square" alt="Research paper"></a>
  <a href="https://github.com/jayantt1dubeyy/onion-ai"><img src="https://img.shields.io/badge/🤖_OpenMythos-Recurrent_LM-green?style=flat-square" alt="OpenMythos"></a>
  <a href="https://nyx-crystal-ai.lovable.app/"><img src="https://img.shields.io/badge/🔮_Nyx-Live_Demo-brightgreen?style=flat-square" alt="Nyx live demo"></a>
  <a href="https://github.com/jayantt1dubeyy/JANE-"><img src="https://img.shields.io/badge/🔧_ASIC_Puzzle-Solved-orange?style=flat-square" alt="ASIC puzzle solved"></a>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Verilog-6E4C9E?style=flat-square" alt="Verilog">
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX">
</p>

---

### 🎓 Education

- **BS in Computer Science** — University of the People (enrolled Oct 2026; WSCUC-accredited, fully online; first term starts 12 Nov 2026)
- **B.Tech in Computer Science & Engineering** — IMS Engineering College (AKTU), 2026–2030

---

### 🔬 Featured work

**[Provenance-Aware Belief Aggregation in Multi-Agent Communication Under Convention Heterogeneity](https://github.com/jayantt1dubeyy/PROVENANCE-AWARE-BELIEF-AGGREGATION)** · [beginner explainer](https://github.com/jayantt1dubeyy/PROVENANCE-AWARE-BELIEF-AGGREGATION/blob/main/EXPLAINED_FOR_BEGINNERS.md)

When agents report through different *communication conventions* — mappings from internal readings to messages that can invert or transform the signal — weighting messages by source reliability answers the wrong question. This work proves structural limitations of scalar trust weighting and introduces a Bayesian aggregator that decodes messages through inferred latent conventions.

> *Reliability is not convention. Weighting evidence is not decoding evidence.*

- 📐 Core claim proved inside the model's assumptions (repaired Theorem 2); real-world universality is NOT claimed
- 🧪 17-page manuscript, headline runs over 190 seeds with confidence intervals, PVI-REAL human-judgment section
- 🔁 Fully reproducible: `bash reproduce.sh` regenerates tables, figures, and the paper

**[Nyx — the Decision Intelligence Simulator](https://github.com/jayantt1dubeyy/nyx-crystal-ai)** · [live demo](https://nyx-crystal-ai.lovable.app/) · [beginner explainer](https://github.com/jayantt1dubeyy/nyx-crystal-ai/blob/main/docs/EXPLAINED_FOR_BEGINNERS.md)

Give it a hard decision — *"should we ban smartphones in schools?"* — and Nyx builds a miniature society of AI agents that debate, feel emotions, influence each other, and occasionally crash. The output isn't just a winner but a strategic forecast: hidden risks, fragile assumptions, key influencers, what-if scenarios.

- 🎲 Fully deterministic kernel: the same seed always reproduces the same outcome — auditable and reproducible by design
- 🧠 Agents carry evolving psychological variables; advanced mode unlocks batch experiments, counterfactuals, Nash equilibria and Pareto frontiers
- 🎬 Worked example + demo GIF in the README: seed-42 smartphone-ban run, Dev cascades in rounds 4–5 then recovers

**[OpenMythos — a miniature recurrent language model](https://github.com/jayantt1dubeyy/onion-ai)** · [44M report](https://github.com/jayantt1dubeyy/onion-ai/blob/main/research/44m_experiment_report.md) · [beginner explainers](https://github.com/jayantt1dubeyy/onion-ai/blob/main/research/44m-explained-for-beginners.md)

A from-scratch language model built around one question: does weight-shared recurrent iteration buy effective depth more cheaply than wider layers? **Prelude → Recurrent Block × N → Coda**, with GQA + RoPE attention, SwiGLU (or sparse MoE), and truncated BPTT.

- ✅ Verification tests passing, including KV-cache equivalence for recurrent generation
- 🧪 Stage-0 result (44M, TinyStories, one T4): loop depth 4 loss 1.484 vs depth-1 baseline 3.380 — but depth 8 is significantly worse (+0.106, 95% CI [+0.101, +0.110]). Extrapolation is scale- and task-dependent, not settled
- 📝 MiniMythos 125M (reported, not independently verified): HellaSwag 29.5% → 30.0% (8 → 16 loops), PIQA flat at 50.0% (chance)
- 🚀 1B roadmap: 1.06B config, loop-depth curriculum — a plan, not a trained model yet

**[Jane Street ASIC Puzzle 2026 — solved](https://github.com/jayantt1dubeyy/JANE-)** · [beginner explainer](https://github.com/jayantt1dubeyy/JANE-/blob/main/EXPLAINED_FOR_BEGINNERS.md)

Reverse-engineered a chip from its GDS layout alone, by four independent methods that all agreed. The chip is a serial-key lock: 121-bit key, flag `(* TWO STARS *)`. Published after submissions closed (4 Sep 2026); nothing was submitted. Includes a 3D viewer plotting all 728 cells at their real layout positions.

**[Recurrent Small LMs — technical report](https://github.com/jayantt1dubeyy/RECURRENT-SMALL-LMS)**

NeurIPS-style technical report (22 pages) on recurrent small language models, with the loop-extrapolation evidence stated honestly — including where it fails.

---

### 🐼 Explained for beginners

Plain-language explainers, one analogy per project, with verified vs reported vs plan-only labels:
[PVI](https://github.com/jayantt1dubeyy/PROVENANCE-AWARE-BELIEF-AGGREGATION/blob/main/EXPLAINED_FOR_BEGINNERS.md) · [Nyx](https://github.com/jayantt1dubeyy/nyx-crystal-ai/blob/main/docs/EXPLAINED_FOR_BEGINNERS.md) · [OpenMythos 44M](https://github.com/jayantt1dubeyy/onion-ai/blob/main/research/44m-explained-for-beginners.md) · [MiniMythos 125M](https://github.com/jayantt1dubeyy/onion-ai/blob/main/research/minimythos-125m-explained-for-beginners.md) · [1B roadmap](https://github.com/jayantt1dubeyy/onion-ai/blob/main/research/1b-roadmap-explained-for-beginners.md) · [ASIC puzzle](https://github.com/jayantt1dubeyy/JANE-/blob/main/EXPLAINED_FOR_BEGINNERS.md)

*Note: tiny8 CPU (8-bit processor built from zero in Verilog, sum 1..10 = 55 verified two ways) has no GitHub repo yet, so it is not linked here until one is created.*

---

### 🛠️ What I work with

`Python` · `PyTorch` · `Verilog` · `NumPy` · `LaTeX` · `Git`

**Interests:** multi-agent systems · Bayesian inference · trust & reputation · small language models · collective decision-making · hardware

---

### 📊 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jayantt1dubeyy&show_icons=true&theme=default&hide_border=true" alt="GitHub stats" height="160">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jayantt1dubeyy&layout=compact&hide_border=true" alt="Top languages" height="160">
</p>

---

<p align="center">
  📫 Reach me: <a href="mailto:dubeymaya787@gmail.com">dubeymaya787@gmail.com</a>
</p>
