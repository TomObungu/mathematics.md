Consider $z\in \mathbb{C},|z|=r,arg(z)=0$.  
![[Pasted image 20251118095401.png]]
We know that the coordinate $z$ can composed from the horizontal and vertical components $r\cos\theta$ and $ri\sin\theta$. Therefore:
modulus argument form is written as:
$$
z = r(\cos\theta +i\sin\theta)
$$
# Worked Example 1 
Write $z=1-\sqrt{ 3 }i$ in modulus argument form:
![[Pasted image 20251118095641.png]]
To calculate $\theta=\arctan\left( \frac{\sqrt{ 3 }}{1} \right) = \frac{\pi}{3}$ . From that we knw that $arg(z)=-\frac{\pi}{3}$. As well as that $|z|=\sqrt{ \sqrt{  3}^{2}+=1^{2} } = 2$. Therefore in modulus argument form:
$$
z = 2\left( \cos\left( -\frac{\pi}{3} \right)+i\sin\left( -\frac{\pi}{3} \right) \right)
$$
# Useful rules
## Addition and subtraction
Consider two complex numebrs, $z_{1}$ and $z_{2}$

It is possible to prove that:
$$|z_{1}z_{2}| = |z_{1}||z_{2}|$$
and:
$$
arg(z_{1}z_{2}) = arg(z_{1}) + arg(z_{2})
$$
The same can be applied for subtraction and division:
$$
\left|\frac{z_{1}}{z_{2}}\right| = \frac{|z_{1}|}{|z_{2}|}
$$
and:
$$
arg\left( \frac{z_{1}}{z_{2}} \right) = arg(z_{1}) -  arg(z_{2})
$$
# Powers
it is possible to prove by induction that:
$$
|z^{n}| = |z|^{n}
$$
and:
$$
arg(z^{n}) = narg(z)
$$
For, $n\in \mathbb{Z}$. This works for negative powers too:
$$
|z^{-n}| = |z|^{-n}
$$
$$
\begin{gather*}
arg(z^{-n})=arg(1)-arg(z^{n})  \\
= 0 - narg(z) \\ \\
\boxed{\therefore arg(z^{-n}) = -narg(z)}
\end{gather*}
$$

Now consider $z\in \mathbb{C}$, $|z|=r$, $arg(z)=\theta$. Consider when raising to a power, what that does to $\theta$:
![[Pasted image 20251118101653.png]]
Each time we multiply by $z$, the angle $\theta$ is increase by the number of times we multiply by $\theta$ each time. So in this case $arg(z^{2})=2\theta$ and $arg(z^{3})=3\theta$ and so on.

It will get to a point that if the number is fractional multiple of $\pi$ e.g. $\frac{\pi}{6}$, Raising $z^{6}$ will yield $\pi$ and the number will be on the part of the Argand diagram only - $z^{6} \in \mathbb{R}$: 
![[Pasted image 20251118102326.png]]

# Worked Example 2
Given that $z_{1}=\sqrt{ 3 }+i$, $|z_{1}z_{2}|=24$, $arg(z_{1}z_{2})=\frac{\pi}{3}$ 
find $z_{2}$ in the form $x+iy$:
$$
\begin{gather*}
|z_{1}|=2, \ arg(z_{1}) = \frac{\pi}{6} \\ \\
|z_{1}||z_{2}| = 24 \\ 
2|z_{2}| = 24 \\ 
|z_{2}| = 12 \\ \\
arg(z_{1}) +arg(z_{2}) = \frac{\pi}{3} \\ \\
\frac{\pi}{6} +arg(z_{2}) = \frac{\pi}{3} \\
arg(z_{2}) =\frac{\pi}{6} \\ \\
z_{2} = 12\left( \cos \frac{\pi}{6} + i\sin \frac{\pi}{6} \right) = 6\sqrt{ 3 } + 6i
\end{gather*}
$$
# Worked Example 2
$$
z=1+\sqrt{ 3 }i
$$
Given that $z^{n}\in \mathbb{R}$, $n\in \mathbb{Z}^{+}$ determine the smallest value of n. Now for this question you must consider the Argand diagram. What value of $n$ must you raise to make the value $\theta$ an integer multiple of $\pi$?:
![[Pasted image 20251118102535.png]]
In this case the smallest number we can multiple to make $\frac{\pi}{3}$ a integer multiple of $\pi$ is $3$:
$$
\begin{gather*}
arg(z) = arctran\sqrt{ 3 }) = \frac{\pi}{3} \\ 
arg(z^{n}) = narg(z) = \pi \\ \\
\frac{\pi}{3}n = \pi \\ \\
\therefore n=3
\end{gather*}
$$


