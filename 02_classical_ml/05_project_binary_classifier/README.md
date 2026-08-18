# Project — Binary classifier

**Ship a trained model with a metric, plots, and a pipeline — not a lucky notebook cell.**

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

## Dataset

Pick one public set and stick to it:

* Titanic survival
* Credit default / churn
* Any binary tabular set you can explain in one sentence

## Build

* [ ] EDA notebook or script (missingness, target rate, leakage check)
* [ ] `Pipeline` + `ColumnTransformer`
* [ ] Baseline (`DummyClassifier`)
* [ ] Model A: logistic regression
* [ ] Model B: random forest (or tree)
* [ ] Val metrics, then **one** test run
* [ ] Confusion matrix + ROC
* [ ] 10 error examples explained (false positives / negatives)

## Deliverables

* [ ] `notebooks/` or `src/` training code
* [ ] `tests/` — e.g. pipeline `predict` on 3 rows
* [ ] `results/` — metrics.json, plots
* [ ] README: problem, features, metric, numbers, how to rerun

## Success

* [ ] Beats dummy by a clear margin
* [ ] Imbalanced? You did **not** use accuracy as the only number
* [ ] README has the test metric and the split seed
