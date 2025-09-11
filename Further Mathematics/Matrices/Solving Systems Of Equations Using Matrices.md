[[Inverting a 3 x 3 matrix]] [[Matrix Multiplication]] 
If $A\begin{pmatrix}x \\ y \\ z\end{pmatrix}=v$ then $\begin{pmatrix}x \\ y \\ z\end{pmatrix}$ = $A^{-1}v$
## Example 1
A use an inverse matrix to solve the simultaneous equations:
$$
\begin{gather*}
-x+6y-2z=21 \\
6x-2y-z=-16 \\
-2x+3y+5z=24
\end{gather*}

$$
Write the system of equations using matrices:
$$
\begin{gather*}
\begin{pmatrix}
-1 & 6 & -2 \\
6 & -2 & -1 \\
-2 & 3 & 5
\end{pmatrix} \begin{pmatrix}
x \\ y \\ z
\end{pmatrix} = \begin{pmatrix}
21 \\ -16 \\ 24
\end{pmatrix} \\ \\
 \begin{pmatrix}
x \\ y \\ z
\end{pmatrix} = \begin{pmatrix}
-1 & 6 & -2 \\
6 & -2 & -1 \\
-2 & 3 & 5
\end{pmatrix}^{-1}\begin{pmatrix}
21 \\ -16 \\ 24
\end{pmatrix} \\ \\
 \begin{pmatrix}
x \\ y \\ z
\end{pmatrix} = \begin{pmatrix}
-1 \\ 4 \\ 2
\end{pmatrix} \\
\text{Hence } x = -1, x = 4,z=2
\end{gather*}
$$
## Example 2
*A colony of 1000 mole-rats is made up of adult males, adult females and youngsters.
Originally there were 100 more adult females than adult males.
After one year:
. the number of adult males had increased by 2%
. the number of adult females had increased by 3%
. the number of youngsters had decreased by 4%
. the total number of mole-rats had decreased by 20
Form and solve a matrix equation to find out how many
of each type of mole-rat were in the original colony.

$$
\begin{gather*}
x = \text{number of adult males} \\
y = \text{number of adult females} \\
z = \text{number of youngsters} \\ \\
x +y+ z =  1000 \\
x+y+ 0z =  -100 \\
1.02x+1.03y+0.96z = 980 \\ \\
 \text{So}
 \begin{pmatrix}
1 & 1 & 1 \\
1 & -1 & 0 \\
1.02 & 1.03 & 0.96
\end{pmatrix} \begin{pmatrix}
x \\ y \\ z
\end{pmatrix} =  \begin{pmatrix}
1000 \\ -100 \\ 980
\end{pmatrix} \\ \\
\begin{pmatrix}
x \\ y \\ z
\end{pmatrix} =  A^{-1}\begin{pmatrix}
1000 \\ -100 \\ 980
\end{pmatrix} = \begin{pmatrix}
100 \\ 200 \\ 700
\end{pmatrix} \\ \\ 
\therefore \text{There were 100 adult males, 200 adult females and 700 youngsters in the original colony}
\end{gather*} 
$$
