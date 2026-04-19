The area of a sector bounded by a polar curve and the half lines $\theta = \alpha$ and $\theta = \beta$, where $\theta$ is in radians is given by:
$$
a = \frac{1}{2}\int_{\alpha}^{\beta} r^{2}d\theta
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
 = a^{2}\left[ \theta + 2\sin\theta -\frac{1}{4}\sin 2\theta +\frac{1}{2}\theta\right]_{0}^{\pi} \\ \\
  = a^{2} \left[ \frac{3}{2}\theta +2\sin\theta -\frac{1}{4}\sin 2\theta\right]_{0}^{\pi} \\ \\
  =a^{2}\left( \frac{3}{2}\pi \ \right) \\ \\
  = \frac{3a^{2}\pi}{2}
\end{gather*}
$$
# Example 2
Find the area of one loop of the curve with equation $r=a\sin 4\theta$

Remember that edexcel only consider the positive loops of $r$. Drawing a graph of $a\sin 4\theta$, we can see that first positive region will be for $0 \leq \theta \leq \frac{\pi}{4}$. 
![[Pasted image 20260303111927.png]]
Therefore we only need to integrate between that region:
$$
\begin{gather*}
\text{area of one loop} = \frac{a^{2}}{2} \int_{0}^{\frac{\pi}{4}} (\sin 4\theta)^{2} d\theta \\ \\
= \frac{a^{2}}{2} \int_{0}^{\frac{\pi}{4}} -\frac{1}{2} \cos 8\theta + \frac{1}{2} d\theta \\ \\ 
= \frac{a^{2}}{2} \left[ -\frac{1}{16}\sin 8\theta +\frac{1}{2}\theta \right]_{0}^{\frac{\pi}{4}} \\ \\
= \frac{a^{2}}{2}\left( \frac{\pi}{8} \right) \\ \\
= \boxed{\frac{a^{2}\pi}{16}}
\end{gather*}
$$

# Example 3
Find the exact area of the region that lies between the curves $r = 2+\cos\theta$ and $r=5\cos\theta$

Firstly sketch out the graphs:
![[Pasted image 20260303112659.png]]

Secondly we need to find the intersections of the graph. We do this by equating the graphs:
$$
\begin{gather*}
2+\cos\theta = 5\cos\theta \\ \
\cos\theta = \frac{1}{2} \\ \\
\theta = \pm \frac{\pi}{3}
\end{gather*}
$$
Since the graph is symmetrical, we can find the area above that axis and double the result. We approach this problem by finding the area for each graph up to the point of intersection:
![[Pasted image 20260303115003.png]]
In this case it is $0$ to $\frac{\pi}{3}$ for $r =2 +\cos\theta$ and $\frac{\pi}{3}$ to $\frac{\pi}{2}$ for $r=5\cos\theta$:
$$
\begin{gather*}
A = 2\left( \frac{1}{2} \int_{0}^{\pi/3} (2+\cos\theta)^{2}+ \frac{1}{2}\int_{\frac{\pi}{3}}^{\pi/2}(5\cos\theta)^{2} \right) \\ \\
= \int_{0}^{\pi/3}(4+4\cos\theta + \cos ^{2}\theta) + 25\int_{\frac{\pi}{3}}^{\pi/2} \cos ^{2}\theta \\ \\
= \left[ 4\theta + 4\sin\theta + \frac{1}{4}\sin 2\theta + \frac{1}{2}\theta \right]_{0}^{\pi/3} + 25\left[ \frac{1}{4}\sin 2\theta + \frac{1}{2}\theta \right]_{\frac{\pi}{3}}^{\pi/2} \\ \\
= \left( \frac{3\pi}{2} + \frac{4\sqrt{ 3 }}{2} +\frac{\sqrt{ 3 }}{8}\right) + \left( \frac{25\pi}{4}\right) - \left( \frac{25\sqrt{ 3 }}{8} + \frac{25\pi}{6} \right) \\ \\
= \frac{43\pi}{12} - \sqrt{ 3 }
\end{gather*} 
$$

