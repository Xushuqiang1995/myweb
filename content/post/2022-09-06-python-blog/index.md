---
title: Python_库_书_blog(介绍)
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



> 主要介绍文章
> 1. 将Python内容按照用途分为若干个专题，其一介绍各个包的用途及包文档说明链接，在第二列对库功能/函数进行简要介绍，且应该给出相应的代表性函数。
> 2. Python实用的资源/推荐书和理由/blog等，保持学习的冲劲，每个领域1-2本书就完全足够了，不在多，而在精，如果能读完，最好能进行一个比较，持续更新学习进度
> 3. 学习进度栏，每次完成一本书/项目，记录完成时间和具体项目(超链接)
> | []()                                                      |  []()                                                       |
> | []()                                                      | []()                                         |


# 博客


# 库

### Python资料Gallery

| **资料汇总网址**                                     |                          |
| -----------------------------                        |  ---------------------   |
| [nbviewer](https://nbviewer.org/)                        | A simple way to share Jupyter Notebooks|输入URL等信息，可在线浏览ipynb信息，例如Github中的ipynb文件   |
| [shell命令解析](https://explainshell.com/)                        | 辅助工具查看/理解shell命令  |
| [scikit learn官网](https://scikit-learn.org/stable/index.html)    | 通过示例介绍Python的特征工程和建模领域的应用  |
| [sklearn中文版](https://www.scikitlearn.com.cn/) | 其参考了scikit learn官网内容进行了整合   |
| [pandas官方网址](https://pandas.pydata.org/pandas-docs/stable/getting_started/comparison/comparison_with_r.html#compare-with-r) | pandas官网，对于其他编程语言爱好者非常友好，将Python的脚本与R中数据处理脚本进行对比  |
| [Python库检索](https://pypi.org/) | 用于python库的查询、下载和发布  |
| [Python内置函数](https://docs.python.org/zh-cn/3/library/functions.html) |   |
| [动态规划问题(Dynamic Programming)](https://oi-wiki.org/dp/) |   |
| []()                        |   |
| []()                        |   |



### 常用package及其介绍

主要应用：数值计算、数据可视化、Web开发、数据库管理、自动化运维、GUI编程、机器学习、深度学习、爬虫、图像处理、自然语言处理、[量化金融](https://space.bilibili.com/389455044/channel/series)、多线程与并发

[Python常用库整理](https://zhuanlan.zhihu.com/p/21563130)  
[24个顶级Python库](https://zhuanlan.zhihu.com/p/76112940)  
[15个Python库](https://zhuanlan.zhihu.com/p/469139128)  
[]()  

| 常用包                            | 用途介绍                             |
|-----------------------------------|-------------------------------------|
| [data.table](https://atrebas.github.io/post/2020-06-14-datatable-pandas/) | Python高效数据清理库 |
| [Pyjanitor](https://blog.csdn.net/bf02jgtrs00xktcx/article/details/108067390) | 同R中janitor一样，用来更好地数据清理 |
| [numpy]()                              | [Numeric Python](https://zhuanlan.zhihu.com/p/382110229),Python数值计算的基石，主要内容有：快速高效的多维数组对象ndarray/基于元素的数学计算/硬盘中数据集的读写/线性代数、傅里叶变换等------------------------------------ |
| [pandas]()                              | [Python Data Analysis](https://zhuanlan.zhihu.com/p/382110229),pandas提供了高级数据结构和函数，这些数据结构和函数的设计使得利用结构化、表格化数据的工作快速、简单、有表现力。------------------------------------ |
| [PyOD]()                              | 异常值检测.[来源](https://zhuanlan.zhihu.com/p/76112940) |
| [matplotlib]()                              | 数据可视化 |
| [Seaborn]()                              | 数据可视化 |
| [Geoplotlib]()                              | 地图数据可视化 |
| [os]()                              | 获取操作系统相关信息 |
| [Statmodels]()                              | Statsmodels库是Python中一个强大的统计分析库，包含假设检验、回归分析、时间序列分析等功能，能够很好的和Numpy和Pandas等库结合起来，提高工作效率。 |
| [unittest](https://www.bilibili.com/video/BV1Sd4y1a7Us?p=36&vd_source=ded60bf71a923854104861c4f0757962) | Python单元测试库，python自带，不需要额外安装 |
| [request]()                              | Request是用于网页分析的依赖库，常用方法为get() |
| [Scrapy]()                              | 网络爬虫工作 |
| [BeautifulSoup]()                              | 用于收集网站内容，Scrapy需要开发自己的‘爬虫’并通过命令操作，而BeautifulSoup只需将其功能导入计算机中并联机使用即可（request/scrapy优先） |
| [Selenium]()                              | 设计初衷用于自动网站测试框架，但其用于网页数据抓取工具的效果极佳 |
| [Scikit-learn]()                              | 机器学习框架，主要包含六大主要模块(数据预处理、维度缩减、数据回归、数据分类、数据聚类、模型选择) |
| [Tensorflow]()                              | 相对高阶的机器学习库，底层使用C++语言编写，运行效率得到了保证；？？Tensorboard上的数据流图像功能最受欢迎，将数据学习流和结果进行了可视化处理； |
| [PyTorch]()                              | Facebook发布的开源库，深度学习框架 |
| [OpenCV]()                              | OpenCV提供了python应用接口 |
| [Librosa]()                              | 音频和声音处理python库 |
| [Django]()                              | 开发网页服务后端，网页开发框架；主要模块有([urls/views/models/forms/templates/admin/settings](https://www.jianshu.com/p/4302f5052b2e))------------------------------------ |
| [Flask]()                              | python的轻量级网页开发框架------------------------------------ |
| [Translators]()                              | 集成谷歌、必应、诱导、百度等多个翻译平台的API接口 |
| [Scipy]()                              | [SciPy是科学计算领域针对不同标准问题域的包集合](https://zhuanlan.zhihu.com/p/382110229)，主要内容有scipy.integrate/scipy.linalg/scipy.optimize/scipy.signal/scipy.sparse/scipy.special/scipy.stats/；[在NumPy库的基础上增加了众多的数学、科学及工程计算中常用的库函数,如线性代数、常微分方程数值求解、信号处理、图像处理、稀疏矩阵等，可进行插值处理、信号滤波，以及使用C语言加速计算。](https://zhuanlan.zhihu.com/p/89477028) |
| [Spacy]()                              | 非常有用且灵活的自然语言处理( NLP )库和框架，用于清理创建模型的文本文档。与类似用途的其他库相比，SpaCy速度更快。[来源](https://zhuanlan.zhihu.com/p/76112940) |
| [missingno]()                              | 用图像的方式快速评估**数据缺失**的情况，可根据数据的完整度对数据进行排序或过滤，或者根据热度图或树状图对数据进行修正。 |
| [XGBoost]()                              | XGBoost是专注于梯度提升算法的机器学习函数库；比起同样实现了梯度提升算法的Scikit-Learn库，其性能提升10倍以上。XGBoost可以处理回归、分类和排序等多种任务。 |
| [Caffe]()                              | **Convolutional Architecture for Fast Feature Embedding**；是一个以表达式、速度和模块化为核心的深度学习框架，具备清晰、可读性高和快速的特性，在视频、图像处理方面应用较多。 |
| [Keras]()                              | 高度模块化的神经网络库，使用Python实现；Keras**专精于深度学习**，其提供了到目前为止最方便的API |
| [datetime]()                              | 日期和时间的操作库datetime |
| [math]()                              | math库提供了数学常数和数学函数 |
| [sys]()                              | 通常用于命令行参数的库sys |
| [random]()                              | random 模块实现了各种分布的伪随机数生成器 |
| []()                              | ------------------------------------ |
| []()                              | ------------------------------------ |
| -----------------------------                                             | ------------------------------------ |




### 爬虫专题

| **爬虫**                                             |                          |
| -----------------------------                        |  ---------------------   |
| [Mining-the-Social-Web-2nd-Edition](https://nbviewer.org/github/ptwobrussell/Mining-the-Social-Web-2nd-Edition/tree/master/ipynb/) | 介绍常用社交网站的爬虫技巧，例如Facebook/Twitter/Linkedn等web   |
| []()                        |   |
| []()                        |   |
| []()                        |   |



# 书

python基础：《Python编程：从入门到实践（第2版）》  
python进阶：《流畅的python》  

