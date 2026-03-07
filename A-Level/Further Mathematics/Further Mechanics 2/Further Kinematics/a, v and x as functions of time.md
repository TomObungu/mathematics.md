In A-Level, we dealt with acceleration, velocity and displacement as functions of time and how to move between them with integration and differentiation. 

# Example 1
Particle P moves along a straight horizontal line with acceleration $6t-18$$ms ^{-2}$ at time $t$ seconds. When $t=0$, the displacement of $P$ from $O$ is zero and its speed is $24 ms ^{-1}$ in the positive direction. Find the distance travelled in the first $3$ seconds. 

We know that acceleration is the derivative of velocity, so we can write acceleration $a$ as  $\frac{dv}{dt}$:
$$
\begin{gather*}
a = \frac{dv}{dt} = 6t-18 
\end{gather*}
$$
This becomes a first order DE that can be easily solved using integration:
$$
\begin{gather*}
\int dv = \int 6t - 18 dt \\ \\
v = 3t^{2} - 18t + c 
\end{gather*}
$$
To find the constant of integration, we use the conditions in the question - think of them as boundary conditions. We know that at $t=0$, $v=+24$, so we can find $c$:
$$
24 = 3(0)+18(0) + c \implies c = 24
$$
Therefore:
$$
v = 3t^{2}-18t+24
$$

