+++
aliases = []
date = 2020-06-01T23:00:00Z
katex = true
markup = ""
tags = ["math", "java"]
title = "To the power"

+++
How does a Java find 2<sup>2</sup>? What about x<sup>n</sup>? We'll look at some different approaches to calculating powers and take a look at how Java Math.pow(double, double) does it.

Let's get grounded with a quick and dirty solution. If n is an integer, a simple way to find x<sup>n</sup> is to multiply x by itself n times. That'll take on the order of n operations: \\[Theta (n)\\].

Notice that n is either odd or even. If odd

To be continued...