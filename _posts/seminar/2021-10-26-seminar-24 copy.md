---
layout: post
title: "学术报告"
subtitle: 'musl libc内存管理'
date: 2021.11.2
host: "王晗"
digest: "介绍Musl libc堆管理，分析Musl libc堆相关结构体以及malloc free流程，并进行常见攻击方式和控制流劫持方式展示。"
permalink: /:categories/:year/:month/:day/:title
categories:
  - seminar

---

## Musl libc堆管理概述
Musl libc是一个轻量级的C标准库，设计作为GNU C library (glibc)、 uClibc或Android Bionic的替代用于嵌入式操作系统和移动设备。使用Musl的Linux发行版和项目包括sabotage，bootstrap-linux，LightCube OS，openwrt LEDE 等等。

## Musl libc堆相关结构体分析

## malloc free流程分析

## 常见攻击方式和控制流劫持方式
+ 程序有堆溢出/UAF等漏洞可以伪造meta，或对伪造的meta进行操作
+ 能够泄露libc地址
+ 能够泄露malloc_context中的secret值



[本次组会内容下载链接](https://github.com/xxycfhb/pku_exploit_files/blob/main/seminar/20211102_musl_libc%E5%86%85%E5%AD%98%E7%AE%A1%E7%90%86.pptx)