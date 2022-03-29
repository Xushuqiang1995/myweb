---
URL: /2022/03/29/My-first-blogdown/
title: "Blogdown Basic Configuration[^1][^4]"
subtitle: 来自Istio的儿童节礼物
date: "2022/3/29"
author: "Shuqiang"

layout: post
published: true

categories:
- Tech
tags:
- Istio

# output:
#   prettydoc::html_pretty:
#     theme: cayman
#     highlight: github
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)

```

Prequare : github/netlify account/RStudio download 'blogdown' and 'hugo' information
整篇文章通过Rmardown编写[^2]

### 1. Github and RStudio 初始化环境配置

  1. 打开github账号创建新的public repository，命名为 ‘website’, 复制repository的链接。
  2. 使用RStudio，打开新建项目，选择version control，然后黏贴github链接及选择在本地文件夹存储位置。至此，RStudio工作路径已在‘website’文件夹下
  3. 下载blogdown以及hugo
```{r eval=FALSE, message=TRUE}
install.packages('blogdown')
library(blogdown)
blogdown::hugo_version() # check if hugo exist and version, if not then download
blogdown::install_hugo() 
```
  4. 配置website文件夹下的环境/主题
      在[___Hugo主页___](https://themes.gohugo.io/)中选择主题并载入

```{r eval=FALSE, message=TRUE}
new_site(theme = 'zhaohuabing/hugo-theme-cleanwhite')
# Stop Server and Start Server
stop_server()
serve_site()
```
  5. 在RStudio files下打开.gitgnore文件

```{r eval=FALSE, message=TRUE}
check_gitignore()
# 根据反馈的[Todo]信息在.gitgnore中添加
    .DS_Store
    Thumbs.db
    /public
    /resources
check_content()
# 得到Great! 信息，则一切顺利
# 至此，我们的project都为website
```

### 2. RStudio通过shell控制github版本
  1. Tools > shell
  2. shell配置
```{r eval=FALSE, message=TRUE}
git config --global usr.name 'your_github_name'
git config --global usr.email 'your_email_address'
git add -A # 所有本地website文件同步至github
```
  3. Git > Commit 勾选所有changed文件，并添加commit comment,点击commit提交
  4. 点击绿色Push提交，得到 HEAD -> main反馈，可以去github下查看是否更新  


# ---------------------------------------------------------------------
### 3. 配置netlify
  1. 打开Netlify网页并通过github登录[^3]
  2. Add New Site > Import Exsiting Project > 选择github > 通过授权选择对应的website repository > Show Advanced > New Varible 输入hugo version对应信息 > Deploy(部署)
  3. 页面上方可看到你的个人网页链接，然后可以选择change site name
  4. 成功部署[个人博客](https://shuqiang.netlify.app/)
  5. 编辑config.yarm文件，修改baseurl:: ####为你的博客链接
```{shell eval=FALSE, message=TRUE}
# git提交报错10054，在website文件夹下打开git bash命令
# 取消http代理
git config --global --unset http.proxy
# 取消https代理 
git config --global --unset https.proxy
# 参考：https://blog.csdn.net/good_good_xiu/article/details/118567249
```


_参考文献_

- [Rmarkdown](http://rmarkdown.rstudio.com/index.html)
- [Cheat Sheet](https://www.rstudio.com/resources/cheatsheets/)
- [Tidymodels](https://www.tidymodels.org/)
- [themes/cayman-hugo-theme](https://themes.gohugo.io/themes/cayman-hugo-theme/)

[^1]: https://www.bilibili.com/video/BV1gL411A71J/?spm_id_from=333.788
[^2]: [Rmakdown官方教程](https://markdown.com.cn/)
[^3]: [Netlify官网](https://app.netlify.com/)
[^4]: https://pzhao.org/zh/post/r-blogdown/
