Matrices can be multiplied together if the number of **columns in the first matrix is equal to the number of columns in the second matrix**

The product matrix will have the same number of rows as the first matrix and the same number of columns as the second matrix.

If matrix $A$ has size $n \times m$ and matrix $B$ has matrix size $m \times k$ then product matrix $C$ has size $n \times k$

--- 
 In General $AB \ne BA$ 
This means that you must write the notation of the matrix you trying to multiply from left to right

---
The matrix $PQ$ represents the transformation $Q$ followed by $P$

---
### Example 1
Let  $A$ be a matrix and let $B$ a matrix. Let $C$ be a matrix such that $A = BC$.

To multiply by matrix B, multiply on the left hand side as matrix $B$ is on the left hand side of the equation it is on
$$
\begin{gather*}
A = BC \\ 
\begin{aligned}
& & & & & & & & & & & & & & & & & &\underrightarrow{\times B}
\end{aligned} \\
BA = BBC \\
BA = B^{2}C
\end{gather*}
$$
### Example 2
Let  $D$ be a matrix and let $F$ a matrix. Let $F^{-1}$ be the inverse of matrix $F$ such that $DF = F^{-1}$.

It possible to multiply the matrix on the right hand side of both equations
$$
\begin{gather*}
DE = F^{-1}\\ 
\begin{aligned}
& & & & & & & & & & & & & & & & & &\underrightarrow{\times F^{-1}}
\end{aligned} \\
DFF^{-1} = F^{-1}F^{-1} \\
DI = F^{-1}F^{-1} \\
D = F^{-1}F^{-1}
\end{gather*}
$$

#### If $AB$ exists then $BA$ does not necessarily exist 


---
### Matrix Multiplication is associative
Let $A, B, C$ be matrices
In general:
$$
AB(C) = (AB)C = A(BC)
$$
---

To find the product of two multiplicatively conformable matrices, multiply each **row** in the left-hand matrix by corresponding **column** in the right hand matrix then add the results together

To find the element in the first column of the second row, multiply each element in the first row of the left matrix with the corresponding element in the column of the right matrix i.e. multiply the first element in the second row with the first element in the first column and then the second and so on.
$$
\begin{gather*}
\begin{pmatrix}
5 & -1 & 2 \\ 
\rowcolor{purple} \colorbox{red}{8} & \colorbox{grey}{3} & \colorbox{green}{-4}
\end{pmatrix} 
\times \begin{pmatrix}
\columncolor{purple} \colorbox{red}{2} & 2  \\
\colorbox{grey}{9} & -3  \\
\colorbox{green}{7} & 4 \\
\end{pmatrix} 
= 
\begin{pmatrix}
15 & 21  \\
\colorbox{purple}{15} & -9
\end{pmatrix} \\
\colorbox{red}{$8 \times 2$} + \colorbox{grey}{$3 \times 9$} + \colorbox{green}{$-4 \times 7$}= 16 + 27 - 28 = \colorbox{purple}{$15$}
\end{gather*}
$$

---

##  Example 1

Given that $A = \begin{pmatrix} 1 & -2  \\ 3 & 4\end{pmatrix}$ and $B = \begin{pmatrix}-3 \\ 2\end{pmatrix}$
*a Find AB* 
b explain why it is not possible to find BA

### a.

**A is a $2\times 2$ matrix**
B is a $2 \times 1$ matrix

**Thus AB is going to be a $2 \times 1$ matrix**
 $$AB=\begin{pmatrix}1 & -2  \\ 3 & 4\end{pmatrix}\begin{pmatrix}-3 \\ 2\end{pmatrix} = \begin{pmatrix} p  \\ q\end{pmatrix}$$
$$
\begin{gather*}
p = 1 \times -3 + -2 \times 2 = -7 \\
q = 3 \times -3 + 4 \times 2 = -1 \\
\end{gather*}
$$
$$
\text{So } AB = \begin{pmatrix}
-7 \\
-1
\end{pmatrix}
$$
### b.
BA cannot be found, since the number of columns in B is not the same as the number of rows in A.
$$
\begin{gather*}
BA = (2 \times 1) \times (2 \times 2) \\
\therefore \text{BA does not exist}
\end{gather*}
$$


---
## Example 2
$A$ is a $2\times 2$ matrix and $B$ is a $2\times 2$ matrix.
$$
\begin{gather*}
AB = \begin{pmatrix}
-1 & 0 \\
2 & 3
\end{pmatrix}
\begin{pmatrix}
4 & 1 \\
0 & -2
\end{pmatrix}
= \begin{pmatrix}
a & b \\
c & d 
\end{pmatrix}
\\ \\
a = -1 \times 4 + 0 \times 0 = -4\\
b = -1 \times 1 + 0 \times -2 = -1\\
c = 2 \times 4 + 3 \times 0 = 8 \\
d 2 \times 1 + 3 \times -2 = -4 \\ \\
\text{So AB} =  \begin{pmatrix}
-4 & 1 \\
8 & -4
\end{pmatrix}
\end{gather*}
$$


