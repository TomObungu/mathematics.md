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

So if I'm understanding this right:
We have a curve with the form $5x^{2}-16xy+13y^{2}=25$ which is an ellipse and we have the transformation rule which is $\begin{pmatrix}1 & a \\ -a & 3\end{pmatrix}$ which in this case is $X=2x+ay$ and $Y=-ax+3y$ . We want to transform the ellipse to a circle centred around the origin. This means after the transformation the coordinates of the transformed points will form a circle with equation $X^{2}+Y^{2}=k$ as this the equation for a circle around the origin. What's not to say we could just substitute $2x+ay$ and $-ax+3y$ into $X^{2}+Y^{2}=k$? Please continue.


Let's go through the working step by step, using only **A-Level Maths** and **AS Further Maths (vectors/ matrices)** ideas.

---

## 1. Problem restatement

We have the curve  
$$ 5x^2 - 16xy + 13y^2 = 25 $$
and a transformation represented by the matrix
$$ M = \begin{pmatrix} -1 & a \\ -a & 3 \end{pmatrix}, \quad a \in \mathbb{R}. $$
We want the value of \( a \) so that the **image** of the curve under this transformation is a **circle centred at the origin**.

---

## 2. Understanding the transformation

Let a point \((x, y)\) be transformed to \((X, Y)\) by:
$$ \begin{pmatrix} X \\ Y \end{pmatrix} = M \begin{pmatrix} x \\ y \end{pmatrix}. $$

But the curve equation is in the old coordinates \((x, y)\).  
If we want the equation of the **new curve** in \((X, Y)\), we find \((x, y)\) in terms of \((X, Y)\) using the inverse matrix.

Let \( \beta = \det(M) \).  
For \( M = \begin{pmatrix} -1 & a \\ -a & 3 \end{pmatrix} \),  
$$ \beta = (-1)(3) - (a)(-a) = -3 + a^2. $$

The inverse is:
$$ M^{-1} = \frac{1}{\beta} \begin{pmatrix} 3 & -a \\ a & -1 \end{pmatrix}. $$

So:
$$ x = \frac{1}{\beta}(3X - aY), $$
$$ y = \frac{1}{\beta}(aX - Y). $$

---

## 3. Substitution into original equation

Original: $$ 5x^2 - 16xy + 13y^2 = 25. $$

Substitute \(x\) and \(y\):

First compute \(x^2, y^2, xy\):

$$ x^2 = \frac{1}{\beta^2}(3X - aY)^2 = \frac{1}{\beta^2}(9X^2 - 6aXY + a^2 Y^2), $$

$$ y^2 = \frac{1}{\beta^2}(aX - Y)^2 = \frac{1}{\beta^2}(a^2 X^2 - 2aXY + Y^2), $$

$$ xy = \frac{1}{\beta^2}(3X - aY)(aX - Y) $$
$$ = \frac{1}{\beta^2}[ 3a X^2 - 3XY - a^2 XY + a Y^2 ]. $$

---

## 4. Multiply and collect terms

Multiply original equation terms by \(5, -16, 13\) respectively:

Term from \(5x^2\):  
$$ \frac{5}{\beta^2}(9X^2 - 6aXY + a^2 Y^2) $$

Term from \(-16xy\):  
$$ -\frac{16}{\beta^2}(3a X^2 - 3XY - a^2 XY + a Y^2) $$

Term from \(13y^2\):  
$$ \frac{13}{\beta^2}(a^2 X^2 - 2aXY + Y^2) $$

Add them up (factor \(1/\beta^2\) later).

---

**Coefficient of \(X^2\):**  
From \(5x^2\): \(5 \times 9 = 45\)  
From \(-16xy\): \(-16 \times 3a = -48a\)  
From \(13y^2\): \(13 \times a^2 = 13a^2\)  
Total: \(13a^2 - 48a + 45\).

**Coefficient of \(Y^2\):**  
From \(5x^2\): \(5 \times a^2 = 5a^2\)  
From \(-16xy\): \(-16 \times a = -16a\)  
From \(13y^2\): \(13 \times 1 = 13\)  
Total: \(5a^2 - 16a + 13\).

**Coefficient of \(XY\):**  
From \(5x^2\): \(5 \times (-6a) = -30a\)  
From \(-16xy\): \(-16 \times (-3) = 48\), and \(-16 \times (-a^2) = 16a^2\), so total from \(-16xy\): \(16a^2 + 48 - 16 \times ??? \) Wait, check:  
\(-16xy\) = \(-16 \times [3a X^2 - 3XY - a^2 XY + a Y^2]\)  
So \(XY\) term from \(-16xy\): \(-16 \times (-3) XY = +48 XY\), and \(-16 \times (-a^2) XY = +16a^2 XY\), and \(-16 \times (-2a?)\) no, there's no -2a, careful:  
Actually: \(xy = 3a X^2 - 3XY - a^2 XY + a Y^2\).  
So \(XY\) part = \((-3 - a^2)XY\).  
Multiply by \(-16\): \(48 + 16a^2\) for the \(XY\) term.  
Also from \(13y^2\): \(13 \times (-2a)XY = -26a XY\).  
From \(5x^2\): \(5 \times (-6a)XY = -30a XY\).  

So \(XY\) coefficient: \(16a^2 + 48 - 30a - 26a = 16a^2 - 56a + 48\).

---

Thus transformed equation:
$$ \frac{1}{\beta^2} \left[ (13a^2 - 48a + 45) X^2 + (5a^2 - 16a + 13) Y^2 + (16a^2 - 56a + 48) XY \right] = 25. $$

Multiply through by \(\beta^2\):
$$ (13a^2 - 48a + 45) X^2 + (5a^2 - 16a + 13) Y^2 + (16a^2 - 56a + 48) XY = 25\beta^2. $$

---

## 5. Condition for a circle centred at origin

A circle centred at origin has equation \(X^2 + Y^2 = \text{constant}\), so:

1. Coefficient of \(XY\) must be 0 (no cross term).
2. Coefficients of \(X^2\) and \(Y^2\) must be equal.

From \(XY\) coefficient = 0:
$$ 16a^2 - 56a + 48 = 0 $$
Divide by 8: $$ 2a^2 - 7a + 6 = 0 $$
$$ (2a - 3)(a - 2) = 0 \implies a = \frac{3}{2} \ \text{or} \ a = 2. $$

---

## 6. Check \(X^2\) and \(Y^2\) coefficients equal

For \(a = 2\):  
\(13a^2 - 48a + 45 = 13\times 4 - 96 + 45 = 52 - 96 + 45 = 1\)  
\(5a^2 - 16a + 13 = 5\times 4 - 32 + 13 = 20 - 32 + 13 = 1\)  
Equal.

For \(a = \frac{3}{2}\):  
\(13a^2 - 48a + 45 = 13\times \frac{9}{4} - 48\times \frac{3}{2} + 45 = \frac{117}{4} - 72 + 45\)  
\(= \frac{117}{4} - 27 = \frac{117 - 108}{4} = \frac{9}{4}\)  
\(5a^2 - 16a + 13 = 5\times \frac{9}{4} - 16\times \frac{3}{2} + 13 = \frac{45}{4} - 24 + 13\)  
\(= \frac{45}{4} - 11 = \frac{45 - 44}{4} = \frac14\)  
Not equal.

So only \(a = 2\) works.

---

## 7. Final check

For \(a = 2\), \(\beta = 1\), transformed equation:  
$$ X^2 + Y^2 = 25, $$
a circle centred at origin.

---

$$ \boxed{2} $$