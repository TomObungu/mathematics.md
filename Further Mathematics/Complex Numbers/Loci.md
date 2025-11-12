A Locus is a set of points that satisfy a given condition. We can define loci in the complex plane using complex numbers.

There are three types of loci that are to be known:

# Circles
Consider $\{z\in \mathbb{C}:|z|=r\}$

The points that satisfy this lie at a distance r from the origin.
Since there are in infinite number of points, these points form a circle with equation $x^{2}+y^{2}=r$:
![[Pasted image 20251112000557.png]]

Now lets consider $\{z\in \mathbb{C}:|z-z_{1}|=r\}$

The expression demands that the distance $z$ and $z_{1}$ is equal to $r$. Therefore points  points lie at a distance of $r$ form the point $a+bi$.

As well as that you can also think of it as a translation as it were a circle. The circle is translated by $-(-z_{1})$ which gives:
![[Pasted image 20251112000949.png]]
$$
(x-a)^{2}+(y-b)^{2}=r^{2}
$$
## Worked Example 1
Sketch locus of the point that satisfies:
$\{z\in \mathbb{C}:|z-4-3i|=3\}$
Find the maximum value of $arg(z)$ and minimum value of $|z|$
Drawing out the circle in the Argand diagram you can see that the largest angle will have side along the tangent of the circle. Drawing in the lines we can see that the largest value of $arg(z)$ will be $2\alpha$:
![[Pasted image 20251112001744.png]]
$$
\begin{gather*}
\alpha = \arcsin\left( \frac{3}{5} \right) = 0.644 \\
arg(z) = 2\alpha = 1.29 \\ \\=
\end{gather*}
$$
In order to work out the minimum value of $|z|$, we can see that, the minimum value will be the shortest distance to the circle. Drawing this out we can see that this will be the length of the triangle minus the radius:
![[Pasted image 20251112002207.png]]
Therefore;
$$
|z|_{min} = 5 - 3 = 2
$$
The same logic can applied to the maximum value too:![[Pasted image 20251112002447.png]]
$|z|_{max=5+3 = 8}$

![[Pasted image 20251112002243.png]]
For this question, you must find the cartesian equations of the circle and the line. For many more questions involving the complex plane, it possible to treat the circles as their cartesian equivalents. You can see that the value of $|z|_{min}$ will be one of the intersections of the line and circle:
![[Pasted image 20251112002619.png]]
$$
\begin{gather*}
\text{Equation Of Circle : } (x-4)^{2}+(y-3)^{2} = 9 \\ \\
\text{Equation Of Line : } y = \frac{3}{4}x \\ \\
\end{gather*}
$$
To find their intersections, substitute $\frac{3}{4}x$ into the circle equation:
$$
\begin{gather*}
(x-4)^{2}+\left( \frac{3}{4}x-3 \right)^{2} = 0 
\end{gather*}
$$
Expanding it all out will give:
$$
x=\boxed{\frac{8}{5}}, \frac{32}{5} \qquad y = \frac{3}{4}\left( \frac{8}{5} \right) = \frac{6}{6}
$$
This will give $z$ to be:
$$
z = \frac{8}{5}+\frac{6}{5}i
$$
# Bisectors
Consider $\{z\in \mathbb{C}:|z-z_{1}|=|z-z_{2}|\}$
$|z-z_{1}|$ is the distance from $z$ to $z_{1}$ and $|z-z_{2}|$ is the distance from $z$ to $z_{2}$. Since they are equal the points that satify the expression are equidistant from $z_{1}$ and $z_{2}$. This means that the locus will be the perpendicular bisector of $z_{1}$ and $z_{2}$:
![[Pasted image 20251112003210.png]]
## Worked Example 2
![[Pasted image 20251112003258.png]]
For this question, it is really asking us to find the perpendicular bisector between to coordinates. We treat these complex numbers as 2-D points and calculate the bisector a bit like A-level math:

![[Pasted image 20251112003416.png]]
We know that the $x$ coordinate will be the midpoint of the points:
![[Pasted image 20251112003624.png]]
$x = \frac{4+2}{2} = 3$
$y = \frac{-1+3}{2} = 1$
From then onwards, we can calculate the gradients of the line between the points and then the gradient of the perpendicular bisector:
$$
m = \frac{3--1}{4-2} = 2
$$
Therefore the gradient of locus will be:
$$
m_{\perp} = -\frac{1}{2}
$$
Substituting the midpoint points into the line formula, the perpendicular bisector is :
$$
y = -\frac{1}{2}x +\frac{5}{2}
$$
To find the minimum value of $|z|$,  we must find the shortest distance from the line. We know that the shortest distance to line is the perpendicular distance from the origin to the line. In this case it will be a line of perpendicular gradient from the origin:
![[Pasted image 20251112004101.png]]
Therefore, it will have equation $y=-\frac{1}{\left( -\frac{1}{2} \right)}=2x$ and pass through the origin. In order to find the minimum distance, find the point of intersection between it:
$$
\begin{gather*}
2x=\frac{1}{2}x+\frac{5}{2} \\ \\
x = 1 \qquad y = 2 \\ \\
|z| = \sqrt{ 1^{2}+2^{2} } = \sqrt{ 5 }
\end{gather*}
$$

# Half Lines
Consider $|\{z\in \mathbb{C}:arg(z)=\theta\}$. The point that satisfy this all have argument. The locus is the 'half-line' from the origin:
![[Pasted image 20251112004434.png]]
Now consider $\{z\in \mathbb{C}:argz(z-z_{1})=\theta$

Since we subtract $z_{1}$ from $z$ before take the argument, we can imagine that we have shifted our origin to $z_{1}$ therefore the points that satisfies this condition have argument $\theta$, but measured from $z_{1}$
![[Pasted image 20251112004630.png]]


