---
layout: post
title: ICAFE
date: 2019-03-13
author: lyton
tags: ICAFE
---
### ICAFE项目介绍
ICAFE项目向网吧卖产品，其中包含的产品是（CPU，SSD等）。那么工作任务是，某公司有一份数据表格，记录了最近一次ICAFE向跟公司沟通的时间和内容。
#### 数据情况
总数据量：186723条

数据属性：网吧名字，网吧属性，网吧城市，网吧具体地址，网吧联系方式，网吧首次信息数据时间，网吧最近一次更新数据时间，最后一次采买时间，最后一次购买产品型号，最后一次采买产品的数量。

项目目标：向网吧提供产品。

实现方法：
###### 1 利用网吧联系方式打电话询问。假设网吧联系方式都是正确的和完整的，那么每个电话打三分钟。那么一个人打电话要打9336小时，打400天。
###### 2 十个人或者更多的人打电话，去解决，方案优化了，你需要更多的人力了
###### 3 实际情况是，电话的缺失值占到了150000条，剩下的电话号码的有效性（能打通，是本网吧）未考虑。
#####  4 其中有一个属性是最后一次采买时间和更新数据时间，都是2007-2015年 那么网吧是否存在是个重要问题。
> 上述方案都可以解决问题，但是不能使利益最大化。当然从已有的数据基础上可以做，但是最后的效果是非常差的。那么就需要新的数据提供帮助。

#### 新方案
> 第一步：获取新的数据（大众点评，美团，百度等） 第二步：根据数据，提供推荐网吧。
