 You can define and use the inverse of hyperbolic functions.
If $f(x) = \sinh (x)$ , then $f^{-1}$ is called $ar\sinh(x)$.

The graph of $arshin(x)$ is a reflection of the graph $y=\sinh(x)$ in the line $y=x$.
![[Pasted image 20251224160640.png]]

Remember, the inverse of a function is only defined if the function is one-to-one. So for $\cosh(x)$. The domain must be restricted in order to define an inverse. 

# Deriving $ar\cosh(x)$
Let's take the same process that would take when finding the inverse of a function by switching $x$ and $y$ around and rearranging to get $y$. 
$$
\begin{gather*}
y = \cosh x \\
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
(t-x)^{2} = x^{2}+1 \\
t-x = \pm \sqrt{ x^{2}+1 } \\ 
t = x \pm \sqrt{ x^{2}+1 }
\end{gather*}
$$Remember that $t=e^{y}$:
$$
e^{y} = x\pm \sqrt{ x^{2}+1 }
$$