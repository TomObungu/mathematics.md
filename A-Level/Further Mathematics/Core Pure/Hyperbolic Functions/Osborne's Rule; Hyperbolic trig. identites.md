Given a trigonometric identity, it is generally possible to write down the corresponding hyperbolic identity using what is know as Osborn's rule.

In any identity, if there is a product of two $\sin$ or implied product of $\sin$, negative the result when putting in hyperbolic form.

e.g. $\sin A\sin B \to -\sinh A\sinh B$.

e.g $\tan ^{2}A \to -\tanh ^{2}A$
This one works as $\tan ^{2}A$ implies the product of two $\sin ^{2}A$ in the numerator:
$$
\tan ^{2}A = \frac{\sin ^{2}A}{\cos ^{2}A}
$$

Other examples are if:

$\tan(A+B) = \frac{\tan A+\tan B}{1-\tan A\tan B}$

then the hyperbolic equivalent is 
$$
\tanh(A+B) = \frac{\tanh A+\tanh B}{1+\tanh A\tanh B}
$$

## Common Hyperbolic trig identities:
Using Osborne's rule it possible to show that:
$$
\cosh ^{2}A-\sinh^{2}A \equiv 1
$$
Thus:
$$
\begin{gather*}
\cosh ^{2}A = 1+\sinh ^{2}A \\ \\
\sinh ^{2}A = -1 + \cosh ^{2}A
\end{gather*}
$$
And also:
$$
\begin{gather*}
\sinh(A \pm B) \equiv \sinh A\cosh B \pm \cosh A\sinh B \\ \\
\cos(A\pm B) \equiv \cosh A\cosh B \pm \sinh A\sinh B
\end{gather*}
$$

It is also possible to prove directly by substituting $e^{y}$ form:
### Example 1
Prove that $\cosh 2A \equiv 1 +2\sinh ^{2}A$:
$$
\begin{gather*}
RHS \equiv 1 + 2\left( \frac{e^{A}-e^{-A}}{2} \right)\left( \frac{e^{A}-e^{-A}}{2} \right) \\ \\
 \equiv 1 + \left( \frac{2e^{2A}-4+2e^{-2A}}{4} \right) \\ \\
 \equiv1-1 +\left( \frac{e^{2A}+e^{-2A}}2{} \right) \\  \\
 \equiv \cos 2A \equiv LHS \\ 
 QED
\end{gather*}
$$

## Solving hyperbolic trigonometric identities continued...

## Example 1
Solve $2\cosh ^{2}x-5\sinh x=5$, giving answers in **exact** form:

Here is a direct case to use Osborne's rule:
$$
\begin{gather*}
\cosh ^{2}x = 1+\sinh ^{2}x \\ 
2\cosh ^{2}x = 2+2\sinh ^{2}x \\ \\
2+2\sinh ^{2} x- 5\sinh x - 5 = 0 \\ \\
t = \sinh x \\ 
2t^{2}-5t-3 =0 \\
(2t+1)(t-3) = 0 \\ \\
t = -\frac{1}{2} \qquad t = 3 
\end{gather*}
$$
Equating $\sinh x$ and solving using $\sinh x = \ln(x+\sqrt{ x^{2}+1 })$:
$$
\begin{gather*}
\sinh x = -\frac{1}{2} \\ \\
x=\ln\left( -\frac{1}{2} \pm \sqrt{ \frac{1}{4} + 1 }  \right) \\ \\ 
\boxed{x = \ln\left( -\frac{1}{2} + \frac{\sqrt{ 5 }}{2} \right)}
\end{gather*}
$$

# Example 2
Solve $\cosh 2x - 5\cosh x + 4 = 0$

We can use Osborne's rule with the double angle formula:
$$
\cos 2x = 2\cos ^{2} x -1 
$$
Thus  the hyperbolic equivalent is:
$$
\cosh 2x = 2\cosh ^{2}x - 1
$$
Thus:
$$
\begin{gather*}
2\cosh ^{2}x -1 -5\cosh x+4 = 0  \\ \\
t = \cosh x \\
2t^{2} -5t+3 = 0 \\
(2t-3)(t-1) = 0 \\ \\
t = \frac{3}{2} \quad t = 1
\end{gather*}
$$
Equating $\sinh x$:
$$
\begin{gather*}
\sinh x = \frac{3}{2} \\
\boxed{x = \ln\left( \frac{3}{2} \pm \frac{\sqrt{ 5 }}{2} \right)}\\ \\
\sinh x = 1 \\ \\
\boxed{x= 0}
\end{gather*}
$$



