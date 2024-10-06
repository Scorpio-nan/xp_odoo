# Odoo 实施使用参考手册

版本：18.0.1.0
作者：[青岛欧姆网络科技](https://odoohub.com.cn) Kevin

## 前言

### 为什么要写这本书

经常有朋友在购买我的服务的时候会问到我这里有没有Odoo的使用手册，遗憾的是，笔者从事了Odoo这么多年的实施和开发，并未能总结出来经验手册之类的东西。细想来，一方面是开发任务比较重，但凡有点空闲时间都去干别的事情了，另一方面就是Odoo的版本变化比较频繁，可能现有的解决方案，在下个版本就不适用了，所以，很难有成体系的东西出来。

本着有困难要上，本着困难制造困难也要上的精神，笔者决定开始执笔写一本Odoo的经验之书。起名实施使用参考手册，因为这里提供的经验不一定适用于您的企业，因为Odoo的开源与灵活，很难说市面上现有的方案就会使您企业的最佳实践。因此，本书的目的，为您提供一种现有通用的解决方案，不是给您最终的解决方案。

### 本书的架构

本书将按照原生业务模块（销售、采购、仓储和生产等）若干大模块划分，读者可以根据章节目录迅速找到想要阅读的部分。当然，模块间的关系其实并不是割裂的，而是有着千丝万缕的联系，因此不能够单独的进行学习，但是为了查找方便，本书将尽量将独立的一个功能作为单独的一章进行编排，以方便读者进行快速查找。

### 版本声明

由于odoo每年一更的节奏,导致很多时候我们上一个版本还没来得及完成就已经过时了。因此，我们决定本书使用"杂糅模式"，即将多个版本的内容都涵盖在内，在有区别的地方使用声明的形式标注其他版本的异同。同时，本书也不会有正式版，因为一直在滚动更新，跟贴近于参考手册的定义。

当前主版本基于17.0，
涵盖：15.0 16.0 17.0

### 建议和反馈

本书由[青岛欧姆网络科技](https://www.odoomommy.com)编写发布，读者如有意见和建议，欢迎关注公众号OdooHub，进行反馈。

![OdooHub](./pub.png)