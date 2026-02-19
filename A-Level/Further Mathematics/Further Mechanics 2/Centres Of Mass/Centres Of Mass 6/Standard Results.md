The distance of the centre of mass for 
## Uniform sphere & uniform cylinder
As these shapes are symmetrical, the centre of mass is just in the centre of the shape.
![[Pasted image 20260218232112.png]]

## Uniform Solid Hemisphere
Now a uniform solid hemisphere can be modelled as a volume of revolution $2\pi$ radians around the x-axis for the graph $y=\sqrt{ r^{2}-x^{2} }$
![[Pasted image 20260218232248.png]]

Therefore the mass elements will then again be horizontal cylinders with cross sectional circles of area $\pi(f(x))^{2}$ and height $dx$
![[Pasted image 20260218232449.png]]
Therefore:
$$
dm = \rho\pi(f(x))^{2}dx
$$
The x-intercepts of the shape will be at $x=0$ and $x=r$. 

The $x$ positions of the mass elements will just be $x$ again.

Therefore we can write out the formula:
$$
\begin{gather*}
\bar{x}\int_{0}^{r}dm = \int_{0}^{r} xdm \\ \\
\bar{x} \\ \\
\bar{x}\int_{0}^{r}\rho \pi(\sqrt{ r^{2}-x^{2} })s^{2}dx = \int_{0}^{r}x\rho \pi(\sqrt{ r^{2}-x^{2} })^{2}dx \\ \\
\bar{x}\int_{0}^{r}(r^{2}-x^{2})dx = \int_{0}^{r} r^{2}x-x^{3}dx \\ \\
\bar{x}\left[r^{2}x-\frac{1}{3}x^{3}\right]_{0}^{r} = \left[\frac{1}{2}r^{2}x^{2}-\frac{1}{4}x^{4}\right]_{0}^{r} \\ \\
\bar{x}\left( r^{3}-\frac{1}{3}r^{3}\right) = \left(\frac{1}{2}r^{4}-\frac{1}{4}r^{4}\right) \\ \\
\bar{x}\left(\frac{2}{3}r^{3}\right) = \left(\frac{1}{4}r^{4}\right) \\ \\
\boxed{\bar{x} = \frac{3}{8}r}
\end{gather*}
$$

Thus the centre of mass of a uniform hemisphere is $\frac{3}{8}r$ from the centre of the hemisphere.

## Uniform Solid Cone
For a solid cone of height $h$ and radius $r$, the cone can be modelled as a volume of revolution of the function
$$
f(x)= y = -\frac{r}{h}x + r
$$
![[Pasted image 20260218233558.png]]

Therefore again the mass elements will be equal to:
$$
dm = \rho \pi\left( -\frac{r}{h}x+r \right)^{2}dx 
$$
Therefore writing out the formula:
$$
\begin{gather*}
\bar{x}\int_{0}^{h} \left( -\frac{r}{h}x +r\right)^{2} = \int_{0}^{h}x\left( -\frac{r}{h}x+r \right)^{2}  \\ \\
\bar{x}\int_{0}^{h}\left( \frac{r^{2}}{h^{2}}x^{2}-\frac{2r^{2}}{h}x+r^{2} \right)dx = \int_{0}^{h}\left( \frac{r^{2}}{h^{2}}x^{3}-\frac{2r^{2}}{h}x^{2}+r^{2}x \right) \\ \\
\bar{x}\left[ \frac{r^{2}}{3h^{2}}x^{3}-\frac{r^{2}}{h}x^{2}+r^{2}x \right]_{0}^{h} = \left[ \frac{r^{2}}{4h^{2}}x^{4}-\frac{2r^{2}}{3h}x^{3}+\frac{r^{2}}{2}x^{2} \right]_{0}^{h} \\ \\
\bar{x}\left( \frac{r^{2}}{3\cancel{ h^{2} }}h\cancel{ ^{3} }-\frac{r^{2}}{\cancel{ h }}h\cancel{ ^{2} }+r^{2}h \right) = \left( \frac{r^{2}}{4\cancel{ h^{2} }}h\cancel{ ^{4} }^{2}-\frac{2r^{2}}{3\cancel{ h }}h\cancel{ ^{3} }^{2}+\frac{r^{2}}{2}h^{2} \right) \\ \\
\bar{x}\left( \frac{r^{2}}{3}h \right) = \left( \frac{r^{2}h^{2}}{12} \right) \\ \\
\bar{x} = \frac{1}{4}h
\end{gather*}
$$
Therefore the centre of mass of a uniform cone is $\frac{1}{4}h$ from its base. 

## Uniform canonical shell
A canonical shell is like a cone of height $h$ with no inside volume - its made up of its outside surface area. It also has no base.
![[Pasted image 20260219000003.png]]
Each mass element is a sector with infinitesimal arc length $dx$. Again since the arc length is infinitesimal, each sector can be modelled as a triangle. 

The of mass of each triangular strip has centre of mass position at $\frac{1}{3}h$ from its base and therefore position $\frac{2}{3}h$ from O.

As each strip has the centre of mass at the same position, the centre of mass of the whole shell is at $\frac{2}{3}h$.

Therefore the centre of mass of the whole canonical shell also has its centre of mass  $\frac{1}{3}h$ from its base. Therefore:

$$
\bar{x} = \frac{1}{3}h \text{ From base}
$$

## Uniform hemispherical shell
Each mass element is a thin band of radius $r\sin\theta$ and thickness $r d\theta$. Thus the mass element is made up of little circumferences that have thickness $r d\theta$. 
![[Pasted image 20260219000641.png]]
Remember that the equation for the length of a circumference is $2\pi r$. In this case the circumference length is $2\pi r\sin\theta$
Therefore:
$$
dm = \rho(2\pi r\sin\theta)(r d\theta)  = 2\pi \rho r^{2}\sin\theta
$$

The $x$ coordinate of the centre of mass of each band $r\cos\theta$. Therefore setting up the formula with that:

Furthermore, we can use the surface area of a sphere formula, $4\pi r^{2}$ to the get the total mass $M$, as $2\pi r^{2}$

The limits are from $0$ to $\frac{\pi}{2}$ as that is the angle between the line $y=0$ and the band with the maximum length.
$$
\begin{gather*}
\bar{x}2\rho\pi r^{2}= \int_{0}^{\frac{\pi}{2}}2\rho\pi r^{2}\sin\theta\cos\theta d\theta \\  
\bar{x} = \frac{1}{2}r\int_{0}^{\frac{\pi}{2}}\sin 2\theta d\theta \\ \\
\bar{x} = \frac{1}{2}r \left[-\frac{1}{2}\cos 2\theta\right]_{0}^{\frac{\pi}{2}} \\ \\
\bar{x} = \frac{1}{4}r\left[\cos 2\theta\right]_{\pi}^{0} \\ \\
\bar{x} = \frac{1}{4}\left[\cos(0)-\cos(\pi)\right] \ \\ \\  
\therefore \bar{x} = \frac{1}{2} \text{ From the centre}
\end{gather*}
$$


