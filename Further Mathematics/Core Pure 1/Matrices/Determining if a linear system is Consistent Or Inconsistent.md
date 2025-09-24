[[Determinants]] [[Solving Systems Of Equations Using Matrices]]
A system of linear equations is consistent if there is at least one set of values that satisfies all the equations simultaneously. Otherwise, it is inconsistent.

# $det(M) \neq 0$
If the matrix corresponding to a set of linear equations is **non-singular, then the system has one unique solution and is consistent.**

### Planes meet at one point
The geometric interpretation of a matrix system of equations being non-singular and consistent is the planes meeting at one point:
![[Pasted image 20250924163634.png]]

# $\det(M) = 0$
However, if the matrix is singular, there are two possibilities: 
- The system is consistent and has infinitely many solutions (all three equations are in the same plane)
- Or it is inconsistent and has no solutions 

# $\det (M) = 0$ & Consistent
### Planes form a sheaf
- If the the matrix equation is consistent i.e removing variable leads to equations that are linear multiples. Then the geometric interpretation is the planes forming a sheaf with a line of infinite solutions.
- No planes are parallel
![[Pasted image 20250924165705.png]]
### Planes lie in the same plane and overlap each other
- If the system's equations all have parallel normals
- The system of equations are consistent then the planes all overlap in the same plane.
![[Pasted image 20250924165952.png]]

## $\det (M) =0$ & Inconsistent
### Two parallel planes
- If the matrix has two planes that are parallel (share the same normal) then the system will form parallel planes with an intersecting plane
![[Pasted image 20250924171642.png]]
![[Pasted image 20250924171340.png]]
### Three parallel planes
- If all planes in the system of equations are parallel but the system is  inconsistent you will get 3 parallel planes
![[Pasted image 20250924171758.png]]
## Planes form a prism
- If none of the planes are parallel and the system is inconsistent you will get a prism
![[Pasted image 20250924171910.png]]

## Example 1
*For each of the following values of k, determine whether the system of equations is consistent or inconsistent. 

If the system is consistent, determine whether there is a unique solution or an infinity*
*of solutions. 

In each case, identify the geometric configuration of the planes corresponding to each*
*value of k.*

$$
\begin{gather*}
3x - ky - 6z = k \\
kx + 3y + 3z = 2 \\ 
-3x - y + 3z = -2 \\ \\
a. \ \ k= 0, \ \ &b. & k = 1, \ \ &c. \ \ k = -6
\end{gather*}
$$
a. 
$$
\begin{gather*}
k=0:\begin{vmatrix} 3 & 0 & -6  \\
0 & 3 & 3 \\
-3 & -1 & 3 \end{vmatrix}=-18
\end{gather*}
$$
The matrix is non-singular, thus the system has one unique solution and is consistent. The planes meet at a singular point.

b.
$$
k=1:\begin{vmatrix}
3 & -1 & -6 \\
1 & 3 & 3 \\
-3 & -1 & 3
\end{vmatrix} = 0
$$
The matrix is singular thus the equations need to be considered to determine if the system is consistent or inconsistent. Eliminate two variable from two different pairs of equations. If the resulting equations are consistent then the system will be consistent.
$$
\begin{gather*}
3x - y - 6z = 1 &(1)\\ 
x + 3y + 3z = 2 &(2)\\ 
-3x - y + 3z = -2 &(3)\\ \\
(1) + 2 \times (2): &5x + 5y = 5 &(4)\\
(2) - 3 \times (2): &4x + 4y = 4 &(5)
\end{gather*}
$$
Equations (4) and (5) are consistent because one in a linear multiple of the other. This is because equation (5) = $\frac{4}{5}$(4). 

Thus the equation is consistent and the equations are linear multiples $\implies$ The sytem is consistent.

However in the matrix system of the equations, none of the planes are paralell (they do not share the same normal). This means non of the planes are parallel, meaning the planes form a sheaf.
c.
$$
\begin{gather*}
k = -6: \begin{vmatrix} 3 & 6 & -6 \\ -6 & 3 & 3 \\ -3 & -1 & 3 \end{vmatrix} = 0 \\ \\
3x - y - 6z = 1 &(1)\\ 
x + 3y + 3z = 2  &(2)\\
-3x - y + 3z = -2 &(3)\\ \\
5x - 3z = -8 &(4)\\ 
15x - 9z = -10 &(5)
\end{gather*}
$$
Equations (4) and (5) are inconsistent so the system is inconsistent and has no solutions.
This means that the system of equations is inconsistent. Looking at the matrix system of equations, non the planes are parallel, this means the system forms prisim.


