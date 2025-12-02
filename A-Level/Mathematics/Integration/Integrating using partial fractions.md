It is possible to use partial fractions when integrating algebraic functions. Using partial fractions can break down an expression that looks hard to integrate into two or more expressions that are easier to integrate:

E.g $\int \frac{3}{x^{2}-4}$

It is possible to split this up into partial fractions:
$$
\begin{gather*}
\frac{3}{x^{2}-4} = \frac{3}{(x+2)(x-2)} \\ \\
\frac{3}{(x+2)(x-2)} = \frac{A}{x+2} + \frac{B}{x-2} \\ \\
3 = A(x-2) + B(x+2) \\ \\
x=-2: \\ 
3= -4A \\ 
A = -\frac{3}{4} \\ \\
x=2:\\ 
3=4B \\ 
B = \frac{3}{4} \\ \\
\frac{3}{(x+2)(x-2)} = -\frac{\frac{3}{4}}{x+2} + \frac{\frac{3}{4}}{x-2} 
\end{gather*}
$$
It is now possible to integrate these fractions this using reverse chain rule of $\int k\frac{f'(x)}{f(x)} = \ln|f(x)|$:
$$
\int-\frac{\frac{3}{4}}{x+2} + \frac{\frac{3}{4}}{x-2}  = -\frac{3}{4}\ln|x+2
$$
