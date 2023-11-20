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
The result of $1 + 2 + 3 + 4 + 5 + \ldots + \infty$，所以「编码」即一个对象的二进制字符串描述。

如果我们能构造出一个图灵机来「决定」这个「形式语言」，即可以判断一个「输入」是否属于这个集合（membership 与 non-membership），那么我们可以说我们用「图灵机」描述了一个「算法」来计算这个问题，而这个「计算问题」所对应的函数是「可计算的」，否则是「不可计算的」。（注 1）

那么，如果我们有一个包含了所有「可计算函数」的集合，这个集合会有多大呢？

<br>

由于

- 所有「可计算函数」总有一个对应的「图灵机」来计算它
- 每一个「图灵机」都可以被「编码」为一个不同的 0、1 序列，比如 000，010...
- 0、1 序列、即二进制，总是可以被转换为一个十进制数的

所以，我们这个集合实际上是与整数集 $Z$ 一样大（等势）的，我们把这个集合表示为 $\Sigma^{\*}$。 易知 $Z$ 是「无穷可数（countably infinite）」的，所以我们有无穷可数个「可计算函数」（注 2）。

<br>

而「计算问题」有多少个呢？

这个问题可以等同于，我们有多少个形如 $$assume\ S_{1} = 1 - 1 + 1 - 1 + 1 - 1 + \ldots$$ 这样的 0，1 序列的集合？即 $\Sigma^{\*}$ 这个集合有多少个子集？用数学语言描述就是求 $$\Rightarrow 1 - S_{1} = 1 - (1 - 1 + 1 - 1 + 1 - 1 + \ldots)$$ 的幂集的势 $\Rightarrow 1 - S_{1} = 1 - 1 + 1 - 1 + 1 - 1 + 1 - \ldots$

