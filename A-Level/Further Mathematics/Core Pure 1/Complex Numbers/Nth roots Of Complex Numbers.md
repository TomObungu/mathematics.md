Suppose we want to solve the equation,
$$
z^{n}=w, z,w \in \mathbb{C}, n \in \mathbb{Z}^{+}
$$
## Worked Example 1
Let's try and solve this equation $z^{3}=2+2i$

Firstly, let's find the modulus and argument of $z^{3}$
$$
|z^{3}| = |2+2i| = 2\sqrt{ 2 } \qquad arg(z^{3}) = \frac{\pi}{4}
$$
We can use the modulus argument form and exponential form if we define $z=re^{i\theta}$. This means:
$$
\begin{gather*}
z=re^{i\theta} \\ \\
(re^{i\theta})^{3}=2\sqrt{ 2 }e^{\frac{\pi}{4}i}
\end{gather*}
$$
However from the proof in [[Exponential (Polar) Form]] that argument is not unique. If we $\pm 2k\pi$ to the argument, despite the angle of argument changing, it will still yield the same number. Thus:
$$
(re^{i\theta})^{3} = 2\sqrt{ 2 }e^{(\frac{\pi}{4} + 2k\pi)i}, \ k \in \mathbb{Z}
$$
Therefore:
$$
r^{3}e^{3i\theta}= 2\sqrt{ 2 }e^{(\frac{\pi}{4}+2k\pi)i}
$$
By comparing coefficients we can see:
$$
r^{3} = 2\sqrt{ 2 } \implies r = (2\sqrt{ 2 })^{\frac{1}{3}} = \sqrt{ 2 }
$$
and:
$$
3\theta = \frac{\pi}{4} + 2k\pi
$$
We can now sub in different values of $k$ until we have all the unique values of $\theta$:
$$
\begin{array}{|c|c|}
\hline
\text{k} & \theta \\
\hline
0 & \frac{\pi}{12} \\
\hline
1 & \frac{3\pi}{4}  \\
\hline
-1 & -\frac{7\pi}{12} \\
\hline
\end{array}
$$
Therefore the solutions to the equation are:
$$
z_{1} = \sqrt{ 2 }e^{\frac{\pi}{12}}, z_{2} = \sqrt{ 2 }e^{\frac{3\pi}{4}}, z_{3} = \sqrt{ 2 }e^{\frac{-7}{12}\pi}
$$
If we kept going we would land back at the same values of roots. For $z^{n}=w$, we get $n$ distinct roots.

It also possible work to the same solution using De Moivre's Theorem:
$$
\begin{gather*}
[r(\cos\theta+i\sin\theta)]^{3} = 2\sqrt{ 2 }\left( \cos\left( \frac{\pi}{4} + 2k\pi \right) \right) + i\sin\left( \frac{\pi}{4}+2k\pi \right) \\ \\
r^{3}(\cos 3\theta+i\sin 3\theta) = 2\sqrt{ 2 }\left( \cos\left( \frac{\pi}{4} + 2k\pi \right) \right)+i\sin\left( \frac{\pi}{4}+2k\pi \right) \\ \\
r^{3} = 2\sqrt{ 2 } \qquad 3\theta = \frac{\pi}{4} + 2k\pi
\end{gather*}
$$
## Worked Example 2
Solve:
$$
z^{n}+1 = 0, z \in \mathbb{C}
$$
From this we know that $z^{5}=-1$. If we take the same steps as before and calculate the modulus and argument of $z^{5}$:
$$
|z^{5}| = 1 \qquad |z^{5}| = \pi
$$
Again, taking $z=re^{i\theta}$:
$$
\begin{gather*}
z=re^{i\theta} \\ 
r^{3}e^{5i\theta} = e^{\pi+2k\pi} \\ \\
r^{5} = 1 \implies r = 1 \\ \\
5\theta = \pi + 2k\pi
\end{gather*}
$$
Forming the table for the different values of $k$:
For these types of questions, experimentally try out different values of k until all distinct solutions are found or all new values of $k$ will yield something outside the principle range of $-\pi<\theta<\pi$

$$
\begin{array}{|c|c|}
\hline
\text{k} & \theta \\
\hline
0 & \frac{\pi}{5} \\
\hline
1 & \frac{3\pi}{5}  \\
\hline
2 & \pi \\
\hline 
-1 & -\frac{\pi}{5} \\
\hline
-2  & -\frac{3\pi}{5} \\
\hline
\end{array}
$$
Therefore:
$$
z_{1} = e^{\frac{\pi}{5}i}, e^{\frac{3\pi}{5}}, e^{\pi}, e^{-\frac{\pi}{5}}, e^{\frac{-3\pi}{5}}
$$

# Roots Of Unity
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

## Relating this back to general roots
Consider $z^{n}=w$. Doing the same process yeilds:
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

To find the values of $z$, we should add $\alpha$ to each of our toots. This will shift the centre from the origin to $\alpha$.

The solutions for $z$ of $(z-a)^{n}=w$ form a regular n-gon centred of $\alpha$.

They lie on a circle with radius $\sqrt[n]{ |w| }$ and centre, $\alpha$.

E.g. $(z-\alpha)^{3}=w$
![[Pasted image 20251125020900.png]]
