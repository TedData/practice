---
layout: post
title: "The Sum of all Natural Numbers"
subtitle: "The Riemann Hypothesis"
author: "Ted"
date: 2013-10-15
header-img: "img/post-bg-infinity.jpg"
header-mask: 0.3
mathjax: true
tags:
  - math
---

This is the most reasonable proof I have encountered so far.
The result of $1 + 2 + 3 + 4 + 5 + \ldots + \infty$
<br>
Proof:
$assume\ S_{1} = 1 - 1 + 1 - 1 + 1 - 1 + \ldots$
········(1)
<br>
$\Rightarrow 1 - S_{1} = 1 - (1 - 1 + 1 - 1 + 1 - 1 + \ldots)$
········(2)
<br>
$\Rightarrow 1 - S_{1} = 1 - 1 + 1 - 1 + 1 - 1 + 1 - \ldots$
········(3)
<br>
$\therefore 1 - S_{1} = S_{1}$
········(4)
<br>
$\therefore S_{1} = \frac{1}{2}$
········(5)
<br>
$assume\ S_{2} = 1 - 2 + 3 - 4 + 5 - 6 + \ldots$
········(6)
<br>
$\Rightarrow 2S_{2} = (1 - 2 + 3 - 4 + 5 - 6 + \ldots) + (1 - 2 + 3 - 4 + 5 - 6 + \ldots)$
········(7)
<br>
$\Rightarrow 2S_{2} = 1 + ( - 2 + 1) + (3 - 2) + ( - 4 + 3) + (5 - 4) + ( - 6 + 5) + \ldots$
········(8)
<br>
$\Rightarrow 2S_{2} = 1 - 1 + 1 - 1 + 1 - 1 + \ldots$
········(9)
<br>
$\Rightarrow 2S_{2} = S_{1} = \frac{1}{2}$$
········(0)
<br>
$\therefore S_{2} = \frac{1}{4}$
········(1)
<br>
$assume\ S = 1 + 2 + 3 + 4 + 5 + 6 + \ldots$
········(2)
<br>
$\Rightarrow S - S_{2} = (1 + 2 + 3 + 4 + 5 + 6 + \ldots) - (1 - 2 + 3 - 4 + 5 - 6 + \ldots)$
········(3)
<br>
$\Rightarrow S - S_{2} = (1 - 1) + (2 + 2) + (3 - 3) + (4 + 4) + (5 - 5) + (6 + 6) + \ldots$
········(4)
<br>
$\Rightarrow S - S_{2} = 0 + 4 + 0 + 8 + 0 + 12 + \ldots$
········(5)
<br>
$\Rightarrow S - S_{2} = 4(1 + 2 + 3 + 4 + 5 + \ldots)$
········(6)
<br>
$\Rightarrow S - S_{2} = 4S$
········(7)
<br>
$\Rightarrow S = - \frac{S_{2}}{3} = - \frac{\frac{1}{4}}{3} = - \frac{1}{12}$
········(8)
<br>
$Therefore,\ the\ sum\ of\ 1 + 2 + 3 + 4 + 5 + 6 + \ldots = - \frac{1}{12}$
········(9)
<br>
