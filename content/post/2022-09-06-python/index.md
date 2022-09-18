---
title: Python方法(多复习)
author: Shuqiang
date: '2022-09-06'
slug: []
categories:
  - Python
tags:
  - tag1
  - tag2
subtitle: ''
description: ''
image: ''
---

> 1.  需要专门用(\>)标明新颖点

```{r, eval = FALSE}
# Linux系统下安装rsvg报错，因为需要下载lib2rsvg包
# 解决办法
# conda install -c conda-forge r-rsvg这条命令可以从conda-forge库里面下载rsvg这个包并且能在本地用了
# 问题
# 1. conda自动下载了librsvg2 device了吗？
# 2. conda执行了哪些步骤？
conda install -c conda-forge r-rsvg
```

[conda install packages error 详解channel 设置](https://blog.csdn.net/lvsehaiyang1993/article/details/80621169)

```{Python}
%matplotlib inline 可以在Ipython编译器里直接使用，功能是可以内嵌绘图，并且可以省略掉plt.show()这一步。
%matplotlib inline

# 用来正常显示中文标签
plt.rcParams['font.sans-serif']=['SimHei']  

# 处理时间变量
from datetime import datetime

# 帮助文档
help(pd_example.describe)
help(pd.describe)
help(pd.DataFrame.describe)

# python常见的数据结构
# https://www.cnblogs.com/yangyuqing/p/10101663.html
# Python中常见的数据结构可以统称为容器。序列（如列表和元组）、映射（如字典）以及集合（set）是三类主要的容器。
# 
# 线性数据结构分类：栈(stack)--先进后出、 队列(queue)-先进先出、双端队列(deque)、链表(LinkedList)

# 列表的类型转换
values = [1,4,7,9]
list(map(str, values))
[str(i) for i in values]
```

# 激活函数

sigmoid函数:$1/(1+e^{-x})$  
sigmoid函数:$$1/(1+e^{-x})$$  
由于其在两端时数值的变化不明显(梯度/斜率趋近于零)，存在梯度消失的现象，由此引起其后的权重不发生明显变化了  
Relu函数：90%的情况下使用，另5%的情况使用Relu的变形情况

# 卷积神经网络

卷积层：提取特征(保持了图像的三维特征)  
池化层：压缩特征, 常用Max-pooling，因为卷积本身就是需要将主要的特征提取出来，而Max-averaging则会弱化主要特征的表现，并且在实际应用中，其Max-pooling表现要好很多  
全连接层： 为什么3*3的卷积层要优于7*7的参数矩阵

- 自由参数少$3 \times 3 = 9 < 7 \times 7=49$
























