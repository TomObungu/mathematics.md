We can solve dynamic problems with variable forces by forming an equation of motion and then rearranging to form a differential equation, like with kinematics. Again we need to choose an appropriate form for acceleration depending on what variables we are working with. 

When dealing with resistive forces, they will negative. 

# Example 1
A 2kg particle moves along the positive $x$ axis in the direction of $x$ increasing. It has velocity, $vms^{-1}$ at times $t$s when its displacement is $x$ m from the origin $O$. It experiences a resistive force of magnitude $3v^{2}$N. 

Find the distance, $D$, the particle travels its velocity decreases from $10ms ^{-1}$ to $8ms ^{-1}$. 

Forming a resultant force equation in form $F=ma$. The resultant force is the resistive force. The mass is 2kg. We are dealing velocity and displacement so acceleration is expressed as $v \frac{dv}{dx}$.:
$$
\begin{gather*}
2v \frac{dv}{dx} = -3v^{2} \\ \\
\end{gather*}
$$
The limits for velocity are $8ms ^{-1}$ to $10ms ^{-1}$ and displacement, $0$ to $D$:
$$
\begin{gather*}
-\frac{2}{3}\int_{10}^{8} \frac{dv}{v} = \int_{0}^{D}dx  \\ \\
\frac{2}{3}[\ln v] = D \\ \\
D = \frac{2}{3}[\ln 10 - \ln 8] = \frac{2}{3}\ln\left( \frac{5}{4} \right)
\end{gather*}
$$

## Example 1 Continued...
Calculate the time taken for the speed to decrease from $10ms ^{-1}$ to $8ms ^{-1}$. 

For this, since the question asks for time, form a resultant force equation with acceleration as $\frac{dv}{dt}$:
$$
\begin{gather*}
2 \frac{dv}{dt} = -3v^{2} \\ \\
=\frac{2}{3}\int_{10}^{8} \frac{dv}{v^{2}} = \int_{0}^{T}dt \\ \\
\frac{2}{3}\left[ \frac{1}{v} \right]_{10}^{8} = T \\ \\
T = \frac{2}{3}\left[  \frac{1}{8} - \frac{1}{19} \right] = \frac{1}{60}
\end{gather*}
$$

# Example 2
At time $t=0$, a $5kg$ ball is released from rest from $O$. It experiences a resistive force of $2v$N.  

Show that $v(t)$
