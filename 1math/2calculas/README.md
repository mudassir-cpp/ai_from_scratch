# Calculus for AI Roadmap

> Goal: Learn the calculus required to understand optimization, neural networks, backpropagation, gradient-based learning, and modern AI systems.

---

# Core Concepts

## Functions

### Scalar Functions

* [ ] Understand scalar-valued functions
* [ ] Domain and range
* [ ] Input → output mapping
* [ ] Polynomial functions
* [ ] Exponential functions
* [ ] Logarithmic functions
* [ ] Trigonometric functions

```text
f(x) = x²
f(x) = eˣ
f(x) = log(x)
```

### Vector Functions

* [ ] Vector inputs
* [ ] Vector outputs
* [ ] Multivariable functions
* [ ] Function composition

```text
f(x,y,z)
f(x⃗)
```

### Composite Functions

* [ ] Nested functions
* [ ] Function pipelines
* [ ] Neural network layers as function compositions

```text
f(g(h(x)))
```

---

## Limits & Continuity

* [ ] Intuition of limits
* [ ] Approaching a value
* [ ] Left-hand and right-hand limits
* [ ] Continuous functions
* [ ] Discontinuous functions
* [ ] Why continuity matters in optimization

```text
lim x→a f(x)
```

---

## Single Variable Derivatives

### Meaning

* [ ] Instantaneous rate of change
* [ ] Slope of a curve
* [ ] Local sensitivity

```text
f'(x)
df/dx
```

### Rules

* [ ] Constant rule
* [ ] Power rule
* [ ] Sum rule
* [ ] Product rule
* [ ] Quotient rule
* [ ] Chain rule

### Important AI Functions

* [ ] Derivative of xⁿ
* [ ] Derivative of eˣ
* [ ] Derivative of log(x)
* [ ] Derivative of sigmoid
* [ ] Derivative of tanh
* [ ] Derivative of ReLU

```text
sigmoid(x) = 1/(1+e⁻ˣ)

sigmoid'(x)
=
sigmoid(x)(1-sigmoid(x))
```

```text
tanh'(x)
=
1 - tanh²(x)
```

---

# Multivariable Calculus

## Partial Derivatives

* [ ] Multiple inputs
* [ ] Differentiate w.r.t one variable
* [ ] Hold others constant

```text
∂f/∂x
∂f/∂y
```

Example:

```text
f(x,y)=x²+y²

∂f/∂x = 2x
∂f/∂y = 2y
```

---

## Gradient

### Definition

* [ ] Collection of partial derivatives
* [ ] Gradient vector
* [ ] Direction of steepest increase
* [ ] Magnitude interpretation

```text
∇f
=
[
∂f/∂x,
∂f/∂y
]
```

### Intuition

* [ ] "Which direction increases fastest?"
* [ ] Optimization interpretation
* [ ] Loss surface navigation

---

## Gradient in Matrix Form

* [ ] Gradient vectors
* [ ] Jacobian intuition
* [ ] Matrix calculus basics
* [ ] Connection with Linear Algebra
* [ ] Column vectors vs row vectors
* [ ] Parameter vector gradients

```text
θ = [θ₁ θ₂ ... θₙ]

∇J(θ)
```

---

## Directional Derivative

* [ ] Derivative in arbitrary direction
* [ ] Relationship with gradient
* [ ] Unit direction vectors

```text
Dᵤf
=
∇f · u
```

---

# Chain Rule

## Single Variable

* [ ] Derivative of nested functions

```text
d/dx f(g(x))
=
f'(g(x))g'(x)
```

---

## Multivariable Chain Rule

* [ ] Dependency graphs
* [ ] Intermediate variables
* [ ] Computational graphs

```text
z=f(y)

y=g(x)
```

```text
dz/dx
=
(dz/dy)(dy/dx)
```

---

## Matrix Chain Rule

* [ ] Vector-valued functions
* [ ] Jacobian multiplication
* [ ] Neural network gradients
* [ ] Foundation of backpropagation

---

# Second Order Calculus

## Hessian Matrix

### Definition

* [ ] Matrix of second derivatives
* [ ] Curvature information
* [ ] Optimization interpretation

```text
H(f)
=
[
∂²f/∂xᵢ∂xⱼ
]
```

### Usage

* [ ] Detect minima
* [ ] Detect maxima
* [ ] Detect saddle points
* [ ] Newton methods

---

## Taylor Series

### First Order Approximation

* [ ] Local linear approximation

```text
f(x+h)
≈
f(x)+f'(x)h
```

### Second Order Approximation

* [ ] Curvature correction
* [ ] Hessian connection

```text
f(x+h)
≈
f(x)
+
f'(x)h
+
(1/2)f''(x)h²
```

### AI Usage

* [ ] Optimization analysis
* [ ] Loss landscape approximation
* [ ] Newton-style methods

---

# Optimization Concepts

## Convexity

* [ ] Convex functions
* [ ] Concave functions
* [ ] Convex sets
* [ ] Why convex optimization is easier

### Learn

* [ ] Local minima
* [ ] Global minima
* [ ] Saddle points
* [ ] Non-convex landscapes

---

## Gradient Descent

### Core Idea

* [ ] Move opposite the gradient
* [ ] Iterative optimization
* [ ] Learning rate

```text
θ
=
θ
-
α∇J(θ)
```

### Variants

* [ ] Batch Gradient Descent
* [ ] Stochastic Gradient Descent (SGD)
* [ ] Mini-batch Gradient Descent
* [ ] Momentum
* [ ] Adam intuition

---

# Loss Functions

| Loss Function             | Formula                    | Gradient               |
| ------------------------- | -------------------------- | ---------------------- |
| MSE                       | (ŷ-y)²                    | 2(ŷ-y)                |
| MAE                       | |ŷ-y|                     | sign(ŷ-y)             |
| Binary Cross Entropy      | -(ylog(ŷ)+(1-y)log(1-ŷ)) | Derived via chain rule |
| Categorical Cross Entropy | -Σ y log(ŷ)               | Softmax - target       |

### Learn

* [ ] Why losses exist
* [ ] Error surfaces
* [ ] Gradient behavior
* [ ] Stable optimization

---

# Activation Function Derivatives

## Sigmoid

* [ ] Forward equation
* [ ] Derivative derivation
* [ ] Vanishing gradients

```text
σ'(x)
=
σ(x)(1-σ(x))
```

---

## Tanh

* [ ] Range [-1,1]
* [ ] Derivative

```text
1 - tanh²(x)
```

---

## ReLU

* [ ] Piecewise definition
* [ ] Dead neurons

```text
0 if x<0
1 if x>0
```

---

## Leaky ReLU

* [ ] Small negative slope
* [ ] Gradient flow

---

## Softmax

* [ ] Probability outputs
* [ ] Jacobian matrix
* [ ] Cross-entropy simplification

Learn:

* [ ] Softmax derivative
* [ ] Softmax Jacobian
* [ ] Softmax + Cross Entropy gradient

---

# Backpropagation

## Intuition

* [ ] Neural network as function composition
* [ ] Computational graph
* [ ] Error propagation
* [ ] Gradient flow

---

## Learn

* [ ] Forward pass
* [ ] Loss calculation
* [ ] Backward pass
* [ ] Weight updates
* [ ] Bias gradients
* [ ] Layer-wise gradients

---

## Chain Rule in Backprop

* [ ] Local derivatives
* [ ] Gradient accumulation
* [ ] Matrix chain rule
* [ ] Efficient gradient computation

---

# Matrix Calculus (AI Focus)

## Learn

* [ ] Vector derivatives
* [ ] Matrix derivatives
* [ ] Jacobian matrix
* [ ] Hessian matrix
* [ ] Gradient of dot product
* [ ] Gradient of matrix multiplication

Examples:

```text
d(wᵀx)/dw
```

```text
d(Ax)/dx
```

```text
d(xᵀAx)/dx
```

---

# Libraries

| Library    | Purpose                   |
| ---------- | ------------------------- |
| NumPy      | Calculus implementations  |
| SymPy      | Symbolic differentiation  |
| SciPy      | Optimization              |
| PyTorch    | Automatic differentiation |
| TensorFlow | Computational graphs      |
| JAX        | Functional autodiff       |
| Matplotlib | Visualizing functions     |

---

# Practical Usage in AI

## Understand Where Calculus Appears

### Neural Networks

* [ ] Backpropagation
* [ ] Weight updates
* [ ] Gradient flow

### Deep Learning

* [ ] Loss minimization
* [ ] Optimization
* [ ] Training loops

### Machine Learning

* [ ] Linear Regression
* [ ] Logistic Regression
* [ ] SVM optimization intuition

### LLMs

* [ ] Transformer training
* [ ] Cross-entropy optimization
* [ ] Billion-parameter gradient descent

### Reinforcement Learning

* [ ] Policy gradients
* [ ] Reward optimization

---

# Code Practice

## Numerical Differentiation

* [ ] Forward Difference Method
* [ ] Central Difference Method
* [ ] Compare numerical vs analytical derivatives

Implement:

```python
numerical_derivative(f, x)
```

---

## Partial Derivatives

Implement:

```python
partial_x(f, x, y)
partial_y(f, x, y)
```

Learn:

* [ ] Numerical partial derivatives
* [ ] Multivariable functions

---

## Gradient From Scratch

Implement:

```python
gradient(f, point)
```

Practice:

* [ ] 2D surfaces
* [ ] 3D surfaces
* [ ] Gradient visualization

---

## Gradient Descent

### 1 Variable

Implement:

```python
gradient_descent_1d()
```

Learn:

* [ ] Learning rate effects
* [ ] Convergence
* [ ] Overshooting

---

### 2 Variables

Implement:

```python
gradient_descent_2d()
```

Learn:

* [ ] Contour plots
* [ ] Loss landscapes

---

### Linear Regression

Implement from scratch:

```python
y = wx + b
```

Without frameworks:

* [ ] Manual gradients
* [ ] MSE gradient
* [ ] Parameter updates

---

## Backpropagation From Scratch

### Single Neuron

Implement:

* [ ] Forward pass
* [ ] Loss
* [ ] Gradient
* [ ] Update step

---

### Two-Layer Neural Network

Using NumPy only:

* [ ] Forward propagation
* [ ] Sigmoid/ReLU
* [ ] Backpropagation
* [ ] Weight gradients
* [ ] Bias gradients
* [ ] Training loop

---

## Gradient Checking

Implement:

```python
gradient_check()
```

Compare:

```text
Numerical Gradient
vs
Analytical Gradient
```

Learn:

* [ ] Debugging backprop
* [ ] Finite difference approximation

---

# Recommended Videos

## 3Blue1Brown

* [ ] Essence of Calculus Playlist

  * https://www.3blue1brown.com/topics/calculus

* [ ] Backpropagation Calculus

  * https://www.3blue1brown.com/lessons/backpropagation-calculus

* [ ] What is Backpropagation Really Doing?

  * https://www.3blue1brown.com/lessons/backpropagation

These are excellent for intuition building and visual understanding.

---

## StatQuest

* [ ] Gradient Descent, Step-by-Step

  * https://www.youtube.com/watch?v=sDv4f4s2SB8

* [ ] Stochastic Gradient Descent

  * https://www.youtube.com/watch?v=vMh0zPT0tLI

Useful for practical ML optimization intuition.

---

# AI Calculus Completion Checklist

## Phase 1 — Foundations

* [ ] Functions
* [ ] Limits
* [ ] Continuity
* [ ] Derivatives
* [ ] Basic chain rule

## Phase 2 — Multivariable Calculus

* [ ] Partial derivatives
* [ ] Gradient
* [ ] Directional derivatives
* [ ] Matrix gradients

## Phase 3 — Optimization

* [ ] Convexity
* [ ] Gradient descent
* [ ] Loss functions
* [ ] Learning rates

## Phase 4 — Deep Learning Calculus

* [ ] Activation derivatives
* [ ] Jacobians
* [ ] Hessians
* [ ] Backpropagation
* [ ] Matrix chain rule

## Phase 5 — Implementation

* [ ] Numerical derivatives
* [ ] Gradient descent from scratch
* [ ] Linear regression from scratch
* [ ] Neural network from scratch
* [ ] Gradient checking

---

# Final Goal

* [ ] Read gradient equations comfortably
* [ ] Understand backpropagation mathematically
* [ ] Implement gradient descent from scratch
* [ ] Implement neural network training from scratch
* [ ] Understand PyTorch autograd internals
* [ ] Be mathematically ready for Deep Learning, Transformers, LLMs, RL, and modern AI research
