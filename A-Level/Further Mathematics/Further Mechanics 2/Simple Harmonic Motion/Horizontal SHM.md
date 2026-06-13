We have seen already that  when a particle is subject to a 'restoring force', proportional to its displacement and directed towards equilibrium position it oscillates in SHM:
$$
\begin{gather*}
\ddot{x} = -\omega^{2}x  \\ \\
\end{gather*}
$$
Where $\omega$ is the angular frequency of the oscillator and the period of oscillation is given by $T = \frac{2\pi}{\omega}$. 

The equation above has the solution:
$$
x = A\cos(\omega t) + B\sin\omega t
$$
Putting the equation in harmonic form gives:
$$
x = a\sin(\omega t + \phi)
$$
If the particle is released from maximum displacement, the equation of motion used is:
$$
x = A\cos\omega t
$$
If the particle is released from equilibrium position, the equation of motion of the particle is:
$$
x = A\sin\omega t
$$
## Velocity
To obtain an expression for velocity, we just differentiate $x$ with respect to time. Consider the case of a particle starting from maximum displacement:
$$
\begin{gather*}
x = A\cos\omega t \\ \\
v = \frac{dx}{dt} = -A\omega \sin\omega t
\end{gather*}
$$
Using the Pythagorean identity of $A\sin\omega t = \sqrt{ A^{2} -A\cos ^{2}\omega t }$. We can show that:
$$
\begin{gather*}
v = -\omega \sqrt{ A^{2}-A\cos ^{2}\omega t } \\ 
v = -\omega \sqrt{ A^{2}-x^{2} }
\end{gather*}
$$
Therefore:
$$
v^{2} = \omega^{2}(A^{2}-x^{2})
$$
This proves a couple of useful results:
- The particle's maximum velocity occurs at equilibrium position. 
 $$
V_{max} = a\omega
$$
- The velocity is zero at the maximum displacement, i.e when $x = a$. 

From the initial condition for SHM, the maximum acceleration occurs at $x=a$:
$$
a_{max } = a\omega^{2}
$$

## Horizontal spring-mass system
Consider a particle resting on a smooth horizontal surface. One end of a light elastic spring is attached to the particle and the other end is attached to a fixed point, A. 

The particle is now displaced to position $x_{0}$ from $O$, then released. Originally the particle is in equilibrium position.
![[Pasted image 20260613083136.png]]

Forming an equation of motion for the particle:
$$
\begin{gather*}
m\ddot{x} = -T \\ 
\ddot{x} = -\frac{\lambda x}{l} \\ \\ 
\ddot{x} = -\frac{\lambda x}{ml}
\end{gather*}
$$
This is in the form $\ddot{x} = -\omega^{2}x$, where $\omega = \sqrt{ \frac{\lambda}{ml} }$. The particle mass with moves with SHM about $O$. The particle oscillates with amplitude $a=x_{0}$. Hence:
$$
x = x_{0}\cos \sqrt{ \frac{\lambda}{ml}t }
$$

# Example 1
Particle P is attached to one end of an elastic spring of natural length $1.5m$ and modulus $12N$. P rests on a smooth horizontal surface and the other end of the spring is attached to a point $A$ on the same surface. The spring is extended to a length of $1.9m$, the released. 

Show that $P$ oscillates with SHM about its equilibrium position and state its period. 

Diagrammatically this can be represented as:
![[Pasted image 20260613091350.png]]
In the diagram, acceleration is defined acceleration in the positive right direction. 

From this, we can form an equation for SHM:
$$
\begin{gather*}
\frac{1}{2} \ddot{x} = - T \\ \\ 
\ddot{x} = -\frac{12x}{1.5} \ \\
\ddot{x} = -16 \\ \\
\therefore \omega = 4
\end{gather*}
$$
Thus the period can be found using $T = \frac{2\pi}{\omega}$:
$$
T = \frac{2\pi}{4} =\frac{1}{2}\pi
$$

## Example 1 Continued... 
Find the time during one complete oscillation for which $P$ is more than 0.3m from O. 

For this question, we must use the trigonometric equations of motion for the particle. As the particle is released from maximum displacement. We will use the equation of motion. $x = A\cos\omega t$. This gives the equation of motion of the particle to be:
$$
0.4\cos 4t
$$
To find the the time during which P is 0.3 from O, we must find the times at which the graph of $x=0.4\cos 4t$, intersects with the line equation $y = 0.3$:
![[Pasted image 20260613092155.png]]
$$
\begin{gather*}
0.4\cos 4t  = 0.3 \\ \\
\cos 4t = \frac{3}{4} \implies t = 0.1807 
\end{gather*}
$$
Thus by symmetry, $T = 4 \times 0.1807 = 0.723$.

# Example 2
A light elastic spring of natural length $2$ and modulus $15N$, lies on a smooth horizontal surface. One end is attached to a particle $P$ of mass $0.3kg$ and the other to a fixed point $A$. The spring is extended to $2.5$m then released. 

a) Show that $P$ moves with SHM and state its period
b) State the maximum speed and maximum acceleration of $P$. 
c) Find the during a complete oscillation for which the speed of $P$ is greater than $2ms ^{-1}$.

(a) Drawing a diagram for part a:
![[Pasted image 20260613093809.png]]
$$
\begin{gather*}
0.3 \ddot{x} = -T \\ \\
0.3\ddot{x} = -\frac{15}{2} x \\ \\
\ddot{x} = -25x 
\end{gather*}
$$
Therefore it is in the form $\ddot{x} = -\omega^{2}x$, thus the particle is in SHM with $T = \frac{2\pi}{5}$.

(b) For part b, recall that $a\omega = V_{max}$ and that $a_{max} = \omega^{2}$ :
$$
\begin{gather*}
v_{max} = a\omega = 0.5 \times 5 = 2.5 ms ^{-1} \\ \\
a_{max} = a\omega^{2} = 0.5 \times 25 = 12.5 ms ^{-1}
\end{gather*}
$$
(c) For part, c as the particle has been released from maximum displacement, the equation of it's motion can be given by:
$$
\begin{gather*}
x = 0.5\cos 5t  \\ \
\dot{x} = -2.5\sin 5t
\end{gather*}
$$
![[Pasted image 20260613094935.png]]

$$
\begin{gather*}
-2.5\sin 5t = -2  \\ \\
t = 0.1855 \\ \\
\end{gather*}
$$
Thus the total time during a complete oscillation in which the particle is above 2 is the period minus the 4 multiplied by the time above $2$ meters:
$$
T = \frac{2\pi}{5} - 4 \times 0.1855 = 0.515
$$

# Strings
With a spring, the particle perform complete oscillation as the spring can compress as well as extend. With a string, it only moves with SHM whilst the string is taut. Once the string foes slack, it moves at constant velocity, assuming a smooth surface. 

P(0.6) rests on a smooth horionztal surface. It is attached to an elastic string of nautral length $0.8m$ and modulus $16N$, the other end of which attached to a fixed point $A$. The string extended to 