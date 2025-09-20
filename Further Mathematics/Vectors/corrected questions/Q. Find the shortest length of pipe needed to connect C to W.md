![[Pasted image 20250920094813.png]]
b)To calculate the shortest distance from C to W. You need to calculate the shortest distance from the line W to the point C on the plane. This is simply just the shortest distance from a point to a line. You must find out $\vec{CW}$ $\vec{OW}$ is the general point on the line $\vec{W}$. 

Alternatively you can work out the shortest distance from the plane the general point on the line and solve for $\lambda$
$$
\begin{gather*}
W : r=\begin{pmatrix}
-1 \\
-1 \\
-3
\end{pmatrix} + \lambda \begin{pmatrix}
2 \\
3 \\
0
\end{pmatrix}  \\ \\
\vec{OC} = \begin{pmatrix}
-1 \\
-2 \\
0
\end{pmatrix} \qquad \vec{OW} = \begin{pmatrix}
-1+2\lambda \\
-1+3\lambda \\
-3
\end{pmatrix} \\ \\
\vec{CW} = \begin{pmatrix}
2\lambda \\
1+3\lambda \\
-3
\end{pmatrix} \\ \\
\begin{pmatrix}
2\lambda \\
1+3\lambda \\
-3
\end{pmatrix} \cdot \begin{pmatrix}
2 \\
3 \\
0
\end{pmatrix} = 0 \\ \\ 
\lambda=-\frac{3}{13}
\end{gather*}
$$