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

Shortest distance between two parallel planes is the the absolute value of difference in the distance from the origin of $d_{2}$ and $d_{1}$
![[Pasted image 20250915202223.png]]
## Worked Example 1
Work out the shortest distance between:
![[Pasted image 20250915202354.png]]
$$
\begin{gather*}
d_{1} = \frac{15}{\sqrt{ 5^{2}+2^{2}+1^{2}}} = \frac{15}{\sqrt{ 30 }}\\ \\
d_{2} = \frac{25}{\sqrt{ 5^{2} + 2^{2}+1^{2} }} = -\frac{25}{\sqrt{ 30 }} \\ \\ \\
d= \left| \frac{15}{\sqrt{ 30 }} - -\frac{25}{\sqrt{ 30 }} \right| = \frac{40}{\sqrt{ 30 }} = \frac{4}{3}\sqrt{ 30 }
\end{gather*}
$$


# Reflecting a line on a plane
To reflect a line through a plane you must find the equation $l_{2}$ of the reflected in the plane:

#### 1. Find point of intersection of line $l_{1}$ and plane $\vec{OB}$
1. Calculate an intersection point B by taking the dot product of the point on the line and the normal vector of the plane. 
2. Calculate the point $\vec{B}$ on the line
3. Take the dot product between $\vec{A}$ and $\vec{B}$ to calculate $\lambda$

#### 2. Find line equation of normal $l_{3}$
1. Find the equation of a line in direction ($l_{3}$) to the normal using starting point of given line and normal vector direction represented using $\gamma$ as the constant of the direction vector
2. Calculate  $\gamma$ by using the dot product and  normal to calculate the point of intersection of $l_{3}$ and the plane
3. Calculate the point of intersection $\vec{OM}$ using the value of $\gamma$ as the scalar 

### 3. Find starting point of $l_{1}$ reflected in plane $OA'$ and direction vector $AB$
1. Calculate the starting point of the line reflected by the plane  $\vec{OA'}$ 
2. Calculate $\vec{A'B}$  as the direction vector of $l_{2}$

The equation of $l_{2}$ is $\vec{OA'}$ + $\mu$$\vec{AB}'$

For questions like this it is best to diagrammatically work through each part with reasoning

## Written Example 1
![[Pasted image 20250915213108.png]]

## Reflecting a point in a plane
![[Pasted image 20250915213426.png]]#
###  My hack for this
a
The shortest distance can be calculated using the formula
$$
d = \frac{\left| -2(1) + 3 - 5 \right|}{\sqrt{ 2^{2}+1^{2}+1^{2} }} = \frac{2\sqrt{ 6 }}{3}
$$
b
The shortest distance is the distance between the line and the point of intersection in the direction of the normal (through the normal)
![[Pasted image 20250915215723.png]]
Recall from [[Lines Distances]] reflecting a point in a line is the vector from $\vec{A}$ to the intersection of the plane in direction of $n$ multiplied by 2.

However since this is a plane we can use calculate the reflection in the point $\vec{A}$ by multiplying the distance 2 and then multiplying that by the scalar product. This in essence has the same affect of finding the vector component in the direction of the normal. If you recall this from [[Dot Product (Scalar Product)]].

Working out the shortest distance has the same effect as  calculating the component of ($r_{0} - \vec{OA}$) in direction $\hat{n}$
![[Pasted image 20250915222142.png]]
Recall from [[Dot Product (Scalar Product)]] the vector component of ($r_{0} - \vec{OA}$ ) in direction $n$ is 
$$
((r_{0} \cdot  \vec{OA})\cdot \hat{n}) \cdot n
$$
This is just the shortest distance multiplied by $n$ thus to calculate the reflection on the point $\vec{OA}$, $\vec{OQ}$ simply do the starting point plus two times the vector component in direciton $n$:
$$

$$