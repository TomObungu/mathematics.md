The method of differences is typically used in questions involving the sums of reciprocals. These questions often involve splitting the fraction into partial fractions then either forming a telescoping series or a general form of the sum of fractions.

## Worked example 1
*Find $\sum_{r=1}^n\frac{2}{4r^{2}-1}$*

1. You must express the fractional expression as partial fractions
$$
\begin{gather*}
\frac{2}{4r^{2}-1} = \frac{2}{(2r+1)(2r-1)} = \frac{A}{2r+1} + \frac{B}{2r-1} \\ \\
2=A(2r-1) + B(2r+1) \\ \\
r=-\frac{1}{2}: \qquad 2=-2A\implies A=-1 \\ \\
r=\frac{1}{2} \qquad 2=2B\implies B=1 \\ \\
\therefore \qquad \frac{2}{4r^{2}-1} = \frac{1}{2r-1} -\frac{1}{2r+1}
\end{gather*}
$$
2. Then write the partial fraction expression as a summation and try for a telescoping series. 
   
   If you notice a telescoping series, start cancelling the terms and find the pattern. e.g each term on the right cancels out with the bottom next term on the left.  
   
   Once this pattern has been found, start from the bottom terms of $f(n)$ and $f(n-1)$ and start working the pattern backwards. Eventually following the pattern backwards, will the summation evaluating to only a few expressions in terms of $n$.
$$
\begin{gather*}
\sum_{r=1}^n \frac{2}{4r^{2}-1} = \sum_{r=1}^n \frac{1}{2r-1} -\frac{1}{2r+1} \\ \\
f(1) = \frac{1}{1} - \cancel{ \frac{1}{3} } \\ \\
f(2) = \cancel{ \frac{1}{3}  }- \cancel{ \frac{1}{5} } \\ \\
f(3) = \cancel{ \frac{1}{5} } - \cancel{ \frac{1}{7}  }\\ \\
\dots \\ \\
f(n-1) = \cancel{ \frac{1}{2n-3} } - \cancel{ \frac{1}{2n-1}  }\\ \\
f(n) = \cancel{ \frac{1}{2n-1}  }- \frac{1}{2n+1}
\end{gather*}
$$
3. Once the summation has been evaluated to only a few expressions in terms of $n$.
$$
=1-\frac{1}{2n+1} = \frac{2n+1}{2n+1} - \frac{1}{2n+1} = \frac{2n}{2n+1}
$$
4. Therefore:
   $$
\sum_{r=1}^n \frac{2}{4r^{2}-1} = \frac{2n}{2n + 1}
$$

# Worked example 2
*Find in terms of $n$ $\sum_{r=1}^n  \frac{1}{r(r+1)(r)}$ giving your answer in the form $\frac{n(n+A)}{B(n+1)(n+2)}$, where $A$ and $B$ are constants to be found*

$$
\begin{gather*}
\frac{2}{r(r+1)(r+2)}=\frac{A}{r} + \frac{B}{r+1} + \frac{C}{r+2} \\ \\
2 = A(r+1)(r+2) + B(r)(r+2) + C(r)(r+1) \\ \\
r = 0: \qquad 2=2A \implies A=1 \\ \\
r = -1  \qquad 2=-B\implies B=-2 \\ \\
r = 1 \qquad 2=6-6+2C\implies C=1 \\ \\
\therefore \frac{2}{r(r+1)(r+2)} = \frac{1}{r}-\frac{2}{r+1}+\frac{1}{r+2}
\end{gather*}
$$
Writing summation in form of partial fractions and try for a telescoping series. Notice that the telescoping series does not explicitly need to be two terms.
$$
\begin{gather*}
\sum_{r=1}^n \frac{2}{r(r+1)(r+2)} = \sum _{r=1}^n  \frac{1}{r}-\frac{2}{r+1}+\frac{1}{r+2} \\ \\
f(1) = \cancel{ \frac{1}{1} } - \cancel{ \frac{2}{2} } + \cancel{ \frac{1}{3}  }\\ \\
f(2) = \cancel{ \frac{1}{2}  }- \cancel{ \frac{2}{3}  }+ \cancel{ \frac{1}{4} } \\ \\
f(3) = \cancel{ \frac{1}{3}  }- \cancel{ \frac{2}{4} } + \cancel{ \frac{1}{5}  }\\ \\
\dots \\ \\
f(n-1) = \cancel{ \frac{1}{n-1} } -\cancel{ \frac{1}{n}  }+ \cancel{ \frac{1}{n+1}  }\\ \\ f(n) = \cancel{ \frac{1}{n} }- \cancel{ \frac{1}{n+1} } + \frac{1}{n+2}
\end{gather*}
$$
