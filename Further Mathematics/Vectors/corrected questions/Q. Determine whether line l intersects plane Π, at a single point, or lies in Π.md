![[Pasted image 20250919180731.png]]
You must substitute it the general point in the scalar product form of the plane (take the dot product between the general point and the normal and set it equal to d), and check if the equation formed is consistent. 
$$
\begin{gather*}
l : r=\begin{pmatrix}
-2 \\
5 \\
4
\end{pmatrix} + \lambda \begin{pmatrix}
1 \\
-1 \\
-3
\end{pmatrix} \\ \\
r = \begin{pmatrix}
-2+\lambda \\
5-\lambda \\
4-3\lambda
\end{pmatrix} \\ \\
\begin{pmatrix}
-2+\lambda \\
5-\lambda \\
4-3\lambda
\end{pmatrix} \cdot \begin{pmatrix}
1 \\
-2 \\
1
\end{pmatrix} = -7 \\ \\
(-2+\lambda)+(-2)(5-\lambda)+(4-3\lambda) = -7 \\ \\
-2 + \lambda -10 +2\lambda +4 -3\lambda=-7 \\ \\
\lambda+2\lambda-3\lambda-2-10+4=-7\\ \\
-8=-7 \\ \\
-8 \neq -7  \\ 
\implies \text{The line and the plane  do not intersect} \\ \\
\therefore l \parallel  \Pi \text{ without intersecting}
\end{gather*}
$$
If you were to get something like 
$$
\begin{gather*}
\begin{pmatrix}
-2+\lambda \\
5-\lambda \\
4-3\lambda
\end{pmatrix} \cdot \begin{pmatrix}
\dots \\
\dots \\
\dots
\end{pmatrix} = -7 \\ \\
\dots \\ \\
-7=-7
\end{gather*}
$$
The line $l$ would lie within the plane giving infinitely many solutions of points of intersection. 