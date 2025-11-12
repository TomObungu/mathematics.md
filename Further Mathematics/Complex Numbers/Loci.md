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

# Worked Example 3
Sketch the locus of the points that satisfies:
$\{z\in \mathbb{C}:arg(z-3)=\frac{3}{4}\pi\}$
and find the minimum value of $|z|$.
Drawing out the locus involves showing that that angle is obtuse. The minimum value of $|z|$ will just be the perpendicular distance from the origin:
![[Pasted image 20251112005303.png]]
From the triangle formed we can see that:
![[Pasted image 20251112005322.png]]

## Worked Example 4
![[Pasted image 20251112005834.png]]
For this example, you need to carefully draw the locus. Always consider which angle is bigger. If one angle is less than the other the intersect, however if one angle is greater or they are parallel, there will be no intersection:
![[Pasted image 20251112005955.png]]
The next thing with theis question is to realise that the gradient of these lines will always be equal to $\tan\theta$:
![[Pasted image 20251112010035.png]]
Once the line equations have been found, set them equal to each other and solve for $x$ and $y$ to give you $z$.
## Worked Example 5
![[Pasted image 20251112010153.png]]
For this question you must draw circles and also draw the locus. In this question, locus can only be the max value if it less than the tangent lines of the circle:
![[Pasted image 20251112010252.png]]

# Regions
If a complex number satisfies a inequality, we can shade a region in the complex plane.

## Circles
Consider $\{z\in \mathbb{C}:|z-z_{1}|\leq r\}$
![[Pasted image 20251112010416.png]]

# Bisectors
Consider $\{z\in \mathbb{C}:|z-z_{1}|>|z-z_{1}|\}$

The distance from $z$ to $z_{2}$ is less than the distance from $z$ to $z_{1}$. The points that satisfy this are closer to $z_{2}$ than $z_{1}$:
![[Pasted image 20251112010550.png]]

# Half-lines
Consider $\{z\in \mathbb{C}:\theta_{1}\leq arg(z-z_{1})\leq \theta_{2}\}$
The argument measured from $z_{1}$ lies between these half-lines:
![[Pasted image 20251112010734.png]]

# Worked Example 6
Sketch the region defined by the following expression and its exact area:
$\{|z-4-5i|\leq_{2}\}\cap\left\{ z\in \mathbb{C}:arg(z-4-3i)\leq \frac{\pi}{3}  \right\}$
The hardest parts of these problems are ensuring that your diagram is drawn correctly. With a correctly drawn diagram, you willl see that that region forms the area of a segment with angle $\alpha$ subtending it:
![[Pasted image 20251112011018.png]]
The angle alpha can be calculated due it it being an isosceles triangle:
$$
\begin{gather}
\alpha = \pi - 2\left( \frac{\pi}{2} - \frac{\pi} {3}\right) = \frac{2\pi}{3} \\ \\ \\
\end{gather}
$$
We know from the area of a segment formula:
$$
A = \frac{1}{2}r^{2}(\theta-\sin\theta)
$$
Therefore the area is:
$$
\frac{1}{2}(2)^{2}\left( \frac{2}{3}\pi - \sin\left( \frac{2}{3}\pi \right) \right) = \boxed{\frac{4}{3}\pi-\sqrt{ 3 }}
$$



