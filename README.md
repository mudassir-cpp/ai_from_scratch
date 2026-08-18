# 1% Applied AI Engineer — 12 Month Repo

Ship working AI products, not notebooks. This repo is the day-by-day track: learn, build, evaluate, deploy.

**Window:** Aug 2026 → Jul 2027 · **Pace:** ~6 days/week, ship a project every month.

---

## How to use this repo

Mark every checkbox yourself as you go.

| Mark | Meaning |
|------|---------|
| `[ ]` | not started |
| `[*]` | in progress |
| `[x]` | done |

Each month folder has:

1. `README.md` — what to learn, 1% bar, projects
2. `deep_dive/` — **one folder per concept** (learn → drill → mini project)
3. `DAYS.md` — Day 1–30 you tick off
4. topic folders — notes + from-scratch drills
5. `*_project_*/README.md` — the thing you ship

Do not skip the month project. Employers care about **data → model → eval → deploy**, not certificates.

---

## 12-month map

| Month | Folder | You ship |
|-------|--------|----------|
| 1 Aug 2026 | [`01_foundations`](01_foundations/README.md) | Python CLI + 7 deep dives (Python, NumPy, math…) |
| 2 Sep 2026 | [`02_classical_ml`](02_classical_ml/README.md) | Binary classifier + 9 algorithm deep dives |
| 3 Oct 2026 | [`03_deep_learning`](03_deep_learning/README.md) | MNIST MLP + 8 PyTorch deep dives |
| 4 Nov 2026 | [`04_computer_vision`](04_computer_vision/README.md) | Image classifier + 6 CNN deep dives |
| 5 Dec 2026 | [`05_nlp_transformers`](05_nlp_transformers/README.md) | Text classifier + 6 transformer deep dives |
| 6 Jan 2027 | [`06_llms_finetuning`](06_llms_finetuning/README.md) | Domain chatbot + 6 LLM deep dives |
| 7 Feb 2027 | [`07_rag`](07_rag/README.md) | Knowledge QA + 6 RAG deep dives |
| 8 Mar 2027 | [`08_agents`](08_agents/README.md) | Task agent + 6 agent deep dives |
| 9 Apr 2027 | [`09_mlops_deployment`](09_mlops_deployment/README.md) | Model API + 5 MLOps deep dives |
| 10 May 2027 | [`10_performance`](10_performance/README.md) | Optimized inference + 5 perf deep dives |
| 11 Jun 2027 | [`11_cloud_scale`](11_cloud_scale/README.md) | Cloud pipeline + 5 cloud deep dives |
| 12 Jul 2027 | [`12_capstone`](12_capstone/README.md) | Capstone + 6 integration deep dives |

---

## Year progress

* [ ] Month 1 — Foundations
* [ ] Month 2 — Classical ML (deep dive)
* [ ] Month 3 — Deep learning
* [ ] Month 4 — Computer vision
* [ ] Month 5 — NLP & transformers
* [ ] Month 6 — LLMs & fine-tuning
* [ ] Month 7 — RAG
* [ ] Month 8 — Agents
* [ ] Month 9 — MLOps & deploy
* [ ] Month 10 — Performance
* [ ] Month 11 — Cloud & scale
* [ ] Month 12 — Capstone

---

## What a 1% applied AI engineer can do

After 12 months you should be able to:

* [ ] Frame a product problem as an ML/LLM system (data, eval, latency, cost)
* [ ] Train and debug classical ML and PyTorch models
* [ ] Fine-tune and serve transformers / LLMs
* [ ] Build RAG with chunking, retrieval metrics, and grounded answers
* [ ] Build agents with tools, traces, and failure handling
* [ ] Evaluate quality (offline metrics + LLM-as-judge + human spot checks)
* [ ] Containerize, CI, log experiments, deploy an API
* [ ] Cut latency/cost (batching, quantization, caching)
* [ ] Run it on a cloud with a real cost estimate

If you cannot **implement, debug, measure, and explain** it, it is not done.

---

## Daily loop (every working day)

Copy this into that day's section in `DAYS.md`:

```text
[*] Hours:
[ ] Learn (docs / one concept)
[ ] Build (code, not highlights)
[ ] Measure (metric, plot, or failing test)
[ ] Write 5 lines: what broke, what you changed
```

Weekly: one commit with a working demo. Monthly: project README + results + GitHub push.

---

## Stack you will actually use

Python · Git · NumPy · pandas · scikit-learn · PyTorch · Hugging Face · sentence-transformers · Qdrant/Chroma · LangChain or LlamaIndex · FastAPI · Docker · GitHub Actions · MLflow · ONNX · one cloud (AWS or GCP)

Official docs first. Papers only when they change how you build.

---

## Rules

1. Applied first. Theory exists to make the system work.
2. From-scratch once, library forever after you understand it.
3. Every project has tests, a README, and a number (accuracy, latency, cost, recall).
4. No month is complete without the project folder filled in.
