---
title: blog阅读记录(收获)
author: Shuqiang
date: '2022-09-07'
slug: []
categories:
  - Tech
tags:
  - tag1
  - tag2
subtitle: ''
description: ''
image: ''
---

> 不让时间/阅读变成一次性的，做好自己的积累过程

# [R语言通过loess去除某个变量对数据的影响--CNV分析](https://www.cnblogs.com/nkwy2012/p/9230880.html)

数据有A/B/C三个变量，因变量为A，自变量为B/C，假定B对A有固有的影响，如果直接A \~ B + C，则C的系数结果不一定真实反映了C与A之间的关系，因此需要剔除B对A的影响后，观察C的系数变化


**Loess局部加权多项式回归**
