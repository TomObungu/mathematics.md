It can be shown from A level maths that:
$$
\begin{gather*}
\frac{d}{dx} \arcsin x = \frac{1}{\sqrt{ 1-x^{2} }} \\ \\
\frac{d}{dx}\arccos x = -\frac{1}{\sqrt{ 1-x^{2} }} \\ \\
\frac{d}{dx}\arctan x = \frac{1}{1+x^{2}}
\end{gather*}
$$
Thus in general when integrating:
$$
\begin{gather*}
\int \frac{1}{a^{2}+x^{2}} = \frac{1}{a}\arctan\left( \frac{x}{a} \right) + c \\ \\
\int \frac{1}{\sqrt{ a^{2}-x^{2} }} = \arcsin\left( \frac{x}{a} \right) + c
\end{gather*}
$$

# Worked Example 1
$$
\begin{gather*}
\int \frac{4}{5+x^{2}} dx \\ \\
= 4\int \frac{1}{5+x^{2}} = 4\left( \frac{1}{\sqrt{ 5 }}\arctan\left( \frac{1}{\sqrt{ 5 }} \right) \right) + c
\end{gather*}
$$
# Worked Example 2
For cases when the coefficient of $x$ is not 1. It is possible to factor out the coefficient and write it in the form $k(a^{2}+x^{2})$:

E.g. Find $\int \frac{1}{25+9x^{2}}$
$$
\begin{gather*}
\int \frac{1}{25+9x^{2}}dx = \int \frac{1}{9\left( \frac{25}{9}+x^{2} \right)} \\ \\
= \frac{1}{9}\int \frac{1}{\frac{25}{9}+x^{2}} = \frac{1}{9}\int \frac{1}{\left( \frac{5}{3} \right)^{2}+(x)^{2}} \\ \\
= \frac{1}{9}\left( \frac{3}{5} \right)\arctan\left( \frac{3x}{5} \right) + c \\ \\
= \frac{1}{15}\arctan\left( \frac{3x}{5} \right)+c
\end{gather*} 
$$

## Worked Example 3
For cases dealing with the integral of $\frac{1}{\sqrt{ a-kx^{2} }}$, factor out the $k$ within the square root and then consider the square roof of $k$ as a factor on the outside:

E.g. Find $\int\frac{1}{\sqrt{ 3-4x^{2} }}$
$$
\begin{gather*}
\int \frac{1}{\sqrt{ 3-4x^{2} }} = \int \frac{1}{\sqrt{ 4\left( \frac{3}{4}-x^{2} \right) }} \\ \\
= \frac{1}{2}\int \frac{1}{\sqrt{ \left( \frac{\sqrt{ 3 }}{2} \right)^{2}-(x)^{2} }} \\ \\
= \frac{1}{2}\arcsin\left( \frac{2x}{\sqrt{ 3 }} \right) + c
\end{gather*}
$$
# Worked Example 4
In cases when you have linear terms on the numerator. The integral can be split into a fraction wich can be integrated using the reverse chan rule:

E.g. Find $\int \frac{x+4}{\sqrt{ 1-4x^{2} }}$:

$$
\begin{gather*}
\int \frac{x+4}{\sqrt{ 1-4x^{2} } } = \int \frac{x}{\sqrt{ 1-4x^{2} }} + \int \frac{4}{\sqrt{ 1-4x^{2} }} \\ \\
\int x(1-4x^{2})^{-\frac{1}{2}} +4\int \frac{1}{\sqrt{ 4\left( \frac{1}{4}-x^{2} \right) }} \\ \\
= -\frac{1}{4}(1-4x^{2})^{\frac{1}{2}}+2\arcsin (2x)+c
\end{gather*}
$$


