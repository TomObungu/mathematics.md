The following Maclaurin series expansions are given in the formulae booklet:
$$
\begin{gather*}
e^{x} = 1+x+\frac{x^{2}}{2!}+ \frac{x^{3}}{3!}+\dots+\frac{x^{r}}{r}+\dots \qquad \forall x\\ \\ 
\ln(1+x) = x-\frac{x^{2}}{2}+\frac{x^{3}}{3}- \frac{x^{4}}{4}+\dots+(-1)^{r+1} \frac{x^{r}}{r}+\dots \qquad -1 < x \leq 1\\ \\
\sin x = x-\frac{x^{3}}{3!}+\frac{x^{5}}{5!}-\frac{x^{7}}{7!}+\dots+ (-1)^{r} \frac{x^{(2r+1)}}{(2r+1)!}+\dots\qquad \forall x  \\ \\
\cos x= 1-\frac{x^{2}}{2!} + \frac{x^{4}}{4!} -\frac{x^{6}}{6!} +\dots+ (-1)^{r} \frac{x^{2r}}{(2r)!} + \dots \\ \\
\arctan x = x -\frac{x^{3}}{3} + \frac{x^{5}}{5}- \dots + (-1)^{r} \frac{x^{2r+1}}{2r+1} + \dots -1 \leq x \leq 1
\end{gather*}
$$

You can find the series expansions of compound functions using these. 

When dealing with compound functions such as $e^{2x}$ and $e^{3x}$ and $\ln(1+2x)$, the Maclaurin expansion is the same except you replace $x$ with $2x$ or $3x$.

However when dealing with successive derivatives of a compound function, it is often possible to use one of the standard results

# Worked Example 1
![[Pasted image 20251229131826.png]]
In this case you can simply substitute $2x^{2}$ into the standard result:
$$
\begin{gather*}
\cos(x) = 1-\frac{x^{2}}{2!} + \frac{x^{4}}{4!} - \frac{x^{6}}{6!} +\dots \\ \\
\cos(2x^{2}) = 1- \frac{(2x^{2})^{2}}{2} + \frac{(2x^{2})^{4}}{24} - \frac{(2x^{2})^{6}}{720} \\ \\
\cos(2x^{2}) -= 1- 2x^{4} + \frac{2}{3}x^{8} - \frac{4}{45}x^{12}+\dots
\end{gather*}
$$
# Worked Example 2
![[Pasted image 20251229132400.png]]
Using rules of logarithms:
$$
\ln\left( \frac{\sqrt{ 1+2x }}{1-3x} \right) = \frac{1}{2}\ln(1+2x) - \ln(1-3x) 
$$
Both of these functions can be evaluated using standard results. Since it is the first three terms, it is up to $x^{3}$
$$
\begin{gather*}
\frac{1}{2}\ln(1+2x) = \frac{1}{2}\left(2x - \frac{(2x)^{2}}{2} + \frac{(2x)^{3}}{3}+\dots\right), -1 < 2x \leq 1 \\ \\
\frac{1}{2}\ln(1+2x) = x - x^{2} + \frac{4}{3}x^{3}+\dots. -\frac{1}{2} < x \leq 1 \\ \\ \\ 
-\ln(1-3x) = -\left(-3x - \frac{(-3x)^{2}}{2} + \frac{(-3x)^{^{3}}}{3}+\dots \right). -1 < -3x \leq 1 \\ \\
-\ln(1-3x) = 3x + \frac{9}{2}x^{2} + 9x^{3} \\ \\
\therefore \ln \sqrt{ \frac{1+2x}{1-3x} } \approx x-x^{2}+\frac{4}{3}x^{3} +3x + \frac{9}{2} x^{2}+9x^{3} \\ \\ 
\approx4x+\frac{7}{2}x^{2}+\frac{31}{3}x^{3}
\end{gather*}
$$
# Worked Example 2
![[Pasted image 20251229195618.png]]
Writethe Maclaurin series expansions up to $x^{3}$ for $\sin x$ and $e^{x}$
$$
\begin{gather*}
e^{x} = 1+x+\frac{x^{2}}{2!} + \frac{x^{3}}{3!} \\ \\
\sin x = x-\frac{x^{3}}{3!}
\end{gather*}
$$
Now substitute the standard result of $\sin x$ as the power of x in  $e^{x}$:
$$
e^{\sin x} \approx e^{x- \frac{x^{3}}{3!}}
$$
Now evaluate $e^{x-\frac{x^{3}}{3!}}$ with index laws:
$$
\begin{gather*}
e^{x}\left( e^{-\frac{x^{3}}{6}} \right) \\ \\

\end{gather*}
$$
Now evaluate $e^{-\frac{x^{3}}{6}}$ using the its Maclaurin expansion but replace $x$ with $-\frac{x^{3}}{6}$. Rewrite $e^{x}$ in it's series expansion aswell and form multiplication of polynomials:
$$
\begin{gather*}
\left( 1+x+\frac{x^{2}}{2} +\frac{x^{3}}{6}\dots \right)\left( 1+\left( -\frac{x^{3}}{6} \dots \right) \right)  \\ \\
= 1 -\frac{x^{3}}{6}+x-\frac{x^{4}}{6}+\frac{x^{2}}{2}-\frac{x^{5}}{12} + \frac{x^{3}}{6} -\frac{x^{6}}{36}\dots \\ \\
= 1+x + \frac{x^{2}}{6}

\end{gather*}
$$