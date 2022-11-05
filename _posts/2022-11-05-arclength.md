---
title: Deriving the arc length formula
sidebar:
  nav: layouts
---

The arc length formula is an interesting formula because it incorporates both the integral and the derivative. This is how I like to think the derivation goes.
There are many derivations for this formula, but I take a special liking to this one because I came up with it on a particularly breezy evening. <br>

Let there be a differentiable function $f(x)$ in $[a,b]$.<br>
<center>![image](https://user-images.githubusercontent.com/117506013/200125354-c49512f4-cb35-4e2b-9abe-a0ad7bc24e83.png)</center><br>
We can divide this curve into several partitions. In the figure above, we divide it into 9 equal partitions.
The finer our partitions are, the better the approximation. In our case, we will make a generalisation.
Let there be $n$ partitions from $a$ to $b$. We will call the $x$-value of $P_0$, $x_1$. The $P_{n-1}$-th partition
assumes the $x$-value $x_n$. The size of each partition is $\Delta x=\frac{b-a}{n}$, so the distance between two consecutive
$x$-values, say $x_j$ and $x_{j+1}$, can be interpreted as $x_{j+1}=x_j+\Delta x $.<br>
The length of one line, say in the figure $P_1$ to $P_0$ can be derived from the Pythagorean theorem. We have<br>
$$\displaystyle \sum^n_{i=1}\sqrt{(\Delta x)^2+[f(x_i)-f(x_{i-1})]^2}$$.
