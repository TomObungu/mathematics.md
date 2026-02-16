Consider A uniform rod hinged at one and released from being held horizontally.
Since the centre of mass, G, produces a moment about the pivot, the rod is not in equilibrium and swings clockwise
![[Pasted image 20260216211944.png]]

The rod will end up hanging in equilibrium when the centre of mass is directly vertical below the pivot. 
The is because in this position, the perpendicular distance from the line of action of the force, weight, to the pivot is zero. Thus there is no moment:
![[Pasted image 20260216212134.png]]

The same applies to any obect, including laminas and frameworks. 

The object hangs in equilibrium when the centre of mass is vertically below the point of suspension. 

For example, a triangular lamina ABC will look like this when hung in equilibrium about A:
![[Pasted image 20260216212312.png]]


# Angle with the vertical
Questions often ask you to find the angle that a certain line makes with the downward vertical when the object is suspended. 

Consider the same example of triangle ABC. 

$\theta$ is the angle that AB makes with the downward vertical. The downward vertical is the line joining the centre of mass and the point of suspension.

![[Pasted image 20260216212456.png]]

Knowing this, we don't have to draw it hanging and titled. We can just extend a line from the vertex of suspension to centre of mass and label the subtending angle $\theta$. This line is the downward vertical.
![[Pasted image 20260216212558.png]]

# Example 1
ABC is a uniform lamina. Find the angle that AB makes with the downward vertical when it is suspended from A. 
![[Pasted image 20260216212658.png]]

From the law of that the centre of mass is about 1 third away from the 'flat sides' in a right angle triangle, we known the the horizontal distance from $AB = \frac{2}{3}a$, and the vertical distance from $BC= \frac{1}{3}a$. Thus the length of the adjacent side in the triangle formed to work out $\theta$ will be $a - \frac{1}{3}a=\frac{2}{3}a$Thus it is possible to work out theta by using $\arctan$:
$$
\theta = \arctan\left( \frac{\frac{2}{3}}{\frac{2}{3}} \right) = 45^\circ
$$
# Example 2
Uniform lamina AFEDCB is suspended from vertex F. Find the angle that EF makes with the downward vertical.
![[Pasted image 20260216213300.png]]

In this problem you must find out the position of the centre of mass using the already learned techniques of splitting the lamina in individual components. Afterwards you must compute the lengths of the triangle formed with the downward vertical as the hypotenuse.

Forming the table. In questions like this, it is useful to the origin as the vertex of suspension and the adjacent lines from the vertex as the x and y component planes. 

As well as that it is also beneficial to set the downward direction as positive 

| Object            | Sqr. ABF  | Rect. EDC      | Total     |
| ----------------- | --------- | -------------- | --------- |
| Area              | $16a^{2}$ | $6a^{2}$       | $22a^{2}$ |
| CoM Dist. From EF | $-2a$     | $\frac{3}{2}a$ | $\bar{x}$ |
| CoM Dist. From AF | $2a$      | $3a$           | $\bar{y}$ |

Using the formula to work out $\bar{x}$ and $\bar{y}$:
$$
\begin{gather*}
16a^{2}(-2)+6a^{2}\left( \frac{3}{2}a \right)=22a^{2}\bar{x} \\ \\
\bar{x} = -\frac{23}{22}a \\ \\ \\
16a^{2}(2a)+6a^{2}(3a) = 22a^{2}\bar{y} \\ \\
\bar{y} = \frac{25}{11}a
\end{gather*}
$$
Therefore it is possible to work out $\theta$ using $\arctan$:
$$
\theta = \arctan\left( \frac{\frac{23}{23}a}{\frac{25}{11}a}\right) = 24.7^\circ
$$

# Example 3
The uniform lamina is formed by removing a square PQRE from an isosesles triangle ABC, where AC=BC. The centre of the square is O. PQ=4cm. 

When the lamina is suspended freely from A, it hangs in equilibrium with AB at $25^\circ$ to the downward vertical. 

Find the distance of $O$ from DC.

![[Pasted image 20260216221352.png]]

In this problem, the missing distance can be labelled as an unknown variable $y$. 

For this question, you must find the centre of mass in terms of the missing variable $y$ and rearrange to solve for $y$ when found the actual value of the centre of mass. 

Firstly set up the table for the shape. Include the area of the cut out square as a negative value:


| Object             | Trngl. ABC    | Sqr. PQRS | Total     |
| ------------------ | ------------- | --------- | --------- |
| Area               | 48            | -16       | 32        |
| CoM dist. from AB  | $\frac{8}{3}$ | 2         | $\bar{x}$ |
| CoM dist. from  DC | 0             | $y$       | $\bar{y}$ |
Forming the equations to calculate the centre of mass $\bar{x}$ and $\bar{y}$ components:

$$
\begin{gather*}
\frac{8}{3}(48)-2(16) = 32\bar{x} \implies \bar{x}=32 \\ \\
-16y=32\bar{y} \implies \bar{y} = -\frac{1}{2}y 
\end{gather*}
$$

From the question, we know that the angle between the vertical is $25^\circ$ thus we can form an equation of $\tan 25$:

Remember that the side length of the adjacent of the triangle formed by the downward vertical will be $6-\bar{y}$ as it is the length of the long side from the vertex A. 
![[Pasted image 20260216225843.png]]
Therefore: 
$$
\begin{gather*}
\tan 25 = \frac{3}{6-\bar{y}} \\ \\
\bar{y} = -0.4435
\end{gather*}
$$
Now we can rearrange for $y$:
$$
\begin{gather*}
\frac{1}{2}y =-0.4335 \\ \\ 
y = 0.867 
\end{gather*}
$$
Thus the distance of $O$ from $DC$ is $0.867$

# 'Two string' problems
Laminas and frameworks can also be suspended from two strings, like we did with uniform rod moment problems with their centres of mass based in the midpoint of the rod. It is no more different with laminas and frameworks except with the centre of mass being in a separate position and dealing with the perpendicular distance of the centre of mass to the pivot.

## Example 4
Uniform lamina ABCDEGH lays in equilibrium from two light inextensible strings attached to A and D, with BC horizontal.  Find the tension in the string attached to $A$, $T_{A}$ and the tension in the string attached to B, $T_{B}$:
![[Pasted image 20260216231429.png]]

Firstly, start by calculating the centre of mass of the lamina:

| Object      | Rect. AHB | Rect. GF      | Rect GDC       | Total     |
| ----------- | --------- | ------------- | -------------- | --------- |
| Area        | 8         | 6             | 9              | 23        |
| CoM from AB | 1         | $\frac{7}{2}$ | $\frac{13}{2}$ | $\bar{x}$ |
Forming the equations:
$$
8(1)+6\left( \frac{7}{2} \right) + 9\left( \frac{13}{2} \right) = 23\bar{x} \implies \bar{x} = \frac{175}{46}
$$

Now we know the perpendicular distance of the centre of mass from string A. The problem can be reduced to a uniform rod problem.
![[Pasted image 20260216231841.png]]

Taking the same procedure as A level mechanics:
Setting up the equations of forces:
$$
T_{A} + T_{D} = Mg
$$
Setting up the moment equations from A:
$$
\begin{gather*}
\frac{175}{46}Mg = 8T_{D} \\ \\
\therefore T_{D} = \frac{175}{368}Mg
\end{gather*}
$$
Thus:
$$
T_{A} = \frac{193}{368}Mg
$$

## Example 5
Framework ABCD is suspended from C. Length AD has 3 times the mass per unit length of AB, BC and CD.

The framework is in equilibrium with AB horizontal when horizontal force $X$ is applied at B. 
![[Pasted image 20260216233731.png]]

For these types of question, you only need to consider the perpendicular horizontal component as you will deal with moments. Thus you only need to consider $\bar{x}$ for this problem.

Firstly set up the table. Remember that you are dealing with frameworks and set the origin as the edge that the vertex of suspension lies on:

Do not forget that the mass of AD is three times the mass of AB, DC and CB. To account for this, triple the length. 

| Object            | Length AD      | Length DC | Length AB | Length CB | Total                |
| ----------------- | -------------- | --------- | --------- | --------- | -------------------- |
| 'Length'          | $3\sqrt{ 13 }$ | $4a$      | $6a$      | $3a$      | ($13 + \sqrt{ 13 }$) |
| CoM Dist. From BC | 5a             | 2a        | 3a        | 0         | $\bar{x}$            |
Setting up the equations:
$$
\begin{gather*}
5a(3\sqrt{ 13 }) + 4a(2a)+6a(3a)+3a(0) = (13+3\sqrt{ 13 })a\bar{x} \\ \\
(15\sqrt{ 13 }+26)a = (13+3\sqrt{ 13 })\bar{x} \\ \\
\bar{x} = \frac{9\sqrt{ 13 }-19}{4}a
\end{gather*}
$$
Now consider this as a moments problem again. Remember that with forces and moments, always consider the distance perpendicular from force to the pivot. In this case, if we were to draw it as a uniform rod, we can see that the perpendicular distance of the weight force, $Mg$ from the pivot will be $\bar{x}$. For the force $x$, as it acts horizontally, the vertical distance is the perpendicular distance from the pivot and thus the perpendicular distance will be the length of CB which is 3a.

![[Pasted image 20260216235130.png]]

Thus only considering the perpendicular distances for the forces, we can set up a moment equation to solve for force X.

Taking moments about C:
$$
\begin{gather*}
3aX = \frac{9\sqrt{ 13 }-19}{4}aMg \\ \\
X = \frac{9\sqrt{ 13 }-19}{12}Mg
\end{gather*}
$$
