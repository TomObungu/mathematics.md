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

## Uniform circular sector
For a uniform sector we will consider it in polar form. Each mass element is a sector of radius $r$, subtending an angle of $d\theta$.
![[Pasted image 20260218144618.png]]
The area of this sector is $\frac{1}{2}r^{2}d\theta$. Thus the mass element $dm$ is:
$$
dm = \frac{1}{2}\rho r^{2}d\theta
$$

Now since the arc length $r d\theta$ has infinitesimal length, it also has infinitesimal curvature. Hence the arc can can be modelled as a straight line with no curvature. If the arc is modelled as a straight line, then sector can modelled as an isosceles triangle with equal sides $r$, base $r d\theta$ and height $r$.

This can be shown in terms of limits. The length of the arc is $r d\theta$,. Now when $d\theta$ approaches 0, $\lim_{ d\theta \to 0 }$, the length of the arc is approximately equal to the length of the chord between the sector, $r\sin\theta \approx r\theta$

Since it is an isosceles triangle, the centre of mass $G$ is measured $\frac{1}{3}r$ from the bass of the triangle. This means it is measured $\frac{2}{3}$ away from the centre of the sector $O$. 
![[Pasted image 20260218145155.png]]


As the sector itself is symmetrical, we do not need to consider the the $\bar{y}$ component as it will lie on line of the midpoint of the shape. 

Therefore we only need to consider the $\bar{x}$ component  the centre of mass of the mass element. When looking at the individual mass element, we can see that the x component is just $\frac{2}{3}r\cos\theta$:

![[Pasted image 20260218150127.png]]

Therefore $x = \frac{2}{3}r\cos\theta$.

With that information it is now possible to use $\bar{x} \int dm = \int x dm$. The bounding limits are between $-\alpha$ and $\alpha$. As well as that $r^{2}$,$\rho$ and $\frac{1}{2}$ are all constant, thus they cancel out. Remember we are integrating with respect to $\theta$
$$
\begin{gather*}
\bar{x} \int_{-\alpha}^{\alpha} \frac{1}{2}\rho r^{2}d\theta =  \frac{1}{2}\int_{-\alpha}^{\alpha}\frac{2}{3}r^{2}\rho r\cos\theta d\theta \\ \\
= \bar{x}\int_{-\alpha}^{\alpha}d\theta = \int_{-\alpha}^{\alpha} \frac{2}{3}r\cos\theta d \theta \\ \\
= \bar{x}\left[\theta\right]_{-\alpha}^{\alpha} = \frac{2}{3}r\left[\sin \theta\right]_{-\alpha}^{\alpha} \\ \\  \bar{x}\left(\alpha--\alpha\right) = \frac{2}{3}r\left(\sin\alpha - \sin(-\alpha)\right) \implies \bar{x}2\alpha = \frac{4}{3}r\sin\alpha \\ \\
\therefore \bar{x} = \frac{2r\sin\alpha}{3\alpha}
\end{gather*}
$$

As expected.

## Uniform circular arc
This is the case for deriving the centre of mass of a uniform circular arc framework. As we are dealing with a framework, the lamina has no 'body' and thus we are only considering the arc itself. Therefore each mass element has is an of length $r d\theta$:
![[Pasted image 20260218151906.png]]
$$
dm = \rho r d\theta
$$
