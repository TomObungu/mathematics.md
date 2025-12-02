In general:
$$
\int u \frac{dv}{dx} = uv - \int v \frac{du}{dx}
$$
It is good to follow this order setting your value of $u$ by following this hierarchy:
This means the higher the function is in the list, the more priority it takes in setting the value as your $u$ variable. In general try and avoid setting your value to trigonometric and exponential functions as they are infinitely differentiable

L - Logarithms e.g $\ln x$,$\log_{2}x$
I - Inverse trigonometric functions e.g $\arcsin x$,$\arctan x$
A - Algebra e.g. $x^{2}$, $2x$, $x^{5}$
T = Trigonometric functions e.g $\sin x$, $\cos x$
E - Exponential functions e.g $e^{x}$, $3^{x}$

E.g. $\int x^{2}e^{x}$
$$
\begin{gather*}
u=x^{2} \qquad \frac{dv}{dx}=e^{x} \\ \\
\frac{du}{dx} = 2x \qquad v=e^{x} \\ \\
\int x^{2}e^{x} = x^{2}e^{x} - \int 2xe^{x} \\ \\ \\ \\ 
u = 2x \qquad \frac{dv}{dx} = e^{x} \\ \\
\frac{du}{dx} = 2 \qquad v=e^{x} \\ \\
\int x^{2}e^{x} = x^{2}e^{x} - 2xe^{x} +\int 2e^{x} \\ \\ \\ \\ 
\therefore \int x^{2}e^{x} = x^{2}e^{x} - 2xe^{x} +2e^{x} \\ \\
= (x^{2}-2x+2)e^{x}
\end{gather*}
$$

# Exponential and trigonometric functions multiplied together
In cases when you see something in the form $\int e^{ax}\sin kx$ or $\int e^{ax}\cos kx$. Despite LIATE preferring to set $u$ to the trigonometric function, it is actually better to  set $e^{x}$ as the algebra will more cleaner. However this does not mean setting $u$ to the trigonometric function will not yield the same result. 

E.g. $\int e^{2x}\sin 3x$
$$
\begin{gather*}
u = e^{2x} \qquad \frac{dv}{dx} = \sin 3x \\ \\
\frac{du}{dx} = 2e^{2x} \qquad v = -\frac{1}{3}\cos 3x \\ \\ 
\int e^{2x}\sin 3x =-\frac{1}{3}e^{2x}\cos 3x + \frac{2}{3}\int e^{2x}\cos 3x \\ \\ \\ \\ 
u = e^{2x} \qquad \frac{dv}{dx} = \cos 3x \\ \\
\frac{du}{dx} = 2e^{2x} \qquad v = \frac{1}{3}\sin 3x \\ \\
\int e^{2x}\sin 3x =-\frac{1}{3}e^{2x}\cos 3x + \frac{2}{9}e^{x}\sin 3x -\frac{4}{9}\int e^{2x}\sin 3x 
\end{gather*}
$$
Now here is the crux of the problem, you need to realise that the same integral is on both sides of the equation. Thus you can rearrange them into on side of the problem subtracting them. After this you can simply divide out to get the full form of the integral:
$$
\left( \frac{13}{9} \right)\int e^{2x}\sin 3x =-\frac{1}{3}e^{2x}\cos 3x + \frac{2}{9}e^{x}\sin 3x 
$$
Therefore dividing out gives:
$$
\begin{gather*}
\int e^{2x}\sin 3x =-\frac{3}{13}e^{2x}\cos 3x + \frac{2}{13}e^{x}\sin 3x  \\ \\
\therefore \int e^{2x}\sin 3x = \boxed{\frac{1}{13}(2\sin 3x -3e^{2x}\cos 3x)+c} 
\end{gather*}
$$
