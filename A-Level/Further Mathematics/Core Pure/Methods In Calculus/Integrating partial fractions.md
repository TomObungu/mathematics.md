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

If the denominator is a quadratic terms that cannot be expressed is a product of real linear terms, write the variable numerator as a linear terms:
$$
\frac{Bx+d}{x^{2}+k}
$$

## Cubics 
If the denominator were to be a cubic that cannot be factored into the product of real linear terms:
 
 e.g. $x^{3}+x$,  it can either be factored into the product of a linear and an irreducible quadratic in the form  $(x^{2}+c), c>0$ 
 $$
\frac{1}{x^{3}+x} = \frac{1}{x(x^{2}+1)} = \frac{A}{x} + \frac{Bx+C}{x^{2}+1}
$$
e.g $x^{3}+2x^{2}+5x$ , which can be factored in the product of a quadratic and hence be solved using other techniques:
$$
\frac{1}{x^{3}+2x^{2}+5x} = \frac{1}{x(x^{2}+2x+5)}
$$

## Quartics and higher
You can also see that if the denominator were a **quartic** that cannot be factored into the product of real linear terms and that is not easily factorable 
e.g $x^{4}+5$, then you can write the numerator as a cubic term:
$$
\frac{1}{x(x^{4}+5)} = \frac{A}{x} + \frac{Bx^{3}+Cx^{2}+Dx+E}{x^{4}+5}
$$
NOTE: According to a fundamental rule of algebra, every polynomial with real coefficients can be factored into a product of linear and irreducible quadratic factors. In the example above, it possible to take the approach of factoring $x^{4}+5$ into irreducible quadratics and writing the numerator as linear terms, e.g.:
$$
x^{4}+5 = (x^{2}+\sqrt{ 2\sqrt{ 5 } }+\sqrt{ 5 })(x^{2}-\sqrt{ 2\sqrt{ 5 } }+\sqrt{ 5 })
$$
Then:
$$
\begin{gather*}
\frac{1}{x(x^{4}+5)} = \frac{1}{x(x^{2}+\sqrt{ 2\sqrt{ 5 } }+\sqrt{ 5 })(x^{2}-\sqrt{ 2\sqrt{ 5 } }+\sqrt{ 5 })} \\ \\ 
= \frac{A}{x} + \frac{Bx+C}{(x^{2}+\sqrt{ 2\sqrt{ 5 } }+\sqrt{ 5 })} + \frac{Dx+E}{(x^{2}-\sqrt{ 2\sqrt{ 5 } }+\sqrt{ 5 })}
\end{gather*}
$$
Which can then be solved. However this deals with irrational coefficients.