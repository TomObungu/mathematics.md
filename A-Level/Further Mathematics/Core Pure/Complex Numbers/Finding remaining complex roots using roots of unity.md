Consider $z^{n}=w$. Doing the same process yields:
$$
|z^{n}| = |w| \qquad arg(z^{n}) = arg(w)
$$
And again:
$$
\begin{gather*}
z=rei\theta \\ \\
r^{n}e^{in\theta} = |w|e^{arg(w)+2k\pi} \\ \\
r = \sqrt[n]{ |w| } \qquad n\theta = arg(w)+2k\pi
\end{gather*}
$$
Forming the table of values for $k=0,k=1,k=2,k=3\dots k=n-1$:
$$
\begin{array}{|c|c|}
\hline
\text{k} & \theta \\
\hline
0 & \frac{arg(w)}{n} \\
\hline
1 & \frac{arg(w)}{n} + \frac{2\pi}{n}\\
\hline
2 & \frac{arg(w)}{n} + \frac{4\pi}{n}\\
\hline 
3 & \frac{arg(w)}{n} + \frac{6\pi}{n} \\
\hline 
\dots  &  \dots \\
\hline
n-1  & \frac{arg(w)}{n} + \frac{2(n - 1)\pi}{n} \\
\hline
\end{array}
$$
For this we can see that the solutions are:
$$
z_{1} = \sqrt[n]{ |w| }e^{\frac{arg(w)}{n}i}, z_{2} = \sqrt[n]{ |w| }e^{\left( \frac{arg(w)}{n} +\frac{2\pi}{n} \right)i}, z_{3} =\sqrt[n]{ |w| }e^{\left( \frac{arg(w)}{n} \frac{4\pi}{n} \right)i}\dots
$$
Notice this is just:
$$
z_{1},z_{1}e^{\frac{2\pi}{n}}, z_{1}e^{\frac{4\pi}{n}},z_{1}e^{\frac{6\pi}{n}}\dots, z_{1}e^{(\frac{2(n-1)\pi}{n})i}
$$
If you recognise that is the roots of unity, then this becomes:
$$
z_{1}, z_{1}\omega,z_{1}\omega^{2},z_{1}\omega^{3}\dots
$$
These roots of $z^{n}=w$ are equally spaced on a circle, with radius $\sqrt[n]{ |w| }$ and form a regular $n-gon$, centred at the origin. 

**NOTE : You must find the first root of $z^{n} =\omega$, $z_{1}$ as normal using the process described in finding the Nth roots of Complex Numbers. Once you have found $z_{1}$ you need to multiply $z_{1}$ by the roots of unity. **

The vertices of the $n-gon$ are the corresponding roots of unity but scaled by $|z|$ and with their arguments shunted by $arg({z_{1}})$  

The $nth$ roots of any complex number sum to $0$

## Worked Example 3
Point P is one vertex of a regular hexagon, centred on the origin, on an Argand diagram.

P is represented by the complex number $1+\sqrt{ 3 }i$

Find the numbers that represent the other vertices, in exponential form. Argument can be $[0,2\pi]$:

If you know that shape is a regular hexagon, this means:
$$
z^{6}=w 
$$
Thus roots of unity will follow $\omega = \frac{2\pi}{6}, \omega^{2} = \frac{4\pi}{n}\dots$ and so on
As well as that, we are given P in which we can work out a value for $z_{1}$:
$$
z_{1} = 1 + \sqrt{ 3 }i = 2e^{\frac{\pi}{3}i}
$$
Thus the roots will be $z_{1},z_{1}\omega,z_{1}\omega^{3}\dots$
Which is:
$$
\begin{gather*}
z_{2} = 2e^{(\frac{\pi}{3}+\frac{(2\pi}{6})i} = 2e^{\frac{2\pi}{3}i} \\ \\
z_{3} = 2e^{\left( \frac{\pi}{3}+\frac{4\pi}{6} \right)i} = 2e^{\pi i}\\ \\
z_{4} = 2e^{\left( \frac{\pi}{3}+\frac{2\pi}{6} \right)i} = 2e^{\frac{4p\pi}{3}}\\ \\
z_{5} = 2e^{\left( \frac{\pi}{3}+\frac{4\pi}{6} \right)i} = 2e^{\frac{5\pi}{3}} \\ \\
z_{5} = 2e^{\left( \frac{\pi}{3}+\frac{4\pi}{6} \right)i} = 2e^{2\pi i} \\ \\
\end{gather*}
$$
# Polygons not centred around the origin
Consider $(z-\alpha)^{n}=w$

The roots of $(z-\alpha)^{n}$ form a regular n-gon centred around the orign.

To find the values of $z$, we should add $\alpha$ to each of our roots. This will shift the centre from the origin to $\alpha$.

The solutions for $z$ of $(z-\alpha)^{n}=w$ form a regular n-gon centred of $\alpha$.

They lie on a circle with radius $\sqrt[n]{ |w| }$ and centre, $\alpha$.

In order to find the roots at the centre $\alpha$ again. Find the roots as if the triangle were centred around the origin and then reverse the translation of $\alpha$ on the found roots

E.g. $(z-\alpha)^{3}=w$
![[Pasted image 20251125020900.png]]
