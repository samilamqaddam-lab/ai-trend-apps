# 🔄 AutoResearch Loop — Self-Improving AI Research Visualizer

**Date:** 2026-03-08  
**Trend:** Karpathy's "autoresearch" project (viral on X, March 8 2026)  
**Tech:** HTML/CSS/JS (single file, no dependencies)

---

## The Trend

On March 8, 2026, Andrej Karpathy (ex-OpenAI, coined "vibe coding") released a new open-source project called **autoresearch** — a minimal, single-GPU system (~630 lines of Python) for training your own self-improving AI research agent.

The viral thread got significant traction because it shifts the AI narrative from "use frontier models" to "own your specialist model." Key ideas:
- Human iterates on the prompt → AI researches → model trains → loop improves
- Once locked into a domain, specialist models outperform general LLMs
- Keeps data private, gives control over model updates
- ~630 lines, single-GPU, accessible to anyone

This coincides with the Mercury 2 (Inception Labs) diffusion model buzz — both pointing to a trend of **democratized model training and inference**.

---

## What This App Does

An interactive web visualizer that simulates the autoresearch loop concept:

1. **Loop Diagram** — animated 4-step cycle (Define Prompt → AI Researches → Human Reviews → Model Trains)
2. **Simulation Engine** — pick a research topic + domain (ML, Biology, Physics, CS, Economics, Neuroscience) and watch simulated iterations run
3. **Quality Scoring** — tracks research quality improvement across iterations with progress bars
4. **Domain-Specific Content** — realistic hypotheses and feedback for each domain
5. **Stats Dashboard** — iterations run, quality score, improvement gain

---

## How to Run

Just open `index.html` in any browser — no server, no dependencies.

```bash
open index.html
# or
python3 -m http.server 8080
```

---

## The Real autoresearch Project

- GitHub: [github.com/karpathy/autoresearch](https://github.com/karpathy) *(check karpathy's profile)*
- X thread: [x.com/karpathy](https://x.com/karpathy/status/2030371219518931079)

---

## Tags

`karpathy` · `self-improving-ai` · `research-agent` · `fine-tuning` · `autoresearch` · `ai-training`
