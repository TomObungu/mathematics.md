# Oblique impact of two smooth spheres
In questions involving oblique collisions we are look at the scenario from a top-down approach. 

When two spheres collide, there is a common tangent between them. The normal to this tangent is the 'line of centres.' 

![[Pasted image 20251109142638.png]]

If the the sphere's velocity are in the direction of the line of centres it is just a 1-D collision. 

An 'oblique' collision  is one in which the two spheres are not travelling along the line of centres.

The impulse always acts to the normal of the point of contact (the common tangent), the impulse experienced by each sphere acts along the line of centres.

Therefore for Oblique collision, the only components that change are those acting along the.

This means that any motion perpendicular to the line of action is unchanged. 

![[Pasted image 20251109142841.png]]

## Worked Example 1
A moving at 4ms at $40^\circ$ to the line of centres. $e=\frac{3}{5}$. Find the speed and direction of both spheres after impact and the angle through which $A$ is deflected. 
![[Pasted image 20251109142916.png]]
Drawing a diagram of conservation of momentum:
![[Pasted image 20251110212125.png]]
$$
\begin{gather*}
2(4\cos40^\circ)=2v_{1}+3v_{2}
\end{gather*}
$$
Newton's Law Of Restitution:
$$
v_{2}-v_{1}=\frac{3}{5}(4\cos 40^\circ)
$$
Putting the equations into the solve in the calculator:
$$
v_{1}=0.123 \qquad v_{2}=1.96
$$
To find the angle of deflection, you need to extend the original line of motion and compare it with the new line of motion of the and compare the difference in the angles:
![[Pasted image 20251110212414.png]]
The angle of deflection is $\gamma$:
$$
\begin{gather*}
\beta = \arctan\left( \frac{4\sin 40^\circ}{0.123} \right) = 87.3 \\ \\
\text{Angle of deflection, } \gamma = 87.3-40
\end{gather*}
$$
This is the case as:
![[Pasted image 20251110213103.png]]
Speed of $A=\sqrt{ 0.123^{2}+(4\sin 40 ^\circ) }=2.57$ at $87.3\$. Speed of $B$ = 1.96
# Worked example 2
Given that $e$ between the spheres is $\frac{3}{4}$. Find the magnitude of velocities after collision.
![[Pasted image 20251110235230.png]]D
Conservation Of Momentum:
![[Pasted image 20251110235312.png]]
$$
\begin{gather*}
2(5\cos 45^\circ) - 8\cos 30^\circ = 2v_{1}+v_{2} \\
2v_{1} + v_{2} = 5\sqrt{ 2 }-4\sqrt{ 3 }
\end{gather*}
$$
Newton's Law Of Restituion:
$$
\begin{gather*}
v_{2}-v_{1} = \frac{3}{4}(5\cos 45^\circ+8\cos_{3}0^\circ) \\ \\
v_{2}-v_{1} = \frac{24\sqrt{ 3 }-15\sqrt{ 2 }}{8} \\ \\
v_{1} = 2.568 \qquad v_{2} = 5.279
\end{gather*}
$$
Find the magnitudes and directions:
![[Pasted image 20251110235605.png]]

# Worked Example 3
It is possible to have oblique collisions given as vectors:
![[Pasted image 20251110235711.png]]
Convservation Of Restitution:
$$
\begin{gather*}
5(3)-3(2) = 5v_{1}+3v_{2} \\ 
5v_{1}+3v_{2}=9
\end{gather*}
$$
Newton's Law Of Restitution:
$$
 \begin{gather*}
v_{2}-v_{1}=\frac{3}{5}(2+3) \\
v_{2}-1v_{1} = 3 \\ \\
\therefore v_{1} = 0 \qquad v_{2} = 3 \\ \\
V_{A} = 2i \qquad V_{B}=4i+3j
\end{gather*}
$$
To calculate the K.E lost in the collision, you must take components before and after the collision;
![[Pasted image 20251111000019.png]]

# Worked Example 5
![[Pasted image 20251111120649.png]]
In this example, the direction of rotation of A is turned by $90^\circ$. In order to represent this diagrammatically properly. You need to extend the initial of motion an d rotate from that line by $90^\circ$. This process will work for any question that states the rotation that the motion is turned by:
![[Pasted image 20251111121022.png]]
From the diagram you can see that the new direction of motion will form a right angle triangle. The angle in the bottom left corner of the triangle will be equal to alpha:
![[Pasted image 20251111123234.png]]
It is also possible to work out the direct angle the line makes with the line of centres:
![[Pasted image 20251111123136.png]]In this case, the angel $\beta$ will be equal to:
$$
\begin{gather*}
\beta = 180-90-\alpha \\
\beta = 90 - \alpha
\end{gather*}
$$
This is because it lies on a straight line along the original direction of motion. 
When the angle is usually $90-\alpha$ then eventually you will end up using $\cos(90-\alpha)=\sin\alpha$, $\sin(90-\alpha)=\cos\alpha$ or $\tan(90-\alpha)=\cot\alpha$ for later parts in your working when showing a proof. 

For this question we will use the the first scenario of the angle at the bottom left corner of the triangle. Forming the conservation of momentum diagram:
![[Pasted image 20251111191154.png]]


The next biggest thing with this question is that if we are told the direction has been turned by $90^\circ$. This proves to show that the direction of motion is towards the opposite direction. 

**This means that component along the line of centres will be negative**. This means that $v_{1}$ will be $-v_{1}$Always consider this case for all problems like this:
![[Pasted image 20251111190638.png]]
$$
\begin{gather*}
mu\cos\alpha=4mv_{2}-mv_{1}\\ 
4v_{2}-v_{1} = u\cos\alpha \ (1)
\end{gather*}
$$
Newton's Law Of Restitution:
$$
\begin{gather*}
\frac{v_{2}--v_{1}}{u\cos\alpha} = \frac{1}{2} \\ \\
v_{2}+v_{1} = \frac{1}{2}u\cos\alpha \\ \\
2v_{2}+2v_{1}=u\cos\alpha \ (2)
\end{gather*}
$$
We know that $v\sin\alpha=v_{1}$ therefore we must find $v_{1}$:
$$
\begin{gather*}
(1) + (-2(2)) : \\
4v_{2}-v_{1}=u\cos\alpha \\
-4v_{2}-4v_{1} = -2u\cos\alpha \\ \\
-5v_{1} = -u\cos\alpha \\ \\
\implies v_{1} = \frac{1}{5}u\cos\alpha
\end{gather*}
$$
This means that $vsin\alpha = \frac{1}{5}u\cos\alpha$. Forming the complete set of equations:
$$
\begin{gather*}
v\sin\alpha = \frac{1}{5}u\cos\alpha \\ \\
v\cos\alpha = u\sin\alpha
\end{gather*}
$$
Forming an equation for $\tan\alpha$:
$$
\begin{gather*}
\tan\alpha = \frac{1}{5}\cot\alpha \\
5\tan\alpha = \frac{1}{\tan\alpha} \\ 
\tan ^{2}\alpha = \frac{1}{5} \\ \\
\end{gather*}
$$
Therefore:
$$
\boxed{\tan\alpha=\sqrt{ \frac{1}{5} }}
$$
# Modelling assumption:
The modelling assumption in all these questions is that the spheres has equal radii. Consider if this was not the case:
![[Pasted image 20251111191857.png]]
If this was not the case then spheres collision would not be in the same plane as their velocities. 

Essentially it always ensures that the Impulse direction will always act parallel to the line of centres