[[Determinants]] [[Matrix Multiplication]]
**If matrix $A$ and matrix $B$ are non-singular matrices, then $(AB)^{-1}=B^{-1}A^{-1}$.
If $A = A^{-1}$, then $A^{2} = I$.

---
## Example 1
*P and Q are non-singular matrices. Prove that $(PQ)^{-1} = Q^{-1}P^{-1}$

$$
\begin{gather*}
\text{Let } C = (PQ)^{-1} \text{ then } \\ (PQ)C = I \\
& & & & &\underrightarrow{\times P^{-1}} \\ 
P^{-1}PQC = P^{-1}I \\
IQC = P^{-1} \\
QC = P^{-1}
& & & & &\underrightarrow{\times Q^{-1}} \\ 
Q^{-1}QC = Q^{-1}P^{-1} \\
IC = Q^{-1}P^{-1} \\
C = Q^{-1}P^{-1} \\ \\
\therefore (PQ)^{-1} = Q^{-1}P^{-1}
\end{gather*}
$$
--- 
## Example 2
*$A$ and $B$ are non-singular $2 \times 2$ matrices such that $BAB = I$*
*a Prove that $A=B^{-1}B^{-1}$*
b Given that $B = \begin{pmatrix}2 & 5  \\ 1 & 3 \end{pmatrix}$: Find the matrix $A$ such that $BAB=I$

**a**
$$
\begin{gather*}
BAB = I \\
B^{-1}BAB=B^{-1}I \\
AB = B^{-1} \\ \\
ABB^{-1} = B^{-1}B^{-1} \\
AI = B^{-1}B^{-1} \\ \\
\therefore A = B^{-1}B^{-1} & \text{As required}
\end{gather*}

$$


