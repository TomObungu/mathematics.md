![[Pasted image 20251024225100.png]]
(a) In this question you must consider the restitution only in the perpendicular component. Firstly draw a diagram:
![[Pasted image 20251025102445.png]]
Write the out angle equations:
$$
\begin{gather*}
v\sin\alpha = u\cos\alpha \\
v\cos\alpha = u\sin\alpha \\

\end{gather*}

$$
Secondly, consider the impulse only in the vertical component. Notice that vertical component before will be negative as it is travelling downwards in the opposite direction and we take down to be negative and that question does not introduce the coefficient of restitution into the question yet.
$$
\begin{gather*}
I = m(v\sin\alpha--u\cos\alpha) \\ 
= m(v\sin\alpha+u\cos\alpha)
\end{gather*}
$$
Rewrite $v$ in terms of $u$:
$$
\begin{gather*}
v = u\tan\alpha
\end{gather*}
$$
Substitute back into the impulse equation:
$$
\begin{gather*}
I = m\left( \frac{u\sin\alpha}{\cos\alpha}\sin\alpha+ u\cos\alpha \right) \\ 
= m\left( \frac{u\sin ^{2}\alpha}{\cos\alpha} +u\cos\alpha\right) \\ 
= m\left( \frac{u\sin ^{2}\alpha+u\cos ^{2}\alpha}{\cos ^{2}\alpha} \right) \\
= mu\left( \frac{1}{\cos ^{2}\alpha} \right) \\ \\
= \boxed{mu\sec ^{2}\alpha} \\ 
QED
\end{gather*}
$$
(b) In this question you must find $v$ by squaring the $\sin$ and $\cos$ of the v components and using $e$ for the perpendicular $\sin$ component:
$$
\begin{gather*}
v\sin\alpha = -eu\cos\alpha \\
v\cos\alpha = u\sin\alpha \\ \\
v^{2} = (v\sin\alpha)^{2} + (u\sin\alpha)^{2} \\ 
v^{2} = (-eu\cos\alpha)^{2} + (u\sin\alpha)^{2} \\
v^{2} = u^{2}e^{2}\cos ^{2}\alpha + u^{2}\sin ^{2}\alpha \\ \\
\therefore \boxed{v^{2} = u^{2}(\sin ^{2}\alpha+e^{2}\cos ^{2}\alpha)} \\
QED
\end{gather*}
$$
(c) In this question as you now you have $v^{2}$ and $u^{2}$, substitute them back into the $\frac{1}{2}mv^{2}$ and do starting $KE$ minus ending $KE$
$$
\begin{gather*}
\frac{1}{2}m(u^{2}) - \frac{1}{2}m(v^{2}) \\ \\
 =\frac{1}{2}m(u^{2}) - \frac{1}{2}m(u^{2}(\sin ^{2}\alpha+e^{2}\cos ^{2}\alpha)) \\ 
= \frac{1}{2}mu^{2}(1-\sin ^{2}\alpha-e\cos ^{2}\alpha) \\ 
 =\frac{1}{2}mu^{2}(\cos ^{2}\alpha -e\cos ^{2}\alpha) \\ 
 = \boxed{\frac{1}{2}mu^{2}(1-e^{2})\cos ^{2}\alpha} \\
 QED
\end{gather*}
$$
(d) In these types of question, the main approach is to try and find the missing component in terms of $e$. This is done by finding a suitable identity. In this case as it's $\cos ^{2}\alpha$, then the identity we're trying to find is $\tan ^{2}\alpha +1 = \sec ^{2}\alpha$ in terms of $e$. In other cases if it was $\sin ^{2}\alpha$, we would want $\cot ^{2}\alpha+1=\csc ^{2}\alpha$:
$$
\begin{gather*}
v\sin\alpha = eu\cos\alpha \\ 
v\cos\alpha = u\sin\alpha \\ \\
\tan\alpha = e\cot\alpha \\ 
\tan ^{2}\alpha = e^{2}\cot ^{2}\alpha \\
\tan ^{4}\alpha = e^{2} \\ 
\therefore \tan ^{2}\alpha = e \\ \\
\end{gather*}
$$
In this part we need manipulate $e$ as if it were a substitution:
$$
\begin{gather*}
e = \tan ^{2}\alpha \\ 
1+e = \tan ^{2}\alpha + 1 \\
1+e = \sec ^{2}\alpha \\
1+e = \frac{1}{\cos ^{2}\alpha} \\ \\
\therefore \frac{1}{1+e} = \cos ^{2}\alpha
\end{gather*}
$$
We now have what we want in terms of $e$ only. Therefore we can now substitute it back into the previous equation:
$$
\begin{gather*}
\frac{1}{2}mu^{2}(1-e^{2})\left( \frac{1}{1+e} \right) \\
= \frac{1}{2}m u^{2}(1+e)(1-e)\left( \frac{1}{1+e} \right) \\ \\
=\boxed{\frac{1}{2}mu^{2}(1-e)}
\end{gather*}
$$
