经济管理方向专用提示词模板概览:

![image.png](https://s3.jcloud.sjtu.edu.cn/73ab6ad7b983451089061ee987264ab7-picture/1073d3f5-27f6-4189-8c11-e31d5b51df84_image.png "image.png")
# 金融领域  

## 研报总结与研究  


1.提示模板：
```
请解析《[研报名称|半导体行业市场前景研报]》的核心结论，说明其研究的[主要对象|行业市场规模]及[研究方法|定量分析/案例对比]，重点分析报告中使用的[量化指标|复合增长率、市占率]及其[数据来源|Wind/国家统计局]，阐述结论背后的[经济逻辑|供需关系变化]与[市场趋势|技术迭代驱动]，并提炼未来预测的[关键支撑点|政策红利、资本流入]。要求用通俗语言解释专业术语（如用“行业发动机”比喻龙头企业作用），并附[代码示例|Python数据清洗脚本]说明数据处理流程。
```

2.对比模板：
```
请对比《[研报A|科技行业研报]》与《[研报B|消费行业研报]》对[市场现象|供应链波动]的解读差异，从[数据源|一级市场投融资数据 vs 零售终端数据]、[模型构建|ARIMA预测 vs 蒙特卡洛模拟]、[风险提示|技术风险 vs 库存风险]三方面分析异同，总结[方法论差异|技术导向型 vs 市场导向型]对结论可靠性的影响，最后用[可视化图表|双轴折线图]展示两份报告的预测区间对比。
```

## 股票走势分析  

1.解析模板：
```
请用新手可理解的表述，说明[股票代码|600519]近期出现的[技术信号|20日均线上穿60日均线]及[MACD背离]现象，关联[市场情绪|主力资金净流入]和[基本面数据|Q3净利润同比+15%]，解释这些指标如何反映[资金流向|机构增持]及[趋势转折|短期回调压力]。附[代码示例|TA-Lib指标计算]演示交叉点检测逻辑。  
```


2.对比模板：
```
请分别用[方法A|K线形态识别]和[方法B|GARCH波动率模型]预测[股票代码|300750]走势，对比[代码复杂度|20行 vs 100+行]、[计算效率|实时响应 vs 批量计算]及[维护成本|参数调优频率]，并通过[回测结果|夏普比率对比]说明两者在[趋势捕捉|趋势跟踪胜率75% vs 68%]和[拐点预警|提前1天 vs 滞后3天]的优劣。  
```

## 公司基本情况概览  

1.解析模板：
```
请拆解[公司名称|腾讯控股]的[业务结构|社交/游戏/金融科技]与[财务特征|高毛利低周转]，用[形象比喻|“现金牛+火箭助推器”组合]解释其[收入模型|游戏输血+投资造血]，结合[关键指标|ROE=28%、递延收入占比]和[数据来源|年报/东方财富]，分析[护城河|微信生态粘性]如何通过[计算机技术|分布式架构/推荐算法]强化。要求用Python代码示例展示[财务比率计算|净利率=(净利润/营收)*100]并输出可视化柱状图。
```

2.对比模板：
```
请对比[公司A|宁德时代]与[公司B|比亚迪]在[技术路径|三元锂 vs 刀片电池]和[资本结构|资产负债率62% vs 75%]的差异，从[研发支出|资本化率30% vs 费用化处理]、[供应链控制|锂矿参股 vs 垂直整合]、[数据治理|BMS数据闭环 vs 车联网生态]三个维度展开，用[杜邦分析可视化]代码比较两者ROE驱动因素，并评价[计算机系统|MES生产追溯系统]对管理效率的提升幅度。
```

## 国际重大财经新闻总结  

1.解析模板：
```
请用[5W1H框架]解读[事件|美联储加息25个基点]，说明其对[跨境资本|美债收益率倒挂]和[汇率市场|离岸人民币破7.2]的传导路径，引用[波动率数据|VIX指数飙升15%]和[衍生品信号|NDF隐含贬值预期]，使用[网络爬虫示例|Python抓取Reuters标题情感分析]验证市场情绪。要求用[通俗类比|“全球经济血压计”]解释[利率走廊机制]，并附[汇率联动热力图]可视化代码。  
```

2.对比模板：
```
请对比[事件A|日本央行YCC调整]与[事件B|欧债危机重现担忧]对[资产定价|日债流动性 vs 意德利差]的不同冲击模式，从[政策工具|收益率曲线控制 vs OMT购债计划]、[算法交易影响|套利机器人停摆 vs 风险平价策略调仓]、[数据验证|UBS外汇流量 vs Target2清算系统余额]三方面分析，用[Plotly双事件时间轴]代码展示市场响应节奏差异。
```

## 量化投资策略模拟与复现  

1.解析模板：
```
请阐述[策略名称|双均线趋势跟踪]的[信号规则|5日线上穿20日线买入]，用[数学表达式|Signal=MA(close,5)-MA(close,20)]说明其[经济含义|动量惯性捕捉]，结合[参数优化|网格搜索夏普比率最大化]和[过拟合防范|Walk-forward检验]，提供[完整代码|Backtrader回测框架]包含[手续费控制|佣金0.03%]和[滑点模拟|±0.1%随机扰动]。要求用[交易诊断图|资金曲线+信号点位]分析[策略短板|震荡市连续磨损]。
```

2.对比模板：
```
请对比[策略A|基于LSTM的价格预测]与[策略B|基于协整的配对交易]，从[数据需求|分钟级行情 vs 日频财报]、[计算资源|GPU加速 vs CPU单线程]、[逻辑脆弱性|过拟合风险 vs 价差发散]三个维度分析，通过[AB测试代码|PyAlgoTrade多策略引擎]输出[绩效对比|年化收益21% vs 15%、最大回撤25% vs 12%]，并用[决策树图示]说明不同市场环境下的适用性差异。  
```
 
# 经济（经济与数学双学位）


## 宏观经济预测模型构建


1.解析模板：
```
请解析《[全球经济展望：2024年预测报告]》中对[GDP增长率|全球GDP增长率]的预测结果，说明其采用的[模型种类|DSGE动态随机一般均衡模型]及[主要变量|通货膨胀率、失业率、利率]，重点分析报告中使用的[数据来源|世界银行、国际货币基金组织]及其[模型假设|理性预期、市场出清]，阐述预测背后的[经济逻辑|全球贸易形势、地缘政治风险]，并提炼未来预测的[关键风险点|供应链中断、金融市场波动]。要求用通俗语言解释专业术语（如用“经济的脉搏”比喻GDP增长率），并附[代码示例|Python时间序列预测代码]说明模型预测流程。
```

2.对比模板：
```
请对比《[中国经济增长预测A|基于固定资产投资的预测]》与《[中国经济增长预测B|基于消费增长的预测]》对[中国经济增长率|中国GDP增长率]的解读差异，从[数据源|国家统计局 vs 零售终端数据]、[模型构建|时间序列分析 vs 计量经济学模型]、[风险提示|投资效率下降 vs 消费信心不足]三方面分析异同，总结[方法论差异|供给侧分析 vs 需求侧分析]对结论可靠性的影响，最后用[可视化图表|柱状图]展示两份报告的预测区间对比。
```

## 计量经济学数据分析


1.解析模板：
```
请用新手可理解的表述，说明如何使用[计量经济学模型|多元线性回归模型]分析[变量关系|房价与收入、利率的关系]，关联[数据来源|国家统计局、央行数据]和[统计指标|R平方、显著性水平]，解释这些指标如何反映[变量间的因果关系|收入增加对房价的影响]及[模型的可信度|模型的解释力]，附[代码示例|R语言回归分析代码]演示回归分析流程。
```

2.对比模板：
```
请分别用[方法A|OLS普通最小二乘法]和[方法B|GMM广义矩估计]分析[经济现象|教育水平对工资的影响]，对比[模型复杂度|简单线性模型 vs 复杂非线性模型]、[适用范围|线性关系 vs 非线性关系]及[模型假设|严格外生性 vs 内生性]，并通过[统计检验|Hausman检验]说明两者在[参数估计的有效性|估计结果的差异]和[内生性问题的处理|处理内生性问题的能力]的优劣。
```

## 博弈论案例动态推演


1.解析模板：
```
请用通俗易懂的语言分析[博弈论案例|价格战]中的[博弈参与者|两家竞争企业]的[策略选择|降价或维持价格]，说明其[博弈类型|重复博弈]及[均衡结果|纳什均衡]，重点分析[博弈过程|企业间的互动]及其[策略演变|长期博弈中的策略调整]，阐述结论背后的[经济逻辑|企业利润最大化]，并提炼[策略建议|避免囚徒困境]。要求用图表说明博弈过程，并附[代码示例|Python博弈论模拟代码]演示博弈动态演化。
```

2.对比模板：
```
请分别用[方法A|静态博弈分析]和[方法B|动态博弈分析]预测[市场行为|企业间的并购决策]，对比[模型复杂度|简单矩阵 vs 复杂决策树]、[信息处理|静态信息 vs 动态信息]及[策略分析|一次性决策 vs 序贯决策]，并通过[案例分析|不同行业的并购案例]说明两者在[预测准确性|预测效果的差异]和[策略指导性|策略建议的有效性]的优劣。
```

## 资源分配优化建模

1.解析模板：
```
请解析[资源分配问题|城市公共资源配置]的核心目标，说明其采用的[优化模型|线性规划模型]及[约束条件|预算约束、人口需求]，重点分析模型中使用的[目标函数|资源利用效率最大化]及其[决策变量|各类资源的分配量]，阐述结论背后的[经济逻辑|社会福利最大化]，并提炼[政策建议|如何实现最优资源配置]。要求用通俗语言解释专业术语（如用“资源的蛋糕”比喻资源分配），并附[代码示例|Python优化求解代码]说明资源分配优化流程。
```

2.对比模板：
```
请对比[资源分配模型A|基于效率的分配模型]与[资源分配模型B|基于公平的分配模型]对[资源分配结果|不同群体的资源获得情况]的差异，从[目标函数|效率最大化 vs 公平最大化]、[约束条件|资源总量约束 vs 群体平等约束]、[评估指标|资源利用率 vs 基尼系数]三方面分析异同，总结[模型构建差异|经济学视角 vs 社会学视角]对结论可靠性的影响，最后用[可视化图表|饼图]展示两种分配模型的结果对比。
```

## 微观经济模型分析


1.解析模板：
```
请用新手可理解的表述，说明[微观经济模型|消费者选择模型]如何分析[消费者行为|购买决策]，关联[模型假设|效用最大化]和[关键变量|商品价格、消费者收入]，解释这些变量如何影响[消费者需求|商品需求量]，附[代码示例|Python消费者效用计算代码]演示消费者选择模型。
```

2.对比模板：
```
请分别用[方法A|完全竞争模型]和[方法B|垄断竞争模型]分析[市场结构|餐饮行业]，对比[市场参与者数量|众多小企业 vs 众多差异化企业]、[产品差异化程度|同质产品 vs 差异化产品]及[市场竞争程度|激烈竞争 vs 品牌竞争]，并通过[案例分析|不同类型的餐饮企业]说明两者在[市场效率|资源配置效率]和[企业利润|企业盈利能力]的优劣。  
```
 
# 会计


## 财务报表协助写作


1.解析模板：
```
请协助撰写一份针对[公司名称|腾讯公司]的[财务报表|资产负债表]的分析报告，说明其[关键组成部分|流动资产、非流动资产、所有者权益]及[主要财务指标|资产负债率、流动比率]，重点分析报告中使用的[数据来源|公司年度财务报告]及其[编制依据|中国企业会计准则]，阐述结论背后的[经济逻辑|公司偿债能力、运营效率]，并提炼未来预测的[关键风险点|短期偿债压力、长期资本结构]。要求用通俗语言解释专业术语（如用“公司的家底”比喻资产负债表），并附[代码示例|Python数据可视化]说明财务报表数据展示。
```

2.对比模板：
```
请对比[公司A|腾讯公司]与[公司B|上汽公司]的[财务报表|现金流量表]，从[现金流量类型|经营活动现金流、投资活动现金流、筹资活动现金流]、[分析侧重点|现金流质量 vs 现金流规模]、[风险提示|技术研发投入 vs 生产设备更新]三方面分析异同，总结[财务战略差异|高增长型 vs 稳健型]对财务报表的影响，最后用[可视化图表|柱状图]展示两家公司的现金流量构成对比。
```

## 会计指标的计算与解释


1.解析模板：
```
请用新手可理解的表述，说明如何计算[会计指标|存货周转率]，关联[财务报表科目|期初存货、期末存货、销售成本]，解释该指标如何反映[公司运营效率|存货管理水平]，附[代码示例|Python会计指标计算代码]演示存货周转率的计算过程。
```

2.对比模板：
```
请分别用[方法A|传统公式计算]和[方法B|行业平均值比较]分析[会计指标|净资产收益率]，对比[计算复杂度|简单公式 vs 行业数据收集]、[分析深度|公司自身分析 vs 行业对比]及[应用场景|内部管理 vs 外部投资者]，并通过[案例分析|不同行业的净资产收益率]说明两者在[指标解释的全面性|单一公司分析 vs 行业背景分析]和[决策参考价值|管理决策 vs 投资决策]的优劣。
```

## 发票与应付/应收管理


1.解析模板：
```
请用通俗易懂的语言分析[应收账款管理|账龄分析]中的[关键流程|发票开具、应收账款记录、逾期账款催收]，说明其[管理目标|降低坏账风险、加速资金回笼]及[关键指标|平均收款期、坏账准备率]，重点分析[管理过程|应收账款的跟踪与监控]及其[风险控制|信用政策的制定与执行]，阐述结论背后的[经济逻辑|资金时间价值]，并提炼[管理建议|优化应收账款管理流程]。要求用表格说明账龄分析，并附[代码示例|Python应收账款管理代码]演示应收账款管理流程。
```

2.对比模板：
```
请分别用[方法A|手工记录]和[方法B|会计软件]管理[应付账款]，对比[管理效率|低效 vs 高效]、[数据准确性|易出错 vs 准确]及[管理成本|低成本 vs 高成本]，并通过[案例分析|不同规模公司的应付账款管理]说明两者在[管理效率的差异]和[风险控制的能力]的优劣。
```

## 公司财报总结与分析


1.解析模板：
```
请解析[上市公司|腾讯公司]的[财务报告|年度财务报告]的核心内容，说明其[主要财务指标|营业收入、净利润、资产负债率]及[关键财务活动|投资活动、筹资活动]，重点分析报告中使用的[数据来源|公司公告、证券交易所网站]及其[编制依据|中国企业会计准则]，阐述结论背后的[经济逻辑|公司盈利能力、偿债能力]，并提炼未来预测的[关键支撑点|行业发展趋势、公司战略规划]。要求用通俗语言解释专业术语（如用“公司的健康体检报告”比喻财务报告），并附[代码示例|Python财务报告分析代码]说明财务报告数据处理流程。
```

2.对比模板：
```
请对比[财报A|盈利能力分析]与[财报B|偿债能力分析]对[同一公司|腾讯公司]的[财务状况]的解读差异，从[分析侧重点|收入与利润 vs 资产与负债]、[数据源|利润表 vs 资产负债表]、[风险提示|盈利能力下降 vs 偿债压力增加]三方面分析异同，总结[分析方法差异|盈利能力分析 vs 偿债能力分析]对结论可靠性的影响，最后用[可视化图表|折线图]展示两份财报的预测区间对比。  
```

# 工商管理


## 商业数据可视化设计


1.解析模板：
```
请设计一份针对[销售数据|年度销售额]的[商业数据可视化图表|交互式仪表盘]，说明其[关键元素|销售趋势、区域分布、产品销量]，重点分析图表中使用的[可视化技术|折线图、地图、柱状图]及其[设计原则|清晰性、易读性、美观性]，阐述结论背后的[商业逻辑|销售业绩分析、市场洞察]，并提炼[可视化建议|如何提升数据展示效果]。要求用通俗语言解释专业术语（如用“数据的眼睛”比喻数据可视化），并附[代码示例|Python Matplotlib/Seaborn代码]说明数据可视化流程。
```

2.对比模板：
```
请对比[可视化工具A|Tableau]与[可视化工具B|Power BI]在[数据可视化效果|交互性、美观性]、[数据处理能力|大数据处理、实时更新]、[用户友好性|学习曲线、易用性]三方面分析异同，总结[工具选择差异|专业分析 vs 快速报告]对可视化结果的影响，最后用[可视化图表对比|仪表盘截图]展示两种工具的可视化效果对比。
```

## 用户画像与精准营销


1.解析模板：
```
请用新手可理解的表述，说明如何构建[用户画像|电商平台用户画像]，关联[用户行为数据|浏览记录、购买记录、搜索记录]和[用户属性数据|年龄、性别、地域]，解释这些数据如何反映[用户偏好|购买偏好、消费习惯]，附[代码示例|Python用户画像构建代码]演示用户画像构建流程。
```

2.对比模板：
```
请分别用[方法A|传统细分方法]和[方法B|机器学习聚类方法]构建[用户画像]，对比[数据处理复杂度|简单统计 vs 复杂算法]、[用户细分精度|粗略划分 vs 精细划分]及[营销效果|大众营销 vs 精准营销]，并通过[案例分析|不同行业的精准营销案例]说明两者在[用户洞察的深度]和[营销效率的提升]的优劣。
```

## 供应链网络优化


1.解析模板：
```
请用通俗易懂的语言分析[供应链优化问题|物流成本最小化]，说明其[优化目标|降低运输成本、缩短交货时间]及[约束条件|需求约束、产能约束]，重点分析[优化模型|线性规划模型]及其[优化方法|网络流优化算法]，阐述结论背后的[经济逻辑|成本最小化、效率最大化]，并提炼[优化建议|如何提高供应链效率]。要求用图表说明供应链网络，并附[代码示例|Python供应链优化代码]演示供应链优化流程。
```

2.对比模板：
```
请分别用[方法A|传统库存管理]和[方法B|数字化供应链管理]优化[供应链网络]，对比[信息透明度|信息滞后 vs 信息实时]、[风险控制能力|风险被动应对 vs 风险主动预警]及[运营效率|运营效率低下 vs 运营效率高]，并通过[案例分析|不同行业的供应链优化案例]说明两者在[供应链管理效率的差异]和[风险控制能力]的优劣。
```

## 公司的商业模型分析


1.解析模板：
```
请解析[公司名称|比亚迪公司]的[商业模型|商业模式画布]，说明其[关键组成部分|客户细分、价值主张、渠道通路、客户关系、收入来源、关键资源、关键业务、重要合作、成本结构]，重点分析报告中使用的[分析工具|商业模式画布]及其[分析框架|价值创造、价值传递、价值获取]，阐述结论背后的[经济逻辑|公司盈利模式、竞争优势]，并提炼未来预测的[关键支撑点|市场变化、技术创新]。要求用通俗语言解释专业术语，并附[图表示例|商业模式画布图]说明商业模型。
```

2.对比模板：
```
请对比[商业模型A|传统零售]与[商业模型B|电商平台]对[同一产品|书籍]的[销售模式]的解读差异，从[销售渠道|实体店 vs 网络平台]、[客户关系|面对面服务 vs 在线互动]、[收入来源|商品销售 vs 平台服务]三方面分析异同，总结[模型构建差异|线下销售 vs 线上销售]对结论可靠性的影响，最后用[图表示例|商业模式画布图]展示两种商业模型对比。  
```

作者：安泰经济与管理学院2023级本科生乐子健
</br>
© Copyright 2025，上海交通大学网络信息中心
