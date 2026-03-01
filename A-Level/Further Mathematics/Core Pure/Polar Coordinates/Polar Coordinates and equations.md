Polar coordinates are an alternative way of describing the position of a point $P$ in two-dimensional space. You need two measurements: firstly, the distance the point is from the pole (usually the origin O), $r$ and secondly, the angle measured anticlockwise from the initial line (usually the positive x-axis), $\theta$. 

Polar coordinates are written as $(r,\theta)$.

![[Pasted image 20260222221204.png]]

When working in polar coordinates, the axis might also be labelled like this:
![[Pasted image 20260222221230.png]]

The coordinates of $\mathrm{P}$ can be written in either Cartesian form as $(x,y)$ or in polar forms as $(r,\theta)$. 

You can convert between Cartesian coordinates and polar coordinates using right-angled triangle trigonometry. 

From the diagram above you can see that:
$$
\begin{gather*}
r\cos \theta = x \\ \\
r\sin \theta = y \\ \\
\end{gather*}
$$
Therefore:
$$
\begin{gather*}
r^{2} = x^{2} + y^{2} \\ \\
\theta = \arctan\left( \frac{y}{x} \right)
\end{gather*}
$$
Always draw a diagram to check in which quadrant the point lies. Always measure the polar angle from the positive x-axis. 
# Example 1
Find polar coordinate of the point with the following Cartesian coordinate
## a ($-\sqrt{ 3 },-1$)
Finding r:
$$r = \sqrt{ \sqrt{ 3 }^{2} + (-1)^{2} } = 2$$
Finding $\theta$:
![[Pasted image 20260301074444.png]]
$$
\alpha = \arctan\left( \frac{1}{\sqrt{ 3 }} \right) = \frac{\pi}{6}
$$
The point is in the third quadrant and we want to measure from the positive x-axis. Therefore we must add $\pi$ to correct it.:
$$
\therefore \theta = \pi + \frac{\pi}{6} = \frac{7\pi}{6}
$$
So the polar coordinates are:
$$
\left( 2, \frac{7\pi}{6} \right)
$$
## b $(5, -12)$
The $\arctan$ function on your calculator will mostly likely return a negative value for negative values. Thus it is possible to have negative numerator for fractional values. In this case $-\frac{12}{5}$ can be directly typed in for the angle and used. 

However there is ambiguity. $\arctan$ will not be to distinguish the angles for the points $(5,-12)$ and $(-5,12)$ as $\frac{12}{-5}$ will yield the same value for $\frac{-12}{5}$. 

In general, you use it directly if the numerator of the fraction is the one that is negative.

Finding $r$:
$$
r = \sqrt{ 5^{2} + (-12)^{2} } = 13
$$

Finding $\theta$:
![[Pasted image 20260301080621.png]]
$$
\theta = \arctan\left( -\frac{12}{5} \right) = -1.176\dots
$$
Therefore the polar coordinates are:
$$
(13, -1.176)
$$
## c $(-2,1)$
In this case since the denominator of the fraction will be negative. You must correct the angle accordingly to avoid ambiguity between the angle for  $(2,-1)$:

Finding $r$:
$$
r = \sqrt{ (-2)^{2} + 1^{2} } = \sqrt{ 5 } 
$$
Finding $\theta$:
![[Pasted image 20260301080959.png]]

$$
\theta = \arctan\left( \frac{1}{-2} \right) = -0.464 + \pi = 2.678
$$

Therefore the polar coordinates are:
$$
(\sqrt{ 5 }, 2.678)
$$


# Example 2
Convert the following polar coordinate into Cartesian form. The angles are in radians and are measured form the positive x-axis
$$
\left( 10, \frac{4\pi}{3} \right)
$$
Finding $x$:
$$
x = r\cos\theta = 10\cos \frac{4\pi}{3} = -5
$$
Finding $y$:
$$
y = r\sin\theta = 10 \sin \frac{4\pi}{3} = -5\sqrt{ 3 }
$$


So the Cartesian coordinates are:
$$
(-5, -5\sqrt{ 3 })
$$


# Example 3
Find the Cartesian coordinate of the following polar curve:
## a $r=5$
You need to replace $r$ with an equation in $x$ and $y$. Use $x^{2}+y^{2}=r^{2}$. So the equation $r=5$ represents an circle with centre $O$, with radius $5$. So a Cartesian equation is:
$$
x^{2} + y^{2} = 5
$$
## b $r = 2+\cos 2\theta$
It is possible to simplify polar equations use trigonometric identities
