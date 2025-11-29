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
## Exact DEs
Now, to kick off the start the DE topic, we will start off with exact DEs. Consider the equation:
$$
xy'+y=e^{x}
$$
Notice, that the LHS of this equation is the product rule from the derivative of $xy$. Recall from the product rule that:
$$
\frac{d}{dx}(xy) = xy'+y
$$
Thus, from this we can substitute $\frac{d}{dx}(xy)$ into the left side of the equation:
$$
\frac{d}{dx}(xy)=e^{x}
$$
From then onwards, integrating will give the solution to the differential equation:
$$
\begin{gather*}
xy = \int e^{x}dx \\ \\
xy = e^{x} \\ 
\boxed{y=\frac{e^{x}}{x}}
\end{gather*}
$$

**DEs where the LHS is the derivative of a product are called exact differential equations**

# Standard Form
The standard form a linear first order DE is:
$$
y'+P(x)y=Q(x)
$$
We need to get equations into this form before we can solve them. I.e We might have to divide by a factor of $x$ in order to leave $y'$
# Integrating factor
Lets assume that there exists a function, $f(x)$ that we can multiply a DE in standard form by, such that it will transform it into an exact DE.
$$
f(x)y'+f(x)P(x)y=f(x)Q(x)
$$
Let's take a process of trying to find $f(x)$. If we know that the LHS is the derivative of the product $f(x)y$. If we know that the derivative of $f(x)y$ is:
$$
f(x)y' + f'(x)y
$$
Then by comparing the equation for the exact DE $f(x)y'+f(x)P(x)y=f(x)Q(x)$, we can see that in order for the equation to hold being a the derivative of a product:
$$
f'(x) = f(x)p(x)
$$
Therefore, if we rearrange and integrate, we can find $f(x)$:
$$
\begin{gather*}
p(x) = \frac{f'(x)}{f(x)} \\ \\
\int p(x) = \int \frac{f'(x)}{f(x)} \\ \\
\int p(x) = \ln|f(x)| \\ \\
\end{gather*}
$$
Therefore, the function $f(x)$ can be found as:
$$
\boxed{f(x)=e^{\int p(x)}}
$$
Where $p(x)$ is the function multiplying $y$ in the equation. This is the integrating factor (IF). The constant is ignored as when multiplying by $f(x)$ to make the DE exact, the constants will be on both sides and cancel out.

Multiplying a DE in **standard form** by the IF gives an exact DE:
$$
\begin{gather*}
\frac{d}{dx}[f(x)y]=f(x)Q(x) \\ \\
\implies f(x)y=\int f(x)Q(x)dx + c \\ \\
\therefore \boxed{y = \frac{\int f(x)Q(x)dx + c }{f(x)}}
\end{gather*}
$$

# Worked Example 1
Find the solution to:7
![[Pasted image 20251129230346.png]]
For questions like this, we want to get get the equation in standard form:
$$
\begin{gather*}
xy' + 3y = \frac{e^{x}}{x^{2}} \\ \\
y'+\frac{3}{x}y=\frac{e^{x}}{x^{3}}
\end{gather*}
$$
Now it is in standard form, work out the integrating factor $f(x)$:
$$
\begin{gather*}
f(x) = e^{\int \frac{3}{x}} \\ \\
= e^{3ln|x|} \\ \\
= e^{\ln|x^{3}|} \\ \\
= x^{3}
\end{gather*}
$$
Therefore the resultant product with the equation will be:
$$
\begin{gather*}
x^{3}y = \int \frac{e^{x}}{\cancel{ x^{3} }}(\cancel{ x^{3}) } \\ \\
\end{gather*}
$$
Thus the solution to the DE is:
$$
\begin{gather*}
x^{3}y=e^{x} + c\\ \\
\therefore \boxed{y = \frac{e^{x}}{x^{3}} +\frac{c}{x^{3}}}
\end{gather*}
$$
# Worked Example 1
Find the solution to
![[Pasted image 20251129230920.png]]
Getting equation in standard form:
$$
\begin{gather*}
y' +\frac{2}{x}y=\frac{\sin x}{x^{2}}
\end{gather*}
$$
Finding the integrating factor:
$$
\begin{gather*}
f(x) = e^{\int \frac{2}{x}} \\ \\
= e^{\ln|x^{2}|} = x^{2} \\ \\
\end{gather*}
$$
Find the product and integrating:
$$
\begin{gather*}
x^{2}y = \int \frac{\sin x}{\cancel{ x^{2} }} (\cancel{ x^{2} }) \\ \\
\boxed{x^{2}y=-\cos x+c}
\end{gather*}
$$
# Worked Example 3