---
theme: bricks
title: misc?
author: taem
colorSchema: dark
aspectRatio: 16/9
transition: fade-out
mdc: true
layout: cover
class: text-center
---

# misc?

---
layout: center
---

# Misc是什么？有什么特点？
Miscellaneous

Misc，也就是安全杂项

在 CTF 中，不能归类到其他方向的题目，都属于 Misc 的范畴
- 内容种类多，范围广
- 对前置基础要求较低，学习曲线平缓
- 知识点有趣

> 接下来，让我们一起走进 Misc 的世界

---
layout: items
---

# Misc 包含什么？

- 编码
- 隐写
- 压缩包
- OSINT
- 流量/内存/磁盘取证
- 应急响应
- 区块链
- AI安全
- ....

---
layout: center
---

# 编码
encode&decode

编码把原始信息转换为另一种形式，经常用于数据的传输和储存

在 Misc 中，我们会遇到不同形式的编码

从最简单的ASCII, base64到神秘的文字、看似杂乱无章的字符，都可能是一种编码

我们就要在已有知识的基础上 在网上搜索相关信息来解出编码中的信息

<!--
比如计算机的底层使用2进制编码，而网页的数据传输通常使用base64编码
-->

---
layout: center
---

# 隐写
Steganography

隐写是一种将秘密信息隐藏在其他载体中的技术

这个载体可以是图片，视频，甚至是一段普通的文本

计算机中的文件以二进制形式存储，因此信息可以通过不同方式隐藏在文件数据之中。

常见隐写载体包括
- 图片隐写
- 音频隐写
- 视频隐写
- 文档隐写

隐写包含的内容很多，且层出不穷，要结合题目持续学习和实践

---
layout: image-right
image: /powchanosint1.jpg
---

# OSINT
Open source intelligence

OSINT也是 Misc 的一部分。

它通过公开可获得的信息进行搜集、关联和分析

简单来说，网络上所说的"开盒"就是从开源信息中找到人的信息和地理位置

一些看似普通的公开信息也可能暴露位置、身份或其他隐私线索

---
layout: center
---

# 压缩包
形形色色的压缩包

Misc 题目中也常见各种加密的压缩包

有些密码藏在旁边的隐写中，有些密码甚至根本无法恢复

常见处理思路包括：

- 密码爆破
- 修复伪加密
- 明文攻击

最基础的方法是**直接尝试恢复**密码

更高级的方法则需要理解压缩包的**结构和工作原理**

---
layout: center
---

# 流量分析（取证）
forensics

取证是从数据中恢复，寻找并分析有价值的信息，最常见的是流量取证

流量一般就是网络/USB流量，设备和网络活动传输的一个个数据包汇集起来就变成了一组流量

流量分析，就是对这些数据包进行查看和分析，从中寻找通信内容与相关线索

![pcap流量包](./pcap.png)

---
layout: end
class: text-center
---

# THANKS FOR WATCHING

## 谢谢观看

主讲人：taem
