Consider the following adaptation of the spring-mass system. ![[Pasted image 20260220125514.png]]

The mass experiences a restoring force, $X$, a damping force, $R$ and a driving force $F(t)$.

The driving force changes with time and we define positive as the direction of positive displacement. 

Now, the equation of motion is:
$$
m \ddot{x} = -k_{1}x - k_{2}\dot{x} + F(t)
$$
Therefore rearranging gives us a 2nd order inhomogeneous ODE:
$$
m\ddot{x} +k\dot{x} + \omega^{2}x = f(t)
$$

Examples of driven/forces harmonic motion include:
- Pendulum clock - The driving force is provided by a weight and gearing system.
-  Pushing a child on a swing
- Resonant circuit driven from a signal generator
- Shattering a glass with singing
# Example 1
A particle of mass $1.5kg$ moves in a straight horizontal line. $x$ is its displacement from the origin. It experiences a restoring force of $7.5xN$, resistive force of $6vN$ and a driving force, $12\sin tN$.

It has an initial displacement of $5m$ and initial velocity $2ms ^{-1}$.

Find $x(t)$.

Setting up the DE:
$$
1.5\ddot{x} +6\dot{x}+7.5x = 12\sin t
$$
Solving complementary DE:
$$
\begin{gather*}
1.5\ddot{x} +6\dot{x}+7.5x  \\ \\
1.5m^{2} + 6m+7.5 = 0 \\ \\
m = -2 \pm i \\ \\ \\ 
\therefore x_{c} = e^{-2t}(A\cos t+B\sin t) 
\end{gather*}
$$
Now solving trying for the particular integral
$$
\begin{gather*}
\text{Let } x_{p} = \lambda \cos t + \mu \sin t \\ \\
\therefore \dot{x}_{p} = -\lambda \sin t + \mu \cos t \\ \\
\ddot{x}_{p} = -\lambda \cos t - \mu \sin t
\end{gather*}
$$
Substituting the particular integral into the ODE and solving for $\lambda$ and $\mu$
$$
\begin{gather*}
1.5(-\lambda \cos t-\mu \sin t) + 6(-\lambda \sin t+\mu \cos t) + 7.5(\lambda \cos t+\mu \sin t) = 12\sin t + 0\cos t \\ \\

(6\lambda + 6\mu)\cos t + (6\mu - 6\lambda)\sin t = 12\sin t + 0\cos t \\ \\
\therefore (6\lambda+6\mu) = 0 \\ \\
(6\mu-6\lambda) = 12 \\ \\
\lambda = -1 \qquad \mu = 1 
\end{gather*}
$$
Therefore:
$$
\begin{gather*}
x(t) = e^{-2t}(A\cos t+B\sin t)-\cos t+\sin t \\ \\
\end{gather*}
$$
Differentiating to find $\dot{x}(t)$ for procedure of finding boundary conditions later:
$$
\begin{gather*}
\dot{x}(t) = e^{-2t}(-A\sin t + B\cos t) -2e^{-2t}(A\cos+B\sin t) + \sin t + \cos t\\ \\
=  e^{-2t}((B - 2A)\cos t+(-A-2B)\sin t) + \sin t + \cos t
\end{gather*}
$$
Using boundary conditions to find arbitrary constants:
$$
\begin{gather*}
x(0) = A - 1 = 5 \implies A  = 6 \\ \\ 
\dot{x}(0) =B-2A + 1 = 2 \\ \\
\implies B - 11 = 2 \implies B = 13
\end{gather*}
$$
Therefore:
$$
\boxed{x(t) = e^{-2t}(6\cos t+13\sin t)-\cos t+\sin t}
$$

