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
Writing summation in form of partial fractions and try for a telescoping series. Notice that the telescoping series does not explicitly need to be two terms. For such questions with more than two fractions in the sum, it is better to write from f(1) to f(5) and from f(n) to (n-2) on the bottom allow a clear indication of the pattern of telescoping series
$$
\begin{gather*}
\sum_{r=1}^n \frac{2}{r(r+1)(r+2)} = \sum _{r=1}^n  \frac{1}{r}-\frac{2}{r+1}+\frac{1}{r+2} \\ \\
f(1) = \cancel{ \frac{1}{1} } - \cancel{ \frac{2}{2} } + \cancel{ \frac{1}{3}  }\\ \\
f(2) = \frac{1}{2}- \cancel{ \frac{2}{3} } + \cancel{ \frac{1}{4}  }\\ \\
f(3) = \cancel{ \frac{1}{3}  }- \cancel{ \frac{2}{4} } + \cancel{ \frac{1}{5} } \\ \\
f(4) = \cancel{ \frac{1}{4} } \cancel{ -\frac{2}{5} } + \frac{1}{6}\\ \\
f(5) = \cancel{ \frac{1}{5} } -\frac{2}{6} +\frac{1}{7}\\ \\
\dots \\ \\
f(n-2) = \frac{1}{n-2} - \frac{2}{n-1} + \cancel{ \frac{1}{n} }\\ \\
f(n-1) = \frac{1}{n-1} - \cancel{ \frac{2}{n}  }+ \frac{1}{n+1} \\ \\ f(n) = \cancel{ \frac{1}{n}- } \frac{2}{n+1} + \frac{1}{n+2}
\end{gather*}
$$
Evaluate the sum as a few expressions of n:
$$
\begin{gather*}
\sum_{r=1}^n  \frac{2}{r(r+1)(r+2)} = \frac{1}{2} +\frac{1}{n+2}-\frac{1}{n+1} \\ \\
= \frac{(n+1)(n+1)+2(n+1)-2(n+2)}{2(n+2)(n+1)} \\ \\
= \frac{n^{2}+3n}{2(n+1)(n+2)} \\ \\
=\frac{n(n+3)}{2(n+1)(n+2)}
\end{gather*}
$$

## Step by step Best practices
These questions are very tedious and have a lot of room for error so here are some best practices step by step.

1. For cases when you have two fractions within the telescoping series, in most cases start with f(1) / f(0) and go until f(3).  However the cancelling pattern still does not show go until f(5) and then at the bottom go from f(n) to f(n-1).
   
   For cases when you have three or more fractions, it is better to start with f(1) / f(0) then go until f(5) and then from f(n) to f(n-2) to ensure the pattern is clearly seen. in general go from f(0) / f(1) to f(2k-1) and from from(n) to f(n-k-1) where k is the number of fractions within the telescoping series.

2. Always make sure check limits are correct. And be sure to fully expand all values of $r$ within the summation expression before evaluating the terms of $r$ in terms of $n$ e.g.
 ![[Pasted image 20250927115239.png]]
 For this expression be sure to expand everything out like this before writing in terms of $n$
 $$
\begin{gather*}
\sum_{r=1}^{2n} r((-1)^{2r}+4(-1)^{r}+4r^{2}) \\ \\= r+4(-1)^{r}r^{2} + 4r^{3}
\end{gather*}
$$
3. Once fully expanding out be sure to simplify any fractions that are inside and outside the brackets e.g:n
$$
\dots 4\left( \frac{1}{4}(2n)^{2}(2n+1) \right) = 4n^{2}(2n+1)
$$
4. When simplifying the terms in terms of $n$, try and factorise the common term in every expression and **factor by the smallest fraction** (in this case the smallest fraction is $\frac{1}{3}$e.g.:
$$
\begin{gather*}
\dots \frac{2}{3}n(n+1)(2n+1) - 2n(n+1) +n \\ \\
= \frac{n}{3}(2(n+1)-6(n+1) + 3)
\end{gather*}
$$
5. The last step in these is make sure the total expression is as factorised as possible and any nested expressions that cannot be factorised must be expanded e.g.:
$$
\begin{gather*}
= \frac{n}{3}(4n^{2}+6n+2-6n+3) \\ \\
= \frac{n}{3}(4n^{2}-1)
\end{gather*}
$$
