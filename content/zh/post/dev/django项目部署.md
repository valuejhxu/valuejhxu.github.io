---
title: "Django 项目部署"
date: 2024-03-21
draft: false
categories: ["开发"]
tags: ["Python", "Django", "部署"]
author: ["valuejhxu"]
aliases: ['/zh/post/develop/django项目部署/']
---

## 安装Python环境
Python Interpreter下载地址：https://www.python.org/ftp/python/
拉取自己所需要的版本的 python 解释器，并安装：
```shell
mkdir django_dev
cd django_dev
wget https://www.python.org/ftp/python/3.8.8/Python-3.8.8.tar.xz
tar vxf Python-3.8.8.tar.xz
cd Python-3.8.8/
./configure
make && make install 
```
通过`whereis python`可以查看到安装成功的 python 解释器。需要使用的话直接输入对应的python版本号即可，例如我安装的`python3.8`。

往往在 Linux 环境下会有默认的 python2.7 版本, `python` 命令也是链接到这个解释器的，如果需要将 `python` 命令链接到新安装的 python 解释器的，则：
```shell
cd /usr/local/bin
ll -a python*
```

## 安装conda



## 安装django
```shell
pip3 install django
```
