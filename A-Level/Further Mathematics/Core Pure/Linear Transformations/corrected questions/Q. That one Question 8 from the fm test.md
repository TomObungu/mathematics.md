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

# Explanation of Method
We have a curve $C$ with the form $5x^{2}-16xy+13y^{2}=25$ which is an ellipse and we have the transformation $U$ which is matrix denoted by matrix $M=$ $\begin{pmatrix}1 & a \\ -a & 3\end{pmatrix}$ .

We want to transform the ellipse to a circle centred around the origin. This means after the transformation the coordinates of the transformed points will form a circle with equation $X^{2}+Y^{2}=k$ as this the equation for a circle around the origin. 

We can denote the coordinates of $x$ and $y$ that have the transformation applied to them as $X$ and $Y$. After applying the transformation $U$ through the matrix $M$, the transformed coordinates $X$ and $Y$, in terms of the coordinates in the $xy$ plane, will be $X=2x+ay$ and $Y=-ax+3y$ . 

So we first want the equation for circle in terms of $X$ and $Y$ and the equation for a circle is $X^{2}+Y^{2}=k$

What's not to say we could just substitute $2x+ay$ and $-ax+3y$ into $X^{2}+Y^{2}=k$? 

Will this approach is incorrect as this will give me some separate equation in terms of  $xy$ in the $xy$ plane that is not the original ellipse equation, $C$, but some separate curve in the un-transformed  plane that will map to the transformed circle.  This is not what the question asked.

Remember that the original equation will be in terms of $x$ and $y$ but after applying the transformation $U$ the transformed equation will be in a separate plane with coordinate system of the transformed coordinates, $X$ and $Y$ - or in other words the $XY$ plane.

So we to ensure that points in the original $xy$ plane are strictly the points on the curve $C$ and not some arbitrary points in the $xy$ plane that do not match the curve $C$

In order to do this we need to use the inverse matrix to find equivalent $x$ and $y$ coordinates in the $xy$ plane that corresponding to the coordinates in the $XY$ plane.  This is algebraically identical to  writing $x$ and $y$ in terms of $X$ and $Y$ respectively. 

Once we have the equivalent $x$ and $y$  in terms of $X$ and $Y$ we must substitute them back into the original curve $C$, **In order to ensure that coordinates are strictly coordinates that satisfy the curve equation C**. If the question was asking to find **any** curve within the $xy$ plane that will satisfy a circle around the origin in the $XY$ plane then, we would not need to do this step. However since the question asks us to do so for the curve $C$ we must take this step. 
# Computation
$$
\begin{align*}
\begin{pmatrix}x\\[4pt]y\end{pmatrix}&=M^{-1}\begin{pmatrix}X\\[4pt]Y\end{pmatrix}
=\frac{1}{\beta}\begin{pmatrix}3 & -a\\[4pt]a & -1\end{pmatrix}\begin{pmatrix}X\\[4pt]Y\end{pmatrix}\\[6pt] \\ \\
x&=\frac{1}{\beta}\bigl(3X-aY\bigr),\qquad
y=\frac{1}{\beta}\bigl(aX-Y\bigr)\\[6pt]
\end{align*}
$$


Now have the coordinates of $x$ and $y$ in terms of $X$ and $Y$ it is time to substitute them back into curve $C$
$$
\begin{align*}
\Rightarrow\quad&\frac{5}{\beta^{2}}(3X-aY)^{2}-\frac{16}{\beta^{2}}(3X-aY)(aX-Y)
+\frac{13}{\beta^{2}}(aX-Y)^{2}=25\\[6pt] \\
\Longrightarrow\quad&5(3X-aY)^{2}-16(3X-aY)(aX-Y)+13(aX-Y)^{2}=25\beta^{2}\\[6pt] \\
\Longrightarrow\quad&5\bigl(9X^{2}-6aXY+a^{2}Y^{2}\bigr)-16\bigl(3aX^{2}-(3+a^{2})XY+aY^{2}\bigr)\\
&\qquad\qquad\qquad+13\bigl(a^{2}X^{2}-2aXY+Y^{2}\bigr)=25\beta^{2}\\[6pt]
\Longrightarrow\quad&(13a^{2}-48a+45)X^{2}+(5a^{2}-16a+13)Y^{2}+(16a^{2}-56a+48)XY=25\beta^{2} \\
\end{align*}
$$
Now we have the coordinates of $x$ and $y$ in terms of $X$ and $Y$ that are on the curve $C$ that will map to a circle in $XY$ plane. 

The final bit of the question now asks to find the value of the $a$ such that equation the circle in the $XY$ plane is a circle. 

We know that for a circle **centred around the origin** it's equation  is $X^{2}+Y^{2}=k$.  This means the coefficient for $XY$ will be equal to 0. 

Thus we must set $16a^{2}-56a+48=0$. Do so will lead to:
$$
\begin{align*}
16a^{2}-56a+48 = 0 \\ \\
\implies a=-\frac{3}{2} \qquad a=2
\end{align*}
$$
This equation gives us two values of $a$ thus we need to check if the value of $a$ is valid. To do so we can substitute them back into the coefficients $X^{2}$ and $Y^{2}$ and check if they match up.
$$
\begin{align*}
\text{For } a=2:&\\
13a^2-48a+45 &= 13\times 4 -96 +45 = 52 -96 +45 = 1,\\
5a^2-16a+13 &= 5\times 4 -32 +13 = 20 -32 +13 = 1,\\
&\text{Equal.}\\[6pt]
\text{For } a=\tfrac{3}{2}:&\\
13a^2-48a+45 &= 13\times \tfrac{9}{4} -48\times \tfrac{3}{2} +45 = \tfrac{117}{4} -72 +45 = \tfrac{117}{4} -27 = \tfrac{9}{4},\\
5a^2-16a+13 &= 5\times \tfrac{9}{4} -16\times \tfrac{3}{2} +13 = \tfrac{45}{4} -24 +13 = \tfrac{45}{4} -11 = \tfrac{1}{4},\\
&\text{Not equal.}
\end{align*}
$$
Therefore since the value of $a$ when $a=\frac{3}{2}$ is invalid. The correct value of a is $a=2$:
$$
a=\boxed{2}
$$

---
