Consider the geometric series 
$$
1 + e^{i\theta}+e^{2i\theta}\dots+e^{n-1}\theta
$$
For complex numbers, we call:
- First term : $w$
- Common ratio : $z$

In this case:
$$
w = 1 \qquad z = e^{i\theta}
$$
This formula for the sum of a geometric series is:
$$
\boxed{S_{n} = \frac{w(z^{n}-1)}{z-1}}
$$
Thus for this case:
$$
S_{n} = \frac{e^{in\theta}-1}{e^{i\theta}-1}
$$

# Worked Example 1
$$
z = \cos \frac{\pi}{n} + i\sin \frac{\pi}{n}
$$
Show that $1+z+z^{2}+\dots+z^{n-1}=1+i\cot \frac{\pi}{2n}$.
Writing $z$ in exponential form:
$$
z = e^{\frac{\pi}{n}i}
$$
Expressing the geometric series:
$$
1+z^{2}+z^{3}+\dots = 1+e^{\frac{\pi}{n}i}+e^{\frac{2\pi}{n}i}+e^{\frac{3\pi}{n}i}\dots
$$
The sum of the series is:
$$
\begin{gather*}
S_{n}= \frac{\left( e^{ \frac{\pi}{n} } \right)^{n}-1}{e^{\frac{\pi}{n}i}-1} \\ \\
= \frac{e^{i\pi}-1}{e^{\frac{\pi}{n}i}-1} \\ \\
= -\frac{2}{e^{\frac{\pi}{n}i}-1}
\end{gather*}
$$
Now here is the tricky (tricky as in you literally need to apply a trick)... We are aiming for $\sin\left( \frac{\pi}{2n} \right)$ on the denominator.  Currently we have $e^{\frac{\pi}{n}}$ which will yield $\dots\sin \frac{\pi}{n}$.  So we need to turn $e^{\frac{\pi}{n}}$ into $e^{\frac{\pi}{2n}}$...

This is possible by doing the trick of of multiplying by $\frac{e^{-\frac{\pi}{2n}i}}{e^{-\frac{\pi}{2n}i}}$. This is because this will have the same affect of multiplying by $1$ but due to index laws $e^{\frac{\pi}{n}}e^{-\frac{\pi}{2n}}$ = $e^{\frac{\pi}{n}-\frac{\pi}{2n}}$ which equals $e^{\frac{\pi}{2n}}$ which is what we want.:

$$
\begin{gather*}
= -\frac{2}{e^{\frac{\pi}{n}i}-1}\left(  \frac{e^{-\frac{\pi}{2n}i}}{e^{-\frac{\pi}{2n}i}}\right) \\ \\
= \frac{-2e^{\frac{-\pi}{2n}i}}{e^{\frac{\pi}{n}i}-e^{-\frac{\pi}{2n}i}}
\end{gather*}
$$
Now if we turn this into modulus argument form:
$$
= \frac{-\cancel{ 2 }\left( \cos \frac{\pi}{2n}-i\sin \frac{\pi}{2n} \right)}{\cancel{ 2 }i\sin \frac{\pi}{2n}}
$$
Another trick to remember is dividing by $i$ is the same as multiplying by $-i$:
$$
\begin{gather*}
= \frac{i\cos \frac{\pi}{2n}+\sin \frac{\pi}{2n}}{\sin \frac{\pi}{2n}}
\end{gather*}
$$
Splitting this up into real and imaginary form ($a+bi$):
$$
\begin{gather*}
= \frac{\sin \frac{\pi}{2n}}{\sin \frac{\pi}{2n}}+\frac{i\cos \frac{\pi}{2n}}{\sin \frac{\pi}{2n}} \\ \\
= 1 + i\cot \frac{\pi}{2n} \\ 
QED
\end{gather*}
$$


