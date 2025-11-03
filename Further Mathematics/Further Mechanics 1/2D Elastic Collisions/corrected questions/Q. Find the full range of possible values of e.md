![[Pasted image 20251025095929.png]]
(a) Setting up the diagram. Remember that for a flat plane (parallel to either $i$ or $j$) you simply need to multiply the affected component by $-e$ to get the new component when dealing with vectors.
![[Pasted image 20251103085303.png]]
For this question you sort of just need to remember the gradient thing. Once you've seen a question like this before it's very easy.

In order for the ball to bounce off the wall $\vec{ST}$, the gradient of the velocity after the collision with $\vec{RS}$ needs to be less to the gradient of the wall $\vec{ST}$. It has to be less than as if it was equal to, then the motion would parallel to the wall. If was greater  it would not hit the wall at all.

You know that the gradient of the velocity after is $\frac{8e}{6}$

and the wall $\vec{ST}$ gradient is $\frac{1}{2}$ (as it is parallel to $(2i+j)$)

To find the range of values e you need form an inequality:
$$
\begin{gather*}
\frac{8e}{6} < \frac{1}{2} \\
8e < 3 \\ 
e < \frac{3}{8}
\end{gather*}
$$
As the ball does not coalesce with the wall afterwards we know that $e<0$ therefore:
$$
\boxed{0<e< \frac{3}{8}}
$$
(b) For the next question, simply follow the process of finding the unit vectors of the wall $\vec{ST}$ then taking the dot product between the incoming vector to find the components of the outgoing vector:

As well as that it is best to work out the vectors immediately given the value of $e$ to simplify calculations:
![[Pasted image 20251103091121.png]]

$$
\begin{gather*}
v_{1} = \begin{pmatrix}
6  \\
2
\end{pmatrix} \\ \\
\text{Unit vector for walls :} \\
\vec{ST}_{\parallel} = \frac{1}{\sqrt{ 5 }} \begin{pmatrix}
2 \\
1
\end{pmatrix} \qquad \vec{ST}
_{\perp} = \frac{1}{\sqrt{ 5 }}\begin{pmatrix}
-1 \\
2 
\end{pmatrix} \\ \\
v_{1\parallel} = \frac{1}{\sqrt{ 5 }} \begin{pmatrix}
2 \\
1
\end{pmatrix} \cdot \begin{pmatrix}
6 \\
2
\end{pmatrix} =  \frac{14\sqrt{ 5 }}{5} \\  \\
v_{1\perp} = \frac{1}{\sqrt{ 5 }}\begin{pmatrix}
-1 \\
2
\end{pmatrix} \cdot \begin{pmatrix}
6 \\
2
\end{pmatrix} = -\frac{2\sqrt{ 5 }}{5} \end{gather*} \\ \\
$$
Now form equations for $v_{2}$ by considering restitution:
$$
\begin{gather*}
v_{2\parallel} = v_{1\parallel} = \frac{14\sqrt{ 5 }}{5} \\ \\
v_{2\perp} = -\frac{1}{2}v_{1\perp} = -\frac{1}{2}\left( -\frac{2\sqrt{ 5 }}{5} \right) = \frac{\sqrt{ 5 }}{5}
\end{gather*}
$$
Finally multiply the components of $v_{2}$ by the parallel and perpendicular unit vectors of the wall $\vec{ST}$ and the result to for $v_{2}$:
$$
\begin{gather*}
v_{2} = \frac{14\sqrt{ 5 }}{5}\left( \frac{1}{\sqrt{ 5 }} \right)\begin{pmatrix}
2 \\
1
\end{pmatrix} + \frac{\sqrt{ 5 }}{5}\left( \frac{1}{\sqrt{ 5 }} \right)\begin{pmatrix}
-1 \\
2
\end{pmatrix} \\ \\ 
v_{2} = \begin{pmatrix}
\frac{27}{5} \\
\frac{16}{5}
\end{pmatrix} \\ \\
\therefore \boxed{v_{2} = \frac{27}{5}i+\frac{16}{5}j}
\end{gather*}
$$
