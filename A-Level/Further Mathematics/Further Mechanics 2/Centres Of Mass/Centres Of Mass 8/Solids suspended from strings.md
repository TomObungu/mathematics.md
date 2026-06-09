As with laminas, solids suspended freely are in equilibrium with their centre of mass vertically below the point of suspension.

The cylinder is suspended from a point of the circumference, $A$. We can find the angle that the side of the cylinder makes with the downward vertical using trigonometry as before. 

![[Pasted image 20260220073155.png]]


# Example 1 
A uniform solid hemisphere is suspended from a point on the circumference of its plane face. Find the angle between the downward vertical and the plane face. 
![[Pasted image 20260220073703.png]]

Now the position of the centre of mass of the hemisphere is given by $\frac{3}{8}r$ from its origin O.  

Now since the whole shape is symmetrical, we can take the same approach of considering the shape side on and drawing a line from its its line of suspension:

![[Pasted image 20260220073801.png]]

From that we can take the same approach of using trigonometry to find $\theta$:

$$
\theta = \arctan\left( \frac{\frac{3}{8}r}{r} \right) = \arctan\left( \frac{3}{8} \right) = 20.6
$$

# Example 2
A uniform solid formed when two solid cones, both of radius $a$, and height $a$ and $2a$. The solid is suspended from $A$, a point of the circumference of the plane faces. Find the angle that $OA$ makes with the downward vertical. 
![[Pasted image 20260220074053.png]]

In these problems, always consider symmetry. In this problem since the centres of mass both lie on the same horizontal line, you only need to consider the horizontal $x$ position of the centre of mass, $\bar{x}$.

Firstly, start by setting up the table to calculate the centre of mass form the composite solids:

| Object       | Cone \w height 2a         | Cone \w height a       | Total       |
| ------------ | ------------------------- | ---------------------- | ----------- |
| Volume       | $\frac{2}{3}\pi a^{3}$    | $\frac{1}{3}\pi a^{3}$ | $\pi a^{3}$ |
| Dist. From O | $-\frac{\frac{1}{2}a}{2}$ | $\frac{1}{4}a$         | $\bar{x}$   |

Setting up the formula to work out $\bar{x}$:
$$
\begin{gather*}
\frac{2}{3}\pi a^{3}\left( -\frac{a}{2} \right) + \frac{1}{3}\pi a^{3}\left( \frac{a}{4}  \right) = \pi a^{3}\bar{x} \\ \\
\bar{x} = -\frac{1}{4}a
\end{gather*}
$$

Now looking at the side view of the solid and drawing a line from the point of suspension:
![[Pasted image 20260220074554.png]]

It is possible to calculate the angle $\theta$ using trigonometry again:
$$
\theta = \arctan\left( \frac{1}{4} \right) = 14.0 ^\circ
$$

Questions may ask for the angle to the horizontal is just $90-\theta$. In this case that is $76.0^\circ$

# Example 3
 A uniform solid formed from a hemisphere of radius $r$ and a cylinder of height $\lambda r$. 

When suspended from A, a point on the circumference of the plane face of the hemisphere, $AO$ makes an angle $\theta$ to the downward vertical, where $\tan\theta = \frac{51}{44}$. Find $\lambda$.

![[Pasted image 20260220080936.png]]

For this question, the first part is just calculating the vertical position of the centre of mass, $\bar{y}$:

Taking downwards as positive:

| Object        | Hemisphere             | Cylinder            | Total                                         |
| ------------- | ---------------------- | ------------------- | --------------------------------------------- |
| Volume        | $\frac{2}{3}\pi r^{3}$ | $\lambda \pi r^{3}$ | $\left( \frac{2}{3}+\lambda \right)\pi r^{3}$ |
| Dist below O. | $-\frac{3}{8}r$        | $\frac{1}{2}\pi r$  | $\bar{y}$                                     |

Forming the equations to solve for $\bar{y}$:
$$
\begin{gather*}
\frac{2}{3}\pi r^{3}\left( -\frac{3}{8}r \right) + \lambda \pi r^{3}\left( \frac{1}{2}\lambda r \right) = \left( \frac{2}{3}+\lambda \right)\pi r^{3}\bar{y} \\ \\
\left( \frac{1}{2}\lambda^{2}-\frac{1}{4} \right)r = \left( \frac{2}{3} + \lambda \right)\bar{y}
\\ \\
\left( \frac{2\lambda^{2}-1}{4} \right)r = \left( \frac{2+3\lambda}{3} \right)\bar{y} \\ \\

\end{gather*}
$$
Therefore:
$$
\bar{y} = \frac{3(2\lambda^{2} - 1)}{4(2+3\lambda)}
$$

Now the question says that the angle between the downward vertical is $\theta$ where $\tan\theta = \frac{51}{44}$. If we draw that out diagrammatically, we see that this will correspond to another triangle. 
![[Pasted image 20260220082009.png]]
We can then form an equation in $\lambda$ to $\frac{51}{44}$ to work out $\lambda$
$$
\begin{gather*}
\tan \theta = \frac{\bar{y}}{r}
\end{gather*}
$$
Therefore:
$$
\begin{gather*}
\frac{3(2\lambda^{2}-1)}{4(2+3\lambda)}=\frac{51}{44} \\ \\
11(2\lambda^{2} - 1) =  17(2+3\lambda) \\ \\
22\lambda^{2}-11 = 34 + 51\lambda \\ \\
22\lambda^{2} - 51\lambda - 45 = 0 \\ \\ \\ 
\boxed{\lambda = 3}
\end{gather*}
$$

# Example 4
A non-uniform 3m flagpole is hinged to a vertical wall at $A$. It is held at $60^\circ$ to the wall by a wire attached at $90^\circ$, 1m from A.
![[Pasted image 20260220084703.png]]
The mass per unit length  of the rod $m=8-2x$, where $x$ is the distance from A. Find the tension in the wire. 


For this problem, you need to immediately recognise it is a moments problem. Sketching out the moments diagrammatically gives:
![[Pasted image 20260220084958.png]]

From the diagram, it becomes obvious that you first need to work out the mass of the rod $M$, then after that use integration to calculate $\bar{x}$ as from previous.

For a uniform rod, the mass elements are just point masses $dx$. Do not forget to consider the density function of the rod. Thus:
$$
dm = (8-2x)dx
$$
Now the mass $M=\int dm$, therefore we can work out the mass $M$:
$$
M = \int_{0}^{3} 8-2x d x = \left[8x-x^{2}\right]_{0}^{3} = (24-9) = 15
$$

The x-coordinate of each mass element is also just $x$.

Now we set up the whole $\bar{x}\int dm = \int xdm$ formula:

$$
\begin{gather*}
15\bar{x} = \int_{0}^{3} x(8-2x)dx \\ \\
15\bar{x} = \left[4x^{2}-\frac{2}{3}x^{3}\right]_{0}^{3} \\ \\
15 \bar{x} = \left( 36 -\frac{54}{3} \right)  \\ \\
15\bar{x} = 18 \\ \\
\bar{x} = \frac{6}{5} = 1.2m
\end{gather*}
$$
Now we we know $\bar{x}$ we can just complete the moments problem.

Taking moments at $A$:
$$
\begin{gather*}
T = 1.2(15)(9.8)\sin 60 \\ \\
T = \frac{441\sqrt{ 3 }}{5} \\ \\
T = \boxed{153N}
\end{gather*}
$$

 
