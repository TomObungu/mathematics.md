we can now up with a more general formula for finding centres of mass that will help us when we extend it to different scenarios.

For a discrete mass distribution, we have:
$$
M\bar{x} = \sum xm \ \ \text{and} \ \ M\bar{y} = \sum xm
$$

Consider now a general case where we want to find the centre of mass of a continuous mass distribution. 

We model the mass distribution as if it is made up of mass elements. Each mass element is denoted as $dm$.

We can then sum these elements over the whole mass distribution to obtain:

$$
\begin{gather*}
M\bar{x} = \int xdm  \\ \\ M\bar{y} = \int ydm
\end{gather*}
$$
Or:
$$
\begin{gather*}
\bar{x} \int dm = \int xdm \\ \\  \bar{y} \int dm = \int ydm
\end{gather*}
$$
Here $x$ and $y$ are the positions of the centres of mass of the **mass elements** and $\bar{x}$ and $\bar{y}$ are components of the coordinates of the continuous mass distribution of course.

Now recall from our previous scenario. $x$ is just $x$ and $y=\frac{1}{2}f(x)$.
Therefore:
$$
\begin{gather*}
dm = \rho f(x)dx \\ \\ 
x = x \\ \\
y = \frac{1}{2}f(x)
\end{gather*}
$$

Now this yields the same result as before for all continuous mass distribution over the $xy$ (Cartesian) plane. However in our next example, we will see that  we will not be using $xy$  plane where mass elements are modelled as rectangles, but using the polar plane where mass elements are separate to rectangles

# Deriving previous results

## Uniform Sector
For a uniform sector we will consider it in polar form. Each mass element is a sector of radius $r$, subtending an angle of $d\theta$.
![[Pasted image 20260218144618.png]]
The area of this sector is $\frac{1}{2}r^{2}d\theta$. Thus the mass element $dm$ is:
$$
dm = \frac{1}{2}\rho r^{2}d\theta
$$

Now since the arc length $r d\theta$ has infinitesimal length, it also has infinitesimal curvature. Hence the arc can can be modelled as a straight line with no curvature. If the arc is modelled as a straight line, then sector can modelled as an isosceles triangle with equal sides $r$, base $r d\theta$ and height $r$.

Since it is an isosceles triangle, the centre of 


