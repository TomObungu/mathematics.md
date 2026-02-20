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
\frac{1}{4}\ddot{x}-\frac{1}{2}\dot{x} = x - \frac{1}{4}\dot{x} + \frac{1}{2}x \\ \\
\frac{1}{4}\ddot{x}-\frac{1}{2}\dot{x} = -\frac{1}{4}\dot{x} +\frac{3}{2}x \\ \\
\frac{1}{4}\ddot{x} - \frac{1}{4}\dot{x} - \frac{3}{2}x = 0 \\ \\ 
\ddot{x} - \dot{x} -6x = 0 \\ \\ 
\end{gather*}
$$
Solving the auxiliary equation for $x(t)$
$$
\begin{gather*}
m^{2} -m - 6 = 0 \\ \\ 
m = -2,3 
\end{gather*}
$$
Therefore:
$$
\boxed{x = Ae^{-2t} + Be^{3t}}
$$
We can find $y$ by substituting this into the equation for $y$:
Pre-computing $\dot{x}$:
$$
\dot{x} = -2Ae^{-2t}+3Be^{3t}
$$
Substituting $\dot{x}$ and $x$ into y:
$$
\begin{gather*}
y = \frac{1}{4}(-2Ae^{-2t}+3Be^{3t}) - \frac{1}{2}(Ae^{-2t}+Be^{3t}) \\ \\
y = \left( -\frac{1}{2}A-\frac{1}{2}A \right)e^{-2t} + \left( \frac{3}{4}B - \frac{1}{2}B \right)e^{3t} \\ \\
= -Ae^{-2t} + \frac{1}{4}Be^{3t}
\end{gather*}
$$
Thus:
$$
y = \boxed{-Ae^{-2t}+\frac{1}{4}Be^{3t}}
$$


Now using the boundary conditions:
$$
\begin{gather*}
x(0) = A + B = 2 \\ \\
y(0) = -A + \frac{1}{4}B = -2 \\ \\
A= 2 \qquad B = 0 
\end{gather*}
$$
Therefore:
$$
\boxed{\begin{gather*}
x(t) = 2e^{-2t} \\ \
y(t) = -2e^{-2t}
\end{gather*}}
$$
# Example 2
The population of wolves, $x$ and sheep, $y$, in a field after $t$ decades is modelled by:
$$
\begin{gather*}
\frac{dx}{dt} = x + y  \\ \\
\frac{dy}{dy} = -2x + 3y
\end{gather*}
$$
At the start of 2016, there are 100 wolves and 400 sheep.

Find $x(t)$ and $y(t)$ and find the years in which both populations die out, commenting on your answer. 

$$
\begin{gather*}
y = \dot{x} -x  \\ \\
\therefore \dot{y} = \ddot{x} - \dot{x} \\ \\ \\
\therefore \ddot{x}-\dot{x} = -2x + 3\dot{x} -3x \\ \\
\ddot{x}-4\dot{x}+5x = 0  \\ \\
m^{2} -4m + 5 = 0 \\ \\

\end{gather*}
$$