[[Invariant points and lines]]
$$
\begin{align*}
&\text{Let }M=\begin{pmatrix}2 & 1\\[4pt] 2 & a\end{pmatrix},\qquad a\in\mathbb{R}.\\[6pt]
&(a)\ \ \text{Given that }M^{2}-5M=bI, \\ \\

&\quad b\in\mathbb{R},\ \text{find the value of }b\text{ and show that }a=3.\\[6pt]
&(b)\ \ \text{Determine the equations of the invariant lines of the linear transformation represented by }M.\\[6pt]
&(c)\ \ \text{Determine which, if any, of these are lines of fixed points.}
\end{align*}
$$
![[Pasted image 20250908170657.png]]

b) 
In this case a = 3.
For an invariant line $y=mx+c$, the points on the line are mapped to points on the same line.  In other words if $\begin{pmatrix}x \\ y\end{pmatrix}$ a point on the line, its image $\begin{pmatrix}x' \\ y'\end{pmatrix}$ must also be on the line.
$$
\begin{gather*}
\begin{pmatrix}
2 & 1 \\
2 & 3
\end{pmatrix}
\begin{pmatrix}
x \\
y
\end{pmatrix}=\begin{pmatrix}
x' \\
y'
\end{pmatrix} \\ \\
\begin{pmatrix}
2x & y \\
2x & 3y
\end{pmatrix} = \begin{pmatrix}
x' \\
y'
\end{pmatrix} \\ \\ 
2x + y = x' \\ 
2x + 3y = y'
\end{gather*}
$$
This also means $y'=mx'+c$. Thus substitute $y=mx+c$ into both equations
$$
\begin{gather*}
2x + (mx+c) = x' \\
2x + 3(mx+c) = y' \\ \\
(2+m)x + c = x' \\
(2+3m)x + 3c = y'
\end{gather*}
$$
Now substitute $x'$ and $y'$ back into $y'=mx'+c$ 
$$
\begin{gather*}
(2+3m)x + 3c = m((2+m)x+c) \\ \\ 
(2+3m)x + 3c = (2m+m^{2})x + mc + c
\end{gather*}

$$
Equation coefficients for both m and c. Do this by equating coefficients for x:
$$
\begin{gather*}
2+3m = m^{2}+2m \\ 
m^{2}-m-2 = 0 \\
(m-2)(m+1) = 0 \\ \\
m = 2 \qquad m=-1
\end{gather*}
$$
Now equate constant terms:
$$
\begin{gather*}
3c = mc + c \\
2c = mc \\ 
c(2-m) = 0 \\ 
\end{gather*}
$$
Finally find $c$ for each value of $m$ :
$$
m=2 \implies c(2-2) = 0 \implies 0c = 0 \implies c = 0 \\ \\
$$
So this means for $m=2$, and $c=0$

$y=2x+0=2x$ is an invariant line


$$
m=-1 \implies c(2--1) \implies 3c = 0 \implies c = 0
$$
So this means for $m=-1$ and $c=0$

$y=-x+c=-x$ is an invariant line