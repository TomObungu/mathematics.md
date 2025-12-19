
## Cross product method
To find the shortest distance between a line and a point. Calculate the general point $\vec{OR}$ on the line and take the cross product between the unit vector of the direction vector $\hat{b}$

This computation can be simplified into this equation 
$$
d = \left|\vec{OR} \times  \hat{b}\right|
$$


## Worked question 1
*In a crystallography experiment, a powerful laser is positioned at the origin point O. The laser is used to probe a specific atomic layer within a crystal. This layer is modelled as a plane with the equation:*
*$$
2x - y + 2z = 12
$$*
*where $x$, $y$, and $z$ are measured in nanometres.*
*To avoid damaging the crystal, the laser must be activated at a safe distance from this atomic layer.*
*Calculate the exact distance the laser must be from the atomic layer to ensure it is at the closest possible point of activation without intersecting it.*





## Old method
This is a special case that is does not follow the same procedure as [[Lines Distances]] in that to work out the shortest distance from a point to a line you must take the dot product between the general line formula and the point on the line. This is because the point will be $(0,0,0)$ thus the dot product will be 0 and you will be unable to solve for $\lambda$.

In order to work out the shortest distance from the line to the origin you must take the dot product between the general point on the line and direction vector of the line. This is because the shortest distance to the general point must be perpendicular otherwise the distance will be greater than the shortest distance for any point on the line segment $\vec{AB}$.
![[Pasted image 20250920104545.png]]

Therefore in this scenario the shortest distance is worked out bu taking the dot product between the general point and the direction vector of the line segment $\vec{AB}$.
$$
\begin{gather*}
\begin{pmatrix}
-3 + 8\lambda \\
6 + 5\lambda \\
8 - 4\lambda
\end{pmatrix} \cdot \begin{pmatrix}
8 \\
5 \\
-4
\end{pmatrix} = 0 \\ \\ 
-26 +  105\lambda = 0 \\
\lambda = \frac{26}{105} \\ \\
d = \left|\begin{pmatrix}
-\frac{107}{105}  \\
-\frac{152}{21}  \\
\frac{736}{105}
\end{pmatrix}\right| = \frac{11\sqrt{ 9345 }}{105}
\end{gather*}
$$


