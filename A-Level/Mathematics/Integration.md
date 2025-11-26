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

$$