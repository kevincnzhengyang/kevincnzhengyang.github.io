---
layout: post
title:  "Python学习浅淡"
author: kevin
categories: [ Python ]
image: assets/images/jumbotron.jpg
rating: 3
---

# 概述

在码农的圈子有句戏言：人生苦短，早学Python。

本文从个人体会角度，说说Python学习的浅显建议。

# 基础语法

Python的历史就不赘述了，有兴趣的同学请自行查阅。

和其他脚本解释语言一样，Python也是有脚本解释器，负责执行我们编写的Python语法文本脚本。脚本解释器经过若干年的发展，目前已经是3.10.x的版本，和以前2.x在语法上有重大不兼容的地方，所以建议学习并使用3.8之后。

基础的语法学习，快速入门资料：

- [最良心的 Python 教程](https://github.com/walter201230/Python)
- [Python - 100天从新手到大师](https://github.com/jackfrued/Python-100-Days)
- [廖雪峰 python3 教程](https://www.liaoxuefeng.com/wiki/1016959663602400)


# 语言环境

建议安装Anaconda作为Python语言的学习环境，它是一个用于科学计算的Python工具集，有非常多强大、实用的工具包。

[Anaconda](https://www.anaconda.com/)

这个是跨平台的工具集，哪种操作系统都可以安装使用。

同时，不建议一开始就使用Python裸解释器和诸如Pycharm或者VSCode等IDE集成开发环境，而是尝试使用Anaconda中的Jupyter Lab，会省却很多关于配置使用的麻烦，更方便使用Markdown笔记。其实在[Github](https://github.com/)上能找到很多Python学习笔记，就是Jupyter Lab的（兼容Jupyter Notebook格式），下载后用Jupyter Lab打开，可以一边看笔记，一边执行脚本。

# 更进一步

在基础语法之后，建议更进一步学习高级语法和功能扩展库。

## 高级语法

建议阅读 Fluent Python: Clear, Concise, and Effective Programming（中文：流畅的Python），Kindle上有电子书

## 功能扩展库

Python最吸引人的地方，在于丰富且庞大的扩展库资源。

总结不完的总结， 简单罗列一下：

- [学习Python，常用的这22个库怎能不掌握？](https://developer.51cto.com/article/709615.html)
- [耗时6个月，整理了538个Python常用库！](https://blog.51cto.com/u_15493782/5012032)
- 最全大全[Awesome Python](https://github.com/vinta/awesome-python)

# 个人建议

学习路线，在快速学习基础语法后，可以不要投入过多精力在高级语法学习上（这部分可以有时间有兴趣慢慢细究），而先把精力放在学习和使用特定领域的扩展库上：

- 云服务领域：requests、boto3等（Amazon云服务AWS SDK）
- Web服务领域：FastAPI、TortoiseORM或者SQLAlchemy、Dash
- 数据分析与处理：Numpy、Pandas、Streamlit

在各个系统上管理Python解释器运行环境，也是实际工作经常要面对的问题，建议学习pip及poetry、conda或者pyenv之一。
