1D Elastic collisions contain problems involving multiple collisions: 

# Ball bouncing
A ball is dropped form a height, h. It bounces to a height of $h_{1}$, after the second returns to a second height $h_{2}$, after the third height is $h_{3}$, etc...

For questions involving the vertical speed of the particle,
it's speed just before it hits the ground can be calculated using:
$$
u = \sqrt{ 2gh }
$$
The speed of the ball when it bounces of the ground will be:
$$
v = eu
$$
If given the height of the ball only, when the ball travels a height $h_{1}$ again. It will hit the ground with speed 
$$
v =\sqrt{ 2gh_{1} }
$$

Forming a WEP equation will lead to finding out the coefficient of restitution:
$$
\begin{gather*}
u = \sqrt{ 2gh } \qquad v = \sqrt{ 2gh_{1} } \\
\therefore e = \frac{v}{u} = \frac{\sqrt{ 2gh }}{\sqrt{ 2gh_{1} }}
\end{gather*}
$$

# Worked Example 2
Both walls have a coefficient of restitution $e$. The particle is projected midway between $A$ and $B$, B with velocity $4ms^{-1}$. Show that time taken for the particle to return to its starting position after bouncing off both walls once is: $\frac{(e+1)^{2}d}{8e^{2}}$

Write out the velocity of each collision and their times based on the distances travelled:
$$
\begin{gather*}
\text{After first collision: } v_{1} = 4e \\ \\
\text{After second collision: } v_{2}=4e^{2} \\ \\
\text{Time to hit B, } t_{1} = \frac{\left(\frac{d}{2}\right)}{4} = \frac{d}{8} \\ \\
\text{Time to hit A, } t_{2} = \frac{d}{4e} \\ \\
\text{Time from A to midpoint, } t_{3} = \frac{\left(\frac{d}{2}\right)}{8e^{2}} \\ \\
\therefore \text{Total time t} = \frac{d}{8}+ \frac{d}{4e} + \frac{d}{8e^{2}} \\ 
= \frac{e^{2}d}{8e^{2}} + \frac{2ed}{8e^{2}} + \frac{d}{8e^{2}} \\ 
= \frac{(e^{2}+2e_{1})d}{8e^{2}} = \frac{(e+1)^{2}d}{8e^{2}} \\ \\
QED
\end{gather*}
$$
# Worked Example 3
$A$(4kg) particle particle is projected towards $B$ (11kg) at $ums^{-1}$. B is initially at rest. After the collision, the direction of $A$ is reversed. B hits a smooth wall rebounds. The coefficient of restituion between the spheres is $e$. The coefficient of restitution between the sphere and the wall is $\frac{e}{2}$. 

Find the range of values of $e$ for which there is a second collision between $A$ and $B$

Start off by finding the first collision between $A$ and $B$ 
![[Pasted image 20251020224017.png]]

$$
\begin{gather*}
\underline{\text{First Collision}} : \\
\text{Conservation Of Momentum } : \\ 
4u = 4v_{1} + 11v_{2} \ (1)  \\ \\
\text{Newton's Law Of Restitution} : \\
\frac{v_{2}-v_{1}}{u} = e \\
\therefore v_{2}-v_{1}=eu \ (2)
\end{gather*}
$$
For such situations, it is beneficial to rearrange to find the missing unknowns $v_{1}$ and $v_{2}$. 
$$
\begin{gather*}
(1) + 4(2): \\
15v_{2} = 4u + 4eu \\ 
v_{2} = \frac{4}{15}u(1+e) \\ \\ \\
(1) - 11(2): \\ 
15v_{1} = 4u - 11eu \\ 
v_{1} = \frac{1}{15}u(4-11e)
\end{gather*}
$$
Now we have $v_{1}$ and $v_{2}$. We can now use the problem statements to find the values of $e$.

$$
\begin{gather*}
\text{Problem states "Direction of A is reversed"} \therefore v_{1} < 0  \\ \\
\implies \frac{1}{15}u(4-11e) < 0  \\ 
\implies 4-11e < 0  \\ \\
\therefore e > \frac{4}{11}
\end{gather*}
$$
This gave us the lower bound of $e$. Now we can calculate the upper bound of $e$ based on the second collision with the wall:
![[Pasted image 20251020225630.png]]
$$
\begin{gather*}
\underline{\text{Second collision}} : \\
v_{3} = -\frac{2}{15}u(1+e) 
\end{gather*}
$$
In order for a second collision to occur between $A$ and $B$, $B$ must be faster than $A$. $|v_{3}| > |v_{1}|$. Accounting for the values being negative, the smaller negative value is the one with the largest speed:
$$
\begin{gather*}
v_{1} = \frac{1}{15}u(4-11e) \qquad v_{3} = -\frac{2}{15}eu(1+e) \\ \\
v_{3} < v_{1} \\ \\
\therefore -\frac{2}{15}e\cancel{ u }(1+e) < \frac{1}{15}\cancel{ u }(4-11e) \\ \\
-2e -2e^{2} < 4-11e \\ \\
2e^{2}-9e+4 > 0 \\ \\ 
e<\frac{1}{2} \qquad \cancel{ e>4  }
\end{gather*}
$$
We have $e< \frac{1}{2}$ required for the second collision. Also direction of $A$ is reversed so $e>\frac{4}{11}$. Therefore:
$$
\boxed{\frac{4}{11}<e < \frac{1}{2}}
$$


