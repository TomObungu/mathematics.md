We know that centre of mass of a sphere as its centre. The gravitational force between an object and the Earth, we have to consider $r$, which is the distance from the centre of the Earth to that object. 

Consider the gravitational force, $F$, experienced by mass $m_{1}$, at distance, $x$, from the Earth's centre, where $M$ is the mass of Earth. The force is given by Newton's law of gravitation equation. 
$$
F = \frac{GMm}{x^{2}} \ \ (1)
$$
Where $G$ is the gravitational constant and has an approximate value of $6.7 \times 10^{-11}$

Now we know that at the surface of the Earth, i.e. when $x=R$, where $R$ is the radius of the Earth, $F=mg$. Therefore:
$$
\begin{gather*}
\frac{GMm}{R^{2}} = mg \\ \\
GM = gR^{2} \ \ (2)
\end{gather*}
$$
Substituting $(2)$ into $(1)$ gives:
$$
F = \frac{mgR^{2}}{x^{2}}
$$
This the force acting on $m$ at a distance $x$ from the Earth's centre, the force itself also works towards the centre. 

Exam questions often ask to show this relationship.

## Example 1
Given that the magnitude of the force on a particle due to the Earth's gravitational field is inversely proportional to the square of its distance from the centre of the Earth and that the acceleration due to gravity at the surface is $g$, show that $F=\frac{mgR^{2}}{x^{2}}$.

First, form equations from the statement of the inverse square relationship:
$$
F \propto \frac{1}{x^{2}}  \implies F =\frac{k}{x^{2}}
$$
Secondly, as the statement states that we are at the surface of the Earth, we must take $x$ to be $R$, where $R$ is the radius of the Earth. Equate this force to the weight $mg$ and solve for $k$:
$$
\begin{gather*}
F = \frac{k}{R^{2}} = mg \\ \\
k = mgR^{2} \\ \\
\text{Thus:} \ \ F = \frac{mgR^{2}}{x^{2}}
\end{gather*} 
$$
# Solving dynamic problems 
As an object moves towards or away from the Earth, the force acting on it varies with displacement. Hence, we can use dynamic techniques from [[Further Dyanmics]]


## Example 2
A rocket is fired from the surface of the Earth vertically upwards. When it is at a height $2R$, alone from the surface of the Earth, its speed is $\frac{1}{2}\sqrt{ gR }$. Assuming that air resistance can be ignored and that the rokcet engine is switched off as it fired, find the speed with which it was fired, $U$.

The question states that the rocket is fired from the surface of the Earth. Thus we can use $F=\frac{mgR^{2}}{x^{2}}$. With this, form an equation for resultant force using $F=ma$ and $a$ in terms of $\frac{vdv}{dx}$ or $\frac{dv}{dt}$ based on the question. Remember that gravitational force is always attractive, thus the force is negative.
$$
\begin{gather*}
F = ma \\ \\ 
mv\frac{dv}{dx} = -\frac{mgR^{2}}{x^{2}} \\ \\
\int vdv = -gR^{2}\int \frac{1}{x^{2}} \\ \\
\frac{1}{2}v^{2} = \frac{gR^{2}}{x} + c
\end{gather*}
$$
Now reading the question, we can show that the limits of the integrals are $U$ to $\frac{1}{2}\sqrt{ gR }$ for velocity and $R$ to to $3R$for displacement. This is because the rocket is released from the surface of the Earth in which the displacement is already $R$. 
$$
\begin{gather*}
\left[  \frac{1}{2}v^{2} \right]_{0}^{\frac{1}{2}\sqrt{ gR }} = \left[ \frac{gR^{2}}{x} \right]_{R}^{3R} \\ \\
\frac{gR}{8}- \frac{1}{2}U^{2} = gR^{2}\left[ \frac{1}{3R} - \frac{1}{R} \right] \\ \\
\frac{gR}{8} - \frac{1}{2}U^{2} = -\frac{2gR}{3} 
\end{gather*}
$$
Thus U can be rearranged to be found:
$$
U = \sqrt{ \frac{19gR}{12} }
$$
## Example 3

A particle $P$, mass $m$, is fired vertically upwards from the surface of the Earth. When $P$ is at a height of $\frac{R}{3}$ above the surface of the Earth, it moving from the Earth with speed $\sqrt{ \frac{2gR}{5} }$. 

Find, in terms of $R$ the greatest height revealed by $P$ above the Earth's surface. 

For this problem we must find $v(x)$ and now that $v(x) = 0$, when $x$ is at a maximum. $v(x)$ can be found using further Dynamics again with $a$ as $\frac{vdv}{dx}$:
$$
\begin{gather*}
F = ma \\ \\
mv \frac{dv}{dx} = -\frac{mgR^{2}}{x^{2} } 
\end{gather*}
$$
For this question we are performing indefinite integration as we are not given the original lift off speed i.e we are only given $3$ limits. 

$$
\begin{gather*}
\int vdv = -gR^{2}\int \frac{1}{x^{2}}dx \\ \\
\frac{1}{2}v^{2} = \frac{gR^{2}}{x }+c \\ \\
\end{gather*}
$$
Instead we must use the constraints given in the question as boundary conditions to find $c$:
$$
\begin{gather*}
v\left( \frac{4}{3}R \right) = \sqrt{ \frac{2gR}{5} } \\ \\
\frac{1}{2}\left( \sqrt{ \frac{2gR}{5} } \right)^{2} = \frac{gR^{2}}{\frac{4}{3}R} + c  \\ \\
c = -\frac{11}{20}gR \\ \\ 
\end{gather*}
$$
Therefore:
$$
\begin{gather*}
\frac{1}{2}v^{2} = \frac{gR^{2}}{x} -\frac{11}{20}gR
\end{gather*}
$$
Since $v=0$, when $x$ is at a maximum:
$$
\begin{gather*}
0 = \frac{gR^{2}}{x} - \frac{11}{20}gR \\ \\
\frac{gR^{2}}{x} = \frac{11}{20}gR \\ \\
x = \frac{20R}{11}
\end{gather*}
$$
Thus the total height above the surface of the earth is $x-R$:
$$
\text{Height above the surface} = \frac{20R}{11} -1 = \frac{9}{11}R
$$
