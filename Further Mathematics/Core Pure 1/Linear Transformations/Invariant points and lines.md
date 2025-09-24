[[Linear Transformations in Two Dimensions]]
Points that do not move under the given transformation are called invariant points, and lines which do not move are called invariant lines.

- For reflections in the y-axis and stretches parallel to the y-axis only, the invariant line has equation $x=0$ and y=k
- For reflections in the x-axis and stretches parallel to the x-axis only, the invariant line has equation $y=0$ and x=k
- For stretches in both the y-axis and x-axis the, there are no invariant lines and the only invariant point is the origin. 
- For rotations the only invariant point is (0,0)
- A reflection in the line y=x has invariant line with equation y=x and y=-x+k are invaraint
- A reflection in the line y=-x is represented as matrix has invariant line with equation y=-x and y=x+k

## Example 1
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
## Example 2
$$
\mathbf{M}=\begin{pmatrix}
4  & -5 \\
2 & -7
\end{pmatrix}
$$
*(a) Show that the matrix M is non-singular.

The transformation T of the plane is represented by the matrix M.

The triangle R is transformed to the triangle S by the transformation T.

Given that the area of S is 63 square units,

(b) find the area of R.

**(c) Show that the line y = 2x is invariant under the transformation T.**

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




