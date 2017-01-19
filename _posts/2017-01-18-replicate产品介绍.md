--- 
layout: post
title: "attunity replicate 产品介绍" 
categories: [产品介绍]
---


# 什么是Attunty Replicate
- Attunity Replicate是一款基于数据库日志的异构数据库变化量同步工具
- B/S架构，通过浏览器图形化界面、鼠标点击拖拽的方式进行数据源、目标表的配置
- 支持包括Oracle、SQL server、DB2等十几种同构、异构数据库之间的跨平台数据同步

![产品架构](/img/markdown/replicate/replicate.png)

# 特点
- Attunity Replicate安装部署简单，无需在源端或目标端操作系统上安装软件，只需一台独立的server安装service
- 支持异构数据库间的DDL同步
- 高性能
	- 全量采用native load
	- 变化量同步提供Batch优化
- 并行工作，自定义并发度
- 支持转换
- 提供调度功能
	- 基于WEB页面
	- 命令行
- 使用简单方便，只需要两步即可完成数据同步配置
