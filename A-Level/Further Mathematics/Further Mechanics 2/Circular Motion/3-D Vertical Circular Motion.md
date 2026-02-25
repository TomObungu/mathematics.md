Consider a particle moving in a vertical circular orbit of radius $r$,around a point $O$, with velocity $v$.
 ![[Pasted image 20260225190852.png]]
If we represent the the position of the particle in $i$ and $j$ vector notation, we can see that the function for the radius at time $t$ is defined by:
$$
r(t) = (r\cos\theta)i + (r\sin\theta)j
$$
From, the definition of velocity, the velocity of the particle is the derivative of $r(t)$ with respect to time. We can differentiate $r(t)$ implicitly:
$$
v(t) =  \dot{r}(t) = (-r\dot{\theta}\sin\theta )i + (r \dot{\theta}\cos\theta)j
$$
If we take the dot product between $v$ and $r$, $v \cdot r$:
$$
v \cdot r = -r^{2}\dot{\theta}\sin\theta \cos\theta + r^{2}\dot{\theta}\sin\theta \cos\theta =0
$$
We can see that their dot product is zero. This confirms that the velocity and radial vector and perpendicular as expected. 

If we want to find the acceleration of the particle, we must implicitly differentiate again:
$$
a(t) = \dot{v}(t) = \left[-r \dot{\theta}^{2}\cos\theta-r \ddot{\theta}\sin\theta \right]i + \left[-r\dot{\theta}^{2}\sin\theta+r \ddot{\theta}\cos \theta  \right]j
$$
If we factorise and group in terms of $\dot{\theta}$ and $\ddot{\theta}$, we get an expression for $a(t)$:
$$
a(t) = -\underbrace{ \left[r\cos\theta i+r\sin\theta j\right]  }_{ r }\dot{\theta}^{2} + \left[-r\cos\theta i+r\sin\theta j\right]\ddot{\theta}
$$
We can see from the above expression, we can simplify the expression to have an $r$ term:
$$
\begin{gather*}
a(t) = \underbrace{ -r \dot{\theta}^{2}\hat{r}  }_{ a_{1} } + \underbrace{ \left[-r\sin\theta i+r\cos\theta j\right] \ddot{\theta} }_{ a_{2} }
\end{gather*}
$$
Remember that $\vec{r}$ can be written as:
$$
\vec{r} = r\hat{r}
$$
Where $r$ is the magnitude of the vector.

Labelling the components of acceleration $a_{1}$ and $a_{2}$, we can examine each component.

For $a_{1}$, it is negative and is it is in the unit vector of $r$. This means it acts in the same radial direction towards the centre of the circle. 

If it acts towards the centre of the circle, it is the centripetal acceleration component. 

For $a_{2}$, if take the dot product between $a_{2}$ and $r$, we can see that:
$$
a_{2} \cdot r = 0
$$
Therefore $a_{2}$ is perpendicular to $r$ and is the tangential motion and can be expressed as:
$$
a_{2} = r \ddot{\theta}\hat{v}
$$

Therefore, as a whole, acceleration for vertical circular motion is both radial and tangential
$$
a = -r\dot{\theta}^{2}\hat{r} + r  \ddot{\theta}\hat{v}
$$

**This means that acceleration is not uniform for vertical circular motion**

## Instantaneous rest
For vertical circular motion, if the particle is instantaneously at rest, the component of $\dot{\theta} = \omega$ is 0. Therefore is no radial acceleration:
$$
\therefore r  \dot{\theta}^{2}\hat{r} = 0
$$
