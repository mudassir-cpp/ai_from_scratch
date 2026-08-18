# Decision trees — deep dive

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

## What to learn

* [ ] Splits: Gini vs entropy vs MSE (regression trees)
* [ ] Recursion, depth, leaves
* [ ] Overfit: deep trees memorize
* [ ] `max_depth`, `min_samples_leaf`
* [ ] Feature importance (mean decrease impurity) — use carefully

## From scratch

* [ ] Tiny tree: one feature, one split, Gini
* [ ] Compare to `sklearn.tree.DecisionTreeClassifier`

## Applied

* [ ] When: nonlinear tabular, inspectable rules
* [ ] When not: alone on noisy high-dim data (use forests)

## Mini project

* [ ] Train a tree, export `plot_tree` or text rules, find one wrong leaf and explain it
