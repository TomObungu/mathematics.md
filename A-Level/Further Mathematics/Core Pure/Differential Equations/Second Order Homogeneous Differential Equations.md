Equations of the form:
$$
ay''+by'+cy = 0
$$
are called 'homogeneous'  because the RHS is 0. 

Equations of the form:
$$
ay''+by'+cy =f(x)
$$
are called 'inhomogeneous'

# Principle of superposition
If $y_{1}$ is a solution of $ay''+by'+cy=f_{1}(x)$ and
$y_{2}$ is a solution of $ay''+by'+cy=f_{2}(x)$ then:
$$
(Ay_{1}+by_{2})
$$
Is a solution of:
$$
ay''+by'+cy = Af_{1}(x) + Bf_{2}(x)
$$
The solution to a DE with a linear combination of terms on the RHS is equal to the solutions for each of those forms.

# Homogeneous 2nd order DEs

## Case 1: $b^{2} - 4ac>0$
Consider:
$$
ay''+by'+cy = 0
$$
To solve this we can start by guessing the solution. This is called a trial solution. 

We will guess, $y=e^{mx}$

Differentiating gives:
$$
\begin{gather*}
y' = me^{mx} \\ \\ 
y'' = m^{2}e^{mx}
\end{gather*}
$$
Substituting in gives
$$
\begin{gather*}
am^{2}e^{mx}+bme^{mx}+ce^{mx} = 0
\end{gather*}
$$
The $e^{x}$ cancel out and we are left with.
$$
am^{2}+bm+c = 0 
$$
This quadratic is called the auxiliary equation. Solving this quadratic equation of $m$ will give solutions $m=\alpha$ and $m=\beta$. Thus the solutions to the DE are :
$$
y = e^{\alpha x} \qquad y = e^{\beta x}
$$

Now since both of these satisfy the homogeneous equation, any linear combination of them also satisfies the equation, since the RHS is $0$. Thus any linear combination of constants that lead to the RHS = 0 can satisfy the equation:

Thus the general solution is:
$$
y = Ae^{\alpha x} + Be^{\beta x}
$$

## Case 2: $b^{2}-4ac=0$
If the auxiliary equation's discriminant is $0$. We will only get one root.

If $b^{2}-4ac=0$, the solution to the auxiliary equation will $\alpha$ 

In this scenario, the general solution is given by
$$
y = (A+Bx)e^{\alpha x}
$$

## Case 3: $b^{2}-4ac < 0$
If the discriminant is less than $0$. The auxiliary equation will have complex roots, forming a conjugate pair. The solutions will be:
$$
\alpha = p + qi \qquad \beta = p-qi
$$
Substituting into our original solution we get:
$$
\begin{gather*}
y = Ce^{(p+qi)x} + De^{(p-qi)x} \\ \\
= Ce^{px}e^{qix} + De^{px}e^{-qix} \\ \\
= e^{px}[Ce^{qix}+De^{-qix}] \\ \\
= e^{px}[C\cos qx +iC\sin qx + D\cos qx-iD\sin qx] \\ \\
= e^{px}[(C+D)\cos qx+i(C-D)\sin qx]
\end{gather*}
$$
Let $A = C + D$ and $B = i(C-D)$:

The general solution becomes:
$$
y = e^{px}[A\cos qx+B\sin qx]
$$

## Summary
![[Pasted image 20251229231114.png]]

# Trivial solution
It is worth noting that $y=0$ also satisfies $ay''+by'+cy=0$. This the 'trivial solution'. We can add it to the solution by superposition but since it's +0,t does nothing.