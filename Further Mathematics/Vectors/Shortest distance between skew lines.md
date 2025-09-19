
To workout the shortest distance between skew lines you must work out the perpendicular distance between the direction vectors between. This vector can be named $n$.
Skew lines may be drawn in 2D like this:
![[Pasted image 20250912201149.png]]
However, rotating around the 3D axis you will be able to see the lines are on completely different planes with different distances apart such the lines will never intersect:
![[Pasted image 20250912201248.png]]
Another way to represent skew lines is this:
![[Pasted image 20250912210848.png]]

The vector $\hat{n}$ is the unit vector of $n$ that is perpendicular to both direction vectors of the line.
Recall from [[Cross Product]] that:
$$
\hat{n}=a\times b
$$
Where the $a$ is the direction vector of line $l_{1}$ and b is the direction vector of $l_{2}$
![[Pasted image 20250912201800.png]]

Recall for [[Dot Product (Scalar Product)]] that the scalar product between vector $a$ and $b$ gives the component of a in direction $b$. This is where the scalar product becomes useful. This means that the direction that points towards the perpendicular vector between a point $A$ and a point $B$ on the line from point $A$ is the scalar product of $\vec{AB}$ multiplied by the $\hat{n}$. 

Thus, the short distance between the two skew lines $d$ can be calculated by:
$$
d=|\vec{AB}\cdot\hat{n}|
$$
Where $\vec{AB}$ is the direction vector between two points on the line and $\hat{n}$ is the cross product of the lines' direction vectors.

### Why
Why can we use any two points on the skew lines and use their direction vector?

This is because the shortest possible distance between the two lines will always be perpendicular. This means that for any other direction vector between the lines that's not the shortest, the component of the perpendicular distance between that line will always have the same component. This is true as if the points form the direction vector that is the shortest line between then then component will be the same. 

In other words, the direction vector between the two lines will always have the component value in the direction of the normal equal to the value of the shortest distance. This is because the direction vectors can never have a length short than the normal. Any shorter length would mean the line distances would become closer meaning the lines would intersect and not be skew.




## Worked example 1

Always remember that when given two skew lines, the points $A$ and $B$ can be any two points. Thus when given the lines, use the starting positions as points $A$ and $B$

1. Use the starting points of the equations of the line as starting points $A$ and $B$ to work out a direction vector $\vec{AB}$
$l_{1}:r=\begin{pmatrix}1 \\ 0 \\ 0\end{pmatrix} +\lambda \begin{pmatrix}0 \\ 1 \\ 1\end{pmatrix} \qquad l_{2}:r=\begin{pmatrix}-1 \\ 3 \\ -1\end{pmatrix} +\mu \begin{pmatrix}2 \\ -1 \\ -1\end{pmatrix}$
$$
\begin{gather*}\vec{OA} = \begin{pmatrix}
1 \\
0 \\
0
\end{pmatrix} \qquad
\vec{OB}=\begin{pmatrix}
-1 \\
3 \\
-1
\end{pmatrix} \\ \\
\vec{AB} = \begin{pmatrix}
-2 \\
3 \\
-1
\end{pmatrix}
\end{gather*}
$$
2. Calculate $\hat{n}$ by taking the cross product of the lines' direction vectors:
$$
\begin{gather*}
n = \begin{pmatrix}
0 \\
1 \\
1
\end{pmatrix} \times \begin{pmatrix}
2 \\
-1 \\
-1
\end{pmatrix} = \begin{pmatrix}
0 \\
2 \\
-2
\end{pmatrix} \\ \\ 
\hat{n} = \frac{1}{2\sqrt{ 2 }} \begin{pmatrix}
0 \\
2 \\
-2
\end{pmatrix} = \begin{pmatrix}
0 \\
\frac{\sqrt{ 2 }}{2}  \\
-\frac{\sqrt{ 2 }}{2}  
\end{pmatrix}
\end{gather*}

$$
3. Calculate d using $d=|\vec{AB}\cdot\hat{n}|$
$$
d=\begin{pmatrix}
-2 \\
3 \\
-1
\end{pmatrix} \cdot \begin{pmatrix}
0 \\
\frac{\sqrt{ 2 }}{2}  \\
-\frac{\sqrt{ 2 }}{2}  
\end{pmatrix} = 2\sqrt{ 2 }
$$
