
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

## Initial unloaded framework table

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
\begin{pmatrix}
30 \\
-\frac{45}{2}
\end{pmatrix} = 15\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
2 \\
-\frac{3}{2}
\end{pmatrix} = \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix}
\end{gather*}
$$

### Considering masses 

Now consider the masses and their positions PLUS the **posotion and mass of the centre of mass of the unloaded framework as a singular coordinate and mass value**.

Still consider AB as the x-axis and the downward position as positive. 

For the position of the unloaded CoM, use the already worked out position of CoM in the previous table. 

| Object   | Mass A                               | Mass B                               | Mass C                                | Unloaded CoM                                    | Total                                            |
| -------- | ------------------------------------ | ------------------------------------ | ------------------------------------- | ----------------------------------------------- | ------------------------------------------------ |
| 'Length' | 10                                   | 20                                   | 30                                    | 15                                              | 75                                               |
| CoM      | $\begin{pmatrix}0 \\ 0\end{pmatrix}$ | $\begin{pmatrix}3 \\ 0\end{pmatrix}$ | $\begin{pmatrix}3 \\ -4\end{pmatrix}$ | $\begin{pmatrix}2 \\ -\frac{3}{2}\end{pmatrix}$ | $\begin{pmatrix}\bar{x} \\ \bar{y}\end{pmatrix}$ |

Now forming the equations:
$$
\begin{gather*}
10\begin{pmatrix}
0 \\
0
\end{pmatrix} + 20\begin{pmatrix}
3 \\
0
\end{pmatrix} + 30\begin{pmatrix}
3 \\
-4
\end{pmatrix} + 15\begin{pmatrix}
2 \\
-\frac{3}{2}
\end{pmatrix} = 75\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
180 \\
-\frac{285}{2}
\end{pmatrix} = 75\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\therefore \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} = \begin{pmatrix}
\frac{12}{5} \\
-\frac{19}{10}
\end{pmatrix}
\end{gather*}
$$

## Initial total loaded framework table with masses

An equivalent table with the point masses considered for their lengths as mass value and positions would have yielded the final answer in one go.

| Object   | Length AB                                        | Length AC                                        | Length BC                             | Mass A                               | Mass B                               | Mass C                                | Total                                            |
| -------- | ------------------------------------------------ | ------------------------------------------------ | ------------------------------------- | ------------------------------------ | ------------------------------------ | ------------------------------------- | ------------------------------------------------ |
| 'Length' | $3\left( \frac{15}{12} \right)$                  | $5\left( \frac{15}{12} \right)$                  | $4\left( \frac{15}{12} \right)$       | 10                                   | 20                                   | 30                                    | 75                                               |
| CoM      | $\begin{pmatrix}  \frac{3}{2} \\ 0\end{pmatrix}$ | $\begin{pmatrix} \frac{3}{2} \\ -2\end{pmatrix}$ | $\begin{pmatrix}3 \\ -2\end{pmatrix}$ | $\begin{pmatrix}0 \\ 0\end{pmatrix}$ | $\begin{pmatrix}3 \\ 0\end{pmatrix}$ | $\begin{pmatrix}3 \\ -4\end{pmatrix}$ | $\begin{pmatrix}\bar{x} \\ \bar{y}\end{pmatrix}$ |

Forming the equations and solving:
$$
\begin{gather*}
10\begin{pmatrix}
0 \\
0
\end{pmatrix} + 20\begin{pmatrix}
3 \\
0
\end{pmatrix} + 30\begin{pmatrix}
3 \\
-4
\end{pmatrix} + 15\begin{pmatrix}
2 \\
-\frac{3}{2}
\end{pmatrix} + 10\begin{pmatrix}
0 \\
0
\end{pmatrix} + 20\begin{pmatrix}
3 \\
0
\end{pmatrix} + 30\begin{pmatrix}
3 \\
-4
\end{pmatrix} = 75\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\ 
\begin{pmatrix}
180 \\
-\frac{285}{2}
\end{pmatrix} = 75\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\therefore \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} = \begin{pmatrix}
\frac{12}{5} \\
-\frac{19}{10}
\end{pmatrix}
\end{gather*} 
$$
