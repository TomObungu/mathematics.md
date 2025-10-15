# Worked Example 3
P(m) moves with speed $4u$ when it collides with stationary particle $Q$ mass $3m$. Given the direction of $P$ reversed after the collision. Find the value of $e$.

For such problems, always label unknown values of velocity going to right to simplify calculations are reduce chance of error with signs.

![[Pasted image 20251015175641.png]]

Start of by writing the equations as a result of conservation of momentum:
$$
\begin{gather*}
m(4u)=mv_{1} + 3mv_{2} \\ 
4u = v_{1} + 3v_{2} \qquad (1)
\end{gather*}
$$
Secondly, form the equations as a result of restitution:
$$
\begin{gather*}
\frac{v_{2}-v_{1}}{4u} = e \\ \\
v_{2}-v_{1} = 4eu \qquad (2)
\end{gather*}
$$
As it is known that the direction of P was reversed, it's final velocity $v_{1}$ will be negative as it is travelling in the other direction. Therefore we need to find $v_{1}$ in terms of $4u$ and $e$ using equations equations $(1)$ and $(2)$:
$$
\begin{gather*}
(1) - 3 \times (2) : \\ \\
4v_{1} = 4u - 12eu \\
v_{1} = u - 3eu \\
v_{1} = u(1-3eu)
\end{gather*}
$$
As we know that $v_{1} < 0$. Form the inequality by comparing the 
$$
\begin{gather*}
v_{1} < 0 \\
u(1-3e) < 0 \implies (1-3e) < 0 \\
1-3e < 0 \\
1 < 3e \\ 
\frac{1}{3} < e
\end{gather*}
$$