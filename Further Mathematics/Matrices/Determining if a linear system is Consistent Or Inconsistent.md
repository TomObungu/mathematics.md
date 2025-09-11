[[Determinants]] [[Solving Systems Of Equations Using Matrices]]
A system of linear equations is consistent if there is at least one set of values that satisfies all the equations simultaneously. Otherwise, it is inconsistent.

If the matrix corresponding to a set of linear equations is **non-singular, then the system has one unique solution and is consistent.**

However, if the matrix is singular, there are two possibilities: 
- The system is consistent and has infinitely many solutions (all three equations are in the same plane)
- Or it is inconsistent and has no solutions (Two or more parallel lines)
### Planes meet at one point
- Non-singular
- System of equations is consistent 
- Has one solution
- This solution is the only case when matrix is non-singular
## Planes form a sheaf
- Singular matrix
  - Consistent 
- Equations are linear multiples when eliminating variables
- Infinitely many solutions
## Two or more parallel planes
- Singular matrix
- Equations are linear multiples only in matrix not when eliminating variables
- Inconsistent (When eliminating variables the equations are not linear variables)
- No solutions
## Planes form a prism
- Singular matrix
- No linear multiples in matrix and when eliminating variables
- Inconsistent 
- No solutions
## All three equations represent same plane
- Singular matrix
- Consistent
- Infinitely many solutions. 

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

Thus the equation is consistent and the equations are linear multiples, thus the planes meet in a sheaf.
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
Equations (4) and (5) are inconsistent so the system is inconsistent and has no solutions thus the planes form a prism


