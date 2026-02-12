A 'uniform framework' is made form uniform rods. It may be that is bent out a single piece of wire.

The centre of mass of each rod is at its centre. So we can Just treat these as point masses proceed as normal.

Each rod has mass per unit length $\rho$. If the framework is uniform, these will all cancel and we can just consider length.

# Centres of mass for component frameworks

## Circular arcs
![[Pasted image 20260207212838.png]]
A framework arc with radius $r$, and angle $2\alpha$ will have its CoM at:
$$
\frac{r\sin\alpha}{\alpha} \ \ \text{From O}
$$
# Example 1
A uniform rod is bent into a uniform triangular framework ABC. Find the distance of the centre of mass of the framework from BC.
![[Pasted image 20260212173437.png]]

For this problem, firstly set up the table for the component rods:

When dealing with diagonal line frameworks. It is good to treat them as right angle triangles with their respective x and y and components.:

![[Pasted image 20260212174450.png]]

Therefore the vertical component of the centre of mass from BC is 2a. 

| Object      | Length BA | Length BC | Length AC | Total     |
| ----------- | --------- | --------- | --------- | --------- |
| Length      | 5a        | 6a        | 5a        | 16a       |
| CoM from BC | 2a        | 0         | 2a        | $\bar{y}$ |
Now form the equations:
$$
\begin{gather*}
5a(2a) + 6a(0) + 5a(2a) = 16a\bar{y} \\ \\
10a^{2} + 10a^{2} = 16a\bar{y} \\ \\
20a = 16\bar{y} \\ \\
\therefore \bar{y} = \frac{5}{4}a
\end{gather*}
$$Thus the centre of mass is $\frac{5}{4}a$ from BC.

# Example 2
ABCDE is bent out of a uniform rod. Find the position of the centre of mass from the origin, A. Give your answer to 3 significant figures.
![[Pasted image 20260212174737.png]]

Firstly in this problem, we need to deal with sector BCD. 
From the sector we can see that it has angle $\theta= \frac{\pi}{2}$, thus $\alpha= \frac{\pi}{4}$. Therefore the this distance of the centre of mass can be calculated diagonally from origin $B$ using $d = \frac{r\sin\alpha}{\alpha}$
$$
d = \frac{r\sin\alpha}{\alpha} = \frac{3a\left( \sin \frac{\pi}{4} \right)}{\frac{\pi}{4}} = \frac{6\sqrt{ 2 }a}{\pi}
$$
Now we now that the angle $\alpha$ is $\frac{\pi}{4}$ thus $d\cos\alpha = d\sin\alpha$. Therefore we can solve for $G_{x}$ and $G_{x}$ using $d\sin\alpha$:
$$
G_{x} = G_{y} = d\sin \frac{\pi}{4} = \left( \frac{6\sqrt{ 2 }a}{\pi} \right)\sin \frac{\pi}{4} = \frac{6a}{\pi}
$$
As the problem does not state to find the centre of mass from a specific side of the framework, it is suitable to give the centre of mass as a coordinate.:
$$
\therefore G = \begin{pmatrix}
\frac{6a}{\pi} \\
\frac{6a}{\pi}
\end{pmatrix}
$$

Now we can commence to find the rest of the centre of masses of the basic uniform lengths:

| Object | Length AC                                         | Arc DC                                                                              | Length ED                              | Length AE                                       | Total                                            |
| ------ | ------------------------------------------------- | ----------------------------------------------------------------------------------- | -------------------------------------- | ----------------------------------------------- | ------------------------------------------------ |
| Length | 7a                                                | $\frac{3\pi}{2}a$                                                                   | 4a                                     | 3a                                              | $\frac{3\pi + 28}{2}a$                           |
| CoM    | $\begin{pmatrix} \frac{7}{2}a \\ 0 \end{pmatrix}$ | $\begin{pmatrix} \left( 4 + \frac{6}{\pi} \right)a \\ \frac{6}{\pi}a \end{pmatrix}$ | $\begin{pmatrix}2a \\ 3a\end{pmatrix}$ | $\begin{pmatrix}0 \\ \frac{3}{2}a\end{pmatrix}$ | $\begin{pmatrix}\bar{x} \\ \bar{y}\end{pmatrix}$ |

Remember that the length of an arc is given by:
$$
\begin{gather*}
l = r\theta = 3a\left( \frac{\pi}{2} \right)  \\ \\
\therefore l = \frac{3\pi}{2}a
\end{gather*}
$$

For these types of problems, the hardest thing is to ensure that the numbers for the centres of mass a correct. Be sure to read of the diagram correctly and consider additional distance from the origin. As well as that take a little more time to ensure that value calculated is correct and  that what your wrote down is right too. 

Form the equations. Ensure that you write down the correct values and do not slip up on rearranging:
$$
\begin{gather*}
7a \begin{pmatrix}
\frac{7}{2}a \\
0
\end{pmatrix} + \frac{3\pi}{2}a\begin{pmatrix}
\left( 4 + \frac{6}{\pi} \right)a \\
\frac{6}{\pi}a
\end{pmatrix} + 4a\begin{pmatrix}
2a \\
3a
\end{pmatrix} + 3a\begin{pmatrix}
0 \\
\frac{3}{2}a
\end{pmatrix} = \frac{3\pi+28}{2} \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
\frac{83+12\pi}{28+3\pi} \\
\frac{51}{28+3\pi} 
\end{pmatrix} = \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix}
\end{gather*}
$$