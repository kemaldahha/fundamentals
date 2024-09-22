---
layout: default
---
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]},
    "HTML-CSS": { linebreaks: { automatic: true } },
    SVG: { linebreaks: { automatic: true } }
  });
</script>
<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# Vector Magnitude Notation or Norm

The **magnitude** or **norm** of a vector $\mathbf v$ can be represented as:

$$
\mathbf \| v \|
$$

# Orthonormal Basis

An **orthonormal basis** consists of vectors that are both **orthogonal** to each other and of **unit length** (norm 1). For example, in the Euclidean space $\mathbb{R}^3$, the set of vectors ${\mathbf{e_1}, \mathbf{e_2}, \mathbf{e_3}}$ forms the **standard basis**, where:

$$
e_1 = \begin{pmatrix} 1 \\ 0 \\ 0 \end{pmatrix}, \quad e_2 = \begin{pmatrix} 0 \\ 1 \\ 0 \end{pmatrix}, \quad e_3 = \begin{pmatrix} 0 \\ 0 \\ 1 \end{pmatrix}
$$

Each vector is orthogonal to the others and has a norm of 1: 

$$
\mathbf{e_1} \cdot \mathbf{e_2} = \mathbf{e_1} \cdot \mathbf{e_3} = \mathbf{e_2} \cdot \mathbf{e_3} = 0
$$

$$
\| \mathbf{e_1} \| = \| \mathbf{e_2} \| = \| \mathbf{e_3} \| = 1
$$

Any vector in $\mathbb{R}^3$ can be expressed as a combination of these basis vectors.

# Orthogonality

Two vectors in a vector space $\mathbf V$ are said to be **orthogonal** if their dot product is 0:

$$
\mathbf{v_1} \cdot \mathbf{v_2} = 0
$$

# Vector Space

A **vector space** (or **linear space**) is a collection of vectors where two operations are defined: **vector addition** and **scalar multiplication**. These operations must satisfy certain properties, such as associativity, commutativity, and distributivity.

### Definition

Formally, a vector space is a set $V$ (the set of vectors) along with a field $F$ (the set of scalars) that satisfies the following properties for all vectors $\mathbf{v}, \mathbf{w} \in V$ and scalars $a, b \in F$:

1. **Closure under addition**: If $\mathbf{v}, \mathbf{w} \in V$, then $\mathbf{v} + \mathbf{w} \in V$.
2. **Closure under scalar multiplication**: If $\mathbf{v} \in V$ and $a \in F$, then $a \mathbf{v} \in V$.
3. **Associativity of addition**: $(\mathbf{v} + \mathbf{w}) + \mathbf{u} = \mathbf{v} + (\mathbf{w} + \mathbf{u})$ for all $\mathbf{v}, \mathbf{w}, \mathbf{u} \in V$.
4. **Commutativity of addition**: $\mathbf{v} + \mathbf{w} = \mathbf{w} + \mathbf{v}$ for all $\mathbf{v}, \mathbf{w} \in V$.
5. **Additive identity**: There exists a vector $\mathbf{0} \in V$ such that $\mathbf{v} + \mathbf{0} = \mathbf{v}$ for all $\mathbf{v} \in V$.
6. **Additive inverse**: For every $\mathbf{v} \in V$, there exists a vector $-\mathbf{v} \in V$ such that $\mathbf{v} + (-\mathbf{v}) = \mathbf{0}$.
7. **Associativity of scalar multiplication**: $a(b \mathbf{v}) = (ab) \mathbf{v}$ for all $a, b \in F$ and $\mathbf{v} \in V$.
8. **Distributivity of scalar multiplication with respect to vector addition**: $a(\mathbf{v} + \mathbf{w}) = a \mathbf{v} + a \mathbf{w}$ for all $a \in F$ and $\mathbf{v}, \mathbf{w} \in V$.
9. **Distributivity of scalar multiplication with respect to scalar addition**: $(a + b) \mathbf{v} = a \mathbf{v} + b \mathbf{v}$ for all $a, b \in F$ and $\mathbf{v} \in V$.
10. **Scalar multiplication identity**: $1 \mathbf{v} = \mathbf{v}$ for all $\mathbf{v} \in V$, where 1 is the multiplicative identity in the field $F$.

### Example: Euclidean Space

One of the most familiar examples of a vector space is **Euclidean space**, such as $\mathbb{R}^2$ or $\mathbb{R}^3$, where vectors are represented as tuples of real numbers. For example, in $\mathbb{R}^2$, vectors have the form:

$$
\mathbf{v} = \begin{pmatrix} v_1 \\ v_2 \end{pmatrix}
$$

### Example: Function Space

Another example of a vector space is the space of functions, where vectors are functions, and scalar multiplication or addition follows function rules.

A **subspace** is a subset of a vector space that is also a vector space under the same operations. For example, the set of all vectors in $\mathbb{R}^3$ that lie on a plane through the origin forms a subspace of $\mathbb{R}^3$.

# Element of symbol $\in$

$\in$ means "belongs to". It originates from Set Theory and denotes membership in a set or space. 

For example, if we have a set $A=\{1, 2, 3\}$, we can say:

$$
1 \in A
$$

Or, if we have a vector $\mathbf v$ in a vector space $V$, we can say:

$$
\mathbf v \in V
$$

# Square of magnitude of vector $\mathbf v$

### Vector Algebra

The magnitude or norm of a vector squared is:

$$
\| \mathbf{v} \|^2 = \mathbf{v} \cdot \mathbf{v}
$$

This represents the dot product of the vector with itself.

For example, if we have $\mathbf v \in \mathbb{R}^3$:

$$
\mathbf v = \begin{pmatrix} v_1 \\ v_2 \\ v_3 \end{pmatrix}
$$

then:
$$
\| \mathbf{v} \|^2 = \mathbf{v} \cdot \mathbf{v} = \begin{pmatrix} v_1 \\ v_2 \\ v_3 \end{pmatrix} \begin{pmatrix} v_1 \\ v_2 \\ v_3 \end{pmatrix} = v_1^2 + v_2^2 + v_3^2
$$

### Matrix Algebra

In vector algebra, it doesn't matter whether we represent vectors as row vectors or column vectors, they are essentially the same objects.

However, in matrix algebra, we must be mindful of the shape of a vector (column or row). 
Specifically, the dot product between two vectors in matrix algebra requires that one vector is transposed to align dimensions.

To compute the norm squared in matrix algebra, we use the transpose of the vector:

$$
\| \mathbf{v} \|^2 = \mathbf{v}^T \mathbf{v}
$$

Taking the example above:

$$
\| \mathbf{v} \|^2 = \mathbf{v} \cdot \mathbf{v} = \begin{pmatrix} v_1 & v_2 & v_3 \end{pmatrix} \begin{pmatrix} v_1 \\ v_2 \\ v_3 \end{pmatrix} = v_1^2 + v_2^2 + v_3^2
$$

# Transpose of a matrix

The transpose of a matrix $\mathbf A$ is obtained by swapping the rows and columns of $\mathbf A$. This means the first row becomes the first column, the second row becomes the second column, and so on.

This can also be represented as:

$$
\mathbf{(A^T)_{ij}} = \mathbf{A_{ji}}
$$

# Transpose of a Matrix Product $(\mathbf{A} \mathbf{B})^T = \mathbf{B}^T \mathbf{A}^T$

The transpose of a product of two matrices is equal to the product of the matrices' transposes in reverse order.

Definitions:
- Let $ \mathbf{A} $ be an $ m \times n $ matrix.
- Let $ \mathbf{B} $ be an $ n \times p $ matrix.

We know that:

$$
((\mathbf{A} \mathbf{B})^T)_{ij} = (\mathbf{A} \mathbf{B})_{ji}
$$

By the definition of matrix multiplication, the $ (j,i) $-th entry of $ \mathbf{A} \mathbf{B} $ is:

$$
(\mathbf{A} \mathbf{B})_{ji} = \sum_{k=1}^n \mathbf{A}_{jk} \mathbf{B}_{ki}
$$

This represents the dot product of the $ j $-th row of $ \mathbf{A} $ and the $ i $-th column of $ \mathbf{B} $, where $ k $ runs over the shared dimension $ n $.

Now, let's write the same summation for $ \mathbf{B}^T \mathbf{A}^T $:

$$
(\mathbf{B}^T \mathbf{A}^T)_{ij} = \sum_{k=1}^n \mathbf{B}_{ki} \mathbf{A}_{jk}
$$

Thus, we find that:

$$
((\mathbf{A} \mathbf{B})^T)_{ij} = (\mathbf{B}^T \mathbf{A}^T)_{ij}
$$

Hence:

$$
(\mathbf{A} \mathbf{B})^T = \mathbf{B}^T \mathbf{A}^T
$$

# Transpose of a Matrix Product with arbitrary number of matrices 

We can extend this property to a product of an arbitrary number of matrices $(\mathbf{A_1}  \mathbf{A_2} ... \mathbf{A_K})^T$


$$
\left( \prod_{i=1}^K \mathbf{A_i} \right)^T = (\mathbf{A_1}  \mathbf{A_2} ... \mathbf{A_K})^T
$$

By applying the transpose to the first matrix and the rest of the product, we get:

$$
(\mathbf{A_1}  \mathbf{A_2} ... \mathbf{A_K})^T = (\mathbf{A_1}  \mathbf{B_1})^T 
$$

Where:

$$
\mathbf {B_1} = \mathbf{A_2} ... \mathbf{A_K}
$$

Now applying the transpose:

$$
(\mathbf{A_1}  \mathbf{B_1})^T = \mathbf{B_1}^T  \mathbf{A_1}^T
$$

Continuing this process recursively for each matrix, we eventually get:

$$
\prod_{i=K}^1 \mathbf{A_i}^T = \mathbf{A_K}^T  \mathbf{A_{K-1}}^T ... \mathbf{A_1}^T
$$

For 3 matrices $\mathbf{A}$, $\mathbf{B}$, and $\mathbf{C}$:

$$
(\mathbf{A} \mathbf{B} \mathbf{C})^T = \mathbf{C}^T \mathbf{B}^T \mathbf{A}^T
$$

# Derivative of the Quadratic Form $\frac {\partial} {\partial \mathbf{x}} (\mathbf{x}^T \mathbf{A} \mathbf{x})$

$$
\begin{align*}
\frac {\partial} {\partial \mathbf{x}} (\mathbf{x}^T \mathbf{A} \mathbf{x}) &=
\frac {\partial} {\partial \mathbf{x}}(\mathbf{x}^T) \mathbf{A} \mathbf{x} + 
\mathbf{x}^T \frac {\partial} {\partial  \mathbf{x}} (\mathbf{A} \mathbf{x}) \\ &=
\left(\frac {\partial \mathbf{x}} {\partial \mathbf{x}}\right)^T \mathbf{A} \mathbf{x} + 
\mathbf{x}^T \frac {\partial} {\partial \mathbf{x}} (\mathbf{A} \mathbf{x}) \\ &=
\mathbf{A} \mathbf{x} + \mathbf{x}^T \mathbf{A} \\ &=
\mathbf{x}^T \mathbf{A}^T + \mathbf{x}^T \mathbf{A} \\ &=
\mathbf{x}^T (\mathbf{A}^T + \mathbf{A})
\end{align*}
$$

If $\mathbf A$ is symmetric, then:

$$
\frac {\partial} {\partial \mathbf{x}} (\mathbf{x}^T \mathbf{A} \mathbf{x}) = 2 \mathbf{x}^T \mathbf{A} = 2 \mathbf{A} \mathbf{x}
$$

# Singular Matrix

A singular matrix is a **square matrix** that does not have an inverse. In other words, for a matrix $\mathbf A$, if there is no matrix $\mathbf B$ such that:

$$
\mathbf{A} \mathbf{B} = \mathbf{B} \mathbf{A} = \mathbf{I}
$$

then $\mathbf{A}$ is called a singular matrix.

Properties of singular matrices:
1. Determinant is zero: $\det(\mathbf A)=0$. This indicates that the matrix compresses space in such a way that the volume of the transformed space collapses to zero, implying no unique inverse exists.
2. Linearly dependent rows or columns
3. Rank deficiency (i.e. rank smaller than number of rows or columns)
4. No unique solution to $\mathbf{A} \mathbf{x} = \mathbf{b}$

# Why is the determinant zero of an uninvertible matrix?

Determinant is like a scaling factor by which the matrix transforms the volume of an object in space. For a $2 \times 2$ matrix, the determinant represents the area of the parallelogram formed by the transformed basis vectors. For a a $3 \times 3$ it's a parallelepiped.

If the determinant is non-zero, the matrix transforms space by stretching or compressing it, but still preserves some volume (or area in 2D). A non-zero determinant indicates that the transformation is invertible — you can "undo" the transformation and recover the original space.

However, when the determinant is zero, the matrix collapses the space into a lower dimension (e.g., turning a 3D space into a 2D plane or a 2D plane into a line). In this case, the matrix has compressed all the volume to zero, effectively squashing the space into a flat, lower-dimensional subspace. This means that **information is lost** — points that were distinct before the transformation may now overlap after the transformation.

# Why can only square matrices have an inverse?

A square matrix maps between spaces of the same dimension ($\mathbb {R}^n$ to $\mathbb {R}^n$). Such transformations are reversible, as long as the matrix spans $\mathbb{R}^n$, meaning it is full rank.

On the other hand, a rectangular matrix maps between spaces of different dimensions ($\mathbb {R}^n$ to $\mathbb {R}^m$). This means that a rectangular matrix $\mathbf A$ takes an input vector $\mathbf{x} \in \mathbb {R}^n$ and outputs a vector $\mathbf{y} = \mathbf{A} \mathbf{x} \in \mathbb{R}^m$

If:
- $n>m$: dimensions are reduced, information is lost, cannot invert and span $\mathbb{R}^n$ again.
- $n<m$: dimensions are expanded, but the output cannot span the full space $\mathbb{R}^m$. Instead, it is in a subspace of dimension $n$ in $\mathbb {R}^m$ space

Therefore rectangular matrix tranformations are non-invertible and an inverse is not defined.