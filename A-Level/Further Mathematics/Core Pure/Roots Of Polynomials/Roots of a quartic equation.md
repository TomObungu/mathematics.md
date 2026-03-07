If $\alpha$, $\beta$, $\gamma$ and $\gamma$ are roots of the equation $ax^{4} + bx^{3} + cx^{2} + dx +e =0$ then:
$$
\begin{gather*}
\alpha + \beta + \gamma + \delta = -\frac{b}{a} \\ \\
\alpha\beta + \alpha\gamma  + \alpha\delta + \beta\gamma + \beta\delta + \gamma\delta = \frac{c}{a} \\ \\
\alpha\beta\gamma + a\beta\delta + \alpha\gamma\delta + \beta\gamma\delta = -\frac{d}{a} \\ \\ 
\alpha\beta\gamma\delta = \frac{e}{a}
\end{gather*}
$$
# Example 1
The equation $x^{4}+2x^{3}+px^{2}+qx-60=0$, $x \in \mathbb{C}$, $p$, $q$, $\in \mathbb{R}$, has roots $\alpha$, $\beta$, $\gamma$ and $\delta$. Given that $\gamma = -2+4i$ and $\delta = \gamma^{*}$,
a Show that $\alpha + \beta - 2 =0$ and that $\alpha\beta + 3 = 0$.
b Hence find all the roots of the quartic equation and find the values of $p$ and $q$. 
a $$
\begin{gather*}
\alpha + \beta + \gamma + \delta = -2 \\ \\  
\alpha + \beta +(-2+4i) + (-2-4i) = -2 \\ \\
\alpha + \beta -4 = -2 \\ \\  
\alpha + \beta -2 = 0 \\ 
QED \\ \\
\alpha\beta(-2+4i)(-2-4i) = -60 \\ \\
20\alpha\beta = -60 \\ \\
a\beta = -3 \\ \\ 
\alpha\beta +3 = 0 \\ 
QED
\end{gather*}
$$b
Rearranging and solving simultaneously to find $\alpha$ and $\beta$
$$
\begin{gather*}
\alpha + \beta - 2 = 0\\ \\
\beta = 2 - \alpha \\ \\ \\
a(2-\alpha) + 3 =0 \\ 
\alpha^{2} - 2\alpha - 3 = 0 \\
(\alpha-3)(\alpha+1) = 0 \\ \\
\alpha = 3 \qquad \alpha = -1 \\ \\
\implies \beta = -1 \qquad \beta = 3 \\ \\
\end{gather*}
$$
So the roots of the quartic equation are:
$$
3, -1, 2+4i, -2-4i
$$
Using the sum of the products of pairs to find $p$. We will use the pair of $\alpha=3$ and $\beta=-1$
$$
\begin{gather*}
\sum\alpha\beta = \frac{p}{a} \\ \\ 
\alpha\beta + \alpha\gamma + \alpha\delta + \beta\gamma + \beta\delta +\delta\gamma = \frac{p}{a} \\ \\
(3)(-1) + (3)(-2+4i) + 3(-2-4i)+(-1)(-2+4i) + (-1)(-2-4i) + (-2-4i)(-2+4i) = \frac{p}{a} \\ \\
\therefore 9 = p 
\end{gather*}
$$
Using the sum of the products of the triplets to find $q$. When dealing with sum of triplets or higher, follow a pattern of $\alpha\beta\gamma$, $\alpha\beta\delta$, $\alpha\gamma\delta$ and so. Do the first 2 terms in increasing order then gradually increase the last term then go back and increase the first two terms. It also possible to double check if you have all the triplets by using $\begin{pmatrix}n \\ k\end{pmatrix}$ formula.

In this case we know that is only 4 products as $\begin{pmatrix}4 \\ 3\end{pmatrix}=3$
$$
\begin{gather*}
\sum \alpha\beta\gamma = -\frac{q}{a} \\ \\
\alpha\beta\gamma + \alpha\beta\delta + \alpha\gamma\delta + \beta\gamma\delta = -\frac{q}{a} \\ \\
(3)(-1)(-2+4i) + (3)(-1)(-2-4i) + (3)(-2+4i)(-2-4i) + (-1)(-2-4i)(-2+4i) = -\frac{q}{a} \\ \\
\boxed{-52 = q}
\end{gather*}
$$