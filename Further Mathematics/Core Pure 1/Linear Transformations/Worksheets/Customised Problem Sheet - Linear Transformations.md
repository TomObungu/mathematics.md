
1. a) Let $M = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$ be a matrix such that $M^2 = I$. Show that if $a+d \neq 2$, then $(M-I)$ is non-singular.

b) For the specific case $M = \begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}$, write down $M^2$, $M^3$, and $M^4$, and state the general form of $M^n$.

The transformation $T$ is defined by the matrix $(M-I)^{-1}(M^n - I)$.

c) Prove that $T$ has a line of invariant points if and only if $n$ is even.

d) Hence, demonstrate that the line $y = -x$ is invariant under $T$ for all even $n$.

***

2.  A conic section $S$ is defined by the equation
$$
3x^2 + 10xy + 8y^2 = 12
$$

A linear transformation $T$ is represented by the matrix $A$, where
$$
A = \begin{pmatrix} 2 & b \\ -b & 1 \end{pmatrix}, \quad b \in \mathbb{R}
$$

Determine the value of the real constant $b$ for which the image of the conic $S$ under transformation $T$ is a circle centered at the origin.

**Hint:** You may find it useful to denote $\det(A)$ as $\delta$ to simplify your algebraic working.

(7 marks)

---

### Mark Scheme

**1.**
- **a) Answer:** For $M^2=I$, $(M-I)(M+I)=0$. If $a+d\neq2$, then $M\neq I$, ensuring non-singularity.
- **b) Answer:** $M^2=I$, $M^3=M$, $M^4=I$, so $M^n=I$ if $n$ even, $M^n=M$ if $n$ odd.
- **c) Answer:** When $n$ even, $M^n=I$, creating a line of invariant points.
- **d) Answer:** For even $n$, the transformation becomes zero, making all points invariant, including those on $y=-x$.

**2.**
- **Answer:** $b = \pm 2$
- **Explanation:**
    1.  Let a point on the original conic be $\begin{pmatrix} x \\ y \end{pmatrix}$ and its image under $T$ be $\begin{pmatrix} X \\ Y \end{pmatrix} = A \begin{pmatrix} x \\ y \end{pmatrix}$.
    2.  Since $A$ is invertible for the transformation to be valid, we have $\begin{pmatrix} x \\ y \end{pmatrix} = A^{-1} \begin{pmatrix} X \\ Y \end{pmatrix}$.
    3.  The inverse matrix is $A^{-1} = \frac{1}{\delta} \begin{pmatrix} 1 & -b \\ b & 2 \end{pmatrix}$, where $\delta = \det(A) = 2 + b^2$.
    4.  Substituting $x = \frac{1}{\delta}(X - bY)$ and $y = \frac{1}{\delta}(bX + 2Y)$ into the original equation $3x^2 + 10xy + 8y^2 = 12$ yields the equation of the transformed conic in terms of $X$ and $Y$.
    5.  For this transformed conic to be a circle centered at the origin, the coefficients of $X^2$ and $Y^2$ must be equal, and the coefficient of $XY$ must be zero.
    6.  Calculating the coefficient of $XY$ from the substitution and setting it equal to zero gives a condition in terms of $b$. Solving $10(2 - b^2) + 2b(3 - 8) = 0$ simplifies to $20 - 10b^2 - 10b = 0$, or $b^2 + b - 2 = 0$.
    7.  Solving the quadratic yields $b = 1$ or $b = -2$.
    8.  Checking the coefficients of $X^2$ and $Y^2$ for these values confirms they become equal, resulting in a circle. Thus, $b = 1$ or $b = -2$.
