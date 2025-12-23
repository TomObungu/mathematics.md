The volume of revolution formed when $x=f(y)$ is rotated through $2\pi$ radians about the y-axis between $y=a$ and $y=b$ given by volume:
$$
\pi \int_{a}^{b}x^{2}dy
$$
In problem like this, the difference is that you must
- Rearrange to get in terms of $y$, then integrate the square of that function
- If given any bounds of x, convert them into bounds of $y$

![[Pasted image 20251223151133.png]]
$$
\begin{gather*}
y = 4\ln x -1 \\ \\
e^{\frac{y+1}{4}} = x \\ \\ 
x^{2} =e^{\frac{y + 1}{2}} \\ \\
x^{2} =  e^{\frac{y}{2}}e^{\frac{1}{2}} \\ \\ \\
V = \pi \int_{0}^{4} e^{\frac{y}{2}}e^{\frac{1}{2}} =  \pi e^{\frac{1}{2}} \int_{0}^{4} e^{\frac{y}{2}} \\ \\
 = 2\pi e^{\frac{1}{2}}\left[ e^{\frac{y}{2}} \right]_{0}^{4} \\ \\
 = 2\pi e^{\frac{1}{2}}(e^{2}-e^{0}) \\ \\
 = 2\pi \sqrt{ e }(e^{2}-1)
\end{gather*}
$$
