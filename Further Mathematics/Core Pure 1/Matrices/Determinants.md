[[Completing The Square]]
You can calculate the determinant of a square ($n \times n$) matrix. The determinant is the scalar value associated with that matrix.

For a $2 \times 2\text{ matrix } M = \begin{pmatrix}a & d \\ c & d\end{pmatrix}, \text{the determinant is } ab-bc$
If $\det M = 0$ then $M$ is a singular matrix - It does not have an inverse then $\det M \neq 0$ then matrix $M$ is a non-singular matrix.

- For a linear transformation represented by matrix $\mathbf{M}$, det$\mathbf{M}$ represents the scale factor for the change in area. 
- If the determinant of the matrix $\mathbf{M}$ is negative, then the shape has been reflected

---
## Example 1
*Given that $A = \begin{pmatrix}6 & 5 \\ 1 & 2\end{pmatrix}$, find $\det A$.*
$$
\det A = ad-bc - 6 \times 2 - 5 \times 1 = 12 - 5 = 7
$$
---
## Example 2
$$
A = \begin{pmatrix}
4 & p+2 \\
-1 & 3-p
\end{pmatrix}
$$
*Given $A$ is a $2\times 2$ matrix and is singular, find the value of p.*
$$
\begin{gather*}
\det A = 4(3-p) - (p+2)(-1) = 0 \\
14 - 3p = 0 \implies p = \frac{14}{3}
\end{gather*}
$$

---
## Determinant of a 3 $\times$ 3 matrix.
You find the determinant of a $3\times 3$ matrix by reducing the $3\times 3$ determinant to $2 \times 2$ determinants using the formula:
$$
\left| \begin{matrix}
a & b & c \\
d & e & f \\
g  & h & i
\end{matrix}
\right| = a\left|\begin{matrix}
e & f \\
h & i
\end{matrix}\right| - b\left|\begin{matrix}
d & f \\
g & i
\end{matrix}\right| +
b\left|\begin{matrix}
d & e \\
g & h
\end{matrix}\right|
$$


![[Pasted image 20250903003258.png]]

![[Pasted image 20250904110618.png]]

---
### Example 1
Given $P = \begin{pmatrix}k & -2 & 7 \\ -3 & -5 & 2 \\ k & k & 4\end{pmatrix}$ where k is a constant.
*Show that P is non-singular for all real values of k.*

$$
\begin{gather*}
\left| \begin{matrix}
k & -2 & 7 \\
-3 & -5 & 2 \\
k  & k & 4
\end{matrix}
\right| = k(-20-2k)-(-2)(-12-2k)+7(-3k+5k) \\
= -7(-5)(k)-k(2)(k)-(-2)(-3)(4) \\ \\
= -2k^{2}-10k-24 \\ \\ \\
b^{2}-4ac = (-10)^{2}-4(-1)(-12) = -92 < 0 \\ 
\therefore \text{No real roots so matrix is non-singular} \\ \\

Or \\ \\
-2k^{2}-10k-24 = -2\left( k+\frac{5}{2} \right)^{2}-\frac{23}{2}\leq 0
\end{gather*}
$$