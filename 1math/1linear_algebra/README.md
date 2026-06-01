# Linear Algebra for AI — Roadmap

# concepts
* scalars
* vectors

* matrices
* tensors
* matrix multiplication
* dot product
* cross product
* transpose
* inverse
* identity matrix
* rank
* span
* basis
* vector space
* linear independence
* linear combination
* linear transformation

advanced concepts

* norms (L1, L2, Lp)
* eigenvalues
* eigenvectors
* eigenspaces
* diagonalization
* SVD (singular value decomposition)
   1.https://www.youtube.com/watch?v=mhy-ZKSARxI
   2.https://www.youtube.com/watch?v=vSczTbgc8Rc
  
* PCA (principal component analysis) [ included in Machine learning Playlist by stat quest so do it later]
* orthogonality
* projections
* orthonormal basis

techniques

* feature scaling (normalization, standardization)
  1.https://www.youtube.com/watch?v=XdDNtNkLbhY
  2.https://www.youtube.com/watch?v=sxEqtjLC0aM
* vectorization (replace loops with matrix ops) [ using numpy for all math operation to override python interpreter overhead]
* matrix factorization
* dimensionality reduction
    [Dimensionality Reduction in Machine Learning — Simplifying Complex Data for Better Insights](https://anilpise7.medium.com/dimensionality-reduction-in-machine-learning-simplifying-complex-data-for-better-insights-a2181c2b519b)
  
* similarity measures (cosine similarity, euclidean distance)
[cosine simlirity short](https://www.youtube.com/shorts/rmNNK42Asd0)
* gradient representation in matrix form
* batching (data in matrix form) [DEEP SEEK LINK](https://chat.deepseek.com/share/5qlixq0inxy7op92yy)

libraries

* numpy
* pytorch
* tensorflow	High	Fast but sharp	May overfit
Full batch	Small datasets (< 10K)	Very high	Smooth, accurate	Guaranteed descent

* jax
* scipy

practical usage in AI

* linear regression
* logistic regression
* neural networks (forward pass as matrix ops)
* backpropagation (chain rule in matrices)
* embeddings (word/sentence vectors)
* recommendation systems
* clustering (k-means, distance-based)
* nearest neighbor search

code practice (do before moving to next topic)

* implement vector addition (from scratch + numpy)
* implement dot product manually
* implement matrix multiplication (triple loop)
* compute transpose of a matrix manually
* compute inverse using numpy
* compute rank of a matrix
* compute L1 and L2 norms manually
* implement cosine similarity between two vectors
* implement linear regression using only numpy
* build simple neural network forward pass (no libraries)
* implement k-nearest neighbors using distance formula
* implement PCA using numpy (basic version)
