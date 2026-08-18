# Linear regression — deep dive

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

## What to learn

* [ ] Hypothesis: `ŷ = Xw + b`
* [ ] MSE loss and why we square
* [ ] Closed form (`(XᵀX)⁻¹Xᵀy`) vs gradient descent
* [ ] Normal equation failure: singular / ill-conditioned X
* [ ] Regularization: Ridge (L2), Lasso (L1) — why they exist
* [ ] Assumptions: linear, iid-ish noise — and that real data violates them

## From scratch

* [ ] NumPy GD linear regression
* [ ] Plot loss vs step
* [ ] Compare to `sklearn.linear_model.LinearRegression`

## Applied

* [ ] When: baseline for tabular, interpretable coefficients
* [ ] When not: strong non-linearity, heavy outliers (try robust / trees)

## Mini project

* [ ] Predict a numeric column from 2–3 features; report MAE and R² on a held-out set
