[[Matrix Multiplication]] [[Invariant points and lines]]
You can define a transformation by describing how a general point with position vector $\begin{pmatrix} x \\ y \end{pmatrix}$  is transformed. 
$$T:\begin{pmatrix} x \\ y \end{pmatrix} \mapsto \begin{pmatrix} 2x - y \\ x + y \end{pmatrix}$$
$$T: \binom{2}{3} \mapsto \binom{2 \times 2 - 3}{2 + 3} = \binom{1}{5}$$

- Linear transformations always map the origin to itself
- Any linear transformations can be represented by a matrix
- The linear transformation $T:\begin{pmatrix} x \\ y \end{pmatrix}\mapsto \begin{pmatrix} ax + by \\ cx + dy \end{pmatrix}$ can be represented by matrix 

$$\begin{gather*}
\mathbf{M} = \begin{pmatrix} a & b \\ c & d \end{pmatrix}  \\ \\
\begin{pmatrix} a & b \\ c & d \end{pmatrix} \begin{pmatrix} x \\ y \end{pmatrix} = \begin{pmatrix} ax + by \\ cx + dy \end{pmatrix}
\end{gather*}$$

## Example 1
Find the matrices to represent these linear transformations
a. $$T: \begin{pmatrix} x \\ y \end{pmatrix} \mapsto \begin{pmatrix} 2y + x \\ 3x \end{pmatrix} \ \ \ \ \ \ \ \ \ \ \ \ \ \ V: \begin{pmatrix} x \\ y \end{pmatrix} \mapsto \begin{pmatrix} -2y \\ 3x + y \end{pmatrix}$$The transformation is equivalent to: 
$$T:\begin{pmatrix} x \\ y \end{pmatrix} \mapsto \begin{pmatrix} 1x + 2y \\ 3x + 0y \end{pmatrix}$$
so the matrix is:
$$
\begin{pmatrix}
1 & 2  \\
3 & 0
\end{pmatrix}
$$
## Example 2
a. The square S has coordinates (1, 1), (3, 1), (3, 3) and (1, 3). Find the vertices of the image of $S$ under the transformation given by the matrix $\mathbf{M} = \begin{pmatrix}-1 & 2 \\ 2 & 1\end{pmatrix}$
$$
\begin{gather*}
\text{The coordiantes can be represented by this matrix : } \\ \\
\begin{pmatrix}
1  & 3 & 3 & 1 \\
1 & 1 & 3 & 3
\end{pmatrix} \\ \\
\text{The veritces of the image S can be found by: } \\ \\
\begin{pmatrix}-1 & 2 \\ 2 & 1\end{pmatrix}\begin{pmatrix}
1  & 3 & 3 & 1 \\
1 & 1 & 3 & 3
\end{pmatrix} \\ \\ = \begin{pmatrix}
1 & -1 & 3 & 5 \\
3 & 7 & 9 & 5
\end{pmatrix}
\end{gather*}
$$
So the vertices of the image S lie at (1,3), (-1,7),(3,9),(5,5).

---
Any linear transformation can be described by effect it has on the unit vectors $\begin{pmatrix}1 \\ 0\end{pmatrix}$ and $\begin{pmatrix}0 \\ 1\end{pmatrix}$ 
$$
\begin{gather*}
M = \begin{pmatrix} a & b \\[4pt] c & d \end{pmatrix}\\ \\
M\begin{pmatrix}1\\[4pt]0\end{pmatrix} \mapsto \begin{pmatrix}a\\[4pt]c\end{pmatrix}\qquad
M\begin{pmatrix}0\\[4pt]1\end{pmatrix} \mapsto  \begin{pmatrix}b\\[4pt]d\end{pmatrix}
\end{gather*}
$$

## Transformations
- A reflection in the y-axis is represented by the matrix $\begin{pmatrix}-1 & 0 \\ 0 & 1\end{pmatrix}$ 
- A reflection in the x-axis is represented by the matrix $\begin{pmatrix}1 & 0 \\ 0  & -1\end{pmatrix}$ 
- A reflection in the line y=x is represented as matrix $\begin{pmatrix}0 & 1 \\ 1 & 0\end{pmatrix}$ 
- A reflection in the line y=-x is represented as matrix $\begin{pmatrix}0 & -1 \\ -1 & 0\end{pmatrix}$ 

### Rotations
#rotations
- The matrix representing a rotation through angle $\theta$ anticlockwise about the origin is $$
\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta
\end{pmatrix}
$$ The only invariant point is the origin $(0,0)$
## Example 1
$$\mathbf{M} = \begin{pmatrix} -\frac{\sqrt{2}}{2} & -\frac{\sqrt{2}}{2} \\ \frac{\sqrt{2}}{2} & -\frac{\sqrt{2}}{2} \end{pmatrix}$$
*a Describe geometrically the rotation represented by $\mathbf{M}$.

a
$$
\begin{gather*}
\cos 135 = -\frac{\sqrt{ 2 }}{2} \\
\sin 135 = \frac{\sqrt{ 2 }}{2}
\end{gather*}
$$
So $\mathbf{M}$ is a rotation anticlockwise, through 135 about (0,0)


## Enlargements
[[Determinants]]
- A transformation represented by the matrix $\begin{pmatrix}a & 0 \\ 0 & b\end{pmatrix}$ is a stretch of scale factor a parallel to the x-axis and a stretch scale factor b parallel to the y-axis
	- In the case here a=b, the scale factor is an enlargement with scale factor a
