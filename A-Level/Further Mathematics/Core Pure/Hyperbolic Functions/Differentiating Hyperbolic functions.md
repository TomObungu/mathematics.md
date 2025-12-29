It is possible to show that:
$$
\begin{gather*}
\frac{d}{dx} \sinh x = \cosh x  \\ \\
\frac{d}{dx}\cosh x = \sinh x \\ \\
\frac{d}{dx} \tanh x = sech^{2}x
\end{gather*}
$$

## Deriving $\frac{d}{dx}\cosh x$
Start of with:
$$
\cosh x = \frac{e^{x} + e^{-x}}{2}
$$
Taking the derivative of both sides gives:
$$
\begin{gather*}
\frac{d}{dx}\cosh x = \frac{d}{dx} \frac{e^{x}+e^{-x}}{2}\\ \\
 = \frac{e^{x}-e^{x}}{2} \\ \\
 = \sinh x
\end{gather*}
$$

# Deriving $\frac{d}{dx} \sinh x$
Start of with:
$$
\begin{gather*}
\sinh x = \frac{e^{x}-e^{-x}}{2} \\ \\
\frac{d}{dx}\sinh x = \frac{e^{x}+e^{-x}}{2} \\ \\
= \cosh x
\end{gather*}
$$



# Differentiating inverse hyperbolic functions
It is possible to show that:
$$
\begin{gather*}
\frac{d}{dx}arsinh x = \frac{1}{\sqrt{ x^{2} +1 }} \\ \\
\frac{d}{dx}arcoshx = \frac{1}{\sqrt{ x^{2}-1 }}, x > 1 \\ \\
\frac{d}{dx}artanhx = \frac{1}{1-x^{2}}, |x| < 1
\end{gather*}
$$

# Deriving $\frac{d}{dx} ar\sinh x$:
$$
\begin{gather*}
x = \sinh y \\ \\
\frac{dx}{dy} = \cosh y \\ \\
\frac{dy}{dx} = \frac{1}{\cosh y} \\ \\
\cosh y = \sqrt{ 1+\sinh ^{2} y} \\ \\
\frac{dy}{dx} = \frac{1}{\sqrt{ 1 + \sinh ^{2}y}} \\ \\
\frac{dy}{dx} = \frac{1}{\sqrt{ x^{2} + 1 }}
\end{gather*}
$$

# Deriving $\frac{d}{dx}ar\cosh x$ 
$$
\begin{gather*}
x = \cosh y \\ \\
\frac{dx}{dy} = \sinh y \\ \\
\frac{dy}{dx} = \frac{1}{\sinh y} \\ \\
\sinh y =\sqrt{ -1+\cosh ^{2}y } = \sqrt{ \cosh ^{2}y-1 } \\ \\
\frac{dy}{dx} = \frac{1}{\sqrt{ \cosh ^{2}y -1 }} \\ \\
\frac{dy}{dx} = \frac{1}{\sqrt{ x^{2}-1 }}
\end{gather*}
$$

# Deriving $\frac{d}{dx} ar\tanh x$
$$
\begin{gather*}
x = \tanh y \\ \\
\frac{dx}{dy} = sech^{2}x \\ \\
\frac{dy}{dx} = \frac{1}{sech^{2}x} \\ \\
1-\tanh ^{2} x = sech^{2}x \\ 
\sqrt{ 1-\tanh ^{2}x } = sechx \\ \\
\frac{dy}{dx} = \frac{1}{\sqrt{ 1-\tanh ^{2}x }} \\ \\
\frac{dy}{dx} = \frac{1}{\sqrt{ x^{2}-1 }}
\end{gather*}
$$
