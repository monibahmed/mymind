+++
title = "Linear Algebra"
author = ["Monib Ahmed"]
draft = false
toc = true
type = "docs"
linktitle = "Linear Algebra"
[menu.mathematics]
  weight = 1001
  identifier = "linear-algebra"
+++

## Introduction - Linear Combinations {#introduction-linear-combinations}

This subject begins with two vectors \\(v\\) and \\(w\\), pointing in
different directions. The key step is to take their linear
combinations. That new vector is in the same place as \\(v\\) and
\\(w\\). When we take all combinations, we are filling in the whole
plane. In the langauge of linear equations, I can solve \\[cv+dw=b\\]
exactly when the vector \\(b\\) lies in the same plane as \\(v\\) and \\(w\\).


### Matrices {#matrices}

Now I can describe the first part of the book, about linear
equations \\(Ax=b\\). The matrix A has \\(n\\) columns and \\(m\\)
rows. _Linear Algebra moves steadily to n vectors in m dimensional
space._ We still want combinations of the columns (in the column
space). We still get \\(m\\) equations to produce \\(b\\) (one for each
row). Those equations may or may not have a solution. They always
have a least-square solution.

The interplay of columns and rows is the heart of linear
algebra. Here are the four key ideas:

1.  The **column space** (all combinations of the columns).
2.  The **row space** (all combinations of the rows).
3.  The **rank** (the number of independent columns) (or rows).
4.  **Elimination** (the good way to find the rank of a matrix).


### Structure of the Course {#structure-of-the-course}

The two fundamental problems are \\(Ax=b\\) and \\(Ax=\lambda x\\). The
first problem \\(Ax=b\\) has a solution when A has _independent
columns_. The second problem \\(Ax=\lambda x\\) looks for _independent
eigenvectors._ A crucial part of this course is to learn what
"independence" means".

Elimination is the simple natural way to understand a matrix by
producing a lot of zero entries. So the course starts there. You
hav eto get from combinations of the rows, to indepence of the
rows, to "dimension of the row space." That is the key goal, to
see whole spaces of vectors: the **row space** and the **column
space** and the **nullspace**.

A further goal in to understand how the matrix _acts_. When \\(A\\)
multiplies \\(x\\) it produces a new vector \\(Ax\\). The whole space of
vectors moves - it is "transformed" by \\(A\\). Special
transformations comes from particular matrices, and those are the
foundation stones of linear algebra: diagonal matrices, orthogonal
matrices, triangular matrices, symmetric matrices.

The eigenvalues of those matrices are special too. Sections 5.1
and 5.2 are worth careful reading, to see how \\(Ax = \lambdax\\) is
useful.

Overall, the beauty of linear algebra is seen in so many different
ways:

1.  **Visualization.** Combination of vector. Spaces of
    vectors. Rotations and reflection and projection of
    vectors. Perpendicular vectors. Four Fundamental subspaces.
2.  **Abstraction.** Independence of vectors. Basis and dimension of
    a vector space. Linear transformations. Singular value
    decomposition and the best basis.
3.  **Computation.** Elimination to produce zero
    entries. Gram-Schmidt to produce orthogonal
    vectors. Eigenvalues to solve differential and difference
    equations.
4.  **Applications.** Least-squares solution when \\(Ax=b\\) has too many
    equations. Difference equations approximating differental
    equations. Markiv probability matrices. Orthogonal eigenvectors
    as principal axes (and more...).


## Matrics and Gaussian Elimination {#matrics-and-gaussian-elimination}


### Introduction {#introduction}

-   Solving Linear Equations Certainly constants A, B, C, D, E, and F determine the values of \\(x\\) and \\(y\\).
    -   Elimination
    -   Determinants
    -   Gaussian Elimination
-   Geometry of Planes
-   Matrix Notation
-   Elimination Breakdowns
-   Number of Elimination Steps


### Geometry of Linear Equations {#geometry-of-linear-equations}

-   Row picture and Column Picture
    -   "The problem is to find the combination of the column vectors
        on the left side that produces the vector on the right side."
    -   Column Vectors and Linear Combinations
    -   Singular Cases


### Gaussian Elimination {#gaussian-elimination}

-   "Method starts by subtracting multiples of the first equation from the other equations."
-   The Cost of Elimination


### Matrix Notation and Matrix Multiplication {#matrix-notation-and-matrix-multiplication}

-   Coefficient Matrix
-   Row times column
-   Matrix multiplication


### Triangular Factors and Row Exchanges {#triangular-factors-and-row-exchanges}

-   Upper triangular: all entries below the diagonal are zero


### Inverses and Tranposes {#inverses-and-tranposes}

-   "If you multiply by \\(A\\) and then multiply by \\(A^{-1}\\), you are
    back to where you started."
-   "Not all matrices have inverses. An inverse is impossible when
    \\(Ax\\) is zero and \\(x\\) is nonzero."
-   Gauss-Jordan Method for \\(A^{-1}\\)
-   Invertible matrices
-   Tranpose Matrix
-   Symmetric Matrices


### Special Matrices and Applications {#special-matrices-and-applications}


## Vectors Spaces {#vectors-spaces}


### Vector Spaces and Subspaces {#vector-spaces-and-subspaces}


### Solving \\(Ax=0\\) and \\(Ax=b\\) {#solving--ax-0--and--ax-b}


### Linear Independence, Basis and Dimension {#linear-independence-basis-and-dimension}


### Four Fundamental Subspaces {#four-fundamental-subspaces}


### Graphs and Networks {#graphs-and-networks}


### Linear Transformations {#linear-transformations}


## Orthogonality {#orthogonality}


### Orthogonal Vectors and Subspaces {#orthogonal-vectors-and-subspaces}


### Cosiines and Projections onto Lines {#cosiines-and-projections-onto-lines}


### Projections and Least Squares {#projections-and-least-squares}


### Orthogonal Bases and Gram-Schmidt {#orthogonal-bases-and-gram-schmidt}


### Fast Fourier Transform {#fast-fourier-transform}


## Determinants {#determinants}


### Introduction {#introduction}


### Properties {#properties}


### Formulas {#formulas}


### Applications {#applications}


## Eigenvalues and Eigenvectors {#eigenvalues-and-eigenvectors}


### Introduction {#introduction}


### Diagonilization of a Matrix {#diagonilization-of-a-matrix}


### Difference Equations of Powers \\(A^k\\) {#difference-equations-of-powers--a-k}


### Differential Equations and \\(e^{At}\\) {#differential-equations-and--e-at}


### Complex Matrices {#complex-matrices}


### Similarity Transformations {#similarity-transformations}


## Positive Definite Matrices {#positive-definite-matrices}


### Minima, Maxima, and Saddle Points {#minima-maxima-and-saddle-points}


### Tests for Positive Definiteness {#tests-for-positive-definiteness}


### Signular Value Decomposition {#signular-value-decomposition}


### Minimum Principles {#minimum-principles}


### Finite Element Method {#finite-element-method}


## Computation with Matrices {#computation-with-matrices}


### Introduction {#introduction}


### Matrix Norm and Condition Number {#matrix-norm-and-condition-number}


### Computation of Eigenvalues {#computation-of-eigenvalues}


### Iterative Methods for \\(Ax=b\\) {#iterative-methods-for--ax-b}


## Linear Programming and Game Theory {#linear-programming-and-game-theory}


### Linear Inequalities {#linear-inequalities}


### Simplex Method {#simplex-method}


### Dual Problem {#dual-problem}


### Network Model {#network-model}


### Game Theory {#game-theory}