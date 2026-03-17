---
title: "llama2.c"
date: 2024-03-25
draft: true
categories: ["LLM"]
tags: ["llama2.c", "LLM", "Open Source Project"]
author: ["valuejhxu"]
---

## 项目地址
[llama2.c](https://github.com/karpathy/llama2.c)

## 项目简介
llama.c 是一个用 C 语言实现的 LLM 推理引擎，支持单机多卡推理，并且支持在 MPS、CUDA、Metal、CPU 上运行。

## 项目特点
- 支持单机多卡推理
- 支持在 MPS、CUDA、Metal、CPU 上运行
- 支持量化
- 支持混合精度推理
- 支持多轮对话
- 支持上下文学习
    
## Get Start

### 拉取项目与编译run脚本
```shell
git clone git@github.com:karpathy/llama2.c.git
cd llama2.c
make run
```

### 创建Python虚拟环境与安装第三方库
```shell
conda create -n llama2c python=3.10
pip install -r requirements.txt
```