[[Determinants]]
The cross product gives the vector that is perpendicular to two vectors. In 3D space it will look like this: 
![[Pasted image 20250911233002.png]]
The blue line represents vector a, the red line vector b and the green line is the cross product of a and b ($a \times b$). Which forms a right angle with both vectors.

The cross product is defined as:
$$
\mathbf{a}\times\mathbf{b} = (bf-ec)\,\hat{\mathbf{i}}-(af-dc)\,\hat{\mathbf{j}}+(ae-bd)\,\hat{\mathbf{k}}
$$
This values in the brackets are determinants of a larger a larger $3\times 3$ matrix Thus, To find the vector $\hat{i},\hat{j},\hat{k}$ that is perpendicular to two vectors $\begin{pmatrix}a  \\ b \\ c\end{pmatrix}$ and $\begin{pmatrix}d \\ e \\ f\end{pmatrix}$
$$
\begin{gather*}
\mathbf{a}\times\mathbf{b} = \begin{vmatrix} b & c\\ e & f \end{vmatrix}\hat{\mathbf{i}}
- \begin{vmatrix} a & c\\ d & f \end{vmatrix}\hat{\mathbf{j}}
+ \begin{vmatrix} a & b\\ d & e \end{vmatrix}\hat{\mathbf{k}}\\
= \begin{vmatrix} \hat{\mathbf{i}} & \hat{\mathbf{j}} & \hat{\mathbf{k}}\\
a & b & c\\
d & e & f \end{vmatrix}
\end{gather*}
$$
## Worked Example 1
*Find a vector perpendicular to $a=2\hat{i}+7\hat{j}-3\hat{k}$ and $b=4\hat{i}=\hat{j}+2\hat{k}$*
$$
\begin{align*}
\mathbf{a}\times\mathbf{b}
&=\begin{vmatrix}
\hat{\imath} & \hat{\jmath} & \hat{k}\\
2 & 7 & -3\\
4 & -1 & 2
\end{vmatrix}\\ \\
&= \mathbf{a}\times\mathbf{b} = \begin{vmatrix} 7 & -3\\ 1 & 2 \end{vmatrix}\hat{\mathbf{i}}
- \begin{vmatrix} 2 & -3\\ 4 & 2 \end{vmatrix}\hat{\mathbf{j}}
+ \begin{vmatrix} 2 & 7\\ 4 & -1 \end{vmatrix}\hat{\mathbf{k}} \\ \\
&=\hat{\imath}\bigl(7\cdot2-(-3)(-1)\bigr)-\hat{\jmath}\bigl(2\cdot2-(-3)\cdot4\bigr)+\hat{k}\bigl(2\cdot(-1)-7\cdot4\bigr)\\
&=11\hat{\imath}-16\hat{\jmath}-30\hat{k}. \\ \\
&=\begin{pmatrix}
11 \\
-16 \\
-30
\end{pmatrix}
\end{align*}
$$
It is possible to calculate the cross product using the Cross(u,v) function on the numworks calculator.

Swapping the rows in a matrix changes the sign of the determinant. Therefore this means:
$a\times b\neq b\times a$ (Non commutative)
$a\times b=-b\times a$ 
$-b\times a$ means the vector points in the opposite direction.


# Area Of a triangle using cross product
The cross product will produce a vector perpendicular to the vectors $\vec{v}$ and $\vec{w}$. The magnitude of the cross product will be equal to the parallelogram formed between $\vec{v}$ and $\vec{w}$. 
![[Pasted image 20250914185755.png]]
It is possible to calculate the area of a triangle using the cross product of two of sides as vectors. The area will be the the half magnitude of the cross product. This is because taking the cross product of vectors in 3D will be equal equal to half the area of the parellelogram. 
![[Pasted image 20250914185413.png]]

## Right hand rule
It possible to deduce the direction the cross product ($\vec{p}$) will face by using your right hand. Point your index finger in the direction of $\vec{v}$  based on its coordinates in the 3D space and do the same for $\vec{w}$ and the direction of your thumb will the direction of the perpendicular vector $\vec{p}$
![[Pasted image 20250914185644.png]]