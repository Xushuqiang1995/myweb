---
title: R 包/blog/书籍介绍
author: shuqiang
date: '2022-08-18'
output:
  toc: true
slug: []
categories:
  - R
tags:

subtitle: '主要整理了R常用包详细介绍、书籍、blog信息'
description: '主要整理了R常用包详细介绍、书籍、blog信息'
image: ''
---

> 主要介绍文章
> 1. 将R内容按照用途分为若干个专题，其一介绍各个包的用途及包文档说明链接，在第二列对包功能/函数进行简要介绍，且应该给出相应的代表性函数。
> 2. R实用的资源/推荐书和理由/blog等，保持学习的冲劲，每个领域1-2本书就完全足够了，不在多，而在精，如果能读完，最好能进行一个比较，持续更新学习进度
> 3. 学习进度栏，每次完成一本书/项目，记录完成时间和具体项目(超链接)
> | []()                                                      |  []()                                                       |
> | []()                                                      | []()                                         |

# R

### R资料Gallary

| **流行的R资源汇总网址**    | 用途介绍 |
| ---------------------- | -------- |
| [awesome-R](https://github.com/qinwf/awesome-R) | 它统计了CRAN上前50且git上被赞500以上的包。其一，R包系列，涵盖数据处理,绘图,ML,NLP,贝叶斯,高性能R,最优化,金融,空间,生信等领域；其二，资料，涵盖网址,书,慕课,podcast,Reference Card；其中的[R-blogger](https://www.r-bloggers.com/)/[R-weekly](https://rweekly.org/)/[R-users](https://www.r-users.com/)/[R AI blog](https://blogs.rstudio.com/ai/)|
| [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness) | Awesome系列，对每种编程语言都进行了汇总，并总结成awesome-R相似的界面  |
| [Awesome-rshiny](https://github.com/grabear/awesome-rshiny) | 根据shiny开发不同需求汇总shiny包内容   |
| [Awesome NLP in R](https://github.com/BZRLC/R-notes/blob/master/NLP/readme.md) | `NLP`在R应用中的细分领域，有中文，包含分词、向量化、文本回归与去重、文本定量分析与主题模型等内容  |
| [R Data Science Tutorials](https://github.com/ujjwalkarn/DataScienceR) | 数据科学指南更加注重统计建模内容，大多会转至另一个R-blogger超链接，适合长期抽空阅读看；[Python数据科学指南](https://github.com/ujjwalkarn/DataSciencePython)  |
| [Python Data Science Tutorials](https://github.com/ujjwalkarn/DataSciencePython)  |  Python数据科学指南专题 |
| [Machine Learning & Deep Learning Tutorials](https://github.com/ujjwalkarn/Machine-Learning-Tutorials/blob/master/README.md)  | Awesome系列，python数据科学指南  |
| [R package list(中文)](http://www.idata8.com/index2.html)                                |  (偶尔)R包中文介绍目录      |
| [计算机电子书 2021 Git 仓库备份](https://github.com/apachecn/it-ebooks-archive/blob/66a1d479215c0e325d5b86175996a7677d4ff19c/docs/it-ebooks-2021.md) |  视觉AI应用/NLP基本概念和基于Transformer的NLP入门  |
| [Awesome lists about all kinds of interesting topics](https://github.com/sindresorhus/awesome) |  Awesome系列(对Big Data专题感兴趣) |
| [awesome-python](https://github.com/vinta/awesome-python) |  ------------------------------------                        |
| [学习笔记——机器学习与经济学](https://github.com/jmxsy2016/Data-Science-and-Economics/blob/aeebd1f13c4881fdd1d30222f9d1848c0c684a93/README.md)                                |                      |
| [BiocManager::install]()                                |  生信常用包安装方式                        |
| [Big Cook of R(R百科全书，全面介绍了R语言在各领域的应用内容，并附上推荐书籍)](https://www.bigbookofr.com/big-data.html#using-spark-from-r-for-performance-with-arbitrary-code) | 超过300本免费书籍，在[R-blogger](https://www.r-bloggers.com/2022/07/part-1-of-3-300-milestone-for-big-book-of-r/)中有3篇单独文章介绍其内容和发展。其中涉及计量经济学、机器学习、贝叶斯、文本分析等领域的应用 |
| [bigcook of R 新增23本书](https://www.r-bloggers.com/2022/09/23-new-books-added-to-big-book-of-r/) |  涉及生物/多元统计分析/brms包/中介、调节效应/网页抓取等内容 |
| [bigcook of R](https://www.bigbookofr.com/index.html)                                |  ------------------------------------                        |
| [RStudio Cheatsheet](https://github.com/rstudio/cheatsheets)                                |  在github中找到最新的cheatsheet内容信息                        |
| [神经网络计算图解小工具](https://aegeorge42.github.io/)                                |  通过图形的方式，介绍了神经网络的计算/迭代过程                        |
| []()                                |  ------------------------------------                        |
| **优质R-blogger记录**                   |  理由/读后感                        |
| [预测模型的可解释性和可解释性](https://www.r-bloggers.com/2022/08/interpretability-and-explainability-of-predictive-models/) |  ------------------------------------                        |
| [基于R的贝叶斯回归](https://www.r-bloggers.com/2022/08/interpretability-and-explainability-of-predictive-models/)                                |  ------------------------------------                        |
| [Guy开发维特根斯坦shiny(wecd in git)界面总结](https://gjabel.wordpress.com/2015/06/15/shiny-app-for-the-wittgenstein-centre-population-projections/) | Guy遇到的问题，数据量过大/复杂图导出PDF/ggvis渲染图形及交互/[前端设计自动生成脚本](https://www.cssmatic.com/gradient-generator#%27\-moz\-linear\-gradient\%28left\%2C\%20rgba\%28248\%2C80\%2C50\%2C1\%29\%200\%25\%2C\%20rgba\%28241\%2C111\%2C92\%2C1\%29\%2050\%25\%2C\%20rgba\%28246\%2C41\%2C12\%2C1\%29\%2051\%25\%2C\%20rgba\%28240\%2C47\%2C23\%2C1\%29\%2071\%25\%2C\%20rgba\%28231\%2C56\%2C39\%2C1\%29\%20100\%25\%29\%3B%27)/以及对大型shiny讨论理解|
| [R:使用Arrow包对10亿行出租车数据可视化](https://blog.djnavarro.net/posts/2022-08-23_visualising-a-billion-rows/)                                |  ------------------------------------                        |
| [张丹个人blog-算法]为王系列(http://blog.fens.me/series-algorithm/) |  张丹是以为擅长Java/R/Hadoop生态的数据科学家，现在金融科技领域从事开发、数据分析工作 |
| [R 46种距离算法表示]()                                |  ------------------------------------                        |
| []()                                |  ------------------------------------                        |
| []()                                |  ------------------------------------                        |
| []()                                |  ------------------------------------                        |
| **深度学习方向**                    |                          |
| [百度的Paddelpaddle框架](https://aistudio.baidu.com/aistudio/course/list/1/4) |  Paddlepaddle机器学习/深度学习进阶学习                        |
| [来自咖喱国的Marktechpost网站](https://www.marktechpost.com/) | 该科技网站将内容归纳为ML/DL/AI/NLP等内容，主要通过阅读文件后总结内容，对AI领域最新的研究进行简短介绍，并附有论文地址                        |
| []()                                |  ------------------------------------                        |
| []()                                |  ------------------------------------                        |




### 常用package及其介绍

| 常用包                                                       | 用途介绍                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [pacman](https://www.rdocumentation.org/packages/pacman/versions/0.5.1) <br>[pacman](https://cloud.tencent.com/developer/article/1655756) | package管理  |
| [rlang](https://www.rdocumentation.org/packages/rlang/versions/1.0.4) | rlang 是用于使用 R 编程的框架和 API 的集合  |
| [base]() | **base**是R包基础核心内容，囊括了数据转换、处理、文本匹配等内容，help(package = 'base')命令查看函数，其中有不少好用的函数 |
| [stats]() | **stats**是R包基础核心内容，囊括了数据转换、处理、文本匹配等内容，help(package = 'base')命令查看函数，其中有不少好用的函数 |

### 机器学习专题

| 机器学习内容                                                       | 用途介绍                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [LDAbiplots](https://www.r-bloggers.com/2022/08/july-2022-top-40-new-cran-packages/) | 提供工具来提取、探索、分析和可视化数字报纸使用潜在 Dirichlet 和机器学习算法在网络上发布的新闻 |
| [sentiment.ai](https://www.r-bloggers.com/2022/03/better-sentiment-analysis-with-sentiment-ai/) | sentiment.ai助力更优质的情感分析 |
| [Tensorflow数据科学教程](https://datasciencetut.com/best-books-to-learn-tensorflow/) | 学习Python/Tensorflow的最佳书籍推荐 |
| [Yolo算法介绍及物体检测](https://appsilon.com/object-detection-yolo-algorithm/) |                          |
| [Python与数据科学 推荐书籍](https://datasciencetut.com/best-books-on-data-science-with-python/)                                |                          |
| [R 编程语言中的数据科学挑战](https://www.r-bloggers.com/2022/09/data-science-challenges-in-r-programming-language/) | 今天，我们为您提供了五个 R 编程语言的数据科学家庭作业问题，适合那些没有多少先验知识和有几年知识的人。|
| [用加密新闻调查主题模型](https://www.r-bloggers.com/2017/03/investigating-topic-models-with-crypto-news/) | 将Julia的tidytext包通过主图模型实现新闻调查 |
| []()                                |                          |
| []()                                |                          |



### Markdown/Report专题

| **Markdown/Report专题**                                             |                          |
| -----------------------------                                |  ------------------------------------                        |
| [blogdown]()                                                 |  搭建个人博客                        |
| [knitr]()                                                    |  优雅、灵活和快速的生成动态报告，将R与Tex、Markdown、html相结合 |
| [rmakrdown]()                                                | 在markdown文档中嵌入R代码，最终以html/pdf/word/beamer等方式呈现代码及其结果                          |
| [Markdown](https://www.imooc.com/wiki/markdownlesson/markdowntodolist.html) | Markdown高阶语法，包含进阶、流程图、时序图、状态图、背景色、字体、字号等内容 |
| [kable]()                                                    |  markdown中展示原始数据                        |
| [kableExtra]()                                               |  markdown中展示原始数据                        |
| [DT]()                                                       |  markdown中展示原始数据，通过[DT.option = list(...)](https://www.r-bloggers.com/2014/02/using-dates-and-times-in-r/)对表格进行更多的调整  |
| [bookdown]()                                                 |  将知识总结汇总为bookdown内容，附[bookdown](https://www.bookdown.org/)官网，web中含有大量成熟的R书籍    |
| [坚果云Markdown高阶语法](https://markdown.jianguoyun.com/skill) | Markdown高阶语法，包含进阶、流程图、时序图、状态图、背景色、字体、字号等内容 |
| [Advanced R Markdown Workshop](https://arm.rbind.io/)        |  为期2天的高级Markdown工作坊，第一天介绍flexdashboard/xaringan/bookdown/blogdown，第二天介绍knitr和pandoc/rticles/及其跨语言性能  |
| [markdown1在线测试](https://markdown-it.github.io/) <br>[markdown2](https://md.mzr.me/) | 在线测试小工具。markdown1()，markdown2(不一样的list格式) |
| [xaringan]()                                |  Yihui出版的包，使用Rmarkdown写类似PPT一样的幻灯片进行数据分析报告。                       |
| [WrapRmd](https://github.com/tjmahr/WrapRmd)  |  整理markdown文件段落                        |
| [imageclipr](https://www.zhihu.com/question/398418315/answer/1467917011)      |  复制图片至rmarkdown文档中                        |
| [regexplain](https://www.zhihu.com/question/398418315/answer/1467917011)      |  调试正则表达式，谁用谁知道                        |
| [regex101.com](https://regex101.com/)      |  stackoverflow推荐正则表达                        |
| [regexplain](https://www.zhihu.com/question/398418315/answer/1256685676)      |  ------------------------------------             |
| [mermaid 语法绘制UML/甘特图/流程图等](https://zhuanlan.zhihu.com/p/172635547) |  ------------------------------------                        |
| [Markdown数学公式](http://onceoa.com/wiki/view/markdown/katex) | Markdown常用数学表达符号一览，行内公式用$math_expr$，另起一行公式用$$math_expre$$|
| [Markdown数学公式(在线测试)](https://latex.codecogs.com/eqneditor/editor.php) |  ------------------------------------                        |
| []()                                |  ------------------------------------                        |
| -----------------------------                                |  ------------------------------------                        |

### Shiny专题

| **Shiny专题**                                                |                                                              |
| -----------------------------                                |  ------------------------------------                        |
| [shinydashboard](http://rstudio.github.io/shinydashboard/structure.html) | ------------------------------------                         |
| [reactlog](https://mastering-shiny.org/reactive-graph.html)  | 画shiny app的响应图,reactlog::reactlog_enable() shiny::reactlogShow() |
| [shinyloadtest](https://mastering-shiny.org/performance.html) | 模拟许多人同时使用您的应用程序                               |
| [promises](https://rstudio.github.io/promises/)              | 异步编程是用来提高可伸缩性和响应能力的一种技术，仅适用于shiny这样的R Web应用程序 |
| [shinyWidgets::shinyWidgetsGallery()]()                       | shiny控件集合，可以随时参考所需要的控件                         |
| [Shiny 中的各种主题和 UI 插件](https://cloud.tencent.com/developer/article/1749336) | 该文章从shiny主题和UI组间角度总结了常用的内容，其中主题(通用主题,仪表盘主题,移动端主题,自定义主题)，UI组件(Bootstrap,文件输入,特殊输入,加载动画,反馈/警报/通知,创建新手指引/帮助文档,剪贴板,取色器,编辑器,表格展示,创建抽屉,实现拖拽操作,文本,图片/音频/视频,嵌入 PDF,Icon Font,图像比较,代码比较,日历) |
| [使用CSS优化shiny界面，更美观](https://shiny.rstudio.com/articles/css.html) | CSS(Cascading Style Sheets,简称‘’层叠样式表)是一门修改文本样式的计算机语言                        |
| []()                                |  ------------------------------------                        |
| []()                                |  ------------------------------------                        |
| -----------------------------                                |  ------------------------------------                        |
| -----------------------------                                |  ------------------------------------                        |


### Statistical专题

| **Statistical专题**                                          |                          |
| -----------------------------                                |  ------------------------------------                        |
| [flextable]()                                                |  模型系数输出为表格形式                        |
| [sjPlot](https://strengejacke.github.io/sjPlot/articles/tab_mixed.html) |  用于绘制线性模型、边际效应、混合效应模型的参数估计图/统计系数表，常用plot_model/plot_scatter |
| [gtsummary]()                                                | 将分析的结果整理成表格输出                         |
| [broom]()                                                    |  (常用)通过tidy/augment/glance获取模型参数估计值、误差项、P.value|
| [broom.mixed]()                                              |   ()主要用于线性混合模型提取参数估计值等统计量                       |
| [effectsize](https://easystats.github.io/effectsize/reference/index.html) |  F/t等检验统计量的相互转换，大学生初次接触检验统计量时常会用到                        |
| [dotwhisker::dwplot]()                                |  Julia用该函数绘制统计量的置信区间点图                        |
| [performance]()                                | 检测多重共线性                        |
| -----------------------------                                |  ------------------------------------                        |


### 数据处理专题

| **数据处理专题**                                             |                          |
| -----------------------------                                |  ------------------------------------                        |
| [`data.table`](https://atrebas.github.io/post/2019-03-03-datatable-dplyr/) |高效数据处理结构，运行速度优于data.frame，是R中除了分布式处理方式中最快的，处理GB级数据  |
| [tidyfst](https://hope-data-science.github.io/tidyfst/) <br>  [tidyfst](https://hope-data-science.github.io/tidyfst/)   | 相比tidyverse有更高效的数据读取、处理、保存功能,但由于是基于fst速度读取，基于data.table的数据处理，所以是目前单机GB级数据最高效的处理方式|
| [fst](https://cran.r-project.org/web/packages/fst/index.html) <br> [fst](http://www.fstpackage.org/#:~:text=The%20fst%20package%20for%20R%20provides%20a%20fast%2C,full%20random%20access%2C%20both%20in%20column%20and%20rows.) | R中目前最快的数据读取和导出方式，优于read.csv/feather/vroom/，tidyfst、data.table的数据读写功能依赖于该包| 
| [tidyvese](https://www.tidyverse.org/)                       | 以简洁、高效、易读的语法对tibble结构数据处理                 |
| [tidyselect]()                       |                  |
| [arrow](https://cran.r-project.org/web/packages/arrow/index.html)|  基于C++ Arrow库接口的数据读写功能，但速度低于fread|
| [arrow::read_feather()/write_feather()]()                    | 高性能读取                                                   |
| [feather]()                                                  |                                                              |
| [vtoom::vroom()]()                                           | 高性能读取，相比fread()慢一点，但也被用于读取GB级数据  |
| [collapse](https://sebkrantz.github.io/collapse/)            | 基于C/C++的包，用于R中的数据转换和统计计算；超链接中含有其介绍，以及它与data.table等其他类似包的比较                                                   |
| [dtplyr](https://zhuanlan.zhihu.com/p/543252519)             |  只有dtplyr::lazy_dt()这个函数，用于将dplyr语句翻译为data.table语法，提高处理速度|
| [glue]()                                                     | 提供了一种从数据创建字符串的强大方法                         |
| [reticulate]()                                               | 在R中提供了python接口，可轻松调用Python    |
| [magrittr]()                                                 | 提供管道运算符%>%链接命令的机制    |
| [lubridata]()                                                | 方便地做日期/时间操作，各种标准化时间和时区的处理  |
| [janitor-Rblogger介绍](https://www.r-bloggers.com/2020/08/r-packages-janitor-for-data-cleaning/)  <br> [janitor-示例](https://nexacu.com/insights-blog/the-r-janitor-package/)                               |  对数据进行初步清理，比如整理杂乱的变量名clean_names()，发现数据中的重复值,get_dupes()查找某列的重复值  |
| [effectsize ]()                                |  ------------------------------------                        |
| [slider]()                                |  (推荐)求滑动平均值(油管上Julia slide window)                        |
| [tidylog]()                                |  记录tidyverse处理流，通过warning提示数据处理过程中去除的数据 |
| [lubridate]()                                |  (推荐)专门用于处理日期数据                        |
| []()                                |  ------------------------------------                        |
| []()                                |  ------------------------------------                        |


### 文本处理/挖掘/爬虫专题

| **文本处理/挖掘/爬虫专题**                                             |                                                              |
| -----------------------------                                |  ------------------------------------                        |
| [tidytext](https://www.jumpingrivers.com/training/course/r-text-mining-tidyverse-stringr-tidytext/) | Julia开发专门来做文本挖掘的，提供tf-idf/主题模型/情感分析等内容  |
| [stringr](https://stringr.tidyverse.org/)                    | 字符串/文本处理，(base中的文本处理函数)[https://www.jianshu.com/p/5bd0846b0d7d],其中文表达为[`[\\p{Han}]`](https://zhuanlan.zhihu.com/p/376151000)  |
| [httr]()                                |  ------------------------------------                        |
| [xml2]()                                |  ------------------------------------                        |
| [rvest]()                                |  实现静态页面爬取功能；html表格抓取;html_encoding_guess()判断网页文本编码格式 |
| [unpivotr](https://github.com/nacnudus/unpivotr) |  实现对多层次表头的xlsx表格进行正确读取（不丢失表头信息）                        |
| [htmltab](https://github.com/crubba/htmltab) |  (年久失修，很久没维护了)允许对多层次表头的html表格的进行指定抓取（不丢失表头信息）                        |
| [RSelenium]()                                |  爬取动态页面时常用,可结合(Docker部署爬虫系统)[https://www.jianshu.com/p/eeeace34d20c] |
| [Rwebdriver]()                               |  支持动态页面爬取功能 |
| [W3C正则表达式在线工具](https://www.w3cschool.cn/tools/index?name=reg)     |  w3cschool正则表达式，有少量常用字符匹配说明，[w3c正则介绍](https://www.w3cschool.cn/regexp/tfua1pq5.html)                        |
| [runoob菜鸟教程在线工具](https://c.runoob.com/front-end/854/) |  界面更加简洁                        |
| [MK正则表达式在线工具](https://www.mklab.cn/utils/regex) |  有html注释的正则表达式  |
| [taskscheduleR](https://cran.r-project.org/web/packages/taskscheduleR/readme/README.html) |  让计算机自动定时运行脚本，例如基于所有网站的数据库每个月都要更新       |
| -----------------------------                                |  ------------------------------------                        |


[爬虫技术](https://rworld.huhuaping.com/scraping.html)：流程：Docker部署 > 正则表达式 > RSelenium动态抓取 > APACHA人机验证 > html表格抓取

### 画图专题

| **画图专题**                                                 |                          |
| -----------------------------                                |  ---------------------|
| [ggplot2函数介绍](https://rdocumentation.org/packages/ggplot2/versions/3.3.6) <br>  [ggplot2在tidyverse官网介绍](https://ggplot2.tidyverse.org/) | R的ggplot2画图功能相比Python美观且实用不少  |
| [GGally官网](https://ggobi.github.io/ggally/)                | GGally::ggpairs()用来绘制多个变量分布及其二元关系;ggcoef()模型[系数可视化](https://blog.csdn.net/weixin_41346050/article/details/96903479)图;ggtable()生成交叉表(列联表);初步感觉其核心在于ggmatrix()将将图形汇总成矩阵形式 |
| [ggsci]()                                |  通过scale_***_color(scal_npg_color)调整颜色； |
| [ggtext](https://cloud.tencent.com/developer/article/1629499) | (推荐)该ggtext软件包为ggplot2 提供了富文本（基本HTML和Markdown）支持。 富文本可用于图注解（图标题，字幕，标题，轴标签，图例等） |
| [ggrepel](http://www.sthda.com/english/wiki/ggplot2-texts-add-text-annotations-to-a-graph-in-r-software)  |  在ggplot图中添加文本标签(可能遇到重叠的情况，通过position_nudge_repel调整文本的具体位置) |
| [patchwork]()                                | 拼接多个ggplot图                        |
| [gridExtra](https://www.jianshu.com/p/c154ca35530b) | 拼接多个ggplot图;因为R base中par()和layout()对多个ggplot对象排版无效                      |
| [esquisse]()                        | (不使用，仅适用于初学者/只想画图的人)免代码ggplot生成器，鼠标点点点就能在R-studio里面画图                         |
| [ggThemeAssist]()                   | (不使用，但是对于初学者而言，有助于了解了解ggplot画图有哪些内容)调节ggplot对象,免代码调节ggplot的细节参数,比如字体，背景颜色等等。选择绘图代码后，Addins > ggplot Theme Assistant |
| [ggstatsplot]()                     |  绘制带有统计检验性的图表，可用于文章发表  |
| [gtable]()                          | gtable包用于处理ggplot2图像,底层处理图像  |
| [ggridges](https://cran.r-project.org/web/packages/ggridges/vignettes/introduction.html) | (用过)可视化脊线图的包，对可视化时间或空间分布的变化非常有效  |
| [eulerr](https://www.jianshu.com/p/3013e7710f0a)  | (推荐尝试)有在线shiny绘图，画图比VennDiagram好看点                        |
| [ggcor]()                                | 相关性可视化(下三角矩阵图) |
| [treemapify和ggpol包]()                                | (没用过)矩形树图 |
| [gganimate]() | 将ggplot2包的可视化图像转化成动画的包 |
| [ggfortify]() | (推荐)包含autoplot()函数，可以只用一行代码就可对主成分分析、聚类分析、回归分析、时间序列分析等方法的统计结果，以ggplot2的风格进行可视化，大大提高了数据分析的效率    |
| [缺失值可视化包VIM和naniar](http://naniar.njtierney.com/index.html) | 其中naniar包的缺失值可视化图像是基于ggplot2包的，所以可以将图像更好的和ggplot2包结合，对图像进行调整。在Julia的tidymodel视频课程中也使用naniar函数    |
| [处理缺失数据的高级方法](https://jmxsy2016.github.io/Data-Science-and-Economics/Statistics/%E5%A4%84%E7%90%86%E7%BC%BA%E5%A4%B1%E6%95%B0%E6%8D%AE%E7%9A%84%E9%AB%98%E7%BA%A7%E6%96%B9%E6%B3%95.html) | (推荐)通过示例介绍缺失值的类型、识别缺失值、探索缺失值 |
| [mice]()                                |  (推荐)填补缺失值常用包 |
| [cowplot](https://mp.weixin.qq.com/s?__biz=MzI1NjUwMjQxMQ==&mid=2247486838&idx=2&sn=21ee1c8b683e7d27373f3e1f40901428&chksm=ea24f292dd537b843db330a88161ce6f89227418f64515164615c3f63721df6464b6d91a2b1a&scene=21#wechat_redirect) |  用R添加水印               |
| [tidyHeatmap](https://github.com/stemangiola/tidyHeatmap) | (推荐)该包继承tidyverse简洁的语法格式，用于绘制热图  |
| [ComplexHeatmap]()                                | 在生信领域常被用于绘制热图，通过BiocManager::install()方式安装生信关联包; [complexHeatmap简介 - 百迈客生物科技](http://www.biomarker.com.cn/archives/16110)  |
| []()                                | ggplot2::annotate()添加注释信息[ggplot2绘图细节调整视频教学](https://space.bilibili.com/594999645/video?tid=0&page=1&keyword=&order=pubdate)  |
| [gganimate](https://zhuanlan.zhihu.com/p/110156607) | (推荐)支持生成动态图形，可用于报告中呈现动态结果   |
| [echarts4r](https://zhuanlan.zhihu.com/p/111755894) | echarts4r包调用了百度的Echarts可视化工具的API,构建常规交互式绘图包  |
| [ggbreak](https://cran.r-project.org/web/packages/ggbreak/vignettes/ggbreak.html#feature-11-compatible-with-dual-axis) | (基本不使用)其功能类似于坐标轴的数值转换(log/exp)等，当分组绘制柱状图时，柱子的垂直差距过大，但不想跟对坐标轴/y值数值转换，此时只去柱状图垂直两端的柱子和y轴信息，可更直观地比较   |
| []()                                |   |
| []()                                |   |
| []()                                |   |



### 数据库连接与处理

| **数据库连接与处理**                                                 |                          |
| -----------------------------                                       |  ---------------------|
| [DBI]()| R连接数据库的工具 |
| [bdplyr]() | ?对数据库内的数据进行处理 |
| [RODBC](https://www.zhihu.com/question/21792740?sort=created) |  连接ODBC数据库接口  |
| [RSQLite ](https://www.zhihu.com/question/21792740?sort=created)  |                          |
| []()                                |  ------------------------------------                        |


| **性能与R包开发** | ---------------------- |
| ----------------- |  --------------------- |
| [profvis](https://mastering-shiny.org/performance.html)      | 分析应用程序，识别R代码慢速部分                              |
| [profvis](https://rstudio.github.io/profvis/) | 在开发包/shiny过程中，交互式查看代码性能，帮助coder精准优化代码性能 |
| [roxygen2](https://www.tidyverse.org/blog/2022/05/roxygen2-7-2-0/) | roxygen2 允许您编写特殊格式的 R 注释，生成 R 文档文件 ( man/*.Rd) 和NAMESPACE文件|
| [pkgdown](https://www.tidyverse.org/blog/2021/12/pkgdown-2-0-0/)  | pkgdown 旨在使您可以快速轻松地为您的软件包构建网站 |
| [usethis](https://www.tidyverse.org/blog/2020/12/usethis-2-0-0/) | usethis 是一个促进 R 项目创建和开发的交互式工作流的包。它主要专注于简化日常的包开发，但它的许多功能对于非包项目也很有用 |
| [OOP in R(S3/S4/R6)](https://www.jumpingrivers.com/training/course/oop-s3-s4-r6-classes/)|                                                               |
| [jsonlite](https://zhuanlan.zhihu.com/p/27662104) |  json是当下非常流行的数据交换格式，该包提供了json数据读取、导出及与R数据类型双向转换的功能 |
| [testthat]()                                |  扩展包自动测试                        |
| [pipeR]() |  (不使用)自己写的高性能、低损耗、分工明确的管道操作（pipeline operator）扩展包，使得数据变换流程化 |
| [devtools](https://www.rdocumentation.org/packages/devtools/versions/2.4.4) | 扩展包开发必备，在线安装托管的扩展包，检查扩展包是否符合CRAN标准等等 |
| [testthat]()                   |  (没用过)扩展包自动测试  |
| [Deepdep](https://dominikrafacz.github.io/deepdep/index.html) | (作为R包开发者很有用)R包的依赖包可视化工具                        |
| [gWidgets](https://zhuanlan.zhihu.com/p/115068286) | 交互式程序控制功能，在代码的重要节点，返回控件信息请求用户判断是否进行下一步；gWidgets包的ginput函数                          |
| []()                   |  ------------------------------------                        |
| []()                   |  ------------------------------------                        |

| **数值计算** | ------------------------------------                        |
| ----------------- | ------------------------------------                        |
| [rootSolve]()                   |  非线性方程求根、ODE均衡状态解 |
| [Rsolnp]()                      |  非线性优化  |
| [sde]()                   | 随机微分方程模拟和统计推断 |
| [KernSmooth]()                   | 非参数平滑与分布估计  |
| [stats4]()                   | (推荐尝试使用)可用来方便地做MLE估计 |
| []()                   |  ------------------------------------                        |
| []()                   |  ------------------------------------                        |
| -----------------------------                                |  ------------------------------------                        |


### 空间数据

| **空间数据**                                                 |                          |
| -----------------------------                                |  ------------------------------------                        |
| [sf](https://r-spatial.github.io/sf/index.html)                                |  ------------------------------------                        |
| [tmap]()                                |  ------------------------------------                        |
| [leaflet](http://rstudio.github.io/leaflet/) |  leaflet是交互式地图中最受欢迎的JavaScript库之一，常用于shiny/markdown文档交互;可参考[Tom Jenkins的示例介绍](https://tomjenkins.netlify.app/tutorials/r-leaflet-introduction/) |
| [Geocomputation with R](https://geocompr.robinlovelace.net/index.html)   |  ------------------------------------        |
| [Apllied Spatial Data Analysis with R]()    |  ------------------------------------                        |
| [Spatial Mivrosimulation with R](https://spatial-microsim-book.robinlovelace.net/index.html)  |                          |
| [baidumap]()                   |  (没用过)devtools::install_github('badbye/baidumap') library(baidumap) options(baidumap.key = '百度地图API') getCoordinate("江苏省南京市",formatted=T) longtitude   latitude 118.80242   32.06465 查询城市经纬度 |
| [ggspatial](https://zhuanlan.zhihu.com/p/151400985)                   |  ggplot2空间绘图，layer_spatial()专门用于画栅格数据，[ggspatial官方介绍](https://paleolimbot.github.io/ggspatial/articles/ggspatial.html)                        |
| [biscale](https://github.com/chris-prener/biscale)                   |  空间二元主题绘图(图形美观好看)                        |
| []()                   |  ------------------------------------                        |
| []()                   |  ------------------------------------                        |
| -----------------------------                                |  ------------------------------------                        |

### 大数据处理

| **大数据处理**                                                 |                          |
| -----------------------------                                |  ------------------------------------                        |
| [sparklyr]()                                |  [data.table和Sparklyr分布式运算比较](https://zhuanlan.zhihu.com/p/374434258)   |
| [parallel](https://zhuanlan.zhihu.com/p/376151000) |  [foreach](https://zhuanlan.zhihu.com/p/110107815)等支持对大数据/多文件的并行运算函数                        |
| -----------------------------                                |  ------------------------------------                        |


### 其他

| **其他**                                                 |                          |
| -----------------------------                                |  ------------------------------------                        |
| [utils::readClipboard()](https://www.r-bloggers.com/2018/11/windows-clipboard-access-with-r/) |  R 和 Clipboard的数据相互导入 |
| [reprex](https://www.tidyverse.org/blog/2021/04/reprex-2-0-0/) <br> [reprex](https://www.zhihu.com/question/398418315/answer/1256685676)| 把代码块变成一个可‘reproducible example’，常用语提问，可以让别人复现你的代码(错误)；用于github/stackoverflow提问环节 |
| [datapasta](https://milesmcbain.github.io/datapasta/)|  (好用,推荐使用)加载包后，可直接从csv/excel/html文档中直接拷贝数据，RStudio > Addins > 'paste as tribble';可自定义快捷键;dt_paste()比较实用 |
| [clipr::write_clip(data)](https://statisticsglobe.com/copy-data-frame-clipboard-r#:~:text=This%20example%20illustrates%20how%20to%20copy%20a%20data,as%20shown%20below%3A%20clipr%20%3A%3Awrite_clip%28data%29%20%23%20Apply%20write_clip)| 复制代码输出结果，方便用于提问，让读者看到清楚地数据结构等信息|
| [showtext](https://cran.r-project.org/web/packages/showtext/vignettes/introduction.html)  |  在图例中添加不同的字体font_family，可[解决中文乱码问题](https://www.jianshu.com/p/cfe2ed736c6d),参考[ggplot2 Gallary](https://r-graph-gallery.com/custom-fonts-in-R-and-ggplot2);[参考思路，了解showtext和其他Graphic Device](https://r-coder.com/custom-fonts-r/) |
| [`Discover and install useful RStudio addins`](https://github.com/daattali/addinslist)                                |  Github中总结的RStudio好用的插件               |
| [here/rstudioapi](https://zhuanlan.zhihu.com/p/268306337)  |  通过vignette('here')查看更多信息，方便快捷的获取目标文件路径;rstudioapi::getActiveDocumentContext()$path获取当前脚本完整路径信息 |
| [ProjectTemplate](http://projecttemplate.net/index.html) |  (没用过)建立结构化的数据分析项目，给每个数据分析单独建一个项目，促进数据分析的可再生性                        |
| [todor]()                                |  (暂未使用过)这个包特别在专门针对你代码中的comment 进行归类，使你的代码更加结构化。可以通过R-studio的插件来使用这个包  |
| [SRAdb]()                                |  下载原始测序数据  |
| [TCGA工具](https://www.jianshu.com/p/023a26e94282) |  GDCRNATools是一个R包，提供标准的，易于使用和全面的管道，用于下载，组织和综合分析GDC门户中的RNA表达数据，重点是解读癌症中lncRNA-mRNA相关的ceRNA调控网络 |
| [qs](https://zhuanlan.zhihu.com/p/147643442) |  qs::qsavem()存储多个R对象(结构)，                        |
| [vitae]()                                |  (?)制作个人简历用途，可重复利用                        |
| []()                                |  ------------------------------------                        |



# 个人收集的免费R学习资源

| [个人收集的免费R学习资源](https://jingtailiu.shinyapps.io/learnr-resource/)  |  ------------------------------------   |
| -----------------------------                                |  ------------------------------------  |
| [`TidyTuesday`](https://github.com/rfordatascience/tidytuesday) |  `TidyTuesday`      |
| [Available CRAN Packages](https://cloud.r-project.org/web/packages/available_packages_by_name.html#available-packages-B) | 涵盖Cran中已收纳的包 |
| [tidytuesdayR](https://cloud.r-project.org/web/packages/tidytuesdayR/index.html) | R社区TidyTuesday项目，旨在让不同领域的R专家在实践中使用R，推广R，让R语言爱好者更好的了解R语言生态 |
| []()                                |  ------------------------------------                        |
| []()                                |  ------------------------------------                        |



> `R` [tidyfst vs pandas:文章列表(持续更新)](https://zhuanlan.zhihu.com/p/230798879)

### 相关blog资料，例如tidyverse/tidymodels/mlr3等

- [& #9744][RStudio Cheatsheet](https://www.rstudio.com/resources/cheatsheets/)
- [& #9744][tidyverse](https://www.tidyverse.org/blog/)
- [& #9745][tidyverse](https://www.tidyverse.org/blog/)
- [x][tidyverse](https://www.tidyverse.org/blog/)
- [& #10004][tidyverse](https://www.tidyverse.org/blog/)
- [& #10004][jumpingrivers,R/Python最新信息](https://www.jumpingrivers.com/blog/)
- [x][JLaw's R Blog 每周一篇R应用文章](https://jlaw.netlify.app/)
- [于淼 《现代科研指北》](https://yufree.cn/cn/2022/08/29/sciguide-on-market/)
- [科研工具及技能表推荐](https://github.com/MLNBA-Lab/DataCollection2Public/blob/1ece83ca3d1e2009cc5c8c25b7cdf8100fae47bf/%E7%A7%91%E7%A0%94%E6%96%B9%E6%B3%95%E5%8F%8A%E5%B7%A5%E5%85%B7/%E7%A7%91%E7%A0%94%E5%B7%A5%E5%85%B7%E5%8F%8A%E6%8A%80%E8%83%BD%E8%A1%A8%E6%8E%A8%E8%8D%90.md)
- [Awosome Network Analysis- Github Awosome系列](https://github.com/briatte/awesome-network-analysis)
- [(R按行处理)Row-oriented workflows in R with the tidyverse](https://github.com/jennybc/row-oriented-workflows#readme)
- [旋涡周报(专注自动化、分布式系统和存储)](https://xuanwo.io/reports/)
- [高策周报-主要关注在云原生和 AI infra 领域。云原生机器学习基础设施开源项目 Kubeflow 社区 Co‑chair & Tech Lead，曾经全球贡献第二的贡献者。](https://gaocegege.com/Blog/featured/)

# 书籍推荐、理由及完成进度
* **绘图**
  1. [The Grammar of Graphics](https://www.amazon.com/Grammar-Graphics-Statistics-Computing/dp/0387245448/ref=as_li_ss_tl)开发的，它是一套用来描述创建图形的系统
  2. [ggplot2 gallery](http://r-graph-gallery.com/ggplot2-package.html): 包含了大量使用ggplot2画图示例，能广泛满足各种画图基本需求
  3. [ggplot2 gallery-extension](https://exts.ggplot2.tidyverse.org/gallery/): ggplot2画图拓展，相比ggplot基础内容更丰富
  4. [The R Graphics Cookbook](https://r-graphics.org/):这本书能够解决大部分的画图问题
  5. [ggplot2: Elegant Graphics for Data  Analysis](https://ggplot2-book.org/): 在掌握ggplot2画图的基础后，它能帮助你理解ggplot2底层理论知识，了解图层是如何拼接到一起
  6. []()

* **R性能提高**
  1. [Advanced R](https://adv-r.hadley.nz/): 内容偏宏观(底层)，书本遵从了函数式编程、面向对象OOP特性、Metaprogramming以及代码调试的渐进结构；`回顾S3/S4/R6`类的内容
* **文本挖掘**
  1. [Text Mining with R](https://www.tidytextmining.com/index.html)：对于
  2. [Text Mining with R(中文版)](https://text-mining-with-r-a-tidy-approach.netlify.app/tidytext.html)：对于
  3. [《Text Mining in Practice with R》]()：Julia Silge的书主要介绍了文本处理的基本内容，内容不够深刻，(而Kwartler写的本书更贴合实际，并且介绍了不少数据分析形成的误区)[https://zhuanlan.zhihu.com/p/138495809]
  4. [Supervised Machine Learning for Text Analysis in R](https://smltar.com/)：有监督学习在文本分析的应用----基于R语言
  5. [Text Mining for Social Scientists](https://bookdown.org/f_lennert/text-mining-book/)：社会科学家中的文本挖掘
* **空间**
  1. [空间广义线性混合效应模型及其应用](https://bookdown.org/xiangyun/Thesis-Template-Bookdown/)：by黄湘云
  2. [Geocomputation with R]()
  3. [Apllied Spatial Data Analysis with R]()
  4. [Spatial Mivrosimulation with R]()
  5. [Doing Bayesian Data Analysis in brms and the tidyverse](https://bookdown.org/content/8ba612b7-90f2-4ebc-b329-0159008e2340/)：基于brms和tidyverse的贝叶斯应用
* **机器学习**
  1. [Tidy Modeling with R](https://www.tmwr.org/)：tidymodels框架
  2. [精通特征工程(Python)]()
  3. [A Bayesian Course with Examples in R and Stan](https://xcelab.net/rm/statistical-rethinking/)：使用R/Stan教授完整Bayesian课程,并附有R/Stan/Julia示例[Youtube视频课程](https://www.youtube.com/playlist?list=PLDcUM9US4XdMROZ57-OIRtIK0aOynbgZN)
  3. []()
  3. []()

| 阅读书籍                          | 进度                             |
|-----------------------------------|-------------------------------------|
|                           |                              |

