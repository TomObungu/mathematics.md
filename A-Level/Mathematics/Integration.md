## Standard functions
Integrals of standard functions:
$$
\begin{gather*}
\int x^{n} = \frac{x^{n+1}}{n+1} \\ \\
\int e^{x} = e^{x} + c \\ \\
\int \frac{1}{x} = \ln|x| + c \\ \\
\int \cos x = \sin x \\ \\
\int \sin x = -\cos x \\ \\
\int \sec ^{2} x = \tan x \\ \\
\int \csc \cot x = -\csc x \\ \\
\int \csc ^{2} x = -\cot x \\ \\
\int \sec x \tan x = \sec x 
\end{gather*}
$$
More standard functions:
$$
\begin{gather*}
\int \tan x = \ln|\sec x| \\ \\
\int \sec x = \ln|\sec x + \tan x| \\ \\
\int \cot x = \ln|\sin x| \\ \\
\int \csc x = \ln|\csc x -\cot x|
\end{gather*}
$$
## Integrating $f(ax+b)$
In general:
$$
\int f(ax+b) = \frac{1}{a}F(ax+b)
$$
That is $F(x)$ is the integral result of the function
E.g $\int \cos(2x+3)$:
$$
\begin{gather*}
f(x) = \cos(g(x))  \qquad F(x) = \sin (g(x))
\\ \\ \int \cos(2x+3) = \frac{1}{2}\sin(2x+3)
\end{gather*}

$$
E.g. $\frac{1}{3x+2}$:
$$
\begin{gather*}
f(x) = \frac{1}{g(x)} \qquad \ln|g(x)| \\ \\
\int \frac{1}{3x+2} = \frac{1}{3}\ln(3x+2)
\end{gather*}
$$
E.g $(2x+3)^{4}$:
$$
\begin{gather*}
f(x) = (g(x)^{4} \qquad F(x) = \frac{1}{5}(g(x))^{5} \\ \\
\int (2x+3)^{4} = \frac{1}{2}\left( \frac{1}{10} \right)(2x+3)^{5} = \frac{1}{10}(2x+3)^{5}
\end{gather*}
$$
# Reverse chain rule
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
E.g $\int \frac{\csc ^{2}x}{(2+\cot x)^{3}}$
$$
\begin{gather*}
= \int \csc ^{2}x(2+\cot x)^{-3} \\ \\
y = (2+\cot x)^{-2} \\ \\
\frac{dy}{dx} = 2\csc ^{2}x(2+\cot x)^{-2} \\ \
\therefore I = \frac{1}{2}(2+\cot x)^{-2}
\end{gather*}
$$
# Integrating by susbtitution
E.g. $\int x\sqrt{ 2x+5 }$
$$
\begin{gather*}
u = 2x+5 \\ \\
\frac{du}{dx} = 2 \\ \\
\frac{du}{2} = dx \\ \\
x = \frac{u-5}{2} \\ \\
\int \frac{u-5}{5} u^{\frac{1}{2}} \frac{du}{2} \\ \\
= \int \frac{1}{4}(u-5)u^{\frac{1}{2}}du \\ \\
= \int \frac{1}{4}\left( u^{\frac{3}{2}}-5^{\frac{1}{2}} \right) \\ \
= \frac{u^{\frac{5}{2}}}{10}-\frac{5u^{\frac{3}{2}}}{6} \\ \\
= \frac{(2x+5)^{\frac{5}{2}}}{10}-\frac{5^{*}(2x+5)^{\frac{3}{2}}}{6}
\end{gather*}
$$
# Integration by parts
In general:
$$
\int u \frac{dv}{dx} = uv - \int v \frac{du}{dx}
$$

