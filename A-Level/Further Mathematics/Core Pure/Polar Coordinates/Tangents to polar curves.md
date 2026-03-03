If you are given a curve $r=f(\theta)$ in polar form, you can write as a parametric curve in Cartesian form, using $\theta$ as the parameter.
In this case:
$$
\begin{gather*}
x = r\cos\theta = f(\theta)\cos\theta \\ \\
y = r\sin\theta = f(\theta)\sin\theta
\end{gather*}
$$
By differentiating parametrically, we can find the gradient of the curve at any point and use that to find the tangent equation.:
$$
\frac{dy}{dx} = \frac{\frac{dy}{d\theta}}{\frac{dx}{d\theta}}
$$
To find a tangent parallel to the initial line $\frac{dy}{d\theta}=0$

To find a tangent perpendicular to the initial line $\frac{dx}{d\theta} = 0$.

# Example 12 
Find the coordinates of the points $r=a(1+\cos\theta)$ where the tangents are parallel to the initial line $\theta=0$. 

Finding $\frac{dy}{d\theta}$:
$$
\begin{gather*}
y=r\sin\theta = a(1+\cos\theta)\sin\theta \\ \\
\frac{dy}{d\theta} = a(\cos\theta +\cos 2\theta) = 0 \\ \\
2\cos ^{2}\theta +\cos\theta -1 = 0 \\ \\
(\cos\theta + 1)(2\cos\theta - 1) \\ \\
\cos\theta = \frac{1}{2} \implies \theta = \pm \frac{\pi}{3}
\end{gather*}
$$
Therefore:
$$
\begin{gather*}
r = a\left( 1 +\frac{1}{2} \right) = \frac{3a}{2} \\ \\
\cos\theta = -1 \implies \theta = \pi \implies r = 0 \\ \\

\end{gather*}
$$
So the tangents are at $\left( \frac{3a}{2}, \pm \frac{\pi}{3} \right)$ and $(0,\pi)$


# Proving the curves for $r=(p+q\cos\theta)$

The curve $C$ has equation $r=(p+q\cos\theta)$, where $p$ and $q$ are positive constants and $p > q$. Prove that the curve is convex for $p \geq 2q$, and has a dimple for $p < 2q$.

If the curve is not convex then then there will be more than two tangents to the curve that are perpendicular to the initial line. 

![[Pasted image 20260303200533.png]]

Finding $\frac{dx}{d\theta}$:
$$
\begin{gather*}
x = r\cos\theta = p\cos\theta + q\cos ^{2}\theta \\ \\
\frac{dx}{d\theta} = -q\sin\theta + -2q\cos\theta \sin\theta  \\ \\ 
-\sin\theta(p+2q\cos\theta) = 0 \\ \\
-\sin\theta = 0  \implies 0, \pi \\ \\
\cos\theta = -\frac{p}{2q} \\ \\ 
\end{gather*}
$$
If $p < 2q$, then there will be two solutions to this equation in the second and third quadrants. In this case the curve is not convex and has a dimple. This brings the total solution count 4 solutions meaning there is 4 tangents as expected for a dimple.

If $p=2q$ then the solution is $\theta = \pi$ and so there are only two tangents. In this case the curve is convex. In this case there is only two solutions as $\pi$ is a repeated solution as expected for the convex curve.

If $p > 2q$. Then there is no solution and again leaving the solutions as $0$ and $\pi$. Hence the curve is convex for $p \geq 2q$ and has a dimple for $p < 2q$. 


