[[Vector Equations Of Lines]]
A plane a two dimensional flat surface that extends infinitley. A plane looks like this on the 3D vector plane. ![[Pasted image 20250912205932.png]]
- A plane is denoted $\Pi$. 
- A plane can be defined by a known point $r_{0}$ and any two non-parallel vectors that are in the plane.
- Any point $r$ in the plane cab represented by adding a combination of the two vectors to the known point $r_{0}$

$$
\Pi:r=r_{0}+\lambda b+\mu c
$$
Where $b$ and $c$ are any two non-parallel vectors that lie on the same plane.

Note that if two lines intersect, then they lie on the same plane:
![[Pasted image 20250912210312.png]]

# Worked Example 1
*Find the vector equation of the plane that contains the point $A(0,3,2)$, $B(5,4,1)$ and $C(-2,2,-4)$ 

1. When given three points. Start from point $A$ as $r_{0}$ then calculate non-parallel vectors $AC$ $AB$
$$
\begin{align*}
\overrightarrow{AB} &= \begin{pmatrix}5\\1\\-1\end{pmatrix}, &
\overrightarrow{AC} &= \begin{pmatrix}-2\\-1\\-6\end{pmatrix},\\
\end{align*}
$$
2. Write out the equation of the plane using the formula for a plane
$$
\begin{align*}
\Pi:\quad \mathbf{r} &= \begin{pmatrix}0\\3\\2\end{pmatrix} + \lambda\begin{pmatrix}5\\1\\-1\end{pmatrix} + \mu\begin{pmatrix}-2\\-1\\-6\end{pmatrix}
\end{align*}
$$

# Normal Vector
The normal vector $n_{\Pi}$ is the vector that is perpendicular to the  surface of the plane. 
Since we are given two direction vectors to form the plane. The normal vector must also be perpendicular to the two direction vectors on the plane. 

Thus the normal vector n is calculated by the cross product of the direction vectors in the plane formula
$$
n_{\Pi}=\begin{pmatrix}
5 \\
1 \\
-1
\end{pmatrix} \times \begin{pmatrix}
-2 \\
-1 \\
-6
\end{pmatrix} = \begin{pmatrix}
-7 \\
32 \\
-3
\end{pmatrix}
$$
# Plane Equation In Scalar Product Form
A plane can be described entirely by $n_{\Pi}$ and $r_{0}$ 
![[Pasted image 20250912213002.png]]

If we are given a point on the plane $r$ and a 
Vector $r-r_{0}$ lies in the plane but it is also perpendicular to $n_{\Pi}$. Thus the plane vector can be calculated using $r-r_{0}$ and n. 
