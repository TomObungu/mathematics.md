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
$$

In general:
$$
\frac{dy}{dx} = \frac{1}{\frac{dx}{dy}}
$$
## The product rule
If $f(x)=g(x)h(x)$ then $f'(x)$ is:
$$
g(x)h'(x) + g'(x)h(x)
$$
## The quotient rule
If $f(x) = \frac{g(x)}{h(x)}$ then $f'(x)$ is:
$$
\frac{h(x)g'(x)-g(x)h(x)}{(h(x))^{2}}
$$
## Standard trigonometric functions
$$
\begin{gather*}
\frac{d}{dx}\tan kx = k\sec ^{2}kx \\ \\
\frac{d}{dx} \csc kx = -k\csc kx\cot kx \\ \\
\frac{d}{dx} \sec kx = -k\sec kx\tan kx \\ \\ 
\frac{d}{dx} \cot kx = -k\csc ^{2}kx
\end{gather*} 
$$
Inverse trigonometric functions:
$$
\begin{gather*}
\frac{d}{dx}\arcsin x = \frac{1}{\sqrt{ 1-x^{2} }} \\ \\
\frac{d}{dx} \arccos x = -\frac{1}{\sqrt{ 1-x^{2} }} \\ \\
\frac{d}{dx} \arctan x = \frac{1}{1+x^{2}}
\end{gather*}

$$