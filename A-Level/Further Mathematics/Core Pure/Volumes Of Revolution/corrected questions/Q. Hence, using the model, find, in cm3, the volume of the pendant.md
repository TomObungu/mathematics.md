![[Pasted image 20260118235952.png]]
(a)
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
(b) 
For this part of the problem, finding the volume of revolution using the standard approach of $V = \frac{1}{2}\theta \int x^{2} \frac{dx}{dt}dt$ is possible but that would yield integrating $\int(1+\sin t)^{2}(-\sin t+\cos 2t)$ which is less easier to evaluate. A a simpler method of finding the volume is by noticing $x^{2}$ is already in Cartesian form and does not need to be multiplied by $\frac{dx}{dt}dt$. Therefore you just need to do $\int x^{2}dy$:
$$
\begin{gather*}
V = \pi\int x^{2} dy  \\ \\
V = \pi\int-(y^{4}+2y^{3})dy \\ \\
= \pi\left[  -\frac{1}{5}y^{5} +\frac{1}{2}y^{4} \right]
\end{gather*}
$$
For the limits, you need to realise since the value of $y$ is negative and the maximum value of $(1+\sin\theta)$ is 2, thus the limits are $[-2,0]$. A mistake would be to assume the upper limit is 2 without considering the equation for $y$ properly. 
$$
\begin{gather*}
\therefore V = \pi \left[-\frac{1}{5}y^{5} + \frac{1}{2}y^{4} \right]_{-2}^{0} \\ \\ \\
= \pi \left[ \left( -\frac{1}{5}(0)^{5}+\frac{1}{2}(0)^{4} \right) - \left( -\frac{1}{5}(-2)^{5} + \frac{1}{2}(-2)^{4} \right)\right] \\ \\
= \frac{8}{5} 
\end{gather*}
$$
