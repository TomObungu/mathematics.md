## $\int x^{2}e^{x^{3}}$
The case of  $\int x^{2}e^{x^{3}}$ is a special case as it can be evaluated entirely using reverse chain rule. Being able to do this can also simplify doing a similar integration by parts problem. 

Do not be haste to try and do integration by parts but instead consider $y=e^{x^{^{3}}}$ . Do not try $y=e^{n+1}$ but $y=e^{n}$:
$$
\begin{gather*}
y = e^{x^{3}} \\ \\
\frac{dy}{dx} = 3x^{2}e^{x^{3}}
\end{gather*}
$$
Therefore:
$$
\int x^{2}e^{x^{3}} = \frac{1}{3}e^{x^{3}}
$$
In general if you ever see something in the form $x^{n}e^{n+1}$ always try $e^{n+1}$

## $\int x^{5}x^{x^{3}}$
This problem is much like the previous problem, instead you must split the components into 



## $\int \frac{1}{1+\cos x}$



## $\int \frac{\sin x}{\sin x+\cos x}$


## $\int \sqrt{ x^{2}+2x }$



$$
\begin{gather*}
\int \frac{3}{x^{2}-4}dx \qquad x =2\sec u \qquad dx = 2\sec u\tan u du \\ \\
=\int \frac{3}{4\tan ^{2}u}2\sec u\tan u du \\ \\
= \int \frac{3}{2} \csc u du \\ \\
= \frac{3}{2}\ln|\csc u - \cot u| +c
\end{gather*}
$$
My rearranging process:
$$
\begin{gather*}
\frac{1}{x} = \frac{1}{2}\cos u  \\ \\
\frac{4}{x^{2}} = \cos ^{2}u \\ \\
1-\frac{4}{x^{2}} = 1-\cos ^{2}u \\ \\
\sqrt{ \frac{x^{2}}{x^{2}-4} } = \csc u \\ \\ \\
\cot u = \csc u \cos u \\ \\
= \frac{2}{x} \sqrt{ \frac{x^{2}}{x^{2}-4} }  
\end{gather*}
$$
Thus:
$$
\int \frac{3}{x^{2}-4}dx  = \frac{3}{2}\ln\left| \sqrt{ \frac{x^{2}}{x^{2}-4} }\left( 1-\frac{2}{x} \right)  \right| + c
$$
 