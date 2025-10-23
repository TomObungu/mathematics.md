An oblique collision of a particle with a fixed plane means that the particle does not collide with plane perpendicular to it. This means the particle will not collide in the direction of the normal to the plane. 

![[Pasted image 20251023173735.png]]

When a particle collides with a fixed plane obliquely, then the motion of the particle is affected $\perp$ to the plane. The motion of the particle $\parallel$ is unchanged:

![[Pasted image 20251023174011.png]]

If we do $\frac{2}{(1)}$ we get:
$$
\begin{gather*}
\frac{v\cos\beta}{v\cos \beta} = \frac{eu\sin\alpha}{u\cos\alpha} \\ \\
\therefore \tan\beta = e \tan \beta
\end{gather*}
$$
Now as $e\leq_{1}$, then:
$$
 \tan\beta < \tan\alpha 
$$
Therefore:
$$
\therefore \beta \leq \alpha
$$

## Angle of deflection:
The angle of deflection $\theta$, is the change in the direction from the direction it was moving to the new direction. 

Diagrammatically, if we sketched the direction vector of the particle and continued it's direction vector we can see that $\theta$ is equal to $\alpha+\beta$:
![[Pasted image 20251023175059.png]]

# Worked Example 1
![[Pasted image 20251023175258.png]]
If e = 1/3. Find $v$ and the angle![[Pasted image 20251023175258.png]] of deflection $\theta$:
From the diagram we know:
$$
\begin{gather*}
v\cos\theta = 5\cos 40 \\
v\sin\theta = \frac{1}{3}(5\sin 40) \\ \\
\therefore \tan\theta = \frac{\frac{5}{3}\sin_{4}0}{5\cos 40} \qquad \theta = 15.6 \\ \\
v^{2} = (5\cos 40)^{2} + \left( \frac{5}{3}\sin 40 \right)^{2} \\ 
v = 3.98 ms ^{-1}
\end{gather*}
$$
# Worked Example 1 Continued
Calculate the magnitude of impulse exerted on the particle by the wall. Particle has mass 0.3kg. 

Remember that the impulse only acts in the direction perpendicular to the plane so you must only consider the component perpendicular to the plane.
$$
\begin{gather*}
I = 0.3(v\sin\theta+5\sin_{4}0) \\
= 0.3(3.98\sin(15.6)+5\sin 40)
= 1.29Ns
\end{gather*}
$$

# Worked Example 2
A particle is dropped onto a smooth plane inclined at $30^\circ$ to the horizontal. Immediately before it hits the plane, it has speed $6ms^{-1}$. Immediately after rebounding, it has speed $4ms^{-1}$. Find the coefficient of restitution between the particle and the wall.

If the plane is inclined at 30 degrees. then if you draw the right angle triangle against the plane, the angle in the top corner of the triangle will also be $30^\circ$

Firstly interpret the diagram correctly:
![[Pasted image 20251023181556.png]]
From the diagram we can deduce:
$$
\begin{gather*}
4\sin\alpha = 6\sin 30 \\ 
4\sin\alpha = 6e\cos 30 \\
\end{gather*}
$$
We know that $4^{2} = (4\sin\alpha)^{2}+(4\cos\alpha)^{2}$. Therefore:
$$
\begin{gather*}
16 = 36\sin^2 30 + 36e^{2}\cos ^{2} 30 \\ 
\frac{16-36\sin ^{2} 30}{36\cos ^{2}30} = e^{2} \\ \\
\frac{7}{27} = e^{2} \\ \\
\therefore \boxed{\frac{\sqrt{ 21 }}{9}}
\end{gather*}
$$
# Worked Example 3
![[Pasted image 20251023192539.png]]
a) As we are given the motion of the particle as a vector, we need to find the components of the plane that are parallel to it and perpendicular to it.

As the plane is parallel to $i$, then the parallel component is just the $i$ component of the particle:
$$
v_{\parallel} = 2
$$
Restitution only occurs on the perpendicular component of the vector in collisions with a fixed plane, thus the perpendicular component of $v$ will be:
$$
v_{\perp} = -e(3)
$$
Always remember that when an object rebounds, it will be in the opposite direction, therefore it will be multiplied by $-e$. Therefore the vertical component of $v$ is:
$$
v_{\perp} = -\frac{1}{4}(3) = -\frac{3}{4}
$$
Thus the vector $v$ is:
$$
v=(2i-\frac{3}{4}j)ms^{-1}
$$
b) When given the vectors when dealing with 2D collisions, the best way to calculate the angle of deflection is to use the dot product between the two vectors. The dot product will yield the angle of deflection between the starting vector and ending vector:
![[Pasted image 20251023193417.png]]
$$
\cos\theta = \frac{\begin{pmatrix}
2 \\
3
\end{pmatrix}  \cdot \begin{pmatrix}
2 \\
-\frac{3}{4}
\end{pmatrix}}{\left|\begin{pmatrix}
2 \\
3
\end{pmatrix}
\right|\left|\begin{pmatrix}
2 \\
-\frac{3}{4}
\end{pmatrix}\right|} \qquad \theta = 76.9
$$
c) The KE lost is just difference in KE with the ending velocity and starting velocity:
$$
KE_{loss} = \frac{1}{2}(2)\left( (2^{2}+3^{2})-\left( 2^{2}+\left( \frac{3}{4} \right)^{2} \right) \right) =\frac{135}{16}J
$$

# Worked Example 3
For the cases when the plane is  not parallel to $i$ or $j$, but is defined by the direction of a vector.
![[Pasted image 20251023194123.png]]

You need find the unit vector components to the plane and take the dot product of the incoming vector. This will give you vertical and horizontal components of the incoming vector relative to the plane:

## Finding perpendicular vector in 2-D
To find the vector perpendicular to a 2D vector, simply switch the $i$ and $j$ components and make the $i$ component negative:
e.g. $(3i+4j)$ becomes $(-4i+3j)$. This can be especially useful for calculating the the impulse as the impulse is the perpendicular vector the plane of impact. 



$$
\begin{gather*}
U_{x} = \begin{pmatrix}
5 \\
1
\end{pmatrix}  \cdot \left( \frac{1}{\sqrt{ 5 }} \right)\begin{pmatrix}
1 \\
2
\end{pmatrix} = \frac{7\sqrt{ 5 }}{5} \\ \\
U_{y} = \begin{pmatrix}
5 \\
1
\end{pmatrix}  \cdot \left( \frac{1}{\sqrt{ 5 }} \right) \begin{pmatrix}
-2 \\
1
\end{pmatrix} = -\frac{9\sqrt{ 5 }}{5}
\end{gather*}
$$



