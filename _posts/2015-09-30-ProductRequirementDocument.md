---
layout: post
category : PDM
tagline: "互联网术语"
tags : [产品经理,目标管理]
title:  "PRD文档的撰写"
comments: true
---

##什么是PRD文档
- 产品需求文档(Product Requirement Document，PRD)的英文简称
- PRD文档**向上**是对MRD内容的**继承与发展**，**向下**则是要把MRD文档里面的各种理论要求**技术化**，向研发部门与设计部门说明产品的的功能和性能要求。
- PRD文档是产品文档中**最底层最细致的文档**，所以写作的时候，需要细致耐心。

##再谈BRD，MRD，PRD文档的区别与用途

- **BRD-这么做有好处，并说明好处在哪里**
	- 唐僧出发前,参见唐皇（老板）,告诉唐皇西去取经的重要意义与大兴佛法的好处,唐皇答应,并发放免签护照（授权），于是唐僧带着任务出发了，那个时候唐朝真实V5啊。
- **MRD-通过BRD明确了这个事情值得一做后，描述应该这么做，并说明这么做的原因**
	- 唐僧上路了，但是他需要选择走哪条路线，带几个人，为什么这么走，为什么带这些人，要说清楚：
		- A路线：妖怪多
		- B路线：神仙多
		- C路线：美女多
	- 经过分析，唐僧决定选择C路线，所以才有了三打白骨精，路过女儿国等经典故事（开个玩笑）
- **PRD-获得了授权，而且已经确定了要走的路线，剩下的就是打造装备（产品）了**
	- 要把装备的需求给工匠（研发人员），就需要把你（PM）对装备（产品）的要求讲清楚
	- 金箍棒（需要能缩短到耳朵里面，直径1毫米，长度6毫米，需要金色，重量必须控制在1KG）
	- 九齿钉耙（必须要9个齿，废话啊，黑色，齿长8里面，把手长1.5米，直径2.5厘米）
	- 于是工匠（研发人员）根据需求，打造出了旷世的武器
- **BRD>MRD>PRD是一个逐步论证并得出结果的过程，是产品经理思维升华的过程，是这三个文档三位一体的过程。**

##PRD文档面向的对象
- 研发人员
	 由于研发人员本生专注于功能的实现与性能，所以他们相对对其它诸如运营，市场，设计等表现相对不太关心，对于产品更多的了解来至于产品经理的产品宣讲。
- 设计人员
	-	设计人员本生更多的会关注与产品的调性与原型图，所以对PRD文档的需求是相对较弱的。
- 所以，PRD文档，根据阅读对象，就不要去耍花架子了，用最平铺直叙最简单的话，把问题说的一清二楚就行，绕来绕去小心被程序猿们掏出板斧劈成两截啊

##PRD文档的几种表现方式
PRD文档的目的在于把问题讲清楚，而不是用什么工具！
- 根据实际情况，能满足把问题讲清楚的方式大概有以下几种：
	- 文字模式（Word…..最常见的）
	- 原型图模式（Axure….推荐使用的）
	- 图片模式（有的产品经理本来就是美术转交互转产品，所以他们擅长于此，有门槛的….）
	- 影像模式也可以，就是太烧油了
##常见PRD文档包含内容

###1. 文档说明

- 1.1 产品版本号 （1.26）
	- 版本号 （ **1**.26 ）
		- 重大调整升级
		- 产品结构功能等有调整
	- 子版本号（ 1.**2**6 ）
		- 在原有基础上面对局部功能进行了升级或调整
		- 在原有基础上面对局部功能进行了升级或调整
	- 修正版本号（ 1.2**6** ）
		- 局部小范围优化与Bug修复
		- 一般是不动功能性的东西
- 版本号的命名原则
	- 归零原则：前一个数字增加一位，后面的数字都归零
	- 收费原则：子版本号和修正版本号的变化，一般看做版本内升级，付加收费用，版本号变化则加收费用

- 1.2 历史修订
	- 编号
	- 版本号
	- 修订章节
	- 修订原因
	- 修订日期
	- 修订人
	- 历史修订的作用
	- 对修改前后进行比较
	- 有利于维护和管理PRD
	- 修订人
	- 修订日期
	- 方便查阅，可以只看修订部分

- 1.3 名词术语表
	- 将一些产品里面不易理解，容易混淆，或者缩写的词汇在开篇进行统一的列表说明，有利于阅读
	- 例如产品100的
		- 积分
			- 根据产品100用户的一系列操作行为系统根据后台设定产生的虚拟分数，积分决定了用户的等级与论坛权限s，积分的计算方式为：总积分=发帖数X1 + 铜币X1 + 威望X1 + 会员历史在线时间X1
		- 威望
			- 反应了用户在论坛里面的资历，是根据发帖数量，回帖数量，附件上传数量，在线时长等综合因素决定，是用户积分的重要参考依据
		- 铜板
			- 产品100的货币，主要用于购买有价值的下载资料与信息，完成新手任务可以获得初期足够的铜板，发布下载资源也可以获得相当数量的铜板，铜板是用户积分的重要参考依据
###2. 产品说明
- 产品信息结构
	- 信息结构图是只按照产品经理思路中的产品表现信息来整理产品的一种示意图
	- 信息结构能帮助我们**整理产品结构**，同时是研发人员建立数据库的参考
- 产品结构图
	- 产品结构图是按照产品的逻辑与表现方式,结构化的表现产品构造的一种示意图（后面会举例）
	- 通过这个产品结构图，我们大致就能将之前抽象的逻辑形象化的表现出来，也便于文档阅读者理解我们的产品思路
- 用户使用流程图
	- 用户使用流程图用于表述用户在使用产品过程中的行为走向
	- 通过用户行为串联信息结构与产品结构，阅读者通过阅读用户使用流程，能更好的理解产品经理设计的用户行为

![产品一百主贴与回复信息结构图](http://7xkqbu.com1.z0.glb.clouddn.com/产品一百主贴与回复信息结构图.jpg)
![产品一百用户流程图](http://7xkqbu.com1.z0.glb.clouddn.com/产品一百用户流程图.jpg)

###3. 全局功能说明

- 由于接下来我们要比较详细的表述每个类与每个子类的功能说明，所以这里就要把那些不能放到子类里面去的全局性的东西说清楚
- 尽管是全局功能，但也可以分类说明，例如：
	- UI
	- 交互
	- 等等….
- 例如： 用户交互统一说明：
	- 本客户端在用户触发操作后，应优先加载用户界面，同时在界面中加载数据的位置使用风火轮提示用户数据加载中。
	- 本客户端的时间显示，建议使用人性化提示，例如：20分钟前，一天前，三天前，超过7天的，则显示为具体时间，如：3月30日 17点55分，超过一年，则显示12年3月30日17点55分

###4. 详细功能说明

整体说明完成以后，我们就要开始对各个需求板块进行详细的需求说明

- 根据实际的需求，你可以按照你习惯的表述顺序来表述，常见的表述顺序有：
	- 按照功能的逻辑来表述（更抽象，研发喜欢）
	- 按照产品结构来表述(频道，页面，模块，元素的逻辑表述,相对比较适合产品经理的逻辑，产品经理喜欢）
- 具体哪一个，看团队要求和默契程度


##按照产品的逻辑来表述需求

UML>用例文档>用例图与状态图

- UML登场了(其实产品经理的PRD文档写作所涉及到的UML知识非常有限)
	- 中文名称：统一建模语言
	- 英文名称：Unified Modeling Language
	- 定义：是一种面向对象的建模语言，它是运用统一的、标准化的标记和定义实现对软件系统进行面向对象的描述和建模。
-  UML常见的说明图类型
	- 用例图-表述
	- 状态图
	- 时序图
	- 结构图
	- 等….

###什么是用例图

- 用例
	- 用例就是一种描述系统功能需求的方法
- 用例图
	- 用例图表述的是系统的外部参与者与系统之间的关系,是由参与者与用例组成的示意图
	- 用例图的组成要素
		- 参与者(可以是人,也可以是另一个系统,也可以是其它的东西,是相对的)
		- 用例
		- 关联线
		- 方框

![用例图](http://7xkqbu.com1.z0.glb.clouddn.com/用例图举例.jpg)

- 用例说明

![用例说明](http://7xkqbu.com1.z0.glb.clouddn.com/用例说明.jpg)

### 产品的整体用例图

- 功能板块1需求
	- 功能板块1的子功能1
		- 功能板块1的子功能1的元素1说明(**用例描述**)
		- 功能板块1的子功能1的元素2说明(**用例描述**)
	- 功能板块1的子功能2
		-功能板块1的子功能2的元素1说明(用例描述)
		- 功能板块1的子功能2的元素2说明(用例描述)
- 功能板块2需求(用例文档)
	- 功能板块2的子功能1
		- 功能板块2的子功能1的元素1说明(用例描述)
		- 功能板块2的子功能1的元素1说明(用例描述)
	- 功能板块2的子功能1
		- 功能板块2的子功能1的元素1说明(用例描述)
		- 功能板块2的子功能1的元素1说明(用例描述)

###详细需求说明的原则
- MECE原则
	- MECE，是Mutually Exclusive Collectively Exhaustive，中文意思是“相互独立，完全
穷尽”。 也就是对于一个重大的议题，能够做到不重叠、不遗漏的分类，而且能够藉此有效把握问题的核心，并解决问题的方法。
- MECE只是一种思考方式，当PRD文档撰写交付研发以后，其实多少还是会存在没
有考虑到位或者需求调整的情况，所以:
	- 撰写PRD文档前一定要保证思考到位了,产品结构本身短期内不会有重大改动
	- 需求分类与表述方式要参考MECE原则
	- 这样即便是在交付后，出现调整或需要优化的地方，也不会出现重构的情况
		- 重构需求,重新调整产品结构等,对已经处在开发过程中的团队来说是灾难性的
	- 需求撰写，更多的是考验耐心，思路，经验，但产品架构的确定等更是考验一个产品经理对产品的规划与把握能力
	- 不要害怕，不要迷信


###优秀的PRD文档应该具备的特点
- 正确
	- 确保文档中的表述与产品经理的思路是对应且正确的
- 无歧义
	- 文档的表述方便阅读理解，不会产生歧义
- 完备
	- MECE原则尽量保证对产品功能需求表述的系统完整
- 一致
	- 文档中用词用语一致，对于同一事物的表述应该一样，避免混用同义
- 具有优先级
	- 产品的功能性需求是有先后主次的，对于一次性规划叫多功能的PRD，应该注明功能性需求的先后主次
- 可验证
	- 对于功能性的描述，是可以进行测试的，而不是不发测试，无法定性的东西，例如：效率高，交互完美等词语，都是无法验证的
- 可修改
	- PRD文档利于后期的修改与升级
- 可追踪
	- 每个功能性需求的来源应该是清楚明白的

- - - 


### 分享两句话

话糙理不糙，希望你能都够坚持走下去。事情会越来越好的。	

<center>
<div style="background:#0000;color:#FFC702;width:70%;font-family:Microsoft YaHei" >
<font color="#FFC702" size=5>命运就像一只</font><br>
<font color="#FFC702" size=10>蛆</font>
<br>
<font color="#FFC702" size=5>你让步<br>
它就顺着往上爬<br>
你拿出你的个性和脾气<br>
它就悄悄的缩回去<br>
</font>
</div>
</center>


<center>
<div style="background:#0000;color:#FFC702;width:70%;font-family:Microsoft YaHei" >
<font color="#FFC702" size=5>
竖起你的中指<br>
操起你的生活吧
</font>
</div>
