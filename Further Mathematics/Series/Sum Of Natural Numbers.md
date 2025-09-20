## Sum of a constant $k$
To find the sum of a series of a constant number $k$ you can use the formula:
$$
\sum_{r=1}^n k = nk
$$
## Sum of all n up to n
To find the sum of a the natural numbers from $1$ to $r$ you can use the formula:
$$
\sum_{r=1}^nr=\frac{n(n+1)}{2}
$$
This evaluated equation is also the formula for the $nth$ triangular number

# Summation Of a series that does not start with $r=1$

It is possible to split the summation into two separate parts by evaluation:
$$
\sum_{r=k}^nf(r)= \sum_{r=1}^nf(r) - \sum_{r=1}^{k-1}f(r)
$$

# Summation expression with a constant
When a constant is with summation of an expression. It is possible to move the constant to the other side. Of the summation.
$$
\begin{gather*}
\sum_{r=1}^nkf(r)  \\ \\
= kf(1)+ kf(2) + k(3) \dots k(n) \\ \\
= k(f(1) + f(2) + f(3) \dots f(n)) \\ \\
= k\sum_{r=1}^nf(r)
\end{gather*}
$$

# Summation with the sum of two or more expressions
It possible to individually evaluation each distinct expression in a summation: 
$$
\begin{gather*}
\sum_{r=1}^n f(r) + g(r) \\ \\
= f(1) + g(1) \\ \\
= f(2) + g(2) \\ \\
= f(3) + g(3) \\ \\
\dots \\ \\
= f(n) + g(n) \\ \\
= \sum_{r=1}^nf(r) + \sum_{r=1}^ng(r)
\end{gather*}
$$

