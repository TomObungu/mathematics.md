It is possible to prove using the small angle approximations:
$$
\begin{gather*}
\sin x \approx x  \\ \\
\cos x \approx 1-\frac{x^{2}}{2}
\end{gather*}
$$
And first principles $\lim_{ h\to 0}  \frac{f(x+h)-f(x)}{h}$ that:
$$
\begin{gather*}
\frac{d}{dx} \sin kx = k\cos kx \\ \\
\frac{d}{dx} \cos kx = -k\sin kx
\end{gather*}

$$
For $e^{x}$
$$
\frac{d}{dx} e^{kx} = ke^{kx}
$$
For $\ln x$:
$$
\frac{d}{dx}\ln x = \frac{1}{x}
$$
## The chain rule
The chain rule allows you differentiate a function of a function. In general:
$$
\frac{d}{dx}(f(x))^{n} = n(f(x))^{n-1}f'(x)
$$
For nested functions:
$$
\frac{d}{dx}(f(g(x))) = f'(g(x))g'(x)
$$
E.g Find $\frac{d}{dx} \sqrt{ 5x^{2}+1 }$:
$$
\begin{gather*}
f(x) = 5x^{2}+1 \\ \\
\sqrt{ 5x^{2}+1 } = (f(x))^{\frac{1}{2}} \\ \\
\therefore \frac{d}{dx} = \frac{1}{2}(f(x))^{-\frac{1}{2}}f'(x) \\ \\
= \frac{1}{2}(5x^{2}+1)^{-\frac{1}{2}}(10x) \\ \\ 
= \boxed{5x(5x^{2}+1)^{-\frac{1}{2}}}
\end{gather*}
$$#