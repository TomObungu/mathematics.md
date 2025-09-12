[[Vector Equations Of Lines]] 
## Shortest distance from a point to a line
https://youtu.be/64gLQw99XCU?si=uuwIAamF74xwPjBu
The shortest test distance is the perpendicular distance to the line.  Therefore you must work $\vec{AB}$ then where $A$ is the point and $B$ is the general point on the line. 

Then you must dot product $\vec{AB}$ with the direction vector of the line and demand it is equal to 0. This is because if you recall from [[Dot Product (Scalar Product)]]. The dot product of any two vectors that are perpendicular are 0.

# Worked Example 1

In this type of example always remember to work out $\vec{AB}$ in general form and dot product the direction vector of the line


*$l_{1}:r=\begin{pmatrix}1 \\ 5 \\ -3\end{pmatrix} +\lambda \begin{pmatrix}1 \\ 1 \\ -1\end{pmatrix} \qquad A(4,5,6)$*
*Find the shortest distance from A to $l_{1}$
$$
\begin{gather*}
\vec{OA} = \begin{pmatrix}
4 \\
5 \\
6
\end{pmatrix} \qquad \vec{OB} =\begin{pmatrix}
1+\lambda \\
5+\lambda \\
-3-\lambda
\end{pmatrix} \\ \\
\vec{AB} = \begin{pmatrix}
-3+\lambda \\
\lambda \\
-9-\lambda
\end{pmatrix} \\ \\
\begin{pmatrix}
-3+\lambda \\
\lambda \\
-9-\lambda
\end{pmatrix} \cdot \begin{pmatrix}
1 \\
1 \\
-1
\end{pmatrix} = 0\\ \\
(-3+\lambda)-(-9-\lambda)+(-3-\lambda)=0\\
-3+\lambda+9+\lambda-3-\lambda=0\\
3\lambda=-6\\
\lambda=-2\\
\vec{AB}=(-5,-2,-7)\\
d=\|\vec{AB}\|=\sqrt{(-5)^2+(-2)^2+(-7)^2}=\sqrt{78}
\end{gather*}
$$

