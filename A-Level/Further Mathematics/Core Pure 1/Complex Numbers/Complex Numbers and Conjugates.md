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
\boxed{z+z^{*} = 2x} \\ \\
\boxed{z-z = -2iy} \\ \\
\boxed{zz^{*}=x^{2}+y^{2}} \\ \\
\boxed{\frac{z}{z^{*}} = \frac{x^{2}-y^{2}+2ixy}{x^{2}+y^{2}}}
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
