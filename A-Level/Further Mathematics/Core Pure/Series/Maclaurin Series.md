Many functions can be written as an infinite sum of terms of the form $ax^{n}$. For example, throw back to the binomial expansion from A-Level:
$$
\begin{gather*}
(1-x)^{-1}=\frac{1}{1-x} = 1+x+x^{2}+x^{3}\dots, |x|<1 \\ \\
(1-x)^{\frac{1}{2}} = \sqrt{ 1-x } = 1+\frac{x}{2} + \frac{x^{2}}{8} + \frac{x^{3}}{16}\dots, |x| < 1 \\ \\
\end{gather*}
$$
As well as that, you have known:
$$
e^{x} = 1+x+\frac{x^{2}}{2} + \frac{x^{3}}{6}+\frac{x^{4}}{24}+\dots, x \in \mathbb{R}
$$
# Derivation of Maclaurin Series 
Given that a function $f(x)$,  can be differentiated infinitely many times and that is has a valid series expansion of the form $f(x) = a_{0}+a_{1}x+a_{2}x^{2}+a_{3}x^{3}\dots,a_{r}x^{r}\dots ,$ where $a_i$ are all real constants, it is possible to show that:
$$
\begin{gather*}
f(0) = a_{0}
\end{gather*}
$$
Differentiating $f(x)$ gives:
$$
\begin{gather*}
f'(x) = a_{1} + 2a_{2}x+3a_{3}x^{2}+\dots+ ra_{r}x^{r-1} +\dots\\ \\
f''(x) = 2(1)a_{2} + 3(2)a_{3}x+ 4(3)a_{4}x^{r-1} + \dots +r(r-1)a_{r}x^{r-2} +\dots \\ \\
f'''(x) = (3)(2)(1)a_{3}+ 4(3)(2)a^{4}x +\dots + r(r-1)(r-2)a_{r}x^{r-3} +\dots
\end{gather*}
$$

