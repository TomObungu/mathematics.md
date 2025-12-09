The key step for proof by induction for matrices is to first evaluate the given expression for $n=k$ in terms of k. Often the matrix proof involves proving an expression for the matrix raised to the power $n$. 

For cases when the matrix is raised to the power $n=k+1$. If matrix $\mathbf{M}$ is raised to the power of $n$, $\mathbf{M^{n}}$ then:
$$
\mathbf{M^{n+1}} = \mathbf{M}^{n}\mathbf{M}
$$
In this form, $M^{n}$ will be given as an expression that you can rewrite in terms of $k$
# Worked Example 1

![[Pasted image 20251209084109.png]]
Consider the case when $n=1$:
$$
\begin{gather*}
LHS = \begin{pmatrix}
1  & -1\\
0 & 2
\end{pmatrix} \qquad RHS = \begin{pmatrix}
1 & 1-2^{1} \\
0 & 2^{1}
\end{pmatrix} = \begin{pmatrix}
1  & -1 \\
0  & 2
\end{pmatrix} \\ \\
LHS =RHS  \\
\therefore \text{Statement is true for } n = 1
\end{gather*}
$$
Now suppose the statement is true for $n=k$:
$$
\begin{pmatrix}
1 & -1 \\
0  & 2 &
\end{pmatrix}^{k} = \begin{pmatrix}
1 & 1-2^{k} \\
0  & 2^{k}
\end{pmatrix}
$$
Consider the case when $n=k+1$:
$$
\begin{gather*}
\begin{pmatrix}
1 & -1 \\
0 & 2
\end{pmatrix}^{k+1}  = \begin{pmatrix}
1 & -1 \\
0  & 2
\end{pmatrix}^{k}\begin{pmatrix}
1 & -1 \\
0 & 2
\end{pmatrix} \\ \\ 
= \begin{pmatrix}
1 & 1-2^{k} \\
0 & 2k
\end{pmatrix}\begin{pmatrix}
1 & -1 \\
0 & 2
\end{pmatrix} = \begin{pmatrix}
1 & -1 + 2-2(2^{k}) \\
0 & 2(2^{k})
\end{pmatrix} \\ \\ 
= \begin{pmatrix}
1  & 1-2^{k+1} \\
0 &  2^{k+1}
\end{pmatrix}\\ \\
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
