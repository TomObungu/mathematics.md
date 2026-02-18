We know that the centre of mass of a discrete mass distribution is given by:
$$
\bar{x} \sum_{i=1}^{n}m_{i} = \sum_{i=i}^{n}m_{i}x_{i}
$$
and
$$
\bar{y} \sum_{i=1}^{n}m_{i} = \sum_{i=i}^{n}m_{i}y_{i}
$$

Now consider a uniform lamina defined by the area bounded by the function $y=f(x)$, the x-axis and the the lines $x=a$ and $x=b$

![[Pasted image 20260218122444.png]]

Much like the derivation of integration from first principles, consider splitting the area into elemental strips of widths $\delta x$. 
Each strip is a uniform rectangular lamina.

Zooming in and considering one of these rectangular laminas, we can see that the centre of mass is located at $\left( x+\frac{\delta x}{2}, \frac{1}{2}f(x) \right)$
![[Pasted image 20260218122607.png]]

Now if we consider the limit as $\delta x$ approaches 0, $\lim_{ \delta x \to 0 }$, the CoM becomes:
$$
\left( x, \frac{1}{2}f(x) \right)
$$
The area of each strip is $f(x)\delta x$, so for a uniform lamina with mass per unit area, $\rho$, the mass of each strip is:
$$
\rho f(x)\delta x
$$

## Finding $\bar{x}$
Now we know the mass of each individual element that makes up the lamina, we can use the formula for $\bar{x}$, starting between $a$ and $b$, and taking the limit as $\delta x\to 0$.
$$
\begin{gather*}
\bar{x} \sum_{i=1}^{n}m_{i} = \sum_{i=i}^{n}m_{i}x_{i} \\ \\
\therefore \bar{x} \lim_{ \delta x \to 0 } \left[\sum_{a}^{n} \rho f(x)\delta x\right] = \lim_{ \delta x \to 0 } \left[\sum_{a}^{n} \rho x f(x)\delta x\right]
\end{gather*} 
$$
Now the stuff with with limit and inside the square bracket is the definition of an integral, thus we can rewrite the formula. Furthermore, on the left hand side, the sum of the total mass elements of each strip will yield the total mass $M$ of the lamina. Thus we can denote the left hand side limit as just $M$. Therefore:
$$
M\bar{x} = \int_{a}^{b}\rho xf(x)dx
$$
For a uniform lamina, $\rho$ is constant, so we can cancel it out to obtain:
$$
\bar{x}\underbrace{ \int_{a}^{b}f(x)dx }_{ \text{Total area of the lamina} } = \int_{a}^{b}xf(x)dx
$$

Often, we are given the total area, so we can use:
$$
\boxed{A \bar{x} = \int_{a}^{b}xf(x)dx}
$$

## Finding $\bar{y}$
Now consider the same thing, except we multiply by $\frac{1}{2}f(x)$ on the right hand side instead of $x$.
$$
\bar{y} \lim_{ \delta x \to 0 } \left[\sum_{a}^{n} \rho f(x)\delta x\right] = \lim_{ \delta x \to 0 } \left[\sum_{a}^{n} \frac{1}{2} \rho f(x) f(x)\delta x\right]
$$
This simplifies to:
$$
\bar{y} \lim_{ \delta x \to 0 } \left[\sum_{a}^{n} \rho f(x)\delta x\right] = \lim_{ \delta x \to 0 } \left[\sum_{a}^{n} \frac{1}{2} \rho \left[f(x)\right]^{2}\delta x\right]
$$
Therefore:
$$
\bar{y}\int_{a}^{b}\rho f(x)dx = \frac{1}{2}\int \rho\left[f(x)\right]^{2}dx
$$
In the same way as with $\bar{x}$, the total mass $M$ or the total area $A$ is usually given, thus we can write down:
$$
\begin{gather*}
M\bar{y} = \frac{1}{2}\int_{a}^{b}\rho\left[f(x)\right]^{2}dx \\ \\
\boxed{A\bar{y} = \frac{1}{2}\int_{a}^{b}\rho\left[f(x)\right]^{2}dx}
\end{gather*}
$$

# Example 1
Find the coordinates of the centre of mass of the uniform lamina defined by the equation $y=4-x^{2}$, bounded by the curve and the positive $x$ and $y$ axis.
![[Pasted image 20260218124314.png]]
The x-intercept of the curve is $x=2$. Thus our limits are from $0$ and $2$. We first need to find out the total area of the lamina:
$$
\begin{gather*}
A = \int_{0}^{2}(4-x^{2}) = \left[4x-\frac{1}{3}x^{3}\right]_{0}^{2} = 4(2)-\frac{1}{3}(2)^{3} = \frac{16}{3}
\end{gather*}
$$
Now we can use the value of $A$ to find out $\bar{x}$ using the above formula
$$
\begin{gather*}
\frac{16}{3}\bar{x} = \int_{0}^{2}x(4-x^{2})dx \\ \\
\frac{16}{3}\bar{x} = \int_{0}^{2}(4x -x^{3})dx \\ \\
= \left[2x^{2} -\frac{1}{4}x^{4} \right]_{0}^{2} = 2(2)^{2} - \frac{1}{4}(2)^{4} = 4  \\ \\
\therefore \bar{x} = \frac{3}{4}
\end{gather*}
$$
Now we do the same thing to calculate $\bar{y}$, however this time being careful to multiply $\frac{1}{2}f(x)$ instead of $x$ on the right hand side:
$$
\begin{gather*}
\frac{16}{3}\bar{y} =  \frac{1}{2} \int_{0}^{2}(4-x^{2})(4-x^{2})dx   \\ \\
\frac{16}{3}\bar{y} = \frac{1}{2}\int_{0}^{2}(4-x^{2})^{2}dx \\ \\ 
= \frac{1}{2}\int_{0}^{2}(16-8x^{2}+x^{4})dx \\ \\ 
= \frac{1}{2}\left[16x -\frac{8}{3}x^{3}+\frac{1}{5}x^{5}\right]_{0}^{2} = \frac{1}{2}\left(16(2)-\frac{8}{3}(2)^{3}+\frac{1}{5}(2)^{5}\right) = \frac{128}{15} \\ \\
\therefore \bar{y} = \frac{8}{5}
\end{gather*}
$$
Thus the centre of mass is at:
$$
\boxed{ \left( \frac{3}{4}, \frac{8}{5} \right)}
$$
# Example 2
A uniform lamina ABCD is bounded by the curve $y=16e^{-2x}$. The x-axis and $x=\ln2$ and $x=\ln 4$. The area of ABCD is $\frac{3}{2}$. Find the coefficients of the CoM and the angle that AB makes with the downward vertical when the lamina is suspended from A. 
![[Pasted image 20260218125520.png]]
For this question, you need to first work out the centre of mass and then treat it as a regular suspension problem by drawing the line of suspension from A and considering the triangle formed in doing so.

The total area $A$ is given to us as $\frac{3}{2}$, thus we do need to work out the total area and can use the formula directly to find out $\bar{x}$, being careful to multiply by $x$ on the right hand side:
$$
\frac{3}{2}\bar{x} = \int_{\ln 2}^{\ln 4} x 16e^{-2x}
$$
Now $\int x 16e^{-2x}$ is integration by parts:
$$
\begin{gather*}
u = x \qquad  \frac{dv}{dx} = 16e^{-2x}\\ \\
\frac{du}{dx} = 1 \qquad v = -8e^{-2x} \\ \\ \\
\int 16e^{-2x}dx = -8xe^{-2x} - \int-8e^{-2x} \\ \\
= -8xe^{-2x} - 4e^{-2x} +c
\end{gather*} 
$$
Thus we can substitute the result of the integral back into the brackets but disregarding the constant of integration:
$$
\frac{3}{2}\bar{x}  = \left[ -8xe^{-2x} - 4e^{-2x}\right]_{\ln 2}^{\ln 4} = \left(\right)
$$