From Euler's identity, we know that:
$$
e^{i\theta}=\cos \theta + i\sin \theta
$$
and:
$$
e^{-i\theta} = \cos \theta - i\sin \theta
$$
Thus it possible to use these equations to form identities for $\cos \theta$:
$$
\begin{gather*}
e^{i\theta}+e^{-i\theta} = 2\cos \theta \\ \\
\frac{e^{i\theta}+e^{-i\theta}}{2} = \cos \theta \\ \\
\end{gather*}
$$
 and $i\sin \theta$:
 $$
 \begin{gather*}
e^{i\theta}-e^{-i\theta} = 2i\sin \theta \\ \\
\frac{e^{i\theta}-e^{-i\theta}}{2} = i\sin \theta
\end{gather*}
$$

Now let's consider the case for when $\theta=ix$:
$$
\begin{gather*}
\therefore \frac{e^{i \cdot ix}+e^{- i \cdot ix}}{2} = \cos ix \\ \\ 
\therefore \frac{e^{x}+e^{-x}}{2} = \cos ix
\end{gather*}
$$
Notice that, for input $ix$, the input is real, thus we can define $\cos(ix)$ as function called hyperbolic cosine or $\cosh(x)$:
$$
\boxed{\cosh(x) = \cos(ix) = \frac{e^{x}+e^{-x}}{2}} 
$$
The same for sine; Consider when $\theta=ix$:
$$
\begin{gather*}
\frac{e^{i \cdot ix}-e^{-i \cdot ix}}{2} = i\sin(ix) \\ \\
\frac{e^{x}-e^{-x}}{2} = i\sin(ix)
\end{gather*}
$$
