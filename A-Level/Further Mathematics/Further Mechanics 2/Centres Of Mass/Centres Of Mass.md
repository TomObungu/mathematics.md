So far in mechanics, we have only been working with point masses.

A real object has its mass distributed across its volume.

A centre of mass is a hypothetical point in an object where all the mass in concentrated. It is at this point where standard Newtonian laws can be applied to produce the same motion as if it where a point mass.

The centre of mass is the point in a force can be applied and the object experience linear acceleration with no rotational moment. 

![[Pasted image 20260120122251.png]]

A force through the centre of mass will cause linear acceleration with no rotational moment. However a force not through the centre of mass will cause linear acceleration plus a rotational moment with pivot around the centre of mass.

Consider masses situated a distance from origin $O$:
![[Pasted image 20260120122522.png]]
The masses do not need to be directly connected to share a centre of mass. Disconnected objects will still have a centre of mass.

This is important for things like in a solar system. Planets and solar systems orbit a common centre of mass. 

If we treat the origin $O$ as the axis of rotation. The masses $m_{1}$, $m_{2}$ and $m_{3}$ provide a moment around $O$. 

We can represent the cumulative moment of the masses $m_{1}$, $m_{2}$ and $m_{3}$ with a **single** mass $M$ at a single point to give the same effect as the moment these three masses would produce. This single point will be the centre of mass of the masses. 

![[Pasted image 20260120122939.png]]

This single point will have distance $\bar{x}$ from the origin and mass $M$ will be the sum of all the masses. 

Thus we can express this mathematically as:
$$
M\bar{x} = x_{1}m_{1}  + x_{2}m_{2} + x_{3}m_{3}
$$
Or more formally:
$$
\sum_{i=1}^{n}m_{i}x_{i} = \bar{x}\sum_{i=1}^{n}m_{i}
$$
Thus the point $\bar{x}$ will be the centre of mass. 

# Worked Example 1
Three masses, 2kg, 4kg and 3kg are positioned at (2,0), (5,0) and (1,0) respectively. Find the position of the centre of mass:
Using: $\sum_{i=1}^{n}m_{i}x_{i} = \bar{x}\sum_{i=1}^{n}m_{i}$:
$$
\begin{gather*}
2(2) + 4(5) + 3(1) = \bar{x}(9) \\
\bar{x} = 3
\end{gather*}
$$
Therefore the centre of mass is:
$$
(3,0)
$$

# Worked Example 2
A light rod PQ of length 2m, is loaded with particles 0.4kg, 0.6kg that are placed at P and R respectively, where $PR=0.5$. Find the value of a mass placed at $Q$ so that the centre of mass is at the midpoint of the rod:
Using: $\sum_{i=1}^{n}m_{i}x_{i} = \bar{x}\sum_{i=1}^{n}m_{i}$, but this time you solve for $M$ knowing that $\bar{x}=1$:
$$
\begin{gather*}
0(0.4) + 0.5(0.6) + 2(m) = (1)(0.4 + 0.6 + m) \\ \\
0.3 + 2m = 1 + m \\ \\ 
m = 0.7
\end{gather*}
$$
# 2D centres of mass
Working with centres of masses in 2D involves considering the distances from each axis and then writing the centre of mass as a point within the coordinate system.
![[Pasted image 20260120124248.png]]
Thus it is possible to treat the distances of each masses as vectors in the 2D plane and write the values of $x_{1}$, $x_{2}$ and $x_{3}$ as vector points:
$$
m_{1}\begin{pmatrix}
x_{1} \\
y_{1}
\end{pmatrix} + m_{2}\begin{pmatrix}
x_{2} \\
y_{2}
\end{pmatrix} + m_{3}\begin{pmatrix}
x_{3} \\
y_{3}
\end{pmatrix}  = M \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix}
$$
Or more formally:
$$
\sum_{i=i}^{n}m_{i}\begin{pmatrix}
x_{i} \\
y_{i}
\end{pmatrix}  = \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \sum_{i=1}^{n}m_{i}
$$

# Worked Example 3
Find the CoM of a 2kg mass (1,2), a 3kg mass at (3,1) and a 5kg mass at (4,3):
Using $\sum_{i=i}^{n}m_{i}\begin{pmatrix}x_{i} y_{i}\end{pmatrix}  = \begin{pmatrix}\bar{x} \\ \bar{y}\end{pmatrix} \sum_{i=1}^{n}m_{i}$
$$
\begin{gather*}
2\begin{pmatrix}
1 \\
2 
\end{pmatrix} + 3\begin{pmatrix}
3 \\
1
\end{pmatrix} + 5\begin{pmatrix}
4 \\
3
\end{pmatrix}  = 10\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
31 \\
22 
\end{pmatrix} = 10 \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
\bar{x} \\
\bar{y} 
\end{pmatrix} = \begin{pmatrix}
3.1 \\
3.2
\end{pmatrix}
\end{gather*}
$$
Therefore the centre of mass is at $(3.1,3.2)$

# Worked Example 4
Two particles of mass 3m and 2m are situated at (2,4) and (-1,3). Find a possible position for a particle of mass 5m such that centre of mass is at position (2,5)
This question is similar to example 2 but instead writing the missing point as a vector $\begin{pmatrix}x \\ y \end{pmatrix}$ and using $\sum_{i=i}^{n}m_{i}\begin{pmatrix}x_{i} y_{i}\end{pmatrix}  = \begin{pmatrix}\bar{x} \\ \bar{y}\end{pmatrix} \sum_{i=1}^{n}m_{i}$:
$$
\begin{gather*}
5m\begin{pmatrix}
x \\
y
\end{pmatrix} + 3m\begin{pmatrix}
2 \\
4
\end{pmatrix} + 2m\begin{pmatrix}
-1 \\
3
\end{pmatrix} = 10m\begin{pmatrix}
2 \\
5
\end{pmatrix} \\ \\
\begin{pmatrix}
5x \\
5y 
\end{pmatrix} + \begin{pmatrix}
4 \\
18
\end{pmatrix}  = \begin{pmatrix}
20 \\
50
\end{pmatrix}
\end{gather*}
$$
Therefore:
$$
\begin{pmatrix}
x \\
y 
\end{pmatrix} = \begin{pmatrix}
3.2 \\
6.4
\end{pmatrix}
$$
A possible position for the point 5m is (3.2, 6.4)

# Worked Example 5
Three particles off mass 2m, 5m and 3m are position at (3,2), (1,-2) and (a,2a). Find the value of a such that the centre of mass of the particles is the shortest distance from the origin O. 
Now there is multiple approaches to this problem. It is possible to solve it via the dot product or treating it as an optimisation problem.

## Optimisation approach:
Firstly writing out  $\sum_{i=i}^{n}m_{i}\begin{pmatrix}x_{i} y_{i}\end{pmatrix}  = \begin{pmatrix}\bar{x} \\ \bar{y}\end{pmatrix} \sum_{i=1}^{n}m_{i}$:n approach:
Firstly writing out 
$$
\begin{gather*}
2m\begin{pmatrix}
3 \\
2
\end{pmatrix} + 5m\begin{pmatrix}
1 \\
-2
\end{pmatrix}  + 3m\begin{pmatrix}
 a \\
2a
\end{pmatrix} = 10m\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
11 \\
-6 
\end{pmatrix} + \begin{pmatrix}
3a \\
6a
\end{pmatrix} = 10\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} 
\end{gather*}
$$
It is possible to now write $\bar{x}$ and $\bar{y}$ as a system of linear equations that represent and x-coordinate and y-coordinate:
$$
\begin{gather*}
\bar{x} = \frac{1}{10}(11+3a) \\ \\
\bar{y} = \frac{1}{10}(-6+6a)
\end{gather*}
$$
Now the distance $d$ from the origin is calculated from the distance formula $d = \sqrt{ \bar{x}^{2} + \bar{y}^{2} }$ thus:
$$
\begin{gather*}
d^{2} = \bar{x}^{2}+\bar{y}^{2} \\ \\
d^{2} = \left( \frac{1}{100} \right)\left((11+3a)^{2} + (-6+6a)^{2})\right)\\ \\
d^{2} = \frac{1}{100}(45a^{2}-6a+157)
\end{gather*}
$$


Now we can differentiate with respect to $d^{2}$ and set to it to 0 to work out a:
$$
\begin{gather*}
\frac{d(d^{2})}{da} = \frac{1}{100}(90a-6) = 0 \\ \\ 
90a - 6  = 0 \\ \\
\boxed{a  = \frac{1}{15}}
\end{gather*}
$$
