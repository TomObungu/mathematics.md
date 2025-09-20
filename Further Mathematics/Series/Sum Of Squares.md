# Proof
It is possible to prove that $r^{3}-(r-1)^{3} \equiv 3r^{2}+3r+1$

Recall that ($ax+b)^{3} = a^{3}x^{3}+3a^{2}bx^{2}+3ab^{2}x+b^{3}$

$$
\begin{gather*}
r^{3}-(r-1)^{3} = r^{3}-(r^{3}-3r^{2}+3r-1) \\ \\
= 3r^{2}-3r+1
\end{gather*}
$$

Use that result, it possible to form an evaluation using the formulas. 
$$
\begin{gather*}
\sum_{r=1}^n 3r^{2}-3r+1 = \sum_{1}^n r^{3}-(r-1)^{3} \\ \\
= 1^{3} - 0^{3} \\ \\
+ 2^{3}-1^{3} \\ \\
+ 3^{3} - 2^{3} \\ \\
+ 4^{3}-3^{3}
\end{gather*}
$$
This will lead to a type of pattern in summation known a as a **telescoping sum**. 
$$
\begin{gather*}
\sum_{r=1}^n 3r^{2}-3r+1 = \sum_{1}^n r^{3}-(r-1)^{3} \\ \\
= \cancel{ 1^{3} } - 0^{3} \\ \\
+ \cancel{ 2^{3} }-\cancel{ 1^{3} } \\ \\
+ \cancel{ 3^{3} } - \cancel{ 2^{3} } \\ \\
+ 4^{3}-\cancel{ 3^{3} } \\ \\ 
\dots \\ \\
+ \cancel{ (n-1)^{3} } -\cancel{ (n-2)^{3} }\\ \\
+ n^{3}-\cancel{ (n-1)^{3} } \\ \\
= n^{3}
\end{gather*}
$$
Therefore it possible to evaluate $r^{2}$ by rearranging to find $r$. Remember it is also beneficial to evaluate the constant first when dealing with equations. 

You can evaluate fractions by multiplying everything inside the bracket by the largest denominator and then dividing out the fraction by the largest denominator

It also better to have leading terms (The exponent with the highest degree of accuracy) to have the same sign or better to both be positive to simplify calculations.
$$
\begin{gather*}
n^{3} = \sum_{r=1}^n 3r^{2}-3r+1 \\ \\
-3\sum_{r=1}^n r^{2} = -n^{3}-\sum_{r=1}^n 3r + \sum_{r=1} ^n 1 \\ \\
3\sum_{r=1}^nr^{2}=n^{3}+\sum_{r=1}^n3r-\sum_{r=1}^n 1 \\ \\
= \frac{1}{3}\left( n^{3}+\frac{3n(n +1)}{2} - n \right) \\ \\
= \frac{1}{6}(2n^{3}+ 3n(n+1) -2n) \\ \\
= \frac{1}{6}(2n^{3}+3n^{2}+3n-2n) \\ \\
=\frac{1}{6}(2n^{3}+3n^{2}+n) \\ \\
=\frac{1}{6}n(2n^{2}+3n+1) \\ \\
=\frac{1}{6}n(n+1)(2n+1)
\end{gather*}
$$


Therefore:
$$
\sum_{r=1}^n r^{2} = \frac{1}{6}n(n+1)(2n+1)
$$
