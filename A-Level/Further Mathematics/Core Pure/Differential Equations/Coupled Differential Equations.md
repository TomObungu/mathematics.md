In lots of real-life scenarios, the rates of change of two quantities are connected. 

For example, in a chemical reaction, the rate of change of the masses of the reactant depends on the amounts of each reactant. 

In a predator-prey scenario, the predators eat the prey. The more predators, the faster the prey get eat, but if the prey fall too low, the predators wont have any food and will die out. Clearly, the two are connected. 

For two quantities, $x$ and $y$, coupled differential equations take the form:
$$
\begin{gather*}
\frac{dx}{dt} = ax+by +f(t)  \\ \\
\frac{dy}{dt} = cx + dy + g(t)
\end{gather*}
$$
If $f(t)=g(t)=0$, every term contains $x$, $y$ or their derivatives. The equations are homogeneous. 

Clearly, the rates of change of $x$ and $y$ depend on the current quantities of $x$ and $y$. 

$f(t)$ and $g(t)$ are time-dependant functions whose rate of change do not depend on the on the quantities of each. For example the time-dependant function signifying a constant rate of flow of chemical reactant. 

# Example 1
$$
\begin{gather*}
\frac{dx}{dt} = 2x + 4y \ \ (1) \\ \\
\frac{dy}{dt} = x - y  \ \ (2) \\ \\
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

Finding the general solution for $x$:
$$
\begin{gather*}
y = \dot{x} -x  \\ \\
\therefore \dot{y} = \ddot{x} - \dot{x} \\ \\ \\
\therefore \ddot{x}-\dot{x} = -2x + 3\dot{x} -3x \\ \\
\ddot{x}-4\dot{x}+5x = 0  \\ \\
m^{2} -4m + 5 = 0 \\ \\
m = 2 \pm i \\ \\
\end{gather*}
$$
Therefore:
$$
\therefore x = e^{2t}(A\cos t + B\sin t) \\ \\
$$
And thus:
$$
\begin{gather*}
\dot{x}=e^{2t}(-A\sin t + B\cos t) + 2e^{2t}(A\cos t+B\sin t) \\ \\
= e^{2t}((B + 2A)\cos t+(-A+2B)\sin t)
\end{gather*}
$$
Substituting into $y$:
$$
\begin{gather*}
y = e^{2t}((B+2A)\cos t+(-A+2B)\sin t) - e^{2t}(A\cos t + B\sin t) \\ \\
= e^{2t}((B+A)\cos t+(-A+B)\sin t) 
\end{gather*}
$$
Finding the boundary conditions:
$$
\begin{gather*}
x(0) = A = 100 \\ \\
y(0) = A + B = 400 \implies B = 300 \\ \\
\therefore \boxed{\begin{gather*}
x(t) = e^{2t}(100\cos t + 300\sin t) \\
y(t) = e^{2t}(400\cos t + 200\sin t)
\end{gather*}}
\end{gather*}
$$

# Example 2 Continued...
Finding when the wolves die out will require to find when both functions are zero and comparing them. It is important to note that since wolves and the predator and sheep are the prey, if the sheep die out, then wolves will die out in the same year as they will not have any food to live. 

Finding when wolves die i.e $x(t)=0$:
$$
\begin{gather*}
\cancel{ e^{2t} }(100\cos t + 300\sin t) = 0 \\ \\
\tan t = -\frac{1}{3} \qquad t = \cancel{ -0.321 }, \boxed{2.820} \\ \\
\therefore t = 28.2 \text{ Years} \\ \\
\text{After 2.82 decades, the wolves die out in } 2044
\end{gather*}
$$

Finding when sheep die i.e $y(t)=0:$
$$
\begin{gather*}
e^{2t}(400\cos t + 200\sin t) = 0 \\ \\ 
\tan t =  -2 \implies t =\cancel{  -1.107, } \boxed{2.034}  \\ \\
\therefore t = 20.3 years \\ \\
\text{After 2.034 decades, the sheep die out 2036}
\end{gather*}
$$
When the sheep die out in 2036, the model is no longer valid, so the year in which the wolves die out is also invalid. 
# Example 3
$$
\begin{gather*}
\frac{dx}{dt} = -3x -2y -3t \\ \\
\frac{dy}{dt} = 2x + y + t - 2 \\ \\
\text{When } x(0)=1, y(0)=0, \text{ find } x(t) \text{ and } y(t).
\end{gather*}
$$
Rearranging to find $y$ and $\dot{y}$ to form an equation for $\frac{dy}{dt}$
$$
\begin{gather*}
\dot{x} +3x +3t = 2y \\ \\
y = \frac{1}{2}\dot{x} +\frac{3}{2}x + \frac{3}{2}t \\ \\
\dot{y} = \frac{1}{2}\ddot{x} + \frac{3}{2}\dot{x} +\frac{3}{2}
\end{gather*}
$$
Forming an equation for $\frac{dy}{dt}$ and obtaining an ODE from it:
$$
\begin{gather*}
\frac{1}{2}\ddot{x} + \frac{3}{2}\dot{x} + \frac{3}{2} = 2x + \frac{1}{2}\dot{x} + \frac{3}{2}x + \frac{3}{2}t + t - 2 \\ \\
\ddot{x} +2\dot{x} + x = t + 1 \\ \\
\end{gather*}
$$
Solving the auxiliary equation:
$$
\begin{gather*}
m^{2} + 2m + 1 = 0 \\  \\ 
(m+1)^{2} = 0 \\ \\
m = -1 \\ \\
\therefore x_{c} = e^{-t}(A+Bt) 
\end{gather*}
$$
Trying the particular integral:
$$
\begin{gather*}
x_{p} = \lambda + \mu t \\ \\
\dot{x}_{p} = \mu \\ \\
\ddot{x}_{p} 0 \\ \\
2\mu + \lambda +\mu t = t + 1 \\ \\
\mu = 1 \\ \\
2\mu + \lambda = 1 \implies \lambda = -1 \\ \\
\therefore x_{p} = t-1 \\ \\
\end{gather*}
$$
Therefore
$$
\begin{gather*}
\therefore x(t) = e^{-t}(A+Bt) + t-1  \\ \\
\dot{x}(t) = e^{-t}(B)-e^{-t}(A+Bt) + 1 
\end{gather*}
$$
Thus combining to form $y$:
$$
\begin{gather*}
y(t) = \frac{1}{2}[e^{-t}(A+Bt)-Be^{-t}-1 - 3e^{-t}(A+Bt)-3t + 3 -3t] \\ \\
= e^{-t}\left(-A-\frac{1}{2}B-Bt \right) -3t + 1  \\ \\

\end{gather*}
$$
Finding the particular solution:
$$
\begin{gather*}
x(0) = A-1 = 1 \implies 2 \\ \\
y(0) = -A - \frac{1}{2}B + 1 = 0 \implies B = -2
\end{gather*}
$$
Therefore:
$$
\boxed{
\begin{gather*}
x(t) = e^{-t}(2-2t) + t - 1 \\ \\
y(t) = e^{-t}(-1 + 2t) - 3t + 1
\end{gather*}
}
$$
# Example 3 Continued...
Determine the behaviour for large values of $t$.
$$
\begin{gather*}
t \to \infty, e^{-t} \to 0 \\ \\
\therefore x(t) \to t - 1 \\ \\
y(t) \to -3t + 1
\end{gather*}
$$



