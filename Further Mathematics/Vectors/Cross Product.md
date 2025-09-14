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

## Worked example 1
![[Pasted image 20250914190606.png]]
$$
\begin{align*}
\vec{AC}&=\langle1,4,1\rangle,\qquad \vec{BC}=\langle-3,3,2\rangle\\
\vec{AC}\times\vec{BC}&=5\mathbf{i}-5\mathbf{j}+15\mathbf{k}= \langle5,-5,15\rangle\\
\text{Area}(\triangle ABC)&=\tfrac{1}{2}\|\vec{AC}\times\vec{BC}\|=\tfrac{1}{2}\cdot5\sqrt{11}=\tfrac{5\sqrt{11}}{2}
\end{align*}
$$

## Volume of a tetrahedron using cross product
For this you need to know that:
$$
\text{Volume of a pyramid } = \frac{1}{3} \frac{b\times w}{2} h = \frac{b \times w \times h}{6}
$$

For example if you are given vectors $\vec{A}$,$\vec{B}$,$\vec{C}$  relative to $O$ and you are asked to work the out the area of tetrahedron $OABC$ You must first work out the base of the tetrahedron using cross product of $\vec{OB}$ and $\vec{OC}$. Take the product and half the magnitude to get the are of the base as discussed earlier. 

However to get the volume you must take the dot product between $\vec{A}$ and $\vec{B}\vec{\times}\vec{C}$ and multiply 

### Why
This is because to work out the volume of the parallelised between the vectors $\vec{A}$, $\vec{B}$ and $\vec{C}$ you must calculate the component of the vecotor parallel to $\vec{B}$ and $\vec{C}$  to get the appropiate height of the parallelpiped:
![[Pasted image 20250914213034.png]]
![[Pasted image 20250914212025.png]]
# Right hand rule
It possible to deduce the direction the cross product ($\vec{p}$) will face by using your right hand. Point your index finger in the direction of $\vec{v}$  based on its coordinates in the 3D space and do the same for $\vec{w}$ with your middle finger and the direction of your thumb will the direction of the perpendicular vector $\vec{p}$
![[Pasted image 20250914185644.png]]
E.g.
![[Pasted image 20250914190145.png]]
![[Pasted image 20250914190159.png]]
Pointing your index vertically upwards towards the positive $\hat{j}$ direction and your middle finger towards the positive $\hat{i}$ direction and your thumb will face in the negative $\vec{k}$ direction. The magnitude of the vector will be equal to the parallelogram between $\vec{v}$ and $\vec{w}$ (which is actually a square as they are perpendicular). 
![[Pasted image 20250914190344.png]]