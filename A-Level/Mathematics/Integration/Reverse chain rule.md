In general:
$$
\int k\frac{f'(x)}{f(x)} = \ln|f(x)|
$$
E.g $\frac{\cos x}{3+2\sin x}$:
$$
\frac{1}{2}\ln|3+2\sin x|
$$
Do not forget to adjust for the constant in the denominator. 

This rule also works on the case:
$$
\int kf'(x)(f(x))^{n} = (f(x))^{n+1}
$$

Do not forget to adjust for the constant in the denominator.
That is, try $f(x)^{n+1}$  and differentiate to check, and then adjust any constant

E.g $\int 3\cos x\sin ^{2} x$:
$$
\begin{gather*}
y = \sin ^{3}x  \\ 
\frac{dy}{dx} = 3\cos x \sin x \\ \\
\therefore I = \sin ^{3}x+c
\end{gather*}
$$
E.g. $\int x(x^{2}+5)^{3}$:
$$
\begin{gather*}
y = (x^{2}+5)^{4} \\ \\
\frac{dy}{dx} = 8x(x^{2}+5)^{3}  \\ \\
\therefore I = \frac{1}{8}(x^{2}+4)^{4}
\end{gather*}
$$
E.g $\int \frac{\csc ^{2}x}{(2+\cot x)^{3}}$:
$$
\begin{gather*}
= \int \csc ^{2}x(2+\cot x)^{-3} \\ \\
y = (2+\cot x)^{-2} \\ \\
\frac{dy}{dx} = 2\csc ^{2}x(2+\cot x)^{-2} \\ \
\therefore I = \frac{1}{2}(2+\cot x)^{-2}
\end{gather*}
$$
E.g. $\int x^{2}e^{x^{3}}$