Many functions can be written as an infinite sum of terms of the form $ax^{n}$. For example, throw back to the binomial expansion from A-Level:
$$
\begin{gather*}
(1-x)^{-1}=\frac{1}{1-x} = 1+x+x^{2}+x^{3}\dots, |x|<1 \\ \\
(1-x)^{\frac{1}{2}} = \sqrt{ 1-x } = 1+\frac{x}{2} + \frac{x^{2}}{8} + \frac{x^{3}}{16}\dots, |x| < 1 \\ \\
\end{gather*}
$$
As well as that, you have known:
$$
e^{x} = 1+x+\frac{x^{2}}{2} + \frac{x^{3}}{6}+\frac{x^{4}}{24}+\dots, x \in \mathbb{R}
$$
# Derivation of Maclaurin Series 
Given that a function $f(x)$,  can be differentiated infinitely many times and that is has a valid series expansion of the form $f(x) = a_{0}+a_{1}x+a_{2}x^{2}+a_{3}x^{3}\dots,a_{r}x^{r}\dots ,$ where $a_i$ are all real constants, it is possible to show that:
$$
\begin{gather*}
f(0) = a_{0}
\end{gather*}
$$
Differentiating $f(x)$ gives:
$$
\begin{gather*}
f'(x) = a_{1} + 2a_{2}x+3a_{3}x^{2}+\dots+ ra_{r}x^{r-1} +\dots\\ \\
f''(x) = 2(1)a_{2} + 3(2)a_{3}x+ 4(3)a_{4}x^{r-1} + \dots +r(r-1)a_{r}x^{r-2} +\dots \\ \\
f'''(x) = (3)(2)(1)a_{3}+ 4(3)(2)a^{4}x +\dots + r(r-1)(r-2)a_{r}x^{r-3} +\dots
\end{gather*}
$$
By continuing in this way by differentiating $r$ times, we can show that at every term at $x=0$ can be evaluated in the form:
$$
f^{r}(0) = r!a_{r}
$$
Thus:
$$
\begin{gather*}
f'(0) = a_{1}  \\ \\
f''(0) = 2!a_{2} \implies a_{2} =  \frac{f''(0)}{2!} \\ \\
f'''(0) = 3!a_{3} \implies a_{3} = \frac{f'''(0)}{3!} \\ \\
f^{r}(0) = r!a_{r} \implies a_{r} = \frac{f^{r}(0)}{r!}
\end{gather*}
$$
There evaluating the coefficients in the series expansion for $f(x)$ gives:
$$
f(x) = f(0) + f'(0)x + \frac{f''(0)}{2!}x^{2} + \frac{f'''(0)}{3!}x^{3} +\dots +\frac{f^{r}(0)}{r!}x^{r}\dots +
$$
In this process, a polynomial of powers of x is being formed step by step. The process focuses on $x=0$. Substituting $x=0$ into successive derivatives increases the power of the polynomial. For example, if you stop  after $f'(0)$, the polynomial is linear - $f(0)+f'(0)x+$. If you stop after $f''(0)$, the polynomial is quadratic - $f(0) + f'(0)x + \frac{f''(0)}{2!}x^{2}$, after $f'''(0)$ it is cubic and so on.

The above argument assumes that function can be written in the given form: $f(x) = a_{0}+a_{1}x+a_{2}x^{2}+a_{3}x^{3}\dots,a_{r}x^{r}\dots ,$ . However this only true if the given series converges. 

The above argument also holds if the function can be differentiated an infinite number of times and the value of $f^{r}(0)$ is always finite - that is it is always defined.

An example of a continuously differentiable function that is not defined at all values of $f^{r}(0)$ is $f(x)=\ln x$  .  When differentiating $f'(x)= \frac{1}{x}$, $f'(0)$ is undefined and does not have a finite value.

Therefore **the Maclaurin series expansion of a function $f(x)$ is given by:

$$
\boxed{f(x) = f(0)+f'(0)x + \frac{f''(0)}{2}x^{2} + \frac{f'''(0)}{3!}x^{3}+\dots +\frac{f^{r}(0)}{r!}x^{r}+\dots}
$$
**The series is valid provided that $f(0), f'(0), f''(0), \dots,f^{r}(0),\dots$ all have finite values. 

As well as that the series is only valid for values of $x$ that give rise to a convergent series expansion. 

E.g. The Macluarin series of $\frac{1}{1-x}$ is $1+x+x^{2}+x^{3}+\dots$, but when $x=2$, the series gives $1+2+4+8\dots$ which is divergent. Thus $\frac{1}{1-x}$ only converges when $|x|<1$


# Worked Example 1
![[Pasted image 20251229102613.png]]
$$
\begin{gather*}
f(x) = \ln(1+x) \qquad f(0) = \ln 1 = 0 \\ \\
f'(x) = (1+x)^{-1} \qquad f'(0) = 1\\ \\
f''(x)= (-1)(1+x)^{-2} \qquad f''(0) = -1 = -1!\\ \\
f'''(x = (-1)(-2)(1+x)^{-3} \qquad f'''(0) = 2 = 2!\\ \\
\dots
f^{r}(x) = (-1)^{r-1}(r-1)!(1+x)^{-r} \qquad f^{r}(0)= (-1)^{r-1}(r - 1)!
\end{gather*}
$$

Note that $(-1)^{r}$ can be used to represent an alternating series of negative to positive, for $r\geq 1, r \in \mathbb{Z}$

The same for $(-1)^{r-1}$ can be used to represent an alternating series of positive to negative, for $r \geq 1, r \in \mathbb{Z}$

Thus the Macluarin expansion for $1+x$ is:
$$
\begin{gather*}
f(x) = f(0) + f'(0)x + \frac{f''(0)}{2!}x^{2}+\frac{f'''(0)}{3!}x^{3}+\dots+ \frac{f^{r}(0)}{r!}x^{r} \\ \\
f(x) = 0 + x - \frac{1!}{2!}x^{2} + \frac{2!}{3!}x^{3} +\dots+ (-1)^{r-1}\frac{(r-1)!}{r!}x^{r} +\dots\\ \\ 
f(x) = x-\frac{1}{2}x^{2} + \frac{1}{3}x^{2}-\frac{1}{4}x^{4} +\dots (-1)^{r-1}\frac{1}{r}x^{r}+\dots
\end{gather*}
$$



 