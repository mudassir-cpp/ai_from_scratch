# SVM — deep dive

Legend: `[ ]` not started · `[*]` in progress · `[x]` done

## What to learn

* [ ] Margin, support vectors
* [ ] Soft margin `C`
* [ ] Kernel trick intuition (RBF) — you will rarely write kernels by hand
* [ ] Scaling is mandatory
* [ ] LinearSVC vs SVC: size of data

## From scratch

* [ ] Skip a full QP solver. Implement a *linear* SVM with sklearn or a simple subgradient if you want pain
* [ ] Fit `SVC(kernel="linear")` and `SVC(kernel="rbf")` on moons vs blobs

## Applied

* [ ] When: medium tabular, clear margin, kernels on small n
* [ ] When not: millions of rows (use linear models / trees / NNs)

## Mini project

* [ ] Two datasets: one where linear SVM wins, one where RBF wins; screenshot the plots
