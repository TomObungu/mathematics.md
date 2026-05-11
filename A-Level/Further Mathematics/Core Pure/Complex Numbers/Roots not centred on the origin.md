Consider the equation 
$$
(\beta(z-\alpha))^{n} = w
$$

Solving this equation is essentially the same as finding the standard n-th roots of unity, but with layers of transformation approach. Instead of solving for $z$ directly, treat the entire term as single variable, $U$. 
## Steps 
1. Solve the equation $U^{n}=\omega$ to find the vertices of the regular n-gon centered around the origin
2. Once you have the roots for $U$, you must undo the transformations by dividing $\beta$ and adding $\alpha$. In general you must perform arbitrary operations in order to rearrange for $z$. 

# Formal derivation 

To solve $(\beta(z-\alpha))^{n} = w$, express the complex number $\omega = |\omega|e^{(\phi  + 2k\pi)i}$. 
This is through finding $|(\beta(z-a))| = |w|$ and $arg((\beta(z-a))) = arg(w)$. 

After wards go through the same process of equating coefficients of $z^{n}e^{ni\theta} = |w|e^{arg(w) + 2k\pi}$. You end up getting:
$$
\beta(z-\alpha) = (|w|)^{\frac{1}{h}}e^{\frac{arg(w)+2k\pi}{n}}
$$
Therefore:
$$
z_{1} = \frac{\left( (|w|)^{\frac{1}{h}}e^{\frac{arg(w)+2k\pi}{m}}\right)}{\beta} + \alpha
$$
Where $k=1$. 

The corresponding roots will the be $z_{1}\omega$, $z_{1}\omega^{2}$, $z_{1}\omega^{3}$, ... $z^{n-1}$

## Geo