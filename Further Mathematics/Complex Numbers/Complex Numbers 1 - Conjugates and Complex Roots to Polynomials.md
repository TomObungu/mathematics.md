# Types of Numbers
Each number group contains the numbers from the previous group. 
- Natural numbers: $\mathbb{N} : 1,2,3\dots$
	- The numbers are ones that we can physically see. They are defined as positive integers 
- Integers: $\mathbb{Z}:-2,-1,0,1,2,3\dots$
	- The set of natural numbers including 0 and negative numbers. The lack of physical representation of these numbers delayed their acceptance. 
- Rational Numbers $\mathbb{Q}:$ $\frac{3}{4},\frac{2}{5},-\frac{1}{2}\dots$
	- Fractional numbers that can be expresses a ratio. Fractions have more a physical representation that negative numbers but still have a level of abstractness. 
- Real Numbers $\mathbb{R}:$ 
	- Algebraic irrational: $\sqrt{ 2 }, \sqrt{ 3 }$
	- Transcendental: $\pi,e$
		- These numbers that cannot be expressed a ratio of two integers. 
# Imaginary Numbers
Suppose if we cant to solve an equation like $x^2+1=0$. This might be a problem as it may seem like you can't square root $-1$. But it is possible to define it without any logical contradictions.:
$$
i = \sqrt{ -1 }
$$
Therefore the solutions to $x^{2}+1$ can be as followed:
$$
\begin{gather*}
x^{2}+1=0 \\
x^{2}=-1 \\
x = \pm i
\end{gather*}
$$
Multiples of $i$ are called 'imaginary numbers'. 
## Complex Numbers
A complex number has a part belong to real numbers and an imaginary part. E.g. $2+3i$, $4-i$, $3i$ (here the real part is 0)

## Cartesian form
A complex number in Cartesian form can be written as:
$$
z = x+iy  \qquad \mathbb{Z} \in \mathbb{Q}
$$
The notation to get the real and imaginary part of the number is:
$$
\begin{gather*}
\mathrm{Re}(z) = x \\ \\
\mathrm{Im}(z)=y
\end{gather*}
$$
# The complex plane
It is possible to use a 2-D number line to represent numbers in the 'complex plane'. This is called an 'Argand Diagram'.

A real number lines of the real axis and the the imaginary number lies on the imaginary axis. 

We can also draw the number as a vector
![[Pasted image 20251110080006.png]]

# Addition/Subtraction 
To add/subtract complex numbers, just calculate the part separately:
$$
(2+3i)(3-4i) = 5-i
$$

## Aragand diagram representation
It is possible to visualise addition and subtraction of numbers in the complex plane using vectors. 
![[Pasted image 20251110080346.png]]

# Multiplying 
Just compute the multiplication as if you were expanding brackets but always being careful as $i\times i=-1$:
$$
\begin{gather*}
(2+i)(3+4i) = 6 +8i+3i-4 = 2+ii \\
(3-i)(-2+2i) = -6+6i+2i+2 = -4+8i
\end{gather*}
$$
# Powers of i
All odd powers of i are imaginary and even powers are real and the sign alternates:
$$
\begin{gather*}
i^{1}=i, \ i^{2}=-1, \ , i^{3}=-i, \ i^{4} = 1
\end{gather*}
$$
## Computing an odd power of i
If you want to compute an odd power of i such as $i^{25}$. Substitute $i^{2}$ to find the last even number before the power and the multiply $i$ to get the even number. Final compute the product knowing that $i^{2}=-1$:
$$
i^{25} = (i^{2})^{12}i = (-1)^{12}i = i 
$$
Another example:
$$
i^{27}=(i^{2})^{13}=(-1)^{13}i=-i
$$
## Computing an even power of i
To compute an even number of i, repeat the same process or deduce by intuition that any odd numbered occurrence in the sequence of even powers $i$ is negative and any even occurrence is positive:
$$
i^{52}=(i^{2})^{26}=(-1)^{26}=1
$$
Another example (this is an even occurrence of an even power of i)
$$
i^{72}=(i^{2})^{36}=(-1)^{36} = 1
$$
Another example (this is an odd occurrence of an even power of i):
$$
i^{34} = (i^{2})^{17}=(-1)^{17}=-1
$$

# Dividing 
To divide a complex number you must multiply by the conjugate of numerator:
$$
\begin{gather*}
\frac{3-i}{4+2i} = \frac{3-i}{4+2i}\left( \frac{4-2i}{4-2i} \right) = \frac{12-6i-4i-2}{16+4} =\frac{10-10i}{20} \\ \\
= \frac{1}{2}-\frac{1}{2i}
\end{gather*}
$$
It is possible to compute complex division the Numworks calculator. 

# Complex Conjugates
As seen in complex division, negating the imaginary part of  the complex number, $z$ yields its 'conjugate', $z^{*}$ :
$$
z=x+iy \qquad z^{*}=x-iy
$$
# Useful properties
$$
\begin{gather*}
z+z^{*} = (x+iy)(x-iy) = 2x \\ \\
z-z= (x+iy)-(x-iy) = -2iy \\ \\
zz^{*}= (x+iy)(x-iy) = x^{2}-ixy+ixy+y^{2} =x^{2}+y^{2} \\ \\
\frac{z}{z^{*}} = \frac{(x+iy)}{x-iy} \left( \frac{x+iy}{x+iy} \right) = \frac{x^{2}-y^{2}+2ixy}{x^{2}+y^{2}}
\end{gather*}
$$

# Conservation Of Conjugation:
Consider $z=a+bi$, $w=c+di$. If you compute each operation and take the conjugate of the final outcome, you will see that: 
## Addition
$$
z^{*}+w^{*} = (z+w)^{*}
$$
## Subtraction
$$
z^{*}-w^{*} = (z-w)^{*}
$$
## Multiplication
$$
z^{*}w^{*}=(zw)^{*}
$$
## Division
$$
\begin{gather*}
\frac{z^{*}}{w^{*}} = \left( \frac{z}{w} \right)^{*}
\end{gather*}
$$
## Exponentiation
To prove conjugation is preserved for exponentiation, we must use proof by induction:
$$
\begin{gather*}
\text{We want to prove that } (z^{*})^n = (z^n)^{*}, \ n \in \mathbb{Z} \\ \\
n=0: \\
(z^{*})^{0} = (z^{0})^{*} = 1 \qquad \therefore\text{ true for n=0} \\ \\
n=1: \\
(z^{*})^{1}=(z^{*})=(z^{1})^{*} \qquad \therefore\text{true for n=1} \\ \\
n = k: \\
\text{Assume } (z^{*})^{k} = (z^{k})^{*}, \ k\in \mathbb{N} \\ \\
n=k+1: \\
(z^{*})^{k+1} = (z^{*})^{k}z^{*} \\ 
= (z^{k})^{*}z^{*} \\
=(z^{k}z)^{*} \text{( multiplication is convserved in conjugation)} \\ 
= (z^{k+1})^{*} \\ \\
\text{If ture for } n = k+1 \text{ then true for } n\in \mathbb{Z}^{+}
\end{gather*}
$$

Time for continue the proof for negative values of $n$:
$$
\begin{gather*}
\text{Assume } n =-m, m\in \mathbb{Z}^{+} \\ \\
(z^{*})^{-m} = \frac{1}{(z^{*})^{m}} = \frac{1}{(z^{m})^{*}} = \left( \frac{1}{z^{m}} \right)^{*} = (z^{-m})^{*} \\ \\
\therefore (z^{*})^{n} = (z^{n})^{*}
\end{gather*}
$$
# Multiplying a real scalar
We know that $w^{*}z^{*}=(wz)^{*}$

Consider $w\in \mathbb{R}$, as $w$ has no imaginary part (the imaginary part is 0), then the conjugate is itself $w^{*}=w$. $$
\therefore w^{*}z^{*} = wz^{*} = (wz)^{*}
$$
Therefore multiplication by a real scalar is preserved. In this we only need to conjugate $z$.

# Roots of polynomials
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
