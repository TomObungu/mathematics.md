# Worked Example 1
Two particles A(5m) and B(3m) are moving in opposite directions along the same straight line on a smooth horizontal surface when they collide directly. The coeffcient of restitution between the particles is $e$, $e>0$.

Immediately after the collision, the speed of A is v and B, 2v.

Given that $A$ & $B$ are moving in the same direction after the collision, find the range of possible values of $e$. 

The first step is to the diagram required for conservation of momentum. Notice that missing values of initial speed are missing. We denote them as $u_{1}$ and $u_{2}$
![[Pasted image 20251020172120.png]]
$$
\begin{gather*}
\underline{\text{Conservation Of Momentum}} : \\ \\
5m(u_{1}) - 3m(u_{2}) = 5mv + 6mv \\ 
5u_{1}-3u_{2} = 11v (1)
\end{gather*}
$$
Form the second equation using Newton's law of restitution:
$$
\begin{gather*}
\underline{\text{Newton's Law Of Restitution}} :  \\
\frac{2v-v}{u_{1}--u_{2}} = e \\
\implies \frac{v}{u_{1}+u_{2}} =e \\
\implies \frac{v}{e} = u_{1}+u_{2} (2)
\end{gather*}
$$
When given two unknowns, it is best to calculate their values in terms of $v$ and $e$ to simplify future calculations and to have $u_{1}$ and $u_{2}$ in known terms:
$$
\begin{gather*}
(1) + 3(2): \\
8u_{1} = 11v + \frac{3v}{e} \\
\therefore u_{1} = \frac{1}{8}v\left( 11+\frac{3}{e} \right) \\ \\
5(2) - (1): \\
8u_{2} = \frac{5v}{e} - 11v \\
\therefore u_{2}=\frac{1}{8}v\left( \frac{5}{e} - 11 \right)
\end{gather*}
$$
Now the problem states that they remain in the particles remain travelling in the same direction after the collision. This means that $u_{1}>0$. This means:
$$
\begin{gather*}
\frac{1}{8}v\left( 11+\frac{3}{e} \right) > 0 \\ \\
\implies \left( 11+\frac{3}{e} \right) > 0 \\ \\
\implies 11 > -\frac{3}{e} \\
\implies 11e > -3 \\
\implies e > -\frac{3}{11}\\
\end{gather*}
$$

However as the physical properties of $e$ state that $0\leq e \leq 1$ and the problem states that $e<0$ then we automatically now that $e<0$ for this case. 

In fact for anytime an inequality yields a negative result and the lower bound of the problem is stated, then $e>\text{lower bound}$. If the lower bound is not stated then e will always $e\geq0$ for negative inequalities.

Therefore:
$$
e>0
$$


Now if we know that collisions after wards remain moving in the same direction and $u_{1}>0$, then $u_{2}>0$ also:
$$
\begin{gather*}
u_{2} > 0 \\ 
\implies \frac{1}{8}v\left( \frac{5}{e} -11 \right) > 0 \\ 
\implies \left( \frac{5}{e}-11 \right) > 0 \\
\frac{5}{e} > 11  \\
5 > 11e \\
\frac{5}{11} > e
\end{gather*}
$$
Therefore the upper bound of $e$ is $\frac{5}{11} > e$
Combining the bounds for $e$, the final result is:
$$
\boxed{0<e< \frac{5}{11}}
$$
# Worked Example 1 Continued
The kinetic energy energy of $A$ immediately after the collision is 16% of its KE before the collision. Find $e$. 
$$
\begin{gather*}
\text{KE before} = \frac{1}{2}(5m)\left( \frac{1}{8}v\left( 11+\frac{3}{e} \right) \right)^{2} \\ \\
\text{KE after} =  \frac{1}{2}(5m)v^{2} \\ \\
\cancel{ \frac{1}{2}(5m) }v^{2} = 0.16\left( \cancel{ \frac{1}{2}(5m) }\left( \frac{1}{8}v\left( 11+\frac{3}{e} \right) \right)^{2} \right) \\ \\
\cancel{ v^{2} } = \frac{1}{400}\cancel{ v^{2} }\left( 11+\frac{3}{e} \right)^{2} \\ \\
\left( 11+\frac{3}{e} \right)^{2} = 400 \\ \\
121+\frac{66}{e} +\frac{9}{e^{2}} = 400 \\ 
279e^{2}-66e -9 = 0 \\ \\
e = -\frac{3}{31}, \frac{1}{3} \\ \\
\text{However } 0\leq e < \frac{5}{11} \\
\therefore \boxed{e=\frac{1}{3}}
\end{gather*}
$$

