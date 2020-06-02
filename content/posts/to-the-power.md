+++
aliases = []
date = 2020-06-01T23:00:00Z
katex = true
markup = ""
tags = ["draft", "math", "java"]
title = "To the power"

+++
How does a Java find 2<sup>2</sup>? What about x<sup>n</sup>? We'll look at some different approaches to calculating powers and take a look at how Java Math.pow(double, double) does it.

Let's get grounded with a quick and dirty solution. If n is an integer, a simple way to find x<sup>n</sup> is to multiply x by itself n times. That'll take on the order of n operations: \\(\Theta (n)\\).

If n is odd \\(n=(n-1) + 1\\) so we have \\(x^n=x^{n-1} \cdot x\\). Otherwise, \\(x^n=x^{frac{n}{2}^{2}}\\).

To be continued...