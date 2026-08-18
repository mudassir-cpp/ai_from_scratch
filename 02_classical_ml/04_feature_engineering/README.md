# Feature engineering

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

## Learn

* [ ] Numeric: scale (Standard / MinMax), clip outliers
* [ ] Categorical: one-hot vs ordinal (when ordinal is a lie)
* [ ] Missing: indicator + impute
* [ ] `Pipeline` so val/test never leak fit statistics
* [ ] `ColumnTransformer` for mixed types

## Do

* [ ] One pipeline: impute → scale → one-hot → logistic
* [ ] Fit only on train; transform val/test
* [ ] Dump `pipeline.named_steps` in the project README

## Resources

* [ ] [sklearn pipelines](https://scikit-learn.org/stable/modules/compose.html)
