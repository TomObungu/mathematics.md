Much like the sum of squares proof in [[Sum Of Squares]]. It is possible to prove that $r^{4}-(r-1)^{4} \equiv 4r^{3}-6r^{2}+4r-1$

Recall from [[Binomial Expansion]] that:
$$
(a+bx)^{4} = a^{4}\left( 1+\begin{pmatrix}
4 \\
1
\end{pmatrix}\left( \frac{b}{a}x \right) + \begin{pmatrix}
4 \\
2
\end{pmatrix}\left( \frac{b}{a}x \right)^{2} + \begin{pmatrix}
4 \\
3
\end{pmatrix}\left( \frac{b}{a}x \right)^{3} + \left( \frac{b}{a}x \right)^{4}\right)
$$


$$
\begin{gather*}
r^{4} - (r-1)^{4}\\ \\
= r^{4}-(r^{4}-4r^{3}+6r^{2}-4r+1) = 4r^{3}-6r^{2}+4r-1
\end{gather*}

$$
Evaluating the LHS expression produces a telescoping series:
$$
\begin{gather*}
r^{4}-(r-1)^{4} \\ \\
= \cancel{ 1^{4}  }- 0^{4} \\ \\
=\cancel{ 2^{4} } - \cancel{ 1^{4} }  \\ \\
= \cancel{ 3^{4 }} - \cancel{ 2^{4} } \\ \\ 
\dots \\ \\
= n^{4} - \cancel{ (n-1)^{4} } \\ \\
= n^{4}
\end{gather*}
$$
Therefore:
$$
\sum_{r=1}^n4r^{3}-6r^{2}+4r-1 = \sum_{r=1}^n n^{4}
$$
Rearranging to get the expression $\sum_{r=1}^n r^{3}$ :
$$
\begin{gather*}
-\sum_{r=1}^n 4r^{3} = -\sum_{r=1}^n
\end{gather*}
$$

