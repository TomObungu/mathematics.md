Sometimes it is possible to simplify an integral by changing the variable. The process is similar to that of use the chain rule in differentiation

E.g. $\int x\sqrt{ 2x+5 }$
$$
\begin{gather*}
u = 2x+5 \\ \\
\frac{du}{dx} = 2 \\ \\
\frac{du}{2} = dx \\ \\
x = \frac{u-5}{2} \\ \\
\int \frac{u-5}{5} u^{\frac{1}{2}} \frac{du}{2} \\ \\
= \int \frac{1}{4}(u-5)u^{\frac{1}{2}}du \\ \\
= \int \frac{1}{4}\left( u^{\frac{3}{2}}-5^{\frac{1}{2}} \right) \\ \
= \frac{u^{\frac{5}{2}}}{10}-\frac{5u^{\frac{3}{2}}}{6} \\ \\
= \frac{(2x+5)^{\frac{5}{2}}}{10}-\frac{5^{*}(2x+5)^{\frac{3}{2}}}{6}
\end{gather*}
$$

## Trigonometric substitution 
In general if you ever see a problem in the form:
$$
\begin{gather*}
\int\frac{k}{\sqrt{ a -x^{2}}} dx
\end{gather*}
$$
It's more or less going to involve substituting $x=\sqrt{ a }\sin u$
E.g. Show that $\int \frac{4}{\sqrt{ 4-x^{2} }} = 4\arcsin \left( \frac{x}{2} \right)+c$
$$
\begin{gather*}
\text{Let } x = 2\sin u \\ \\
\frac{dx}{du} = 2\cos u \\ \\ 
dx = 2\cos udu \\ \\
I = \int \frac{4}{\sqrt{ 4-(2\sin u)^{2} }}dx = \int \frac{4}{\sqrt{ 4-4\sin ^{2}u }}dx \\ \\ 
= \int \frac{4}{\sqrt{ 4(1-\sin ^{2}u) }}dx= \int \frac{4}{\sqrt{ 4\cos ^{2}u }}dx \\ \\
= \int \frac{4}{\cancel{ 2\cos u }}\cancel{ 2\cos ud }u  = \int 4du\\ \\
= 4u+c \\ \\ \\
\arcsin \left( \frac{x}{2} \right)= u \\ \\
\therefore \int \frac{4}{\sqrt{ 4-x^{2} }}  = 4\arcsin\left( \frac{x}{2} \right)+c \\
QED
\end{gather*}
$$
### Types of Trigonometric substitution
For cases when the question is in the form:
$$
\int \frac{k}{\sqrt{ a-x^{2} }} \implies \text{Substitute: }x=\sqrt{ a } \sin u
$$
--- 
For cases when the question is in the form:
$$
\int \frac{k}{\sqrt{ x^{2}-1 }} \implies \text{Substitute: }x=\sqrt{ a }\sec u
$$
This  is because:
$$
\begin{gather*}
\tan ^{2}u = \sec ^{2}u - 1 \\ 
\end{gather*}
$$
Hence:
$$
x=\sec u \implies \sqrt{  x^{2}-1 } = \sqrt{\sec ^{2}u-1} = \sqrt{ \tan ^{2} u } = \tan u
$$

---
For cases when the question is in the form:
$$
\int \frac{k}{\sqrt{ 1+x^{2} }} \implies \text{Substitute: }x=\sqrt{ a }\tan u
$$
This  is because:
$$
\begin{gather*}
\sec ^{2}u = \tan ^{2}u +1 \\ 
\end{gather*}
$$
Hence:
$$
x=\tan u \implies \sqrt{  1+x^{2} } = \sqrt{1+\tan ^{2}u} = \sqrt{ \sec u } = \sec u
$$
### Changing to algebraic form
Sometimes, it is possible to further simplify the result of an integral into terms of $x$ when you have used substitution. Let's take this example as a an exercise of trigonometric substitution:
$$
\int \frac{\sqrt{ 9-x^{2} }}{x^{2}}
$$
Notice that the equation contains $\sqrt{ a-x^{2} }$ thus we can use $x=3\sin u$:
$$
\begin{gather*}
x = 3\sin u \\ \\
\frac{dx}{du} = 3\cos u \\ 
dx=3\cos u du \\ \\
\int \frac{\sqrt{ 9-x^{2} }}{x^{2}} = \int \frac{\sqrt{ 9-9\sin ^{2} u }}{9\sin ^{2} u}3\cos u du \\ \\
= \int \frac{3\cos u}{9\sin ^{2}u}3\cos u du \\ \\
= \int\frac{9\cos ^{2}u}{9\sin ^{2}u}du =\int \cot ^{2}udu \\ \\
= -\cot u -u+c
\end{gather*}
$$
Now it is possible to simplify $\cot u$ in terms of $x$. Most of the time if you see something with $\tan u$ or $\cot u$ it can be simplified or writing something like $\cos u = \sqrt{ 1-x^{2} }$ if $x$ were $\sin  u$:
$$
\begin{gather*}
= -\frac{\cos u}{\sin u} -u + c \\ \\ \\
9-x^{2} = 9-9\sin ^{2} u \\ \\
\sqrt{ 9-x^{2} } =\sqrt{ 9(1-\sin ^{2}u) } \\ \\
\sqrt{ 9-x^{2} } = 3\cos u \\ \\
\frac{\sqrt{ 9-x^{2} }}{3} = \cos u \\ \\
\frac{1}{3}\sqrt{ 9-x^{2} } = \cos u
\end{gather*}
$$
Therefore $\cot u$ can be written as:
$$
\begin{gather*}
= - \frac{1}{3} \frac{\sqrt{ 9-x^{2} }}{x} -u+c
\\ \\
= -\frac{\sqrt{ 9-x^{2} }}{3x} -u+c
\end{gather*}
$$
Now it is not possible to rewrite $u$ in terms of $x$ only thus:
$$
\begin{gather*}
x=\sin u \\ \\
u = \arcsin(x) 
\end{gather*}
$$
Thus the final form of of the integral is:
$$
\boxed{-\frac{\sqrt{ 9-x^{2} }}{3x} -\arcsin(x)+c}
$$
