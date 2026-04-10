![[Pasted image 20260118235911.png]]
https://www.edufax.co.uk/problemsheets/12_diff_eq_1.pdf

(a) This is another first order DE. You need to know that integral of $\tan x$ is $\sec x$.:
Rearrange to get into standard form:
$$
y' + \tan xy = e^{2x}\cos x \\ \\
$$
Find the integrating factor:
$$
f(x) = e^{\int\tan x} = e^{\ln(\sec x)} = \sec x \\ 
$$
Therefore:
$$
\begin{gather*}
\sec x y = \int e^{2x} \\ \\
\sec x y = \frac{1}{2}e^{2x} + c \\ \\
y = \frac{1}{2}\cos xe^{2x} + \cos x c 
\end{gather*}
$$
(b) Using the boundary conditions 