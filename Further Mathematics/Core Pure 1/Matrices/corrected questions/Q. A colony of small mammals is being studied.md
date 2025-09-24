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
c) With previous equation it is now possible to solve for given $B_{0}=25$
$$
40=2a(25)=50a\implies a=0.8
$$
