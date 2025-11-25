![[Pasted image 20251125113238.png]]
In this question, we first have to translate the vertices so that the triangle is centred around the origin. 
In this case $z=3-2i$ and the triangle is centred at $\alpha=2-3i$. This means $(z-\alpha)$ will have the roots of triangle centred at the origin. With $(z-\alpha)$ we can compute the roots with the roots of unity:
$$
\begin{gather*}
z=3-2i \qquad \alpha = 2-3i \\ \\
(z-\alpha) = 1-5i
\end{gather*}
$$
As the shape is a triangle, the roots of unity $\omega$ will be:
$$
\omega = e^{\frac{2\pi}{3}i}
$$
As we are given a vertex, we can take that as our value of $z_{1}$:
$$
z_{1} = 1-5i
$$
The remaining roots **centred around the origin** will be:
$$
\begin{gather*}
z_{2}  = z_{1}\omega = (1-5i)\left( e^{\frac{2\pi}{3}i} \right) = \left( \frac{1}{2} + \frac{5\sqrt{ 3 }}{2} \right) + \left( \frac{5}{2}+\frac{\sqrt{ 3 }}{2} \right)i \\ \\
z_{3} = z_{1}\omega^{2} = (1-5i)\left( e^{\frac{2\pi}{3}i} \right)^{2} = \left( -\frac{1}{2} - \frac{5\sqrt{ 3 }}{2} \right) + \left( \frac{5}{2}-\frac{\sqrt{ 3 }}{2} \right)i 
\end{gather*}
$$
However in order for the roots to be centred around (2,3) we must reverse the translation i.e $(z+\alpha)$ again:
$$
\begin{gather*}
z_{1} + 2+3i = 3 - 2i\\ \\
z_{2} + 2+3i = \left( \frac{3}{2}+\frac{5\sqrt{ 3 }}{2} \right)+\left( \frac{11}{2}+\frac{\sqrt{ 3 }}{2} \right)i \\ \\
z_{3} + 2+3i = \left( \frac{3}{2}-\frac{5\sqrt{ 3 }}{2} \right)+\left( \frac{11}{2}-\frac{\sqrt{ 3 }}{2} \right)i \\ \\
\end{gather*}
$$
Thus the coordinates will be:
$$
\begin{gather*}
\boxed{(3 , 2)} \\ \\
\boxed{\left( \frac{3}{2}+\frac{5\sqrt{ 3 }}{2} ,\frac{11}{2}+\frac{\sqrt{ 3 }}{2} \right)} \\ \\
 \boxed{\left( \frac{3}{2}-\frac{5\sqrt{ 3 }}{2} , \frac{11}{2}-\frac{\sqrt{ 3 }}{2} \right)}
\end{gather*}
$$


