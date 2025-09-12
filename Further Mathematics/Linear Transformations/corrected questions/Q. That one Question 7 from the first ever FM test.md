[[Determinants]][[Matrix Multiplication]][[Inverting a 2 x 2 matrix]][[Invariant points and lines]]
$$
\begin{align*}
&\text{Let } M \text{ denote the matrix } \\ \\
& \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix}. \\ 
\\ &\text{a) Show that } (M - I) \text{ is non-singular.} \\
\\ &\text{b) Write down the matrices } M^2, M^3, M^4 \text{ and } M^n \text{ and hence determine the general form of the matrix } M^n, n \in \mathbb{N}. 
\\ \\ &\text{The linear transformation } T \text{ is represented by} \\ \\
&(M - I)^n (M^T - I), \quad n \in \mathbb{N}. \\
\\ &\text{c) Prove that } T \text{ has a line of invariant points if and only if } n \text{ is odd.} \\
\\ &\text{d) Hence, show that } y = -x \text{ is a line of invariant points for all odd values of } n.
\end{align*}
$$
![[Pasted image 20250908170926.png]]
a)
$$
M - I = \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix} - \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix} = \begin{pmatrix} 1 & 3 \\ 0 & -2 \end{pmatrix}
$$
$$
\begin{gather*}
\det(M - I) = (1)(-2) - (3)(0) = -2 \neq 0 \\ \\
\therefore ()M - I) \ \ \ \text{is non-singular}
\end{gather*}
$$
b) 
$$
\begin{gather*}
\text{Compute powers of M : } \\ \\
M^{2} = \begin{pmatrix}
4 & 3 \\
0 & -1
\end{pmatrix} \\ \\
M^{3} = \begin{pmatrix}
8 & 9 \\
0 & -1
\end{pmatrix} \\ \\
M^{4} = \begin{pmatrix}
16 & 15 \\
0 & -1
\end{pmatrix} \\ \\
\text{Top left entry : } 2,4,8,16\dots\text{which is }2^{n} \\ \\
\text{Top right entry : } 3,3,9,15\dots\text{Notice that for n=1: 3, n=2: 3, n=3: 9, n=4:4} \\
\text{This sequences satisfies } 2^{n}-(-1)^{n} \\ \\
\text{Top bottom left entry is always } 0 \\ \\
\text{Top bottom right entry -1,1,-1,1... which is } (-1)^{n} \\ \\ \text{Thus the general form is : } \\ \\
\begin{pmatrix}
2^{n}  & 2^{n}-(-1)^{n} \\
0 & (-1)^{n}
\end{pmatrix}
\end{gather*}
$$
c)
$$
\begin{gather*}
\text{The transformation is presented by: } \\ \\
T = (M-I)^{-1}(M^{n}-I) \\ \\
\text{At point } \mathbf{x} \text{ is invariant under } T\mathbf{x}=\mathbf{x}. So: \\ \\
(M-I)^{-1}(M^{n}-I)\mathbf{x}= \mathbf{x} \\ \\ 
\text{Multiply both sides by } (M - I): \\ \\
(M^{n}-I)\mathbf{x}= (M-I)\mathbf{x} \\
M^{n}\mathbf{x}-\mathbf{x}= M\mathbf{x}-\mathbf{x} \\ 
M^{n}\mathbf{x}=M\mathbf{x} = 0 \\
(M^{n-1} - M)\mathbf{x} = 0 \\ \\
\text{Since M is non-signuar, we can multiply by } M^{-1} \\ \\
(M^{n-1}-I)\mathbf{x}=0 \\
M^{n-1}\mathbf{x}=\mathbf{x} \\ \\
\text{So x is an invariant point of } M^{n-1.} \\ \text{For there to be a line of invariant points, the matrix } \\M^{n-1}-I \text{ must be singular meaning its determinant is zero} \\ \\
 \text{Using the general form of M equation from last question: } \\ \\
 M^{n-1} = \begin{pmatrix}
2^{n-1} & 2n^{n-1}-(-1)^{n-1} \\
0 & (-1)^{n-1}
\end{pmatrix} \\ \\
 \text{Then : } \\
 M^{n-1} - I = \begin{pmatrix}
2^{n-1} - 1 & 2n^{n-1}-(-1)^{n-1} \\
0 & (-1)^{n-1} - 1
\end{pmatrix} \\ \\
\text{The determinant is: } \\ \\
\det(M^{n-1} - I) \\ = (2^{n-1} - 1) [(-1)^{n-1} - 1] - [2^{n-1} - (-1)^{n-1}](0) \\ = (2^{n-1} - 1)[(-1)^{n-1} - 1] \\ \\
\text{For a line of invariant points, we need infintley many solutions, so the determinant must be zero.} \\ \\
2^{n-1} - 1)[(-1)^{n-1} - 1] = 0 \\ \\ 
2^{n-1} - 1) = 0 \text{ Only when n=1, but we consider } n \in \mathbb{N}. \\ 
(-1)^{n-1}-1 = 0 \text{ when } (-1)^{n-1} = 1, \text{ i.e when n-1 is even so, n is odd.} \\ \\
\\det(m^{n - 1} - I)=0  \ if \text{ and only if n is odd. Thus for odd n, there is a line of invariant points.} \\ \\
\therefore \ \text{T has a line of invariant points if and only if n is odd.}
\end{gather*}
$$

d) 
$$
\begin{gather*}

\end{gather*}
$$

Let's solve the problem step by step using concepts from Edexcel Further Mathematics Core Pure (Matrices and Linear Transformations).

---

### Given:
\[
M = \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix}
\]

---

### a) Show that \( (M - I) \) is non-singular.

Compute \( M - I \):
\[
M - I = \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix} - \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix} = \begin{pmatrix} 1 & 3 \\ 0 & -2 \end{pmatrix}
\]

Now, find its determinant:
\[
\det(M - I) = (1)(-2) - (3)(0) = -2 \neq 0
\]

Since the determinant is non-zero, \( M - I \) is non-singular (invertible).

---

### b) Write down \( M^2, M^3, M^4 \) and hence determine \( M^n \).

Compute powers of \( M \):

- \( M^1 = \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix} \)

- \( M^2 = M \cdot M = \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix} \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix} = \begin{pmatrix} 4 & 3 \\ 0 & 1 \end{pmatrix} \)
  - Explanation: \( (2)(2) + (3)(0) = 4 \), \( (2)(3) + (3)(-1) = 6 - 3 = 3 \), \( (0)(2) + (-1)(0) = 0 \), \( (0)(3) + (-1)(-1) = 1 \).

- \( M^3 = M^2 \cdot M = \begin{pmatrix} 4 & 3 \\ 0 & 1 \end{pmatrix} \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix} = \begin{pmatrix} 8 & 9 \\ 0 & -1 \end{pmatrix} \)
  - Explanation: \( (4)(2) + (3)(0) = 8 \), \( (4)(3) + (3)(-1) = 12 - 3 = 9 \), \( (0)(2) + (1)(0) = 0 \), \( (0)(3) + (1)(-1) = -1 \).

- \( M^4 = M^3 \cdot M = \begin{pmatrix} 8 & 9 \\ 0 & -1 \end{pmatrix} \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix} = \begin{pmatrix} 16 & 15 \\ 0 & 1 \end{pmatrix} \)
  - Explanation: \( (8)(2) + (9)(0) = 16 \), \( (8)(3) + (9)(-1) = 24 - 9 = 15 \), \( (0)(2) + (-1)(0) = 0 \), \( (0)(3) + (-1)(-1) = 1 \).

Observing the pattern:
- The top-left entry: \( 2, 4, 8, 16, \dots \) which is \( 2^n \).
- The top-right entry: \( 3, 3, 9, 15, \dots \). Notice that for \( n=1 \): 3, \( n=2 \): 3, \( n=3 \): 9, \( n=4 \): 15. This sequence satisfies \( 2^n - (-1)^n \). Check: \( n=1: 2^1 - (-1)^1 = 2 + 1 = 3 \), \( n=2: 4 - 1 = 3 \), \( n=3: 8 - (-1) = 9 \), \( n=4: 16 - 1 = 15 \).
- The bottom-left entry is always 0.
- The bottom-right entry: \( -1, 1, -1, 1, \dots \) which is \( (-1)^n \).

Thus, the general form is:
\[
M^n = \begin{pmatrix} 2^n & 2^n - (-1)^n \\ 0 & (-1)^n \end{pmatrix}
\]

---

### c) Prove that \( T \) has a line of invariant points if and only if \( n \) is odd.

The transformation \( T \) is represented by:
\[
T = (M - I)^{-1} (M^n - I)
\]

A point \( \mathbf{x} \) is invariant under \( T \) if \( T\mathbf{x} = \mathbf{x} \). So:
\[
(M - I)^{-1} (M^n - I) \mathbf{x} = \mathbf{x}
\]
Multiply both sides by \( (M - I) \):
\[
(M^n - I) \mathbf{x} = (M - I) \mathbf{x}
\]
\[
M^n \mathbf{x} - \mathbf{x} = M \mathbf{x} - \mathbf{x}
\]
\[
M^n \mathbf{x} = M \mathbf{x}
\]
\[
(M^n - M) \mathbf{x} = 0
\]
\[
M (M^{n-1} - I) \mathbf{x} = 0
\]

Since \( M \) is non-singular (its determinant is \( (2)(-1) - (3)(0) = -2 \neq 0 \)), we can multiply by \( M^{-1} \):
\[
(M^{n-1} - I) \mathbf{x} = 0
\]
\[
M^{n-1} \mathbf{x} = \mathbf{x}
\]

So, \( \mathbf{x} \) is an invariant point of \( M^{n-1} \). For there to be a line of invariant points (infinitely many), the matrix \( M^{n-1} - I \) must be singular (non-invertible), meaning its determinant is zero.

From part (b):
\[
M^{n-1} = \begin{pmatrix} 2^{n-1} & 2^{n-1} - (-1)^{n-1} \\ 0 & (-1)^{n-1} \end{pmatrix}
\]
Then:
\[
M^{n-1} - I = \begin{pmatrix} 2^{n-1} - 1 & 2^{n-1} - (-1)^{n-1} \\ 0 & (-1)^{n-1} - 1 \end{pmatrix}
\]

The determinant is:
\[
\det(M^{n-1} - I) = (2^{n-1} - 1)[(-1)^{n-1} - 1] - [2^{n-1} - (-1)^{n-1}](0) = (2^{n-1} - 1)[(-1)^{n-1} - 1]
\]

For a line of invariant points, we need infinitely many solutions, so the determinant must be zero:
\[
(2^{n-1} - 1)[(-1)^{n-1} - 1] = 0
\]

- \( 2^{n-1} - 1 = 0 \) only when \( n=1 \), but we consider all \( n \in \mathbb{N} \).
- \( (-1)^{n-1} - 1 = 0 \) when \( (-1)^{n-1} = 1 \), i.e., when \( n-1 \) is even, so \( n \) is odd.

Thus, \( \det(M^{n-1} - I) = 0 \) if and only if \( n \) is odd (and \( n \neq 1 \), but for \( n=1 \), \( M^0 = I \), which also has infinitely many invariants). So for odd \( n \), there is a line of invariant points.

For even \( n \), \( (-1)^{n-1} = -1 \), so \( (-1)^{n-1} - 1 = -2 \neq 0 \), and \( 2^{n-1} - 1 \neq 0 \) for \( n \geq 2 \), so determinant is non-zero, and only the trivial solution \( \mathbf{x} = 0 \) exists.

Therefore, \( T \) has a line of invariant points if and only if \( n \) is odd.

---

### d) Hence, show that \( y = -x \) is a line of invariant points for all odd \( n \).

For odd \( n \), we have a line of invariant points. We need to show that this line is \( y = -x \).

From above, the invariant points satisfy:
\[
M^{n-1} \mathbf{x} = \mathbf{x}
\]
For odd \( n \), \( n-1 \) is even. Let \( n-1 = 2k \). Then:
\[
M^{2k} \mathbf{x} = \mathbf{x}
\]

From the general form:
\[
M^{2k} = \begin{pmatrix} 2^{2k} & 2^{2k} - 1 \\ 0 & 1 \end{pmatrix}
\]
So the equation is:
\[
\begin{pmatrix} 2^{2k} & 2^{2k} - 1 \\ 0 & 1 \end{pmatrix} \begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} x \\ y \end{pmatrix}
\]

This gives:
1. \( 2^{2k} x + (2^{2k} - 1)y = x \)
2. \( y = y \) (always true)

From (1):
\[
2^{2k} x + (2^{2k} - 1)y - x = 0
\]
\[
(2^{2k} - 1)x + (2^{2k} - 1)y = 0
\]
\[
(2^{2k} - 1)(x + y) = 0
\]

Since \( 2^{2k} - 1 \neq 0 \) for \( k \geq 1 \), we have:
\[
x + y = 0 \quad \Rightarrow \quad y = -x
\]

Thus, the line of invariant points is \( y = -x \).

For \( n=1 \) (odd), \( T = (M-I)^{-1}(M-I) = I \), so every point is invariant, including those on \( y = -x \).

Therefore, for all odd \( n \), \( y = -x \) is a line of invariant points.

---

### Final Answers:

**a)** \( M - I = \begin{pmatrix} 1 & 3 \\ 0 & -2 \end{pmatrix} \), det = \(-2 \neq 0\), so non-singular.

**b)** 
- \( M^2 = \begin{pmatrix} 4 & 3 \\ 0 & 1 \end{pmatrix} \)
- \( M^3 = \begin{pmatrix} 8 & 9 \\ 0 & -1 \end{pmatrix} \)
- \( M^4 = \begin{pmatrix} 16 & 15 \\ 0 & 1 \end{pmatrix} \)
- General form: \( M^n = \begin{pmatrix} 2^n & 2^n - (-1)^n \\ 0 & (-1)^n \end{pmatrix} \)

**c)** \( T \) has a line of invariant points iff \( n \) is odd, as shown by the determinant condition.

**d)** For odd \( n \), the invariant points satisfy \( x + y = 0 \), i.e., \( y = -x \).

---

This solution uses concepts of matrix algebra, determinants, and invariant lines from Edexcel Further Mathematics Core Pure.