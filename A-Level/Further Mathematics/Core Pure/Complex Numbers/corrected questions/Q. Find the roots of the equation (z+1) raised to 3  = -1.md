![[Pasted image 20251125011437.png]]
For this question we must take $z$ as $z+1$ as a whole and solve as if it were z then reverse the translation when calculating the roots at the end:
Taking $z=z+1$ a
$$
(z+1)^{3}=-1
$$
Following the same procedure of calculating the modulus and argument:
$$
|(z+1)^{3}| = 1 \qquad arg((z+1)^{3}) = \pi
$$
Setting $(z+1)=re^{i\theta}$:
$$
\begin{gather*}
(z+1)=re^{ i\theta } \\ \\
r^{3}e^{3i\theta} = (1)e^{(\pi+2k\pi)i} \\ \\
r^{3} =1 \implies r=1 \\ \\
3\theta =  \pi + 2k\pi
\end{gather*}
$$
Substituting different values of $k$ to find the distinct solutions:
$$
\begin{array}{|c|c|}
\hline
\text{k} & \theta \\
\hline
0 & \frac{\pi}{3} \\
\hline
1 & \pi \\
\hline
-1 & -\frac{\pi}{3}\\
\hline
\end{array}
$$
Now this is the crux of the question. The values of $\theta$ will give us the roots of $(z+1)$. In order to find the roots of $z$ around the origin we must subtract $1$ from the roots of $(z+1)$:
$$
\begin{gather*}
\therefore z_{1}+1 = e^{\frac{\pi}{3}i} \\ \\
z_{2} + 1 = e^{\pi i} \\ \\
z_{3} + 1 = e^{-\frac{\pi}{3}}
\end{gather*}
$$
To find $z_{1},z_{2},z_{3}$:
$$
\begin{gather*}
z_{1} = e^{\frac{\pi}{3}i}-1 = \boxed{-\frac{1}{2} + \frac{\sqrt{ 3 }}{2}i} \\ \\
z_{2} = e^{\pi i}-1 = \boxed{-2} \\ \\
z_{3} = e^{-\frac{\pi}{3}} - 1 = \boxed{-\frac{1}{2}-\frac{\sqrt{ 3 }}{2}i}
\end{gather*}
$$
(b)  The points will always form a unit circle (radius 1) centred around $\alpha$
![[Pasted image 20251125123137.png]](
(c) In this case we are given $(z-\alpha)=z+1$. Therefore $\alpha=-1$. This means the centre of the unit circle will be around $(\alpha,0)$. Thus in our case, the points will lie on a circle with centre $(-1,0)$ with radius $1$.