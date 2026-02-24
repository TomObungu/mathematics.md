## Uniform Angular Velocity and Speed
Consider a circle with centre $O$. A particle moves along the arc of the circle from point A to point B. Although the diagram is exaggerated, assume the angle that subtended the arc AB is an infinitesimally small angle $d\theta$
![[Pasted image 20260224105426.png]]
When considering the motion of the particle as it moves along the arc, the motion is always in the tangential direction to the path of the arc. 
![[Pasted image 20260224105644.png]]
Therefore, if we were to define the rate of change of the angle the particle travels across the circumference of the circle, we can define it as:
$$
\frac{d\theta}{dt}
$$
This is angular velocity and is denoted $\omega$. Note that the angular velocity only considers how much the angle changes per unit time. It does not consider the distance being travelled due to the size of the circle. Two particles may be travelling on different circles, with one having a large radius than the other, however both particles may be clearing the same the same angle through the circumference of the circle in the same amount of time.  Because of this, the particles will be travelling at the same angular velocity. However it is clearly evident that the particle moving on the larger radius has a greater velocity than the other. This is because it travels more distance in the same amount of time.

The actual distance being covered as the particle travels along the circumference of the circle is the particle's linear speed $v$. 

When a particle travels across an arc AB with angle $d\theta$. Its distance travelled is equal to to $r d\theta$. From the definition of speed, we know that $s = \frac{d}{t}$. Thus, the linear speed is defined as that distance, $r d\theta$, travelled over change in time, $dt$:
$$
v = \frac{d(r\theta)}{dt}
$$
Since $r$ is a constant, we can just pull out of the equation and we are left with the linear speed being equal to the radius of the circle, $r$ multiplied by the particle's angular velocity:
$$
\therefore v = r \frac{d\theta}{dt} = r\omega
$$
Thus, as a result of our derivations, we know that:
$$
\begin{gather*}
\omega = \frac{d\theta}{dt}  \text{ (Angular velocity) }  \\ \\
 v = r\omega \text{ (Linear speed) }
\end{gather*}
$$
We know that angle of one full revolution of a circle is $2\pi$. Thus we can find out the time taken to cover one full revolution of the circle, which the period $T$ of revolution, as:
$$
T = \frac{2\pi}{\omega} \text{ (Period of revolution )}
$$

## Uniform Acceleration
Consider the same particle travelling at a uniform speed $v$, around the same circular arc, subtending the angle $d\theta$. If We were to bisect the angle $d\theta$, and draw lines to signify the parallel and perpendicular components of the velocity, we would get something like this:
![[Pasted image 20260224112542.png]]
Remember all of this can only work because we are assuming that the angle $d\theta$ is infinitesimally small. By considering the diagram, we can see that at A:
$$
\begin{gather*}
V_{\parallel} = V\sin\left( \frac{d\theta}{2} \right) \text{ Outwards } \\ \\
V_{\perp} = V\cos\left( \frac{d\theta}{2} \right)
\end{gather*}
$$
And we can also see that at B:
$$
\begin{gather*}
V_{\parallel} = V\sin\left( \frac{d\theta}{2} \right) \text{ Inwards }\\ \\
V_{\perp} = V\cos\left( \frac{d\theta}{2} \right)
\end{gather*}
$$
We can see that only the parallel component has velocity has changed. It has changed direction. Going from moving outwards, to inwards:
![[Pasted image 20260224112825.png]]
This reversal or direction results is in a total change in velocity, $\Delta v$ of:
$$ 
\Delta V = V\sin\left( \frac{d\theta}{2} \right) --V\sin\left( \frac{d\theta}{2}  \right) = 2V\sin\left( \frac{d\theta}{2} \right)
$$
(Assuming we take left as positive to get only the magnitude of change)

Now here is where the assumption of $d\theta$ being infinitesimally small comes to play. Since $d\theta$, is small, we can use the small angle approximations $\sin\left( \frac{d\theta}{2} \right)$:
$$
\begin{gather*}
\therefore \sin\left( \frac{d\theta}{2} \right) = \frac{d\theta}{2}
\end{gather*}
$$
Therefore $\Delta V$ can be written as:
$$
\therefore \Delta V = 2V\left( \frac{d\theta}{2} \right) = Vd\theta
$$
Now we know from $\frac{d\theta}{dt} = \omega$, that:
$$
d\theta = \omega dt
$$
And  $v =\omega r$. Therefore:
$$
\Delta V = (\omega r)(\omega dt) = \omega^{2}r dt
$$
Dividing by $dt$ gives:
$$
\frac{\Delta V}{dt} = \omega^{2}r
$$
Writing $\frac{\Delta V}{dt}$, properly gives us:
$$
\frac{dv}{dt} = \omega^{2}r
$$
Now $\frac{dv}{dt}$, is rate of change of velocity, which is the definition of acceleration. Therefore:
$$
a = \omega^{2} r
$$
From $v = r\omega$, we can further write:
$$
a = \left( \frac{v}{r}\right)^{2}r = \frac{v^{2}}{r^{2}}r = \frac{v^{2}}{r}
$$
Therefore, the uniform acceleration of a particle travelling in circular motion is given as:
$$
a = \omega^{2}r \qquad a = \frac{v^{2}}{r}
$$

