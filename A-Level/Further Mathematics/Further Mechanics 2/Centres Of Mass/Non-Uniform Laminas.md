# Example 1
The uniform lamina ABCDE is folded along line FC. 
![[Pasted image 20260207162055.png]]
After it being folded, the lamina becomes:
![[Pasted image 20260207162117.png]]

Find the distance of the CoM from EF and ED.

For this question you must set up a table in regards to the shape FEDGBC and consider the regions which have been folded over as additional shapes. 

| Object | Rect. FCGD                                       | Sqr. FCAG                                                   | Trgl CGB                                                     | Total                                            |
| ------ | ------------------------------------------------ | ----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------ |
| Area   | $2a^{2}$                                         | $a^{2}$                                                     | $\frac{a^{2}}{2}$                                            | $\frac{7}{2}a^{2}$                               |
| CoM    | $\begin{pmatrix} \frac{a}{2} \\ a \end{pmatrix}$ | $\begin{pmatrix}  \frac{a}{2} \\ \frac{3}{2}a\end{pmatrix}$ | $\begin{pmatrix} \frac{4}{3}a  \\ \frac{4}{3}a\end{pmatrix}$ | $\begin{pmatrix}\bar{x} \\ \bar{y}\end{pmatrix}$ |

Forming the fomulae:
$$
\begin{gather*}
2a^{2} \begin{pmatrix}
\frac{a}{2} \\
a
\end{pmatrix} + a^{2} \begin{pmatrix}
\frac{a}{2} \\
\frac{3}{2}a
\end{pmatrix} + \frac{1}{2}a^{2}\begin{pmatrix}
\frac{4}{3}a \\
\frac{4}{3}a
\end{pmatrix} = \frac{7}{2}a^{2} \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
\frac{13}{6}a \\
\frac{25}{6} 
\end{pmatrix} = \frac{7}{2} \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix}
\end{gather*}
$$
Thus:
$$
\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} = \begin{pmatrix}
\frac{13}{21}a \\
\frac{25}{21}a
\end{pmatrix}
$$
Thus the distance from EF $= \frac{13}{21}a$ and the distance from ED is $\frac{25}{21}a$.

# Non Uniform laminas
Sometimes, different parts of the lamina have different mass per unit area. We first have to take this into account in our table. 

# Example 2
![[Pasted image 20260207162953.png]]
ABDE has mass per unit area $\rho$
BCD has mass per unit area $2\rho$
Find the CoM of this shape by considering A as the origin. 

Set up the table for each component lamina but consider the mass with the density for each shape:

If given varying densities or given the mass only of an object.  Then 

| Object | Sqr. EDAB | Trngl DBC | Total |
| ------ | --------- | --------- | ----- |
| Mass   |           |           |       |
| CoM    |           |           |       |