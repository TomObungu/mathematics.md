Consider the equation 
$$
(\beta(z-\alpha))^{n} = w
$$

Solving this equation is essentially the same as finding the standard $n$-th roots of unity, but with layers of transformation approach. Instead of solving for $z$ directly, treat the entire term as single variable, $U = (\beta(z-\alpha))$. 
## Steps 
1. Solve the equation $U^{n}=\omega$ to find the vertices of the regular $n$-gon centered around the origin.
2. Once you have the roots for $U$, you must undo the transformations by dividing $\beta$ and adding $\alpha$. In general you must perform arbitrary operations in order to rearrange for $z$. 

# Formal derivation 

To solve $U^{n} = w$, express the complex number $\omega = |\omega|e^{(\phi  + 2k\pi)i}$. 
This is through finding  $|w|$ and $arg(w)$. 

After wards go through the same process of equating coefficients of $U ^{n} =z^{n}e^{ni\theta} = |w|e^{arg(w) + 2k\pi}$. You end up getting:
$$
U = (|w|)^{\frac{1}{n}}e^{\frac{arg(w)+2k\pi}{n}}
$$
Substituting $\beta(z-\alpha)$ for $U$ gives:
$$
\beta(z-\alpha) = (|w|)^{\frac{1}{n}}e^{\frac{arg(w)+2k\pi}{n}}
$$
Therefore:
$$
z_{1} = \frac{\left( (|w|)^{\frac{1}{h}}e^{\frac{arg(w)+2k\pi}{m}}\right)}{\beta} + \alpha
$$
While any consecutive value of $k$ work (e.g., $k = 0, 1, \dots, n -1$), exam boards usually require the argument to be in the range $(-\pi, \pi]$.  

To ensure the first root lands within or near this range immediately, set $k$ to $\left\lfloor  \frac{n}{2}  \right\rfloor$. 

Alternatively, set $k = 0$, or $k=1$, to find a "base" root and then use the roots of unity to find the rest. 

Once the first root $z_{1}$ is found, you do not need re-calculate the entire formula for every $k$. 

The corresponding roots will then be $z_{1}\omega$, $z_{1}\omega^{2}$, $z_{1}\omega^{3}$, ... $z^{n-1}$

## Geometric Interpretation
These roots will form a regular $n$-gon centered around $\alpha$. 