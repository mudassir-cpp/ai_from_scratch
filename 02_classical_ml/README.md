# Month 2 — Classical ML (Sep 2026)

**Goal:** train, evaluate, and *explain* standard models. This is the deep-dive month: every important algorithm gets its own folder under [`deep_dive/`](deep_dive/README.md).

**You ship:** [`05_project_binary_classifier`](05_project_binary_classifier/README.md)

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

---

## Status

* [ ] Supervised learning
* [ ] Unsupervised learning
* [ ] Metrics + cross-validation
* [ ] Feature engineering + sklearn pipelines
* [ ] Deep dive: all 9 algorithms (from scratch once + sklearn)
* [ ] Binary classifier project shipped

---

## What to learn

### Workflow (do this every time)

* [ ] Problem type: regression vs classification vs clustering
* [ ] Leakage: target in features, future data in train
* [ ] Split: train / val / test (or CV)
* [ ] Baseline first (mean predictor, DummyClassifier)
* [ ] Fit → predict → metric → error analysis
* [ ] sklearn `Pipeline` + `ColumnTransformer`

### Supervised — [`01_supervised`](01_supervised/README.md)

* [ ] Linear / logistic regression
* [ ] Trees, forests, boosting intuition (RF this month; XGBoost light)
* [ ] SVM, KNN, Naive Bayes — when they win vs when they waste time

### Unsupervised — [`02_unsupervised`](02_unsupervised/README.md)

* [ ] k-means, how to pick k
* [ ] PCA for visualization and noise, not magic

### Evaluation — [`03_evaluation`](03_evaluation/README.md)

* [ ] MSE / MAE / R²
* [ ] accuracy vs F1 vs ROC-AUC (imbalance)
* [ ] confusion matrix, calibration (optional)
* [ ] k-fold CV, stratified split

### Features — [`04_feature_engineering`](04_feature_engineering/README.md)

* [ ] scaling, encoding, missing values
* [ ] simple feature crosses only if they help the metric

---

## Deep dive (own folder)

Work through **in order**. Each algorithm: math in one page → NumPy from scratch → sklearn → “when I would use this at work”.

| # | Algorithm | Folder |
|---|-----------|--------|
| 1 | Linear regression | [`deep_dive/01_linear_regression`](deep_dive/01_linear_regression/README.md) |
| 2 | Logistic regression | [`deep_dive/02_logistic_regression`](deep_dive/02_logistic_regression/README.md) |
| 3 | Decision trees | [`deep_dive/03_decision_trees`](deep_dive/03_decision_trees/README.md) |
| 4 | Random forest | [`deep_dive/04_random_forest`](deep_dive/04_random_forest/README.md) |
| 5 | SVM | [`deep_dive/05_svm`](deep_dive/05_svm/README.md) |
| 6 | KNN | [`deep_dive/06_knn`](deep_dive/06_knn/README.md) |
| 7 | Naive Bayes | [`deep_dive/07_naive_bayes`](deep_dive/07_naive_bayes/README.md) |
| 8 | k-means | [`deep_dive/08_kmeans`](deep_dive/08_kmeans/README.md) |
| 9 | PCA | [`deep_dive/09_pca`](deep_dive/09_pca/README.md) |

---

## 1% bar (Month 2)

* [ ] Implement logistic regression (GD) in NumPy and match sklearn on a tiny dataset
* [ ] Explain bias/variance using a tree vs a linear model on the same data
* [ ] Choose a metric for an imbalanced problem and defend it
* [ ] Ship a pipeline: raw CSV → ColumnTransformer → model → test metric in README

---

## Project

**Binary classifier** on a public dataset (Titanic, credit risk, churn). Two models minimum, error analysis, plots.

See [`05_project_binary_classifier/README.md`](05_project_binary_classifier/README.md).

---

## Resources

* [ ] [scikit-learn user guide](https://scikit-learn.org/stable/user_guide.html)
* [ ] StatQuest ML playlist (PCA, trees, logistic)
* [ ] Hands-On ML (Géron) ch. 2–6 — skim, then code

Open [`DAYS.md`](DAYS.md) every morning.
