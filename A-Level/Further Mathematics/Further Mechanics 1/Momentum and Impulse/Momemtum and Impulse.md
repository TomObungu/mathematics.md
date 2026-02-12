According to Newton's 2nd law,

$$
F=ma
$$
- m represents the inertia mass of a the object. It represents how much an objects changes it velocity when acted on by a force, F
### What is inertia?
According to many definitions, Inertia is the natural tendency of an object to resist change in its state of motion. Inertia tells us how strong an object's tendency is to resist in its state of motion.

If you increase an object's mass, you will increase it's tendency to resist motion.

If you have an object made of the same material but one is larger, the larger object will have more mass. If the same force was used to push the two objects at once, the larger object

As we know that $F=\frac{\Delta \rho}{\Delta t}$. However the mathematical derivation for this can be shown as follows:

We can write $F=ma$ as $F=m\frac{dv}{dt}$. We known that $mv$ is the momentum. Therefore:
Force = rate of change of momentum.

In order for to keep the same force, if the mass of the object is greater, $\frac{dv}{dt}$  will be smaller.

However this means that $\frac{d(mv)}{dt}$ is always the same.

# Impulse
Consider a force, F, acting on a object for time t (from $t_{1}$ to $t_{2}$). If $F=m \frac{dv} {dt}$

Then we can solve this differential equation for a constant force F. This is because if F is a constant with respect to t, we can just multiply by t due to the power rule.  If F was not constant then we will need to use advanced integration techniques.
$$
\begin{gather*}
\int_{t_{1}}^{t_{2}} F dt = \int_{u}^{v}mdv \\ \\
[Ft]_{t_{1}}^{t_{t_{2}}} = [mv]_{u}^{v} \\ \\
F(t_{2} - t_{1}) = mv - mu \\
\end{gather*}
$$
As $t=t_{2} - t_{1}$ then 
$$
Ft = mv-mu
$$
Which leads us back to:
$$
\begin{gather*}
F=\frac{mv-mu}{t} \\ \\
F = \frac{\Delta p}{\Delta t}
\end{gather*}
$$

However we define the  impulse an object as the change in momentum of an object. 

If:
$$
Ft = mv - mu
$$
Then impulse is $Ft$ or written differently:
$$
I = mv - mu
$$
Impulse has units $kgms ^{ -1}$

## Worked example 1
A 10N force acts for 5s, find the final velocity $v$ of an object.
![[Pasted image 20251013172820.png]]
First chose the positve direction because momentum is a vector. In this we define positive as to the right:
$$
\begin{gather*}
Ft=mv
\end{gather*}
$$
In this case $F=10$ and $t=5$ therefore the impulse is $Ft=\Delta \rho=10(5)$. This also means $Ft=\Delta p=mv-mu$If the right is the positive direction:
$$
10(5) = 5v -5(2) \qquad \therefore 5v = 10(5)+5(2) \qquad \therefore v =12
$$
## Worked example 2
A ball hits the wall at 4$ms ^{-1}$ and rebounds at 3$ms ^{-1}$. Find the magnitude and direction of the impulse exerted by the wall on the ball. 

The impulse is simply the direction of the change in momentum and it's magnitude. When the object in motion changes it momentum, it will change relative to a direction with a certain magnitude. 

If the ball rebounds then it's change in momentum is towards the left therefore it's impulse is also towards the left. 

If the impulse is acting towards the left then it means we can set the positive direction of motion towards the left. 
![[Pasted image 20251013173846.png]]
$$
\begin{gather*}
I = mv - mu \\ \\
I = 1.5(3) - 1.5(-4) = 10.5
\end{gather*}
$$
# Worked example 3 class
A ball of mass 0.2 dropped 2.5m rebounds to 1.8m. Calculate the impulse exerted by the ground on the ball.
![[Pasted image 20251013174719.png]]
Since the impulse of the ground is causing the ball to rebound vertically upwards, we can define vertically upwards as the positive direction of motion

For this equation we need:
$$
I = mv - mu
$$
It is possible to calculate the velocity of an object from free fall using $v=\sqrt{ 2gh }$ (can be proved using SUVAT or work energy principle)
$$
\begin{gather*}
u = \sqrt{ 2g(2.5) } = 7
\end{gather*}
$$
The same equation is also applicable to $v$:
$$
v = \sqrt{ 2(9.8)(1.8) } = 5.940 ms ^{-1}
$$
Therefore:
$$
I = 0.2(5.940) - 0.2(-7) = 2.59 Ns \text{Upwards}
$$

## Note on impulse
The impulse required to change object's momentum is independent of gravity. Moment depends on the mass of the object not the weight. 

# Worked example 
A 2kg particle is moving with velocity $2i+3j$. It experiences an impulse of $-i+2j$. Find its new velocity and the angle of deflection.
![[Pasted image 20251013175457.png]]
In this case, if we are given impulse as a vector and the velocity of an object as a vector it is possible to use:
$$
\begin{gather*}
I = mv - mu \\ 
i + 2j = 2v - 2(2i + 3j \\ 
2v = 3i + 8j \\ \\
\therefore v = \frac{3}{2}i + 4j
\end{gather*}
$$
The angle of deflection is the angle the particle turn grom its original direction, $\theta$. This angle is calculated using the dot product:
$$
\cos\theta = \frac{\begin{pmatrix}
2 \\
3
\end{pmatrix} \cdot \begin{pmatrix}
\frac{3}{2} \\
4
\end{pmatrix}}{\left|\begin{pmatrix}
2 \\
3
\end{pmatrix}\right|\left|\begin{pmatrix}
\frac{3}{2} \\
4
\end{pmatrix}\right|} = 13.1 ^\circ
$$
## Worked example 5
A 0.4kg particle is moving at a constant velocity, u when it receives and impulse of $-5i+3j$. After receiving the impulse. the particles velocity is $12i+15j$.

Find $u$ the angle of deflection and the KE lost by the particle as a result of the impulse.

$$
\begin{gather*}
-5i+3j = 0.4(12i+15j) - 0.4u \\
-12.5 + 7.5j = 12i + 15j - u \\ 
u = 24.5i +7.5j
\end{gather*}
$$
Using the dot product to calculate $\theta$
$$
\begin{gather*}
\cos \theta = \frac{\begin{pmatrix}
24.5 \\
7.5
\end{pmatrix} \cdot \begin{pmatrix}
12 \\
15
\end{pmatrix}}{\left|\begin{pmatrix}
24.5 \\
7.5
\end{pmatrix}\right|\left|\begin{pmatrix}
12 \\
15
\end{pmatrix}\right|}
\end{gather*} \\
\theta = 34.3^\circ
$$
The change in kinetic energy is just the $KE_{final} - KE_{initial}$:
$$
\Delta KE=\frac{1}{2}m|v|^{2} - \frac{1}{2}m|u|^{2} \\ 
= \frac{1}{2}(0.4)((12^{2}+15^{2}) = (24.5^{2}+7.5^{2}))
= -57.5
$$
As the change in kinetic energy is negative this means the there has been a loss of kinetic energy in the environement:
$$
\therefore 57.5J \text{ loss}
$$
