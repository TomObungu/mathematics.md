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
	