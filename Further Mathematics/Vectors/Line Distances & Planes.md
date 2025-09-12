[[Vector Equations Of Lines]] 
## Shortest distance from a point to a line
https://youtu.be/64gLQw99XCU?si=uuwIAamF74xwPjBu
The shortest test distance is the perpendicular distance to the line.  Therefore you must work $\vec{AB}$ then where $A$ is the point and $B$ is the general point on the line. 

Then you must dot product $\vec{AB}$ with the direction vector of the line and demand it is equal to 0. This is because if you recall from [[Dot Product (Scalar Product)]]. The dot product of any two vectors that are perpendicular are 0.

# Worked Example 1

In this type of example always remember to work out $\vec{AB}$ in general form and dot product the direction vector of the line. It is better to set the line equation as $\vec{OB}$ to avoid needing to negate any $\lambda$ variables which could potentially lead to errors. 


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

## Shortest distance between parallel lines
https://youtu.be/EyKPii_0BQY?si=iA8AcxQCc7oYrxbg
The shortest distance between parallel lines is the shortest distance from any point on one line to the other line. Consider
$$
l_{1}:r=\begin{pmatrix}
2 \\
-4 \\
0
\end{pmatrix} + \begin{pmatrix}
1 \\
-3 \\
2
\end{pmatrix} \qquad l_{2}:\begin{pmatrix}
4 \\
2 \\
1
\end{pmatrix} + \mu \begin{pmatrix}
-2 \\
6 \\
-4
\end{pmatrix}
$$

The method is identical however instead of  caculating the general point of $l_{2}$ in the form $\begin{pmatrix}4-2\mu \\ 2+6\mu \\ 1-4\mu\end{pmatrix}$, you only need to calculate the general form of one line e.g. $l_{1}$ then repeat the process to find the short distance from point using the starting point from $l_{2}$ as the secondary point $\vec{OB}$

# Worked example 2

*$l_{1}:r=\begin{pmatrix}2 \\ -3 \\ 0\end{pmatrix} +\lambda \begin{pmatrix}1 \\ -3 \\ 2\end{pmatrix} \qquad l_{2}:r=\begin{pmatrix}4 \\ 2 \\ 1\end{pmatrix} +\mu \begin{pmatrix}2 \\ 6 \\ -4\end{pmatrix}$ 
Find the shortest distance between $l_{1}$ and $l_{2}$
$$
\begin{gather*}
\vec{OA}=\begin{pmatrix}
4 \\
2 \\
1
\end{pmatrix} \qquad  \vec{OB} = \begin{pmatrix}
2+\lambda \\
-3-3\lambda \\
2\lambda
\end{pmatrix}  \\ \\
\vec{AB} = \begin{pmatrix}
-2+\lambda \\
-5-3\lambda \\
-2\lambda-1
\end{pmatrix} \\ \\
\begin{pmatrix}
-2+\lambda \\
-5-3\lambda \\
-2\lambda-1
\end{pmatrix} \cdot \begin{pmatrix}1 \\ -3 \\ 2\end{pmatrix} = 0 \\ \\

-2+t-3(-5-3t)+2(2t-1)=0\\
-2+\lambda+(-5+9\lambda)+4\lambda-2=0\\
14\lambda=-11\\
\lambda=-\tfrac{11}{14}\\ \\
\therefore\ \overrightarrow{AB}=\begin{pmatrix}-\tfrac{39}{14}\\[4pt]-\tfrac{53}{14}\end{pmatrix}\\ \\
d=\dfrac{\sqrt{4186}}{14}

\end{gather*}
$$


## Reflecting a point in a line
To reflect a point in a line you must work out the perpendicular vector $\vec{AB}$ from the line to the point and then add the the vector twice from the start point such the reflected point $\vec{OC}=\vec{OA}+2\vec{AB}$

# Shortest distance between skew lines
To workout the shortest distance between skew lines you must work out the perpendicular distance between the direction vectors between 