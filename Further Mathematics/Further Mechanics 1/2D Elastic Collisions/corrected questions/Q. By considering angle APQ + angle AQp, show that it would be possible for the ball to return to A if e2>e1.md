![[Pasted image 20251025095958.png]]
(a) Firstly, draw out the diagram with each parallel and perpendicular component correctly labelled for each vector:
![[Pasted image 20251025164247.png]](a) Form equations from the diagram:
$$
\begin{gather*}
V\cos\beta = U \cos\alpha \ (1) \\ 
V\sin\beta = e_{1}U\sin\alpha \ (2)\ \ \\
\frac{(2)}{(1)} \implies \frac{V\sin\beta}{V\cos\beta} = \tan\beta = \frac{e_{1}Usin\alpha}{U\sin\alpha} = \ \therefore e_{1}\tan\alpha  \\ \\
QED
\end{gather*}
$$
(b) Form the equations for $\gamma$ in from the diagram:
$$
\begin{gather*}
W\cos\gamma=V\sin\beta \ (3) \\
W\sin\gamma = e_{2}V\cos\beta \ (4 )\\ \\ 
\frac{(3)}{(4)} \implies \frac{W\cos\gamma}{W\sin\gamma} =\cot\gamma = \frac{V\sin\beta}{e_{2}V\cos\beta} \\ 
=\frac{e_{1}U\sin\alpha}{e_{2}U\cos\alpha} = \frac{e_{1}}{e_{2}}\tan\alpha \\ \\
\therefore e_{2}\cot\gamma = e_{1}\tan\alpha \\
QED
\end{gather*}
$$
(c) Now for this question, you must look at what the question is asking. If $e_{2} > e_{1}$ and $e_{2}$ is found in $e_{2}\cot\gamma$  and $e_{1}$ is found in $e_{1}\tan\alpha$ then these two statements will be involved in the calculation and in in an inequality. 

However, firstly the question asks us to compute angle $APQ$ and angle $AQP$. Let's work it out:
APQ is $180 - \alpha -\beta$ as it lies on a straight line:
$$
APQ = 180 - \alpha - \beta
$$
To work out AQP let's look at angle PQC which we will call $\varepsilon$ :
![[Pasted image 20251025164649.png]]
$$
\begin{gather*}
\varepsilon= 180 - 90 - \beta \\= 90 - \beta
\end{gather*}
$$
Therefore $AQP$ is:
$$
\begin{gather*}
AQP =180 - \varepsilon - \gamma =180 - (90 -\beta) - \gamma \\
\therefore AQP = 90 +\beta - \gamma
\end{gather*}
$$
If we compute $AQP + APQ :$
$$
\begin{gather*}
(90+\beta-\gamma) + (180 - \alpha -\beta) \\ 
 = \boxed{270 -\alpha-\gamma}
\end{gather*}
$$

Now in order for the particle to return to A, all the angles within traingle $APQ$ would need to add up to $180$. Therefore in order for the triangle to exist, $AQP+APQ < 180$. Therefore:
$$
\begin{gather*}
270 - \alpha - \gamma < 180 \\ 
-\alpha-\gamma < -90 \\ \\
\alpha + \gamma > 90
\end{gather*}
$$
Now we have an inquality for $\alpha$ and $\gamma$, we just need work out $$
