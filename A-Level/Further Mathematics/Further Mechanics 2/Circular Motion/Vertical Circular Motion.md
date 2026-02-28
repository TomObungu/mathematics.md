 Consider a particle moving in a vertical circular orbit of radius $r$,around a point $O$, with velocity $v$.
 ![[Pasted image 20260225190852.png]]
If we represent the the position of the particle in $i$ and $j$ vector notation, we can see that the function for the radius at time $t$ is defined by:
$$
r(t) = (r\cos\theta)i + (r\sin\theta)j
$$
From, the definition of velocity, the velocity of the particle is the derivative of $r(t)$ with respect to time. We can differentiate $r(t)$ implicitly:
$$
v(t) =  \dot{r}(t) = (-r\dot{\theta}\sin\theta )i + (r \dot{\theta}\cos\theta)j
$$
If we take the dot product between $v$ and $r$, $v \cdot r$:
$$
v \cdot r = -r^{2}\dot{\theta}\sin\theta \cos\theta + r^{2}\dot{\theta}\sin\theta \cos\theta =0
$$
We can see that their dot product is zero. This confirms that the velocity and radial vector and perpendicular as expected. 

If we want to find the acceleration of the particle, we must implicitly differentiate again:
$$
a(t) = \dot{v}(t) = \left[-r \dot{\theta}^{2}\cos\theta-r \ddot{\theta}\sin\theta \right]i + \left[-r\dot{\theta}^{2}\sin\theta+r \ddot{\theta}\cos \theta  \right]j
$$
If we factorise and group in terms of $\dot{\theta}$ and $\ddot{\theta}$, we get an expression for $a(t)$:
$$
a(t) = -\underbrace{ \left[r\cos\theta i+r\sin\theta j\right]  }_{ r }\dot{\theta}^{2} + \left[-r\cos\theta i+r\sin\theta j\right]\ddot{\theta}
$$
We can see from the above expression, we can simplify the expression to have an $r$ term:
$$
\begin{gather*}
a(t) = \underbrace{ -r \dot{\theta}^{2}\hat{r}  }_{ a_{1} } + \underbrace{ \left[-r\sin\theta i+r\cos\theta j\right] \ddot{\theta} }_{ a_{2} }
\end{gather*}
$$
Remember that $\vec{r}$ can be written as:
$$
\vec{r} = r\hat{r}
$$
Where $r$ is the magnitude of the vector.

Labelling the components of acceleration $a_{1}$ and $a_{2}$, we can examine each component.

For $a_{1}$, it is negative and is it is in the unit vector of $r$. This means it acts in the same radial direction towards the centre of the circle. 

If it acts towards the centre of the circle, it is the centripetal acceleration component. 

For $a_{2}$, if take the dot product between $a_{2}$ and $r$, we can see that:
$$
a_{2} \cdot r = 0
$$
Therefore $a_{2}$ is perpendicular to $r$ and is the tangential motion and can be expressed as:
$$
a_{2} = r \ddot{\theta}\hat{v}
$$

Therefore, as a whole, acceleration for vertical circular motion is both radial and tangential
$$
a = -r\dot{\theta}^{2}\hat{r} + r  \ddot{\theta}\hat{v}
$$

**This means that acceleration is not uniform for vertical circular motion**

## Instantaneous rest
For vertical circular motion, if the particle is instantaneously at rest, the component of $\dot{\theta} = \omega$ is 0. Therefore is no radial acceleration:
$$
\therefore r  \dot{\theta}^{2}\hat{r} = 0
$$
This means that the acceleration is purely tangential when the particle is instantaneously at rest. 



### Uniform acceleration
For vertical circular motion in uniform acceleration. Since the velocity is a constant, it will differentiate to an acceleration of $0$.Therefore the tangential component of acceleration will be 0 and thus acceleration will be purely radial when at instantaneous uniform vertical circular motion.


# Solving vertical circular motion problems

It is possible to solve problems involving vertical circular motion using conservation of energy and the centripetal acceleration formulae. It will predominantly involve equating kinetic and gravitational potential energies and solving for velocities. 
# Example 1
Consider a light rod of length $a$. The rod has a particle $P$ of mass $m$ attached to one end and the other end attached to a fixed point that allows pivotal rotation. The particle is projected downwards initially at speed $\sqrt{ 3ag }$. Find the tension when the mass at the lowest point. 
![[Pasted image 20260225203831.png]]

Using conservation of energy, we can equate initial kinetic energy and gravitational energy to the final kinetic energy:
$$
\begin{gather*}
E_{\text{start}} = E_{end} \\ \\
KE+GPE = KE \\ \\
 \frac{1}{2}m(3ag) + mga += \frac{1}{2}mv^{2} \\ \\
 5ag =v^{2} \\\
\end{gather*}
$$
Therefore the final velocity $v$ is:
$$
v = \sqrt{ 5ag }
$$
To find the tension, we need to use the centripetal force formula. We need to equate the centripetal force equation to the Tension in string at the bottom most in the vertical circular path:![[Pasted image 20260227162514.png]]

The total resultant force is $T-mg$. This is the centripetal force. We can equate this to the equation $F = \frac{mv^{2}}{r}$ and solve for $T$: Remember since the circle is still at the lowest point, we can use the velocity calculated in the previous part of the problem:
$$
\begin{gather*}
\frac{m(5ag)}{a} = T -mg \\ \\ 
5mg = T -mg \\ \\
\boxed{T = 6mg}
\end{gather*} 
$$

## Example 1 Continued...
Determine whether the particle P performs a full circular revolution around the circular path. 

For this problem you need to consider the forcing acting on the particle when it is as the top most vertical region of the circle. 

For questions like this the particle will continue its circular path if, the velocity, $v$, is greater than $0$ at the top. 
![[Pasted image 20260227162927.png]]
You can again use conservation of energy to calculate the velocity at the top by considering the energy at the bottom of the circle and at the top:
$$
\begin{gather*}
E_{\text{bottom}} = E_{\text{top}} \\ \\ 
KE = KE + GPE \\ \\ 
\frac{1}{2}m(5ag) = \frac{1}{2}mv^{2} + 2mga \\ \\
5ag = v^{2} + 4ag \\ \\
v = \sqrt{ ag }
\end{gather*}
$$

# Example 2
Consider a light rod of length $a$. The rod has a particle $P$ of mass $m$ attached to one end and the other end attached to a fixed point that allows pivotal rotation. The particle is projected downwards initially at speed $\sqrt{ \frac{3}{2}ag }$.  

Show that at angle $\alpha$, the tension in the rod, $T$, is equal to $3mg\sin\alpha + \frac{3}{2}mg$.
![[Pasted image 20260228141628.png]]

For this question we take the same approach of finding the velocity using conservation of energy and then equating the centripetal force formula to find $T$.

When considering conservation of energy, you need to correctly consider the change in height using the change in angle:
![[Pasted image 20260228142531.png]]
Now we have the change in height, we can then use conservation of energy:


$$
\begin{gather*}
E_{\text{start}} = E_{end} \\ \\
KE + GPE = KE \\ \\
\frac{1}{2}m\left( \frac{3}{2}ag \right) + mga\sin\alpha= \frac{1}{2}mv^{2} \\ \\
3a + 4ag\sin\alpha = 2v^{2} \\ \\
v^{2} = 2ag\sin\alpha + \frac{3}{2}ag
\end{gather*}
$$
Notice we do not need to take the square root as we will use $v^{2}$ for the following centripetal force formula. 

From the diagram we can see that the centripetal force is $T-mg\sin\alpha$
![[Pasted image 20260228143003.png]]


Now equating the centripetal force formula.
$$
\begin{gather*}
\frac{mv^{2}}{r} = T -mg\sin\alpha \\ \\
\frac{m\left( 2ag\sin\alpha + \frac{3}{2}ag \right)}{a} = T -mg\sin\alpha 
\end{gather*}
$$
Solving for $T$:
$$
\begin{gather*}
2mg\sin\alpha + \frac{3}{2}mg=T - mg\sin\alpha \\ \\ 
T = 3mg\sin\alpha + \frac{3}{2}mg \\ \\
QED
\end{gather*}
$$

## Example 2 Continued...
Find the magnitude and direction of the particle when it is at rest. 

When a particle is at rest, its velocity $v$ is at 0. Therefore we also know that $v^{2}$ will also be equal to 0. Equating $v^{2}$ to 0 gives us:
$$
\begin{gather*}
2ga\sin\alpha + \frac{3}{2}ag = 0 \\ \\ 
2\sin\alpha +\frac{3}{2} = 0 \\ \\
\sin\alpha = -\frac{3}{4}
\end{gather*}
$$
We know that (from taking $\arcsin$)
$$
\begin{gather*}
\alpha = -48.4903\dots ^\circ \\ \\
= 311.4096\dots ^\circ
\end{gather*}
$$
This can give us an inclination of what $\alpha$ would look like diagrammatically:
![[Pasted image 20260228144909.png]]
From this we can work the acute angle $\beta$. From the properties of angles, this acute angle $\beta$ will just be negation for $\sin\beta$. From that if we draw a triangle using the fact that $\sin \beta = \frac{3}{4}$, we can find out $\cos\beta$
![[Pasted image 20260228145430.png]]
Therefore:
$$
\sin \beta = \frac{3}{4} \qquad \cos\beta = \frac{\sqrt{ 7 }}{4}
$$
  Now recall for vertical circular motion, when an object is at rest, its acceleration is purely tangential:
  ![[Pasted image 20260228145617.png]]
  Thus magnitude of acceleration the particle is purely $mg\cos\beta$.:
  $$
\left| a \right| = mg\cos\beta = \frac{\sqrt{ 7 }}{4}mg
$$
The direction that the particle is travelling will be just be $\beta$, which can be worked out using $\arcsin$:
$$
\beta = \arcsin\left( \frac{3}{4} \right) = 48.6 ^\circ \text{ To the downard vertical}
$$

# Example 3
Consider a bead, $P$, threaded through a light circular wire of radius $a$. The bead is projected upwards initially at speed $\sqrt{ \frac{3}{2}ag }$.  

Show that at angle $\theta$,  $v^{2} = \frac{3}{2}ga -2ga\cos\theta$:
![[Pasted image 20260228153947.png]]
For this scenario, the centripetal force is provided by the normal reaction between the wire and the bead. 

However we can first find the velocity of the bead at angle $\theta$ using conservation of energy. As well as that we need to consider the change in height: 
$$
\begin{gather*}
E_{\text{start}} = E_{end} \\ \\
KE = KE +GPE \\ \\
\frac{1}{2}m\left( \frac{5}{2}ag \right) = \frac{1}{2}mv^{2} + mga\cos\theta \\ \\
\frac{5}{2}ag = v^{2} + 2ga\cos\theta \\ \\
v^{2} = \frac{5}{2}ag - 2ga\cos\theta \\ \\
QED
\end{gather*} 
$$
## Example 3 Continued...
Find the velocity of the bead when the reaction force of the bead is 0.  

Remember that $\theta$ is the angle at any arbitrary point on the circle. If we a draw a diagram of the component forces acting on the particle at the angle $\theta$, we can form equations for centripetal force:
![[Pasted image 20260228161101.png]]
As we have, $v$, we can form the equation for centripetal force using $v^{2}$:
$$
\begin{gather*}
\frac{mv^{2}}{r} = R +mg \cos\theta \\ \\
\frac{m\left( \frac{5}{2}ga - 2ga\cos\theta \right)}{a} = R + mg\cos\theta \\ \\
\end{gather*}
$$
Now since the reaction force is $0$, we can rearrange and solve for $\cos\theta$:
$$
\begin{gather*}
\frac{5}{2} -2\cos\theta = \cos\theta \\ \\
\cos\theta = \frac{5}{6}
\end{gather*}
$$
Substituting $\cos\theta$ into $v^{2}$:
$$
\begin{gather*}
v^{2} = \frac{5}{2}ga - 2ga\left( \frac{5}{6} \right) = \frac{5}{6}ga \\ \\ 
v = \boxed{\sqrt{ \frac{5ga}{6} }}
\end{gather*}
$$

# Example 4
Consider a light rod of length $a$. The rod has a particle $P$ of mass $m$ attached to one end and the other end attached to a fixed point that allows pivotal rotation. The particle is projected downwards initially at speed $u$. 

Show that at angle $\theta$, the tension in the string $T$, is $\frac{mu^{2}}{a}+mg(3\cos\theta-2)$
![[Pasted image 20260228163222.png]]

The thing you need to notice in this question is the difference in height for the change in angle $\theta$. 
![[Pasted image 20260228165725.png]]
The change in height $h$ will be:
$$
\begin{gather*}
h = a -a\cos\theta \\ \\
h = a(1-\cos\theta)
\end{gather*}
$$

From then we can find out $v^{2}$ using conservation of energy:
$$
\begin{gather*}
E_{\text{start}} = E_{\text{end}} \\ \\
KE  = KE + GPE \\ \\
\frac{1}{2}mu^{2} = \frac{1}{2}mv^{2} + mga(1-\cos\theta) \\ \\
u^{2} = v^{2} +2ga(1-\cos\theta) \\ \\
v^{2} = u^{2}+2ga(\cos\theta-1)
\end{gather*}
$$
We can now use the centripetal force formula to find $T$:
![[Pasted image 20260228170741.png]]
 
 $$
 \begin{gather*}
\frac{mv^{2}}{r} = T - mg\sin\theta \\ \\ 
\frac{m(u^{2} + 2ga(\cos\theta-1))}{a} = T - mg\cos\theta \\ \\
\frac{mu^{2}}{a} + 2mg(\cos \theta -1) = T -mg\cos\theta \\ \\
T = \frac{mus^{2}}{a} +mg(3\cos\theta -2) \\ \\
QED
\end{gather*}
$$
## Exampel 4 Continued...
Find $u$ for which the particles performs a complete circular revolution from its starting point. 

For this part of the problem, the particle will continue to do a full revolution if at the top most part of the circle, the tension in the string is greater than 0. We cannot use velocity as we do not know the initial velocity, $u$.

Considering the circle, the particle will be at the top of the circle when $\theta = \pi$:
