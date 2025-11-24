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
