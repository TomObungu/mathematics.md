# Euler's Formula
Consider the Maclaurin expansions of $\cos\theta$ and $\sin\theta$.:
$$
\begin{gather*}
\cos\theta = 1-\frac{\theta^{2}}{2!} + \frac{\theta^{4}}{4!} -\frac{\theta^{6}}{6!}\dots \\ \\
\sin\theta = \theta-\frac{\theta^{3}}{3!} + \frac{\theta^{5}}{5!} -\frac{\theta^{7}}{7!}\dots
\end{gather*}
$$
Consider the same for $e^{x}$:
$$
e^{x} = 1+x+\frac{x^{2}}{2!}+\frac{x^{3}}{3!}+\frac{x^{4}}{4!} + \frac{x^{5}}{5!}\dots
$$Now let's consider $e^{i\theta}$
$$
\begin{gather*}
e^{i\theta} = 1+(i\theta) + \frac{(i\theta)^{2}}{2!} + \frac{(i\theta)^{3}}{3!} + \frac{(i\theta)^{4}}{4!} + \frac{(i\theta)^{5}}{5!} \dots
\end{gather*}
$$
Now all even powers of $i$ are real:
$$
e^{i\theta} = 1+i\theta - \frac{\theta^{2}}{2!} -\frac{i\theta^{3}}{3!} + \frac{\theta^{4}}{4!}+\frac{i\theta^{5}}{5!}\dots
$$
Separating the real from the imaginary parts:
$$
\begin{gather*}
e^{i\theta} = \underbrace{ \left( 1-\frac{\theta^{2}}{2!}+\frac{\theta^{4}}{4!}+\dots \right)  }_{ \cos\theta }+ i\underbrace{ \left( \theta-\frac{\theta^{3}}{3!}+\frac{\theta^{5}}{5!}\dots \right)  }_{ \sin\theta }
\end{gather*}
$$
Therefore:
$$
\boxed{\therefore e^{i\theta} = \cos\theta+i\sin\theta}
$$
This is is 'Eulers Formula'.
Now let's consider $\theta=\pi$:
$$
\begin{gather*}
e^{i\pi}=\cos \pi+i\sin \pi \\ 
e^{i\pi} = -1 \\ \\
\end{gather*}
$$
Therefore:
$$
e^{i\pi}+1=0
$$
This is 'Euler's' identity... The most beautiful equation in the whole of mathematics...

## Exponential / Polar form
We multiply both sides of Euler's formula by r to obtain:
$$
\underbrace{ re^{i\theta}  }_{ \text{Exponential / polar form} }= \underbrace{ r(\cos+i\sin\theta)  }_{ \text{Modulus argument form} }
$$
It is possible to convert between polar, modulus argument and Cartesian form.

## Worked Example 1
Write the following in Cartesian form:
$$
3e^{\frac{\pi}{3}} = 3\left( \cos \frac{\pi}{3}+i\sin \frac{\pi}{3} \right) =  \frac{3}{2} +\frac{3\sqrt{ 3 }}{2}Ii
$$
Write the following in exponential form:
$$
4\left( \cos \frac{\pi}{5}+i\sin \frac{\pi}{5} \right) = 4e^{\frac{\pi}{5}i}
$$

# Multiplying/Dividing Polar form
Applying the rules for modulus argument division and multiplication. We see that the normal rules for exponentiation apply:
$$
\begin{gather*}
z_{1}=r_{1}e^{i\theta_{1}}, \ z_{2} = r_{2}e^{i\theta_{2}} \\ \\
z_{1}z_{2} = r_{1}r_{2}e^{i\theta_{1}}e^{i\theta_{2}} = r_{1}r_{2}e^{i(\theta_{1}+\theta_{2})} \\ \\
\frac{z_{1}}{z_{2}} = \frac{r_{1}e^{i\theta_{1}}}{r_{2}e^{i\theta_{2}}} = \frac{r_{1}}{r_{2}}e^{i(\theta_{1}-@2)}
\end{gather*}
$$
## Powers Of Polar Form
We know that $|z^{n}|=|z|^{n}$ and $arg(z^{n})=narg(z)$. Therefore:
$$
(re^{i\theta})^{n} = r^{n}e^{ni\theta}, \forall n\in \mathbb{Z}
$$
We cannot use the rules for $n\notin\mathbb{Z}$
### Why not...?
We know that $n\in \mathbb{Z}$:
$2nk\pi$ is always a multiple of $2\pi$ . This  means:
$$
e^{2nk\pi i} =1 
$$
The solution is always unique.
![[Pasted image 20251118113111.png]]

Let's consider $n\in \mathbb{Q} \setminus \mathbb{Z}$:
Let's say $n=\frac{1}{2}$:
For $2nk\pi$ is not always an integer multiple of $2\pi$. This means that different values of $k$ give different values of $e^{2nk\pi i}$:
$$
\begin{array}{|c|c|}
\hline
\text{k} & 2nk\pi \\
\hline
0 & 0 \\
\hline
1 & \pi  \\
\hline
2 & 2\pi \\
\hline
3 & 3\pi \\
\hline
\end{array}
$$
This means that $e^{2nk\pi}$ will have two possibilities as it alternates between the odd multiples of $\pi$ $(2k-1)\pi$and even multiples of $2k\pi$. On the Argand diagram, this looks like $e^{2nk\pi}$ alternating between the negative part of the real number line:

The solutions in the case of $n=\frac{1}{2}$ will take the first values of $\pi$ and $2\pi$ and all other solutions will be the same for odd multiples and the same for even multiples
![[Pasted image 20251118113447.png]]
This means there will be multiple but finite solutions for this case:

Now let's consider $n\in \mathbb{R} \setminus \mathbb{Q}$:
As $n$ is always irrational, $2nk\pi$ is never an integer multiple of $2\pi$. This means that there are infinitely many solutions. 

From all of this we can see that we will only get one unique solution for $Z^{n}$ when $n\in \mathbb{Z}$


## Complex Conjugate of Polar Form:
Consider $re^{i\theta}=r(\cos\theta+i\sin\theta)$,
If we do $re^{-i\theta} =r(cos(-\theta)+i\sin(-\theta))$ we know that $\cos(-\theta)=\cos\theta$ and $\sin(-\theta)=-\sin\theta$, therefore:
$$
re^{i\theta}= r(\cos\theta-i\sin\theta)
$$
This is just the conjugated form for $re^{i\theta}$. Therefore:
$$\begin{gather*}
z=re^{i\theta} \ z^{*}=re^{-i\theta}
\end{gather*}
$$
# Worked Example 3
$z=\frac{e^{3i}}{1-e^{2i\theta}}$, find Im(z). To evaluate this, you must multiply by the conjugate:
$$
\frac{e^{3i}}{1-e^{2i\theta}} \left(\frac{1-e^{-2i\theta}}{1-e^{-2i\theta}}\right) = \frac{e^{3i\theta}-e^{i\theta}}{1-e^{-2i\theta}-e^{2i\theta}+1}
$$
Expressing in modulus argument form and separating the imaginary and complex form:
$$
\begin{gather*}
\frac{\cos 3\theta+i\sin 3\theta-(\cos\theta+i\sin\theta)}{2-(\cos 2\theta-i\sin 2\theta)-(\cos 2\theta +i\sin 2\theta)} \\ \\
= \frac{(\cos 3\theta-\cos\theta)+i(\sin 3\theta-\sin \theta)}{2-2\cos 2\theta}
\end{gather*}
$$
Therefore:
$$
\mathrm{Im}(z) = \frac{\sin 3\theta - \sin\theta}{2 - 2\cos 2\theta}
$$
# Worked Example 4
We know that $z=1+i\sqrt{ 3 }$, $\mathrm{Re}\left( \frac{z^{2}}{w} \right)=0$, $\left|\frac{z^{2}}{w}\right|=|z|$
Use geometric reasoning to find two possilble values for $w$, in the form $w=re^{i\theta}$.

The first step in this question is to always draw a diagram:
![[Pasted image 20251118124351.png]]
If we know that the real part of the equation will be $0$ then the equation will have two values of its magnitude in terms of $i$. 
$$
\begin{gather*}
arg(z) = \frac{\pi}{3}, \ |z| = 2 \\ \\
\mathrm{Re}\left( \frac{z^{2}}{w} \right)=0 \qquad arg\left( \frac{z^{2}}{w} \right)=\frac{\pi}{2 } \ or \ \frac{3\pi}{2} \\ \\
arg\left( \frac{z^{2}}{w} \right) = 2arg(z) - arg(w) \\ \\
\therefore arg(w) = 2\left( \frac{\pi}{3} \right) - \frac{\pi}{2} = \frac{\pi}{6} \\ \\ or \\ \\
arg(w) = 2\left( \frac{\pi}{3} \right) - \frac{3}{2} = -\frac{5\pi}{6} \\ \\
\therefore w = 2e^{\frac{\pi}{5}i} \qquad w=2e^{\frac{-5\pi}{6}i}
\end{gather*}
$$


