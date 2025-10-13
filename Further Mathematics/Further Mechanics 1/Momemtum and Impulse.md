According to Newton's 2nd law,

$$
F=ma
$$
- m represents the inertia mass of a the object. It represents how much an objects changes it velocity when acted on by a force, F
### What is intertia?
According to many definitions, Inertia is the natural tendency of an object to resist change in its state of motion. Inertia tells us how strong an object's tendency is to resist in its state of motion.

If you increase an object's mass, you will increase it's tendency to resist motin.

If you have an object made of the same material but one is larger, the larger object will have more mass. If the same force was used to push the two objects at once, the larger object

As we know that $F=\frac{\Delta \rho}{\Delta t}$. However the mathematic derivation for this can be shown as follows:

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
