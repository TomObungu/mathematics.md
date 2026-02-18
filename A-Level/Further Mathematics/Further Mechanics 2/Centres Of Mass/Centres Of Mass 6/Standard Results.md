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

