[[Linear Transformations in Two Dimensions]]

# Invariant points
Points that do not move under the given transformation are called invariant points.

You can see that after the linear transformation on the set of points that form the triangle, the point marked with red cross remains the same whilst the other points are reflected on the line x=1 and are shifted from their original location. 

In this case the transformation matrix would be: $\begin{pmatrix}-1  & 0\\ 0 & 1\end{pmatrix}$ and the matrix of points for the triangle would be: $\begin{pmatrix}1  & 3 & 2\\1 & 2 & 4\end{pmatrix}$

![[Pasted image 20251027100509.png]]

- For reflections in the y-axis and stretches parallel to the y-axis only, the invariant line has equation $x=0$ and y=k
- For reflections in the x-axis and stretches parallel to the x-axis only, the invariant line has equation $y=0$ and x=k
- For stretches in both the y-axis and x-axis the, there are no invariant lines and the only invariant point is the origin. 
- For rotations the only invariant point is (0,0)
- A reflection in the line y=x has invariant line with equation y=x and y=-x+k are invaraint
- A reflection in the line y=-x is represented as matrix has invariant line with equation y=-x and y=x+k

## Worked Example 1
$$
\begin{align*}
A &= \begin{pmatrix}
-\tfrac{1}{2} & -\tfrac{\sqrt{3}}{2} \\
\tfrac{\sqrt{3}}{2} & -\tfrac{1}{2}
\end{pmatrix}
\end{align*}
$$
*(a) Describe fully the single geometrical transformation U represented by the matrix A.

The transformation V, represented by the 2 x 2 matrix B, is a reflection in the line y = -x

(b) Write down the matrix B.

Given that U followed by Vis the transformation T, which is represented by the matrix C,

(c) find the matrix C.

**(d) Show that there is a real number k for which the point (1, k) is invariant under T.**

(d).
To find and invariant point. You must multiply the transformation matrix by the point and then equate the result to the point itself to form an equation. Form equations by comparing the result with the point itself then solve the equation for k.

$$
\begin{gather*}
\text{Matrix } \mathbf{C} = \begin{pmatrix}-\frac{\sqrt{ 3 }}{2} & \frac{1}{2} \\ \frac{1}{2} & \frac{\sqrt{ 3 }}{2}\end{pmatrix} \\ \\ \\ \begin{pmatrix}-\frac{\sqrt{ 3 }}{2} & \frac{1}{2} \\ \frac{1}{2} & \frac{\sqrt{ 3 }}{2}\end{pmatrix} \begin{pmatrix}
1 \\
k
\end{pmatrix} = \begin{pmatrix}
1 \\
k
\end{pmatrix} \\ \\

\begin{pmatrix}
-\frac{\sqrt{ 3 }}{2}+\frac{1}{2}k \\
\frac{1}{2}+\frac{\sqrt{ 3 }}{2}k 
\end{pmatrix} = \begin{pmatrix}
1 \\
k
\end{pmatrix} \\ \\ 
-\frac{\sqrt{ 3 }}{2}+\frac{1}{2}k = 1 \\ \\
k = 2+\sqrt{ 3 }

\end{gather*}
$$





# Invariant lines
For an invariant line under a linear transformation, every point must map **to another point on the same line**. For invariant lines, only the overall line equation is considered not the points themselves.

You can see that after the linear transformation has been applied, the the points are mapped onto a another set of points that lie on the same straight line:

![[Pasted image 20251027095648.png]]

You can see that differen

## Worked Example 1
![[Pasted image 20251027100832.png]]
For an invariant line to exist under the transformation $\begin{pmatrix}2 & -1 \\ -3 & 0\end{pmatrix}$. We only consider the line equation in form $y=mx+c$ to remain the same after the transformation. 

This means that the transformed $x$ coordinate will be mapped onto another coordinate $x'$, however if we substitute the different coordinate $x'$ into the same line with the same value of $m$(gradient) and $c$ (y-intercept), the line equation would still be equal as it is a different point on the same line. 


$$
\begin{pmatrix}
2 & -1 \\
-3 & 0
\end{pmatrix}\begin{pmatrix}
x \\
mx+c
\end{pmatrix} = \begin{pmatrix}
x' \\
mx'+c
\end{pmatrix}
$$
The first equation for $x'$ can be substituted into the second equation for $mx'+c$ by equating the coefficients of $x$ and the equating the constant terms
$$
\begin{gather*}
2x-mx-c = x' \ (1) \\
-3x = mx'+c\ (2)\\ \\
\text{Substitute } (1) \text{ into } (2) : \\ \\
-3x = m(2x-mx-c) + c \\ 
-3x = 2mx-m^{2}x-mc+c \\ 
m^{2}x-3x-2mx +mc-c=0 \\ 
(m^{2}-2m-3)x+(m-1)c = 0 
\end{gather*}
$$
Now this is the most important step, you need to compare the coefficients of $x$ on both sides:

You need to check if $m^{2}-2m-3=0$ and if $(m-1)c=0$ also equals zero

For the first case find the values of m from the equation $m^{2}-2m-3=0$:
$$
\begin{gather*}
m^{2}-2m-3 = 0 \\
m=3 \qquad m = -1
\end{gather*}
$$
With the values of $m$ found, substitute $m$ into $(m-1)c=0$:
$$
\begin{gather*}
\text{When } m = 3: \\
(3-1)c = 0 \\
2c = 0 \\
\therefore c = 0 \\ \\
\text{When } m = -1: \\
(-1-1)c = 0 \\ 
-2c = 0 \\ 
\therefore c = 0
\end{gather*}
$$
Therefore the invariant lines are
$$
y = 3x+0 = \boxed{y=3x} 
$$
when $m=3$,
And:
$$
y = -x+0=\boxed{y=-x}
$$
when $m=-1$

# Line of invariant points
A line of invariant points is when there is a set of invariant points after linear transformation and the these set of invariant points form a line.

You can see that for the red point on the green line with the large blue arching arrow, the same point is mapped onto another point on the same green line. This is an invariant line

However you can see that on the purple line, all those red points map to themselves after the linear transformation. You can see that if you were to draw a line through the points, those points form a uniform straight line. The equation of the line formed by the set of points is the line of invariant points. 
![[Pasted image 20251027105656.png]]


To find a line of invariant points, you need to check if the transformation matrix applied on  $\begin{pmatrix}x \\ y\end{pmatrix}$ will result in the same points $\begin{pmatrix}x \\ y\end{pmatrix}$
## Worked Example 1
Find the line of invariant points for the transformation given by $\mathbf{T} = \begin{pmatrix}7 & -2 \\ 6 & -1\end{pmatrix}$


To confirm if an invariant line is a a line of invariant points, you need to check if the invariant line written as a transformation matrix will yield the same points after its transformation matrix has been performed on the points $x,y$
## Worked Example 2
$$
\mathbf{M}=\begin{pmatrix}
4  & -5 \\
2 & -7
\end{pmatrix}
$$


Show that the line y = 2x is a line of fixed points under the transformation T.

To find the invariant line you must multiply the transformation matrix by the line represented as a linear transformation and then deduce whether the result matches the equation of the line

(c)
$$
\begin{gather*}
\begin{pmatrix}
4  & -5 \\
2 & -7
\end{pmatrix}\begin{pmatrix}
x \\
2x
\end{pmatrix} = \begin{pmatrix}
4x-10x \\
2x-14x
\end{pmatrix}
=\begin{pmatrix}
-6x \\
-12x
\end{pmatrix} \\ \\
y=-6x \ \ \ \ \ x = -12x \\
\implies y=2x \\ \\
\therefore \text{ All points on y=2x map to points on y=2x, hence the line is invariant.}
\end{gather*}
$$