---
title: test file 1
published: 2025-12-6
pinned: true
description: 2025.12.06.
tags: [Markdown, Blogging]
category: Examples
licenseName: "Unlicensed"
author: emn178
sourceLink: "https://github.com/emn178/markdown"
draft: false
---
# 四层与七层负载均衡
## 什么是四层与七层负载均衡
**判定标准：**osi七层协议，能解析到哪一层就是哪一层的设备
**下定义**
1. 客户端产生一个数据包，就好比是一个快递包，层层包裹七层
2. 负载均衡的作用：分析用户的请求包，然依据内部的算法，分发后其代理的后续节点
3. 四层：解析到四层，看到的是tcp或udp协议，然后基于ip+prot进行转发
4. 七层：解析到七层，看到的是七层协议，例如http协议，然后url地址进行转发