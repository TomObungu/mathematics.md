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
c) Find the time during one full osicalltion for which the speed of $P$ is more than half its maximum.

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
b) For the second part of this question, recall that $v_{max}=a\omega$. As the value of $x_{0}$ from the question was given as an additional extension of $\frac{l}{3}$, in this question we take $a$ to be $\frac{l}{3}$ 
$$
v_{max} = a\omega = \frac{l}{3}\sqrt{ \frac{3g}{l} } \sqrt{ \frac{gl}{3} }
$$
The maximum kinetic energy occurs when the velocity is at at $v_{max}$, thus we can substitute $v_{max}$ into an the equation for kinetic energy:
$$
KE_{max} = \frac{1}{2}m\left( \sqrt{ \frac{gl}{3} } \right)^{2} = \frac{mgl}{6}
$$

c) For this part of the question, as the particle is released from maximum displacement, the equation of motion is modelled as:
$$
x = \frac{l}{3}\cos \sqrt{ \frac{3g}{l} }t
$$
In order to find the velocity, we must differentiate:
$$
\begin{gather*}
\dot{x} = - \frac{l}{3}\sqrt{ \frac{3g}{l} } \sin \sqrt{ \frac{3g}{l} }t \\ \\ 
\dot{x} = -\sqrt{  \frac{gl}{3} }\sin \sqrt{ \frac{3g}{l} t }
\end{gather*}
$$
From this, diagram the graph of motion and find the intersection between the $\dot{x}$ and  $\frac{1}{2}\sqrt{ \frac{gl}{3} }$:
![[Pasted image 20260613192950.png]]
$$
\begin{gather*}
-\sqrt{ \frac{gl}{3} }\sin \sqrt{ \frac{3g}{l}t }  = -\frac{1}{2}\sqrt{ \frac{gl}{3} } \\ \\
\sqrt{ \frac{3g}{l} }t = \frac{\pi}{6} \therefore t = \frac{\pi}{6} \sqrt{ \frac{l}{3g} }
\end{gather*}
$$
Thus, the total time the velocity is greater than half its maximum velocity can be calculated by symmetry:
$$
\begin{gather*}
T = 2\pi \sqrt{ \frac{l}{3g} } - 4\left( \frac{\pi}{6} \right)\sqrt{ \frac{l}{3g} } \\ \\ 
= \frac{4}{3}\pi \sqrt{ \frac{l}{3g} }
\end{gather*}
$$
# Strings
Consider the scenario:
![[Pasted image 20260613194608.png]]

An elastic string has natural length $l$.  The extension is $\frac{3}{2}l$. The particle is displaced to $l$ below equilibrium, then released. 

The particle moves with SHM about the equilibrium position with amplitude $l$.

At it highest point, the string still has extension $\frac{l}{2}$ so remains taut. 
Hence, the particle performs complete oscillations. 

In vertical SHM, a particle will perform complete oscillation if the amplitude is less than the extension at equilibrium and hence the string is taut. 

If the amplitude is greater than the extension at equilibrium, the particle will move with SHM while the string remains taut. 

When the string reaches its natural length, its goes slack and the particle moves freely under gravity until the string goes taut again. 

# Example 3
A light elastic string of natural length $1.5m$ and modulus of elasticity $4g$, has one end attached to a fixed point, $A$. A $2kg$ particle is attached to the other end moved to position $B$, vertically below $A$, with $AB = 3.75$, then released.

Show that particle moves with SHm about its equilibrium and state its period 

Firstly set up a diagram for the system. Afterwards find the equilibrium extension, then set up an equation for $F=ma$ using $x_0$:
![[Pasted image 20260613195345.png]]
1. Finding equilibrium extension:
 $$
\frac{4ge}{1.5} = 2g \implies e = 0.75
$$
2. Setting up an equation for $F=ma$ to prove SHM:
3. $$
\begin{gather*}
2\ddot{x} = 2g - \frac{4g(x + 0.75)}{1.5} \\ \\
2\ddot{ x} = 2g -\frac{4gx}{1.5} - \frac{4g(0.75)}{1.5} \\ \\
2\ddot{x} = 2g - \frac{4gx}{1.5} -2g \\ \\ 
\ddot{x} =\frac{2gx}{1.5}x
\end{gather*}
$$
Thus the particle is in SHM with $\omega = \sqrt{ \frac{4g}{3} }$.  Thus, the period of oscillation can be calculated to be:
$$
T = 2\pi \sqrt{ \frac{3}{4g} }
$$

## Example 3 Continued... 
(b) The particle first comes to instantaneous rest at $C$. Find the distance BC.

For this problem the height can be found using conservation of energy. This through equation elastic potential energy when released from the bottom of the string to the gravitational potential energy gained when the particle first comes to rest.

Recall from the diagram that the total extension of the particle is length it was pulled down to, plus its extension from equilibrium position. This is 1.5 + 0. 75 = 2.25:
$$
\begin{gather*}
E_{\text{start}} = E_{\text{end}} \\ 
EPE = GPE \\ 
\frac{4g(2.25)^{2}}{2l} = 2gh \\ \\
h = 3.375
\end{gather*}
$$

(c) Find the time taken for the particle to return to its stationary position, from when it is released. 

For this question, referring back to the diagram is useful. You must first use the equation
