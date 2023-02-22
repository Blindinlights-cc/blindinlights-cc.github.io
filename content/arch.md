+++

title="Arch-Linux 安装过程的记录"
date=2023-02-22
[taxonomies]
tags = ["arch","linux","教程" ]

+++

# Arch linux安装过程记录

> 前段时间电脑主板烧了，拿去维修后原本电脑上的东西都没了，系统也成了Windows。趁着这个机会，就想试试Arch。
> 之前一直用的Manjaro，遇到问题也是在Arch wiki上找解决方案，Arch社区还挺活跃，换成Arch之后各种问题解决方案应该比之前好找不少 

## 0 安装之前的准备

先准备一个大小为32G的U盘，最好是USB3.0

### 0.1 制作系统盘

1. 首先需要安装ArchLinux的系统镜像，可以在官网和各种镜像源里下载，比如[清华镜像源](https://mirrors.tuna.tsinghua.edu.cn/archlinux/iso/latest/archlinux-2023.02.01-x86_64.iso)。我自己用的是学校社区维护的镜像，校园网下载还挺快的。
2. 下载好系统镜像后，就要制作系统启动盘。Windows下可以用的有[Rufus](https://rufus.akeo.ie/?locale=zh_CN/),[dd](http://www.chrysocome.net/dd),Cygwin等。这里用的是Rufus。在Rufus选择好镜像后点击开始即可。根据官方guide的提示，我用的是单系统，应该选择DD Image mode，和GPT分区方案。
3. 在安装系统前还要做一些设置。
    - 关闭Windows快速启动，参考这篇文章[Windows10 关闭快速启动-知乎](https://zhuanlan.zhihu.com/p/359987583)
    - 进入BIOS设置，一般是在开机时按F2键进入。关闭安全模式并允许U盘启动。

设置好后，重启。开机时按F12,选择U盘启动，就可以进入Live系统

未完待续....