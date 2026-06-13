Consider  a particle attached to one end of a light elastic spring, the other end of which is attached to a fixed point $A$, vertically above the particle. 

![[Pasted image 20260613185612.png]]

The particle hangs in its equilibrium position at a distance $e$ below the springs natural length. From this, it possible to form an equation of tension and weight:
$$
\begin{gather*}
T = mg \\ \\
\frac{\lambda e}{l} = mg \\ \\
\end{gather*}
$$

The particle is now displaced to position $x_{0}$ below $O$ and released. 
![[Pasted image 20260613190145.png]]

From this it possible to form an equation of $F=ma$, but this time using the tension, weight and extension $x_{0}$.:
$$
\begin{gather*}
F = ma  \\ \\
m\ddot{x} = mg - T \\ \\
m\ddot{x} = mg - \frac{\lambda(x_{0}+e)}{l} \\ \\
m\ddot{x} = mg -\frac{\lambda x_{0}}{l} + \frac{\lambda e}{l}
\end{gather*}
$$
Recall from the previous equation that $mg = \frac{\lambda e}{l}$$. Thus:
$$
m\ddot{x} = mg -\frac{\lambda x_{0}}{l} - mg
$$
This leaves us with:
$$
\begin{gather*}
m\ddot{x} = \frac{\lambda x_{0}}{l} \\ \\
\ddot{x} = -\frac{\lambda}{ml} x_{0}
\end{gather*}
$$
This is in the form $\ddot{x} = -\omega^{2}x$, thus the particle is in SHM.

# Example 1
A light elastic string has natural length $l$ and modulus 3mg. A particle $P$ of mass m is attched to one of the spring. The other is attached to a fixed point $A$. Point B is vertically below with $AB = \frac{5}{3}l$. P is released from rest at $B$. 

a) Show that P moves with SHM with period $2\pi \sqrt{ \frac{l}{3g} }$
b) Find the maximum kinetic energy of $P$
c) Find the time during one full osicalltion for which the speed of $P$ is more than half its maximum natural length. 

For spring/string style SHM questions that ask about showing that the particle moves in SHM, the questions always start with finding the equilibrium position particle then considering the $F=ma$ equation with  additional extension moved by the particle as a variable of extension $x_{0}$:

Firstly, drawing a diagram of the system:
![[Pasted image 20260613191348.png]]

1. Finding the equilibrium extension. This is found when the tension of the string is equal to the weight of the string:
$$
\begin{gather*}
mg = \frac{3mg e}{l} \\ \\ 
e = \frac{l}{3}
\end{gather*}
$$
2. Finding forming an equation of $F=ma$ and the extension as $x_{0}$:
3. $$
\begin{gather*}
m\ddot{x} = mg - \frac{3mg(x_{0} + e)}{l} \\ \\
\ddot{x} = g - \frac{3g\left( x_{0} + \frac{l}{3} \right)}{l}
\end{gather*}
$$
Recall that $\frac{3mg\left( \frac{l}{3} \right)}{l}$ is just equal to $3mg$:
$$
\begin{gather*}
\ddot{x} =  g - \frac{3gx_{0}}{l} - \frac{3g\left( \frac{l}{3} \right)}{l} \\ \\
\ddot{x} = g - \frac{3gx_{0}}{l} - g \\ \\
\ddot{x} = -\frac{3g}{l}x_{0}
\end{gather*}
$$
Therefore the particle is in SHM with $\omega = \sqrt{ \frac{3g}{l} }$. With this the period can then be calculated using $T = \frac{2\pi}{\omega}$. 
$$
\begin{gather*}
T = \frac{2\pi}{\omega} = \frac{2\pi}{\sqrt{ \frac{3g}{l} }} \\ \\
= 2\pi \sqrt{ \frac{l}{3g} }
\end{gather*}
$$
b) For the second part of this question, recall that $v_{max}=a\omega$. As the value of $x_{0}$ from the question was given as an additional extension of $\frac{l}{3}$, in this question we take $a$ to be $\frac{l}{3}$/
