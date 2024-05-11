# Linear Algebra

## Vectors, Matrices, Norms, Subspaces, Projections, SVD, EVD, Derivatives of matrices, Vector Derivative Identities, Least Squares

Here's a breakdown of key linear algebra concepts for your Machine Learning exam preparation:

**1. Vectors:**

- **Concept:** Ordered collections of numbers representing quantities with magnitude and direction. Used extensively to represent data points, model parameters, and features in ML.
- **Operations:** Addition, subtraction, scalar multiplication, dot product (inner product), and cross product (outer product).
- **Tips:**
    - Understand the geometric interpretation of vectors, especially dot product, which measures projection and similarity.
    - Practice vector manipulations and calculations relevant to ML (e.g., feature representation, distance metrics).

**2. Matrices:**

- **Concept:** Rectangular arrays of numbers used to store and manipulate large datasets, linear transformations, and relationships between variables.
- **Operations:** Addition, subtraction, scalar multiplication, matrix multiplication, transpose, determinant (invertible matrices).
- **Tips:**
    - Grasp the concept of matrix multiplication as a transformation applied to vectors.
    - Be familiar with special matrix types (e.g., identity matrix, diagonal matrix) and their properties.
    - Practice matrix operations for common ML tasks (e.g., linear regression, matrix factorization).

**3. Norms:**

- **Concept:** Measure the "length" or magnitude of a vector. Common norms include L1 norm (Manhattan distance), L2 norm (Euclidean distance), and infinity norm.
- **Formulae:**
    - L1 norm: \\( ||x||_1 = Σ |x_i| \\)
    - L2 norm: \\( ||x||_2 = sqrt(Σ x_i^2) \\)
    - Infinity norm: \\( ||x||_∞ = max(|x_i|) \\)
- **Tips:**
    - Understand how different norms impact optimization algorithms in ML (e.g., L1 norm promotes sparsity, L2 norm helps with regularization).
    - Use norms to measure distances between data points or errors in ML models.

**4. Subspaces:**

- **Concept:** Collections of vectors within a vector space that satisfy certain closure properties (closed under addition and scalar multiplication).
- **Examples:** Column space, row space, null space of a matrix.
- **Tips:**
    - Subspaces represent specific sets of possible data points or model outputs.
    - Analyze subspaces to understand the capabilities and limitations of linear models in ML.

**5. Projections:**

- **Concept:** The orthogonal projection of a vector onto a subspace is the vector in the subspace closest to the original vector.
- **Formula (Projection of x onto subspace S):**
    $$proj_S(x) = (x^T * S * S^T) * x$$
- **Tips:**
    - Projections are used in dimensionality reduction techniques like Principal Component Analysis (PCA).
    - Understand how projections affect data points and their interpretations in the context of ML algorithms.

**6. Singular Value Decomposition (SVD):**

- **Concept:** Decomposes a matrix into three matrices: \\(U\\) (left singular vectors), \\(Σ\\) (singular values), and \\(V^T\\) (right singular vectors).
- **Formula:**
    $$A = U * Σ * V^T$$
- **Tips:**
    - SVD helps reveal the underlying structure of data, enabling dimensionality reduction and matrix factorization techniques.
    - Use SVD for recommender systems, anomaly detection, and information retrieval in ML.

**7. Eigenvalue Decomposition (EVD):**

- **Concept:** Decomposes a square matrix into its eigenvalues (scalars) and eigenvectors (non-zero vectors). Eigenvalues tell us how much a transformation scales a vector, and eigenvectors represent the directions along which the transformation scales.
- **Formula:**
	$$A * v = λ * v$$
    where A is the matrix, v is the eigenvector, and λ is the eigenvalue.
- **Tips:**
    - EVD helps analyze linear transformations and identify directions of maximum variance in data, useful for PCA and feature selection in ML.
    - Understand the relationship between eigenvalues and eigenvectors, as they reveal important properties of the matrix.

**8. Derivatives of Matrices:**

- **Concept:** Calculate the rate of change of a matrix-valued function with respect to a scalar variable.
- **Formulae:** (Specific formulae depend on the function)
- **Tips:**
    - Derivatives of matrices are crucial for back-propagation in training neural networks, where gradients guide parameter updates.
    - Master differentiation rules for matrix operations to perform gradient calculations effectively.

**9. Vector Derivative Identities:**

- **Concept:** Special identities that hold true when differentiating vector-valued functions with respect to a scalar variable.
- **Examples:** Chain rule, product rule, summation rule.
- **Importance:** Simplify calculations in back-propagation and other gradient-based optimization methods in ML.

**10. Least Squares:**

- **Concept:** Method for finding the best-fitting line or curve (linear regression) to minimize the sum of squared errors between the data points and the predicted values.
- **Formula:**
    $$argmin_w ||A w - b||^2$$
    where:
    - A is the design matrix
    - w is the weight vector
    - b is the bias vector
- **Importance:** Foundational concept for linear regression, used in various ML models for finding optimal parameters.

By understanding these core linear algebra concepts and their applications in ML, you'll be well-positioned to tackle problems involving vector operations, matrix manipulations, and optimization techniques in your exams. Remember to practice applying these concepts to sample problems and deepen your understanding.
