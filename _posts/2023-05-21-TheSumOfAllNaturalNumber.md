---
layout: post
title: "The Sum Of All Natural Numbers"
subtitle: 'The Riemann Hypothesis'
date: 2023-05-21
author: "Ted"
header-style: text
tags:
  - math
---


而「计算问题」有多少个呢？

这个问题可以等同于，我们有多少个形如 $\\{000, 010\\}$ 这样的 0，1 序列的集合？即 $\Sigma^{\*}$ 这个集合有多少个子集？用数学语言描述就是求 $\Sigma^{\*}$ 的幂集的势 $\| P(\Sigma^{\*})\|$ 。

由于 $\Sigma^{\*}$ 与 $Z$ 是等势的，所以这个问题等价于求 $\|P(Z)\|$ 的大小。根据 [Cantor's theorem](https://en.wikipedia.org/wiki/Cantor%2527s_theorem)，一个「无穷可数」的集合的幂集是「无穷不可数（uncountably infinite）」的。（注 3）
<br>

The result of $1 + 2 + 3 + 4 + 5 + \ldots + \infty$

Proof:

<br>

     $$assume\ S_{1} = 1 - 1 + 1 - 1 + 1 - 1 + \ldots$$ 

<br>

     $$\Rightarrow 1 - S_{1} = 1 - (1 - 1 + 1 - 1 + 1 - 1 + \ldots)$$     

     $$\Rightarrow 1 - S_{1} = 1 - 1 + 1 - 1 + 1 - 1 + 1 - \ldots$$     

     $$\therefore 1 - S_{1} = S_{1}$$     

     $\therefore S_{1} = \frac{1}{2}$     

     $assume\ S_{2} = 1 - 2 + 3 - 4 + 5 - 6 + \ldots$     

     $\Rightarrow 2S_{2} = (1 - 2 + 3 - 4 + 5 - 6 + \ldots) + (1 - 2 + 3 - 4 + 5 - 6 + \ldots)$     

     $\Rightarrow 2S_{2} = 1 + ( - 2 + 1) + (3 - 2) + ( - 4 + 3) + (5 - 4) + ( - 6 + 5) + \ldots$     

     $\Rightarrow 2S_{2} = 1 - 1 + 1 - 1 + 1 - 1 + \ldots$     

     $\Rightarrow 2S_{2} = S_{1} = \frac{1}{2}$     

     $\therefore S_{2} = \frac{1}{4}$     

     $assume\ S = 1 + 2 + 3 + 4 + 5 + 6 + \ldots$     

     $\Rightarrow S - S_{2} = (1 + 2 + 3 + 4 + 5 + 6 + \ldots) - (1 - 2 + 3 - 4 + 5 - 6 + \ldots)$     

     $\Rightarrow S - S_{2} = (1 - 1) + (2 + 2) + (3 - 3) + (4 + 4) + (5 - 5) + (6 + 6) + \ldots$     

     $\Rightarrow S - S_{2} = 0 + 4 + 0 + 8 + 0 + 12 + \ldots$     

     $\Rightarrow S - S_{2} = 4(1 + 2 + 3 + 4 + 5 + \ldots)$     

     $\Rightarrow S - S_{2} = 4S$     

<br>

     $$\Rightarrow S = - \frac{S_{2}}{3} = - \frac{\frac{1}{4}}{3} = - \frac{1}{12}$$     

     $$Therefore,\ the\ sum\ of\ 1 + 2 + 3 + 4 + 5 + 6 + \ldots = - \frac{1}{12}$$     

<br>
