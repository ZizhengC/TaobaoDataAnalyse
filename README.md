# TaobaoDataAnalyse
淘宝用户行为数据分析复现
项目流程来源: https://blog.csdn.net/zhangruihua1998/article/details/122215976

## 项目背景及目的：电商平台数据分析是最为典型的一个数据分析赛道，且电商数据分析有着比较成熟的数据分析模型，比如：人货场模型。此文中我将通过分析国内最大的电商平台——淘宝的用户行为，来巩固数据分析技能以及思维。通过分析用户行为，以此来实现精准营销，总结现有问题，获得业务增长。

### 一.数据源
数据源：阿里云天池数据集

### 数据说明
该数据集包含了2017年11月25日至2017年12月3日之间，有行为的约一百万随机用户的所有行为（行为包括点击、购买、加购、喜欢）。

## 二.分析框架和思路
数据分析的关键是指标体系的建立，从什么角度着手去达成数据分析的目的，在此次数据分析中，是对淘宝用户行为进行一个分析，而在电商用户行为分析中最常用的是“人货场”模型，人：即用户角度；货：即商品角度；场:即卖场，电商平台指标体系角度。

### 2.1场：电商指标体系角度
电商指标体系维度可以参见一些常见的指标：流量（包括总体流量，每日流量，每时流量），流量漏斗转换，复购率，跳失率。然后下面对每一个概念进行解释：
知识点1：衡量流量的指标为UV，PV，关于他们的解释参考这个链接。如何清除的理解UV和PV的定义
知识点2：流量漏斗转化模型的介绍
知识点3：跳出率
知识点4：重复购买率

### 2.2人：用户角度
从用户角度，可以采用用户转化漏斗模型和RFM用户分层模型，了解用户转化率，以及高价值用户。

### 2.3货：商品角度
知识点1：SKU的解释
商品角度可以从SKU下单量，SKU浏览量进行商品流量分析，结合浏览量和下单量对商品进行流量四象限分析。
