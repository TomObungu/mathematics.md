The area of a sector bounded by a poalr curve and the half lines $\theta = \alpha$ and $\theta = \beta$, where $\theta$ is in radians is given by:
$$
a = \frac{1}{2}\int_{\alpha}^{B} r^{2}d\theta
$$
![[Pasted image 20260303110110.png]]

This is because you are integrating with respect to sectors of infinitesimal arc length $d\theta$ as opposed to little rectangles of width $d\theta$. 

# Example 1
Find the area enclosed by the cardioid with equation $r=a(1+\cos\theta)$:

Start by sketching the curve and inspecting for symmetry to simplify. The curve is symmetric along the horizontal axis, so you can find the area in that half and double the result to get it. 

You need to find starting and ending angles for the first half. Conveniently, this is just from $\theta = 0$ to $\theta =\pi$.
![[Pasted image 20260303110418.png]]
$$
\begin{gather*}
\text{Area} = \frac{2a^{2}}{2} \int_{0}^{\pi} (a(1+\cos\theta))^{2}d\theta \\ \\
 = a^{2} \int_{0}^{\pi}(1+2\cos\theta+\cos ^{2}\theta)d\theta \\ \\
 = a^{2}\int_{0}^{\pi}\left( 1 +2\cos\theta + \frac{1}{2}\cos 2\theta  + \frac{1}{2}\right) \\ \\
 = a^{2}\left[ \theta + 2\cos\theta -\frac{1}{4}\sin 2\theta +\frac{1}{2}\theta\right]_{0}^{\pi} \\ \\
  = a^{2} \left[ \frac{3}{2}\theta +2\cos\theta -\frac{1}{4}\sin 2\theta\right]_{0}^{\pi} \\ \\
  =a^{2}\left( \frac{3}{2}\pi -2\ \right)
\end{gather*}
$$


