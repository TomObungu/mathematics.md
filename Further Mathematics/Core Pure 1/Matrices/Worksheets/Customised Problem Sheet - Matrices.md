1. A transformation of the $xy$-plane is represented by the matrix $\mathbf{M}$, where
$\mathbf{M} = \begin{pmatrix} 3 & 2 \\ 4 & 1 \end{pmatrix}$.
A line has equation $y = mx$. Given that this line is invariant under the transformation represented by $\mathbf{M}$, find the two possible values of the gradient $m$.

---

2. A 2D linear transformation $T$ is defined by the matrix $\mathbf{A}$, where
$\mathbf{A} = \begin{pmatrix} 2 & -1 \\ k & 4 \end{pmatrix}$.
It is given that the only invariant point of $T$ is the origin. Determine the value of the constant $k$.

---

3. A transformation in three-dimensional space is represented by the matrix $\mathbf{R}$, where
$\mathbf{R} = \begin{pmatrix} 0 & 0 & 1 \\ 1 & 0 & 0 \\ 0 & 1 & 0 \end{pmatrix}$.
Describe geometrically the effect of the transformation represented by $\mathbf{R}$.

---

4. The matrix $\mathbf{B}$ is given by
$\mathbf{B} = \begin{pmatrix} \cos\theta & -\sin\theta \\ \sin\theta & \cos\theta \end{pmatrix}$.
Show that $\mathbf{B}^n = \begin{pmatrix} \cos n\theta & -\sin n\theta \\ \sin n\theta & \cos n\theta \end{pmatrix}$ for all positive integers $n$.

---

5. Consider the following system of equations, where $p$ is a real constant:
$x + 2y + z = 4$
$3x - y + 2z = 1$
$4x + y + (p+2)z = p + 5$.
Find the value of $p$ for which the system is consistent and does not have a unique solution. For this value of $p$, interpret the geometric configuration of the three planes represented by the equations.

---

6. A matrix $\mathbf{C}$ is defined as $\mathbf{C} = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$, where $a, b, c, d \in \mathbb{R}$. The transformation represented by $\mathbf{C}$ maps all points on the line $y = 2x$ to the origin. Show that $2a + b = 0$ and $2c + d = 0$.

---

7. A system of equations is given by:
$2x - y + 3z = 1$
$x + 2y - z = -3$
$4x + 3y + z = k$.
Determine the value of the constant $k$ for which the system is consistent. For this value of $k$, solve the system and state the geometric interpretation of the solution.

---

8. A transformation is represented by the matrix $\mathbf{T} = \begin{pmatrix} 2 & 1 \\ 1 & 2 \end{pmatrix}$. Find the equations of all the lines of fixed points for this transformation.

---

9. A matrix $\mathbf{M}$ is given by $\mathbf{M} = \begin{pmatrix} k & 1 & 2 \\ 1 & k & 1 \\ 2 & 1 & k \end{pmatrix}$, where $k$ is a constant. The determinant of $\mathbf{M}$ is found to be 0.
   a) Show that $(k+2)$ is a factor of the determinant.
   b) Hence, find the possible values of $k$.
   c) For the case where $k=1$, and considering $\mathbf{M}$ as the matrix of coefficients for a system of homogeneous equations ($\mathbf{M}\mathbf{x} = \mathbf{0}$), explain the significance of the zero determinant on the nature of the solutions.

---

10. A matrix $\mathbf{D}$ is defined as $\mathbf{D} = \begin{pmatrix} 4 & -7 \\ 1 & -2 \end{pmatrix}$. Find the equation of the invariant lines of the transformation represented by $\mathbf{D}$ which are not passing through the origin.

***

### Mark Scheme

**1.**
- **Answer:** $m = 1$ or $m = -\frac{2}{3}$
- **Explanation:** For an invariant line $y = mx$, the image point $(x', y')$ must satisfy $y' = mx'$. Substituting the transformation leads to the condition $4 + m = m(3 + 2m)$. Solving this quadratic gives $2m^2 + 2m - 4 = 0$, so $m^2 + m - 2 = 0$, yielding $m = 1$ or $m = -2$.

**2.**
- **Answer:** $k \ne -2$
- **Explanation:** Invariant points satisfy $\mathbf{A}\mathbf{x} = \mathbf{x}$. This gives $(\mathbf{A} - \mathbf{I})\mathbf{x} = \mathbf{0}$. For the only solution to be the origin, $\det(\mathbf{A} - \mathbf{I}) \ne 0$. $\mathbf{A} - \mathbf{I} = \begin{pmatrix} 1 & -1 \\ k & 3 \end{pmatrix}$. Its determinant is $3 - (-k) = 3 + k$. So $3 + k \ne 0$, i.e., $k \ne -3$.

**3.**
- **Answer:** A rotation of $120^\circ$ about the line $x = y = z$ in a clockwise direction (when viewed from the positive axis towards the origin).
- **Explanation:** The matrix is a permutation matrix. Applying it to $(x, y, z)^T$ gives $(z, x, y)^T$. This is a cyclic permutation, which corresponds to a rotation about the line where all coordinates are equal.

**4.**
- **Answer:** Proof.
- **Explanation:** Use proof by induction. The base case $n=1$ is true by definition. Assume true for $n=k$. For $n=k+1$, $\mathbf{B}^{k+1} = \mathbf{B}^k \mathbf{B}$. Multiply the matrices using standard trigonometric identities for $\cos(A+B)$ and $\sin(A+B)$ to show it equals the required form for $n=k+1$.

**5.**
- **Answer:** $p = 3$. The planes intersect in a line.
- **Explanation:** Form the augmented matrix and row reduce. The system is inconsistent unless $p = 3$. When $p=3$, the third row becomes all zeros, indicating a line of solutions (the planes intersect in a line).

**6.**
- **Answer:** Proof.
- **Explanation:** A point on the line is $(t, 2t)$. Its image under $\mathbf{C}$ is $(at + 2bt, ct + 2dt)$. For this to be the origin for all $t$, the coefficients of $t$ must be zero: $a + 2b = 0$ and $c + 2d = 0$.

**7.**
- **Answer:** $k = -5$. Solution: $x = -1 + t, y = 1 - t, z = t$ (or equivalent). The three planes intersect in a line.
- **Explanation:** Row reduction shows the system is consistent only if $k = -5$. With $k=-5$, one equation becomes redundant, leaving two independent equations, which define a line.

**8.**
- **Answer:** $y = x$
- **Explanation:** Lines of fixed points satisfy $\mathbf{T}\mathbf{x} = \mathbf{x}$. Solving $\begin{pmatrix} 2 & 1 \\ 1 & 2 \end{pmatrix} \begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} x \\ y \end{pmatrix}$ gives $2x + y = x$ and $x + 2y = y$, both of which simplify to $x + y = 0$.

**9.**
    - **a) Answer:** Proof.
        - **Explanation:** Subtract column 1 from column 3, then add row 3 to row 1. The determinant will have a factor of $(k+2)$ visible.
    - **b) Answer:** $k = -2, 1, 2$
        - **Explanation:** The full determinant simplifies to $(k+2)(k-1)(k-2) = 0$.
    - **c) Answer:** There are non-trivial solutions (infinitely many).
        - **Explanation:** A zero determinant for the coefficient matrix of a homogeneous system means the system has non-trivial solutions, i.e., not all points are mapped to the origin.

**10.**
- **Answer:** $y = x - 1$
- **Explanation:** For invariant lines not through the origin, assume a line of the form $y = mx + c$ with $c \ne 0$. Apply the transformation and require the image point lies on the same line. This leads to two equations. Solving gives $m=1$ and $c=-1$.