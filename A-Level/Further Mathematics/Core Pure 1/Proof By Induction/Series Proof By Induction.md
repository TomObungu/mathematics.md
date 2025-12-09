Often a series summation evaluates to an expression in terms of $n$. The key step for proof by induction when using series is to recognise that for a sum up to $n$, $\sum_{x=1}^{n} f(x)$ then the sum up to $n+1$ is:
$$
\sum_{x=1}^{n+1}f(x) = \sum_{x=1}^{n}f(x) +f(n+1)
$$

# Worked Example 1
![[Pasted image 20251209092253.png]]

Consider the case for $n=1$:
$$
\begin{gather*}
LHS = \sum_{r=1}^{1}r 2^{r} = 1(2)^{1}=2 \qquad RHS = 2(1+(1-1)2^{n}) = 2 \\ 
LHS = RHS \\
\therefore \text{The statement is true for } n=1
\end{gather*}
$$
Assuming that that summation formula is true of r $n=k$:
$$
\sum _{r=1}^{k}r 2^{r}=2(1+(k-1)2^{k})
$$
Consider the case when $n=k+1$:
$$
\begin{gather*}
\sum_{r=1}^{k+1} r 2^{r} = \sum_{r=1}^{k} r2r + (k+1)2^{k+1}\\ \\
= 2(1+(k-1)2^{k}) + (k+1)2^{k+1} \\ \\
= 2+2^{2k+1}-2^{k}+2^{2k+1}+2^{k+1} \\ \\
= 2(2^{2})
\end{gather*}
$$