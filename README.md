# Zoomeye 网空测绘知识库

<img width="200" height="200" src="https://github.com/nday-ldgz/zoomeye-Hacking-TTP/blob/main/img/01.jpg"/>

官网：https://www.zoomeye.org/

ZoomEye是一款针对网络空间的搜索引擎，收录了互联网空间中的设备、网站及其使用的服务或组件等信息。

ZoomEye 拥有两大探测引擎：Xmap 和 Wmap，分别针对网络空间中的设备及网站，通过 24 小时不间断的探测、识别，标识出互联网设备及网站所使用的服务及组件。研究人员可以通过 ZoomEye 方便的了解组件的普及率及漏洞的危害范围等信息。

虽然被称为 “黑客友好” 的搜索引擎，但ZoomEye 并不会主动对网络设备、网站发起攻击，收录的数据也仅用于安全研究。ZoomEye更像是互联网空间的一张航海图。ZoomEye兼具信息收集的功能与漏洞信息库的资源，对于广大的渗透测试爱好者来说以一件非常不错的利器。

链接：https://www.freebuf.com/sectool/163782.html

## 它山之石 国外新闻稿

### NSA/CSS与藏宝图计划TreasureMap

<img width="200" height="200" src="https://github.com/nday-ldgz/zoomeye-Hacking-TTP/blob/main/img/02.png"/>

藏宝图计划由NSA和CSS(中央安全局)两个部门共同负责，NSA的局长一般会兼任CSS局长，共同合作成立NTOC（威胁作战中心），由NSA负责维护运行，搜集全球互联网情报，用于建立态势感知能力。藏宝图计划TreasureMap，实际是通过建立大规模互联网映射、探测和分析引擎系统，建立一个近实时的交互式的全球互联网地图，目的是能够描绘任何时间点互联网上的任=何地点的任何设备。它主要服务于网络空间安全的态势感知（包含敌我双方），用于计算机攻击、漏洞利用环境的准备，以及网络侦查、作战有效性的测量等。它的面向范围包括IPv4、IPv6（部分），关注网络层（路由与自治域），包含物理层、链路层和应用层。

藏宝图的数据由美国主导，多方共建共享。由美国、英国、澳大利亚、加拿大、新西兰共同成立了五眼联盟，情报数据在五个国家间互相共享。在美国内部，建立了全球联合情报通信系统，由16个独立的情报部门共享情报信息。

藏宝图的数据来源非常丰富，包括互联网的开源情报，学术界工具和数据集，信号情报、商业购买与信息保障梳理（针对自有资产）。数据类型（开源/商业/学术）的来源也很丰富，包括BGP、Traceroute、Registries、DNS、OSFingerprints等。

NSA的全球采集点，基于五眼联盟扩大到30多个第三方国家情报组织之间共享数据源，还有80多个特殊情报数据源，也就是不同国家的大使馆；50000多个木马设备，通过将一个植入木马的设备放到指定的地点，成为自己的一个信息搜集点；20多个互联网主干光纤接入点，在全球比较大的海底光缆接入点，进行流量镜像，还有40多个卫星通信拦截点。

数据采集完成后，有专门的系统提供给不同的情报功能使用，用于浏览和检索数据，还提供了很多可视化图或实践，从AS角度、地理位置角度浏览互联网，需要进行攻击时，提供漏洞设备具体的信息，攻击路径信息、可扩展视图，多种数据之间的关联视图查询。

藏宝图计划的目标是要识别互联网地图上的任何时间、任何地点的任何设备。

参考链接：https://www.secrss.com/articles/8950

### NSA发布渗透攻击分析师的招聘告示

此工种主要职责为协助渗透攻击队伍的工作,为渗透攻击队伍分析目标的资产等(属于渗透前期的调研).最终一并完成如下目的:
对渗透攻击小组获得的国家级信号情报出具汇总分析报告.

具体的要求如下:

1. 对元数据的分析(海量数据中找到有关目标系统的信息,以期达到点一下鼠标即黑进系统的效果)
2. 查找目标资产的弱点.
3. 大网捞取特定目标的通信流量.
4. 执行藏宝图分析,将目标线上资产对应到具体的管理员(以期从管理员入手入侵目标).
5. 撰写自定义规则抽取有关目标的情报.
6. 入侵目标系统,在目标系统中搜寻有价值情报.

薪水范围:

– $73,076 – $91,057 (Entry/Developmental)
– $84,529 – $113,362 (Full Performance)
– $103,690 – $159,286 (Senior)

招聘截止时间:2021年6月30日.

参考链接：https://twthu.co/?p=378

## ZoomEYE应用场景

通过ZoomEye dork挖掘的数据可以使用在攻击与防守场景里面。

### 攻击视角

1.开源情报OSINT

2.攻防演练HVV（红队Red Team）

3.漏洞预警到ZoomEye dork（统计和排查数据)攻击者获取情报

4.提交漏洞到SRC

5.等...


### 防御视角

1.暗资产排查（未统计和排查到的资产）

2.攻防演练HVV（蓝队Blue Team）

3.漏洞预警到ZoomEye dork（统计和排查数据)防御者获取情报

4.C&C（命令与控制服务器）排查如cobalt strike后渗透工具

5.等...

参考链接：https://paper.seebug.org/1629/







