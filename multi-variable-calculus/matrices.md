---
layout: default
---

# Matrices

## Conceptually

## Addition and Subtraction
Matrices **of the same size** can be added and subtracted together, by adding or subtracting each and every corresponding element.

$$
\begin{bmatrix}
2 & 3 & 8\\
12 & 8 & 5\\
2 & 9 & 6\\
\end{bmatrix}
+
\begin{bmatrix}
8 & 7 & 1\\
10 & 19 & 3\\
7 & 5 & 2\\
\end{bmatrix}
=
\begin{bmatrix}
10 & 10 & 9\\
22 & 27 & 8\\
9 & 14 & 8\\
\end{bmatrix}
$$

$$
\begin{bmatrix}
2 & 3 & 8\\
12 & 8 & 5\\
2 & 9 & 6\\
\end{bmatrix}
-
\begin{bmatrix}
8 & 7 & 1\\
10 & 19 & 3\\
7 & 5 & 2\\
\end{bmatrix}
=
\begin{bmatrix}
-6 & -4 & 7\\
2 & -11 & 2\\
-5 & 4 & 4\\
\end{bmatrix}
$$

## Scalar Multiplication
A matrix can be scaled up or down, by multiplying every element of the matrix by a scalar.

$$
5
\begin{bmatrix}
3 & 6\\
7 & 9\\
12 & 3\\
\end{bmatrix}
=
\begin{bmatrix}
15 & 30\\
35 & 45\\
60 & 15\\
\end{bmatrix}
$$

## Matrix Multiplication
Two matrices, of varying size can be multiplied together, by **taking the dot product** of each row of the first and each column of the second.

These matrices must be "

 - that is, **the width of one must be the height of the other**, and vis versa.

The process for this is to multiply each element in each row of the first matrix by each element in each column of the second, and add the results together.

$$Taking\ the\ Dot\ Product$$

$$
\begin{bmatrix}
\color{red}{1} & \color{red}{2} & \color{red}{3}\\
4 & 5 & 6\\
\end{bmatrix}
\begin{bmatrix}
\color{blue}{7} & 8\\
\color{blue}{9} & 10\\
\color{blue}{11} & 12\\
\end{bmatrix}
=
\begin{bmatrix}
\color{purple}{58} & 64\\
139 & 154\\
\end{bmatrix}
$$

$$(1)(7) + (2)(9) + (3)(11) = 58$$

The resulting matrix will have the **height** of the first matrix, and the **width** of the second.

### Non-commutativity
Matrix multiplication is **not commutative**. $[A][B]$ may $= [C]$, but $[B][A]$ is not obligated to $=[C]$.

### Distributivity
Although matrix multiplication is non-commutative, it _does_ keep the distributative property.

As



What $[A][B]$ represents: do transformation $B$, then transformation $A$.

(AB)X = A(BX)
