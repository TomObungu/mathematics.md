Consider a spring-mass system and we consider positive displacement in the right direction.

![[Pasted image 20260118194913.png]]

When the mass has a positive displacement, it experiences a tension in the negative direction

When the mass on the spring has a negative displacement, it experiences a tension in the positive direction.

The spring experiences a tension proportional to and in the opposite direction to displacement.

We call this force a 'restoring force'. It acts to restore the mass to the centre. In this case the restoring force is tension in the spring. 

Consider a Pendulum. In this case the restoring force is gravity written as $mg\sin\theta$:
![[Pasted image 20260118195230.png]]

For positive displacement, the restoring force is in the negative direction

For negative displacement, the restoring force is in the positive direction

Again this force is proportional to displacement and in the opposite direction. It will oscillate just like the spring-mass system.

## Definition
In general, any system that has  restoring force proportional to displacement, acting in the opposite direction and no other forces, is said to oscillate with 'simple harmonic motion' (SHM)

From this definition, we can state that:
$$
\begin{gather*}
F \propto -x \\ \
F = -kx
\end{gather*}
$$
Now: 
$$
F=ma = m \ddot{x}
$$
Therefore:
$$
\begin{gather*}
m \ddot{x} = -kx \\ \\
\therefore \ddot{x} = -\frac{k}{m}x
\end{gather*}
$$
Now, k depends on the system and we can combine, $\frac{k}{m}$ into a single constant called $\omega^{2}$. Thus:
$$
\begin{gather*}
\ddot{x} \propto -x \\ \\
\ddot{x} = -\omega^{2}x
\end{gather*}
$$
In physics, $\omega$ is the angular frequency. For SHM to hold, the above equation must be in the system.

Let's solve this second order DE:
$$
\begin{gather*}
\ddot{x} = -\omega^{2}x  \\ \\
\ddot{x} + \omega^{2}x = 0 \\ \\
m^{2}+\omega^{2} = 0 \\
m^{2} = -\omega^{2} \\ 
m = \pm \omega
\end{gather*}
$$
Therefore the solution will be of the form:
$$
x = A\cos(\omega t) + B\sin(\omega t)
$$
This shows that the object will oscillate sinusoidal. Using harmonic form we can show this succinctly:
$$
\begin{gather*}
x = A\sin(\omega t + \phi )  \\ \\ 
x = A\cos(\omega t+\phi) 
\end{gather*}
$$
Where $\phi$ is the phase and $A$ is the amplitude.
$$
\begin{gather*}
x = A\cos(\omega t) \ (\text{A particle released from maximum displacement at t=0}) \\ \\
x = A\sin(\omega t) \ (\text{A particle released from minimum displacement at t=0})
\end{gather*}
$$

The period of oscillation of a particle can be calculated by:
$$
T = \frac{2\pi}{\omega}
$$

# Worked Example 1
![[Pasted image 20260118203055.png]]
Writing the solutions to auxiliary equations:
$$
\begin{gather*}
\ddot{x} + 25x = 0  \\ \\
m^{2} + 25m = \\ 
m = \pm 5i
\end{gather*}
$$
Thus:
$$
 x = A\cos(5t)+B\sin(5t)
$$
Finding $\dot{x}$:
$$
\dot{x} = -5A\sin(5t) + 5B\cos(5t)
$$
Using boundary conditions given in the question:
$$
\begin{gather*}
x(0) = 2 = A  \\ \\
\dot{x}(0) = 5 = 5B \implies B = 1 \\ \\
\therefore x = 2\cos(5t)+\sin(5t)
\end{gather*}
$$
To find the maximum displacement, we can convert the function into harmonic form and the amplitude will be $R$ and the time this happens will be $\phi$:
$$
\begin{gather*}
x = R\cos(5t- \phi) \\ \\
= R\cos(5t)\cos \phi + R\sin(5t)\sin \phi \\ \\
R = \sqrt{ 2^{2}+1^{2} } = \sqrt{ 5 } \\ \\
\phi = \arctan\left( \frac{1}{2} \right) = 0.464
\end{gather*}
$$
Thus the amplitude is $\sqrt{ 5 }$ and it occurs at $t=0.646$

# Velocity
Consider a particle released from its maximum displacement at t = 0.
$$
x = \cos\omega t
$$
Its velocity, $v$ is:
$$
v= \dot{x} = -\omega \sin\omega t
$$
![[Pasted image 20260118210504.png]]
![[Pasted image 20260118210515.png]]
Intuitively and by considering energy:
v = 0 at $x_{max}$ and $v$ is max at $x=0$.

# Worked Example 2
![[Pasted image 20260118210613.png]]
Setting up the equation for SHM:
$$
\begin{gather*}
\ddot{x} = -\omega^{2}x \\ \\
-48 = -w^{2}(3) \\ 
-16 = -\omega^{2} \implies \omega = 4
\end{gather*} 
$$
Thus:
$$
\begin{gather*}
A\cos(4t)+B\sin(4t) \\ \\
\dot{x} -4A\sin(4t) + 4B\cos(4t)
\end{gather*}
$$
Using the boundary conditions:
$$
\begin{gather*}
x(2) = 0, \dot{x}(2) = 20 \\ \\
x(2) = A\cos(8) + B\sin(8) = 0 \\ \\
\dot{x}(2) = -4A\sin(8) + 4B\cos(4t) = 20
\end{gather*}
$$
Solving this system of equations using the calculator gives:
$$
A = -4.95 \qquad B = -0.728
$$
Thus:
$$
\boxed{x = -4.95\cos(4t) - 0.728\sin(4t)}
$$

# Worked Example 3
A particle with SHM. Given that its maximum displacement is $\alpha$, show that:
$$
v^{2} = \omega^{2} (\alpha^{2}-x^{2})
$$

We do that:
$$
\ddot{x} = \frac{dv}{dt}
$$
And we also know that:
$$
\ddot{x} = -\omega^{2}x
$$
From A level differential equations:
$$
\frac{dv}{dt} = \frac{dx}{dt} \times \frac{dv}{dx} = v \frac{dv}{dx}
$$
Thus:
$$
 v \frac{dv}{dx} = -\omega^{2}x
$$
Integrating both sides gives:
$$
\begin{gather*}
\int vdv = \int -\omega^{2}x^{2} dx  \\ \\
\frac{1}{2}v^{2} = -\frac{1}{2}\omega^{2}x^{2} + c \\ \\
v^{2}= -\omega^{2}x^{2} +d
\end{gather*}
$$
Now since this a function of displacement $v(x)$, when the displacement is at its maximum,  $v(\alpha)=0$. Therefore:
$$
0 = -\omega \alpha^{2} + d \implies d = w^{2}\alpha^{2}
$$
Substituting $d$ back into the equation:
$$
\begin{gather*}
v^{2} = -w^{2}x^{2}+\omega^{2}\alpha^{2} \\ \\ 
v^{2} = \omega^{2}(\alpha^{2}-x^{2})
\end{gather*}
$$
