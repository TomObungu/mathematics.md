# Intersection between a line and a plane. 
When a line and a plane intersect, the position vector of $r$ is the same for the line and the plane. Thus when given a line equation $l_{1}$, substitute the line into the plane. 
![[Pasted image 20250915184412.png]]

## Worked Example 1
$$
\begin{gather*}
l_{1} : r=\begin{pmatrix}
-1 \\
1 \\
5
\end{pmatrix} + \lambda\begin{pmatrix}
1 \\
1 \\
2
\end{pmatrix} \qquad \Pi_{1} : r \cdot \begin{pmatrix}
1 \\
2 \\
3
\end{pmatrix} = 4 \\ \\ 
r = \begin{pmatrix}
-1 + \lambda \\
1 + \lambda \\
-5 + 2\lambda
\end{pmatrix} \qquad \begin{pmatrix}
-1 + \lambda \\
1 + \lambda \\
-5 + 2\lambda
\end{pmatrix} \cdot \begin{pmatrix}
1 \\
2 \\
3
\end{pmatrix} = 4 \\ \\
9\lambda = 18 \qquad \lambda=2 \\ \\
\therefore r = \begin{pmatrix}
1 \\
3 \\
-1
\end{pmatrix} \\ \\
\text{The point of intersection is at } (1,3,-1)
\end{gather*}
$$

# Shortest distance between a line and a plane
Working out shortest distance between a line and plane assumes that the line and plane do not intersect. The shortest distance will be perpendicular distance between the line and the plane. 
To calculate the shortest distance between a line and a plane:
1. If given the plane in general form with two directions vectors, take the dot product of the to calculate the normal vector. Otherwise in scalar product form, recognise the coefficients are the normal vector. 
2. 
