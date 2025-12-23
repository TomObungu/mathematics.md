It can be shown that:
$$
\int \frac{1}{a^{2}-x^{2}} = \frac{1}{2a}\ln\left|  \frac{a+x}{a-x}\right| + c
$$

# Proof
This case can be proved using partial fractions and then integrating:
$$\begin{gather*}
\frac{1}{a^{2}-x^{2}} = \frac{1}{(a+x)(a-x)} \\ \\
= \frac{A}{(a+x)} + \frac{B}{(a-x)} \\ \\
1 = A(a-x) + B(a+x) \\ \\
\text{Let } x = -a: \\ 
1 = 2aA  \\
A = \frac{1}{2a} \\ \\
\text{Let } x = a: \\ \\
1 = -2aB \\ 
B = -\frac{1}{2a} \\ \\
\frac{1}{a^{2}-x^{2}} = \frac{\frac{1}{2a}}{a+x}-\frac{\frac{1}{2a}}{a-x}
\end{gather*}
$$
Thus writing the form and integrating:
$$
\begin{gather*}
\int \frac{1}{a^{2}-x^{2}} = \int \frac{\frac{1}{2a}}{a+x}-\frac{\frac{1}{2a}}{a-x} \\ \\
= \frac{1}{2a}\ln|a+x| - \frac{1}{2a}\ln|a-x| + c
\end{gather*}
$$
Simplifying using rules of logarithms:
$$
\boxed{ \frac{1}{2a}\ln\left| \frac{a+x}{a-x} \right| + c}
$$

--- 

As well as that, if the denominator or a partial fraction includes a a quadratic factor of the term $(x^{2}+c)$ you cannot write it as a product of linear factors with real coefficients. 

However, it is possible to write it in partial fractions, where the partial fraction corresponding to the quadratic factor has a linear numerator and a quadratic denominator. 

![[Pasted image 20251223074509.png]]

Find the values of $A$ and $B$ by multiplying both sides and comparing coefficients.
![[Pasted image 20251223074546.png]]

## Worked Example 1
![[Pasted image 20251223074846.png]]
Start by expressing the rational function as partial fractions, with linear terms for any denominator in the form $(x^{2}+c)$, $c>0$:
$$
\frac{1+x}{x(x^{2}+9)} = \frac{A}{x} + \frac{Bx+c}{x^{2}+9}
$$

Notice that if the denominator is a linear term, you expression the variable numerator as a constant
$$
\frac{A}{x+c}
$$

If the denominator is a quadratic terms that cannot be expressed is a product of linear terms, write the variable numerator as a linear terms:
$$
\frac{Bx+d}{x^{2}+k}
$$

If the denominator were to be 