
Any linear transformation in three dimensions can be defined by the effect it has to the unit vectors $\begin{pmatrix}1 \\ 0 \\ 0\end{pmatrix}$ , $\begin{pmatrix}0 \\ 1 \\ 0\end{pmatrix}$ and $\begin{pmatrix}0 \\ 0 \\ 1 \end{pmatrix}$ 
For matrix $\mathbf{M}$:
$$
\begin{align*}
M&=\begin{pmatrix}a & b & c\\[4pt] d & e & f\\[4pt] g & h & i\end{pmatrix}
\end{align*}
$$

$$\begin{align*}
\begin{pmatrix}1\\[4pt]0\\[4pt]0\end{pmatrix}&\mapsto\begin{pmatrix}a\\[4pt]d\\[4pt]g\end{pmatrix},\qquad
\begin{pmatrix}0\\[4pt]1\\[4pt]0\end{pmatrix}\mapsto\begin{pmatrix}b\\[4pt]e\\[4pt]h\end{pmatrix},\qquad
\begin{pmatrix}0\\[4pt]0\\[4pt]1\end{pmatrix}\mapsto\begin{pmatrix}c\\[4pt]f\\[4pt]i\end{pmatrix},\\[6pt]
\end{align*}
$$

![[Pasted image 20250906143843.png]]
## Transformations
###  Reflections
- A reflection in the plane x = 0 is represented by matrix $\begin{pmatrix}-1  & 0 & 0\\ 0 & 1 & 0 \\ 0 & 0 & 1\end{pmatrix}$
  
- A reflection in the plane y = 0 is represented by matrix $\begin{pmatrix}1  & 0 & 0\\ 0 & -1 & 0 \\ 0 & 0 & 1\end{pmatrix}$

- A reflection in the plane z = 0 is represented by matrix $\begin{pmatrix}1  & 0 & 0\\ 0 & 1 & 0 \\ 0 & 0 & -1\end{pmatrix}$
  
### Rotations
[[Linear Transformations in Two Dimensions]] #rotations

- A reflection around the x-axis is represented by the matrix $$\begin{pmatrix}
1 & 0 & 0\\[4pt]
0 & \cos\theta & -\sin\theta\\[4pt]
0 & \sin\theta & \cos\theta
\end{pmatrix}$$
- A reflection around the y-axis is represented by the matrix
$$
\begin{pmatrix}
\cos\theta & 0 & \sin\theta\\[4pt]
0 & 1 & 0\\[4pt]
-\sin\theta & 0 & \cos\theta
\end{pmatrix}
$$
- A reflection around the z-axis is represented by the matrix
$$
\begin{pmatrix}
\cos\theta & -\sin\theta & 0\\[4pt]
\sin\theta & \cos\theta & 0\\[4pt]
0 & 0 & 1
\end{pmatrix}
$$

In all cases the, $\theta$ is the angle measured anticlockwise when facing the positive direction


