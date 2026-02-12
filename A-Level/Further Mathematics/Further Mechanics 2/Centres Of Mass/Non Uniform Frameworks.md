# Example 1 
A framework is made form 5 uniform rods. AC, CE and EA have mass per unit length $\rho$. BD and DF has mass per unit length $2\rho$. Find the distance of the centre of mass from AC and AE. 
![[Pasted image 20260212181339.png]]

For this problem, it is much like the previous problems, however you must consider the densities when computing the lengths of the table. Simply multiply the length by its density when considering its length.

As well as that although we have been given the specific sides of the components of the centre of mass to be found, the sides can be considered as a 2D coordinate system with a vertical $y$ component and horizontal $x$ component. Thus, it is valid to give the centre of mass as a coordinate again.:

| Object | Length AC                             | Length EC                              | Length EA                             | Length FD                                          | Length DB                                        | Total                                            |
| ------ | ------------------------------------- | -------------------------------------- | ------------------------------------- | -------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| Length | 6a                                    | $\sqrt{ 72 } = 6\sqrt{ 2 }$            | 6a                                    | 6a                                                 | 6a                                               | ($24+6\sqrt{ 2 }$)a                              |
| CoM    | $\begin{pmatrix}3a \\ 0\end{pmatrix}$ | $\begin{pmatrix}3a \\ 3a\end{pmatrix}$ | $\begin{pmatrix}0 \\ 3a\end{pmatrix}$ | $\begin{pmatrix} \frac{3}{2}a \\ 3a \end{pmatrix}$ | $\begin{pmatrix}3a \\ \frac{5}{2}a\end{pmatrix}$ | $\begin{pmatrix}\bar{x} \\ \bar{y}\end{pmatrix}$ |
Thus form the equations again:
$$
\begin{gather*}
6a\begin{pmatrix}
3a \\
0
\end{pmatrix} + 6\sqrt{ 2 }\begin{pmatrix}
3a \\
3a
\end{pmatrix} + 6a\begin{pmatrix}
0 \\
3a
\end{pmatrix} + 6a\begin{pmatrix}
\frac{3}{2}a \\
3a
\end{pmatrix} + 6a\begin{pmatrix}
3a \\
\frac{3}{2}a
\end{pmatrix} = (24 + 6\sqrt{ 2 })a\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
45+18\sqrt{ 2 } \\
45 + 18\sqrt{ 2 }
\end{pmatrix}a = (24+6\sqrt{ 2 })\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
\frac{12}{7} +\frac{9\sqrt{ 2 }}{28} \\
\frac{12}{7} +\frac{9\sqrt{ 2 }}{28}
\end{pmatrix} = \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix}
\end{gather*}
$$

# Loaded frameworks
Sometimes, a framework or lamina may be 'loaded' with a point mass. When dealing with this, add the position and mass to the table. For example in the length column, treat the length of the mass as its value for mass.
![[Pasted image 20260212192442.png]]


