[[Vector Equations Of Lines]] [[Dot Product (Scalar Product)]]
## Parallel
If lines are parallel this means that their direction vectors are multiples of each other. 
# Perpendicular 
Lines are perpendicular if their dot product is equal to 0. 
## Intersect
If lines intersect then their angle between them is the dot product. However this alone is not enough to show if lines intersect as the lines may be perpendicular and still intersect. To show if lines intersect you must:
1. have their general formula for each line with their direction vectors as $\lambda$ and $\mu$
2. Set them equal to each other and solve for $\lambda$ and $\mu$ by eliminating variables 
3. Verify the values of $\lambda$ and $\mu$

# Skewed lines
Skewed lines are not $\parallel$ and do not intersect.

# Worked Example 1
Determine whether $l_{1}$ and $l_{2}$ intersect
$$
\begin{gather*}
l_{1}:\begin{pmatrix}
0 \\
2 \\
-1
\end{pmatrix} + \lambda \begin{pmatrix}
4 \\
-2 \\
3
\end{pmatrix} \ \ \ \ \ \ \ \ l_{2}:\begin{pmatrix}
4 \\
1 \\
-2
\end{pmatrix} + \mu \begin{pmatrix}
1 \\
4 \\
4
\end{pmatrix} \\ \\ 
4\lambda = 4+\mu \\
2-2\lambda = 1+4\mu \\
-1+3\lambda = -2 + 4\mu \\ \\
3-5\lambda = 3 \\
\therefore \lambda=0 \qquad \mu=\frac{1}{4} \\ \\
4\lambda = 0 \\
4+\mu = \frac{17}{4}\neq 4\lambda \\ \\
\implies \text{The lines do not intersect} \\
\therefore l_{2} \text{ and } l_{1} \text{ skew }
\end{gather*}
$$