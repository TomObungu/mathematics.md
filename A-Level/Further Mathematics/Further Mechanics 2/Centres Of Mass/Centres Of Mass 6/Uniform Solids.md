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
\bar{x} \int_{a}^{b}f(x))^{2}dx = \int_{a}^{b} x(f(x))dx
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
# Example 1
Find the x-coordinate of the centre of mass of the uniform solid formed by rotating the region under the curve for $x\geq 0$

![[Pasted image 20260218224316.png]]

When considering the shape formed by the revolutions, the mass elements will be cylinders with cross sectional areas equal to area of circles with radius $f(x)$ and heights $dx$
![[Pasted image 20260218224518.png]]

Therefore the mass element, $dm$ is equal to:
$$
dm = \rho\pi(f(x))^{2}dx
$$

With the mass element found, we can the form the equations.
$$
\begin{gather*}
dm = \rho \pi(9-x)dx \\ \\ 
\therefore \bar{x}\int_{0}^{9} \rho\pi(9-x)dx = \int_{0}^{9} x\rho \pi(9-x)dx \\ \\
\bar{x}\int_{0}^{9}(9-x)dx = \int_{0}^{9}9x-x^{2}dx \\ \\
\bar{x}\left[9x-\frac{1}{2}x^{2}\right]_{0}^{9} = \left[\frac{9}{2}x^{2}-\frac{1}{3}x^{3} \right]_{0}^{9} \\ \\
x\left( 81-\frac{81}{2} \right) = \left(\frac{729}{2}-\frac{729}{3}\right) \\ \\
\bar{x} = 3
\end{gather*}
$$
# Example 2
A uniform solid formed by rotating region $R$ through $360^\circ$ about the y-axis. 
Find the distance of the centre of mass from the plane face.


![[Pasted image 20260218230603.png]]
Now this is another volume of revolution question with mass elements that are cylinders except the radius is the function $f(y)$, meaning you must rearrange the function $y=f(x)$ to $x=f(y)$ and take the square of it to calculate the area of the cross section of the cylinder. 
![[Pasted image 20260218231034.png]]
Rearranging for $x$:
$$
f(y) = x = \sqrt{ y }
$$
Therefore the mass elements are:
$$
dm = \rho \pi (f(y))^{2}dy
$$
The y position of the centre of mass of the cylindrical mass elements is just $y$ 
Thus we can form the equations:
$$
\begin{gather*}
\bar{y}\int_{0}^{4}dm = \int_{0}^{4}ydm \\ \\
\bar{y} \int_{0}^{4}\rho \pi (\sqrt{ y })^{2}dy = \int_{0}^{4}y\rho \pi(\sqrt{ y })^{2}dy \\ \\ 
\bar{y} \int_{0}^{4}ydy = \int _{0}^{4}y^{2}dy \\ \\
\bar{y}\left[\frac{1}{2}y^{2}\right]_{0}^{4} = \left[ \frac{1}{3}y^{3}\right]_{0}^{4} \\ \\
\bar{y}(8) = \frac{64}{3} \\ \\
\bar{y} = \frac{8}{3}
\end{gather*}
$$
Now this is the crucial step, the question asks us to find the distance from the plane face, thus you must find the difference in the height of the plane and the distance of the centre of mass from the origin of the solid. Therefore:
$$
\text{Distance from top plane} = 4 - \frac{8}{3} = \frac{4}{3}
$$

