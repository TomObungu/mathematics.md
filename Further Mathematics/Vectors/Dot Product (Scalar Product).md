Consider two vectors $\vec{a}$ and $\vec{b}$. The angle $\theta$ between them can be calculated by working out $|b|,|a|$ and $|a-b|$. 

Applying the cosine rule gives us:
$$
\begin{gather*}
\|a-b\|^2 = \|a\|^2 + \|b\|^2 - 2\|a\|\|b\|\cos\theta \\[6pt]
(a_x-b_x)^2+(a_y-b_y)^2+(a_z-b_z)^2 = a_x^2+a_y^2+a_z^2+b_x^2+b_y^2+b_z^2-2\|a\|\|b\|\cos\theta \\[6pt]
a_x^2-2a_xb_x+b_x^2 + a_y^2-2a_yb_y+b_y^2 + a_z^2-2a_zb_z+b_z^2 = \|a\|^2+\|b\|^2-2\|a\|\|b\|\cos\theta \\[6pt]
a_x b_x + a_y b_y + a_z b_z = \lvert \mathbf{a}\rvert \lvert \mathbf{b}\rvert \cos\Theta
\end{gather*}
$$
The LHS of the equation is expressed as $a\cdot b$. Therefore:
$$
a\cdot b=\lvert \mathbf{a}\rvert \lvert \mathbf{b}\rvert \cos\Theta
$$
The angle between two vectors can be calculated by:
$$
\cos\theta=\frac{a\cdot b}{\lvert \mathbf{a}\rvert \lvert \mathbf{b}\rvert }
$$
