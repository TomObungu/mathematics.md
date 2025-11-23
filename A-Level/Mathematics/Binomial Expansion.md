From AS mathematics. If n is a natural number you can find the binomial expansion for $(a+bx)^{n}$ using the formula:
$$
\begin{gather*}
(a+bx)^{n} = \\ \\
a^{n} + \begin{pmatrix}
n \\
1
\end{pmatrix}a^{n-1}bx + \begin{pmatrix}
n \\
2
\end{pmatrix}a^{n-2}b^{2}x^{2} +\begin{pmatrix}
n \\
3
\end{pmatrix}a^{n-3}b^{3}x^{3} \dots \begin{pmatrix}
n \\
r
\end{pmatrix}a^{n-r}+b^{r}x^{r} + b^{n}
\end{gather*}

$$

From A level mathematics. If n is not a natural number i.e a fraction or negative you can find the infinite series expansion of for $(a+bx)^{n}$ using the formula:

This is possible because the Numworks calculator can actually use the nCr formula for non-natural values of x.


$$
\begin{gather*} 
(1+bx) = b^{n} + n(bx) + \frac{n(n-1)}{2!}(bx)^{2} +\frac{n(n-1)(n-2)}{3!}(bx)^{3} \dots \begin{pmatrix}
n \\
r
\end{pmatrix}(bx)^{r}\\ \\ \\
(a+bx)^{n}=\left( a\left( 1+\frac{b}{a}x \right) = a^{n}\left( 1+\frac{b}{a}x \right)^{n}\right) \\ \\ \\ 
= a^{n}\left( 1+\begin{pmatrix}
n \\
1
\end{pmatrix}\left( \frac{b}{a}x \right) +\begin{pmatrix}
n \\
2
\end{pmatrix}\left( \frac{b}{a}x \right)^{2} + \begin{pmatrix}
n \\
3
\end{pmatrix} \right)\left( \frac{b}{a}x \right)^{3} \dots \begin{pmatrix}
n \\
r
\end{pmatrix}\left( \frac{b}{a}x \right)^{r} + (\frac{b}{a} x)^{n})
\end{gather*}
$$

