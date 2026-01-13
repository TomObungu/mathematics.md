	Since we have two arbitrary constants, we need two boundary conditions for a second order differential equation.

# Worked Example 1
Find the particular solution for $y''+3y'+2y= 10\cos x$, when $y(0)=1$ and when $y'(0)=0$.

The process of solving will lead us to the general equation:
$$
\begin{gather*}
y = Ae^{-x}+Be^{-2x}+\cos x+3\sin x \\ \\
\end{gather*}
$$
The steps to solve this once we have the general solution, $y$ is to consider $y(0)$ and then differentiate the general solution and consider $y'(0)$:
$$
\begin{gather*}
1 = Ae^{-0}+Be^{-2(0)}+\cos(0)+3\sin(0) \\ \\
1 = A+B+1 \\ \\
A+B = 0 \\ \\
A=-B
\end{gather*}
$$
Differentiating our general solution $y$:
$$
y' = -Ae^{-x}-2Be^{-2x}-\sin x+3\cos x
$$
Dealing with $y'(0) = 0$:
$$
\begin{gather*}
0 = -Ae^{-0}-2Be^{-2(0)}-\sin(0)+3\cos(0) \\ \\
0 = -A-2B+3 \\ \\
0 = B-2B + 3 \\ 
B=3 \\ \\
\therefore A = -3
\end{gather*}
$$
Thus the particular solution is:
$$
y = -3e^{-x}+3e^{-2x}+\cos x+3\sin x
$$
