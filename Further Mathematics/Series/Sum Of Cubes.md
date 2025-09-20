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
\sum_{r=1}^nr^{4}-(r-1)^{4} \\ \\
= \cancel{ 1^{4}  }- 0^{4} \\ \\
+\cancel{ 2^{4} } - \cancel{ 1^{4} }  \\ \\
+ \cancel{ 3^{4 }} - \cancel{ 2^{4} } \\ \\ 
\dots \\ \\
+ n^{4} - \cancel{ (n-1)^{4} } \\ \\
= n^{4}
\end{gather*}
$$
Therefore:
$$
\sum_{r=1}^n4r^{3}-6r^{2}+4r-1 = n^{4}
$$
Rearranging to get the expression $\sum_{r=1}^n r^{3}$ :
$$
\begin{gather*}
n^{4} = \sum_{r=1}^n 4r^{3}-6r^{2}+4r-1 \\ \\
-\sum_{r=1}^n 4r^{3} = -n^{4} -6r^{2} + 4r-1 \\ \\
\sum_{r=1}^n 4r^{3} = n^{4} +6r^{2} - 4r+1 \\ \\
\sum_{r=1}^n r^{3} = \frac{1}{4}\left( n^{4}+6\left( \frac{1}{6}n(n+1)(2n+1)\right)  -\frac{4n(n+1)}{2}+n\right) \\ \\
= \frac{1}{4}\left( n^{4}+ n(n+1)(2n+1) - 2n(n+1) +n\right) \\ \\
= \frac{1}{4}n\left( n^{3}+ (n+1)(2n+1) - 2(n+1) +1\right) \\ \\
= \frac{1}{4}n\left( n^{3}+ 2n^{2}+3n+1 - 2n-2 +1\right) \\ \\
= \frac{1}{4}n\left( n^{3}+ 2n^{2}+n\right) \\ \\
= \frac{1}{4}n^{2}\left( n^{2}+ 2n+1\right) \\ \\
= \frac{1}{4}n^{2}\left( n+1\right)^{2} \\ \\
\end{gather*}
$$
Therefore:
$$
\sum_{r=1}^nr^{3}=\frac{1}{4}n^{2}(n+1)^{2}
$$


