---
title: 常用git命令及SSH协议设置
author: Shuqiang
date: '2022-03-29'
slug: R
categories:
  - R
tags:
  - blogdown
  - git
subtitle: ''
description: ''
image: ''
---
希望你能每一刻认真地对待你自己

### 为什么要使用ssh秘钥？

SSH/SRA秘钥存在的目的在于让你的RStudio拥有“钥匙”进入github修改相应文件，主要是为了获取权限

```{r eval=FALSE, message=TRUE}
# 打开git bass命令窗，创建ssh key
$ ssh-keygen -t rsa -C "Xushuqiang19995@806135661@qq.com"
代码运行后会在.ssh文件夹下有id_rsa.pub文件，Notepad文件打开复制内容
Github添加SSH key过程：github网页界面 > setting > SSH and GPG keys > New SSH key > 将C:\Users\user\.ssh\id_rsa.pub内容粘贴

# 开始验证github添加SSH key成功，git bash下输入
$ ssh -T git@github.com

# 修改本地的ssh remote.url 不用https协议，改用git协议。下列命令查看当前远程版本控制协议为https/git
# 通常是https开头的
$ git remote -v

# 因此接下来修改协议为git
$ git remote set-url origin git@github.com:Xushuqiang1995/myweb.git
$ git remote -v

```


### 常用git命令

```{r eval=FALSE, message=TRUE}

mkdir learngit_file_name
cd learn_file_name
pwd
git init 新建一个空的仓库


git status 查看状态
git add . 添加文件
git commit -m '注释' 提交添加的文件并备注说明
git remote add origin git@github.com:jinzhaogit/git.git 连接远程仓库
git push -u origin master 将本地仓库文件推送到远程仓库
git log 查看变更日志
git reset --hard 版本号前六位 回归到指定版本
git branch 查看分支
git branch newname 创建一个叫newname的分支
git checkout newname 切换到叫newname的分支上
git merge newname 把newname分支合并到当前分支上
git pull origin master 将master分支上的内容拉到本地上

# Git处理分支a
git branch -d <branch>
# 合并其他分支到当前分支
git merge <branch>

```

--------------------------------------------------------------------------
_参考文献_

- https://cloud.tencent.com/developer/article/1865750?from=article.detail.1938212)
- https://www.cnblogs.com/jinzhaozhao/p/10012504.html
- [github使用ssh密钥的好处与原因](https://blog.csdn.net/love_fdu_llp/article/details/38752365)
- [廖雪峰git教学](https://www.cnblogs.com/jinzhaozhao/p/10012504.html)