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

## Example 1 Continued... 
The particle passes point $B$ with velocity $8ms ^{-1}$. Find the distance $AB$, $d$.

Now our variables are $v$ and $x$. Therefore we use $v \frac{dv}{dx}$:
$$
\begin{gather*}
v \frac{dv}{dx} = \frac{2}{v-1}
\end{gather*}
$$
For this part of the problem we are told that velocity of he particle is now $8$. Initially it was $4$. Since we have $v(t)$ now, we can use these values as our limits for integration when integrating $v$. Furthermore the limits of displacement will be the initial displacement and the final displacement at $B$, $d$:
$$
\begin{gather*}
\int_{4}^{8}v(v-1)dv = \int_{0}^{d} 2 dx \\ \\
\left[\frac{1}{2}v^{3}-v^{2}\right]_{4}^{8} = [2x]_{0}^{d} \\ \\
d = \frac{1}{2}\left[ \frac{1}{3}v^{3}-\frac{1}{2}v^{2} \right]_{4}^{8} \\ \\
= \frac{1}{2} \left[ \frac{416}{3} - \frac{40}{3} \right]_{4}^{8} \\ \\
= \frac{188}{3}m
\end{gather*}
$$
Note how we formed two different DEs from the same expression for acceleration, based on what we need. 

# Example 2
The acceleration, $a$, of a particle is modelled as $a = \frac{1}{2}(3-v)$. Given that the particle is at rest at the origin, $O$, at $t=0.$

Find $v(t)$ and state its limiting value.  

We are given $a$ and asked to find $v(t)$. Therefore we use $\frac{dv}{dt}$:
$$
\begin{gather*}
\frac{dv}{dt} = \frac{1}{2}(3-v)
\end{gather*}
$$
Integrating:
$$
\begin{gather*}
\int \frac{1}{(3-v)}dv = \int \frac{1}{2} dt  \\ \\
-\ln(3-v) = \frac{1}{2}t +c
\end{gather*}
$$
Using the conditions of the question to find the constant of integration:
$$
-\ln(3-(0)) = \frac{1}{2}(0) + c \implies c = -\ln 3
$$
Rearranging to get in terms of $v=\dots$:
$$
\begin{gather*}
-\ln(3-v) = \frac{1}{2}t -\ln 3 \\ 
\ln(3-v) = \ln 3 - \frac{1}{2}t \\ 
3-v = 3e^{-\frac{1}{2}t} \\ \\
\therefore \boxed{v(t) = 3 - 3e^{-\frac{1}{2}t}}
\end{gather*} 
$$
Finding the limiting value means to take the limit as $t\to \infty$L
$$
\lim_{ t \to \infty } [v(t)] = 3
$$
Therefore the limiting value is $3$.

# Example 2 Continued...
The particle passes $A$ with velocity $2ms ^{-1}.$ Find the distance $OA$. 

For this part, need to use $v \frac{dv}{dx}$ and consider the limits. The initial velocity was $0$ and now its at $2$. The initial position from $O$, was $0$,now we are trying to find it - $d$.:
$$
\begin{gather*}
v \frac{dv}{dx} = \frac{1}{2}(3-v) \\ \\
\int_{0}^{2} \frac{v}{3-v} dv = \int_{0}^{d} \frac{1}{2} dx \\ \\
\end{gather*}
$$
To integrate $\frac{v}{3-v}$, we can use algebraic manipulation:
$$
\begin{gather*}
\int \frac{v}{3-v}  = -\int \frac{-v}{3-v} \\
\\
= -\int \frac{3-v-3}{3-v} = -\int 1 - \frac{3}{3-v} \\ \\
= \int\frac{3}{3-v} - 1 = -3\ln(3-v) -v
\end{gather*}
$$
We could have also used algebraic division too. 

Therefore:
$$
\begin{gather*}
\left[ -3\ln(3-v)-v \right]_{0}^{2} = \frac{1}{2}d \\ \\ 
d = 2[-3\ln(3-v)-v]_{0}^{2} \\ \\
d = 2(-3\ln(3-2)-2) - 2(-3\ln 3 - 0) \\ \\
d= -4+6\ln 3 \\ \\
\boxed{d = 6\ln 3 - 4}
\end{gather*}
$$

# Example 3
$a =-\frac{1}{2}e^{-x}$, $v(0) = 1$, $x(0)=0$. Find $v(x)$ and $x(t)$. 

We are given $a$ and want to find $v(x)$, so we use $v \frac{dv}{dx}$:
$$
\begin{gather*}
v \frac{dv}{dx} = -\frac{1}{2}e^{-x} \\ \\ 
\int vdv = \int - \frac{1}{2}e^{-x} dx \\ \\
\frac{1}{2}v^{2} = \frac{1}{2}e^{-x} + c
\end{gather*}
$$
Using the given conditions to find constant of integration:
$$
\frac{1}{2}(1)^{2}= \frac{1}{2}e^{-0} + c \implies c = 0
$$Using $c$ and rearranging for $v(t)$:
$$
\begin{gather*}
\frac{1}{2}v^{2} = \frac{1}{2}e^{-x} \\ \\
v^{2} = e^{-x} \\ \\
v = e^{-\frac{x}{2}}
\end{gather*}
$$
Now, $\frac{dx}{dt}$