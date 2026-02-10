# Worked Example 1
![[Pasted image 20251024215235.png]]
In general the steps in these problems are:
1. Find parallel component take dot product between it
2. Find the perpendicular component take product
3. Multiply the corresponding component side by $-e$,
4. Multiply the unit vectors by the new components
5. Add them together to form the new 

Always remember that if the vector is parallel to $i$ or $j$, then the new vector is the same vector but multiplied by $e$ in the respective component:

$$
\begin{gather*}
\text{First Collision :} \\
v_{1} = 3i +j \\ \\ 
\text{Second collision :} \\
v_{1\parallel} = \begin{pmatrix}
3 \\
1
\end{pmatrix} \cdot \frac{1}{5}\begin{pmatrix}
3 \\
4
\end{pmatrix} = \frac{13}{5} \\ \\
v_{1\perp} = \begin{pmatrix}
3 \\
1
\end{pmatrix} \cdot \frac{1}{5}\begin{pmatrix}
-4 \\
3
\end{pmatrix} = -\frac{9}{5} \\ \\
v_{2\parallel} = \frac{13}{5} \qquad v_{2\perp} = \frac{1}{2}\left( -\frac{9}{5} \right) =\frac{9}{10} \\ \\
v_{2} = \frac{13}{5}\left( \frac{1}{5}\begin{pmatrix}
3 \\
4
\end{pmatrix} \right) + \frac{9}{10}\left( \frac{1}{5}\begin{pmatrix}
-4 \\
3
\end{pmatrix} \right) = \begin{pmatrix}
\frac{21}{25} \\
\frac{131}{50}
\end{pmatrix} \\ \\
\therefore v_{2} = \left[\frac{21}{25}i+\frac{131}{50}j\right]
\end{gather*}
$$

# Worked Example 1 Continued...
$$
\begin{gather*}
KE_{before} = \frac{1}{2}m(3^{2}+2^{2}) = \frac{13}{2}m \\ \\
KE_{after} = \frac{1}{2}m\left( \left( \frac{21}{25} \right)^{2}+\left( \frac{131}{50} \right)^{2} \right) = \frac{757m}{200} \\ \\ 
\% loss = \frac{\frac{13}{2}-\frac{757}{200}}{\frac{13}{2}} \times 100 \\ \\
=42 \%
\end{gather*}
$$
