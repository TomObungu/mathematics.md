We also need to find centres of mass by integration where $\rho$ is not constant and is instead a function of position. e.g the position is $(x,\theta,etc.)$

As long as we remember our general form for finding the centre of mass, this is straightforward. 

# Example 1
A solid cylinder is formed by rotating region R $360^\circ$ around the x-axis. The density of the solid at $(x,y,z)$ is $3(x+1)$/ Find the distance of the centre of mass from O. 

![[Pasted image 20260220064413.png]]

Now if you consider the volume of revolution formed, you can see that mass elements will again be cylinders of cross sectional area equal to $\pi(f(x))^{2}$ and height $dx$. However this time, in order to find $dm$ you must multiply by $\rho$, which is the density of the solid.

![[Pasted image 20260220064849.png]]


Therefore the mass element $dm$ becomes:
$$
dm = 3(x+1)(2)^{2}\pi = 12\pi(x+1)
$$


Now the $x$ element of the centre of mass of each mass element is just $x$ again. Therefore:
$$
\bar{x} \int_{0}^{5} dm = \int_{0}^{5}xdm
$$
Substituting $dm$ into the formula:
$$
\begin{gather*}
\bar{x} \int_{0}^{5} 12\pi(x+1) = \int_{0}^{5}12\pi x(x+1) \\ \\
\bar{x} \left[\frac{1}{2}x^{2}+x\right]_{0}^{5} = \left[\frac{1}{3}x^{3}+\frac{1}{2}x^{2}\right]_{0}^{5} \\ \\
\frac{35}{2}\bar{x} = \frac{325}{6}
\end{gather*}
$$
Therefore:
$$
\bar{x} = \frac{65}{21} \text{ From O}
$$
Initially, since $\rho$ is increasing, we can expect the centre of mass to be more than halfway.

# Example 2
A solid framework is formed by rotating region R $360^\circ$ about the x-axis. The density of the solid at $(x,y,z)$ is $\frac{\lambda}{x}$
![[Pasted image 20260220065426.png]]
Find the distance of the centre of the centre of mass form O.

Remember for a hemispherical shape, the volume of revolution of the function $f(x)=y=\sqrt{ a^{2}-x^{2} }$. Each mass element is also a cylinder with cross sectional area $\pi(f(x))^{2}$ and height $dx$. As well as that we must multiply each mass element by its density $\frac{\lambda}{x}$:

$$
\begin{gather*}
dm = \pi(a^{2}-x^{2})\left( \frac{\lambda}{x} \right)dx  \\ \\
\end{gather*}
$$

The x-coordinate of the centre of mass of each mass element is also just $x$ again. Therefore we can set up the formulae and solve for $\bar{x}$:

$$
\begin{gather*}
\bar{x} \int_{\frac{a}{3}}^{a}dm = \int_{\frac{a}{3}}^{a}xdm \\ \\
\bar{x} \int_{\frac{a}{3}}^{a} \frac{\lambda\pi}{x}(a^{2}-x^{2}) = \int_{\frac{a}{3}}^{a}\lambda \pi(a^{2}-x^{2}) \\ \\
\bar{x}\int_{\frac{a}{3}}^{a} \frac{a^{2}}{x}-x = \int_{\frac{a}{3}}^{a}a^{2}-x^{2} \\ \\
\bar{x}\left[a^{2}\ln x-\frac{1}{2}x^{2}\right]_{\frac{a}{3}}^{a} = \left[a^{2}x -\frac{1}{3}x^{3}\right]_{\frac{a}{3}}^{a} \\ \\
\bar{x}\left( \left( a^{2}\ln a-\frac{1}{2}a^{2} \right)-\left( a^{2}\ln\left( \frac{a}{3} \right)-\frac{1}{18}a^{2} \right) \right) = \left( \left( a^{2}-\frac{1}{3}a^{3} \right)-\left( \frac{1}{3}a^{3} - \frac{1}{81}a^{3} \right) \right) \\ \\
\bar{x}\left( a^{2}\ln{3} - \frac{4}{9}a^{2} \right) = \frac{28}{81}a^{3} \\ \\
\bar{x} = \frac{28}{8\ln 3 - 36}
\end{gather*}
$$
bar