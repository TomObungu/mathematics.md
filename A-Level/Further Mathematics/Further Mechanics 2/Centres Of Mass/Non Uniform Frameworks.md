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

It is also possible to calculate the centre of mass of the **unloaded**
framework then consider the added masses after. 

In the example below, you will see that the 'length' of the mass is just its value of mass and the positions of the mass are treated as normal coordinates.

# Example 2
![[Pasted image 20260212194252.png]]
In this problem there is also an additional element of problem solving - You must calculate the density of the framework. 

The problem states the the total mass of the framework is $15kg$. Now you know that:
$$
\rho = \frac{m}{V}
$$
since we are dealing with frameworks, the 'volume' is just the total length of the uniform rods. In this case its just $3+4+5 = 12$ (as it is a '3,4,5', Pythagorean triplet triangle). Thus $\rho$ can be worked out to be:
$$
\rho = \frac{15}{12}
$$

Now this is important as you will need to multiply $\rho$ by the length of each rod when writing out the table. 

We will take the approach of calculating the unloaded frameworks centre of mass then considering the point masses after, however a table with point masses included will be shown as well.

As well as that the question does not specify the origin. In these problems, try and set the axis to the most convenient and what the question really inclines to.  It is not helpful that you need to figure it out on your own, however if the question shows a lot of frameworks that are going downwards, it would be beneficial to set downwards as positive. 

In this case let's consider AB as the x-axis and the down direction as the positive y-axis.

## Initial Unloaded Framework Table

Do not forget to multiply by $\rho$

| Object | Length AB                                        | Length AC                                        | Length BC                             | Total                                            |
| ------ | ------------------------------------------------ | ------------------------------------------------ | ------------------------------------- | ------------------------------------------------ |
| Length | $3\left( \frac{15}{12} \right)$                  | $5\left( \frac{15}{12} \right)$                  | $4\left( \frac{15}{12} \right)$       | 15 (as given)                                    |
| CoM    | $\begin{pmatrix}  \frac{3}{2} \\ 0\end{pmatrix}$ | $\begin{pmatrix} \frac{3}{2} \\ -2\end{pmatrix}$ | $\begin{pmatrix}3 \\ -2\end{pmatrix}$ | $\begin{pmatrix}\bar{x} \\ \bar{y}\end{pmatrix}$ |

Now form the equations for the unloaded framework:
$$
\begin{gather*}
\frac{45}{12}\begin{pmatrix}
\frac{3}{2} \\
0
\end{pmatrix} + \frac{75}{12}\begin{pmatrix}
\frac{3}{2} \\
-2
\end{pmatrix} + \frac{60}{12} \begin{pmatrix}
3 \\
-2
\end{pmatrix} = 15\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\

\end{gather*}
$$
