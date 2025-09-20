#Identities #shortcuts
It is possible to show that:
$$
\left( \sum_{r=1}^nr \right)^{2}=\sum_{r=1}^nr^{3}
$$

and:
$$
\sqrt{\sum_{r=1}^nr^{3}} = \sum_{r=1}^nr
$$

This is because:
$$
\left( \frac{n(n+1)}{2} \right)^{2}=\frac{1}{4}n^{2}(n+1)^{2}
$$
This is useful for in an example like this:
*E.g. Compute $\sum_{r=1}^3r_{3}$*
$$
\begin{gather*}
\sum_{r=1}^3r = 1 + 2 + 3 = 6 \\ \\
\therefore \sum_{r=1}^3r_{3} = (\sum_{r=1}^3r )^{2} = 6^{2} = 36
\end{gather*}
$$
Another example:
*Compute $\sum_{r=1}^{10}r^{3}$*
$$
\sum_{r=1}^{10}r^{3} = \left(\frac{10(11)}{2}\right)^{2} = 55^{2} = 3025
$$
This might faster than typing $\frac{1}{4}(10)^{2}(11)^{2}$ into your calculator 

## Problem solving example 1:
*Find n such that $\sum_{r=1}^nr^{3}=8281$*

In this scenario, it might be easier to use $\left(\frac{n(n+1)}{2}\right)^{2}$ than $\frac{1}{4}n^{2}(n+1)^{2}$

$$
\begin{gather*}
\left( \frac{n(n+1)}{2} \right)^{2}=8281 \\ \\
\frac{n(n+1)}{2}=91 \\ \\
n(n+1)=182 \\ \\
\colorbox{purple}{$n=13$} \qquad \cancel{ n = -14 }
\end{gather*}
$$
## Problem solving example 2:
*Simplify $\frac{\sum_{r=1}^n {3}r^{3}}{\sum_{r=1}^n 2r}$*

In this scenario it is much simpler to directly evaluate the expression using the identity expressions

$$
\begin{gather*}
\frac{\sum_{r=1}^n {3}r^{3}}{\sum_{r=1}^n 2r} = \frac{3\sum_{r=1}^n r^{3}}{2\sum_{r=1}^n r} \\ \\
\left( \frac{3}{2} \right)\frac{\left(\sum_{r=1}^n r\right)^{2}}{\sum_{r=1}^n r} = \left( \frac{3}{2} \right)\sum_{r=1}^n r = \frac{3}{2}\left( \frac{n(n+1)}{2} \right)
\end{gather*}
$$
