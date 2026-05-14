 You can define and use the inverse of hyperbolic functions.
If $f(x) = \sinh (x)$ , then $f^{-1}$ is called $ar\sinh(x)$.

The graph of $arshin(x)$ is a reflection of the graph $y=\sinh(x)$ in the line $y=x$.
![[Pasted image 20251224160640.png]]

Remember, the inverse of a function is only defined if the function is one-to-one. So for $\cosh(x)$. The domain must be restricted in order to define an inverse. 

# Deriving $ar\cosh(x)$
Let's take the same process that would take when finding the inverse of a function by switching $x$ and $y$ around and rearranging to get $y$. 
$$
\begin{gather*}
y = arcosh x \\
x = \cosh y \\ \\
x = \frac{e^{y}+e^{-y}}{2} \\ \\
2x = e^{y}+e^{-y}
\end{gather*}
$$
In this scenario let's try multiplying by $e^{y}$:
$$
\begin{gather*}
2xe^{y} = (e^{y})^{2} + 1
\end{gather*}
$$
Now let's rearrange to get terms all one side:
$$
(e^{y})^{2}- 2xe^{y} + 1
$$
Now this almost looks like a quadratic. Let's simplify things a bit by setting $t=e^{y}$:
$$
t^{2} -2xt+1
$$
Now it looks like we have made no progress, however notice there is nothing stopping you from competing the square:
$$
(t-x)^{2}-x^{2}+1
$$
From here it is now possible to rearrange for $t$ easily:
$$
\begin{gather*}
(t-x)^{2} = x^{2}-1 \\
t-x = \pm \sqrt{ x^{2}-1 } \\ 
t = x \pm \sqrt{ x^{2}-1 }
\end{gather*}
$$Remember that $t=e^{y}$:
$$
e^{y} = x\pm \sqrt{ x^{2}-1 }
$$Thus:
$$
\boxed{ar\cosh x = \ln(x \pm \sqrt{ x^{2}-1 })}
$$

## Is it $+\sqrt{ x^{2}-1 }$ or $-\sqrt{ x^{2}-1 }$?

$\cosh x$ is an even, many-to-one function. This means that two different values of $x$ will give the same value for $\cosh x$.
![[Pasted image 20251227140525.png]]

As stated, in order to have an inverse for $\cosh x$, it needs to only take the positive region of $coshx$. Thus using $ar\cosh x$ will only return 1 value or no values. However in order to get the all the values of $x$  when using $ar\cosh x$. You simply negate the answer given from your $ar\cosh x$. 

$ar\cosh x$ will give the positive left hand side of the $\cosh x$ graph. Negating will give the negative right hand side. 

### Example 1
Solve $3\cosh x-4=5$

Rearrange:
$$
\begin{gather*}
3\cosh x = 9 \\ \\
\cosh x = 3
\end{gather*}
$$
When taking the inverse:
$$
x_{1} = ar\cosh(3) = \ln(3+\sqrt{ 3^{2}-1 }) = \ln(3 + 2\sqrt{ 2 })
$$
However this only gives the value of $x$ on the left hand side of the function. Thus to get the other value just negate:
$$
x_{2} = -\ln(3 + \sqrt{ 3^{2}-1 }) = -\ln(3 + 2\sqrt{ 2 })
$$

However it also true that this value is identical to $\ln({3}-2\sqrt{ 2 })$:
$$
\begin{gather*}
-\ln(3+2\sqrt{ 2 }) = \ln\left( \frac{1}{3+2\sqrt{ 2 }} \right) \\ \\
\frac{1}{3 + 2\sqrt{ 2 }} = \frac{3-2\sqrt{ 2 }}{3-2\sqrt{ 2 }} = \frac{3-2\sqrt{ 2 }}{9 - 8} \\ \\
= \frac{3-2\sqrt{ 2 }}{1} = \boxed{3 - 2\sqrt{ 2 }}
\end{gather*}

$$
# Deriving $ar\sinh x$.
Taking the same approach:
$$
\begin{gather*}
x = \sinh y \\ \\
x = \frac{e^{y}-e^{-y}}{2} \\ \\
2x = e^{y}-e^{-y} \\ \\
2xe^{y} = (e^{y})^{2} -1 \\ \\
t = e^{y} \\ 
2xt = t^{2}-1 \\ 
t^{2}-2xt-1 = 0 \\ 
(t-x)^{2} - x^{2} -1 = 0 \\ 
(t-x)^{2} = x^{2}+1 \\ 
t - x= \pm \sqrt{ x^{2}+1 } \\ \\
t = x \pm \sqrt{ x^{2}+1 } \\ 
\end{gather*}
$$
Therefore:
$$
\begin{gather*}
e^{y} = x \pm \sqrt{ x^{2}+1 } \\ \\
y = \ln (x\pm \sqrt{ x^{2}+1 })
\end{gather*}
$$
 
## Only take $+\sqrt{ x^{2}+1 }$ this time
$x-\sqrt{ x^{2}+1 }$ can be ignored since $\sqrt{ x^{2}+1 }>x$, and would give a negative value inside a logarithmic function which is not possible as the value will be undefined. Thus we only take the positive value this:
$$
\boxed{ ar\sinh x = \ln (x + \sqrt{ x^{2}+1 }) }
$$

# Solving hyperbolic equations
## Example 1
Solve for $x$, $6\sinh(x)-2\cosh(x)=7$

With type of question, in A level you would put into harmonic form but with the hyperbolic version, you put it directly into $e^{y}$ and solve it

$$
\begin{gather*}
6\left( \frac{e^{x}-e^{-x}}2{} \right) - 2\left( \frac{e^{x}+e^{-x}}{2} \right) = 7 \\ \\
6e^{x}-6e^{-x}-2e^{x}-2^{-x} = 14 \\ \\
4e^{x} - 8e^{-x} = 14 
\end{gather*}
$$
We take the same approach to solve this by multiplying $e^{x}$:
$$
\begin{gather*}
4(e^{x})^{2} - 8 = 14e^{x}  \\
t = e^{x} \\ 
4t^{2}-14t-8 = 0 \\ 
2t^{2}-7t-4 = 0 \\ 
(2t+1)(t-4) =0  \\
\\
t= -\frac{1}{2} \qquad t  = 4
\end{gather*}
$$
Thus equating $t=e^{x}$:
$$
\begin{gather*}
e^{x} = -\frac{1}{2} \qquad e^{x} = 4 \\ 
\cancel{  x = \ln\left( -\frac{1}{2} \right) } \qquad \boxed{ x = \ln 4 = 2\ln_{2}}
\end{gather*}
$$


# Deriving $ar\tanh x$
The approach is mostly similar:
$$
\begin{gather*}
y = ar\tanh x  \\ 
x = \tanh y  \\ \\
x = \frac{e^{y}-e^{-y}}{e^{y}+e^{-y}}  \\ \\
xe^{y} + xe^{-y} = e^{y}-e^{-y} 
\end{gather*}
$$
Multiplying by $e^{y}$:
$$
x(e^{y})^{2} + x = (e^{y})^{2} -1 
$$
Collecting like terms:
$$
\begin{gather*}
t = e^{y} \\ 
xt^{2} - t^{2} = -1 -x  \\
t^{2}(1-x) = 1+x \\ \\
t^{2} = \frac{1+x}{1-x} \\ \\
t = \pm \sqrt{ \frac{1+x}{1-x} }
\end{gather*}
$$
Thus:
$$
\begin{gather*}
e^{y} =  \pm \sqrt{ \frac{1+x}{1-x} } \\ \\
y = \ln\left( \pm \sqrt{ \frac{1+x}{1-x} }  \right)
\end{gather*}
$$
However as negative values are not defined for the natural logarithm:
$$
y = \ln\left( \sqrt{ \frac{1+x}{1-x} }  \right)
$$
However this can be simplified further into log rules. When dealing with limits and hyperbolic functions, it is good to put the logarithm into the form that makes it a fraction using log rules:
$$
y = \frac{1}{2}\ln\left( \frac{1+x}{1-x} \right)
$$

The domain for this function is $|x|< 1$. If it were to be $|x|\leq_{1}$, the it would not be defined as:
$$
\text{For} |x| \geq 1, \frac{1+x}{1-x} \leq 0
$$
