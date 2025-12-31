[[Determinants]][[Matrix Multiplication]][[Inverting a 2 x 2 matrix]][[Invariant points and Invariant lines]]
$$
\begin{align*}
&\text{Let } M \text{ denote the matrix } \\ \\
& \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix}. \\ 
\\ &\text{a) Show that } (M - I) \text{ is non-singular.} \\
\\ &\text{b) Write down the matrices } M^2, M^3, M^4 \text{ and } M^n \text{ and hence determine the general form of the matrix } M^n, n \in \mathbb{N}. 
\\ \\ &\text{The linear transformation } T \text{ is represented by} \\ \\
&(M - I)^n (M^T - I), \quad n \in \mathbb{N}. \\
\\ &\text{c) Prove that } T \text{ has a line of invariant points if and only if } n \text{ is odd.} \\
\\ &\text{d) Hence, show that } y = -x \text{ is a line of invariant points for all odd values of } n.
\end{align*}
$$
![[Pasted image 20250908170926.png]]
a)
$$
M - I = \begin{pmatrix} 2 & 3 \\ 0 & -1 \end{pmatrix} - \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix} = \begin{pmatrix} 1 & 3 \\ 0 & -2 \end{pmatrix}
$$
$$
\begin{gather*}
\det(M - I) = (1)(-2) - (3)(0) = -2 \neq 0 \\ \\
\therefore (M - I) \ \ \ \text{is non-singular}
\end{gather*}
$$
b) 
$$
\begin{gather*}
\text{Compute powers of M : } \\ \\
M^{2} = \begin{pmatrix}
4 & 3 \\
0 & -1
\end{pmatrix} \\ \\
M^{3} = \begin{pmatrix}
8 & 9 \\
0 & -1
\end{pmatrix} \\ \\
M^{4} = \begin{pmatrix}
16 & 15 \\
0 & -1
\end{pmatrix} \\ \\
\text{Top left entry : } 2,4,8,16\dots\text{which is }2^{n} \\ \\
\text{Top right entry : } 3,3,9,15\dots\text{Notice that for n=1: 3, n=2: 3, n=3: 9, n=4:4} \\
\text{This sequences satisfies } 2^{n}-(-1)^{n} \\ \\
\text{Top bottom left entry is always } 0 \\ \\
\text{Top bottom right entry -1,1,-1,1... which is } (-1)^{n} \\ \\ \text{Thus the general form is : } \\ \\
\begin{pmatrix}
2^{n}  & 2^{n}-(-1)^{n} \\
0 & (-1)^{n}
\end{pmatrix}
\end{gather*}
$$
c)
$$
\begin{gather*}
\text{The transformation is presented by: } \\ \\
T = (M-I)^{-1}(M^{n}-I) \\ \\
\text{At point } \mathbf{x} \text{ is invariant under } T\mathbf{x}=\mathbf{x}. So: \\ \\
(M-I)^{-1}(M^{n}-I)\mathbf{x}= \mathbf{x} \\ \\ 
\text{Multiply both sides by } (M - I): \\ \\
(M^{n}-I)\mathbf{x}= (M-I)\mathbf{x} \\
M^{n}\mathbf{x}-\mathbf{x}= M\mathbf{x}-\mathbf{x} \\ 
M^{n}\mathbf{x}=M\mathbf{x} = 0 \\
(M^{n-1} - M)\mathbf{x} = 0 \\ \\
\text{Since M is non-signuar, we can multiply by } M^{-1} \\ \\
(M^{n-1}-I)\mathbf{x}=0 \\
M^{n-1}\mathbf{x}=\mathbf{x} \\ \\
\text{So x is an invariant point of } M^{n-1.} \\ \text{For there to be a line of invariant points, the matrix } \\M^{n-1}-I \text{ must be singular meaning its determinant is zero} \\ \\
 \text{Using the general form of M equation from last question: } \\ \\
 M^{n-1} = \begin{pmatrix}
2^{n-1} & 2n^{n-1}-(-1)^{n-1} \\
0 & (-1)^{n-1}
\end{pmatrix} \\ \\
 \text{Then : } \\
 M^{n-1} - I = \begin{pmatrix}
2^{n-1} - 1 & 2n^{n-1}-(-1)^{n-1} \\
0 & (-1)^{n-1} - 1
\end{pmatrix} \\ \\
\text{The determinant is: } \\ \\
\det(M^{n-1} - I) \\ = (2^{n-1} - 1) [(-1)^{n-1} - 1] - [2^{n-1} - (-1)^{n-1}](0) \\ = (2^{n-1} - 1)[(-1)^{n-1} - 1] \\ \\
\text{For a line of invariant points, we need infintley many solutions, so the determinant must be zero.} \\ \\
(2^{n-1} - 1)[(-1)^{n-1} - 1] = 0 \\ \\ 
(2^{n-1} - 1) = 0 \text{ Only when n=1, but we consider } n \in \mathbb{N}. \\ 
(-1)^{n-1}-1 = 0 \text{ when } (-1)^{n-1} = 1, \text{ i.e when n-1 is even so, n is odd.} \\ \\
\\det(m^{n - 1} - I)=0  \ if \text{ and only if n is odd. Thus for odd n, there is a line of invariant points.} \\ \\
\therefore \ \text{T has a line of invariant points if and only if n is odd.}
\end{gather*}
$$

