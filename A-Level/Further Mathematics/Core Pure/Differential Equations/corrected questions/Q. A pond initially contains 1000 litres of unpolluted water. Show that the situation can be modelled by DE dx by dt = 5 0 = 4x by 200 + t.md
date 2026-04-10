![[Pasted image 20260118235531.png]]https://www.edufax.co.uk/problemsheets/13_diff_eq_2.pdf

(a) 
For this question you need to find out V in terms of $V_{0}$ and $f_{in}$ and $f_{out}$. You then need to find out $C_{out}$ by using $c = \frac{x}{v}$ and take $x$. The final rate of change will be $f_{in}(c_{in}) - f_{out}c_{out}$
$$
\begin{gather*}
\text{Let } V_{0}  \text{ be the initial water in the tank} = 1000 [L] \\
\text{Let } f_{in} \text{ be the water flowing in } = 25 [L / d] \\ 
\text{Let } f_{out} \text{ be the water flowing out } = 20 [L / d] \\ 
\text{Let } V \text{ be the volume of the water in the tank at t}   \\
\text{Let } C_{in} \text{ be the concentration of water flowing in} = 2 [g / d] \\
\text{Let } C_{out} \text{ be the concentration of water flowing out} \\ 
x \text{ is the concentration of pollutant in the tank}\\ \\
V = V_{0} + (f_{in} - f_{out})t = 1000 + (25-20)t = 1000 + 5t \\ \\
C_{out} = \frac{x}{V} = \frac{x}{1000+5t} \\ \\ 
\frac{dx}{dt} = f_{in}(c_{in}) - f_{out}c_{out} = 25(2) - 20\left( \frac{x}{1000+5t} \right) = 50 - \frac{5(4x)}{5(200+t)} \\ \\
 = 50 - \frac{4x}{200+t} \\ \\
 QED
\end{gather*}
$$
(b)
This is a first order DE. You need to find the integrating factor, multiply by it and then do not forget to find C. 
$$
\begin{gather*}
x' + \frac{4}{200+t} x = 50 \\ \\
f(x) = e^{\int \frac{4}{200+t}} = e^{4\ln(200+t)} = e^{\ln((200+t)^{4})} = (200+t)^{4} \\ \\
\therefore x(200+t)^{4} = \int 50(200+t)^{4} \\ \\
x(200+t)^{4} = 10(200+t)^{5} + c \\ \\
x = 10(200+t) + \frac{c}{(200+t)^{4}}
\end{gather*}
$$
Using the boundary condition of $x(0)=0$, we can find $c$:
$$
\begin{gather*}
10(200) + \frac{c}{(200)^{4}} = 0 \\ \\
c = -3.2 \times 10^{12}
\end{gather*}
$$
Therefore:
$$
x(t) = 10(200+t) -\frac{3.2 \times 10 ^{12}}{(200+t)^{4}}
$$
Thus $x(8)$:
$$
x(8) = 10(200+8) - \frac{3.2 \times 10^{12}}{(200+8)^{4}} = 370.39161\dots = 370g
$$
(c)
The model can be refined by:
- Taking into account that the pollutant does not immediately dissolve throughout the pond upon entry
- The rate of leaking could be made to vary with the volume of the pond. 