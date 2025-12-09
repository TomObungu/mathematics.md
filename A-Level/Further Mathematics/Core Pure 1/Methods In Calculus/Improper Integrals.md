An integral is considered 'improper' if:
- The function is undefined at one of the limits or in-between them, e.g. $\int_{0}^{5} \frac{1}{x}dx$
- One or both of the limits are infinite e.g. $\int_{2}^{\infty} \frac{2}{x^{3}}dx$ 

They can be evaluated by defining the improper integral as the limit of a sequence that approach it. If that limit exists, the integral is convergent and we say that it has the value of the limit.

If the limit does not exist, i.e one or more of the limits tends to $\infty$, the the integral is said to be divergent. 

The main bulk of improper integrals is the actual integration of the function.


# Worked Example 1
![[Pasted image 20251209110551.png]]

Firstly, replace the infinite limit with a variable $t$ and consider the variable as it approaches $\infty$:
$$
\begin{gather*}
\lim_{ t \to \infty } \left\{ \int_{1}^{t} \frac{1}{x^{2}}\right\} \\ \\
= \lim_{ t \to \infty } \left\{ [-x^{-1}]_{1}^{t}\right\} \\ \\
= \lim_{ t \to \infty } \left\{ -t^{-1}+1^{-1}\right\} \\ \\
=\lim_{ t \to \infty } \left\{1 -\frac{1}{t}\right\} 
\end{gather*}
$$
It is always best practice to try and get expressions simplified into fractions. 