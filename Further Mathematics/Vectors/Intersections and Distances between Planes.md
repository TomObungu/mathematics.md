# Intersection between a line and a plane. 
When a line and a plane intersect, the position vector of $r$ is the same for the line and the plane. Thus when given a line equation $l_{1}$, substitute the line into the plane. 
![[Pasted image 20250915184412.png]]

## Worked Example 1
$$
\begin{gather*}
l_{1} : r=\begin{pmatrix}
-1 \\
1 \\
5
\end{pmatrix} + \lambda\begin{pmatrix}
1 \\
1 \\
2
\end{pmatrix} \qquad \Pi_{1} : r \cdot \begin{pmatrix}
1 \\
2 \\
3
\end{pmatrix} = 4 \\ \\ 
r = \begin{pmatrix}
-1 + \lambda \\
1 + \lambda \\
-5 + 2\lambda
\end{pmatrix} \qquad \begin{pmatrix}
-1 + \lambda \\
1 + \lambda \\
-5 + 2\lambda
\end{pmatrix} \cdot \begin{pmatrix}
1 \\
2 \\
3
\end{pmatrix} = 4 \\ \\
9\lambda = 18 \qquad \lambda=2 \\ \\
\therefore r = \begin{pmatrix}
1 \\
3 \\
-1
\end{pmatrix} \\ \\
\text{The point of intersection is at } (1,3,-1)
\end{gather*}
$$

# Shortest distance between a line and a plane
Working out shortest distance between a line and plane assumes that the line and plane do not intersect. The shortest distance will be perpendicular distance between the line and the plane. 

![[Pasted image 20250915191326.png]]

To calculate the shortest distance between a line and a plane, when given plane and point $\vec{OA}$

For such questions, always draw a diagram and try to follow each process step by step to ensure no mistakes are made. Always sanity check your answers.

If given the plane in general form with two directions vectors, calculate scalar product form by:
1. take the dot product of the to calculate the normal vector. 
2. write in $r \cdot  \vec{n} = r_{0} \cdot  \vec{n}$ where $r_{0}$ is the starting point of the plane

Else:
1. Calculate the point $\vec{OB}$ on the plane by setting either setting two variables in the equation to 0 and a final point equalling $d$
2. Calculate $\vec{BA}$ and $\vec{n}$
3. Shortest distance = 
$$
|\vec{BA} \cdot  \hat{n}|
$$
## Finding a formula

Let $\Pi : ax+by+cz=d$ and point $A$ be $A(\alpha,\beta,\gamma)$

The shortest distance will be:
$$
\begin{gather*}
l = |(\vec{OA} - r_{0}) \cdot \hat{n}| \\ \\
= \frac{|(\vec{OA}-r_{0})\cdot\vec{n}|}{|\vec{n}|} \\ \\
=\frac{|\vec{OA}\cdot\vec{n}-r_{0}\cdot\vec{n}|}{|n|} \\ \\
= \frac{\left| \begin{pmatrix}
\alpha \\
\beta \\
\gamma
\end{pmatrix} \cdot \begin{pmatrix}
a \\
b \\
c \\
\end{pmatrix} - d \right|}{\sqrt{ a^{2}+b^{2}+c^{2} }} \\ \\
= \frac{\left| a\alpha + b\beta + c\gamma -d \right|}{\sqrt{a^{2}+b^{2}+c^{2}}}
\end{gather*}
$$

This equation is in the formula book.

## Using formula
## Worked Example 1
![[Pasted image 20250915193356.png]]
$$
\begin{align*}
\Pi:&\quad \mathbf{r}\cdot(2,3,1)=19,\qquad A(-1,0,3)\\
d(A,\Pi)&=\frac{\big|\mathbf{n}\cdot\overrightarrow{OA}-19\big|}{\|\mathbf{n}\|}
=\frac{|(2,3,1)\cdot(-1,0,3)-19|}{\sqrt{2^2+3^2+1^2}}\\
&=\frac{|1-19|}{\sqrt{14}}=\frac{18}{\sqrt{14}}=\frac{9\sqrt{14}}{7}
\end{align*}
$$

## Worked Example 2
![[Pasted image 20250915193649.png]]
$$
\begin{align*}
\Pi:&\;4x-y+3z=15,\qquad A=(3\lambda,2\lambda,\lambda)\\
\text{Distance }d(A,\Pi)&=\frac{|4(3\lambda)-1(2\lambda)+3(\lambda)-15|}{\sqrt{4^2+(-1)^2+3^2}}
=\frac{|13\lambda-15|}{\sqrt{26}}=\frac{11}{\sqrt{26}}\\
&\implies |13\lambda-15|=11\\
&\implies 13\lambda-15=\pm11\\
&\implies \lambda=2\quad\text{or}\quad \lambda=\tfrac{4}{13}
\end{align*}
$$

# Shortest distance from origin to a plane
Using the formula and the other point being the origin - $O(0,0,0)$. Substituting the origin into the formula gives:

$$
\frac{\left| \begin{pmatrix}
0 \\
0 \\
0
\end{pmatrix} \cdot \begin{pmatrix}
a \\
b \\
c \\
\end{pmatrix} - d \right|}{\sqrt{ a^{2}+b^{2}+c^{2} }} \\ \\
= \frac{\left|  -d \right|}{\sqrt{  a^{2}+b^{2}+c^{2}}}
$$Therefore:
$$
\text{Shortest distance between plane and origin } = \frac{d}{|n|}
$$

Shortest distance between two parallel planes 
![[Pasted image 20250915202110.png]]

