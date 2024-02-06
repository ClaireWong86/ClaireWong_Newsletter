作者：ClaireWang
写于：2022-04
```
1、这篇文章是写给谁看的？
产品经理，对数据分析感兴趣的互联网工作者
2、可以收获什么
可以了解一些数据分析背后的业务思考、可以学习如何基于业务视角去思考系统化的报表设计
```
# 前言
1、为什么做“数据与业务”这篇文章？业务与数据之间的关系？
数据源于业务，数据服务于业务，源于业务终于业务的理念
2、业务层视角与数据层视角的关系？
视角互相补充关系。不同视角出发能让业务与数据之间的连接变得更全面且真实。按照什么样的标准进行分类？什么样的分类是最贴近销售场景的？
3、这个阶段要验证的是什么
去验证两个东西

- 全局-图表系统化
- 局部-图表有意义

解决的问题是什么？

- 数据与业务脱节，难以自证价值
- 产品设计与业务流程脱节，主题架构不符实际
# 正文
# 业务视角
以CRM系统为例，通过系统化思考达成销售业绩目标的管理手段有哪些，可以提炼出销售管理关键要素

- 角色
- 场景
- 手段

![](https://cdn.nlark.com/yuque/0/2022/png/218464/1646706874495-8282f40f-6dc2-40cc-b368-9bec859ed555.png#from=url&id=P1SBh&originHeight=808&originWidth=1262&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
以下内容是围绕这三个要素的展开说明
## 1、销售角色
销售管理的工作内容归纳，再进行一次抽象的话
达成销售业绩目标的管理手段有哪些？
1、目标制定管理
2、销售环节设计及过程管理
3、业绩达成评估
4、问题发现与治理
5、方法沉淀与团队搭建激励
[https://mercuri.cn/%e9%94%80%e5%94%ae%e5%9f%b9%e8%ae%ad/](https://mercuri.cn/%e9%94%80%e5%94%ae%e5%9f%b9%e8%ae%ad/)
### 1.1、职能结构图(示例)
![](https://cdn.nlark.com/yuque/0/2022/png/218464/1646552917360-d4144f96-40a2-45f2-92ad-d384e3beb171.png#from=url&id=hYspp&originHeight=312&originWidth=1962&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
### 1.2、销售角色
现实场景中销售角色很复杂，不同行业/公司/业务的组织架构都有不同，所以这里可以简单抽象成通用三级角色

| 角色 | 职能 |
| --- | --- |
| 一线销售人员 | 执行销售动作、遵守销售流程、完成销售目标的一线工作者 |
| 一线销售主管 | 销售目标和销售任务的拆解分配、对一线销售进行人效和业绩考核 |
| 销售组织管理者 | 目标制定管理、制定销售策略和销售流程 |

## 2、销售场景
### 2.1、销售策略
销售管理的工作核心是什么?如果以业绩指标为核心，从制定到完成业绩指标也有很多手段策略来辅助实现

- 阶段指标制定及拆解
- 潜在客户分配机制
- 销售sop落地及进化机制
- 销售动作落地监督及保障机制
- 质量监督机制
- 阶段复盘机制
- 指标达成保障机制
### 2.2、销售流程
销售流程的重要性：销售流程是交易达成的核心。为规范企业销售过程而制定的一套销售固化流程，以帮助销售人员按步骤，按阶段执行并成交的过程。
策略：定义销售流程、监控过程指标

- 销售按部门角色阶段任务进行全流程拆解

![](https://cdn.nlark.com/yuque/0/2022/png/218464/1646134747649-3274e280-6200-460e-9f85-6f56497576df.png#from=url&id=PI1iX&originHeight=692&originWidth=1362&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
这个环节存在业务对象
流量/线索——市场认可线索MQL——销售认可线索SQL——商机——客户（成交客户/续费/增购客户）
#### 销售漏斗
![](https://cdn.nlark.com/yuque/0/2022/png/218464/1646972648992-985ebea0-3e0d-4b84-8d39-b99772994ea5.png#from=url&id=RZfYY&originHeight=540&originWidth=1162&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

- 市场部：获客。目标：如何能获得更多的MQL、如何增加这个漏斗的流速？
- SDR：培育。目标：帮助销售提供更多的SQL、如何增加这个漏斗的流速？
- 销售部：成单。目标：推进成单。如何增加这个漏斗的流速？

#### 增续转模型

- 客服部：推进续约/增购/转介绍

![](https://cdn.nlark.com/yuque/0/2022/png/218464/1646972668411-0c82f6cd-d00d-4262-b962-6ae1299b7dfd.png#from=url&id=rmscP&originHeight=930&originWidth=1162&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
### 2.3、销售行为
销售流程中业务动作可以被抽象吗？
步骤：统计周期内不同行为指标

- 销售过程还是会围绕三个动作：新增、盘活、转化
- 行为分析：数量、类型、分布、密度、频率、时长

示例：统计不同员工一周内内通过“打电话”方式来跟进“A类客户”的次数和客户数量是多少。
![](https://cdn.nlark.com/yuque/0/2022/png/218464/1646586553191-aa8ca166-3497-439a-81f7-0b22ec6a947c.png#from=url&id=oqXmt&originHeight=776&originWidth=1362&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
## 3、销售手段
### 3.1、业绩达成评估
首先，业绩达成的模型里通常是靠“目标值-完成值-完成率”的结构来进行设计
其次，制定销售目标的主指标/副指标，按时间、团队、产品线做拆分下放，所以需要对业绩指标进行分维拆解，来满足不同的业务场景的评估诉求，这时我们常用的分析数据思路是：-对比、-趋势、-分布
#### 维度结构分析法
销售额=销售量*客单价，是销售量下降还是客单价下降

- 销售量=产品1销售量+产品2销售量+……，是哪几件商品或品类的销售量下降
- 销售量=新客户销售量+老客户销售量，是新客户变少还是老客户复购变少
- 销售量=A区销售量+B区销售量+……，是哪些地区的销售量下降
- 销售量=1月销售量+2月销售量+……，是哪个月份的销售量下降

![](https://cdn.nlark.com/yuque/0/2022/png/218464/1646653668554-2b75fbc9-4aa2-47f0-b4bb-42d6d9ab1e4d.png#from=url&id=PH3bB&originHeight=568&originWidth=2632&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
> - 不同月份的业绩对比情况——分析哪个月份的业绩下降
> - 新客户和老客户销量对比情况——分析客户新客户变少还是老客户的复购变少
> - 不同小组团队对比情况：每季/每月小组距离目标值差距、距离销冠小组差

## 4、销售指标拆解
销售量这个指标可以被拆解成更细致的指标
### 指标拆解法
![](https://cdn.nlark.com/yuque/0/2022/png/218464/1646707890436-d96e8fc4-3f56-4dae-a9f3-826898ded4e8.png#from=url&id=xocAZ&originHeight=498&originWidth=1210&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
提高业务员成单效率等于

| 一级指标 | 二级指标 |
| --- | --- |
| 提高客户数 | 线索质量、线索转客户率 |
| 提高转化率 | 提高响应时间、缩短销售周期 |
| 提高客单价 | 提高已成交客户复购率、提高客户购买新产品率、提高高价值客户占比 |
| 降低所需时间 | 加速线索流转效率、缩短销售周期 |
| 做好客户分层 | A类客户、B类客户、C类客户、…… |
| 提供销售人效 | 提供客户盘活量、提高销售积极性 |

### 4.1、响应时间：转化率与响应时间相关
销售会通过多种方 式（如微信、电话、电子邮件、短信等 方式），尽快与潜在客户联系，帮助企业赢单
那么管理者的考核/验证手段可能是：监控并提升最快线索响应时间。
企业对线索的响应时间越快，越容易增加商机。
**-数据支持**
![](https://cdn.nlark.com/yuque/0/2022/png/218464/1645153051342-2bfe85b3-e449-4aa6-a0f8-79c5b6f01165.png#from=url&id=GebfQ&originHeight=658&originWidth=1472&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
> 根据HBR的一项研究，在一小时内对线 索做出响应的公司可以让销售额增加7倍 以上。同时，velocity研究显示发现， 与30分钟后与新线索联系相比，5分钟内 与新线索联系可以获得商机的几率会增 加100倍。

### 4.3、销售周期：销售周期与销售额增长的关系
销售周期越短越好。销售周期构成：从触客到新客户成单的时间、 采购时间、交易时间和货款回收时间构成
指标：阶段转化周期、销售人员的平均销售周期
参考：[https://www.zkcrm.com/article473.html](https://www.zkcrm.com/article473.html)
Q：为什么销售周期长
A: 因为B2B的决策链条长、决策周期长、每一条线索都可能在中间环节流失掉。
### 4.4、线索质量：商机质量与转化率有关
市场提供的线索质量越高、销售对线索的转化率越高
Q: SDR的工作职责是什么？
A: 给销售人员提供高质量SQL销售认可线索。缩小市场和销售之间的差距减少企业在低质量线索上浪费的时间和资源，SDR的目标是高质量的线索，销售的目标是成单。
Q:这个业务环节会做哪些事情?

- 会与客户建立联系、发现客户的业务问题、判断客户的产品意向度/预算。
- 如果符合标准的线索会分配转出给销售人员。
- 如果不符合标准则继续培育转化。（销氪电销转化的标准是符合商机9要素，且有质检员做质检）
### 4.5、客户盘活量：提高客户盘活量与销售额增长
盘活量的定义是周期内跟进客户量（去重），来源“销帮帮”的销售经验，盘活量与销售额呈正相关。（目前无数据支持）
## 5、问题发现与治理
圈定发现问题的范围层，发现什么问题：与业绩相关（见业绩公式），引发问题的核心要素：人员、产品、客户、渠道，通过规律发现及典型分析做策略调整
![](https://cdn.nlark.com/yuque/0/2022/png/218464/1646578095388-42954714-d49c-4281-beb5-c94cc7e5a969.png#from=url&id=v24cc&originHeight=582&originWidth=2526&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
这里先介绍几个相对重要的业务分析模型
### 5.1、资源质量评估（渠道&活动）
市场部的KPI：资源质量和资源数量，分析资源的质量可以从渠道/活动等多维度分析
#### 渠道质量分析
策略：
跟踪CRM系统 中的所有线索的反馈情况来优化渠道
市场团队提供的资源是：MQL，判断这个资源质量的指标有：线索转商机量、线索转赢单商机量、赢单商机金额

步骤：
哪些渠道的线索量更多
哪些渠道的线索质量更高
哪些渠道的投资回报率ROI更高

从周期角度来看的话
每个月能获取多少线索
同期比较线索量是否降低/提升
从1月份流入的线索在1月份的质量评估
从1月份流入的线索在当前时间的质量评估

#### 营销多元归因分析
衡量不同营销渠道的转化效果，评估其对最终转化目标的影响（直接影响或间接影响）及其对应的贡献价值合理分配营销费用，找到最优营销渠道组合，最大化营销转化率和ROI
![](https://cdn.nlark.com/yuque/0/2022/png/218464/1646706277137-cb134e41-cfac-45e9-b017-005955a980e8.png#from=url&id=Ycg6u&originHeight=155&originWidth=876&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)
参考：[https://zhuanlan.zhihu.com/p/57211448](https://zhuanlan.zhihu.com/p/57211448)
### 5.2、转化效率评估（周期产出）
在CRM系统里的转化通过有两类“转化模型”，非常具有通用性
第1类叫：不同业务对象内流转转化，常见名称为“线索转化率”
![image.png](https://cdn.nlark.com/yuque/0/2022/png/12641910/1660577645670-daf7c341-8c0e-4277-8d9c-0e9d7ff4e669.png#clientId=u1cfdfd4c-0e6e-4&from=paste&height=112&id=u00b8b13f&originHeight=216&originWidth=946&originalType=binary&ratio=1&rotation=0&showTitle=false&size=24621&status=done&style=none&taskId=uf52be270-5415-41af-b4b6-368692057b3&title=&width=492)
第2类叫：同一业务对象内阶段推进，常见名称有“商机漏斗分析”
![image.png](https://cdn.nlark.com/yuque/0/2022/png/12641910/1660577840889-7010be44-807b-48b1-bd18-0fa30fa0276f.png#clientId=u1cfdfd4c-0e6e-4&from=paste&height=706&id=u03ca952d&originHeight=1412&originWidth=2220&originalType=binary&ratio=1&rotation=0&showTitle=false&size=281448&status=done&style=none&taskId=u16a6f8f3-1553-4dd6-af8a-0d969c212ed&title=&width=1110)
步骤：
a、漏斗阶段
b、状态：流转、滞留、流失
c、转化率/转化数/转化周期+流失数/流失率+滞留数/滞留率
![image.png](https://cdn.nlark.com/yuque/0/2022/png/12641910/1660578285995-656fcdb2-94b7-4f09-abbe-8dd6892f9ca8.png#clientId=u1cfdfd4c-0e6e-4&from=paste&height=695&id=u4e1f63e9&originHeight=1390&originWidth=3024&originalType=binary&ratio=1&rotation=0&showTitle=false&size=129539&status=done&style=none&taskId=u539ef8af-61c9-4789-8918-2ae1495cc78&title=&width=1512)
#### 销售阶段转化
我们以销售商机内阶段推进转化来进行分析
销售商机阶段可被定义为：产品咨询、报价、方案评估及最后的赢单或输单。根据商机各阶段的数据，预计成交时间和成交金额，可以推算出某一时间段能够达成的销售业绩，进而能够正确的制定相应的销售目标，了解到每个阶段的总体转化情况，具体到哪个阶段客户流失率较高，需要优化和改进这个阶段的销售工作。
![](https://cdn.nlark.com/yuque/0/2022/png/218464/1645175053537-8bd0b2b6-298f-4056-a650-3d2ef650df00.png#from=url&id=SVZVo&originHeight=337&originWidth=1066&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

|  | 商机总数 | 商机总金额 | 阶段转化率 | 平均停留时长 | 流失数 | 流失率 | 滞留数 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 验证客户 | 12个 | 67,666元 | 83% | 1时16分30秒 | 0 | 0% | 2个 |
| 需求确认 | 10个 |  | 60% |  | 0 |  | 2个 |
| 方案/报价 | 8个 |  | 40% |  | 1 |  | 1个 |
| 谈判审核 | 7个 |  | 30% |  | 2 |  | 1个 |
| 赢单 | 3个 |  | 10% |  |  |  |  |
|  |  |  |  |  |  |  |  |

#### 线索转化率（计算字段）
业务场景：对比周期下新增/存量线索的转化率，分析SDR人员加强孵化培育与历史存量线索—转客户的转化率的关系。
分析：线索表一般有的维度属性字段有：渠道、等级、地区等，基于这个维度可以进行分组统计或多维交叉分析。同时除了基础字段外，也可按业务特性新增一些计算字段，比如“当月新增”与“历史存量”就可以做为两类。
案例：
当月新增线索：100个；历史存量线索：1,000个
每月由新增线索转化来的销售合格线索：40个
每月由历史存量潜客转化来的销售合格线索：100个

| 

 | 线索量 | 转客户的线索数 | 转化率 |
| --- | --- | --- | --- |
| 新增线索 | 100 | 40 | 40% |
| 存量线索 | 1,000 | 100 | 10% |

#### 线索生成速度（LVR）（Lead Velocity Rate）
问题：线索生成速度是否保持稳定，是否会出现某个月线索增量很高导致销售人员存在来不及跟进、某个月线索增量很低，导致销售缺乏资源跟进。
线索生成速率＝本月认可线索－上月认可线索／上月认可线索＊100

| 本月新增线索数 | 上月新增线索数 | 线索生成速率 |
| --- | --- | --- |
| 120 | 100 | 20% |
| 80 | 100 | -20% |

## 6、总结
业务分析可以抽象吗?
-可以。销售业务分析的销售策略可抽象为3种：“定目标、盯过程、抓考核”
数据分析可以抽象吗
-可以。销售数据分析背后的业务目标可抽象为3种：以绩效为核心的“量化、评估、预测”

- 描述性数据分析——量化
- 探索性数据分析——评估
- 预测性数据分析——预测

![image.png](https://cdn.nlark.com/yuque/0/2022/png/12641910/1660584376867-14bab6f4-2ed4-4a59-b0f1-743fb9a8caff.png#clientId=u80f2bfe8-f3a6-4&from=paste&height=695&id=NLwmp&originHeight=1390&originWidth=3024&originalType=binary&ratio=1&rotation=0&showTitle=false&size=637393&status=done&style=none&taskId=u380dc781-6ae5-40b4-a47f-70a6bf51abc&title=&width=1512)
业务分析的模型可以有很多很多，数据分析的方法也有很多很多，我们要学习的不是一个个模型和方法，而是在有限的时间里去思考抽象总结内在规律，举一反三。





