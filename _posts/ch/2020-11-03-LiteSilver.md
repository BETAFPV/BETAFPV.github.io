---
layout: post
title: "LiteSilver"
comments: true
lang: ch
date: 2020-11-03
description: "HEXO配置，HEXO+Github，搭建博客"
tag: LiteSilver
---

### 概述
LiteSilver 1-2s是在LiteSilverware 的基础升级来的，采用MM32F103主控，对OSD、使用上做了部分修改。

LiteSilver 支持多种协议的接收机，并添加了USB功能，能方便进行飞控固件的升级。



### 飞控介绍

##### 1、飞行模式

##### 2、OSD



### 下载

1、使用说明书

2、固件版本

[v0.1](https://github.com/BETAFPV/BETAFPV.github.io/releases/tag/0.1)

[v0.2](https://github.com/BETAFPV/BETAFPV.github.io/releases/tag/0.2)

### 常见问题

1、如何设置飞控的rate值

- 通过OSD设置
  - 默认是Starter模式，如下显示
  - 进入OSD，在config菜单下，选中mode选项，往左拨动Roll摇杆两下，再往右拨动两下，会切换到Advanced模式，会出现Rates值设置。
  - ![image-20201119175408821](https://i.loli.net/2020/11/19/azXJ9osThe6Og5G.png)

- 通过Configure设置

  - 更新最新固件

  - 使用Configure上位机，在rates选项下设置。详细见[这里](https://betafpv.github.io/2020/11/Configure/)

    

2、马达启动的时候有卡顿，出现转一下停一下的现象

- 原因是飞控设置的怠速值低了，马达不能正常启动。通过OSD中的motor菜单下MIN选项调高启动怠速值可以解决。