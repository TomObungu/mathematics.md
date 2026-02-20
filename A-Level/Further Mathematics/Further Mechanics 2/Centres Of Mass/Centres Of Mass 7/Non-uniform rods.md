We find the centre of mass of non-uniform rods with mass per unit length, $m$.
# Example 1
A 20m non-uniform rod has mass per unit length, $m=(50-2x)$.  Find the distance of the centre of mass from O.

![[Pasted image 20260220072311.png]]


Now the mass element of a uniform rod is just a point mass of $dx$. We must also account for density so we must multiply that point mass $dx$ by the density function $m$. Therefore:
$$
dm = (50-2x)dx
$$
As well as that the x coordinate of each point mass $dx$ is just $x$. 

Therefore applying  this to the formula:
$$
\begin{gather*}
 \bar{x} \int_{0}^{20}dm = \int_{0}^{20}xdm  \\ \\
 \bar{x}\int_{0}^{20} (50-2x)dx = \int_{0}^{20}x(50-2x)dx \\ \\
 \bar{x}\left[50x-x^{2} \right]_{0}^{20} = \left[25x^{2}-\frac{2}{3}x^{3}\right]_{0}^{20} \\ \\
 600\bar{x} = \frac{14000}{3} \\ \\
 \bar{x} = \frac{70}{9} = 7.78m \text{From O}
\end{gather*}
$$
