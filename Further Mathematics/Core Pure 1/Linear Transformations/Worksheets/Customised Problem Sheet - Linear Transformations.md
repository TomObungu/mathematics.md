1. a) Let $M = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$ be a matrix such that $M^2 = I$. Show that if $a+d \neq 2$, then $(M-I)$ is non-singular.

b) For the specific case $M = \begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}$, write down $M^2$, $M^3$, and $M^4$, and state the general form of $M^n$.

The transformation $T$ is defined by the matrix $(M-I)^{-1}(M^n - I)$.

c) Prove that $T$ has a line of invariant points if and only if $n$ is even.

d) Hence, demonstrate that the line $y = -x$ is invariant under $T$ for all even $n$.

***

2.  A conic section $S$ is defined by the equation
$$
3x^2 + 10xy + 8y^2 = 12
$$

A linear transformation $T$ is represented by the matrix $A$, where
$$
A = \begin{pmatrix} 2 & b \\ -b & 1 \end{pmatrix}, \quad b \in \mathbb{R}
$$

Determine the value of the real constant $b$ for which the image of the conic $S$ under transformation $T$ is a circle centered at the origin.

**Hint:** You may find it useful to denote $\det(A)$ as $\delta$ to simplify your algebraic working.

(7 marks)

---

3.A forestry agency is monitoring the growth of a tree plantation.

In the model, the trees are classified into 3 stages of growth:

| $S$ (Saplings) | 0 to less than 1 year old |
|---|---|
| $Y$ (Young Trees) | 1 to 3 years old |
| $M$ (Mature Trees) | over 3 years old |

(a) State one limitation of this model regarding the classification of trees into these categories.

A model for the plantation's population is given by the matrix equation

$\begin{pmatrix} S_{n+1} \\ Y_{n+1} \\ M_{n+1} \end{pmatrix} = \begin{pmatrix} 0 & 0 & k \\ p & q & 0 \\ 0 & 0.35 & 0.88 \end{pmatrix} \begin{pmatrix} S_n \\ Y_n \\ M_n \end{pmatrix}$

where $p$ and $q$ are constants, $k$ is the annual seed production rate per mature tree, and $S_n$, $Y_n$, and $M_n$ are the numbers of trees in each category $n$ years after monitoring began.

At the start of monitoring, the plantation contains only mature trees, with no saplings or young trees.

According to the model, after 2 years the number of saplings is 264 and the number of young trees is 154.

(b) (i) Determine the number of mature trees in the plantation at the start of monitoring.

(ii) Show that $p = 0.7$

(c) Determine, in terms of $q$,

$\begin{pmatrix} 0 & 0 & 4 \\ 0.7 & q & 0 \\ 0 & 0.35 & 0.88 \end{pmatrix}^{-1}$

Given that the model predicts approximately 2250 trees in total at the start of a particular year, and approximately 892 saplings, 718 young trees, and 640 mature trees at the start of the next year,

(d) determine the value of $q$, giving your answer to 2 decimal places.

It is decided to track the survival rate of planted saplings separately from naturally seeded saplings. Assuming that 38% of new saplings result from natural seeding,

(e) refine the matrix equation for the model to reflect this information, giving a reason for your answer.

*(There is no need to estimate any unknown values for the refined model, but any known values should be made clear.)*

***
4. The population of a rare bird species in a nature reserve consists of fledglings and adults. Fledgling birds do not reproduce.

In a conservation study, the numbers of fledgling and adult birds were counted at the beginning of each breeding season. A model for the population satisfies the matrix system

$\begin{pmatrix}F_{n+1}\\ A_{n+1}\end{pmatrix}=\begin{pmatrix}b&0.22\\ 0.12&0.78\end{pmatrix}\begin{pmatrix}F_{n}\\ A_{n}\end{pmatrix}\qquad n=0,1,2,\ldots$

where $b$ is a constant, and $F_{n}$ and $A_{n}$ are the respective numbers of fledgling and adult birds $n$ years after the start of the study.

(a) Interpret the meaning of the constant $b$ in the context of the model. (1)

At the start of the study, the total number of birds in the reserve was estimated to be 8,500

According to the model, after one year the number of fledgling birds is 2,380 and the number of adult birds is 5,814

(b) (i) Find, in terms of $b$

$\begin{pmatrix}b&0.22\\ 0.12&0.78\end{pmatrix}^{-1}$

(ii) Hence, or otherwise, find the value of $b$. (3)

(iii) Calculate the change in the number of fledgling birds in the first year of the study, according to this model. (3)

Given that the number of fledgling birds is known to be decreasing in the reserve,

(c) comment on the short-term suitability of this model. (1)

Research on this bird species revealed that adult birds stop reproducing after 12 years of age.

(d) Refine the matrix system for the model to reflect this information, giving a reason for your answer.

***

### Mark Scheme

**1.**
- **a) Answer:** For $M^2=I$, $(M-I)(M+I)=0$. If $a+d\neq2$, then $M\neq I$, ensuring non-singularity.
- **b) Answer:** $M^2=I$, $M^3=M$, $M^4=I$, so $M^n=I$ if $n$ even, $M^n=M$ if $n$ odd.
- **c) Answer:** When $n$ even, $M^n=I$, creating a line of invariant points.
- **d) Answer:** For even $n$, the transformation becomes zero, making all points invariant, including those on $y=-x$.

**2.**
- **Answer:** $b = \pm 2$
- **Explanation:**
    1.  Let a point on the original conic be $\begin{pmatrix} x \\ y \end{pmatrix}$ and its image under $T$ be $\begin{pmatrix} X \\ Y \end{pmatrix} = A \begin{pmatrix} x \\ y \end{pmatrix}$.
    2.  Since $A$ is invertible for the transformation to be valid, we have $\begin{pmatrix} x \\ y \end{pmatrix} = A^{-1} \begin{pmatrix} X \\ Y \end{pmatrix}$.
    3.  The inverse matrix is $A^{-1} = \frac{1}{\delta} \begin{pmatrix} 1 & -b \\ b & 2 \end{pmatrix}$, where $\delta = \det(A) = 2 + b^2$.
    4.  Substituting $x = \frac{1}{\delta}(X - bY)$ and $y = \frac{1}{\delta}(bX + 2Y)$ into the original equation $3x^2 + 10xy + 8y^2 = 12$ yields the equation of the transformed conic in terms of $X$ and $Y$.
    5.  For this transformed conic to be a circle centered at the origin, the coefficients of $X^2$ and $Y^2$ must be equal, and the coefficient of $XY$ must be zero.
    6.  Calculating the coefficient of $XY$ from the substitution and setting it equal to zero gives a condition in terms of $b$. Solving $10(2 - b^2) + 2b(3 - 8) = 0$ simplifies to $20 - 10b^2 - 10b = 0$, or $b^2 + b - 2 = 0$.
    7.  Solving the quadratic yields $b = 1$ or $b = -2$.
    8.  Checking the coefficients of $X^2$ and $Y^2$ for these values confirms they become equal, resulting in a circle. Thus, $b = 1$ or $b = -2$.

**3.**
- **(a)** **Answer:** The model assumes all trees develop at exactly the same rate (e.g., all saplings become young trees after exactly 1 year), which may not reflect natural variation in growth rates.
- **(b)(i)** **Answer:** 75 mature trees
  - **Explanation:** Initial vector is $\begin{pmatrix} 0 \\ 0 \\ M_0 \end{pmatrix}$. After 1 year: $S_1 = 4M_0$, $Y_1 = 0$, $M_1 = 0.88M_0$. After 2 years: $S_2 = 4M_1 = 4×0.88M_0 = 264$ ⇒ $M_0 = 264/(4×0.88) = 75$.
- **(b)(ii)** **Answer:** $p = 0.7$
  - **Explanation:** After 2 years: $Y_2 = pS_1 + qY_1 = p×4M_0 + q×0 = 4p×75 = 154$ ⇒ $300p = 154$ ⇒ $p = 154/300 = 0.7$ (to 1 decimal place).
- **(c)** **Answer:** 
$\frac{1}{-0.7q×0.88} \begin{pmatrix} q×0.88 & 0 & 0 \\ -0.7×0.88 & 0 & -2.8 \\ 0.7×0.35 & -1.4 & 0 \end{pmatrix}^T = \frac{1}{-0.616q} \begin{pmatrix} 0.88q & -0.616 & 0.245 \\ 0 & 0 & -1.4 \\ 0 & -2.8 & 0 \end{pmatrix}$
- **(d)** **Answer:** $q ≈ 0.62$
  - **Explanation:** Using the inverse matrix from (c) with the given population vectors to solve for $q$.
- **(e)** **Answer:** The matrix could be refined to a 4×4 system or the first row could be modified to distinguish seeding sources, since natural and planted saplings may have different survival rates.
  - **Explanation:** The refined model should account for different survival probabilities based on whether saplings originated from natural seeding or planting.

**4.**
- **(a)** **Answer:** $b$ represents the proportion of fledgling birds that survive and remain in the fledgling category after one year.
- **(b)(i)** **Answer:** 
$\frac{1}{0.78b - 0.0264}\begin{pmatrix}0.78 & -0.22\\ -0.12 & b\end{pmatrix}$
- **(b)(ii)** **Answer:** $b = 0.65$
  - **Explanation:** Using the initial total $F_0 + A_0 = 8500$ and the values after one year: $F_1 = bF_0 + 0.22A_0 = 2380$ and $A_1 = 0.12F_0 + 0.78A_0 = 5814$. Solving these equations gives $b = 0.65$.
- **(b)(iii)** **Answer:** The number of fledgling birds decreased by 1,120 in the first year.
  - **Explanation:** $F_0 = 8500 - A_0$. From $A_1 = 0.12(8500 - A_0) + 0.78A_0 = 5814$ gives $1020 + 0.66A_0 = 5814$, so $A_0 = 7260$. Then $F_0 = 1240$. Change = $F_1 - F_0 = 2380 - 3500 = -1120$.
- **(c)** **Answer:** The model may not be suitable in the short term as it predicts a decrease in fledgling numbers that contradicts the need for conservation efforts to increase the population.
- **(d)** **Answer:** The matrix should be refined to include an additional age category for non-reproductive adults, since reproductive capability changes with age and affects population growth projections.
  - **Explanation:** A third category for "senior non-reproductive adults" should be added to better reflect the biological reality that reproduction stops after 12 years.