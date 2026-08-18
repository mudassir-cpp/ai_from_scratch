# Month 1 — Foundations (Aug 2026)

**Goal:** write real Python, use Git like a teammate, and know the math you will *use* in models. Every core skill has its own folder under [`deep_dive/`](deep_dive/README.md).

**You ship:** [`04_project_python_cli`](04_project_python_cli/README.md)

---

## Status

* [ ] Python
* [ ] Git / GitHub
* [ ] Linear algebra
* [ ] Calculus
* [ ] Probability & stats
* [ ] Deep dive: all 7 topics
* [ ] Month project shipped

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## What to learn

### Python (applied)

* [ ] Types, functions, modules, packages
* [ ] Lists, dicts, sets, comprehensions
* [ ] OOP: classes, dunder methods you will actually use (`__init__`, `__repr__`)
* [ ] Errors, logging, pathlib, argparse
* [ ] Virtualenv, `requirements.txt`, pytest
* [ ] pandas: load CSV, filter, groupby, missing values
* [ ] NumPy: arrays, broadcasting, vectorization (no Python loops on data)

### Git

* [ ] clone, status, add, commit, push, pull
* [ ] branches, PRs, `.gitignore`
* [ ] write commit messages that say *why*

### Math you will use (not a math degree)

* [ ] Vectors, matrices, dot product, shapes — [`03_math/01_linear_algebra`](03_math/01_linear_algebra/README.md)
* [ ] Derivatives, gradient, chain rule — [`03_math/02_calculus`](03_math/02_calculus/README.md)
* [ ] Probability, distributions, train/test leakage intuition — [`03_math/03_probability_stats`](03_math/03_probability_stats/README.md)

---

## Deep dive (own folder)

Work through **in order**. Each topic: explain → drill → mini exercise.

| # | Topic | Folder |
|---|-------|--------|
| 1 | Python core | [`deep_dive/01_python_core`](deep_dive/01_python_core/README.md) |
| 2 | NumPy vectorization | [`deep_dive/02_numpy_vectorization`](deep_dive/02_numpy_vectorization/README.md) |
| 3 | pandas EDA | [`deep_dive/03_pandas_eda`](deep_dive/03_pandas_eda/README.md) |
| 4 | Git workflow | [`deep_dive/04_git_workflow`](deep_dive/04_git_workflow/README.md) |
| 5 | Linear algebra | [`deep_dive/05_linear_algebra`](deep_dive/05_linear_algebra/README.md) |
| 6 | Calculus & gradients | [`deep_dive/06_calculus_gradients`](deep_dive/06_calculus_gradients/README.md) |
| 7 | Probability & metrics | [`deep_dive/07_probability_metrics`](deep_dive/07_probability_metrics/README.md) |

---

## 1% bar (Month 1)

You can do all of this without looking it up twice:

* [ ] Write a CLI that reads a CSV, prints stats, writes a report file
* [ ] Cover the core functions with pytest
* [ ] Explain gradient descent in one paragraph and in code
* [ ] Multiply matrices with NumPy *and* with a triple loop, then say why NumPy wins

---

## Project

**Python CLI data tool** — see [`04_project_python_cli/README.md`](04_project_python_cli/README.md)

---

## Folder map

```text
01_foundations/
  deep_dive/           one folder per skill (main track)
  01_python/           extra practice
  02_git/              extra practice
  03_math/             full math checklists
  04_project_python_cli/
  DAYS.md              tick Day 1–30
```

Open [`DAYS.md`](DAYS.md) every morning. Change `[ ]` → `[*]` → `[x]`.
