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
\boxed{z^{n}+\frac{1}{z^{n}} = 2\cos n\theta} \\ \\
\boxed{z^{n}-\frac{1}{z^{n}} = 2i\sin n\theta}
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



