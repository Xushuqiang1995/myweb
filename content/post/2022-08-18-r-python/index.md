---
title: r-python包/blog/书籍介绍
author: shuqiang
date: '2022-08-18'
output:
  toc: true
slug: []
categories:
  - R
  - Python
tags:

subtitle: '主要整理了R/Python常用包详细介绍、书籍、blog信息'
description: '主要整理了R/Python常用包详细介绍、书籍、blog信息'
image: ''
---

> 主要介绍文章
> 1. 将R内容按照用途分为若干个专题，其一介绍各个包的用途及包文档说明链接，在第二列队包进行简要介绍，且应该给出相应的代表性函数。
> 2. R实用的资源/推荐书和理由/blog等，保持学习的冲劲，每个领域1-2本书就完全足够了，不在多，而在精，如果能读完，最好能进行一个比较
> 3. 学习进度栏，每次完成一本书/项目，记录完成时间和具体项目(超链接)
> | []()                                                      |  []()                                                       |
> | []() | []() |

# R

### 常用package及其介绍

| 常用包                                                       | 用途介绍                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [pacman](https://www.rdocumentation.org/packages/pacman/versions/0.5.1) <br>[pacman](https://cloud.tencent.com/developer/article/1655756) | package管理  |
| [devtools](https://www.rdocumentation.org/packages/devtools/versions/2.4.4) | R包开发 |
| [rlang](https://www.rdocumentation.org/packages/rlang/versions/1.0.4) | rlang 是用于使用 R 编程的框架和 API 的集合  |
| [base]() | **base**是R包基础核心内容，囊括了数据转换、处理、文本匹配等内容，help(package = 'base')命令查看函数 |
| [stats]() | **stats**是R包基础核心内容，囊括了数据转换、处理、文本匹配等内容，help(package = 'base')命令查看函数 |
| [Available CRAN Packages](https://cloud.r-project.org/web/packages/available_packages_by_name.html#available-packages-B) | 涵盖Cran中已收纳的包 |
| [tidytuesdayR](https://cloud.r-project.org/web/packages/tidytuesdayR/index.html) | R社区TidyTuesday项目，旨在让不同领域的R专家在实践中使用R，推广R，让R语言爱好者更好的了解R语言生态 |

### Markdown/Report专题

| **Markdown/Report专题**                                             |                          |
| -----------------------------                                |  ------------------------------------                        |
| [blogdown]()                                                 |  搭建个人博客                        |
| [knitr]()                                                    |  优雅、灵活和快速的生成动态报告，将R与Tex、Markdown、html相结合                        |
| [rmakrdown]()                                                | 在markdown文档中嵌入R代码，最终以html/pdf/word/beamer等方式呈现代码及其结果                          |
| [Markdown](https://www.imooc.com/wiki/markdownlesson/markdowntodolist.html) | Markdown高阶语法，包含进阶、流程图、时序图、状态图、背景色、字体、字号等内容 |
| [kable]()                                                    |  markdown中展示原始数据                        |
| [kableExtra]()                                               |  markdown中展示原始数据                        |
| [DT]()                                                       |  markdown中展示原始数据                        |
| [bookdown]()                                                 |  将知识总结汇总为bookdown内容，附[bookdown](https://www.bookdown.org/)官网，web中含有大量成熟的R书籍    |
| [坚果云Markdown高阶语法](https://markdown.jianguoyun.com/skill) | Markdown高阶语法，包含进阶、流程图、时序图、状态图、背景色、字体、字号等内容 |
| [Advanced R Markdown Workshop](https://arm.rbind.io/)        |  为期2天的高级Markdown工作坊，第一天介绍flexdashboard/xaringan/bookdown/blogdown，第二天介绍knitr和pandoc/rticles/及其跨语言性能  |
| -----------------------------                                |  ------------------------------------                        |

### Shiny专题

| **Shiny专题**                                                |                                                              |
| -----------------------------                                |  ------------------------------------                        |
| [shinydashboard](http://rstudio.github.io/shinydashboard/structure.html) | ------------------------------------                         |
| [reactlog](https://mastering-shiny.org/reactive-graph.html)  | 画shiny app的响应图,reactlog::reactlog_enable() shiny::reactlogShow() |
| [shinyloadtest](https://mastering-shiny.org/performance.html) | 模拟许多人同时使用您的应用程序                               |
| [profvis](https://mastering-shiny.org/performance.html)      | 分析应用程序，识别R代码慢速部分                              |
| [promises](https://rstudio.github.io/promises/)              | 异步编程是用来提高可伸缩性和响应能力的一种技术，仅适用于shiny这样的R Web应用程序 |
| [shinyWidgets::shinyWidgetsGallery()]()                       | shiny控件集合，可以随时参考所需要的控件                         |
| [Shiny 中的各种主题和 UI 插件](https://cloud.tencent.com/developer/article/1749336) | 该文章从shiny主题和UI组间角度总结了常用的内容，其中主题(通用主题,仪表盘主题,移动端主题,自定义主题)，UI组件(Bootstrap,文件输入,特殊输入,加载动画,反馈/警报/通知,创建新手指引/帮助文档,剪贴板,取色器,编辑器,表格展示,创建抽屉,实现拖拽操作,文本,图片/音频/视频,嵌入 PDF,Icon Font,图像比较,代码比较,日历) |
| [使用CSS优化shiny界面，更美观](https://shiny.rstudio.com/articles/css.html) | CSS(Cascading Style Sheets,简称‘’层叠样式表)是一门修改文本样式的计算机语言                        |
| -----------------------------                                |  ------------------------------------                        |
| -----------------------------                                |  ------------------------------------                        |


### Statistical专题

| **Statistical专题**                                          |                          |
| -----------------------------                                |  ------------------------------------                        |
| [flextable]()                                                |                          |
| [sjPlot]()                                                   |                          |
| [gtsummary]()                                                |                          |
| [broom]()                                                    |                          |
| [broom.mixed]()                                              |                          |
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
| [feather]()                                                    |                                                              |
| [vtoom::vroom()]()                                           | 高性能读取                                                   |
| [collapse](https://sebkrantz.github.io/collapse/)            | 基于C/C++的包，用于R中的数据转换和统计计算；超链接中含有其介绍，以及它与data.table等其他类似包的比较                                                   |
| [dtplyr](https://zhuanlan.zhihu.com/p/543252519)             |  只有dtplyr::lazy_dt()这个函数，用于将dplyr语句翻译为data.table语法，提高处理速度|
| [glue]()                                                     | 提供了一种从数据创建字符串的强大方法                         |
| [reticulate]()                                               | 在R中调用python模块                                                              |
| [magrittr]()                                               | 提供管道运算符%>%链接命令的机制                                                              |
| [lubridata]()                                               | 专门处理日期和时间变量的包                                                              |


### 文本处理专题

| -----------------------------                                |  ------------------------------------                        |
| **文本处理专题**                                             |                          |
| [tidytext](https://www.jumpingrivers.com/training/course/r-text-mining-tidyverse-stringr-tidytext/)|                                                |
| [stringr](https://stringr.tidyverse.org/)                                                  | 字符串/文本处理                                              |
| -----------------------------                                |  ------------------------------------                        |


### 画图专题

| **画图专题**                                                 |                          |
| -----------------------------                                |  ------------------------------------                        |
| [ggplot2函数介绍](https://rdocumentation.org/packages/ggplot2/versions/3.3.6) <br>  [ggplot2在tidyverse官网介绍](https://ggplot2.tidyverse.org/) | R的ggplot2画图功能相比Python美观且实用不少  |
| [GGally官网](https://ggobi.github.io/ggally/)                | GGally::ggpairs()用来绘制多个变量分布及其二元关系;ggcoef()模型[系数可视化](https://blog.csdn.net/weixin_41346050/article/details/96903479)图;ggtable()生成交叉表(列联表);初步感觉其核心在于ggmatrix()将将图形汇总成矩阵形式 |
| -----------------------------                                |  ------------------------------------                        |


- **拓展链接**
- ggplot2是基于[The Grammar of Graphics](https://www.amazon.com/Grammar-Graphics-Statistics-Computing/dp/0387245448/ref=as_li_ss_tl)开发的，它是一套用来描述创建图形的系统
- [ggplot2 gallery](http://r-graph-gallery.com/ggplot2-package.html): 包含了大量使用ggplot2画图示例，能广泛满足各种画图基本需求
- [ggplot2 gallery-extension](https://exts.ggplot2.tidyverse.org/gallery/): ggplot2画图拓展，相比ggplot基础内容更丰富
- []()
- **书**
- [The R Graphics Cookbook](https://r-graphics.org/):这本书能够解决大部分的画图问题
- [ggplot2: Elegant Graphics for Data  Analysis](https://ggplot2-book.org/): 在掌握ggplot2画图的基础后，它能帮助你理解ggplot2底层理论知识，了解图层是如何拼接到一起


### 数据库连接与处理

| **数据库连接与处理**                                                 |                          |
| [DBI]()| R连接数据库的工具 |
| [bdplyr]() | ?对数据库内的数据进行处理 |
| **性能与R包开发**                                                     | ------------------------------------                         |
| [profvis](https://rstudio.github.io/profvis/)                | 在开发包/shiny过程中，交互式查看代码性能，帮助coder精准优化代码性能 |
| [roxygen2](https://www.tidyverse.org/blog/2022/05/roxygen2-7-2-0/) | roxygen2 允许您编写特殊格式的 R 注释，生成 R 文档文件 ( man/*.Rd) 和NAMESPACE文件|
| [pkgdown](https://www.tidyverse.org/blog/2021/12/pkgdown-2-0-0/)  | pkgdown 旨在使您可以快速轻松地为您的软件包构建网站 |
| [usethis](https://www.tidyverse.org/blog/2020/12/usethis-2-0-0/) | usethis 是一个促进 R 项目创建和开发的交互式工作流的包。它主要专注于简化日常的包开发，但它的许多功能对于非包项目也很有用 |
| [OOP in R(S3/S4/R6)](https://www.jumpingrivers.com/training/course/oop-s3-s4-r6-classes/)|                                                               |
| -----------------------------                                |  ------------------------------------                        |


### 空间数据

| **空间数据**                                                 |                          |
| -----------------------------                                |  ------------------------------------                        |
| [sf]()                                |  ------------------------------------                        |
| [tmap]()                                |  ------------------------------------                        |
| [leaflet]()                                |  ------------------------------------                        |
| -----------------------------                                |  ------------------------------------                        |



### 大数据处理

| **大数据处理**                                                 |                          |
| -----------------------------                                |  ------------------------------------                        |
| [sparklyr]()                                |  [分布式处理性能明显由于data.table](https://zhuanlan.zhihu.com/p/374434258)                        |
| -----------------------------                                |  ------------------------------------                        |


### 其他

| **其他**                                                 |                          |
| -----------------------------                                |  ------------------------------------                        |
| [utils::readClipboard()](https://www.r-bloggers.com/2018/11/windows-clipboard-access-with-r/) |  R 和 Clipboard的数据相互导入 |
| [reprex](https://www.tidyverse.org/blog/2021/04/reprex-2-0-0/) <br> [reprex](https://www.zhihu.com/question/398418315/answer/1256685676)| 把代码块变成一个可‘reproducible example’，常用语提问，可以让别人复现你的代码(错误)    |
| [datapasta](https://www.zhihu.com/question/398418315/answer/1467917011)|  从csv/excel/html文档中直接拷贝数据，以data.frame的格式粘贴进RStudio中 |
| [clipr::write_clip(data)](https://statisticsglobe.com/copy-data-frame-clipboard-r#:~:text=This%20example%20illustrates%20how%20to%20copy%20a%20data,as%20shown%20below%3A%20clipr%20%3A%3Awrite_clip%28data%29%20%23%20Apply%20write_clip)| 复制代码输出结果，方便用于提问，让读者看到清楚地数据结构等信息|
| [showtext](https://cran.r-project.org/web/packages/showtext/vignettes/introduction.html)  |  在图例中添加不同的字体font_family                        |
| [WrapRmd](https://github.com/tjmahr/WrapRmd)  |  整理markdown文件段落                        |
| [imageclipr](https://www.zhihu.com/question/398418315/answer/1467917011)      |  复制图片至rmarkdown文档中                        |
| [regexplain](https://www.zhihu.com/question/398418315/answer/1467917011)      |  调试正则表达式，谁用谁知道                        |
| [regexplain](https://www.zhihu.com/question/398418315/answer/1256685676)      |  ------------------------------------                        |
| [taskscheduleR](https://cran.r-project.org/web/packages/taskscheduleR/readme/README.html) |  让计算机自动定时运行脚本，例如基于所有网站的数据库每个月都要更新       |
| [`Discover and install useful RStudio addins`](https://github.com/daattali/addinslist)                                |  Github中总结的RStudio好用的插件               |



# 个人收集的免费R学习资源

| [个人收集的免费R学习资源](https://jingtailiu.shinyapps.io/learnr-resource/)  |  ------------------------------------   |
| -----------------------------                                |  ------------------------------------  |
| [`TidyTuesday`](https://github.com/rfordatascience/tidytuesday) |  `TidyTuesday`      |
| []()                                |  ------------------------------------                        |



> `R` [tidyfst vs pandas:文章列表(持续更新)](https://zhuanlan.zhihu.com/p/230798879)

### 相关blog资料，例如tidyverse/tidymodels/mlr3等

- [& #9744][RStudio Cheatsheet](https://www.rstudio.com/resources/cheatsheets/)
- [& #9744][tidyverse](https://www.tidyverse.org/blog/)
- [& #9745][tidyverse](https://www.tidyverse.org/blog/)
- [x][tidyverse](https://www.tidyverse.org/blog/)
- [& #10004][tidyverse](https://www.tidyverse.org/blog/)
- [& #10004][jumpingrivers,R/Python最新信息](https://www.jumpingrivers.com/blog/)



# 书籍推荐、理由及完成进度

> [Advanced R](https://adv-r.hadley.nz/): 内容偏宏观(底层)，书本遵从了函数式编程、面向对象OOP特性、Metaprogramming以及代码调试的渐进结构；`回顾S3/S4/R6`类的内容

------------------------------------------------------------------------

# Python

### 常用package及其介绍

| 常用包                                                                    | 用途介绍                             |
|-----------------------------------|-------------------------------------|
| [data.table](https://atrebas.github.io/post/2020-06-14-datatable-pandas/) | ------------------------------------ |
| -----------------------------                                             | ------------------------------------ |
| -----------------------------                                             | ------------------------------------ |
