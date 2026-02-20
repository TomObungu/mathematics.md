In simple harmonic motion, the particle will oscillate forever. This is clearly unrealistic. In reality, resistive forces will slow it down over time.

Consider a modification of the spring-mass system with the damper:
![[Pasted image 20260126212139.png]]

Stoke's law states that an object moving in a viscous liquid experiences a resistive force proportional to its velocity.

![[Pasted image 20260126212225.png]]

The object experiences a resistive force acting in the opposite direction to its velocity.

Now let's reconsider then pendulum. The pendulum experiences air resistance which is proportional to velocity
![[Pasted image 20260126212328.png]]

Again air resistance acts in the opposite direction to velocity.

In general, damped harmonic motion describes a particle with a restoring force directed towards the centre and resistive force proportional to velocity.

Thus:
- Restoring force is proportional to and acts opposite to displacement
- Damping force is proportional to and acts opposite to velocity

Thus, damped harmonic motion is described by:
$$
\ddot{x} = -\omega^{2} x -k\dot{x}
$$

Therefore:
$$
\ddot{x} +k\dot{x} + \omega^{2}x = 9
$$
This a 2nd order homogeneous ODE.

# Types Of Damping 
There are three possible forms of the solution take based on the number of roots of the auxiliary equation:
$$
m^{2} + km +\omega^{2} = 0
$$

## Case 1 : Light Damping
Light damping occurs when the discriminant of the auxiliary equation is less than 0, i.e $k^{2} - 4\omega^{2} < 0$. Therefore the auxiliary equation has imaginary roots, in the form $m=p \pm qi$. Therefore:
$$
x = e^{\pi}\left[A\cos(qt)+B\sin(qt)\right]
$$
Graphically, this would be sinusoidal oscillations inside an exponentially decaying envelope:
![[Pasted image 20260220104701.png]]

The amplitude decreases with. An example case of this would be a pendulum subject to air resistance. 

## Case 2 : Heavy Damping
Heavy damping occurs when the discriminant of the auxiliary equation is greater than 0 i.e $k^{2}-4\omega^{2} > 0$. Therefore the auxiliary equation will have two distinct real roots, $\lambda$ and $\mu$. 
Therefore:
$$
x = Ae^{\lambda t} + Be^{\mu t}
$$

Graphically, this produces no oscillations, the displacement just exponentially decays. An example case of this is an an electromagnetic door closer:
![[Pasted image 20260220105205.png]]

## Case 3 : Critical Damping

Critical damping occurs when the discriminant of the auxiliary equation is equal to 0 i.e $k^{2} - 4\omega^{2} = 0$. Therefore the auxiliary equation will have equal roots $\lambda$. Therefore:
$$
x = e^{\lambda t}(A+Bt)
$$

The difference between critical damping and heavy damping that critical damping will decay the initial amplitude the fastest without oscillating. 

Graphically, this is similar to heavy damping, except with a steeper gradient, signifying faster decay. An example case of this is a car suspension spring and a shock absorber. 
![[Pasted image 20260220105509.png]]

# Example 1
A particle of mass $0.5kg$ moves in a horizontal straight line. It experiences a restoring force of $8xN$, where $x$ is the displacement from a fixed point, $O$. It experiences a resistive force of $4vN$. 

The particle has an initial displacement of $1.5m$ and an initial velocity of 4ms. 

Find $x(t)$ and state the type of damping. 

Setting up the ODE:
$$
\begin{gather*}
\frac{1}{2}\ddot{x}+8\dot{x} +4x = 0 \\ \\
\ddot{x} + 16\dot{x} + 8x = 0
\end{gather*}
$$
Solving the auxiliary equations:
$$
\begin{gather*}
m^{2} + 8m + 16 = 0 \\ \\ 
m = -4t
\end{gather*}
$$
Therefore, the system is a critical damping system and thus:
$$
x = e^{4t}(A+Bt)
$$
We need to differentiate once more to use the boundary conditions:
$$
\dot{x} = -4e^{-4t}(A+Bt) + Be^{-4t}
$$

Now time to use the boundary condition so to find the arbitrary constants:
$$
\begin{gather*}
x(0) = A = 1.5 \\ \\
\dot{x}(0) = -4A + B = 4 \implies 10 \\ \\
x(t) = e^{-4t}(1.5 + 10t)
\end{gather*}
$$

# Example 2
A particle moves in a straight line horizontally, its motion is described by: 
$\ddot{x}+2k\dot{x}+2k^{2}x = 0$

The particle is moved to a positive displacement, d, then released from rest at $t=0$. Find $x(t)$, state the type of damping and find the time, $T$, at which the particle is a instantaneous rest. 

Forming and solving auxiliary equations:
$$
\begin{gather*}
m^{2} + 2km + 2k^{2} = 0  \\ \\
(m+k)^{2} + k^{2} = 0 \\ \\
(m+k)^{2} = -k^{2} \\ \\
m = -k \pm ki
\end{gather*}
$$
Therefore:
$$
x = e^{-kt}(A\cos(kt)+B\sin(kt))
$$
Thus this system is light damping. 
Differentiate for use in boundary cases:
$$
\begin{gather*}
\dot{x} = e^{-kt}(-Ak\sin kt+Bk\cos kt)-ke^{-kt}(A\cos kt+B\sin kt)  \\ \\
= e^{-kt}((Bk-Ak)\cos kt+(-Ak-Bk)\sin t)
\end{gather*}

$$
Forming the boundary conditions:
$$
\begin{gather*}
x(0) = A = d \\ \\
x(0) = -kA + kB = 0 \\ 
\implies k(-d+B) = 0 \\
\implies B =d 
\end{gather*}
$$
Therefore:
$$
x(t) = e^{-kt}(d\cos(kt)+d\sin(kt))
$$

To find the time of instantaneous rest, we need to find when $\dot{x} = 0$. Therefore we need to use $\dot{x}(t)$ again:
$$
\begin{gather*}
\therefore \dot{x}(t) = e^{-kt}(dk-dk)\cos kt + (-dk-dk)\sin kt) \\ \\ 
\dot{x}(t) = e^{-kt}(-2k\sin kt)
\end{gather*}
$$
Equating it to zero. All of the multiplying factors of $\dot{x}(t)$ are constants and since the equation is equal to 0, we can just divide them and consider $\sin kt$ only:
$$
\begin{gather*}
-2ke^{-kt}\sin kt = 0 \\ \\
\sin kt = 0  \\ \\
kt = 0, \pi \\ \\
\boxed{t = \frac{\pi}{k}}
\end{gather*}
$$
