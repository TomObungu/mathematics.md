Consider two vectors $\vec{a}$ and $\vec{b}$. The angle $\theta$ between them can be calculated by working out $|b|,|a|$ and $|a-b|$. 

Applying the cosine rule gives us:
$$
\begin{gather*}
\|a-b\|^2 = \|a\|^2 + \|b\|^2 - 2\|a\|\|b\|\cos\theta \\[6pt]
(a_x-b_x)^2+(a_y-b_y)^2+(a_z-b_z)^2 = a_x^2+a_y^2+a_z^2+b_x^2+b_y^2+b_z^2-2\|a\|\|b\|\cos\theta \\[6pt]
a_x^2-2a_xb_x+b_x^2 + a_y^2-2a_yb_y+b_y^2 + a_z^2-2a_zb_z+b_z^2 = \|a\|^2+\|b\|^2-2\|a\|\|b\|\cos\theta \\[6pt]
a_x b_x + a_y b_y + a_z b_z = \lvert \mathbf{a}\rvert \lvert \mathbf{b}\rvert \cos\Theta
\end{gather*}
$$
The LHS of the equation is expressed as $a\cdot b$. Therefore:
$$
a\cdot b=\lvert \mathbf{a}\rvert \lvert \mathbf{b}\rvert \cos\Theta
$$
The angle between two vectors can be calculated by:
$$
\cos\theta=\frac{a\cdot b}{\lvert \mathbf{a}\rvert \lvert \mathbf{b}\rvert }
$$

If $a\cdot b>0$ then the angle $\theta$ is acute. 
If $a\cdot b<0$ then the angle $\theta$ is obtuse.
## Example : 1
*Find the angle between points $A(8,-5,-4)$, $B(5,4,-1)$
$$
\begin{align*}
\vec{A}&=(8,-5,-4),\qquad \vec{B}=(5,4,-1)\\
\vec{A}\cdot\vec{B}&=8\cdot5+(-5)\cdot4+(-4)\cdot(-1)=24\\
\|\vec{A}\|&=\sqrt{8^2+(-5)^2+(-4)^2}=\sqrt{105},\qquad
\|\vec{B}\|=\sqrt{5^2+4^2+(-1)^2}=\sqrt{42}\\
\cos\theta&=\dfrac{\vec{A}\cdot\vec{B}}{\|\vec{A}\|\|\vec{B}\|}
=\dfrac{24}{\sqrt{105\cdot42}}=\dfrac{24}{\sqrt{4410}}=\dfrac{8}{7\sqrt{10}}\\
\theta&=\arccos\!\left(\dfrac{8}{7\sqrt{10}}\right)\approx68.81^\circ
\end{align*}
$$
---

The dot product only works when the vectors point away from the same starting point.

To make sure the angle is the correct angle. Calculate the vectors from the same starting point. i.e $\vec{AB}$ and $\vec{AC}$ and calculate the angle between them. 

Visually this looks like
![[Pasted image 20250911195924.png]]
## Example : 2
*Find the angle between points $A(7,6,2)$, $B(4,-1,3)$ and $C(-2,-1,4)$* 

$$
\begin{align*}
\overrightarrow{AB}&=(4-7,\,-1-6,\,3-2)=(-3,-7,1),\\
\overrightarrow{AC}&=(-2-7,\,-1-6,\,4-2)=(-9,-7,2),\\
\overrightarrow{AB}\cdot\overrightarrow{AC}&=(-3)(-9)+(-7)(-7)+1\cdot2=78,\\
\|\overrightarrow{AB}\|&=\sqrt{(-3)^2+(-7)^2+1^2}=\sqrt{59},\qquad
\|\overrightarrow{AC}\|=\sqrt{(-9)^2+(-7)^2+2^2}=\sqrt{134},\\
\cos\theta&=\dfrac{\overrightarrow{AB}\cdot\overrightarrow{AC}}{\|\overrightarrow{AB}\|\,\|\overrightarrow{AC}\|}
=\dfrac{78}{\sqrt{59\cdot134}}=\dfrac{39}{\sqrt{3953}},\\
\theta&=\arccos\!\left(\dfrac{39}{\sqrt{3953}}\right)\approx0.901\ \text{rad}\approx51.6^\circ.
\end{align*}
$$

# Perpendicular Vectors
If vectors are parallel then they are linear multiples of each other, e.g. $\begin{pmatrix}1 \\ 2 \\ -1\end{pmatrix} \parallel \begin{pmatrix}-4 \\ -8 \\ 4\end{pmatrix}$ as $$\begin{pmatrix}-4 \\ -8 \\ 4\end{pmatrix}=-4\begin{pmatrix}1 \\ 2 \\ -1\end{pmatrix}$$

If vectors are perpendicular, $\theta=90\ \ \therefore\cos\theta=0$
$$
\therefore a\cdot b=0
$$
Vectors are $\perp$ if their dot product = 0.

It is possible to find a variable within a vector if it is perpendicular with another vector by taking its dot product and solving for the variable (as dot product = 0).
## Example 1:
$$
\begin{align*}
\mathbf a &= 4\mathbf i - \mathbf j + 3\mathbf k,\\
\mathbf b &= 2\mathbf i + \lambda\mathbf j - \mathbf k,\\
\text{Find }\lambda\text{ such that }\mathbf a\perp\mathbf b:&\\
\mathbf a\cdot\mathbf b &= 4\cdot2 + (-1)\cdot\lambda + 3\cdot(-1) = 5-\lambda,\\
0 &= 5-\lambda \quad\Rightarrow\quad \lambda = 5.
\end{align*}
$$

# Using dot product for area
It is possible to workout $\cos\theta$ using the dot product when given a set of three points that form a triangle. 

Calculate the sides of the triangle by taking the magnitudes of the vectors from the point and then use the dot product.

Using $\cos\theta$ and $\frac{1}{2}AB\sin\theta$. The area of the given triangle can be calculated using $\sin\theta=\sqrt{ 1 - \cos ^{2}\theta }$ . Thus it possible to calculate the area without working out $\theta$:
## Example 1:
$$
A=\frac{1}{2}|A||B|\sqrt{ 1 - \cos ^{2}\theta }
$$
$$
\begin{align*}
A&=(1,1,3),\quad B=(2,-1,4),\quad C=(1,0,6)\\
\vec{AB}&=B-A=(1,-2,1)\\
\vec{AC}&=C-A=(0,-1,3)\\
\cos\theta&=\dfrac{\overrightarrow{AB}\cdot\overrightarrow{AC}}{\|\overrightarrow{AB}\|\,\|\overrightarrow{AC}\|} = \frac{5}{\sqrt{ 6 } \sqrt{ 10 }} = \frac{\sqrt{ 15 }}{6} \\ \\
A&=\frac{1}{2}\sqrt{ 6 } \sqrt{ 10 } \sqrt{ 1 - (\frac{\sqrt{ 15 }}{6} })^{2} = \frac{\sqrt{ 35 }}{2}
\end{align*}
$$
# Dot product Properties
The dot product is commutative:
$$
a\cdot b=b\cdot a
$$

The dot product is distributive:
$$
a(b\cdot c) =  a\cdot b + a\cdot c
$$
The dot product of a vector by itself is the magnitude of the vector squared:
$$
a\cdot a=a_{x}a_{x}+b_{x}b_{x}+c_{x}c_{x}=a_{x}^{2}+b_{x}^{2}+c_{x}^{2} = |a|^{2} 
$$

# Dot Product usage in projection
Consider $a\cdot b=|a||\hat{b}|\cos\theta$
![[Pasted image 20250911204650.png]]

The dot product gives the component of $a$ in direction of b. This is especially useful for future formulas such as the cross product on the general equation of a plane.

A negative scalar means the component of direction vector b is in the opposite direction of vector b.

![[Pasted image 20250911204811.png]]

Dotting with a vector with $i,j$ or $k$ will result in extracting the $i,j$ or k component.

Example 1:
*$a=3i+4j-2k$ b=$2i-7j+k$  Find the scalar component of a and the vector component of b*
$$
\begin{align*}
\mathbf{a} &= 3\hat{\mathbf{i}}+4\hat{\mathbf{j}}-2\hat{\mathbf{k}},\qquad 
\mathbf{b}=2\hat{\mathbf{i}}-7\hat{\mathbf{j}}+\hat{\mathbf{k}}\\
\mathbf{a}\cdot\mathbf{b} &= 3\cdot 2 + 4\cdot(-7) + (-2)\cdot 1 = -24\\
\|\mathbf{b}\| &= \sqrt{2^2+(-7)^2+1^2}=\sqrt{54}=3\sqrt{6}\\ \\
&\text{scalar component of }\mathbf{a}\text{ in direction }\mathbf{b} \\ \\
&= \frac{\mathbf{a}\cdot\mathbf{b}}{\|\mathbf{b}\|}=\frac{-24}{3\sqrt{6}}=-\frac{8}{\sqrt{6}}=-\frac{4\sqrt{6}}{3}\\
\end{align*}
$$
To calculate a vector component $b$ in $a$ . Multiply $a\cdot\hat{b}$ with $b$
$$
\begin{align*}
\text{vector component of }\mathbf{a}\text{ in direction }\mathbf{b}
&= \frac{\mathbf{a}\cdot\mathbf{b}}{\|\mathbf{b}\|^2}\,\mathbf{b}
= \frac{-24}{54}\,\mathbf{b}=-\frac{4}{9}\,(2\hat{\mathbf{i}}-7\hat{\mathbf{j}}+\hat{\mathbf{k}})\\
&= -\frac{8}{9}\hat{\mathbf{i}}+\frac{28}{9}\hat{\mathbf{j}}-\frac{4}{9}\hat{\mathbf{k}}
\end{align*}
$$
--- 
The dot product can be used to find the perpendicular distance from another point. 
