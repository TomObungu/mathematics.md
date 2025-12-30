## $\int x^{2}e^{x^{3}}$
The case of  $\int x^{2}e^{x^{3}}$ is a special case as it can be evaluated entirely using reverse chain rule. Being able to do this can also simplify doing a similar integration by parts problem. 

Do not be haste to try and do integration by parts but instead consider $y=e^{x^{^{3}}}$ . Do not try $y=e^{n+1}$ but $y=e^{n}$:
$$
3
$$
Therefore:
$$
\int x^{2}e^{x^{3}} = \frac{1}{3}e^{x^{3}}
$$
In general if you ever see something in the form $x^{n}e^{n+1}$ always try $e^{n+1}$

## $\int x^{5}e^{x^{3}}$
This problem is much like the previous problem, instead you must split the components into a polynomial factor and $e^{x^{3}}$ multiplied by a polynomial factor with one less power than the $x^{2}$ terms. Reduce the $x^{5}$ until you have $x^{3}(x^{2}e^{x^{3}})$, the integrate by parts with $u=x^{3}$:
$$ 
\begin{gather*}
I =\int x^{2}(x^{3}e^{x^{3}}) dx \\ \\
u = x^{2} \qquad \frac{dv}{dx} = x^{2}e^{x^{3}} \\ \\
\frac{du}{dx } = 2x \qquad v = \frac{1}{3}e^{x^{3}} \\ \\
I = \frac{1}{3} x^{2}e^{x^{3}}- \frac{2}{3} \int xe^{x^{3}}
\end{gather*}
$$

## $\int \frac{1}{1+\cos x}$


## $\int \frac{\sin x}{\sin x+\cos x}$


## $\int \sqrt{ x^{2}+2x }$


