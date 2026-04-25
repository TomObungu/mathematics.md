![[Pasted image 20251124163415.png]]
(a)
For this question you need to identify the binomial expansion for $(1+x)^{n}$, half angle formulae and Euler's identity.
Firstly sum $C+iS$ to get $(1+e^{\theta i})^{n}$ and re-write in modulus argument form
$$
\begin{gather*}
C+iS = 1 + \begin{pmatrix}
n \\
1 
\end{pmatrix}(\cos\theta + i\sin\theta) + \begin{pmatrix}
n \\
2
\end{pmatrix}(\cos2\theta + i\sin2\theta) + \dots + \begin{pmatrix}
n \\
n
\end{pmatrix}(\cos n\theta + i\sin n\theta) \\ \\
= (1+e^{\theta i})^{n} \\ \\
= (1 +\cos\theta +i\sin\theta)^{n}
\end{gather*}
$$
Use the half angle formulae and Pythagorean identity  to get an expression for $1+\cos\theta$:
$$
\begin{gather*}
1+\cos\theta \\ \\ 
= \left( \sin^{2}\left( \frac{\theta}{2} \right) + \cos ^{2}\left( \frac{\theta}{2} \right) + \cos ^{2}\left( \frac{\theta}{2} \right) - \sin ^{2}\left( \frac{\theta}{2} \right)\right) \\ \\
= 2\cos ^{2}\left( \frac{\theta}{2} \right)
\end{gather*}
$$
Sub that into the modulus argument form equation. Write $\sin\theta$ in half angle form and then factor out.
$$
\begin{gather*}
(1 +\cos\theta +i\sin\theta)^{n} \\ \\
= \left(2\cos ^{2}\left(\frac{\theta}{2}\right) + i\left( 2\sin\left( \frac{\theta}{2} \right)\cos\left( \frac{\theta}{2} \right) \right)\right)^{n} \\ \\
= \left[2\cos\left(\frac{\theta}{2}\right)\left(\cos\left(\frac{\theta}{2}\right) + i\sin\left( \frac{\theta}{2} \right)\right)\right]^{n}\\ \\
\end{gather*}
$$
Use De Moivre's theorem to re-write the part in modulus argument form:
$$
2\cos ^{n}\left( \frac{\theta}{2} \right)\left( \cos\left( \frac{n\theta}{2} \right) + i\sin\left( \frac{n\theta}{2} \right) \right)
$$
Take the real part to find $C$:
$$
\begin{gather*}
C = \mathrm{Re}(C+iS) = \left[2\cos\left( \frac{\theta}{2} \right)\left( \cos\left( \frac{n\theta}{2} \right) \right)\right]^{n} \\ \\ 
=  2\cos^{n}\left( \frac{\theta}{2} \right)\cos\left( \frac{n\theta}{2} \right) \\ \\
QED
\end{gather*}
$$
(b) For part b, just take the imageinary part to get $S$ and then do $\frac{C}{S}$. You get equation for $\tan \frac{n\theta}{2}$@
$$
\begin{gather*}
S = \mathrm{Im}(C+iS) = 2\cos ^{n}\left( \frac{\theta}{2} \right)\sin\left( \frac{n\theta}{2} \right) \\ \\ \\
\therefore \frac{S}{C} = \frac{2\cos ^{n}\left( \frac{\theta}{2} \right)\sin\left(  \frac{n\theta}{2} \right)}{2\cos ^{n}\left( \frac{\theta}{2} \right)\sin\left(  \frac{n\theta}{2} \right)} \\ \\
= \tan\left( \frac{n\theta}{2} \right) \\ \\
QED
\end{gather*}
$$
