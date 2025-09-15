To find the angle between an a plane, it possible to calculate the normal $\vec{n}$ of the plane first, if given it in non-scalar product form. However if you are given a plane in scalar product form, you use the normal vector from the formula first. 

## Why
The geometric interpretation of the angle is the angle between the direction vector $\vec{d}$ and the normal $\vec{n}$.  The angle can be calculated using the dot product:

$$
\cos\theta = \frac{\vec{d} \cdot  \vec{n}}{|\vec{d}||\vec{n}|}
$$



This is because the intersections between the normal, line and plane all form a right angle triangle.
![[Pasted image 20250915095225.png]]
The angle $<FED$ will be cos$\theta$.

The angle between the line and the plane will be the angle $<EDF$. The angle $\phi$ he line makes with the plane will be $\phi = 90 - \theta$ . 

However recall that:
$$
\cos(\theta - 90)= \sin\theta
$$
Therefore the angle between the line and the plane can be calculated using:
$$
\sin\theta = \frac{\vec{d} \cdot  \vec{n}}{|\vec{d}||\vec{n}|}
$$


## Worked Example 1
![[Pasted image 20250915095727.png]]
$$
\begin{gather*}
r=\begin{pmatrix}
-1 \\
2 \\
3
\end{pmatrix} + \lambda \begin{pmatrix}
2 \\
1 \\
-2
\end{pmatrix} \qquad \vec{n} = \begin{pmatrix}
2 \\
3 \\
-5
\end{pmatrix} \\ \\
\sin\theta = \frac{\vec{d} \cdot  \vec{n}}{}
\end{gather*}
$$