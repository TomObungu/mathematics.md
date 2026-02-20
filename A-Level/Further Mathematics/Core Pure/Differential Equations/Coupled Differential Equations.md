In lots of real-life scenarios, the rates of change of two quantities are connected. 

For example, in a chemical reaction, the rate of change of the masses of the reactant depends on the amounts of each reactant. 

In a predator-prey scenario, the predators eat the prey. The more predators, the faster the prey get eat, but if the prey fall too low, the predators wont have any food and will die out. Clearly, the two are connected. 

For two quantities, $x$ and $y$, coupled differential equations take the form:
$$
\begin{gather*}
\frac{dx}{dy} = ax+by +f(t)  \\ \\
\frac{dy}{dt} = cx + dy + g(t)
\end{gather*}
$$
If $f(t)=g(t)=0$, every term contains $x$, $y$ or their derivatives. The equations are homogeneous. 

Clearly, the rates of change of $x$ and $y$ depend on the current quantities of $x$ and $y$. 

$f(t)$ and $g(t)$ are time-dependant functions whose rate of change do not depend on the on the quantities of each. For example the time-dependant function signifying a constant rate of flow of chemical reactant. 

# Example 1
$$
\begin{gather*}
\frac{dx}{dt} = 2\dot{x} + 4y \ \ (1) \\ \\
\frac{dy}{dy} = x - y  \ \ (2) \\ \\
\end{gather*}
$$
Given that $x(0)=2$, $y(0)=-2$, find $x(t)$ and $y(t)$.  

We can eliminate $y$ by rearranging $(1)$:
$$
\begin{gather*}
\dot{x} -2x = 4y \\ \\
y  = \frac{1}{4}\dot{x} - \frac{1}{2}x
\end{gather*}
$$
Differentiating to get another equation for $\frac{dy}{dy}$:
$$
\therefore \frac{dy}{dt} = \frac{1}{4}\ddot{x} - \frac{1}{2}\dot{x}
$$

Equating to equation $(2)$ and forming an ODE for $x(t)$
$$
\begin{gather*}
\frac{1}{4}\ddot{x}-\frac{1}{2}\dot{x} = x - y \\ \\
\frac{1}{4}\ddot{x}-\frac{1}{2}\dot{x} = x - \frac{1}{4}\dot{x} - \frac{1}{2}x \\ \\
\frac{1}{4}\ddot{x}-\frac{1}{2}\dot{x} = -\frac{1}{4}\dot{x} +\frac{1}{2}x \\ \\
\frac{1}{2}\ddot{x} - \frac{1}{2}\dot{x} 
\end{gather*}
$$
