A particle attached to the end of a light (and rigid) rod will perform a complete vertical circle if it has speed, $v$ $>0$ at the top of the circle

A small bead threaded through on to a smooth circular wire will perform complete vertical circles if it has speed, $v >0$ at the top of the circle

A particle attached to light (and rigid) string will perform vertical circles if the tension, $T>0$ at the top of the circle. This means the speed when it reaches the top of the circle must be large enough to keep the string taut at the top of the circle. 

If an object is not considered to stay on its circular path then as soon as the contact force associated with the circular path becomes  zero the object can be treated as a project moving freely under gravity. 

# Example 1
Consider a light inextensible string of length $a$, with a particle, $P$, of mass $m$ attached to it. The other end of the string is attached to a fixed point. The particle is projected at horizontal speed $\sqrt{ 3ag }$ such that the particle will move in vertical circular motion. Find the speed of the particle $v$, when the string becomes slack.

The string becomes once the particle has travelled some angle $\alpha$ and moves at that velocity $v$.
![[Pasted image 20260303091622.png]]

Finding the velocity $v$ using conservation of energy:
$$
\begin{gather*}
E_{\text{start}} = E_{\text{end}} \\ \\
KE = KE + GPE \\ \\
\frac{1}{2}m(3ag)  = \frac{1}{2}mv^{2} + mga(1 -\cos\alpha) \\ \\
3ag + 2ag(\cos\alpha -1) = v^{2} \\ \\
v^{2} = ag(2\cos\alpha + 1)
\end{gather*}
$$
Finding tension using centripetal:
$$
\begin{gather*}
\frac{mag(2\cos\alpha +1)}{a} = T - mg\cos\alpha \\ \\
T = mg(3\cos\alpha +1)
\end{gather*}
$$
The string is slack when Tension, $T$ is 0, thus we equate the equation above to 0:
$$
\begin{gather*}
T = mg(3\cos\alpha + 1 ) = 0 \\ \\
3\cos\alpha + 1 = 0 \\ \\
\cos \alpha = -\frac{1}{3}
\end{gather*}
$$
We now have an expression for $\cos\alpha$ which we can substitute back into $v$ to find the value of $v$ when string is slack:
$$
\begin{gather*}
v^{2} = ag(2\cos\alpha + 1) \\ \\
= ag\left( 2\left( -\frac{1}{3} \right) + 1 \right) \\ \\
= \frac{ag}{3} \\ \\ \\
v = \boxed{\sqrt{ \frac{ag}{3} }}
\end{gather*} 
$$

## Example 1 Continued...
Find the height above the centre of the circle $O$ reached by the particle 

We know that angle travelled $\alpha$ is obtuse from $\cos\alpha = -\frac{1}{3}$. We can label the acute version of the angle as $\beta$. Using this information we model the particle as moving freely under gravity and find the initial vertical component of velocity. 
![[Pasted image 20260303094031.png]]
It is possible to show the acute angle $\cos\beta$ for $\cos\alpha$ will just be the negation of $\cos\alpha$ due to properties of angles. From which we can construct a triangle and find $\sin\beta$.:
$$
\cos\beta = \frac{1}{3} \qquad \sin\beta = \frac{2\sqrt{ 2 }}{3}
$$
We can then find the initial vertical component of the projectile as it enters free fall, $V_{g}$. We know from the previous question, $v = \sqrt{ \frac{ag}{3} }$
$$
\begin{gather*}
V_{g} = V\sin\beta \\ \\
= \sqrt{ \frac{ag}{3} }\left( \frac{2\sqrt{ 2 }}{3} \right) = \sqrt{ \frac{8ag}{27} }
\end{gather*}
$$
Now we have the initial vertical velocity, we can use conservation of energy to find the final height with the initial velocity:
$$
\begin{gather*}
E_{\text{start}} = E_{end} \\ \\
KE = GPE \\ \\
\frac{1}{2}m\left( \frac{8ag}{27} \right) = mgh \\ \\
h = \frac{4a}{27}
\end{gather*}
$$
As the particle has move an obtuse angle $\alpha$, it has also moved a change in height. We can express the change in height in terms of the acute angle $a\cos\beta$.:
$$
\text{Max Height} = a\cos\beta + \frac{4a}{27} = \frac{a}{3} + \frac{4a}{27} = \boxed{\frac{13a}{27}}
$$


# Example 2
Consider a light inextensible string of length $l$, with a particle, $P$, of mass $m$ attached to it. The other end of the string is attached to a fixed point. The particle is projected from the top of the circle, at horizontal speed $\sqrt{ gl }$ such that the particle will move in vertical circular motion. The string will break if tension in the string exceeds $4mg$. Find the angle $\theta$ when this happens.

![[Pasted image 20260303095912.png]]
Finding the velocity, $v$, of the particle after it has travelled an angle $\theta$:
$$
\begin{gather*}
E_{\text{start}} = E_{end} \\ \\
\frac{1}{2}m(gl) + mgl(1-\cos\theta) = \frac{1}{2}mv^{2} \\ \\
gl + 2gl(1-\cos\theta) = v^{2} \\ \\
gl(3-2\cos\theta) = v^{2}
\end{gather*}
$$
Using centripetal force to calculate tension:
$$
\begin{gather*}
\frac{mgl(3-2\cos\theta)}{l} = T + mg\cos\theta \\ \\
T = mg(3-3\cos\theta)
\end{gather*}
$$
Equating the tension to $4mg$ and solving for $\theta$:
$$\begin{gather*}
mg(3-3\cos\theta) = 4mg \\ \\
\cos\theta = -\frac{1}{3} \\ \\
\theta = 109.47127\dots \\ \\
\theta = 109^{\circ}
\end{gather*}
$$

# Example 3
A particle of mass $2g$ moves from rest on a hemisphere of radius $0.5$. The particle travels angle $\theta$ around an arc of the hemisphere before losing contact with the hemisphere and moving as particle freely under gravity. Find the velocity, $v$, of the particle when it loses contact with the hemisphere. 

 
This time we will not be dealing with tension but normal reaction force as the centripetal force. 
![[Pasted image 20260303102032.png]]

Finding the velocity using conservation of energy:
$$
\begin{gather*}
E_{\text{start}} = E_{end}  \\ \\
GPE = KE \\ \\
2g 0.5(1-\cos\theta) = \frac{1}{2}2v^{2} \\ \\
v^{2} = g(1-\cos\theta)
\end{gather*}
$$
Finding the normal reaction using centripetal force:
$$
\begin{gather*}
\frac{2g(1-\cos\theta)}{0.5} = R - 2g\cos\theta \\ \\
4g(1-\cos\theta) = R - 2g\cos\theta \\ \\
R = g(4 +)
\end{gather*}
$$