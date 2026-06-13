It is possible to solve dynamic problems with variable forces by knowing the equations of motion and rearranging to form differential equations. Like with kinematics, we need to choose appropriate forms for the accelerations depending on what variables we are working with. 

Resistive forces will be negative. 
# Example 1
A 2kg particle moves along the positive x axis in the direction of x increasing. It has velocity $v$  at the time $t$. It is displaced $x$ meters from the origin $O$. It experiences a resistive force of magnitude $3v^{2}$. 

Find the distance, $D$, the particle travels as its velocity decreases from $10ms ^{-1}$ to $8ms ^{-1}$. 

For these questions, you need to form an appropriate $F=ma$ equation. As we given $x$, we use the acceleration in the form $a = v \frac{dv}{dx}$ and $m$ as given which is $2kg$:

With $F=ma$, consider the total resistive force:
$$
\begin{gather*}
2v \frac{dv}{dx} = -3v^{2} \\ \\ 
-\frac{2}{3}\int_{10}^{8}  \frac{dv}{v} = \int_{0}^{D} dx \\ \\
\frac{2}{3} [\ln v]_{}{8}^{10} = D \\ \\
D = \frac{2}{3}[\ln 10 - \ln 8 ] = \frac{2}{3}\ln\left( \frac{5}{4} \right)
\end{gather*}
$$

## Example 1 Continued
Calculate the time taken for the speed to decrease from $10ms ^{-1}$ to $8 ms ^{-1}$. For this question you must asses the change in variables and conclude to change the form of acceleration $\frac{dv}{dt}$:

$$
\begin{gather*}
2 \frac{dv}{dt} = -3v^{2} \\ \\
\int -\frac{2}{3}v^{-2}dv = \int_{0}^{T} dt \\ \\
\frac{2}{3}\left[ \frac{1}{v} \right]_{10}^{8} = T \\ \\
T = \frac{1}{60}
\end{gather*}
$$

## Example 2
At time $t=0$, a $5kg$ ball is released from rest from $O$. It experiences a resistive force of $2v$. Show that $v(t) = \frac{5}{2}g\left( 1-^{ e^{-\frac{2}{5}}t} \right)$

For this question, you are given $t$ and asked to find $v(t)$. Thus, we use $a=\frac{dv}{dt}$. For this problem you must consider the force of it's weight minus the resistive force: 
$$
\begin{gather*}
5 \frac{dv}{dt} = 5g -2v \\ \\
5\int \frac{dv}{5g - 2v} = \int dt \\ \\
-\frac{5}{2}\ln| 5g - 2v| = t + c \\ \\


\text{Finding c :} \\ \\
v(0) = 0 \implies c = -\frac{5}{2}\ln(5g) \\ \\
\therefore -\frac{5}{2}\ln|5g - 2v| + \frac{5}{2}\ln(5g) = t
\end{gather*}
$$
From this point forward, we can rearrange to find $v$:
$$
\begin{gather*}
t = \frac{5}{2}\ln\left( \frac{5g}{5g-2v}  \right) \\ \\ 
e^{ \frac{2}{5}t} = \frac{5g}{5g-2v} \\ \\
5g-2v = 5ge^{- \frac{2}{5}t} \\ \\
2v = 5g -5ge^{-\frac{2}{5}t} \\ \\
v = \frac{5}{2}g\left(  1 - e^{ -\frac{2}{5}t} \right)
\end{gather*} 

$$
## Example 2 continued...
Show that the distance ,$D$, that the ball falls as the the speed increases from $g$ to $2g$ is :
$$
\begin{gather*}
D = \frac{5}{2}g\left[ \frac{5}{2}\ln 3 - 1 \right] \\ \\
\end{gather*}
$$
For this problem use $a = \frac{vdv}{dx}$:
$$

$$