If we consider an equation $z^{n}=1$. If we follow the same procedure:
$$
\begin{gather*}
|z^{n}| = 1 \qquad arg(z^{n}) = 0 \\ \\
z = re^{i\theta} \\ \\
r^{n}e^{in\theta} = e^{0+2k\pi} \\ \\
r = 1 \qquad n\theta = 2k\pi
\end{gather*}
$$
Solving for values of $k=0, k=1,k=2...k=n-1$:
$$
\begin{array}{|c|c|}
\hline
\text{k} & \theta \\
\hline
0 & 0 \\
\hline
1 & \frac{3\pi}{5}  \\
\hline
2 & \frac{\pi 2\pi}{n}\\
\hline 
3 & \frac{4\pi}{n}\\
\hline 
\dots  &  \dots \\
\hline
n-1  & \frac{2(n-1)\pi}{n}\\
\hline
\end{array}
$$
We can see that for $z_{n}$ the solution is $e^{\frac{2(n-1)\pi}{n}i}$

If we define $\omega=e^{\frac{2\pi}{n}i}$, we can see that solutions to $z^{n}=1$ are:
$$
z = 1, \omega, \omega^{2},\omega^{3}\dots,\omega^{n-1}
$$
These are called the $nth$ roots of unity. 
## Properties of Roots Of Unity
The first root of the roots of unity will always be $1$

The arguments of the roots are evenly spaced by $\frac{2\pi}{n}$. All the roots all lie on the unit circle

Therefore, these roots will form the vertices of a regular n-sided polygon or 'n-gon':

For example:
$z^{3}=1$
![[Pasted image 20251125012543.png]]

$z^{5}=1$
![[Pasted image 20251125012602.png]]\

If we consider $z^{3}=1$. If we visualise $z_{1}+z_{2}+z_{3}$ by considering the vector addition. We can see the end result will be $0$:
![[Pasted image 20251125013159.png]]
Therefore:
$$
z_{1}+z_{2}+z_{3} = 0
$$
Therefore:
$$
1+\omega+\omega^{2} + \omega^{3} +\dots + \omega^{n-1} = 0
$$
