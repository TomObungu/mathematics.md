![[Pasted image 20251227123559.png]]
The key step in the first part of the problem is to eliminate the parameter t. 

Try and rewrite any of the trigonometric identities in terms of $t$ not $2t$ and then rearrange to get to $t$ on the RHS.

If you notice any form of $x$ or $y$ on the LHS, be sure to rewrite it in that form:

Trying to get  $x$ and $y$ on side on $t$ on the other for $x$:

$$
\begin{gather*}
x =\cos t + \frac{1}{2}(2\sin t\cos t) = \cos t(1+\sin t) \\ \\
x = -y(\cos t) \\ \\
-\frac{x}{y} = \cos t
\end{gather*}
$$

For $y$:
$$
\begin{gather*}
y = -(1+\sin t)  \\
-y -1 = \sin t \\
-(y+1) = \sin t
\end{gather*}
$$

We can eliminate $t$ using the Pythagorean identity of $\sin ^{2}t+\cos ^{2}t=1$:
$$
\begin{gather*}
(-(y+1))^{2} + \left( -\frac{x}{y} \right)^{2} = 1 \\ \\
y^{2}+2y+1 + \frac{x^{2}}{y^{2}} = 1 \\ \\
y^{4}+2y^{3}+y^{2}+x^{2} = y^{2} \\ \\
x^{2} = -y^{4}-2y^{3} \\ \\
\boxed{x^{2}=-(y^{4}+2y^{3})}
\end{gather*}
$$

Always try and rearrange to get t on the LHS and things in terms of $x$ and $y$ on RHS and then try and think of an identity based on the function of t.
