The line of intersection between two planes will have a direction vector that is perpendicular to both planes. Thus this means the directions vector will be the cross product of the normal of plane $\Pi_{1}$ and plane $\Pi_{2}$. 

Thus to form the line you need another point on the plane. To get another point on the plane, simply substitute x = 0 for the plane formula in Cartesian form then solve from the coordinates $y$ and $z$ for both planes. If this doesn't work i.e one the plane is parallel the x-axis. Then substitute y = 0, or z = 0.

# Worked Example 1
*$\Pi_{1} : x+y+z = 1, \qquad \Pi_{2} : x+2y+3z=-4$. Find the equation of the line of intersections between the planes $\Pi_{1}$ and $\Pi_{2}$*

$$
\begin{gather*}
\vec{n} = \begin{pmatrix}
1 \\
1 \\
1
\end{pmatrix} \times \begin{pmatrix}
1 \\
2 \\
3
\end{pmatrix} = \begin{pmatrix}
1 \\
-2 \\
1
\end{pmatrix} \\ \\
\text{Setting } x = 0: \\ \\
y+z=-1 \\ \\
2y+3z=-4 \\ \\
y = 1 \qquad z = -2 \\ \\ 
\therefore r_{l} = \begin{pmatrix}
0 \\
1 \\
-2
\end{pmatrix} + \lambda \begin{pmatrix}
1 \\
-2 \\
1
\end{pmatrix}
\end{gather*}
$$
