Before particles collide, they are travelling towards each other
![[Pasted image 20251020204226.png]]
When the particles collide, they are compressed. Some of the kinetic energy is lost as it is transferred into heat and sound.
Some of the kinetic energy is stored as it transformed into elastic potential energy.
![[Pasted image 20251020204322.png]]
The particles then spring back and release the stored elastic potential energy to be transformed back into kinetic energy.
![[Pasted image 20251020204358.png]]
After, the particles have final velocities and are moving away from each other:
![[Pasted image 20251020204428.png]]

# Fully elastic collisions:
If a collision is fully elastic, then no energy is lost - all it's initial KE is stored as EPE then transferred back into KE:
$$
\text{Total KE (before)} = \text{Total KE (after)} 
$$
In reality, no collision is fully elastic. There will always be some energy lost as heat or sound.

# Fully inelastic collisions:
A collision is fully inelastic if the objects coalesce (stitch together) after colliding. 

If this happens, it means none of the kinetic energy got stored as elastic potential energy as they did not spring apart 

Therefore, the maximum amount of kinetic energy was lost. Not necessarily all of it, just the max amount.

## What this means
In a perfectly inelastic collision, the objects will coalesce. However due to conservation of momentum, if the objects were moving, then combined particle will still have momentum.

However the particles, when they colliding to coalesce to form a combined particle, will show no signs of "bouncing back off each other" and instead will remain coalesced after collision.

In order for this to happen, the maximum amount of kinetic energy will have needed to be lost such that the EPE from the collision is dissipated and there will be no restitution. The EPE is dissipated as either heat, sound or permanent deformation but not transferred into KE. 

However there is still some overall KE in the coalesced particles due to conservation of  momentum of particles that is not from the collision. 

# Newton's Law Of Restitution

The coefficient of restitution $e$ is given by
$$
\frac{v_{2} - v_{1}}{u_{1}-u_{2}} = e
$$
## Elastic collision
In a perfectly elastic collision $e=1$ as the particles will "bounce off each other" with the same velocities however in reverse direction - negated values:
## Inelastic collision
In an inelastic collision, $e=0$, this is because the particles will coalesce and therefore will have the same final velocity.

## All other collisions
When particles do not coalesce or rebound with the same speed i.e when the collision is not perfectly inelastic or elastic, $0<e<1$.


Therefore:
$$
\begin{gather*}
e = \frac{v_{2}-v_{1}}{u_{1}-u_{2}} = \frac{\text{speed of seperation}}{\text{speed of approach}} \\ \\
0\leq e\leq_{1}
\end{gather*}
$$
# Worked Example 3
P(m) moves with speed $4u$ when it collides with stationary particle $Q$ mass $3m$. Given the direction of $P$ reversed after the collision. Find the value of $e$.

For such problems, always label unknown values of velocity going to right to simplify calculations are reduce chance of error with signs.

![[Pasted image 20251015175641.png]]

Start of by writing the equations as a result of conservation of momentum:
$$
\begin{gather*}
m(4u)=mv_{1} + 3mv_{2} \\ 
4u = v_{1} + 3v_{2} \qquad (1)
\end{gather*}
$$
Secondly, form the equations as a result of restitution:
$$
\begin{gather*}
\frac{v_{2}-v_{1}}{4u} = e \\ \\
v_{2}-v_{1} = 4eu \qquad (2)
\end{gather*}
$$
As it is known that the direction of P was reversed, it's final velocity $v_{1}$ will be negative as it is travelling in the other direction. Therefore we need to find $v_{1}$ in terms of $4u$ and $e$ using equations equations $(1)$ and $(2)$:
$$
\begin{gather*}
(1) - 3 \times (2) : \\ \\
4v_{1} = 4u - 12eu \\
v_{1} = u - 3eu \\
v_{1} = u(1-3eu)
\end{gather*}
$$
As we know that $v_{1} < 0$. Form the inequality by comparing the 
$$
\begin{gather*}
v_{1} < 0 \\
u(1-3e) < 0 \implies (1-3e) < 0 \\
1-3e < 0 \\
1 < 3e \\ 
\frac{1}{3} < e
\end{gather*}
$$
Therefore: 
$$
\frac{1}{3} < e \leq 1
$$

# Worked Example 3 continued...
Given that the kinetic energy after the collision is $\frac{1}{16}th$ of what is was before, find the exact value of $e$.

Since we have the initial and final velocity of particle $P$ and we are told that the $KE$ is $\frac{1}{16}th$ of what is was before, we can substitute the values of $u_{1}$ and $v_{1}$ to form an equation for $e$:

$$
\begin{gather*}
\text{KE after} = \frac{1}{2}(m)(v_{1})^{2} \\ \\
\text{KE before} = \frac{1}{2}(m)(4u)^{2} \\ \\
\frac{1}{2}(m)(u(1-3e))^{2} = \frac{1}{16}\left( \frac{1}{2}(m)(4u)^{2} \right) \\ \\
(1-3e)^{2} = 1 \\ \\
e = 0 \qquad e = \frac{2}{3}
\end{gather*}
$$
However as $\frac{1}{3} < e$, thefore:
$$
e = \frac{2}{3}
$$
