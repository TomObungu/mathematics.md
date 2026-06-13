We can have full oscillations with elastic strings if there are two strings attached to the particle, on on each side, or if the particle is attached to a point along a string that is stretched between two points. 

# Example 1
Points A mad B are 8m apart on a smooth horizontal surface. A light elastic string, $l = 2m$, $\lambda=10N$, has one attached to $A$. Another string, $l = 2m$, $\lambda=30N$ has one end attached to B. Particle $P$ is attached to free of each string. Find the distance of the equilibrium position, $O$, from $B$. 

![[Pasted image 20260613104653.png]]


From the diagram we know that tensions of the string will be equal for the particle to be in equilibrium. Thus, we can equate them and form an equation to be solved for $x$:
$$
\begin{gather*}
T_{B} = T_{A} \\  
\frac{30(x-2)}{2} = \frac{10(8-x-2)}{2} \\ \\
3(x-2) = 6 - x \\ \\
4x = 12 \\ \\
x = 3
\end{gather*}
$$

## Example 1 continued...
P is moved towards $B$, then released. Show that $P$ moves with SHM about $O$. 

By forming another diagram, it possible to see that particle now has an amplitude of $x$ from equilibrium position. 
![[Pasted image 20260613105224.png]]

The resultant force on the particle will be the differences in the tensions of the strings. With this information we can set up an equation for SHM:
$$
\begin{gather*}
0.5\ddot{x} = T_{B} - T_{A} \\ \\
\end{gather*}
$$

For the tension in the string $T_{A}$, the extension from equilibrium position is 5 + x minus the natural length of the stirng. For the tension and of string at $B$, the tension is 3 - x  minus it natural length. Which this tensions, we can form an equation force for the system:
$$
\begin{gather*}
0.5\ddot{x} = T_{B} - T_{A}  \\ \\
\ddot{x} = \frac{30(3-x-2)}{2} - \frac{10(5+x-2)}{2} \\ \\
\ddot{x} = 30(1-x) - 10(3 + x) \\ \\
\ddot{x} = 30 - 30x - 30 - 10x  \\ \\
\ddot{x} = -40x
\end{gather*}
$$
This in the form $\ddot{x} = -\omega^{2}x$. Thus the particle moves in SHM

## Example 2
A and B are 4m apart of a smooth horizontal surface. A light elastic string, $l=0.8m$, $\lambda = 15m$ has one end attached to $A$. Another string $l=0.8$, has one end attached at $B$. Particle $P$ of $0.2kg$ is attached to the free end of each string. The particle rests in equilibrium at point $C$. It is then held at $D$, where $AD = 2.16m$ and released. 

(a) Show that $P$ moves with SHM about C
(b) Find the taken from when P is released to when it first moving with speed $2ms ^{-1}$

The first step in this problem is to determine the extension of the particle when it is in equilibrium. 

The most important step in these problems is setting up an accurate diagram. From the diagram it is possible to determine the configuration of the tensions in each string:
![[Pasted image 20260613182352.png]]

From the diagram we can the set up an equation from the equilibrium equation of the tensions of the strings. 

$$
\begin{gather*}
T_{A} = T_{B} \\ \\ 
\frac{15(x - 0.8)}{0.8} = \frac{10(4-x-0.8)}{0.8} \\ \\
15x - 12 = 32 - 10x \\ \\ 
24x = 44 \\ \\
x = 1.76m
\end{gather*}
$$

We are told that particle is then stretched another $0.4$ meters to $2.16m$ and released. We can treat this extension as variable $x_{0}$ and set up an equation of $F=ma$ with tensions with the new $x$ position:
![[Pasted image 20260613183401.png]]

$$
\begin{gather*}
F =ma \implies 0.2a = T_{B} - T_{A} \\ \\
0.2\ddot{x} = \frac{10(2.24 - x_{0} - 0.8)}{0.8} - \frac{15(1.76+x_{0}-0.8)}{0.8} \\ \\
\ddot{x} = 62.5(1.44 - x_{0}) - 93.75(0.96 + x_{0}) \\ \\
\ddot{x} = -\frac{625}{4}x_{0}
\end{gather*}
$$
This is in the form $\ddot{x} = -\omega^{2}x$, thus the particle is in SHM.

b) The second part of the question involves another trigonometric equation of motion. However, this time we must differentiate to get the velocity of the particle.

The equation of motion of the particle can be given by:
$$
\begin{gather*}
x = 0.4\cos \frac{25}{2}t \\ \\
\dot{x} = -5\sin \frac{25}{2}t
\end{gather*}
$$

![[Pasted image 20260613183904.png]]

From the graph we can find the moment the velocity is magnitude is $2$, this occurs when $x=-2$:
$$
\begin{gather*}
-5\sin \frac{25}{2}t = -2  \\ \\
t = 0.0335
\end{gather*}
$$