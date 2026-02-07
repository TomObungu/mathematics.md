A 'lamina' is an object where on direction is a very small component to the other two. E.g a sheet of card of thin metal. Laminas can be modelled as 2D objects with only an area and no volume.

'Uniform' laminas have their mass distributed evenly across their area. E.g a sheet of metal with the same thickness throughout.

# Symmetry
If the lamina has a line of symmetry, the mass will be distributed the same either side of the this line. Therefore the centre of mass lies on this line of symmetry. 

if there are multiple lines of symmetry, the centre of mass must lie on both, therefore it lies at the intersection of the lines.

## Rectangle
![[Pasted image 20260203131711.png]]
The centre of mass as the midpoint of both lines

## Circle
![[Pasted image 20260203131747.png]]
The centre of mass lies in the centre of the circle

## Triangles
Isosceles and equilateral triangles have a line of symmetry (equilateral has 3). Thus the centre of mass lies on their intersection
![[Pasted image 20260207102550.png]]

Now consider a general scalene triangle. The median is the line in which the area is split in half and the area on both sides is the same. The median connects C to the point of AB. 

Splitting the area into thin strips, parallel to AB, each strip is split in half by the median. This means the centre of mass of each strip must lie on the median.  

Therefore, the centre of mass of the triangle must also lie on the median. 
![[Pasted image 20260207102850.png]]

We can do the same for the other two medians. We can see that the centre of mass will lie on the intersections of the other two medians:
![[Pasted image 20260207102926.png]]

The centre of mass is the 'centroid' of the triangle. This is the intersections of the three medians

The centroid is $\frac{2}{3}$ of the way down the median form each vertex.  The proof for this is straightforward. However repeating this proof for each vertex, we can see that the centroid G lives at:
$$
G = \left( \frac{x_{1}+x_{2}+x_{3}}{3}, \frac{y_{1}+y_{2}+y_{3}}{3} \right)
$$
For a general triangle, the centre of mass is as the mean of the three vertices. 

This is simplified for right-angle triangles & isosceles triangles, in which their base is parallel to the horizontal. 
![[Pasted image 20260207103334.png]]
For a right angle - The centroid is $\frac{1}{3}$ away from its base and $\frac{1}{3}$ of its height
For an isosceles - The centroid is $\frac{1}{3}$ away from its base, which is $\frac{1}{3}$ of its height#

## Sectors
For a sector of radius $r$ and angle $2\alpha$,
![[Pasted image 20260207103539.png]]
 The centre of mass $G$ is :
 $$
G = \frac{2r\sin\alpha}{3\alpha} \ \ \text{From O}
$$
## Composite Laminas
A composite Lamina is  lamina made up of different shapes. We can split it into its component shapes, then treat each section as a point mass at its centre of mass.

## Example 1
![[Pasted image 20260207113908.png]]
Let's define our origin as $A$. Often define the origin as what is closest resemblance to an x-y axis or if the question requires the centre of mass to be a specific algebraic closed form, define the origin in that matter.

Split the shapes into their component features:
![[Pasted image 20260207114136.png]]

Now using the sum of moments and equaling them to the total mass multiplied by the unknown position of the centre of mass, we can solve for the position of the centre of mass:
$$
\begin{gather*}
2a^{2}\rho \begin{pmatrix}
a \\
\frac{1}{2}a 
\end{pmatrix} + \frac{1}{2}a^{2}\rho \begin{pmatrix}
\frac{7}{5}a \\
\frac{1}{3}a
\end{pmatrix} = \frac{5}{2}a^{2}\rho \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\begin{pmatrix}
\frac{19}{6}a \\
\frac{7}{6}a
\end{pmatrix} = \frac{5}{2}\begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} \\ \\
\therefore \begin{pmatrix}
\bar{x} \\
\bar{y}
\end{pmatrix} = \begin{pmatrix}
\frac{19}{15}a \\
\frac{7}{15}a
\end{pmatrix}
\end{gather*}
$$
Thus the centre of mass is $\frac{19}{15}a$ from AD and $\frac{7}{15}a$ from AB.


# Example 2
In this problem you must consider the semicircle as a sector with $2\alpha = \pi$ and thus $\alpha=\frac{\pi}{2}$.
![[Pasted image 20260207124343.png]]
Furthermore, you must take precaution with calculating the areas of the laminas correctly
![[Pasted image 20260207124521.png]]
Using the sum of moments formula:
$$
\frac{1}{2}\pi a^{2} \begin{pmatrix}
-\frac{4}{3\pi} \\
a
\end{pmatrix} + 8a^{2}\begin{pmatrix}
2a \\
a
\end{pmatrix}
$$