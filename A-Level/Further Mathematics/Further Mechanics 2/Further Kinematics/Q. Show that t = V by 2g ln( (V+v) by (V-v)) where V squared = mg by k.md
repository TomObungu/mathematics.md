![[Pasted image 20260606154427.png]]

With question you must recognise that this is a kinematics question in which acceleration must first be written as $\frac{dv}{dt}$ then $v \frac{dv}{dx}$ for part (c). 
Remember in further kinematics, you must solve the differential equations using separation of variables. 

Setting up the force equation for the whole system:
$$
\begin{gather*}
\sum F=ma  \\ \\
mg - kv^{2} = m\left( \frac{dv}{dt} \right)
\end{gather*}
$$
Separating variables givens:
$$
\int dt = \int \frac{m}{mg-kv^{2}} dv 
$$
This can be manipulated to form the standard result for the integral of $\frac{1}{a^{2}-x^{2}}$. 
$$
\begin{gather*}
\int dt = m \int \frac{1}{mg-kv^{2}}\\ \\
\int dt = \frac{m}{k} \int \frac{1}{\frac{mg}{k}-v^{2}} \\ \\
\int dt = \frac{m}{k} \int \frac{1}{\sqrt{ \left( \frac{mg}{k} \right)^{2}-(v)^{2}}} \\ \\
t = \left( \frac{m}{k} \right)\left( \frac{1}{2\left( \sqrt{ \frac{mg}{k} } \right)} \right)\ln \left( \frac{\sqrt{ \frac{mg}{k}  }+v}{\sqrt{ \frac{mg}{k} -v }} \right) \\ \\
\end{gather*}
$$
Now we know that:
$$
V ^{2} = \frac{mg}{k} \implies V = \sqrt{ \frac{mg}{k} }
$$
We also known from rearranging $V^{2}$:
$$
\frac{V^{2}}{g} = \frac{m}{k}
$$
Substituting the found values the expression for $t$ therefore gives the expression as wanted:
$$
\begin{gather*}
t =
\frac{m}{k}\left( \frac{1}{2V} \right)\ln\left( \frac{V+v}{V-v} \right) \\ \\
QED
\end{gather*}
$$
For part 
