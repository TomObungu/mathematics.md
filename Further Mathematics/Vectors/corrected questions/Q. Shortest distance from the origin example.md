![[Pasted image 20250920101051.png]]
# Simpler method
a) If you have the direction vector of the line which is found by calculating $\vec{AB}$ , you can form a general equation for the line using the starting point of the line and multiplying the direction vector $\vec{AB}$ by a scalar constant $\lambda$. If you have a general point on the line and the direction victor. The shortest distance will be perpendicular  to that general point on the line and the direction vector. 

Therefore to find the shortest distance you must find the normal between the two vectors by  taking the cross product between the unit vector of  direction vector and the general point on the line:
![[Pasted image 20250922081513.png]]
$$
\begin{gather*}
\vec{AB} = \begin{pmatrix}
12 \\
3 \\
8
\end{pmatrix} \qquad l_{1} : r=\begin{pmatrix}
-3 \\
1 \\
-7
\end{pmatrix} + \lambda \begin{pmatrix}
12 \\
3 \\
8
\end{pmatrix} \\ \\
\vec{OR} =\begin{pmatrix}
-3+12\lambda \\
1+3\lambda \\
-7+8\lambda
\end{pmatrix} \qquad \hat{AB} = \frac{1}{3\sqrt{ 53 }}\begin{pmatrix}
12 \\
3 \\
9
\end{pmatrix}\\ \\
\vec{n} = \begin{pmatrix}
-3+12\lambda \\
1+3\lambda \\
-7+8\lambda
\end{pmatrix} \times \begin{pmatrix}
12 \\
3 \\
8
\end{pmatrix} = 
\end{gather*}
$$

# Old method
a) You must work out line equation $\vec{AB}$ then write the point $\vec{OF}$ as the general  line in vector line  equation format.  Then you must work out the shortest distance from the point $\vec{OF}$ and demand it is perpendicular to the direction vector $\vec{AB}$ and work out $\lambda$
$$
\begin{gather*}
\vec{AB} = \begin{pmatrix}
12 \\
3 \\
18
\end{pmatrix} \qquad \vec{OF} = \begin{pmatrix}
-3 +12\lambda\\
1 + 3\lambda\\
-7 +18\lambda
\end{pmatrix} \\ \\
\vec{OR} = \begin{pmatrix}
-3 +12\lambda\\
1 + 3\lambda\\
-7 +18\lambda
\end{pmatrix} \cdot  \begin{pmatrix}
12  \\
3 \\
18
\end{pmatrix} = 0 \\ \\
-159+477\lambda = 0 \\ \\
\lambda = \frac{1}{3} \\ \\
d=\left|\begin{pmatrix}
1 \\
2 \\
-1
\end{pmatrix}\right| = \sqrt{ 6 } > 2 \\ \\ 
\therefore \text{The octupus will not catch the fish}
\end{gather*}
$$