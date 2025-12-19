An integral is considered 'improper' if:
- The function is undefined at one of the limits or in-between them, e.g. $\int_{0}^{5} \frac{1}{x}dx$
- One or both of the limits are infinite e.g. $\int_{2}^{\infty} \frac{2}{x^{3}}dx$ 

They can be evaluated by defining the improper integral as the limit of a sequence that approach it. If that limit exists, the integral is convergent and we say that it has the value of the limit.

If the limit does not exist, i.e one or more of the limits tends to $\infty$, the the integral is said to be divergent. 

The main bulk of improper integrals is the actual integration of the function.


# Worked Example 1
![[Pasted image 20251209111538.png]]

For the case of $\int_{1}^{\infty} \frac{1}{x^{2}}$:
Firstly, replace the infinite limit with a variable $t$ and consider the variable as $t$ approaches $\infty$:
$$
\begin{gather*}
\lim_{ t \to \infty } \left\{ \int_{1}^{t} \frac{1}{x^{2}}\right\} \\ \\
= \lim_{ t \to \infty } \left\{ [-x^{-1}]_{1}^{t}\right\} \\ \\
= \lim_{ t \to \infty } \left\{ -t^{-1}+1^{-1}\right\} \\ \\
=\lim_{ t \to \infty } \left\{1 -\frac{1}{t}\right\} 
\end{gather*}
$$
It is always best practice to try and get expressions simplified into fractions before considering limits:
$$
\begin{gather*}
\text{As }t\to \infty, \frac{1}{t}\to 0
\end{gather*}
$$
Therefore:
$$
\lim_{ t \to \infty } \left\{1 -\frac{1}{t}\right\}  = 1
$$
Thus the integral can be evaluated as the value of the limit which is $1$:
$$
\int_{1}^{\infty} \frac{1}{x^{2}} = 1
$$


For the case of $\int_{1}^{\infty} \frac{1}{x}dx$:
Replace, the infinite limit with a variable $t$ and consider the limit as $t$ approaches $\infty$:
$$
\begin{gather*}
\lim_{ t \to \infty } \left\{ \int_{1}^{t} \frac{1}{x}\right\} \\ \\
= \lim_{ t \to \infty } \left\{ [\ln x]_{1}^{t}\right\} \\ \\
= \lim_{ t \to \infty } \left\{ \ln t-\ln 1\right\} \\ \\
=\lim_{ t \to \infty } \left\{\ln t\right\} 
\end{gather*}
$$
$$
\text{As } t\to \infty, \ln t\to \infty
$$
Therefore:
$$
\text{The limit does not exist}
$$
Thus:
$$
\therefore \int_{1}^{\infty} \frac{1}{x}dx \text{ is divergent}
$$

# Worked Example 2 - Both limits are undefined/infite
![[Pasted image 20251209114919.png]]
In these types of questions, it is good to firstly handle the integral without the limits:

Integration by u-substitution (reverse chain rule):
$$
\begin{gather*}
\int xe^{-x^{2}} \\ \\
u = -x^{2} \qquad \frac{du}{dx} = -2x \\ \\
\frac{du}{-2x} = dx \\ \\
\int \cancel{ x }e^{u} \frac{du}{-2\cancel{ x }} \\ \\
 -\frac{1}{2}\int e^{u}dx \\ \\
 = -\frac{1}{2}e^{u} + c \\ 
 = -\frac{1}{2}e
\end{gather*}
$$

## Worked Example 3 - Integral with absolute value in it:
![[Pasted image 20251219125749.png]]
For the special problem, you first need to identify the limits 