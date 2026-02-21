It is possible to use hyperbolic functions to simplify integrals that otherwise would be more complex using A Level techniques alone. The general structure of integration with hyperbolics is similar to A level integration using trigonometric techniques and substitution. 

# Standard results
From covering hyperbolic differentiation it is possible to deduce these standard results:

$$
\begin{gather*}
\int \sinh x dx = \cosh x + c \\ \\
\int \cosh x dx = \sinh x + c \\ \\
\int \frac{1}{\sqrt{ 1 + x^{2} }} = arsinhx + c \\ \\
\int \frac{1}{\sqrt{  x^{2} - 1}} = ar\cosh x + c, \ x > 1 \\ \\
\end{gather*}
$$

# Example 1
Find $\int \cosh(4x -1)dx$
Rules like the reverse chain rule still apply when dealing with hyperbolic integrals:
$$
\int \cosh(4x-1) = \frac{1}{4}\sinh(4x-1) + c
$$
# Example 2
Find $\int \frac{2+5x}{\sqrt{ x^{2}+1 }}$
For questions like this, it is possible to split the numerator and deal with the function as two separate functions:
$$
\begin{gather*}
\int \frac{2+5x}{\sqrt{ x^{2}+1 }} = \int \frac{2}{\sqrt{ x^{2}+1 }} +\int \frac{5x}{\sqrt{ x^{2}+1 }} \\ \\
= 2ar\sinh +5(x^{2}+1)^{\frac{1}{2}}
\end{gather*}
$$
# Example 3
Find $\int \cosh^5 2x \sin 2xdx$
For questions like this, the rule of $\int(f(x)^{n}f^{'}(x))dx = \frac{f(x)^{n+1}}{n+1} + c$ still applies:
$$
\begin{gather*}
\int \cosh ^{5}2x\sinh 2x = \frac{1}{2}\int(\cosh 2x)^{5}(2\sinh 2)dx = \frac{1}{12}\cosh ^{6}2x + c
\end{gather*}
$$

# Deriving $\int \tanh x$
Rewriting $\tanh x$ as $\sinh \frac{x}{\cosh x}$ gives:
$$
\int \frac{\sinh x}{\cosh x } = \ln \cosh x+ c
$$
By using $\int \frac{f'(x)}{f(x)} = \ln|f(x)| + c$

# Deriving $\int \sinh ^{2}x$
To integrate $\sinh ^{2}x$, you use the same technique of using the the double angle formulae  however you must also take into consideration of Osborne's rule when dealing with $\sinh x$.

We know that:
$$
\cos 2x = 1 - 2\sin ^{2}x
$$
Therefore we can find the hyperbolic equivalent by considering Osborne's rule:
$$
\therefore \cosh 2x = 1 + 2\sinh ^{2} x
$$
Rearranging to find $\sinh ^{2}x$:
$$
\frac{1}{2}\cosh 2x - \frac{1}{2} = \sinh ^{2}x
$$
In which we can integrate:
$$
\int \sinh ^{2} x = \int \cosh 2x -1 = \int \frac{1}{4}\sinh 2x - \frac{1}{2}x + c
$$


# Deriving $\int \sinh ^{3} x$
When integrating $\sinh ^{3}x$, you can take the same A level approach of splitting it into $(\sinh ^{2}x)(\sinh x)$. Afterwards, re-write the $\sinh ^{2} x$ as $\cosh ^{2}x - 1$:
$$
\begin{gather*}
\int \sinh ^{3} x = \int (\sinh ^{2}x)(\sinh x) = (\cosh ^{2}x-1)(\sinh x )  \\ \\
= \int \cosh ^{2}x\sinh x - \sinh x \\ \\
= \frac{1}{3}\cosh ^{3}x - \cosh x + c
\end{gather*}
$$


# Finding $\int e^{2x}\sinh(x)$
For integrals involving $e^{x}$ and hyperbolic functions, it is possible to directly write the hyperbolic functions in terms of $e^{x}$, multiply them through then integrate:
$$
\begin{gather*}
\int e^{2x}\sinh(x) = \int e^{2x}\left( \frac{e^x-e^{-x}}{2} \right) \\ \\
= \int \frac{e^{3x}}{2} - \int \frac{e^{x}}{2} \\ \\
= \frac{1}{6}e^{3x} - \frac{1}{2}e^{x} + c 
\end{gather*}
$$

