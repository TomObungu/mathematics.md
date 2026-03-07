We know that acceleration is the derivative of velocity. Therefore:
$$
a = \frac{dv}{dt}
$$
We can meddle with the above equation and rewrite it using $v=\frac{dx}{dt}$:
$$
a = \frac{\cancel{ dx }}{dt} \left( \frac{dv}{\cancel{ dx }} \right) = v \frac{dv}{dx}
$$

This relationship is very useful in forming DEs where acceleration is in terms of $v$ or $x$. 

We can solve these problems straightforwardly by forming the appropriate DE for the variables we have. 

- If given $a(t)$ and asked to 'find $v(t)$', use $a = \frac{dv}{dt}$
- If given $a(t)$ and asked to 'find x between $v=\dots$', use $a = v \frac{dv}{dx}$
- If given $a(t)$ and asked to 'find $v(x)$, use $v \frac{dv}{dx}$'
# Example 1
A particle moves along the x-axis with velocity $v ms ^{-1}$ and displacement $x$ from $O$ at time $t$. Its acceleration, $ams ^{-2}$ is:
$$
a = \frac{2}{v-1}
$$
At $t =0$, the particle passes point $A$ with velocity $4ms ^{-1}$. Find $v(t)$. 

We have $v$ and $t$, so we use $\frac{dv}{dt}$:
$$
\frac{dv}{dt} = \frac{2}{v-1}
$$
Solving this simple first order DE use integration:
$$
\begin{gather*}
\int v - 1dv \int 2 dt \\ \\
\frac{1}{2}v^{2} -v = 2t +c
\end{gather*}
$$
Find the constant of integration using the conditions given in the question i.e $v(0) = 4$
$$
\begin{gather*}
\frac{1}{2}(4)^{2}-(4) = 2(0) + c \\ \\
4 = c 
\end{gather*}
$$
Rearranging into form $v=\dots$:
$$
\begin{gather*}
\frac{1}{2}v^{2}-v = 2t + 4 \\ 
v^{2} -2v =4t + 8 \\ \\
(v-1)^{2} -1 = 4t+8 \\ 
(v-1)^{2} = 4t+9 \\ 
v-1 = \sqrt{ 4t+9 } \\ \\
\therefore \boxed{v(t) = \sqrt{ 4t+9 } + 1}
\end{gather*}
$$

# Example 2
The particle passes point $B$ with velocity $8ms ^{-1}$. Find the distance $AB$, $d$.

Now our variables are $v$ and $x$. W