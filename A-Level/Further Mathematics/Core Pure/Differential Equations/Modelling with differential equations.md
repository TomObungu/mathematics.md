We need to consider DEs based on real scenarios where rates of changes in concentration of substances are involved

Consider a tank of water that has a const flow of polluted water in $f_{in}$ mixed with a concentration of pollutant $c_{in}$. Simultaneously, there is water leaving the taking at a constant rate of $f_{out}$ which in turn causes a concentration of pollutant to leave at a rate of $c_{out}$.
![[Pasted image 20260118223220.png]]
Let's quantify a few measurements:

Let $x(t)$ be the amount of pollutant in the rank at time $t$. Units: g/grams

Let $V_{0}$ be the initial volume of water in the tank at $t=0$. Units: L/litres
Let $V$ the volume of water in the tank at $t$. Units: L/litres

Now let's properly label $f_{in},f_{out}$ and $c_{in}$ and $c_{out}$:

Let $f_{in}$ be the rate of water in. Units $L / s$
Let $f_{out}$ be the rate of water out. Units $L / s$

Let $c_{in}$ be the concentration of pollutant flowing in. Units $g /s$
Let $c_{out}$ be the concentration of pollutant flowing out. Units $g / s$

We want to find the rate of flow pollutant at the $t$ or $\dot{x}(t)$. From the definition of rate of flow we know that:
 $$
 \begin{gather*}
\dot{x}(t)= \frac{dx}{dt} = \text{(rate of pollutant in)} - \text{(rate of pollutant out)}
\end{gather*}
$$
The rates of pollutant are the concentration of pollutant flowing multiplied by the rate of water in.  Thus:
$$
\frac{dx}{dt} = f_{in}(c_{in}) - f_{out}(c_{out})
$$
From the equation of concentration, we know that $c = \frac{x}{v}$. Usually $f_{in}$ and $c_{in}$ are fixed quantities and so only $c_{in}$ must be accounted for using the formula of $c = \frac{x}{v}$. Therefore:
$$
c_{out} = \frac{x(t)}{V}
$$
$V$ can be rewritten as:
$$
V = V_{0} + (f_{in}-f_{out})t
$$
Therefore $c_{out}$ is:
$$
c_{out} = \frac{x}{V_{0}+(f_{in}-f_{out})t}
$$

Thus the total formula for $\frac{dx}{dt}$ is:
$$
\dot{x} = \frac{dx}{dt} = f_{in}(c_{in}) - \left( \frac{x}{V_{0} + (f_{in }-f_{out})t} \right)(f_{out})
$$
# Worked Example 3
A tank initially contains 80 litres of pure water. A chemical solution is added to the water at rate of 3 litres per minute. The chemical solution contains 5 grams of solution per litre. Water flows out of the rank at a rate of 2 litres per minute. There are $x$ grams of solution in the rank at time $t$.  Show that:
$$
\frac{dx}{dt} = 15 - \frac{2x}{80+t}
$$
Writing out the variables:

Let initial water in the tank be $V_{0}$ = 80L
Let volume of water at time $t$ be V

Let rate of flow of solution into tank be $f_{in} =$ 3L/s
Let rate of flow of solution out of tank be $f_{out}$ = 2L/s

Let concentration of chemical into tank be $c_{in}$ = 5g/L
Let concentration of chemical be $c_{out}$.

Rewriting $V$
$$
V = V_{0} + (f_{in}-f_{out})t = 80 + (3-2)t = 80+t
$$
Find $C_{out}$ using $c=\frac{x}{v}$:
$$
C_{out} = \frac{x}{v} = \frac{x}{80+t}
$$
Now we have everything needed to write $\frac{dx}{dt}$:
$$
\begin{gather*}
\frac{dx}{dt} = C_{in}(f_{in}) - c_{out}(f_{out}) \\ \\
= 5(3) - \frac{x}{80+t}(2) \\ \\
= 15 - \frac{2x}{80+t} \\ \\
QED
\end{gather*}
$$
## Worked Example 3 continued...
Find the time at which the concentration of chemical inside the tank is 4g/L.  

This questions just becomes solving for $x$ by forming a first order DE with $\frac{dx}{dt}$:
$$
\begin{gather*}
\frac{dx}{dt} = 15 - \frac{2x}{80+t}  \\ \\
x' = 15 - \frac{2x}{80+t} \\ \\
x' +\frac{2x}{80+t} = 15
\end{gather*}
$$
This is a first order DE on standard form:
$$
\text{Integrating factor } = f(x) = e^{\int \frac{2}{80+t}} = e^{2\ln(80+t)} ={(80+t)^{2}}
$$
Therefore, from solving first order DEs:
$$
\begin{gather*}
x(80+t)^{2} = \int 15(80+t)^{2} \\ \\
x(80+t)^{2} = 15\int(80+t)^{2} \\ \\
x(80+t)^{2} = 5(80+t)^{3}+c \\ \\ \\
\therefore x = 5(80+t) + \frac{c}{(80+t)^{2}}
\end{gather*}
$$
Now remember from the initial writings of the question, the tank was purely water. Thus $x(0)=0$. Therefore we can use these boundary conditions:
$$
x(0) = 5(80) + \frac{c}{(80)^{2}  } =400 + \frac{c}{6400} = 0
$$
Thus:
$$
=c = -2.56 \times 10^{6}=
$$
Therefore the full equation for $x$ is:
$$
x = 5(80+t) - \frac{2.56 \times 10 ^{6}}{(80+t)^{2}}
$$
Now remember that concentration $c = \frac{x}{v}$, thus:
$$
c = \frac{x}{V} = \frac{\left( 5(80+t) - \frac{2.56 \times 10 ^{6}}{(80+t)^{2}}\right)}{(80+t)} = 5- \frac{2.56 \times 10^{6}}{(80+t)^{3}}
$$
Now just equate $c$ to equal $4$ and solve for $t$:
$$
\begin{gather*}
5- \frac{2.56 \times 10^{6}}{(80+t)^{3}} = 4 \\ \\
t = 56.79808 \\ 
\boxed{t = 56.8s}
\end{gather*}
$$

