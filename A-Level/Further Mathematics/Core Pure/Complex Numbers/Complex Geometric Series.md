Consider the geometric series 
$$
1 + e^{i\theta}+e^{2i\theta}\dots+e^{n-1}\theta
$$
For complex numbers, we call:
- First term : $w$
- Common ratio : $z$

In this case:
$$
w = 1 \qquad z = e^{i\theta}
$$
This formula for the sum of a geometric series is:
$$
\boxed{S_{n} = \frac{w(z^{n}-1)}{z-1}}
$$
Thus for this case:
$$
S_{n} = \frac{e^{in\theta}-1}{e^{i\theta}-1}
$$

##  Worked Example 1
$$
z = \cos \frac{\pi}{n} + i\sin \frac{\pi}{n}
$$
Show that $1+z+z^{2}+\dots+z^{n-1}=1+i\cot \frac{\pi}{2n}$.
Writing $z$ in exponential form:
$$
z = e^{\frac{\pi}{n}i}
$$
Expressing the geometric series:
$$
1+z^{2}+z^{3}+\dots = 1+e^{\frac{\pi}{n}i}+e^{\frac{2\pi}{n}i}+e^{\frac{3\pi}{n}i}\dots
$$
The sum of the series is:
$$
\begin{gather*}
S_{n}= \frac{\left( e^{ \frac{\pi}{n} } \right)^{n}-1}{e^{\frac{\pi}{n}i}-1} \\ \\
= \frac{e^{i\pi}-1}{e^{\frac{\pi}{n}i}-1} \\ \\
= -\frac{2}{e^{\frac{\pi}{n}i}-1}
\end{gather*}
$$
Now here is the tricky (tricky as in you literally need to apply a trick)... We are aiming for $\sin\left( \frac{\pi}{2n} \right)$ on the denominator.  Currently we have $e^{\frac{\pi}{n}}$ which will yield $\dots\sin \frac{\pi}{n}$.  So we need to turn $e^{\frac{\pi}{n}}$ into $e^{\frac{\pi}{2n}}$...

This is possible by doing the trick of of multiplying by $\frac{e^{-\frac{\pi}{2n}i}}{e^{-\frac{\pi}{2n}i}}$. This is because this will have the same affect of multiplying by $1$ but due to index laws $e^{\frac{\pi}{n}}e^{-\frac{\pi}{2n}}$ = $e^{\frac{\pi}{n}-\frac{\pi}{2n}}$ which equals $e^{\frac{\pi}{2n}}$ which is what we want.:

$$
\begin{gather*}
= -\frac{2}{e^{\frac{\pi}{n}i}-1}\left(  \frac{e^{-\frac{\pi}{2n}i}}{e^{-\frac{\pi}{2n}i}}\right) \\ \\
= \frac{-2e^{\frac{-\pi}{2n}i}}{e^{\frac{\pi}{n}i}-e^{-\frac{\pi}{2n}i}}
\end{gather*}
$$
Now if we turn this into modulus argument form:
$$
= \frac{-\cancel{ 2 }\left( \cos \frac{\pi}{2n}-i\sin \frac{\pi}{2n} \right)}{\cancel{ 2 }i\sin \frac{\pi}{2n}}
$$
Another trick to remember is dividing by $i$ is the same as multiplying by $-i$:
$$
\begin{gather*}
= \frac{i\cos \frac{\pi}{2n}+\sin \frac{\pi}{2n}}{\sin \frac{\pi}{2n}}
\end{gather*}
$$
Splitting this up into real and imaginary form ($a+bi$):
$$
\begin{gather*}
= \frac{\sin \frac{\pi}{2n}}{\sin \frac{\pi}{2n}}+\frac{i\cos \frac{\pi}{2n}}{\sin \frac{\pi}{2n}} \\ \\
= 1 + i\cot \frac{\pi}{2n} \\ 
QED
\end{gather*}
$$

# Complex Convergent Series
Recall for A-level mathematics, the sum of a convergent geometric  series is:
$$
S_{\infty} = \frac{w}{1-z}
$$
also recall, a geometric series is only convergent if $|z|<1$.

## Worked example 2
The follow series are convergent:
$$
\begin{gather*}
c = 1+\frac{1}{2}\cos\theta+\frac{1}{4}\cos(2\theta)+\frac{1}{8}\cos(3\theta)\dots \\ \\
s = \frac{1}{2}\sin\theta+\frac{1}{4}\sin(2\theta)+\frac{1}{8}\sin(3\theta)\dots
\end{gather*}
$$
Show that $c+is=\frac{2}{2-e^{i\theta}}$. 

If we evaluate $c+is$:
$$
c+is = 1 +\frac{1}{2}(\cos\theta +i\sin\theta)+\frac{1}{4}(\cos2\theta+i\sin 2\theta)+\frac{1}{8}(\cos 3\theta+i\sin 3\theta)\dots
$$
Notice that the $\cos\theta+i\sin\theta$ parts can be written as $e^{i\theta}$:
$$
= 1+\frac{1}{2}e^{i\theta}+\frac{1}{4}e^{2i\theta}+\frac{1}{8}e^{3i\theta}\dots
$$
This gives us a series with $w=1$ and $z=e^{\frac{1}{2}i\theta}$
As the series is convergent  we can use the infinite sum formula:
$$
= \frac{1}{1-\frac{1}{2}e^{i\theta}}
$$
Now notice that we want the denominator to be $e^{i\theta}$,  In order to do this we to apply the same trick but this time multiply by $\frac{2}{2}$ to get rid of the $\frac{1}{2}$ in the denominator:
$$
\begin{gather*}
= \frac{2}{2-e^{i\theta}}  \\
QED
\end{gather*}
$$
## Worked Example 2 Continued...
Hence show that $c=\frac{4-2\cos\theta}{5-4\cos\theta}$. 

Now we we know that $c+is=\frac{2}{2-e^{i\theta}}$. If we were to convert into modulus argument form, $c+is$ will yield $\dots 2-\cos\theta+i\sin\theta$ on the denominator. As well as that we know that $c$ will be the real part of $c +is$. In otherwords $\mathrm{Re}\left( \frac{2}{2-e^{i\theta}} \right)$ will yield $2-\cos\theta$ on the denominator. How can we change this to match the $5-4\cos\theta$ as wanted?...

We need to multiply by $2-e^{-i\theta}$. 
### Why...?
In the question, the desired denominator is real. However we have a fraction that contains an imaginary part. So we essentially want to manipulate the fraction in such a way the denominator is purely real

Recall that:
$$
zz^{*}=|z|^{2}
$$
So we want to multiply the denominator by it's conjugate. That is if the denominator $w=2-e^{i\theta}$ we want to multiply it by $w^{*}=2-e^{-i\theta}$

However in order to preserve the fraction we must also do this to the numerator also . This is because multiplying by $\frac{w^{*}}{w^{*}}$ has the same affect as multiplying by $1$ which keeps the fraction the same whilst also making the denominator real

If $\frac{2}{z}$ then:
$$\frac{2}{z}  \frac{z^{*}}{z^{*}} = \frac{2z^{*}}{|z|^{2}}$$ Which yields a completely real denominator. 

---

Thus in doing so will yield us the $4\cos\theta$ which is what we are looking for:
$$
\begin{gather*}
c+is = \frac{2}{2-e^{i\theta}}\left( \frac{2-e^{i\theta}}{2-e^{-i\theta}} \right) \\ \\
= \frac{4-2e^{-i\theta}}{4-2e^{i\theta}-2e^{-i\theta}+1} \\ \\
= \frac{4-2e^{-i\theta}}{5 - 4\cos\theta}
\end{gather*}
$$
Writing in modulus argument form and in form $a+bi$:
$$
\begin{gather*} 
= \frac{4-2(\cos\theta-i\sin\theta)}{5-4\cos\theta} \\ \\
= \frac{4-2\cos\theta}{5-4\cos\theta} +\frac{2i\sin\theta}{5-4\cos\theta}
\end{gather*}
$$
$c=\mathrm{Re}(c+is)$ which is just:
$$
\begin{gather*}
c=\mathrm{Re}(c+is) = \frac{4-2\cos\theta}{5-4\cos\theta} \\ 
QED
\end{gather*}
$$
## Worked Example 2 Continued Continued...
Hence show that $c+is$ cannot be purely be imaginary.

Now we now that if it were purely imaginary, then the real part of complex number must equal to $0$:
$$
\mathrm{Re}(c + is) = c = 0
$$
Let's consider this:
$$
\begin{gather*}
c = \frac{4-2\cos\theta}{5-4\cos\theta} = 0 \\ \\
\implies 4-2\cos\theta = 0 \\ 
2\cos\theta=4 \\
\cos\theta = 2
\end{gather*}
$$
However as $-1\leq \cos\theta\leq 1, \theta \in  \mathbb{R}$, for this case there are no solutions:
$$
\therefore \text{Never purley imaginary}
$$

If we were to do this for the imaginary part we would do $2\sin\theta=0$ which has solutions so $c+is$ can be purely imaginary

# Worked Example 3
$S$ is a convergent series. $S=\sin\theta-\frac{1}{3}\sin(2\theta)+\frac{1}{9}\sin(3\theta)-\frac{1}{27}\sin(4\theta)\dots$ 
Show that $S = \frac{9\sin\theta}{10 + 6\cos\theta}$

In this problem was must define $C$ (that is $C=\cos\theta$). Do this we can write the value of $S$ but with $\cos\theta$ instead of $\sin\theta$:
$$
C = \cos\theta-\frac{1}{3}\cos(2\theta)+\frac{1}{9}\cos(3\theta)-\frac{1}{27}\cos(4\theta)\dots
$$
Therefore $c+is$=:
$$
(\cos\theta +i\sin\theta) -\frac{1}{3}(\cos(2\theta)+i\sin(2\theta))+\frac{1}{9}(\cos(3\theta)+i\sin(3\theta))-\frac{1}{27}(\cos(4\theta)+i\sin(4\theta))\dots
$$
Writing this out in exponential form:
$$
 = e^{i\theta}-\frac{1}{3}e^{2i\theta}+\frac{1}{9}e^{3i\theta}-\frac{1}{27}e^{4i\theta}\dots
$$
This gives us a geometric series with $w=e^{i\theta}$ and $z=-\frac{1}{3}e^{i\theta}$. The sum of the series is:
$$
\begin{gather*}
= \frac{e^{i\theta}}{1+\frac{1}{3}e^{i\theta}}
\end{gather*}
$$
Now time do some trickery again

First let's multiply out by $\frac{3}{3}$ again to get rid of the $\frac{1}{3}$:
$$
\begin{gather*}
= \frac{e^{i\theta}}{1+\frac{1}{3}e^{i\theta}}\left( \frac{3}{3} \right) \\ \\ 
= \frac{3e^{i\theta}}{3+e^{i\theta}}
\end{gather*}
$$
Now in order for us to get $10+6\cos\theta$, which is real,  we must multiply by $3+e^{-i\theta}$  as multiplying by the conjugate will give the real part of a complex number
$$
\begin{gather*}
\frac{3e^{i\theta}}{3+3e^{i\theta}}\left( \frac{3+e^{-i\theta}}{3+e^{-i\theta}} \right)  \\ \\
= \frac{9e^{i\theta}+3}{9 +3e^{-i\theta}+3e^{^{i\vartheta}}+1} \\ \\
= \frac{9e^{i\theta}+3}{10+3\left( e^{i\theta}+\frac{1}{e^{i\theta}} \right)} \\ \\
= \frac{9e^{i\theta}+3}{10+6\cos\theta} \\ \\= \frac{9\cos\theta+9i\sin\theta+3}{10+6\cos\theta} \\ \\
\end{gather*}
$$
Thus if we want $S$ we must take the imaginary part of $c+is$:
$$
\begin{gather*}
\mathrm{Im}(c+is) = \frac{9i\sin\theta}{10+6\cos\theta} \\
QED
\end{gather*}
$$




