[[Determinants]]
## Transpose of a matrix
The transpose of a matrix is found by interchanging the rows and the columns. 
For example, if $A = \begin{pmatrix}1 & 4 \\ 2 & 4\end{pmatrix} A^{T} = \begin{pmatrix}1 & 2 \\ 4 & 3\end{pmatrix}$
The transpose of a 3 x 3 matrix would look like this:
The highlighted numbers have their positions swapped:
$$
\begin{gather*}
\text{Let } C = \begin{pmatrix}
1 & \colorbox{purple}{$1$} & \colorbox{grey}{$-8$} \\
\colorbox{purple}{$-1$} & -2 & \colorbox{red}{$7$} \\
\colorbox{grey}{$-1$} & \colorbox{red}{$1$} & 4
\end{pmatrix} \\ \\
C^{T} = \begin{pmatrix}
1 & -1 & -1 \\
1 & -2 & 1 \\
-8 & 7 & 4
\end{pmatrix}
\end{gather*}
$$

## Find the inverse
 Continue to let $C$ be a $3 \times 3 \begin{matrix}\end{matrix}$ matrix.
1. Find the determinant of $C$
2. Form the matrix of minors i.e
$$
\begin{gather*}
M_{C} = \begin{pmatrix}
\left|\begin{matrix}
4 & 1  \\ -1 & 0 \end{matrix} \right|  & \left|\begin{matrix} 0 & 1  \\ 2 & 0 \end{matrix} \right| & \left|\begin{matrix}0 & 4  \\ 2 & -1 \end{matrix} \right| \\ \left|\begin{matrix}
3 & 1  \\ -1 & 0 \end{matrix} \right|  & \left|\begin{matrix} 1 & 1  \\ 2 & 0 \end{matrix} \right| & \left|\begin{matrix}1 & 3  \\ 2 & -1 \end{matrix} \right| \\ \left|\begin{matrix}
3 & 1  \\ 4 & 1 \end{matrix} \right|  & \left|\begin{matrix} 1 & 1  \\ 0 & 1 \end{matrix} \right| & \left|\begin{matrix}1 & 3  \\ 0 & 4 \end{matrix} \right|
\end{pmatrix} \\ \\
= \begin{pmatrix}
1 & -2 & -8 \\
1 & -2 & -7 \\
-1 & 1 & 4
\end{pmatrix}
\end{gather*}
$$
3. Form the matrix of cofactors by changing the signs of elements according to the rule of alternating sings. Take the result of the matrix of minors then alternate the signs of the values at the positions accordingly to the illustrated matrix below.
$$
\begin{pmatrix}
+ & - & + \\
- & + & - \\
+ & - & +
\end{pmatrix}
$$
4. . Write the transpose, $C^{T}$ of the matrix of cofactors
5. The inverse of the matrix is given by this formula
$$
C^{-1} = \frac{1}{\det A}C^{T}
$$
# Example 1
*The matrix A = $\begin{pmatrix}-2 & 3 & -3 \\ 0 & 1 & 0 \\ 1 & -1 & 2\end{pmatrix}$*
*a show that $A^{-1} = A$

a 
$$
\begin{gather*}
A^{2}=\begin{pmatrix}-2 & 3 & -3 \\ 0 & 1 & 0 \\ 1 & -1 & 2\end{pmatrix}\begin{pmatrix}-2 & 3 & -3 \\ 0 & 1 & 0 \\ 1 & -1 & 2\end{pmatrix}
\end{gather*} = \begin{pmatrix}1 & 0 & 0 \\ 0 & 1 & 0 \\ 1 & 0 & 1\end{pmatrix}
$$
	In general: Proving $A=A^{-1}$ (self inverse) $\equiv$ $A^{2}=I$