There are special cases where $\int \frac{1}{a^{2}+x^{2}} = \frac{1}{a}\arctan\left( \frac{x}{a} \right) + c$ can be used to the integrated a quadratic that can't be factorised but can be written in completing the square format:

# Example 1
$$
\begin{gather*}
\int \frac{1}{x^{2}+2x+16}
\end{gather*}
$$
Completing the square on $\frac{1}{x^{2}+2x+16}$ gives:
$$
 \frac{1}{(x+1)^{2}-1+16} = \frac{1}{(x+1)^{2}+15}
$$
Thus the integral can be written as:
$$
\begin{gather*}
\int \frac{1}{(x+1)^{2}+15}
\end{gather*}
$$
Notice that the form is similar to $\int \frac{1}{a^{2}+x^{2}}$. Let's write the $15$ in the form $a^{2}$:
$$
\begin{gather*}
\int \frac{1}{(x+1)^{2}+(\sqrt{ 15 })^{2}}
\end{gather*}
$$
Now it is possible to write down the answer using the formula: $\int \frac{1}{a^{2}+x^{2}} = \frac{1}{a}\arctan\left( \frac{x}{a} \right) + c$ where we take $a=\sqrt{ 15 }$ and replace $x$ with $x+1$:
$$
= \frac{1}{\sqrt{ 15 }}\arctan\left( \frac{x+1}{\sqrt{ 15 }} \right)+c
$$
