# 系统架构师设计教程(清华)-设计模式
## UML 统一建模语言
统一建模语言(Unified Modeling Language，UML)是一种为面向对象系统的产品进行说明、可视化和编制文档的一种标准语言，
是非专利的第三代建模和规约语言。UML是面向对象设计的建模工具，独立于任何具体程序设计语言。
1997年发布1.0，2017发布至最新版本2.5

## UML 基础
UML通过图形建模分析系统，最新版本共有13中图形，分为静态图和行为图，具体图

![Image text](https://raw.githubusercontent.com/DEAN-Lee/img-rep/master/system_architecture/Snipaste_2021-01-28_20-39-29.png)

其中，最常用的UML图包括：用例图，类图，组件图，部署图，顺序图，活动图，状态机图等。
### 静态图（结构图）
* 对象图
* 包图
* 类图

![Image text](https://raw.githubusercontent.com/DEAN-Lee/img-rep/master/system_architecture/Snipaste_2021-01-28_20-59-46.png)
* 组件图
* 复合结构图
* 部署图

### 行为图
* 用例图
* 活动图
* 状态图
* 顺序图
* 通信图
* 交互概观图
* 时间图

## UML软件开发过程
分为4个阶段
* 初始：明确软件目标和范围,以及分析和经济收益
* 细化
  * 初步需求分析
  * 初步高层设计
  * 部分详细设计
  * 部分原型构造
* 构建 迭代实现架构。用例图、交互图、类图等
  * 部署 部署图
  
## 系统结构文档化
模型采用4+1模式

![Image text](https://raw.githubusercontent.com/DEAN-Lee/img-rep/master/system_architecture/Snipaste_2021-01-29_10-09-33.png)

* 逻辑视图（logical view ）设计的对象模型（使用面向对象的设计方法时）
* 过程视图 (process view) 设计的开发和同步特征
* 物理视图（physical view ）软件到硬件的映射。反映了分布式
* 开发视图（development view ）静态组织结构
* 场景（scenarios） 


