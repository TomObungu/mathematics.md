A first order differential equation (DE) contains only a first derivative in the equation. The equation below is a first order DE:
$$
\frac{dy}{dx}+3y=6x
$$
It is possible to write DEs using Lagrangian notation as a means of simplification. $y'$ denotes and first derivative, $y''$ denotes a second order derivative an so on:
$$
y''-4y'+4y=e^{x}
$$
# Linear vs non-linear DEs
A linear DE has the form:
$$
a_{0}+a_{1}y'+a_{2}y''+\dots=b
$$
Where $a_{0},a_{1},\dots,a_{n}$ are constant or factors of x. The equation below is an example of a non-linear equation:
$$
y'+xy^{2}=1
$$
However the equation below is not linear:
$$
y'=\cot y
$$
# Solutions to DEs
A solution of a DE is a function of $x$, which if substituted into the DE, will yield an identity.  For example:
$$
y'=\cos x
$$
has a solution;
$$
y=\sin x+c
$$
This is verifiable as if we substitute $y$ back into the DE, we will get an identity:
$$
\begin{gather*}
y' = \cos x \\ \\
(\sin x+c)' = \cos x \\ \\
\cos x = \cos x
\end{gather*}
$$
Another example containing a simple second order differential equation is the DE:
$$
y''=5
$$
The solution is $y=\frac{5}{2}x^{2}+cx+d$. Substituting this back into the equation yields an correct identity:
$$
\begin{gather*}
\left( \frac{5}{2}x^{2}+cd+d \right)''=5  \\ \\
\end{gather*}

$$
## Arbitrary Constants
In the first example above, the solution has one arbitrary constant $c$. This is the result of integrating once.

In the second example, we performed two integrations so there are two arbitrary constants $c$ and $d$

In general, an $nth$ order $DE$ has solution containing $n$ arbitrary constants. This is called the general solution.

## Bound conditions and Particular solutions
Boundary conditions (BC) are pieces of information that allow the determination of the values of the arbitrary constants. An $nth$ order DE needs $n$ BCs.

Looking at the second example, let's say the boundary conditions were:
$$
y(0)=0, \qquad y'(0)=0
$$
Plugging $y'(0)=0$ into the integral of second order derivative:
$$
5(0)+c = 0 \implies c =0
$$
Plugging $y(0)=0$ and $c=0$ into the integral of the first derivative gives:
$$
\frac{5}{2}(0)^{2}+d=0 \implies d =0
$$
Therefore the particular solution for the BC is:
$$
y = \frac{5}{2}x^{2}
$$
The particular solution is a solution to the DE that satisfies a particular set of BC. Usually these are physical constraints of a system such as initial velocity etc.

# Solving first order DEs
In A-level mathematics, we learnt about solving differential equations. E.g.:
$$
\begin{gather*}
x\frac{dy}{dx} = y+1 \\ \\
\frac{1}{x} \frac{dx}{dy} = \frac{1}{y+1} \\ \\
\int \frac{1}{x} dx = \int \frac{1}{y+1}dy \\ \\
\ln|x| +c = \ln|y+1| \\ \\
\ln|y+1| = \ln|ax| \\ \\
y = ax-1
\end{gather*}
$$
## Exact DE
Now, to kick off the start the DE topic, we will start off with exact DEs. A DE in exact form is:
$$
y'+P(x)y=Q(x)
$$
We need to get equations into this form before we can solve them. I.e We might have to divide by a factor of $x$ in order to leave $y'$

# Integrating factor
Lets assume that there exists a function, $f(x)$ that we can multiply a DE in standform by such that it will transform it into an exact DE:
$$
f(xy'+f(x)P9
$$