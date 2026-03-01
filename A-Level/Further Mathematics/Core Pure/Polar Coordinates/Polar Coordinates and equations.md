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
($-\sqrt{ 3 },-1$)

## 
Finding r:
$$r = \sqrt{ \sqrt{ 3 }^{2} + (-1)^{2} } = 2$$.
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
