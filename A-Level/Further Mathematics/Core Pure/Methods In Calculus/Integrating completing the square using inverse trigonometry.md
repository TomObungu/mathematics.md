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

However, below is a formal proof of why this works:
## Proof
$$
\begin{gather*}
\int \frac{1}{(x+1)^{2}+(\sqrt{ 15 })^{2}} \\ \\
\text{Let }x+1 = \sqrt{ 15 }\tan\theta \\ 
\frac{dx}{d\theta} = \sqrt{ 15 }\sec ^{2}\theta \\ 
dx = \sqrt{ 15 }\sec ^{2}\theta d\theta \\ \\
\int \frac{1}{15(\tan ^{2}\theta+1)}\sqrt{ 15 }\sec ^{2}\theta d\theta \\ \\
\int \frac{1}{(\sqrt{ 15 })^{2}(\sec ^{2}d\theta)}\sec ^{2}\theta d\theta \\ \\
= \int \frac{1}{\sqrt{ 15 } } = \frac{1}{\sqrt{ 15 }}\theta+c \\ \\
\arctan\left(\frac{x+1}{\sqrt{ 15 }}\right) =x \\ \\
\therefore \frac{1}{\sqrt{ 15 }}\arctan\left(\frac{x+1}{\sqrt{ 15 }}\right) +c
\end{gather*} 
$$

# Example 2
The same can be done with quadratics that have coefficients on the $x^{2}$ terms:
$$
\int \frac{1}{3x^{2}+6x+52}
$$
Completing the square:
$$
\begin{gather*}
3x^{2}+6x+52 \\ \\
3(x^{2}+2x)+52 \\ \\
3(x+1)^{2}-3+52 \\ \\
3(x+1)^{2}+49
\end{gather*}
$$
Rewriting integral:
$$
\int \frac{1}{3(x+1)^{2}+49} 
$$
Now it is similar to $\int \frac{1}{a^{2}+x^{2}}$, we just need to factor out the 3 like we normally do:
$$
\begin{gather*}
\int \frac{1}{3\left( (x+1)^{2}+\frac{49}{3} \right)}  \\ \\
 = \frac{1}{3}\int \frac{1}{(x+1)^{2}+\frac{49}{3}} \\ \\
= \frac{1}{3}\int \frac{1}{(x+1)^{2}+\left( \frac{7}{\sqrt{ 3 }} \right)^{2}}
\end{gather*}
$$
Now in this form we can write down the answer:
$$
\begin{gather*}
= \frac{1}{3} \left( \frac{\sqrt{ 3 }}{7}\arctan\left( \frac{\sqrt{ 3 }(x+1)}{7}+c \right) \right)  \\ \\
= \boxed{\frac{\sqrt{ 3 }}{21}arctan\left( \frac{\sqrt{ 3 }(x+1)}{7}\right)+c}
\end{gather*}
$$
