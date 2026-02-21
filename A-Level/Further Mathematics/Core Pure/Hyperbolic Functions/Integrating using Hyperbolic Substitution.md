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
Finding $\theta$ using the definitons of $ar\cosh\theta$:
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