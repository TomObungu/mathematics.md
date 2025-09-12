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
# Worked Example 1
*Find a vector perpendicular to $a=2\hat{i}+7\hat{j}-3\hat{k}$ and $b=4\hat{i}=\hat{j}+2\hat{k}$*
$$
\begin{align*}
\mathbf{a}\times\mathbf{b}
&=\begin{vmatrix}
\hat{\imath} & \hat{\jmath} & \hat{k}\\
2 & 7 & -3\\
4 & -1 & 2
\end{vmatrix}\\
&=\hat{\imath}\bigl(1\cdot2-(-3)(-1)\bigr)-\hat{\jmath}\bigl(2\cdot2-(-3)\cdot4\bigr)+\hat{k}\bigl(2\cdot(-1)-1\cdot4\bigr)\\
&=-\hat{\imath}-16\hat{\jmath}-6\hat{k}. \\ \\
&=\begin{pmatrix}
-1 \\
-16 \\
-6
\end{pmatrix}
\end{align*}
$$


