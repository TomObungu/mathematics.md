Finding mean value of a function on a given interval $[a,b]$ will involve taking an infinite number of values, so you represent their sum be integrating the function between a and b and you represent the number of values by the width of the interval $b-a$. 

Thus the mean value of the function $f(x)$ over the interval $[a,b]$ is given by:
$$
\frac{1}{b-a} \int_{a}^{b}f(x)dx
$$
You can think of the mean value geometrically by considering the area A, bounded by the curve $y=f(x)$, the axis and lines $x=a$ and $x=b$. If you were to draw a rectangle with its base on the interval $[a,b]$ and height $\bar{f}$, then the area of the rectangle would be equal to $A$. ![[Pasted image 20251222093149.png]]

The area of this rectangle is $(b-a)\bar{f}$. Setting this equal to the area under the curve gives:
$$
(b-a)\bar{f} = \int_{a}^{b}f(x)
$$
Thus:
$$
\bar{f}=\frac{1}{b-a}\int_{a}^{b}f(x)
$$

# Worked Example 1
E.g find the mean value of $f(x)=\frac{4}{\sqrt{ 2+3x }}$ over the interval of $[2,6]$.
$$
\begin{gather*}
\int \frac{4}{\sqrt{ 2+3x }}dx  \\ \\
= \int 4(2+3x)^{-\frac{1}{2}} = \frac{8}{3}(2+3x)^{\frac{1}{2}}
\end{gather*}
$$
Thus the mean value is:
$$
\begin{gather*}
\frac{1}{6-2}\int_{2}^{6} \frac{4}{\sqrt{ 2+3x }} \\ \\
= \frac{1}{4}\left[ \frac{8}{3}(2+3x)^{\frac{1}{2}} \right]^{6}_{2} = \frac{1}{4}\left( \frac{16}{3}(\sqrt{ 5 }-\sqrt{ 2 }) \right) = \frac{4}{3}(\sqrt{ 5 }-\sqrt{ 2 })
\end{gather*}
$$

# Geometric considerations
If the function $f(x)$ has a mean value $\bar{f}$ over the interval $[a,b]$ and k is a real constant, then:

- $f(x)+k$ has mean value $\bar{f}+k$ over the interval $[a,b]$
- $kf(x)$ has mean value  $k\bar{f}$ over the interval $[a,b]$
- $-f(x)$ has mean value $-\bar{f}$ over the interval $[a,b]$

