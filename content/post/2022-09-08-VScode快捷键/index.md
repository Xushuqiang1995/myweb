---
title: VScode IDE使用指南
author: Shuqiang
date: '2022-09-08'
slug: []
categories:
  - Python
tags:
  - Python
subtitle: ''
description: ''
image: ''
---
> VScode作为多语言的集成开发环境(IDE)，常被用于Java/Python/C++/Go等语言的开发，并且具有强大的拓展功能，可在extension中下载
> 1. 介绍VScode常用快捷键使用，以提高开发效率(装杯)
> 2. VScode常使用的功能
> 3. 


# VScode快捷键介绍

Ctrl + Alt + RightArrow  
Ctrl + Alt + LeftArrow  
Ctrl + P：转到文件（经常打开的文件/当前文件夹下的文件）  
Ctrl + B：折叠资源管理器  


Ctrl + \:屏幕分割  
Ctrl + w  
Crtl + /:注释  
Shift + Alt + A：注释  
Alt + Z：切换自动换行  
Crtl + G：转到行  
Crtl + R：切换工作区  
Ctrl + Tab：切换窗口  
Shift + Alt + I：连续选择多行运行后，会在每一行末尾插入光标  
Ctrl + L：当前行全选  
Ctrl + Shift + L：选中所有找到的匹配项（超实用，相当于全局替换修改）  
Ctrl + F2：选中所有匹配项  
Shift + Alt + F：查看参数定义  
Ctrl + Shift + Space：连续选择多行，然后格式化代码  
Ctrl + K & Ctrl + F：格式化选择部分代码  
F12：转到定义处（相当于找到变量最开始出现的位置）  
Alt + F12：查看定义  
F2：重命名符号  
Ctrl + K & Ctrl + X：裁剪尾随空格  
Ctrl + K & R：在资源管理器中显示活动文件  
Ctrl + Shift + H：替换文件（在多个文件中查找检索内容，并对所有文件进行替换修改）  
Ctrl + K & V：侧边预览   
Ctrl + K & Z：切换成禅模式编辑   



Ctrl + K & Crtl + R：打开常用快捷键pdf  
Ctrl + K & Crtl + S：显示快捷键  


Ctrl + PgUP  
Ctrl + PgDown  

Shift + home:选择光标至行首  
Shift + End:选择光标至行尾  

Ctrl + Shift + P:显示所有命令  
Ctrl + Shift + M：问题  
Ctrl + Shift + U：输出  
Ctrl + Shift + Y：调试台  
Ctrl +  ：终端  


各种组合键  
Ctrl + K & ...  

# Conda常用命令 

activate // 切换到base环境  
activate learn // 切换到learn环境  
conda create -n learn python=3 // 创建一个名为learn的环境并指定python版本为3(的最新版本)  
conda env list // 列出conda管理的所有环境  
conda list // 列出当前环境的所有包  
conda install requests 安装requests包  
conda remove requests 卸载requets包  
conda remove -n learn --all // 删除learn环境及下属所有包  
conda update requests 更新requests包  
conda env export > environment.yaml // 导出当前环境的包信息  
conda env create -f environment.yaml // 用配置文件创建新的虚拟环境  
[ref](https://blog.csdn.net/qq_46049113/article/details/121875393)  

# VScode实用功能

# [Jupyter Notebook快捷键介绍](https://zhuanlan.zhihu.com/p/341503927)


> 支持脚本版本对比功能

> 参考资料
> - [vscode快捷键视频教学1](https://www.bilibili.com/video/BV16a411U774?p=18&spm_id_from=pageDriver&vd_source=ded60bf71a923854104861c4f075796)
> - [vscode快捷键视频教学2](https://www.bilibili.com/video/BV13b4y1p7KE?spm_id_from=333.337.search-card.all.click&vd_source=ded60bf71a923854104861c4f0757962)
> - [vscode学习资料链接(提取码：32f7 )](https://pan.baidu.com/s/1EUbg3zT7JsZuegCYgtMLUQ )

