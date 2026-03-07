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

Now we have velocity, $v$, we need to integrate it to find $s$. **However**, we need to be careful and consider the negative regions the velocity function. Graphing it we see that it has a negative region at $[2,4]$ for $t$. 
![[Pasted image 20260307211749.png]]
The question states that we also need to find the displacement $s$ for up to $t=3$. Therefore we need to integrate the positive regions and subtract the negative regions. In this case the positive limits are $t_{1} = 0$ and $t_{2} = 2$ and the negative $t_{1} = 2$ and $t_{2} = 3$. Start of with writing velocity as the derivative of displacement $x$:
$$
v = \frac{dx}{dt} = 3t-18t+24
$$
Now integrate with the limits. For the displacement integral, since we are trying to find some distance $x$, leave the upper limit as the variable $d$ or $x$ we are trying to find from the question.
$$
\begin{gather*}
 \int_{0}^{x} dx = \int_{0}^{2} 3t^{2}-18t+24dt- \int_{2}^{3} 3t^{2} - 18t + 24 dt  \\ \\
 x = [t^{3}-9t^{2}+24t]_{0}^{2} - [t^{3}-9t+24t]_{2}^{3} \\ \\
 x = [20] - [18-20] = 22m
\end{gather*}
$$
Through all of this, we formed a differential equation where the two variables were the desired variable and the limits i.e 'find the distance, $x$, between the limits, $t$ led us to use $\frac{dx}{dt}$ in our DE.'

 