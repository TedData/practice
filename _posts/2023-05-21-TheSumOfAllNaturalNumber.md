---
layout: post
title: "The Sum of all Natural Number"
subtitle: "The Riemann Hypothesis"
author: "Ted"
header-img: "img/post-bg-infinity.jpg"
header-mask: 0.3
mathjax: true
tags:
  - math
---

> 这篇文章转载自[我在知乎上的回答](https://www.zhihu.com/question/51508063/answer/275401076)

严谨的证明的话，可以使用「形式语言」（[Formal language](https://en.wikipedia.org/wiki/Formal_language)）来证明：

在可计算理论和计算复杂度理论中，每个「计算问题」都被描述为一个一个「形式语言」，即字符串的集合。比如对于判断一个图是否是无向连通图这个问题：我们可以写为一个描述所有无向连通图的集合：

$$
A = \{ \langle G \rangle \vert G \text{ is a connected undirected graph}\}
$$

由于图灵机只能接受字符串，所以这里的尖括号表示对图的「编码」。出于简单，我们全部使用现实计算机所使用的字母表
The result of $1 + 2 + 3 + 4 + 5 + \ldots + \infty$

Proof:

$$assume\ S_{1} = 1 - 1 + 1 - 1 + 1 - 1 + \ldots$$
由于图灵机只能接受字符串，所以这里的尖括号表示对图的「编码」。出于简单，我们全部使用现实计算机所使用的字母表
$\Rightarrow 1 - S_{1} = 1 - (1 - 1 + 1 - 1 + 1 - 1 + \ldots)$
由于图灵机只能接受字符串，所以这里的尖括号表示对图的「编码」。出于简单，我们全部使用现实计算机所使用的字母表
$\Rightarrow 1 - S_{1} = 1 - 1 + 1 - 1 + 1 - 1 + 1 - \ldots$
由于图灵机只能接受字符串，所以这里的尖括号表示对图的「编码」。出于简单，我们全部使用现实计算机所使用的字母表
$\therefore 1 - S_{1} = S_{1}$
由于图灵机只能接受字符串，所以这里的尖括号表示对图的「编码」。出于简单，我们全部使用现实计算机所使用的字母表
$\therefore S_{1} = \frac{1}{2}$

$$assume\ S_{2} = 1 - 2 + 3 - 4 + 5 - 6 + \ldots$
$\Rightarrow 2S_{2} = (1 - 2 + 3 - 4 + 5 - 6 + \ldots) + (1 - 2 + 3 - 4 + 5 - 6 + \ldots)$
$\Rightarrow 2S_{2} = 1 + ( - 2 + 1) + (3 - 2) + ( - 4 + 3) + (5 - 4) + ( - 6 + 5) + \ldots$$

$$\Rightarrow 2S_{2} = 1 - 1 + 1 - 1 + 1 - 1 + \ldots$$

$$\Rightarrow 2S_{2} = S_{1} = \frac{1}{2}$$

$$\therefore S_{2} = \frac{1}{4}$$

$$assume\ S = 1 + 2 + 3 + 4 + 5 + 6 + \ldots$
$\Rightarrow S - S_{2} = (1 + 2 + 3 + 4 + 5 + 6 + \ldots) - (1 - 2 + 3 - 4 + 5 - 6 + \ldots)$
$\Rightarrow S - S_{2} = (1 - 1) + (2 + 2) + (3 - 3) + (4 + 4) + (5 - 5) + (6 + 6) + \ldots$
$\Rightarrow S - S_{2} = 0 + 4 + 0 + 8 + 0 + 12 + \ldots$
$\Rightarrow S - S_{2} = 4(1 + 2 + 3 + 4 + 5 + \ldots)$
$\Rightarrow S - S_{2} = 4S$
$\Rightarrow S = - \frac{S_{2}}{3} = - \frac{\frac{1}{4}}{3} = - \frac{1}{12}$
$Therefore,\ the\ sum\ of\ 1 + 2 + 3 + 4 + 5 + 6 + \ldots = - \frac{1}{12}$$
