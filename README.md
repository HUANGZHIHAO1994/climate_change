# 气候变化认知小分队

我们是一只朝气蓬勃的队伍，这个队伍里有硕士，博士还有青年教师，我们致力于从气候变化文献库中挖掘人们对气候变化的认知以及这种认知对气候变化政策制定的影响。

## 你应该了解的IPCC

基本定义引用于百度百科。

> IPCC（Intergovernmental Panel on Climate Change）中文全称为“联合国政府间气候变化专门委员会”，是世界气象组织(WMO)及联合国环境规划署(UNEP)于1988年联合建立的政府间机构。其主要任务是对气候变化科学知识的现状，气候变化对社会、经济的潜在影响以及如何适应和减缓气候变化的可能对策进行评估。

> IPCC的基本工作是为政治决策人提供气候变化的相关资料，但IPCC本身不做任何科学研究，而是检查每年出版的数以千计有关气候变化的论文，并每**五年**出版评估报告，总结气候变化的“现有知识”。例如，1990年、1995年、2001年、2007年和2013年，IPCC相继五次完成了评估报告，这些报告已成为国际社会认识和了解气候变化问题的主要科学依据。

IPCC的官方网站：[https://www.ipcc.ch/](https://www.ipcc.ch/)

IPCC工作人员主要分为三个工作组，三个工作组所评估论文的领域分别是：

* The Physical Science Basis（物理科学基础）
* Impacts, Adaptation, and Vulnerability（气候变化带来风险模式和潜在利益的变化）
* Mitigation of Climate Change（从科学、技术、环境、经济和社会等方面减缓气候变化）

除了上面那几个工作组，IPCC评估报告还包含了一些 Special Report（专题报告）和 Methodology Report（方法报告）。


## 我们要干什么

**简单来说，我们的目标是：**

* 构建气候变化文献引用库
* 挖掘科学家和普通大众对气候变化的认知
* 评估气候变化认知对气候政策制定的影响

### 构建气候变化文献引用库

* 抓取IPCC官网中共5次评估报告PDF原文
	* 爬虫
* 从PDF原文中抽取出文献列表，并作为种子列表
	* 方法1: 直接pdf2text，提取参考文献列表（根据位置进行行合并）
	* 方法2: 先pdf2html，在从html提取文献列表
* 从种子列表中抓取文献所引用的文献
	* 选取数据库

> 未完待续 。。。
