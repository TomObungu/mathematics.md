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

