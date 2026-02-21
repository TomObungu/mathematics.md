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
Therefore we can find the hyerbolic equivalent by considering Osborne's rule:
$$
\therefore \cosh 2x = 1 + \sinh ^{2} x
$$
Rearranging to find 