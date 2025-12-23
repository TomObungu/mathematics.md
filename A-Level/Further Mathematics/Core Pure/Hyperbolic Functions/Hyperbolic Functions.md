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
\therefore \frac{e^{-x}-e^{x}}{2} = i\sin(ix) \\ \\
\therefore \frac{e^{x}-e^{-x}}{2} = -i\sin(ix)
\end{gather*}
$$
Thus:
$$
\boxed{\sinh(x) -i\sin(ix) = \frac{e^{x}-e^{-x}}{2}}
$$

## Graphs of hyperbolic sine and cosine

## Graph of $\sinh(x)$
You can sketch the graphs of hyberbolic functions by considering the graphs of $y=e^{x}$ and $y=-e^{-x}$. 
The graph of $\sinh x$ is the 'average' of the graphs of $y=e^{x}$ and $y=e^{-x}$:
![[Pasted image 20251223171927.png]]
![[Pasted image 20251223172704.png]]

### Approximations:
As $x$ is very large and positive, $\sinh x \approx \frac{1}{2}e^{x}$
As $x$ is very large and negative, $\sinh x = - \frac{1}{2}e^{-x}$
As $\sinh x$ is an odd function, $\sinh(-a)=-\sinh(a)$
![[Pasted image 20251223172002.png]]

## Graph of $\cosh(x)$
As the $\cosh(x) = \frac{e^{x}+e^{-x}}{2}$, then graph of $\cosh(x)$ is just the 'average' of $y=e^{x}$ and $y=e^{-x}$:
![[Pasted image 20251223172422.png]]
![[Pasted image 20251223172755.png]]

### Approximations
As $x$ is very large and positive, $\cosh x \approx \frac{1}{2}e^{-x}$
As $x$ is very large and negative, $\cosh x \approx \frac{1}{2}e^{-x}$
![[Pasted image 20251223181508.png]]
# Hyperbolic tangent 
By using the definitions of $\cosh(x)$ and $\sinh(x)$, it is possible to write $\tanh(x)$ in exponential form:
$$
\begin{gather*}
\tanh(x) = \frac{\sinh x}{\cosh x} = \frac{e^{x}-e^{-x}}{2} \left( \frac{2}{e^{x}+e^{-x}} \right)  \\ \\ 
= \boxed{ \frac{e^{x}-e^{-x}}{e^{x}+e^{-x}} }
\end{gather*}
$$

## Graph of hyperbolic tangent
You can sketch the graphs of $\cosh(x)$ and $\sinh(x)$ and see that for very large values of $x$, $e^{-x}\to {0}$ thus $\tanh(x)\to {1}$:
![[Pasted image 20251223181003.png]]

### Approximations
As $x$ is very large and is positive: $\tanh x \approx {1}$
As $x$ is very large and is negative: $\tanh x\approx -1$
As $\tanh x$ is an odd function, $\tanh(-a)=-\tan h(a)$
# Hyperbolic reciprocal trigonometric functions

$$
sech(x)
$$