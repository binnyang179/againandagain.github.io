# 猫的三千六百年 :heart:

本博客访问地址：

* 关于本站：基于 [Hexo](https://hexo.io/) 构建，主题则是在 [pure](https://github.com/cofess/hexo-theme-pure) 的基础上魔改后得到的。
* 关于地址：本站托管到两个地址上：腾讯云服务器和 Github Page 。
* 关于网址：猫的巧克力会发光：https://inkss.cn

域名的解析事实上是分为两部分：**国内** 和 **国外** ，当你的访问 IP 位于国内时，DNS 会把你解析到腾讯云的 CDN 上；而如果访问 IP 位于国外时，就解析到 Github Page 中。两者都是 CNAME 类型。

> **所爱隔山海，山海皆可平**  :wind_chime:

------

**一、任务列表：**

- [x] ~~基于 Github API 的博客评论功能~~
- [x] 博客图床的解决
- [x] 目录导航取消自动编号
- [x] 修改博客文章的协议
- [x] 使用个人域名解析博客
- [x] 全站 Http 强制转 Https

**二、服务器成本估计：**

* **~~服务器~~**：~~学生价：10元/月~~ ；正常价：`114元/月`
* **域名**：域名续费价格：`35元/年`
* **CDN**：加速流量：100 GB `20元/6个月`
* **SSL 证书**：DV SSL 证书：`免费/年`
* **对象存储**：免费额度：50GB 空间、~~10GB 流量、100 万次请求~~

**三、搭建过程**

* [基于 Hexo 的网站搭建](https://github.com/inkss/markdown/blob/master/Linux/%E7%BD%91%E7%AB%99/%E5%9F%BA%E4%BA%8E%20Hexo%20%E7%9A%84%E7%BD%91%E7%AB%99%E6%90%AD%E5%BB%BA.md)

**四、模板**

```markdown
---
title: {{ title }}
date: {{ date }}
tags:
  - 标签
categories: 分类
toc: true
mathjax: false
description: 
---

<!-- more -->

------

## 目录

@[TOC]

------



------

[回到顶部](#top) © Inkss
```
