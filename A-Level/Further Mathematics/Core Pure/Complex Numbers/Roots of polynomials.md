A polynomial with real coefficients is a combination of exponentiation, multiplication by a real scalar and addition.

For a polynomial, p:
$$
p(z) = w \implies p(z^{*}) = w^{*}
$$

This only works for real coefficients as if $p$ had complex coefficients for the above to true, we would need to have to conjugate the coefficients. If we did that, we would no longer have the same polynomial and the function will not work.
$$
\therefore p(z) = 0 \implies p(z^{*})=0 
$$
This means that if $z$ is a root of $p$ so is $z^{*}$. 

**Therefore this means that complex roots of polynomials with real coefficients always occur in conjugate pairs**

From the fundamental theorem of algebra, an $nth$ degree polynomial has $n$ roots. 

We can use the statement to determine the nature of the roots of different polynomials. 

## Quadratics
A quadratic equation of the form, $az^{2}+bz+c, \  a,b,c\in \mathbb{R}$ has either:
- Two real roots
	- ![[Pasted image 20251110092549.png]]
- A complex conjugate pair of roots
	- ![[Pasted image 20251110092557.png]]

# Worked Example 1
Find the roots the equation $z^{2}-2z+5=0$.

For this type of questions, always complete the square and compute for any multiples of $i$. It is also possible to use the discriminant to determine if the quadratic has roots beforehand if it isn't stated.
$$
\begin{gather*}
z^{2}-2z+5 = 0 \\ 
(z-1)^{2}+4 = 0 \\ 
(z-1)^{2} = -4 \\ 
z-1 = \pm_{2}i \\ \\
z_{1} = 1+2i \qquad z_{2} = 1-2i
\end{gather*}
$$

# Worked Example 2
Given that $z=3+2i$ is a root of the equation $z^{2}+bz+c=0$, find the other root and the equation.

We know that complex roots of quadratics come in conjugate pairs. Therefore:
$$
z_{1} = 3+2i \qquad z_{2} = 3-2i 
$$
Knowing this, it possible to substitute these roots back into the bracket form of the quadratic equation:
$$
\begin{gather*}
\therefore (z-(3+2i))(z-(3-2i)) = 0 \text{ are both factors } \\ \\
z^{2}-(3-2i)z-(3+2i)z+(3+2i)(3-2i) \\ \\
\therefore z^{2}-6z+13 = 0
\end{gather*}
$$
The shortcuts used in this case are:
$$
\begin{gather*}
(x+iy)(x-iy) = x^{2}+y^{2} \\ \\
(x+iy)^{2} = x^{2}-y^{2}+2ixy
\end{gather*}
$$

# Useful rule
For an equation of the form $z^{2}+bz+c=0$, with roots $\alpha$ and $\beta$:
$$
\begin{gather*}
(z-\alpha)(z-\beta) = 0 \\ 
z^{2}-\beta z-\alpha z+a\beta \\
z^{2}-(\alpha+\beta)z+\alpha \beta \\ \\
\end{gather*}
$$
Now if $\alpha=(x+iy)$ and $\beta=(x-iy)$... We know that $z+z^{*} = 2x$ and $zz^{*}=x^{2}+y^{2}$ then:
$$
\begin{gather*}
z^{2}-(\alpha+\beta)z +\alpha \beta = 0 \\ \\
\implies z^{2}-(2x)z+(x^{2}+y^{2})=0
\end{gather*}
$$
Applying this rule to given roots e.g. $z_{1}=3+2i$ $z_{2}=3-2i$, then the quadratic equation for these roots are:
$$
\begin{gather*}
z^{2}-(2(3))z+(3^{2}+2^{2}) = 0 \\ 
z^{2}-6z+13=0
\end{gather*}
$$
## Worked Example 3
Given taht $-2-4i$ is a root of quadratic equation $z^{2}+bz+c=0$, find the equation.

Using the useful rule:
$$
\begin{gather*}
z^{2}-(2(-2))z+((-2)^{2}+4^{2}) = 0 \\
z^{2}+4z+20
\end{gather*}
$$

# Cubics
A cubic equation of the form: $ax^{3}+bx^{2}+cx+d$ has either
- Three real roots
- One real root and one complex conjugate pair of roots

Real roots all lie on the $\mathrm{Re}$ axis
![[Pasted image 20251110094635.png]]
Or two roots lie on the $\mathrm{Im}$ axis and one on the $\mathrm{Re}$ axis. 
The shape that these roots form will either be a triangle or a straight line
![[Pasted image 20251110094649.png]]

# Worked Example 4
Given that one of the roots of equation $z^{3}+bz^{2}+cz-120=0$ is $4+2i$, find the other two roots and the full equation:

We know that the other root will be a conjugate and that the other real root will be come constant $a$:
$$
z_{1}=4+2i, z_{2}=4-2i, z_{3}=a
$$
We know that a cubic can be composed of a quadratic like this: $(z^{2}+bz+c)(z-a)$, we can substitute the complex roots into the brackets of the quadratic:
$$
\begin{gather*}
(z-(4+2i))(z-(4-2i))(z-a) = 0 \\ \\
(z^{2}-8z+20)(z-a) = 0 \\ 
\end{gather*}
$$
We know that after expanding we will get a cubic of the form 
$$
\begin{gather*}
z^{2}-8z+20)(z-a) = z^{3}+bz^{2}+cz-120 
\end{gather*}
$$
Therefore we know the only coefficient we can compare is after multiplying $-20a$. This coefficient will be equal to $120$. Therefore we can solve for $a$:
$$
\begin{gather*}
-20a = 120 \\ 
a = 6
\end{gather*}
$$
Substituting $a=6$ back into the brackets gives:
$$
\begin{gather*}
(z^{2}-8z+20)(z-6) \\ 
z^{3}-8z^{2}+20z-6z^{2}+48z-120 = 0 \\ \\
\boxed{z^{3}-14z^{2}+68z-120}
\end{gather*}
$$
# Worked Example 5
Given that $z^{3}-5z^{2}+pz-78=0$ has one real roof of $3$, find the two other roots and the full equation:

We know that a cubic will be in form $(z-3)(z^{2}+bz+c)=0$
$$
\begin{gather*}
(z-3)(z^{2}+bz+c) = 0 \\ \\
z^{3}+bz^{2}+cz-3z^{2}-3bz-3c=0 \\ 
z+(b-3)z^{2}+(c-3b)z-3c=0 \\ \\
\end{gather*}
$$
Comparing coefficients with $z^{3}-5z^{2}+pz-78=0$:
$$
\begin{gather*}
b-3 = -5 \implies b = -2 \\ \\
-3c = 78 \implies c = 26 \\ \\
c-3b \implies 26 + 6 = p \implies p = 32
\end{gather*}
$$
Finding roots of $z^{2}-2z=26=0$ gives:
$$
\begin{gather*}
(z-1)^{2}+25=0 \\
\therefore(z-1)^{2}=-25 \\
z_{2} = 1+5i, z_{3} = 1-5i 
\end{gather*}
$$
Therefore the final equation is:
$$
z^{3}-5z^{2}+32z-78=0
$$
# Worked Example 6
The roots of the equation $az^{3}+bz^{2}+cz+d=0$ form a vertical line. Given that one root is $-8-i$, find the full equation.

If the roots form a vertical line then it means real part of all the coordinates is the same:
![[Pasted image 20251110162652.png]]
As complex roots always come in conjugate pairs this means the roots to the equations are $z_{1}=-8$, $z_{3}=-8-i$, $z_{3}=-8+i$:
Forming the quadratic equation from the conjugate equations and the real root gives:
$$
\begin{gather*}
(z^{2}+16z+65)(z+8) \\
z^{3}+16z^{2}+65z+8z^{2}+128z+520 \\
z^{3}+24z^{2}+193z+520=0
\end{gather*}
$$
# Quartics
A quartic equation of the form: $ax^{4}+bx^{3}+cx^{2}+dx+e=0$ has either:
- Four real roots
- Two reals roots and one conjugate pair
- Two complex conjugate pairs

![[Pasted image 20251110163144.png]]


# Worked Example
$z^{4}-9z^{3}+26z^{2}+6z-180=0$
Given that one of the roots is $3+3i$, find the other roots.
$$
\begin{gather*}
z_{1}=3+3i, z_{2} = 3-3i \\
\therefore (z^{2}-6z+18)
\end{gather*}
$$
Now there are two ways to factor the quartic.
- Polynomial division
- Equating coefficients 

## Polynomial Division
![[Pasted image 20251110205707.png]]
Doing polynomial division is very straight forward and systematic however there are many calculations which can lead to calculation errors 

## Equating Coefficients 
We know that:
$$
\begin{gather*}
(z^{2}-6z+18)(az^{2}+bz+c) = z^{4}-9z^{3}+26z^{2}+6z-180 

\end{gather*}
$$
For it is possible to deduce a $a$ and $c$. We know $a$ will be:
$$
az^{4} = z^{4}
$$
Therefore $a=1$. As well as that we know that $-180$ will be a result of:
$$
18c=-180
$$
Therefore $c=-10$.
To calculate $b$ you must form an equation with $b$ to compare a coefficient with. We know that to form $z^{2}$ will need to multiply $b$
$$
\begin{gather*}
-6bz^{2}+cz^{2}+18az^{2} = 26z^{2} \\ 
(-6b-10+18) = 26 \\ 
-6=18 \\ 
b=-3
\end{gather*}
$$
We can see that this method has less calculations but is not the standard of doing so. As well it is not always obvious whether your coefficients are correct. In polynomial division, if your remainder is not 0 then it means there is probably an error in calculations.

Continuing the question we can see:
$$
\begin{gather*}
(z^{2}-6z+18)(z^{2}-3z-10) = 0 \\
(z^{2}-6z+18)(z-5)(z+2)=-2 \\ \\
z_{3}=5, z_{4}=-2
\end{gather*}


$$
# Worked Example 7
Given that $z^{4}+bz^{3}+cz^{2}+dz+e=0$
Given that one of the roots is $7-4i$ and that the roots form a square with one root in each quadrant, find the full equation.

Drawing an argand diagram, you can see that:
![[Pasted image 20251110211413.png]]
We can see that difference between the conjugate is side length $8$. Therefore we can see that the side length of the square is 8. This means that the real part of the other vertices of the square will be $7-8=-1$.

From the onwards, you can form an equation for the polynomial:
$$
\begin{gather*}
(z^{2}-14z+65)(z^{2}+2z+17) = 0 \\ 
z^{4}+2z^{2}-17z-14z^{3}-28z^{2}-238z+65z^{2}+130z+1105 \\ 
z^{4}-12z^{3}+54z^{2}-108z+1105=0
\end{gather*}
$$



