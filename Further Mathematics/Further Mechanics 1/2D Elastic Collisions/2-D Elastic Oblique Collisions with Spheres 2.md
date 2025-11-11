It is possible to have 2-D Oblique collisions with spheres with vectors and with a line of centres parallel to a vector equation:

# Worked Example 1
![[Pasted image 20251111192339.png]]
We know that the impulse will always be in the line of centres, there for if we calculate the impulse of $A$, we will get the vector of the impulse;
$$
\begin{gather*}
\text{Impulse On A : } I = 2\left[\begin{pmatrix}
1 \\
3
\end{pmatrix} - \begin{pmatrix}
3 \\
1
\end{pmatrix} \right] = \begin{pmatrix}
-4 \\
4
\end{pmatrix} = 4\begin{pmatrix}
-1 \\
1
\end{pmatrix} \\ \\ = 4(-i+j) \\ 
\text{Impulse acts along the line of centres. Impulse is parallel to } -i+j \\ 
QED
\end{gather*}
$$
![[Pasted image 20251111192725.png]]
We know that $I_{A}=-I_{B}$ this means that the impulse of $B$ will be $\begin{pmatrix}4 \\ -4\end{pmatrix}$. With this information we can form an equation for impulse:
$$
\begin{gather*}
\begin{pmatrix}
4 \\
-4
\end{pmatrix} = 3\begin{pmatrix}
V_{B} -\begin{pmatrix}
-1 \\
2
\end{pmatrix}
\end{pmatrix} \\ \\
3V_{B} =\begin{pmatrix}
1 \\
2
\end{pmatrix} \\ \\
V_{b} = \frac{1}{3}\begin{pmatrix}
1 \\
2
\end{pmatrix} = \frac{1}{3}(i+2j)
\end{gather*}
$$
![[Pasted image 20251111193549.png]]
To do this part of the question, you must think back to find the unit components of parallel to the line of centres and forming an equation for $e$.:

We know that the line of centres is parallel to $(-i+j)$ therefore the unit vector for the line of impulse is $\frac{1}{\sqrt{ 2 }}(-i+j)$. If we draw a diagram for this scenario, we can see that:
![[Pasted image 20251111193832.png]]
and:
![[Pasted image 20251111194413.png]]
To find these components we must take the dot product of the incoming vectors with with the unit vector of the impulse. As the impulse only acts in the direction in the line of centres, we only need to use the unit vector parallel to the line of centres
$$
\begin{gather*}
\text{Unit vector parallel to LOC : } \frac{1}{\sqrt{  2}}(-i+j ) \\ \\
u_{A\parallel} = \begin{pmatrix}
3 \\
1
\end{pmatrix} \cdot \left[ \left( \frac{1}{\sqrt{ 2 }} \right)\begin{pmatrix}
-1 \\
1
\end{pmatrix} \right] = -\frac{2}{\sqrt{ 2 }} \\ \\
u_{B\parallel} = \begin{pmatrix}
-1 \\
2
\end{pmatrix} \cdot \left[ \left( \frac{1}{\sqrt{ 2 }} \right)\begin{pmatrix}
-1 \\
1
\end{pmatrix}\right] = \frac{3}{\sqrt{ 2 }} \\ \\
v_{A\parallel} = \begin{pmatrix}
1 \\
3
\end{pmatrix} \cdot\left[ \left( \frac{1}{\sqrt{ 2 }} \right) \begin{pmatrix}
-1 \\
1
\end{pmatrix}\right] = \frac{2}{\sqrt{ 2 }} \\ \\
v_{B\parallel} = \frac{1}{3}\begin{pmatrix}
1 \\
2
\end{pmatrix} \cdot \left[ \left( \frac{1}{\sqrt{ 2 }} \right) \begin{pmatrix}
-1 \\
1
\end{pmatrix}\right] = \frac{1}{3\sqrt{ 2 }}
\end{gather*}
$$
From this we can now form an equation for $e$ using the speed of approach and speed of separation:
$$
e = \frac{\frac{2}{\sqrt{ 2 }}-\frac{1}{3\sqrt{ 2 }}}{\frac{2}{\sqrt{ 2 }}+\frac{3}{\sqrt{ 2 }}} = \boxed{\frac{1}{3}}
$$




