When equations of curves are given parametrically, you can adjust the formulae for volumes of revolution by using chain.

The volume of revolution formed by the parametric curve with equations $x=f(t)$ and $y=g(t)$ 

is rotated through $\theta$ radians about the x-axis between $x=a$ and $x=b$ is given by:
$$
V = \frac{1}{2} \theta\int_{x=a}^{x=b}y^{2} dx = \frac{1}{2}\theta \int_{x=a}^{x=b}y^{2} \frac{dx}{dt}dt
$$

is rotated through $\theta$ radians about the x-axis between $y=a$ and $y=b$ given by:
$$
V = \frac{1}{2} \theta \int_{y=a}^{y=b}x^{2}dy = \frac{1}{2}\theta \int_{y=a}^{y=b}x^{2} \frac{dy}{dt}dt
$$

# Worked Example 1
![[Pasted image 20251223154052.png]]
$$
\begin{gather*}
x=t(1+t) = t^{2}+t\\ 
\frac{dx}{dt} = 2t+ 1 \\ \\
y = \frac{1}{1+t} \qquad y^{2} = \frac{1}{(1+t)^{2}} \\ \\
x = 0 \implies t = 0 \\ 
x = 2 \implies t = 1 \\ \\
V = \pi \int_{0}^{1} \frac{1}{(1+2t)^{2}}(1+t)dt = \pi \int_{0}^{1} \frac{1+2t}{(1+t)^{2}}dt \\ \\

\frac{1+2t}{(1+t)^{2}} = \frac{A}{(1+t)^{2}} + \frac{B}{1+t} \\ \\
1+2t + A + B(1+t) \\ \\
A = -1 \qquad B = 2 \\ \\
V = \pi \left( \int_{0}^{1} \frac{2}{1+t} - \int_{0}^{1} \frac{1}{(1+t)^{2}}  \right)  \\ \\ 
= \pi([2\ln 1 + t] + (1+t)^{-1}]_{0}^{1} \\ \\
= \pi\left( 2\ln 2 + \frac{1}{2} - 0 + 1 \right) \\ \
= \pi\left( 2\ln 2 - \frac{1}{2} \right)
\end{gather*}
$$
