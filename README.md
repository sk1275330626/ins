# 搜索引擎 by深圳大学

* Author: StrickYan 

## 捐赠
  <img src="https://raw.githubusercontent.com/StrickYan/sixchat/master/md_img/IMG_0238.jpg" width="400px" />

## 简介

1. 搜索引擎让人们平等便捷地获取信息，找到所求。

2. 本项目的愿景是实现一个基于Scrapy和Lucene的个人搜索引擎，该搜索引擎的主要功能有：

   （1）爬虫抓取深圳大学公文通信息（数据来源需后期增加，目前只抓公文通），进行数据预处理，数据提取，分词，建立索引，当用户搜索相关信息时呈现准确的信息检索服务。

   （2）集成一些常用校内服务的入口，例如讲座，课程表，校园小巴实时位置等，扮演一个信息聚合的角色。

3. 本项目采用了Python(Scrapy), Java(Lucene), PHP(ThinkPHP)，分别对应了爬虫模块，索引模块，查询模块的功能实现，并实现了不同语言的功能模块间的接口通讯，接口间数据交换格式为Json文本。

4. 本仓库包含索引模块和查询模块的源码，爬虫模块源码在另一个仓库：[szu spider](https://github.com/StrickYan/szuspider)


## 效果图

![](https://raw.githubusercontent.com/StrickYan/ins/master/example_2.png)
