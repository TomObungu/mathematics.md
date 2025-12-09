The key step to proof by induction for divisibility  is to consider:
$$
f(k+1) - f(k)
$$
And write the final expression in terms of $f(k+1)$ only

The other key step for proof by induction for Divisibility is to  try techniques such as reducing powers until the expression is in terms of $k+1$ or splitting up expressions to get multiples of $f(n)$.

In general for any expression $a^{x}$, it possible to reduce the power of the expression such that:
$$
\begin{gather*}
a^{x+1} = a(a^{x}) \quad  or \quad a^{x+2} = a^{2}(a^{x}) \\
\dots \\ 
a^{x+m} = a^{k}(a^{x+m-k}) \\ \\

\end{gather*}
$$
This can only go up until $a^{x-1}$ as $x\geq{1}$ thus at the very least $a^{0}=1$

As well as that it is possible to split multiples of powers up which can be useful when trying to get an expression for some $f(n)$ given in the question:
E.g.
$$
\begin{gather*}
8(a^{x+1}) = 3(a^{x+1}) + 5(a^{x+1})
\end{gather*}
$$

# Worked Example 1
This is a standard example that involves reduction of powers but not splitting up sums of powers terms:
![[Pasted image 20251209102028.png]]

Let $f(n)=3^{2n+11}$.

Consider the case when $n=1$:
$$
\begin{gather*}
f(1) = 3^{2}+11 = 20 = 4(5), \\ \text{which is divisible by } 4 \\ \\
\therefore \text{The statement is true for } n=1
\end{gather*}
$$
Assuming that the statement is true for $n=k$ such that $f(k)$ is divisible by $4$:
$$
f(k) = 3^{2k}+11
$$
Consider the case $f(k+1)-f(k)$:
$$
\begin{gather*}
= (3^{2(k+1)} +11) - (3^{2k}+11) \\ \\
= 3^{2k+2}+11-3^{2k}+11 \\ \\
= 9(3^{2k})-3^{2k} \\ \\
=8(3^{2k}) \\ \\
= 4(2)(3^{2k}), \text{ wich is divisible by } 4 

\end{gather*}
$$Therefore:
$$
f(k+1) = f(k) + 4(2)(3^{2k})
$$
Hence, since $f(k)$ is divisible $by$ 4 and  $4(2)(3^{2k})$ is also divisible $4$ then $f(k+1)$ is also divisible by $4$:
$$
\therefore \text{The statement is true for } n = k+1
$$
$$
\begin{gather*}
\text{We have proven the statement is true for n =1, n = k and for n = k +1} \\
\text{Therefore, the statement is true for all n>1} \\
QED
\end{gather*}
$$

# Worked Example 2
This is a standard example which involves reducing the power and splitting up a sum of the power terms