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

| Object | Sqr. EDAB                                                      | Sqr. FAGC                             | Total                                              |
| ------ | -------------------------------------------------------------- | ------------------------------------- | -------------------------------------------------- |
| Mass   | $9a^{2}\rho$                                                   | $9a^{2}\rho$                          | $18a^{2}\rho$                                      |
| CoM    | $\begin{pmatrix}  \frac{3}{2}a  \\ \frac{3}{2}a \end{pmatrix}$ | $\begin{pmatrix}4a \\ a\end{pmatrix}$ | $\begin{pmatrix}\bar{x}  \\  \bar{y}\end{pmatrix}$ |

Forming the equations:
$$
\begin{gather*}
9a^{2}\rho \begin{pmatrix}
\frac{3}{2}a \\
\frac{3}{2}a
\end{pmatrix} + 9a^{2}\rho \begin{pmatrix}
4a \\
a
\end{pmatrix} = 18a^{2} \rho \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
\frac{99}{2}a  \\
\frac{45}{a}a
\end{pmatrix} = 18 \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix}
\end{gather*}
$$
Therefore:
$$
\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} = \begin{pmatrix}
\frac{11}{4}a \\
\frac{5}{4}a
\end{pmatrix}
$$

![[Pasted image 20260207190257.png]]
The distance is just the magnitude of the centre of mass from the vertex of a.

$$
\begin{gather*}
d = \sqrt{ \left( \frac{11}{4}a \right)^{2} + \left( \frac{5}{4}a \right)^{2} } \\ \\
= \frac{\sqrt{ 146 }}{4}a
\end{gather*}
$$

# Example 3
A square uniform lamina has a corner folded over. 
Find the distance of the CoM from AD and AB.
![[Pasted image 20260207190651.png]]

For this question, you need to double area of the triangle as you need to consider the triangle have twice the width of paper as it has been folder over.

Therefore the area of the triangle go from $2a^{2}$ to $2(2a^{2}) = 4a^{2}$

| Object | Rect. AB                              | Sqr. DC                               | Trngl C                                                      | Total                                            |
| ------ | ------------------------------------- | ------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------ |
| Area   | $8a^{2}$                              | $4a^{2}$                              | $4a^{2}$                                                     | $16a^{2}$                                        |
| CoM    | $\begin{pmatrix}2a \\ a\end{pmatrix}$ | $\begin{pmatrix}a \\ 3a\end{pmatrix}$ | $\begin{pmatrix}  \frac{8}{3}a \\ \frac{8}{3}a\end{pmatrix}$ | $\begin{pmatrix}\bar{x} \\ \bar{y}\end{pmatrix}$ |

Writing up the formulae:
$$
\begin{gather*}
8a^{2}\begin{pmatrix}
2a \\
a
\end{pmatrix} + 4a^{2}\begin{pmatrix}
a \\
3a
\end{pmatrix} + 4a^{2}\begin{pmatrix}
\frac{8}{3}a \\
\frac{8}{3}a
\end{pmatrix} = 16a^{2}\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
\frac{92}{3}a  \\
\frac{92}{3}a
\end{pmatrix} = 16\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix}
\end{gather*}
$$
Therefore:
$$
\begin{pmatrix}
\bar{x} \\
\bar{y} 
\end{pmatrix} = 16a^{2} \begin{pmatrix}
\frac{23}{12}a \\
\frac{23}{12}a
\end{pmatrix}
$$
Thus the distance of the CoM from AD is $\frac{23}{12}a$ 
the distance of the CoM AB is $\frac{23}{12}a$

# Example 4
BCEF has mass per unit area $\rho$. ABF and CDE has mass per unit area $3\rho$. Find the distance of CoM from FE.
![[Pasted image 20260207200002.png]]

For this problem you must consider the densities and multiply the areas appropriately

| Object      | Sqr. FGBC     | ABF                               | ECD                               | Total     |
| ----------- | ------------- | --------------------------------- | --------------------------------- | --------- |
| Area        | $a^{2}$       | $3\left( \frac{a^{2}}{2} \right)$ | $3\left( \frac{a^{2}}{2} \right)$ | $4a^{2}$  |
| CoM from FE | $\frac{a}{2}$ | $\frac{2}{3}a$                    | $\frac{2}{3}a$                    | $\bar{y}$ |
Writing the respective formulae and solving for $\bar{y}$
$$
\begin{gather*}
a^{2} \begin{pmatrix}
\frac{a}{2}
\end{pmatrix} + \frac{3}{2}a^{2}\begin{pmatrix}
\frac{2a}{3}
\end{pmatrix} + \frac{3}{2}a^{2}\begin{pmatrix}
\frac{2a}{3}
\end{pmatrix} = 4a^{2}\bar{y} \\ \\ 
\bar{y} = \frac{5}{8}a
\end{gather*}
$$
The horizontal position of the CoM will be midpoint via symmetry. 