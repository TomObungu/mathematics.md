A line has no thickness or no curvature. The vector equation of a line can be represented by:
$r$ = A position vector of any generic point on a line
$a$ = A position vector of a known starting point 
$b$ = Direction vector of the line
$$
r = a + \lambda b
$$
Thus any point on the line can be represented by adding a scalar multiple $\lambda$of the direction vector.

# Example 1
If you are given two points, $A$ and $B$ the line will be vector A + $\lambda\vec{AB}$

# Example 2
If you are given a point and asked to confirm if it lies on the line. Set the line equal to that point and solve for $\lambda$. However you must write the line $l_{1}$ in position vector form. E.g.
$$
l_{2} : r = \begin{pmatrix}
2 \\
1 \\
6
\end{pmatrix} + \lambda \begin{pmatrix}
3 \\
3 \\
-1
\end{pmatrix}
$$
Then the general point $B$ of $l_{2}$ is $$
\vec{OB} = \begin{pmatrix}
2 + 3\lambda \\
1+3\lambda \\
6-\lambda
\end{pmatrix}
$$
# Example 3
If lines are parallel then their direction vector will be the same due to parallel lines being multiples of each other. 

If you are given two lines and they are parallel and one passes through a given point $A$. The equation of the given line will be the given point $A$ + $\lambda b$  where b is the direction vector

# Cartesian Equation Of Line 
If
$$
r = a + \lambda b
$$
then
$$
\begin{pmatrix}
x \\
y \\
z
\end{pmatrix}=\begin{pmatrix}
a_{x} \\
b_{y} \\
c_{z} \
\end{pmatrix} + \lambda\begin{pmatrix}
b_{x}  \\
b_{y} \\
b_{z} \\
\end{pmatrix}
$$
this means:
$$
\begin{gather*}
x=a_{x}+\lambda b_{x} \\
y=a_{y}+\lambda b_{y} \\
z=a_{z}+\lambda b_{z}
\end{gather*}
$$
$$
\begin{align*}
x &= a_x + \lambda b_x,\quad y = a_y + \lambda b_y,\quad z = a_z + \lambda b_z\\ \\
\therefore\quad \lambda &= \frac{x-a_x}{b_x} = \frac{y-a_y}{b_y} = \frac{z-a_z}{b_z}
\end{align*}
$$
Always remember that the minus sign means the coordinate of vectors with $a_{x}$ are positive.

## Shortest distance between parallel lines
The short