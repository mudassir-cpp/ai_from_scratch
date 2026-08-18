# NumPy vectorization — deep dive

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

## What to learn

* [ ] `ndarray` shape, dtype, `axis`
* [ ] Indexing, slicing, boolean masks
* [ ] Broadcasting rules
* [ ] `@`, `dot`, element-wise ops
* [ ] Why loops on rows are slow

## From scratch

* [ ] `dot(a,b)` with a loop, then NumPy — assert equal
* [ ] Standardize a column: `(x - mean) / std`
* [ ] Replace a 20-line loop with one vectorized line

## Applied

* [ ] When: all tabular + tensor prep
* [ ] When not: giant sparse matrices (use scipy.sparse later)

## Mini drill

* [ ] Batch of 1000 vectors → pairwise cosine similarity matrix (NumPy only)
