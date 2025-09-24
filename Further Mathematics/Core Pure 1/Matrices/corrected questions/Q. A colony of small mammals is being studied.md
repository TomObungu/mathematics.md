![[Pasted image 20250924182222.png]]
![[Pasted image 20250924182245.png]]
a) With these types of limitations, you mainly need to think of a logical flaw with the system whilst also applying the context of the scenario to the logic. In this case the most easy to deduce flaw with the system is the mammals/juviniles wont start breeding at exactly three years old.
![[Pasted image 20250924202139.png]]
b) For this question you need consider each case for when n = 0 (the start of the study) and equate the equations for when n = 1 to when n = 2. In this case the question states that at the start of the study, there are breeders only which we can denote as $B_{n}$. This means we can form an equation for when n = 0:
$$
\begin{gather*}
\begin{pmatrix}
N_{1} \\
J_{1} \\
B_{1}
\end{pmatrix} = \begin{pmatrix}
0 & 0 & 2 &  \\
a  & b  & 0 \\
0  & 0.48  & 0.96
\end{pmatrix} \begin{pmatrix}
0 \\
0 \\
B_{0}
\end{pmatrix} = \begin{pmatrix}
2B_{0} \\
0 \\
0.96B_{0}
\end{pmatrix}
\end{gather*}
$$
With n = 0 now giving the values for n = 1. We can form an equation to get the values of n = 2.
$$
\begin{gather*}
\begin{pmatrix}
N_{2} \\
J_{2} \\
B_{2}
\end{pmatrix} =\begin{pmatrix}
48 \\
40 \\
B_{2}
\end{pmatrix} = \begin{pmatrix}
0 & 0 & 2 &  \\
a  & b  & 0 \\
0  & 0.48  & 0.96
\end{pmatrix} \begin{pmatrix}
2B_{0} \\
0 \\
0.96B_{0}
\end{pmatrix} \\ \\
\begin{pmatrix}
48 \\
40 \\
B_{2}
\end{pmatrix} = \begin{pmatrix}
1.92B_{0} \\
2aB_{0} \\
0.9216B_{0}
\end{pmatrix}
\end{gather*}
$$
From this it is now possible to form a solvable equations for the number of breeders at the beginning of the study.
$$
\begin{gather*}
48 = 1.92B_{0} \\ \\
B_{0} = 25 \\ \\
\implies 25 \text{ breeders at the start of the study}\\ \\
\therefore \text{There were 25 mammals at the start of the study}
\end{gather*}
$$
(ii) With the previous equation it is now possible to solve for given $B_{0}=25$
$$
40=2a(25)=50a\implies a=0.8
$$
c) For this question, I got caught up in computation. For such things if it is convienient, I can use the pi trick on the numworks to check however try at least work out the determinant of the matrix and the matrix of minors. Overall advice, for future questions, it is better to divide the computation into smaller chunks and then use pi trick / numworks to speed up calculation. It is better to not become reliant on it. 
$$
\mathbf{M^-1} = \begin{pmatrix}
\frac{5}{4}b & \frac{5}{4} & -\frac{125}{48}b \\
-1 & 0 & \frac{25}{12} \\
\frac{1}{2} & 0 & 0
\end{pmatrix}
$$
d) With the value of $a$ calculated it is now possible to find b based on the given information and solving the matrix equation using its inverse
$$
\begin{gather*}
N_{n} + J_{n} +B_{n} = 1015 \\ \\
\begin{pmatrix}
596 \\
464 \\
437
\end{pmatrix} = \begin{pmatrix}
0 & 0 & 2 &  \\
0.8  & b  & 0 \\
0  & 0.48  & 0.96
\end{pmatrix} \begin{pmatrix}
N_{n}  \\
J_{n} \\
B_{n}
\end{pmatrix} \\ \\
\begin{pmatrix}
N_{n}  \\
J_{n} \\
B_{n}
\end{pmatrix} = \begin{pmatrix}
\frac{5}{4}b & \frac{5}{4} & -\frac{125}{48}b \\
-1 & 0 & \frac{25}{12} \\
\frac{1}{2} & 0 & 0
\end{pmatrix} \begin{pmatrix}
596 \\
464 \\
437
\end{pmatrix} = \begin{pmatrix}
580-\frac{18865}{48}b \\
\frac{3773}{12} \\
298
\end{pmatrix}
\end{gather*}
$$
Now with the values of $N_n$, $J_{n}$, $B_{n}$, it possible to substitute it back into the first equation for solve for b
$$
\begin{gather*}
1015 = 580-\frac{18865}{48}b + \frac{3773}{12} + 298 \\ \\
b = 0.45141696\\ \\
b\approx 0.45
\end{gather*}
$$
e)