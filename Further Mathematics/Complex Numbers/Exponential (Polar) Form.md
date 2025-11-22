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
z_{1}=r_{1}e^{i\theta_{1}}, \ r_{2}e^{i\theta_{2}} \\ \\
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


# Definitions of $\sin\theta$ and $\cos\theta$
We can use Euler's formula to obtain definitions for $\sin\theta$ and $\cos\theta$:
$$
\begin{gather*}
e^{i\theta} = \cos\theta+i\sin\theta \\ 
e^{-i\theta} = \cos\theta-i\sin\theta \\ \\
e^{i\theta}+e^{-i\theta} = 2\cos\theta \\ 
\therefore \boxed{\cos\theta = \frac{e^{i\theta}+e^{-i\theta}}{2}} \\ \\
e^{i\theta}-e^{i\theta} = 2i\sin\theta \\ 
\therefore \boxed{\sin\theta = \frac{e^{i\theta}-e^{-i\theta}}{2i}}
\end{gather*}
$$
# De Moivre's Theorem
Consider $z=r(\cos\theta+i\sin\theta)$ then $z^{n}=r^{n}(\cos\theta+i\sin\theta)^{n}$. If were to write this identity in exponential form:
$$
z=re^{i\theta} \qquad z^{n}=(re^{i\theta})^{n} = r^{n}e^{in\theta}
$$
We also know that $z^{n}=r^{n}(\cos(n\theta)+i\sin(n\theta))$. Therefore we can form an identity using De Moivre's theorem:
$$
\boxed{[r(\cos\theta + i\sin\theta)]^{n} = r^{n}(\cos(n\theta)+i\sin(n\theta))}
$$

# Proving Trigonometric Identities using polar form and De Moivre's theorem
# Worked Example 1
Show that $\cos 5\theta=16\cos ^{5}\theta-20\cos ^{3}\theta+5\cos\theta$:

Using the identity from De Moivre's theorem:
$$
(\cos(5\theta)+i\sin(5\theta)) = (\cos\theta+i\sin\theta)^{5}
$$
In order to obtain a value for $\cos 5\theta$ we must take $\mathrm{Re}(\cos 5\theta+i\sin 5\theta)$ and as result the the real part of the of the expansion of $(\cos\theta+i\sin\theta)^{5}$. 

We can use the binomial expansion to computer $(\cos\theta +i\sin\theta)$ as well as that we can make substitutions for $\sin\theta$ and $\cos\theta$ as $c = \cos\theta$ and $g=\sin\theta$ (I am making g the substitution as my s looks like a 5 on paper):
$$
\begin{gather*}
(\cos\theta+i\sin\theta)^{5} = c^{5}+\begin{pmatrix}
5 \\
1
\end{pmatrix}c^{4}(ig)+\begin{pmatrix}
5 \\
2
\end{pmatrix}c^{3}(ig)^{2}+\begin{pmatrix}
5 \\
3
\end{pmatrix}c^{2}(ig)^{3}+\begin{pmatrix}
5 \\
4
\end{pmatrix}c(ig)^{4}+ \begin{pmatrix}
5 \\
5
\end{pmatrix}(ig)^{5}
\end{gather*}
$$
We know that all even powers of $i$ are real thus, in order to obtain the real part of the expansion, we must consider the even power in the binomial expansion:
$$
\begin{gather*}
\mathrm{Re}(\cos\theta+i\sin\theta)^{5} = c^{5}+\begin{pmatrix}
5 \\
2
\end{pmatrix}c^{3}(ig)^{2}+\begin{pmatrix}
5 \\
4
\end{pmatrix}c(ig)^{4} \\ \\ 
= c^{5}-10c^{3}g^{2}+5cg^{2}
\end{gather*}
$$
Now in order to make everything in terms of $\cos\theta$, we must turn the $\sin ^{2}\theta$ into $1-\sin ^{2}\theta$ which is $1-c^{2}$. We write higher powers of $\sin\theta$ e.g $\sin ^{4}\theta$as $(1-\cos ^{2}\theta)^{2}$ which is $(1-c^{2})^{2}$
$$
\begin{gather*}
= c^{5}-10c^{3}(1-c^{2}) + 5c(1-c^{2})^{2} \\ \\
= c^{5}-10c^{3}+10c^{5}+5c(1-2c^{2}+c^{4}) \\ \\
= c^{5}-10c^{3}+10c^{5}+5c-10c^{3}+5c^{5} \\ \\
= 16c^{5}-20c^{3}+5c 
\end{gather*}
$$
Rewriting in terms of $\cos\theta$:
$$
\begin{gather*}
= 16\cos ^{5}\theta - 20\cos^{3}\theta+5\cos\theta \\ 
QED
\end{gather*}
$$
## Worked Example 1 continued:
Use the solution to find the distinct solutions of:
$$
\begin{gather*}
16x^{5}-20x^{3}+5x=0 \\ \\\
\end{gather*}
$$
We can solve this by substituting $x=\cos\theta$ and solving in the range $0\leq\theta\leq 360$ to give us distinct values of $\cos \theta$. Since it is 5th degree polynomial, we can have up to 5 **distinct** solution's. Once we have at least 5 distinct solutions when solving, we can take that the solutions as that set of values. 

This is because $\sin\theta$ and $\cos\theta$ are oscillating functions and may repeat solutions within the range. If you do not have 5 distinct solutions by the time you have solved to $\theta=360$ then the function has repeated solutions.

If $16\cos ^{5}\theta-20\cos ^{3}\theta+5\cos\theta=0$ then $\cos 5\theta=0$. Solving for $\cos 5\theta$ using the calcuator and to 3 significant figures:

![[Pasted image 20251122184246.png]]


# Other trig identities
Consider $z=\cos\theta+i\sin\theta$. Now $z^{n}=(\cos\theta+i\sin\theta)^{n}$ . From polar form we know that $\frac{1}{z^{n}}=z^{-n}=(\cos\theta+i\sin\theta) = \cos(n\theta)-i\sin n\theta$. Therefore we know that:
$$
\begin{gather*}
z^{n}+\frac{1}{z^{n}} = 2\cos n\theta \\ \\
z^{n}-\frac{1}{z^{n}} = 2\sin n\theta
\end{gather*}
$$
We must be able to recognise these definitions too.

# Worked Example 2
Show that $\cos ^{5}\theta=\frac{1}{6}\cos 5\theta+\frac{5}{16}\cos 3\theta+\frac{5}{8}\cos\theta$

To do this question, we must use $z=\cos\theta+i\sin\theta$ and the fact that $\left( z+\frac{1}{z} \right)^{5}=(2\cos\theta)^{5}$ . We can expand $\left( z+\frac{1}{z} \right)^{5}$ using the Binomial expansion:
$$
\begin{gather*}
\left( z+\frac{1}{z} \right)^{5} = z^{5}+\begin{pmatrix}
5 \\
1 
\end{pmatrix}z^{4}\left( \frac{1}{z} \right)+\begin{pmatrix}
5 \\
2 
\end{pmatrix}z^{3}\left( \frac{1}{z} \right)^{2} + \begin{pmatrix}
5 \\
3 
\end{pmatrix}z^{2}\left( \frac{1}{z} \right)^{3}+\begin{pmatrix}
5 \\
4
\end{pmatrix}z\left( \frac{1}{z} \right)^{4}+\begin{pmatrix}
5 \\
5
\end{pmatrix}\left( \frac{1}{z} \right)^{5} \\ \\ 
= z^{5}+5z^{3}+10z+10\left( \frac{1}{z} \right)+5\left( \frac{1}{z^{3}} \right)+\frac{1}{z^{5}}
\end{gather*}
$$
Now in order to get trigonometric functions of $\cos$ in the expansion, we must group everything in terms of $\left( z^{n}+\frac{1}{z^{n}} \right)$:
$$
=\left( z^{5}+\frac{1}{z^{5}} \right)+5\left( z^{3}+\frac{1}{z^{3}} \right)+10\left( z+\frac{1}{z} \right)
$$
We must now substitute $\left( z^{n}+\frac{1}{z^{n}} \right)$ as $2cos(n\theta)$:
$$
= 2\cos 5\theta +10\cos 3\theta + 20\cos\theta
$$
We know this $\equiv(2\cos ^{5}\theta)^{5}=32\cos ^{5}\theta$.  Thus we can set them equal and get the value of $\cos ^{5}\theta$:
$$
\begin{gather*}
\implies 32\cos ^{ 5}\theta = 2\cos 5\theta+10\cos 3\theta+20\cos \theta \\ \\
\therefore \cos ^{5}\theta = \frac{1}{16}\cos 5\theta + \frac{5}{16}\cos 3\theta + \frac{5}{8}\cos\theta \\ 
QED
\end{gather*}
$$
# Worked Example 3
Show that $\sin ^{4}\theta=\frac{1}{8}\cos(4\theta)-\frac{1}{2}\cos(2\theta)+\frac{3}{8}$. 
We know that $\left( z-\frac{1}{z} \right)^{4}=(2i\cos\theta)^{4}=16\sin ^{4}\theta$. Therefore we can equate $16\sin ^{4}\theta$ to the expansion of $\left( z-\frac{1}{z} \right)^{4}$:
$$
\begin{gather*}
\left( z-\frac{1}{z} \right)^{4} = z^{4}+\begin{pmatrix}
4 \\
1 
\end{pmatrix}z^{3}\left( \frac{1}{z} \right)+\begin{pmatrix}
4 \\
2
\end{pmatrix}z^{2}\left( \frac{1}{z} \right)^{2}+\begin{pmatrix}
4 \\
3
\end{pmatrix}z\left( \frac{1}{z} \right)^{3}+\begin{pmatrix}
4 \\
4
\end{pmatrix}\left( \frac{1}{z} \right)^{4} \\ \\
= z^{4}-4z^{2}+6-4\left( \frac{1}{z^{2}} \right)+\frac{1}{z^{4}}
\end{gather*}
$$
Grouping in terms of $\left( z^{n}+\frac{1}{z^{n}} \right)$:
$$
\begin{gather*}
= \left( z^{4}+\frac{1}{z^{4}} \right)-4\left( z^{2}+\frac{1}{z^{2}} \right)+6 \\ \\ 
2\cos 4\theta - 8\cos 2\theta + 6
\end{gather*}
$$
Thus:
$$
\begin{gather*}
16 \sin ^{4}\theta = 2\cos 4\theta -8\cos 2\theta + 6 \\ \\
\sin ^{4}\theta = \frac{1}{8}\cos 4\theta - \frac{1}{2}\cos 2\theta + \frac{3}{8} \\ 
QED
\end{gather*}
$$



