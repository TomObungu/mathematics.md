$$
\begin{align*}
&\text{The curve C has equation} \\ 
&5x^2-16xy+13y^2=25,\\ \\
&\text{The transformation U is represented by matrix } \mathbf{M} \text{, where } \\ \\
&\mathbf{M}=\begin{pmatrix}-1 & a\\[4pt] -a & 3\end{pmatrix},\qquad a\in\mathbb{R}. \\ \\
&\text{Determine the value of A for which the image of C under transformation U is a circle centetered on the origin.} \\
&\text{You may denote det(M) as } \beta, \text{ to simplify you workings }
\end{align*}
$$
![[Pasted image 20250909134724.png]]]
![[Pasted image 20250928092908.png]]
Let's go through the working step by step, using **A-Level Further Maths** terminology (specifically from the **linear transformations** and **conics** topic).

---

## **1. Problem restatement**

We have the curve  
\[
5x^2 - 16xy + 13y^2 = 25
\]
and a transformation \( U \) represented by the matrix
\[
M = \begin{pmatrix} -1 & a \\ -a & 3 \end{pmatrix}, \quad a \in \mathbb{R}.
\]
We want \( a \) such that the **image of \( C \) under \( U \)** is a **circle centred at the origin**.

---

## **2. Understanding the transformation**

Let \( \mathbf{x} = \begin{pmatrix} x \\ y \end{pmatrix} \).

The transformation \( U \) is represented by \( M \), so  
\[
\mathbf{x}' = M \mathbf{x}.
\]
That is, if \( (x, y) \) is the original point, then the transformed point \( (X, Y) \) is given by
\[
\begin{pmatrix} X \\ Y \end{pmatrix} = M \begin{pmatrix} x \\ y \end{pmatrix}.
\]

But careful: In the working, they seem to use \( M \left( \frac{x}{y} \right) \) to mean \( M \) acting on coordinates, but the **curve equation** is in the **original coordinates** \((x, y)\), and the **image** is in \((X, Y)\).

Actually, more standard:  
If \( \mathbf{x}' = M \mathbf{x} \), then \( \mathbf{x} = M^{-1} \mathbf{x}' \).

So if the original curve satisfies \( Q(\mathbf{x}) = 25 \), then after transformation, the new curve satisfies \( Q(M^{-1} \mathbf{x}') = 25 \).

---

## **3. Inverse transformation**

Let \( \beta = \det(M) = (-1)(3) - (a)(-a) = -3 + a^2 \).

Then
\[
M^{-1} = \frac{1}{\beta} \begin{pmatrix} 3 & -a \\ a & -1 \end{pmatrix}.
\]
So
\[
x = \frac{1}{\beta}(3X - a Y), \quad y = \frac{1}{\beta}(a X - Y).
\]

---

## **4. Substitution into original equation**

Original: \( 5x^2 - 16xy + 13y^2 = 25 \).

Substitute \( x, y \) from above:

\[
x = \frac{1}{\beta}(3X - a Y), \quad y = \frac{1}{\beta}(a X - Y).
\]

Then
\[
x^2 = \frac{1}{\beta^2}(9X^2 - 6a XY + a^2 Y^2),
\]
\[
y^2 = \frac{1}{\beta^2}(a^2 X^2 - 2a XY + Y^2),
\]
\[
xy = \frac{1}{\beta^2}\big( 3a X^2 - 3XY - a^2 XY + a Y^2 \big).
\]

---

## **5. Multiply out**

The working does:

\[
5x^2 - 16xy + 13y^2
\]
\[
= \frac{1}{\beta^2} \big[ 5(9X^2 - 6a XY + a^2 Y^2) - 16(3a X^2 - 3XY - a^2 XY + a Y^2) + 13(a^2 X^2 - 2a XY + Y^2) \big].
\]

They then collect terms for \( X^2, Y^2, XY \):

- \(X^2\) term:  
\(5 \cdot 9 = 45\)  
\(-16 \cdot 3a = -48a\)  
\(13 \cdot a^2 = 13a^2\)  
So \(X^2\) coefficient: \(13a^2 - 48a + 45\).

- \(Y^2\) term:  
\(5 \cdot a^2 = 5a^2\)  
\(-16 \cdot a = -16a\)  
\(13 \cdot 1 = 13\)  
So \(Y^2\) coefficient: \(5a^2 - 16a + 13\).

- \(XY\) term:  
\(5 \cdot (-6a) = -30a\)  
\(-16 \cdot (-3) = 48\)  
\(-16 \cdot (-a^2) = 16a^2\)  
\(13 \cdot (-2a) = -26a\)  
Sum: \(16a^2 + (-30a - 26a) + 48 = 16a^2 - 56a + 48\).

So transformed equation:
\[
\frac{1}{\beta^2} \left[ (13a^2 - 48a + 45) X^2 + (5a^2 - 16a + 13) Y^2 + (16a^2 - 56a + 48) XY \right] = 25.
\]
Multiply by \( \beta^2 \):
\[
(13a^2 - 48a + 45) X^2 + (5a^2 - 16a + 13) Y^2 + (16a^2 - 56a + 48) XY = 25\beta^2.
\]

---

## **6. Condition for a circle centred at origin**

A circle centred at origin has equation \( X^2 + Y^2 = R^2 \), so:

1. Coefficient of \( X^2 \) = coefficient of \( Y^2 \)  
2. Coefficient of \( XY \) = 0.

From \( XY \) term zero:
\[
16a^2 - 56a + 48 = 0.
\]
Divide 8: \( 2a^2 - 7a + 6 = 0 \).  
\[
(2a - 3)(a - 2) = 0 \implies a = 2 \ \text{or} \ a = \frac{3}{2}.
\]

---

## **7. Check \(X^2\) and \(Y^2\) coefficients equal**

For \( a = 2 \):  
\(13a^2 - 48a + 45 = 13\cdot 4 - 96 + 45 = 52 - 96 + 45 = 1\)  
\(5a^2 - 16a + 13 = 5\cdot 4 - 32 + 13 = 20 - 32 + 13 = 1\)  
Yes, equal.

For \( a = \frac{3}{2} \):  
\(13a^2 - 48a + 45 = 13\cdot \frac{9}{4} - 48\cdot \frac{3}{2} + 45 = \frac{117}{4} - 72 + 45\)  
\(= \frac{117}{4} - 27 = \frac{117 - 108}{4} = \frac{9}{4}\)  

\(5a^2 - 16a + 13 = 5\cdot \frac{9}{4} - 16\cdot \frac{3}{2} + 13 = \frac{45}{4} - 24 + 13\)  
\(= \frac{45}{4} - 11 = \frac{45 - 44}{4} = \frac14\)  

Not equal. So \( a = \frac{3}{2} \) gives an ellipse (different coefficients for \(X^2\) and \(Y^2\)), not a circle.

Thus only \( a = 2 \) works.

---

## **8. Final check**

For \( a = 2 \), \( \beta = a^2 - 3 = 1 \).  
Transformed equation: \( X^2 + Y^2 = 25 \), a circle centred at origin.

---

\[
\boxed{2}
\]