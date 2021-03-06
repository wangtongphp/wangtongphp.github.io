-- 《计算广告》 -  刘鹏

 [原文](https://item.jd.com/10099018823.html) 
#### 前言
  以广告为核心的后向变现体系
  在能够获得充分的流量或高价值数据后，我们认为，所有能够传播信息的商品，其售价都会趋向其边际成本
  
#### 第1章在线广告综述

  在线广告，也称为网络广告、互联网广告
  
  1.1免费模式与互联网核心资产4
  1.2大数据与广告的关系5。
  大数据问题特征示意图、
  Volume（规模）、Variety（多样性）、Velocity（高速）、Value（价值），即所谓的4V特征来描述大数据问题的特性。
  A类，个性化推荐（personalized recommendation）和计算广告（computational advertising）典型的大数据问题。
  B类，中等规模问题上的复杂算法 用Spark。 
  1.3广告的定义与目的7
  —出资人（sponsor）和媒体（medium）。需求方（demand）和供给方（supply）。是广告主（advertiser）、代理商（agency）、受众（audience）。
  品牌广告（brand awareness）；直接效果广告（direct response）。
  整合营销（integrated marketing）的概念，即通过多种渠道的有机配合来达到整体投放效果的最优。
  投入产出比（Return On Investment，ROI）
  1.4在线广告表现形式9
  banner/rich media/video/social/mobile/E-mail Direct Marketing，EDM
  1.5在线广告简史15
  展示广告（display advertising）/ 合约广告（agreement-based advertising）
  一是受众定向（audience targeting）， 二是广告投放（ad serving），
  品牌广告主： 担保式投送（Guaranteed Delivery，GD）按千次展示付费（Cost per Mille，CPM）
  在线分配（online allocation）。用带约束优化 （constrained optimization）
  竞价广告 （auction-based advertising）。广义第二高价（Generalized Second Price， GSP）
  广告网络 （ad Network，ADN）。以按点击付费（Cost per Click，CPC），中小互联网媒体
  交易终端（Trading Desk，TD）。实时竞价（Real Time Bidding，RTB）。广告交易平台（ad Exchange，ADX）。
  
#### 第2章计算广告基础20
而千次展示期望收入（expected Cost Per Mille，eCPM）
  2.1广告有效性原理21
  选择（selection）、 解释（interpretation）与态度（attitude）
  曝光（exposure）、关注（attention）、理解（comprehension）、接受（acceptence）、保持（retention）与决策（decision）
  2.2互联网广告的技术特点23
  技术和计算导向。效果的可衡量性。创意和投放方式的标准化。媒体概念的多样化。数据驱动的投放决策。
  2.3计算广告的核心问题24
  计算广告的核心问题，是为一系列用户与环境的组合找到最合适的广告投放策略以优化整体广告活动的利润。
  2.3.1广告收入的分解25
  点击率（Click Through Rate，CTR）、落地页（landing page）、转化率（Conversion Rate，CVR）
  2.3.2结算方式与eCPM估计的关系26
  CPT/CPM/CPC/CPS/CPA/ROI
  2.4在线广告相关行业协会29
  2.4.1交互广告局29
  交互广告局（Interactive Advertising Bureau，IAB， http://www.iab.net）:横幅广告创意尺寸标准/视频广告标准VAST/通用实时竞价接口标准OpenRTB
  2.4.2美国广告代理协会30
  （American Association of Advertising Agencies，4A）:品牌广告的代理商在美国的行业协会
  2.4.3美国国家广告商协会30
  Association of National Advertisers，ANA.广告主的协会。 反对DNT
  
#### 第3章在线广告产品概览33
  合约、竞价、程序化交易、原生
  3.1商业产品的设计原则34
  客户关系管理（Customer Relation Management，CRM）、网站分析（Web Analytics，WA）、的数据管理平台（Data Management Platform，DMP）
  3.2广告系统的产品接口35
  3.2.1广告主层级组织与投放管理35
  广告的层次分为广告主、广告（推广）计划（campaign）、广告（推广）组（ad group）、广告创意（creative）等几个层级
  3.2.2供给方管理接口38
  3.2.3供需之间多种接口形式39
  
#### 第4章合约广告41
  4.1广告位合约42
  广告排期系统的代表性产品有DoubleClick的DFP以及中国市场上好耶（Allyes）的类似产品，还有免费给中小网站使用的百度广告管家
  4.2受众定向43
  4.2.1受众定向方法概览43
  geo-targeting/demographical targeting/channel targeting/contextual targeting/behaviorial targeting/hyper-local targeting/retargeting/look-alike targeting/group-purchase
  4.2.2受众定向标签体系46
  标签及关键词
  4.2.3标签体系的设计思路47
  4.3展示量合约48
  4.3.1流量预测49
  流量预测（traffic forecasting）
  4.3.2流量塑形50
  流量塑形（traffic shaping）。
  4.3.3在线分配50
  二部图（bipartite graph）匹配的问题
  4.3.4产品案例51
  
#### 第5章搜索广告与竞价广告53
  5.1搜索广告54
  5.1.1搜索广告产品形态55
  5.1.2搜索广告产品新形式57
  5.1.3搜索广告产品策略60
  5.1.4产品案例62
  5.2位置拍卖与机制设计64
  5.2.1市场保留价65
  5.2.2定价问题66
  5.2.3价格挤压68
  5.2.4Myerson优拍卖69
  5.2.5定价结果示例69
  5.3竞价广告网络70
  5.3.1广告网络产品形态71
  5.3.2广告网络产品策略72
  5.3.3产品案例73
  5.4竞价广告需求方产品74
  5.4.1搜索引擎营销74
  5.4.2交易终端75
  5.4.3产品案例75
  5.5竞价广告与合约广告的比较77
  
#### 第6章程序化交易广告78
  6.1实时竞价79
  浏览流量主网址->SDK call ADX -> DSP
  6.2其他程序化交易方式82
  6.2.1优选82
  6.2.2私有市场83
  6.2.3程序化直投84
  6.2.4广告交易方式谱系84
  6.3广告交易平台85
  6.4需求方平台87
  6.4.1需求方平台产品策略87
  6.4.2出价策略88
  6.4.3出价和定价过程89
  6.4.4重定向89
  6.4.5新客推荐91
  6.4.6产品案例92
  6.5供给方平台94
  6.5.1供给方平台产品策略94
  6.5.2HeaderBidding95
  6.5.3产品案例96
  
#### 第7章数据加工与交易99
  7.1有价值的数据来源100
  7.2数据管理平台102
  7.2.1三方数据划分102
  7.2.2方数据管理平台102
  7.2.3第三方数据管理平台103
  7.2.4产品案例104
  7.3数据交易的基本过程107
  7.4隐私保护和数据安全109
  7.4.1隐私保护问题109
  7.4.2程序化交易中的数据安全111
  7.4.3欧盟的通用数据保护条例113
  
#### 第8章信息流与原生广告115
  8.1移动广告的现状与挑战116
  8.1.1移动广告的特点117
  8.1.2移动广告的传统创意形式117
  8.1.3移动广告的挑战119
  8.2信息流广告121
  8.2.1信息流广告的定义121
  8.2.2信息流广告产品关键123
  8.3其他原生广告相关产品124
  8.3.1搜索广告125
  8.3.2软文广告125
  8.3.3联盟125
  8.4原生广告平台126
  8.4.1表现原生与场景原生126
  8.4.2场景的感知与应用127
  8.4.3植入式原生广告128
  8.4.4产品案例130
  8.5原生广告与程序化交易134
  第三部分计算广告关键技术
  
#### 第9章计算广告技术概览137
  9.1个性化系统框架138
  9.2各类广告系统优化目标139
  9.3计算广告系统架构140
  9.3.1广告投放引擎142
  9.3.2数据高速公路143
  9.3.3离线数据处理143
  session log/behaviorial targeting/contextual targeting/click modeling/planning/BI/广告管理系统
  9.3.4在线数据处理144
  anti-spam、billing、在线行为反馈、real-time indexing
  9.4计算广告系统主要技术144
  9.5用开源工具搭建计算广告系统146
  9.5.1Web服务器Nginx146
  9.5.2分布式配置和集群管理工具ZooKeeper148
  9.5.3全文检索引擎Lucene148
  9.5.4跨语言通信接口Thrift149
  9.5.5数据高速公路Flume150
  9.5.6分布式数据处理平台Hadoop150
  9.5.7特征在线缓存Redis151
  9.5.8流计算平台Storm152
  9.5.9高效的迭代计算框架Spark152
  
#### 10章基础知识准备154
  10.1信息检索155
  10.1.1倒排索引155 *
  map+链表, 每个关键词跟着文档ID的链表
  10.1.2向量空间模型157
  Vector Space Model， VSM。
  10.2优化方法158
  10.2.1拉格朗日法与凸优化159 
  10.2.2下降单纯形法160
  10.2.3梯度下降法160
  10.2.4拟牛顿法162
  10.3统计机器学习167
  10.3.1熵与指数族分布168
  10.3.2混合模型和EM算法169
  10.3.3贝叶斯学习171
  10.4统计模型分布式优化框架174
  10.5深度学习175
  10.5.1深度神经网络优化方法176
  10.5.2卷积神经网络（CNN）177
  10.5.3递归神经网络（RNN）178
  10.5.4生成对抗网络（GAN）180
  
#### 11章合约广告核心技术181
  11.1广告排期系统182
  11.2担保式投送系统183
  11.2.1流量预测185
  11.2.2频次控制186
  11.3在线分配188
  11.3.1在线分配问题188
  11.3.2在线分配问题举例190
  11.3.3极限性能研究192
  11.3.4实用优化算法193
  
#### 12章受众定向核心技术201
  12.1受众定向技术分类202
  12.2上下文定向203
  12.3文本主题挖掘205
  12.3.1LSA模型206
  12.3.2PLSI模型206
  12.3.3LDA模型207
  12.3.4词嵌入word2vec208
  12.4行为定向209
  12.4.1行为定向建模问题210
  12.4.2行为定向特征生成211
  12.4.3行为定向决策过程214
  12.4.4行为定向的评测215
  12.5人口属性预测217
  12.6数据管理平台218
  
#### 13章竞价广告核心技术220
  13.1竞价广告计价算法220
  13.2搜索广告系统222
  13.2.1查询扩展223
  13.2.2广告放置226
  13.3广告网络227
  13.4广告检索229
  13.4.1布尔表达式的检索230
  13.4.2相关性检索234
  13.4.3基于DNN的语义建模238
  13.4.4近邻语义检索241
  
#### 14章点击率预测模型247
  14.1点击率预测248
  14.1.1点击率基本模型248
  14.1.2LR模型优化算法249
  14.1.3点击率模型的校正256
  14.1.4点击率模型的特征257
  14.1.5点击率模型评测262
  14.1.6智能频次控制264
  14.2其他点击率模型264
  14.2.1因子分解机264
  14.2.2GBDT265
  14.2.3深度学习点击率模型267
  14.3探索与利用268
  14.3.1强化学习与E&E268
  14.3.2UCB方法270
  14.3.3考虑上下文的bandit271
  
#### 15章程序化交易核心技术272
  15.1广告交易平台273
  15.1.1cookie映射273
  15.1.2询价优化277
  15.2需求方平台278
  15.2.1定制化用户标签280
  15.2.2DSP中的点击率预测282
  15.2.3点击价值估计283
  15.2.4出价策略284
  15.3供给方平台284
  
#### 16章其他广告相关技术286
  16.1创意优化287
  16.1.1程序化创意287
  16.1.2点击热力图288
  16.1.3创意的发展趋势289
  16.2实验框架291
  16.3广告监测与归因292
  16.3.1广告监测292
  16.3.2广告安全294
  16.3.3广告效果归因295
  16.4作弊与反作弊296
  16.4.1作弊的方法分类296
  16.4.2常见的作弊方法297
  16.5产品技术选型实战301
  16.5.1媒体实战302
  16.5.2广告主实战304
  16.5.3数据提供方实战306
  
  第四部分附录
  附录主要术语及缩写索引311
  参考文献317
  
  
## 总结思考

#### 第一部分
  分类
  * SEM做的竞价调价
  * 百度网盟
  * 淘宝侧橱窗
  * feed流的广告卡片
  * 门户banner或横幅广告
  * 友情链接
  * 看视频前的广告视频
  
  