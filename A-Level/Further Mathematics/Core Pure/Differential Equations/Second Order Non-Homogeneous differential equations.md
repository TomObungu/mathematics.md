Solving a DE in the form:
$$
ay'' + by' + cy = f(x)
$$
# Particular Integral
There exists a function, $y_{p}(x)$, that satisfies the DE.  We call this the particular integral.

Consider, $y''-5y'+6y=e^{x}$. 

We need something that looks like it will cancel down we will try a trail solution of the same form as $f(x)$.

Let's try 
$$
y_{p} = \lambda e^{x}
$$
$$
\lambda e^{x} - 5\lambda e^{x}+6\lambda e^{x}= e^{x}
$$
The terms cancel out and we are left with:
$$
y_{p} = \frac{1}{2}e^{x}
$$
This is a solution to a second order DE but it has no arbitrary constant. 

$y_{p}$ alone cannot be the general solution.

## Complementary function
The complementary function, $y_{c}$ is the solution to the corresponding homogeneous equation. 

For  our example:
$$
\begin{gather*}
m^{2}-5m+6 = 0  \\ \\ 
(m-3)(m-2) = 0 \\ \\
y_{c} = Ae^{3x} + Be^{2x}
\end{gather*}
$$

## General solution
We know that 
$$
\begin{gather*}
ay_{c}''+by_{c}'+cy_{c} = 0  \\ \\
ay_{p}''+by_{p}'+cy_{p} = 
f(x)\end{gather*}
$$
from the principle of superposition, we know that:
$$
a(y_{c} + y_{p})'' + b(y_{c} + y_{p})' + c(y_{c}+y_{p}) = f(x) + 0
$$
Thus $(y_{c}+y_{p})$ is a solution to the inhomogeneous equation.

Since the complementary function contains the arbitrary constants, this is now a general solution:
$$
y = y_{c} + y_{p}
$$

For the example above:
$$
y = Ae^{3x} + Be^{2x} + \frac{1}{2}e^{x}
$$

# Forms of particular integrals
We need to find a solution of the same form as $f(x)$. 

| $f(x)$                        | $y_{p(x)}$                            |
| ----------------------------- | ------------------------------------- |
| $p$                           | $\lambda$                             |
| $p+qx$                        | $\lambda + \mu x$                     |
| $p+qx+rx^{2}$                 | $\lambda+\mu x+\gamma x^{2}$          |
| $px^{kx}$                     | $\lambda e^{kx}$                      |
| $p\cos\omega x+q\sin\omega x$ | $\lambda \cos\omega+\mu \sin\omega x$ |

Now that some terms are missing in $f(x)$, still try the full form of $y_{p}$.

E.g. $f(x) = p\cos\omega x$, $y_{p}=\lambda \cos\omega x+\mu \sin\omega x$

# Worked Example 1
Find the general solution to:
$$
\begin{gather*}
y''-5y'+6y=3x^{2}  \\ \\
m^{2}-5m+6 = 0 \\ 
(m-3)(m-2) = 0 \\ \\
y_{c} = Ae^{3x} + Be^{2x} \\ \\
y_{p} = \lambda +\mu x + \gamma x^{2} \\ \\
y_{p}' = \mu+2\gamma x \\ \\
y_{p}'' = 2\gamma \\ \\
2\gamma -5(\mu+2\gamma x) + 6(\lambda+\mu x +\gamma x^{2}) = 3x^{2} + 0x + 0 \\ \\
2\gamma -5\mu-10\gamma x + 6\lambda + 6\mu x + 6\gamma x^{2} = 3x^{2} + 0x + 0 \\ \\
(6\gamma)x^{2} + (6\mu-10\gamma)x + (2\gamma-5\mu+6\lambda) = 3x^{2} + 0x + 0 \\ \\
6\gamma = 3 \implies \gamma = \frac{1}{2} \\ \\
6\mu - 5 = 0 \implies \mu=\frac{5}{6} \\ \\
1-\frac{25}{6} + 6\lambda \implies \lambda = \frac{19}{36} \\ \\
y_{p} = \frac{19}{36} + \frac{5}{6}x + \frac{1}{2}x^{2} \\ \\
\therefore y = Ae^{3x} + Be^{2x} + \frac{19}{36} + \frac{5}{6}x + \frac{1}{2}x^{2}
\end{gather*}
$$

# Failure case for exponentials
Consider $y''-5y'+4y=e^{x}$
$$
\begin{gather*}
m^{2}-5m+4 = 0 \\ \\
(m-1)(m-4) = 0 \\ \\
y_{c} = Ae^{x} + Be^{4x} \\ \\
y_{p} = \lambda e^{x}
\end{gather*}
$$

Now let's try the particular solution again, $y_{p} = \lambda e^{x}$

We have a problem, this already a part of $y_{c}$. This satisfies the homogeneous equation so it cannot also be the solution to the inhomogenous. This would imply $e^{x}=0$. 

We can reduction of order, like before, to find that an additional solution. The additional solution is:
$$
\begin{gather*}
y_{p} = \lambda xe^{x} \\ \\
\therefore y_{p}' = \lambda xe^{x} + \lambda e^{x} \\ \\
y_{p}'' = \lambda xe^{x} + 2\lambda e^{x}
\end{gather*}
$$
Therefore substituting back into the equation yeilds:
$$
\begin{gather*}
\lambda(xe^{x}+2e^{x}) - 5(\lambda xe^{x}+\lambda e^{x}) + \lambda xe^{x} = e^{x} \\ \\ 
\lambda x+2\lambda-5\lambda x-5\lambda+4\lambda x=1 \\ \\
-3\lambda = 1 \qquad \lambda = -\frac{1}{3} \\ \\
y_{p} = -\frac{1}{3}xe^{x} 
\end{gather*}
$$
Therefore the solution is now satisfied as:
$$
y = Ae^{x} + Be^{4x}- \frac{1}{3}xe^{x}
$$
