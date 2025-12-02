Trigonometric identities  can be used to integrate expression during inspection of the integral. This allows an expression that cannot be integrated to be replaced by an identical expression can that can be integrated.

Some useful cases to remember for integrating $\sin ^{2}x$ and $\cos ^{2}x$:
$$
\begin{gather*}
\text{From } \cos 2x = 1-2\sin ^{2}x \\ \\
\boxed{\sin ^{2} x =\frac{-\cos2x +1}{2}} \\ \\
\text{From } \cos 2x = 2\cos ^{2}x-1 \\ \\
\boxed{\cos ^{2}x = \frac{\cos 2x+1}{2}}
\end{gather*}
$$
Thus integrating $\sin ^{2}x$ gives:
$$
\int \sin ^{2}x = \int -\frac{1}{2}\cos 2x+\frac{1}{2} = \boxed{-\frac{1}{4}\sin(2x)+\frac{1}{2}x}
$$
And integrating $\cos ^{2}x$ gives:
$$
\int \cos ^{2}x = \int \frac{1}{2}\cos 2x +\frac{1}{2} = \boxed{\frac{1}{4}\sin 2x +\frac{1}{2}x}
$$


---

Integrals of reciprocal trigonometric functions:
$$
\begin{gather*}
\int \tan x = \ln|\sec x| \\ \\
\int \sec x = \ln|\sec x + \tan x| \\ \\
\int \cot x = \ln|\sin x| \\ \\
\int \csc x = \ln|\csc x -\cot x|
\end{gather*}
$$
Integrals of $\tan ^{2}x$ and $\cot ^{2}x$:
$$
\begin{gather*}
\int \tan ^{2}x = \tan x -x \\ \\
\int \cot ^{2}x = -\cot x -x
\end{gather*}
$$
# Integrating $\sin ^{3} x$ and $\cos ^{3}x$
## $\sin ^{3}x$
To integration $\sin ^{3}x$, first rewrite it as $\sin x(\sin ^{2}x)$ ,then as $\sin x(1-\cos ^{2})$ , then as multiply them out and use the chain rule:
$$
\begin{gather*}
\int \sin ^{3}x dx\\ \\
= \int \sin x(\sin ^{2}x)dx=\int \sin x(1-\cos ^{2}x) dx\\ \\
= \int\sin x -\sin x\cos ^{2}xdx \\ \\
= \int \sin xdx - \int \sin x\cos ^{2}xdx
\end{gather*}
$$
Using the the standard result and the chain rule as it is in form $\int kf'(x)(f(x))^{n}$ thus we can try $ = $(f(x))^{n+1}$ and adjust for constants
$$
\begin{gather*}
= \int \sin x dx = -\cos x+c \\ \\
\int \sin x \cos ^{2}x \\ \\
y = \cos ^{3}x \\ \\
\frac{dy}{dx} = -3\sin x\cos ^{2}x \\ \\
\therefore \int \sin x\cos ^{3}x = -\frac{1}{3}\cos ^{3}x + c
\end{gather*}
$$
Thus, the final result is:
$$
\boxed{\cos x+\frac{1}{3}\cos ^{3}x+c}
$$
## $\cos ^{3}x$
The process is the same except writing out $\cos(1-\sin ^{2}x)$:
$$
\begin{gather*}
\int \cos ^{3}x \\ \\
= \int \cos x(1-\sin ^{2}x)dx = \int \cos x-\sin ^{2}x\cos xdx \\ \\ 
= \int \cos x -\int \sin ^{2}x\cos
\end{gather*}
$$
Using the standard result and the revers chain rule:
$$
\begin{gather*}
\sin x-\int \sin ^{2}x\cos x \\ \\
y = \sin ^{3}x \\ \\
\frac{dy}{dx} = 3\cos x\sin ^{2}x \\ \\ 
\therefore \int \sin ^{2}x\cos x = \frac{1}{3}\sin ^{3}x
\end{gather*}
$$
Therefore the final result is:
$$
\boxed{\sin x-\frac{1}{3}\sin ^{3}x+c}
$$

