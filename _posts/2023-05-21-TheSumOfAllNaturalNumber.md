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

Proof:
$assume\ S_{1} = 1 - 1 + 1 - 1 + 1 - 1 + \ldots$
········(1)
$\Rightarrow 1 - S_{1} = 1 - (1 - 1 + 1 - 1 + 1 - 1 + \ldots)$
········(2)
$\Rightarrow 1 - S_{1} = 1 - 1 + 1 - 1 + 1 - 1 + 1 - \ldots$
········(3)
$\therefore 1 - S_{1} = S_{1}$
········(4)
$\therefore S_{1} = \frac{1}{2}$
········(5)
$assume\ S_{2} = 1 - 2 + 3 - 4 + 5 - 6 + \ldots$
········(6)
$\Rightarrow 2S_{2} = (1 - 2 + 3 - 4 + 5 - 6 + \ldots) + (1 - 2 + 3 - 4 + 5 - 6 + \ldots)$
········(7)
$\Rightarrow 2S_{2} = 1 + ( - 2 + 1) + (3 - 2) + ( - 4 + 3) + (5 - 4) + ( - 6 + 5) + \ldots$
········(8)
$\Rightarrow 2S_{2} = 1 - 1 + 1 - 1 + 1 - 1 + \ldots$
········(9)
$\Rightarrow 2S_{2} = S_{1} = \frac{1}{2}$$
········(0)
$\therefore S_{2} = \frac{1}{4}$
········(1)
$assume\ S = 1 + 2 + 3 + 4 + 5 + 6 + \ldots$
········(2)
$\Rightarrow S - S_{2} = (1 + 2 + 3 + 4 + 5 + 6 + \ldots) - (1 - 2 + 3 - 4 + 5 - 6 + \ldots)$
········(3)
$\Rightarrow S - S_{2} = (1 - 1) + (2 + 2) + (3 - 3) + (4 + 4) + (5 - 5) + (6 + 6) + \ldots$
········(4)
$\Rightarrow S - S_{2} = 0 + 4 + 0 + 8 + 0 + 12 + \ldots$
········(5)
$\Rightarrow S - S_{2} = 4(1 + 2 + 3 + 4 + 5 + \ldots)$
········(6)
$\Rightarrow S - S_{2} = 4S$
········(7)
$\Rightarrow S = - \frac{S_{2}}{3} = - \frac{\frac{1}{4}}{3} = - \frac{1}{12}$
········(8)
$Therefore,\ the\ sum\ of\ 1 + 2 + 3 + 4 + 5 + 6 + \ldots = - \frac{1}{12}$
········(9)
