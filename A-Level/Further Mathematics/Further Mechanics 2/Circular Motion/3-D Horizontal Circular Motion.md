 It is possible to use the method of resolving forces to solve problems involving objects moving in horizontal circles. 

# Example 1
Consider a conical pendulum formed of string of length $l$ and pendulum bob of mass $m$. The pendulum bob moves in uniform circular motion.:
![[Pasted image 20260224175154.png]]
Find the angular speed, $\omega$.

Approach this problem by labelling the angle subtended by the string and the vertical as $\theta$, the tension in the string as $T$ and the force due to the weight of the pendulum bob as $mg$:

In doing so, we can also find the components of the tension of the string:
![[Pasted image 20260224175628.png]]


Starting of by considering the horizontal and vertical components:
$$
T\cos\theta = mg
$$
Therefore we can rearrange for $T$:
$$
T = \frac{mg}{\cos\theta}
$$

From the diagram we can see that the centripetal force is the parallel component of the tension in the string. Thus:
$$
m\omega^{2}r = T\sin\theta
$$

From the diagram we can deduce that the radius of the string is $r = l\sin\theta$. Substituting these found out values
$$
\begin{gather*}
m\omega^{2}(l\sin\theta) = \frac{mg}{\cos\theta}\sin\theta  \\ \\
\omega^{2}l = \frac{g}{\cos\theta}
\end{gather*}
$$
Therefore:
$$
\omega = \sqrt{ \frac{g}{\cos\theta} }
$$

From this, we know that $\theta < 90$, otherwise there will not be any vertical component force in the string, $T\cos\theta$, to counter the weight force, $mg$.

# Example 2
Consider a light inextensible string threaded through a smooth ring of mass $mg$. The string has length $l$. One end of the string is attached to a fixed point $A$ and the other end of the string is attached to a fixed point B, such that A is vertically above B and $AB=3a$. 

The ring moves with constant angular speed $\omega$ in a horizontal circle with centre $A$. The string is taut and subtends an angle $\theta$ with downward vertical.:
![[Pasted image 20260224181437.png]]
Given that $\tan\theta = \frac{5}{12}$

Find the angular speed $\omega$:

In this problem, it is possible to  calculate rational values of $\sin\theta$ and $\cos\theta$, using the properties of $\tan\theta$.
![[Pasted image 20260224182103.png]]

Thus:
$$
\sin\theta = \frac{5}{13} \qquad \cos\theta = \frac{12}{13}
$$

Drawing the components of the string, we see that centripetal force is parallel component of the tension PLUS the overall tension of the string as it is threaded through the ring:
![[Pasted image 20260224181654.png]]

Thus by considering the horizontal and vertical components of force:
$$
\begin{gather*}
T\cos\theta = mg \\ \\
\frac{12}{13}T = mg 
\end{gather*}
$$Therefore we can calculate $T$:
$$
T = \frac{13}{12}mg
$$

Now we can consider the centripetal force. We know that the centripetal force will be equal to $T + T\sin\theta$:
$$
\begin{gather*}
m\omega^{2}r = T + T\sin\theta  \\ \\
\end{gather*}
$$
However we need to find $r$. Now from the diagram we can see that $\tan\theta = \frac{5}{12}$. If we label the missing value of $r$ as the opposite side, we can see that:
$$
\frac{r}{3a} = \frac{5}{12}
$$
Therefore we can find out r:
$$
r = 3a\left( \frac{5}{12}  \right) = \frac{5}{4}a
$$
Now we can substitute $r$ back into the centripetal force equation:
$$
\begin{gather*}
m\omega^{2}\left( \frac{5}{4}a \right) = T \left( 1 + \frac{5}{13} \right) \\ \\
m\omega^{2} \left( \frac{5}{4}a  \right) = \left( \frac{13}{12}mg \right)\left( \frac{18}{13} \right) \\ \\
\left( \frac{5a}{4} \right)\omega^{2}  = \frac{3}{2}g  \\ \\ 
\omega = \sqrt{ \frac{6g}{5a} }
\end{gather*} 
$$

# Example 3
Consider a looking at the rear view of car moving on an inclined rough plane like the one of a cycling rink. The car is inclined at $\theta = 10 ^\circ$ The car moves around a an arc on the rough plane, with arc of the circular path  containing a radius of 100m. Given that the car is moving at velocity, $v$, such that it does not slip up the plane and that the coefficient of restitution between the plane, $\mu$, is $0.2$.
![[Pasted image 20260224214819.png]]
Find the maximum speed, $v$, the car can move at.  

For this problem, we need to consider the normal reaction force $R$, the force of friction on the car $F_{r}$ and the force of weight from the car, $mg$.  

If the car is moving at maximum speed, the force of friction will act down the plane to prevent the car from slipping up the plane:
 ![[Pasted image 20260224215345.png]]

If we resolve the vertical forces:
$$
\begin{gather*}
R\cos10 - F_{r}\sin10 = mg
\end{gather*}
$$
We know that $F_{r} = \mu R\sin10$, thus we can write the equation in terms of $R$ on the left side:
$$
R(\cos10 - 0.2\sin 10) = mg \ (1)
$$

If we look at the horizontal force for centripetal force, we can see that:
$$
\begin{gather*}
\frac{mv^{2}}{r} = R\sin10 + F_{r}\cos10  \\ \\
\frac{mv^{2}}{r} = R(\sin10 + 0.2\cos10) \ (2)
\end{gather*} 
$$
Now it is possible to divide equation $(2)$ by equation $(1)$ in order to cancel out the mass of the car in the system:
$$
\frac{(2)}{(1)} = \frac{mv^{2}}{r mg} = \frac{R(\sin10+0.2\cos10)}{R(\cos 10-0.2\sin 10)}
$$
Therefore:
$$
\begin{gather*}
\frac{v^{2}}{100g} = \frac{\sin 10 + 0.2\cos 10}{\cos 10 - 0.2\sin 10} \\ \\
v = \sqrt{ \frac{\sin 10 + 0.2\cos 10}{\cos 10 - 0.2\sin 10}(100(9.8)) } = 19.6ms ^{-1}
\end{gather*}
$$

# Example 4
Consider a hollow right circular cone of base diameter $6a$ and height $4a$., with the axis vertical and its vertex pointing downwards.  A particle of mass $m$, moves in a horizontal circle on the rough inner surface of the cone with constant angular speed $\omega$.  The height of the particle is $2a$ above the vertex. Given that the angel between the greatest slope of the cone from the vertex and the horizontal plane is $\theta$ and the coefficient of restitution of the inner surface of the cone, $\mu$, is $\frac{1}{3}$
![[Pasted image 20260225055739.png]]
Find the minimum possible value of $\omega$. 

For this problem we will need to find out the angle $\theta$. From the diagram we can see that $\theta$ will subtend a right angle triangle with opposite side $4a$ and adjacent side $3a$ from the radius of the cone:
![[Pasted image 20260225055943.png]]

Therefore $\tan\theta = \frac{4}{3}$. With $\tan\theta$, it is the possible to find out rational definitions of $\sin\theta$ and $\cos\theta$:
![[Pasted image 20260225060119.png]]
Therefore:
$$
\sin\theta = \frac{4}{5} \qquad \cos\theta = \frac{3}{5}
$$
Now if we zoom into the particle and view the cross section of particle on the surface of the cone at a side view, we can see that the particle will again experience a reaction force $R$, a frictional force $F_{r}$ and the weight of the particle $mg$.

Now friction will be acting up the slope. This is because we are trying to find the minimum value of $\omega$ - any value smaller than this and the particle will slip down the slope. Thus friction is actively trying to prevent the particle from slipping down the slope at this value of $\omega$. 

![[Pasted image 20260225060836.png]]

From here, it is then possible to equate the vertical forces and the horizontal centripetal forces. 

Considering the vertical forces only:
$$
\begin{gather*}
R\cos\theta + F_{r}\sin\theta = mg \\ \\
R\left( \cos\theta + \frac{1}{3}\sin\theta \right) = mg \\ \\
R\left( \frac{3}{5} + \frac{1}{3}\left( \frac{4}{5} \right) \right) = mg \\ \\
\frac{13}{15}R = mg \\ \\
R = \frac{15}{13}mg
\end{gather*}
$$

Considering the horizontal centripetal forces only:
$$
\begin{gather*}
m\omega^{2}r = R\sin\theta - F_{r}\cos\theta  \\ \\
m\omega^{2}r = R\left(\frac{4}{5}-\frac{1}{3}\left( \frac{3}{5} \right) \right) \\ \\
m\omega^{2}r = \frac{3}{5}R 
\end{gather*}
$$
Now before we can continue using the centripetal force formulae, we must find out $r$. If we go back to our triangle with the opposite side being the height of the particle from the vertex, we know that $\tan\theta = \frac{4}{3}$. If we draw the adjacent side $r$, we can use the law of tangent to find out $r$:
![[Pasted image 20260225061539.png]]
$$
\begin{gather*}
\frac{2a}{r} = \frac{4}{3} \\ \\
 r = \frac{3}{2}a
\end{gather*}
$$
We can now substitute the value of $r$ back into the equation for centripetal force and solve for $\omega$.
$$
\begin{gather*}
\frac{3}{2}a\omega^{2}m = \frac{3}{5}R \\ \\
a\omega^{2}m = \frac{2}{5}R \\ \\
a\omega^{2}m = \frac{2}{5}\left( \frac{15}{13}mg \right) \\ \\
a\omega^{2} = \frac{6g}{13} \\ \\ 
\omega = \sqrt{ \frac{6g}{13a} }
\end{gather*}
$$

# Example 5
A thin hollow hemisphere, with centre O and radius $5a$, is fixed with its axis vertical. A particle of mass $m$,
