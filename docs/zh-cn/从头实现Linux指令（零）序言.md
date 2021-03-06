---
title: 目录
top: true
cover: true
toc: true
mathjax: true
date: 2020-03-11
password:
summary:
tags:
- 目录
categories:
- 目录
---

本文是从零实现Linux指令系列文章，其他系列文章：
[从头实现Linux指令（零）序言](https://blog.csdn.net/weixin_42089190/article/details/123168895)
[从头实现Linux指令（一）实现自己的shell](https://blog.csdn.net/weixin_42089190/article/details/123431703)

[TOC]



<font color=#999AAA >操作系统是计算机从业人员的基础素养，大名鼎鼎的《ostep》的作者 `Remzi Arpaci-Dusseau`认为每个从业者所掌握的操作系统内容包括：基本操作系统结构、进程和线程同步和并发、文件系统和存储服务器、内存管理技术、进程调度和资源管理以及虚拟化。
最终获得的能力有：
解释操作系统抽象的基本类型，包括进程、同步、虚拟内存和持久性。
设计和实现系统库和内核调用，它们是提供给用户访问和开发新操作系统功能的机制。
评估系统性能并解释将各种算法和数据结构应用于操作系统的复杂操作的影响。




# 前言
笔者认为上述内容确实应该学习。不过为了合理利用我们珍贵的资源 ——时间，大家对于操作系统的学习应该有所侧重。我认为熟练应用Linux下的各种系统调用，熟悉多线程多进程同步，相对比较重要。

笔者认为一种比较好的练习`系统调用`的方式就是利用c语言实现Linux下的各种指令。包括但不限于 `ls wc shell zip cd cat > <  pwd mkdir chmod `等等。同时，这些学习的过程本身就可以当作自己简历上一个关于不起眼的操作系统小项目。

所以，笔者会在之后陆续分享完成以下功能的指令源码，形成一个关于Linux系统调用的系列，希望能和读者朋友们一起学习。今天先将笔者实现的一些指令功能介绍罗列如下。
## shell
简而言之，shell 是一种程序，它从键盘获取命令并将它们交给操作系统执行。在过去，它是类 Unix 系统（如 Linux）上唯一可用的用户界面。如今，除了 shell等命令行界面 (CLI)之外，我们还有图形用户界面 (GUI) 。

在大多数 Linux 系统上，人们使用bash（即 Bourne Again SHell，原始 Unix shell 程序的增强版本，sh由 Steve Bourne 编写）充当 shell 程序。除 bash以外，还有其他可用于 Linux 系统的 shell 程序，比如ksh，tcsh和zsh。

我们自己也可以实现一个toy的shell。同时一个基本的shell也应该能够实现 `cd`, `path`, `&`, `pwd`, `echo`, `<`,`>`等通用命令。


## wc
wc(word count)命令可以计算每个给定文件或标准输入的行，单词，字符和字节数并打印结果。

## 压缩解压
Linux使用的解压缩命令一般都是zip或者tar。相应的压缩包格式也是zip或者tar。我们也可以自己定义一种解压缩的协议，能够把文件合并成一个单独的文件。
这里我们将这个解压文件命名为edd。


## ls
查看文件以及文件夹目录，在这里我们还希望能够递归地实现文件夹内容的查看。

## who
Linux为多用户操作系统，有时候需要查看系统是否繁忙，某人是否正在使用系统等，可以使用who指令来查看Linux系统中活动用户的情况。

命令也是程序。Linux系统中，几乎所有的命令都是人为编写的程序。在Linux系统的中增加新的命令很简单，把可执行文件放到以下任意一个目录即可：/bin、/usr/bin、/usr/local/bin，这些目录存放着很多系统命令。

## cat
输出文件内容。

## cp
复制文件


## 关于文件相关的各类操作
比如使用chmod加权限，比如判断某文件是否存在等命令。



## 互相交流


读者你好！如果你对本文内容感兴趣，我十分希望能够和你互相学习，可以扫码和我联系！一起进步



![在这里插入图片描述](https://img-blog.csdnimg.cn/20200529103009878.gif#pic_center)