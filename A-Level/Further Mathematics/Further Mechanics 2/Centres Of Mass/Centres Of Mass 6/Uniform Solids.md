It is possible to find the centres of mass of solids of revolution. 

Consider the uniform solid when $y=f(x)$ is rotated $2\pi$ around the x-axis, between $x=a$ and $x=b$. The x-axis is a line of symmetry so $\bar{y}=0$.

![[Pasted image 20260218211004.png]]

Each mass element is a circular disc with radius $f(x)$ and thickness $dx$.

Therefore the mass element of the solid, $dm$:
$$
dm = \rho \pi \left(f(x)\right)^{2}dx
$$
The x position of the centre of mass each disc is just $x$. Therefore:
$$
\bar{x} \int_{a}^{b}dm = \int_{a}^{b}xdm
$$
Writing this fully gives:
$$
\begin{gather*}
\bar{x} \int_{a}^{b} \rho \pi \left(f(x)\right)^{2}dx = \int_{a}^{b} x\rho \pi \left(f(x)\right)^{2}dx \\ \\
\bar{x} \int_{a}^{b}f(x))^{2}dx = \int_{a}^{b} x(f(x))s^{2}dx
\end{gather*}
$$
Or better:
$$
\begin{gather*}
M\bar{x} = \int_{a}^{b} \rho \pi(f(x))^{2}dx \\ \\
\boxed{ M\bar{x} = \int_{a}^{b}x(f(x))^{2}dx}
\end{gather*}
$$

Again, the $\rho$ will cancel, it best to just remember the general form for finding the centre of mass rather than trying to remember each individual case.

In this case that is
1. Determine the mass element of the form, $dm$
2. Determine the general form for the x coordinate of the mass element, $x$
3. Work out the total mass $M$ by $\int dm$ if it's not already given
4. Form the formula: 
$$
M\bar{x} = \int_{a}^{b}x(f(x))^{2}dx
$$
and solve for $\bar{x}$. 

The same applied for $\bar{y}$ except you must consider the general form for the y coordinate of the mass, $y$ and do $\int ydm$
$$

$$
