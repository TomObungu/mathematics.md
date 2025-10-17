# Hooke's Law
Hooke's Law was discovered experimentally in 1660. However we cannot derive it mathematically. However modern attempts at a fundamental derivation include molecular theory:

The spring has no exerted forces applied to it. It's sitting on a horizontal surface and we are looking down on it. The length of the spring with forces applied is called the natural length.
![[Pasted image 20251017155747.png]]

The force required to extend or compress a spring is proportional to the extension or compression:
$$
\begin{gather*}
F \propto x \\ 
\therefore F = kx
\end{gather*}
$$
The spring constant represents the stiffness of the spring. As stiffer spring will require more force to extend/compress it. 

When the spring is in equilibrium:
![[Pasted image 20251017160112.png]]
$$
T = F \implies T = kx
$$

## Identical strings connected in series
Each spring has natural length $l$ and spring constant $k$.

This means if we look at the springs in series as one spring. The natural length of this spring is 2l. However this combined spring will have a different spring constant of $k_{2}$. 
![[Pasted image 20251017160623.png]]

When the combined spring is stretched by $x$ due to force $F$:
![[Pasted image 20251017160345.png]]
Each spring is stretched by $\frac{x}{2}$

This also means for a single spring with a particle in separating the spring, the natural lengths of the local spring segments will be $\frac{l}{2}$

If the junction of the two springs is in equilibirum, the tension in each spring must be the same $T$.

This means for the smaller spring(s) with force constant $k_{1}$:
$$
T=\frac{k_{1}x}{2}
$$
For the combined spring:
$$
T = k_{2}x
$$
If we form an equation for both $T$:
$$
k_{2}x=\frac{k_{1}x}{2}
$$
This means for springs in series of that cause the length of the spring to double:
$$
k_{2} = \frac{1}{2}k_{1}
$$
In other words:
$$
\therefore \boxed{\text{Doubling the length in series, halves the spring constant}}
$$

From this we can this also forms another relationship for the spring constant. If doubling the length of spring caused spring constant to decrease, then we can show the spring constant is inversely proportional to the natural length of the length of spring.
$$
k \propto \frac{1}{l} \qquad k = \frac{\lambda}{l}
$$
In this case, $\lambda$ is a constant known as the modulus of elasticity.

As $\lambda$ is a property of the material, we can therefore find the spring constant $k$ for a given material and natural length.

Thus bring us to:
$$
\begin{gather*}
T = kx \\ \\
\boxed{T = \frac{\lambda x}{l}}
\end{gather*}
$$
## Worked Example 3
![[Pasted image 20251017162421.png]]

# Worked Example 4
An elastic string of natural length $2a$ is attached to the point $A$ and $B$, where $AB=2a$. A mass m is attached to the midpoint of $AB$ and hangs in equilibrium a distance $a$ below $AB$. Find $\lambda$
![[Pasted image 20251016122336.png]]

To begin with such questions, resolve the vertical force of weight downwards against the vertical component of the tension in the string $T$:
![[Pasted image 20251016122041.png]]
$$
\begin{gather*}
2T\sin 45 = mg \\ 
T = \frac{mg}{\sqrt{ 2 }}
\end{gather*}
$$

Now we have an expression for $T$, we can now formulate an expression for x in terms of $T$.

As the system forms two right angle triangles with length $a$ and $a$. The the length of the string diagonally is:
$$
\sqrt{ a^{2} + a^{2} } = a\sqrt{ 2 }
$$
Therefore the total length of the string when it has been extended by the mass is $2a\sqrt{ 2 }$
Knowing the total length of the string we can calculate the extension of the whole string by subtracting it's new length by it's natural length
$$
2a\sqrt{ 2 } - 2a = 2a(\sqrt{ 2 }-1)
$$
Now knowing the extension, the natural length and the tension, we can form an equation for $\lambda$:
$$
\begin{gather*}
T = \frac{\lambda x}{l} \\ 
\implies \frac{mg}{\sqrt{ 2 }} = \frac{\lambda (2a(\sqrt{ 2 }-1))}{2a} \\
\implies \frac{mg}{\sqrt{ 2 }} = \lambda(\sqrt{ 2 }-1) \\
\therefore \lambda = \frac{mg}{\sqrt{ 2 }(\sqrt{ 2 }-1)} \\
= \frac{mg}{2-\sqrt{ 2 }}
\end{gather*}
$$
	