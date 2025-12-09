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
= 2+(k-1)2^{k+1}+(k+1)2^{k+1} \\ \\
= 2 +2^{k+1}(k-1+k+1) \\ \\
= 2+2^{k+1}(2k) \\ \\
= 2(1+k 2^{k+1}) \\ \\
= 2(1+(k+1)-1)2^{k+1}) \\ \\
\therefore \text{The statement is true for } n = k+1
\end{gather*}
$$
$$
\begin{gather*}
\text{We have proven the statement is true for n=1, n =k and for n=k +1} \\
\text{Therefore, the statement is true for all n>1} \\
QED
\end{gather*}
$$
# Worked Example 2
For some series questions, you will be asked to prove standard sum expressions or even use them within the first half of the question as a standard series question.

However in the parts of the question to do with proof by induction, you should always evaluate the expression and aim to rearrange it in terms of $k+1$

Prove by induction that:
![[Pasted image 20251209094454.png]]

Consider the case when $n=1$:
$$
\begin{gather*}
LHS = \sum_{r=1}^{1}(2(1)-1)^{2}=1 \qquad RHS = \frac{1}{3}(1)(4(1)^{2}-1) =1 \\ \\
LHS = RHS \\ \\ 
\therefore \text{The statement is true for } n = 1
\end{gather*}
$$
Assuming that the summation formula is true for $n=k$:
$$
\sum_{r=1}^{k}(2r-1)^{2}=\frac{1}{3}(k)(4k^{2}-1)
$$
Consider the case for when $n=k+1$:
$$
\begin{gather*}
\sum_{r=1}^{k+1} (2r-1)^{2} = \sum_{r=1}^{k}(2r-1)^{2} + (2(k+1)-1)^{2} \\ \\
= \frac{1}{3}(k)(4k^{2}-1)+(2k+1)^{2} \\ \\
\end{gather*}
$$

--- 
Now remember some tips for when dealing with the evaluated expressions for sums:

1. Always factor out by the fraction with the largest denominator
2. Recognise any differences of squares or ways to simplify brackets rather than expanding them
3. Always factor out any common terms in brackets to the outside
4. If what remaining in the inner brackets of factorisation can be expanded, expand them and try factorise a quadratic

5. It is possible to try and work backwards from the final evaluated expression by substituting in $k+1$. E.g in this case:
$$
\begin{gather*}
W.T.S = \frac{1}{3}(k+1)(4(k+1)^{2}-1) \\ \\
= \frac{1}{3}(k+1)(4k^{2}+8k+4-1) \\ \\
= \frac{1}{3}(k+1)(4k^{2}+8k+3)
\end{gather*}
$$
Meaning we should try and rearrange and manipulate our expression to look something like $\frac{1}{3}(k+1)(4k^{2}+8k+3)$
--- 
 $$
\begin{gather*}
 = \frac{1}{3}(k)(2k+1)(2k-1)+(2k+1)^{2} \\ \\
 =\frac{1}{3}(2k+1)\left[k(2k-1)+3(2k+1)\right] \\ \\
 = \frac{1}{3}(k)(2k+1)\left[ 2k^{2}-k+6k+3 \right] \\ \\
 = \frac{1}{3}(k)(2k+1)\left[ 2k^{2}+5k+3 \right] \\ \\
 = \frac{1}{3}(k)(2k+1)(2k+3)(k+1) \\ \\
 = \frac{1}{3}(k)(k+1)[(2k+3)(2k+1)] \\ \\ 
 = \frac{1}{3}(k)(k+1)[4k^{2}+8k^{2}+3] \\ \\ 
= \frac{1}{3}(k)(k+1)[4(k+1)^{2}-1)] \\ \\ 
\therefore \text{The statement is true for } n = k+1
\end{gather*}
$$
$$
\begin{gather*}
\text{We have proven the statement is true for n=1, n =k and for n=k+1 } \\
\text{Therefore, the statement is true for all n>1} \\
QED
\end{gather*}
$$
