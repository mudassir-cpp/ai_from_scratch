# Month 12 — Capstone (Jul 2027)

**Goal:** one product that a user can try. Combine data + model/LLM + eval + deploy.

**You ship:** a public repo + demo (live URL or video) + architecture writeup.

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## Status

* [ ] Design frozen
* [ ] Build complete
* [ ] Shipped (demo + docs)
* [ ] Capstone `[x]` on root README

---

## What to learn

You are not learning a new stack. You are **integrating**.

### Design — [`01_design`](01_design/README.md)

* [ ] User, job-to-be-done, out of scope
* [ ] Architecture diagram
* [ ] Eval plan (quality, latency, cost)
* [ ] Risk list (PII, cost, hallucinations)

### Build — [`02_build`](02_build/README.md)

* [ ] Vertical slice week 1 (ugly but end-to-end)
* [ ] Then quality
* [ ] Tests on the dangerous parts (parse, retrieve, auth)

### Ship — [`03_ship`](03_ship/README.md)

* [ ] README for strangers
* [ ] Demo
* [ ] Postmortem: what you’d redo

---

## Deep dive (own folder)

Work through one topic at a time in [`deep_dive/`](deep_dive/README.md). Each folder should end with a usable artifact you can plug into the capstone.

* [ ] [`01_problem_framing`](deep_dive/01_problem_framing/README.md)
* [ ] [`02_system_design`](deep_dive/02_system_design/README.md)
* [ ] [`03_data_pipeline`](deep_dive/03_data_pipeline/README.md)
* [ ] [`04_model_llm_core`](deep_dive/04_model_llm_core/README.md)
* [ ] [`05_eval_quality`](deep_dive/05_eval_quality/README.md)
* [ ] [`06_deploy_demo`](deep_dive/06_deploy_demo/README.md)

## Project ideas (pick one)

* [ ] Internal knowledge assistant (RAG + citations + eval set)
* [ ] Support agent (tools + traces + guardrails)
* [ ] Vision + text product (classify/detect + small API)
* [ ] Tabular decision API (sklearn/PyTorch + monitoring)

## 1% bar

* [ ] A stranger can run or click the demo from README
* [ ] You have numbers (quality + latency or cost)
* [ ] You can defend every major design choice in 15 minutes

Open [`DAYS.md`](DAYS.md).
