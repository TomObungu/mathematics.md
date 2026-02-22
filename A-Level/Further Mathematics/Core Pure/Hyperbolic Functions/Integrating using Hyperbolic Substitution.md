It is possible to use u substitution and setting variables as hyperbolic functions to simplify integration

# Example 1
Find $\int \sqrt{ x^{2}-1 }$
Use the substitution $x= \cosh \theta$ and differentiating:
$$
\begin{gather*}
x = \cosh \theta \\ \\
\frac{dx}{d\theta} = \sinh \theta \\ \\
dx = \sinh \theta d\theta
\end{gather*}
$$
Substituting the results:
$$
\begin{gather*}
 \int \sqrt{ x^{2}-1 } = \int \sqrt{ \cosh ^{2}\theta  - 1 }\sinh\theta d\theta \\ \\
 = \int \sinh ^{2}\theta d\theta \\ \\
 = \int \frac{1}{2}\cosh 2\theta - \frac{1}{2} d\theta \\ \\ 
 = \frac{1}{4}\sinh 2\theta  - \frac{1}{2}\theta + c
\end{gather*}
$$
Finding $\theta$ using the definitions of $ar\cosh\theta$:
$$
\theta = ar\cosh x = \ln (x^{2} + \sqrt{ x^{2} - 1 })
$$

Rewriting in terms of the new found definitions of $\theta$. You can furthermore rewrite $\sinh 2\vartheta$ as $2\cosh \theta \sinh\theta$ - rewriting $\cos\theta$ as just $x$. As well as that, you can write $\sinh x$ as $\sqrt{ x^{2}-1 }$ . 
$$
\begin{gather*}
 = \frac{1}{4}\sinh 2\theta  - \frac{1}{2}\theta + c \\ \\
 = \frac{1}{4}(2\cosh \theta \sinh\theta) - \frac{1}{2}\theta + c \\ \
 \frac{1}{2}x\sqrt{ x^{2}-1 } - \frac{1}{2}\ln(x^{2}+\sqrt{ x^{2}-1 }) + c
\end{gather*}
$$

# Example 2
Find $\int \frac{x^{3}}{\sqrt{ 9+x^{2} }}$
For this type of question you need to again using trigonometric substitution except you must consider the coefficients. Substituting, $x = \sinh\theta$ will yield $9+\sinh ^{2}\theta$ which is close to the identity for $\cosh ^{2} \theta$, however in order to make it feasible, we need to substitute with a scaling of 3 in order to make the coefficients the same.
$$
\begin{gather*}
x = 3\sinh \theta \\ \\ 
\frac{dx}{d\theta} = 3\cosh \theta \\ \\ 
dx = 3\cosh\theta d\theta
\\ \\ \\

\therefore I = \int \frac{27\sinh ^{3}\theta}{\sqrt{ 9 + 9\sinh ^{2}\theta }}d\theta \\ \\ 
= \int \frac{27\sinh ^{3}\theta}{\sqrt{ 9(1 + \sinh ^{2}\theta)}}d\theta \\ \\ 
= \int \frac{27\sinh ^{3}\theta}{3\cosh\theta} (3\cosh\theta) d\theta \\ \\ 
= 27 \int\sinh ^{3} \theta do\theta \\ \\
= 27 \int(\cosh ^{2} \theta -1)\sinh\theta d\theta \\ \\
= 27 \int \cosh ^{2} \theta \sinh\theta - \sinh\theta d\theta \\ \\   
= 27\left(\frac{1}{3}\cosh ^{3}\theta-\cosh\theta\right) \\ \\
= 9\cosh ^{3}\theta - 27\cosh\theta \\ \\
\end{gather*}
$$
Therefore:
$$
I = 9\left( 1+\frac{x^{2}}{9} \right)^{\frac{3}{2}} - 27\sqrt{ 1+\frac{x^{2}}{9} } + c 
$$
Factoring out the $\frac{1}{9}$ from the $x^{2}$ from inside the brackets will yield a simplified version:
$$
I = \frac{1}{3}(9 + x^{2})^{\frac{3}{2}} - 9\sqrt{ 9+x^{2} } + c
$$

Always remember when factoring out the terms inside the brackets, you must apply whatever function is applied to the entire bracket. For example in the $\left( 1 +\frac{x^{2}}{9} \right)^{\frac{3}{2}}$ bracket, when factoring out $\frac{1}{9}$, you must raise it to $\frac{3}{2}$, which yields $\frac{1}{27}$. Thus you must multiply the out brackets by $\frac{1}{27}$ also. This yields $\frac{9}{27}$ which is $\frac{1}{3}$ accordingly.The same applies for the $\left( \sqrt{ 1 + \frac{x^{2}}{9} } \right)$ term. When factoring out $\frac{1}{9}$, you must raise it to $\frac{1}{2}$ (the same effect as square rooting), which yields multiplying by $\frac{1}{3}$, hence the $27$ term turning $9$. 

# Deriving $\int \frac{1}{\sqrt{ a^{2} + x^{2} }}dx$
It is is possible to simp