---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

我叫罗潇阳，湖南娄底人，本科就读于东北大学。

竞赛方面，我经验丰富，国家级获奖颇丰。初中开始接触编程参加信息竞赛，并在高中代表湖南省参加 NOI 比赛获得国家级铜牌，大学 5 次获得 ICPC/CCPC 国家级银牌。

开发方面，我有产品思维，实现过多个全栈项目。高中时承担了学校的 Online Judge 开发和运维，保证了学校竞赛队 50+ 人三年的日常竞赛训练；大学时接下了学校导师横向项目“计算机学习网”全栈开发，3 个月时间实现了项目的 MVP。

团队方面，我极具领导力，参与过多类型的项目。在“三下乡“活动中，我从零招募“井冈山乡村振兴促进团”，带领 7 人团队走进大山中农户的家里，带领团队完成了从前期的选题、立项、行程规划、政府对接，到中期的实地考察、拍摄记录，到后期的汇报路演、总结复盘，获得了校优秀团队的称号。在“挑战杯”比赛中，我加入学长组建的团队，独立负责了“农村畜牧废水”子项目，并协助发表了相关论文，目前该项目已经进入了国家赛。

工作方面，我产出高效且持续，能够清晰明确进行汇报。我在腾讯实习期间，主导了两个项目的开发，协助了一个项目的推进。三个项目全部投入线上运营，我完成了运营数据的分析和汇报材料端撰写，并向 +2 进行了汇报。

如果您对我感兴趣，可以下载[我的简历](/sources/简历-罗潇阳.pdf)。

# 🔥 News
- *2024.08*: 💼💼 腾讯实习转正拟留用
- *2024.06*: 💼💼 腾讯实习入职
- *2023.01*: 💼💼 担任华为耀星计划校园大使
- *2022.12*: 💼💼 担任字节跳动稀土掘金 KeyPlayer 
- *2022.10*: 🎉🎉 “三下乡”暑期社会实践活动中，带领“风泽中孚”井冈山乡村振兴促进团获校级重点项目

# 🎖 Honors and Awards
- *2022.11* ICPC国际大学生程序设计竞赛 [国家级二等奖](/sources/ICPC2022-济南-银牌.pdf)
- *2022.11* 中国大学生程序设计竞赛（CCPC）[国家级三等奖](/sources/CCPC2022-绵阳-铜牌.jpg)
- *2022.10* 中国大学生程序设计竞赛（CCPC）[国家级二等奖](/sources/CCPC2022-桂林-银牌.jpg)
- *2022.07* 中国大学生程序设计竞赛（CCPC）国家级三等奖
- *2022.06* 第一届火象投资家全国大学生统计建模量化模拟交易大赛 [国家级一等奖](/sources/202207052037303.png)
- *2022.06* “蓝桥杯”全国软件和信息技术专业人才大赛 [国家级二等奖](/sources/蓝桥杯2021-国赛-二等奖.jpg)
- *2022.05* “蓝桥杯”全国软件和信息技术专业人才大赛 [省级一等奖](/sources/蓝桥杯2021-省赛-一等奖.jpg)
- *2022.04* ICPC国际大学生程序设计竞赛 [国家级二等奖](/sources/ICPC2021-昆明-银牌.pdf)
- *2021.11* ICPC国际大学生程序设计竞赛 [国家级三等奖](/sources/ICPC2021-沈阳-铜牌.pdf)
- *2021.11* 中国大学生程序设计竞赛（CCPC）[国家级二等奖](/sources/CCPC2021-广州-银牌.jpg)
- *2021.11* 中国大学生程序设计竞赛（CCPC）[国家级二等奖](/sources/CCPC2021-桂林-银牌.jpg)
- *2020.08* NOI 全国青少年信息学奥林匹克竞赛 [国家级铜牌](https://www.noi.cn/hjmd/mdcx)

# 💻 Internships
- *2024.06 - (now)*, 腾讯, 深圳

# 🏗 Projects

<div class='paper-box'> 
<div class='paper-box-text' markdown="1">

[基于混元大模型的情报标准化 Agent 及运营工具](#)

copoluo(罗潇阳)

[**Project**](#)

- 为进一步提升内网安全性，需扩大处理月均万级的第三方漏洞情报信息，人工筛查无法满足，考虑引入大模型来解放一线人员
- 主导完成了情报标准化 Agent，能够通过情报 URL 提取出标准化的 JSON 格式漏洞情报信息，解析成功率达到 95%+
- 接入内部安全平台，完成资产关联及告警生成的全链路自动化流程，产生月均 10+ 漏洞工单，对比人工筛查的方式存在新增漏洞
- 完成相关运营工具的开发，如情报解析、资产关联、告警生成的企业微信机器人，漏洞情报数据库、运营看板网站。
- 在本地 Agent 稳定运行的前提下，通过内部低代码平台实现 Agent 迭代的解耦，双线运行确保了服务的稳定性

</div>
</div>

<div class='paper-box'> <div class='paper-box-image'> <div> <div class="badge">C++</div> <img src='/images/500x300.png' alt="sym" width="100%"> </div> </div> <div class='paper-box-text' markdown="1">

[基于混元大模型的漏洞工单智能问答客服](#)

copoluo(罗潇阳)

[**Project**](#)

- 为进一步解放一线人员，提高用户的漏洞相关工单处理效率，考虑引入大模型来完成前置的智能问答客服
- 项目正在开发推进中

</div>
</div>

<div class='paper-box'> <div class='paper-box-image'> <div> <div class="badge">C++</div> <img src='/images/500x300.png' alt="sym" width="100%"> </div> </div> <div class='paper-box-text' markdown="1">

[Web 端弱口令扫描工具](#)

copoluo(罗潇阳)

[**Project**](#)

- 为进一步提升内网安全性，需处理潜在的弱口令漏洞
- 项目正在开发推进中

</div>
</div>


<div class='paper-box'> <div class='paper-box-image'> <div> <div class="badge">C++</div> <img src='/images/500x300.png' alt="sym" width="100%"> </div> </div> <div class='paper-box-text' markdown="1">

[CppDB](https://github.com/ccviolett/CppDB)

CCViolett(罗潇阳)

[**Project**](https://github.com/ccviolett/CppDB)

- 项目源于一个“实现数据库 ACID 原子性的新思路“，使用了 `C++` 编写
- 实现了一个兼容 Mysql 指令集的简易数据库
- 项目难点在于该项目综合运用多种设计模式，实现了高度可扩展性，与 Spring 的思想具有一定的相似性
- 目前项目还在开发中

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">React</div><img src='/images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[H5 稀土掘金客户端](https://ccviolett.github.io/H5-juejin/)

CCViolett(罗潇阳)

[**Project**](https://github.com/ccviolett/H5-juejin)

- 项目来源于“字节跳动字学计划v2.0“，使用了 `Nodejs + React + SASS` 的技术栈，项目通过了字节跳动相关负责团队验收
- 实现了一个单页应用稀土掘金客户端，完成文章列表与文章两个模块，包括首页、文章页、评论区、登录页、个人信息页、创作后台等页面，实现基础交互逻辑并完成 API 对接
- 项目难点在于路由管理、无限滚动和查看历史页面
- 技术细节见[讲解视频](https://www.bilibili.com/video/BV1LT41157VK)
- 发布了[npm 仓库](https://www.npmjs.com/package/h5-juejin)

</div>
</div>

# 📝 Publications 

<div class='paper-box'> <div class='paper-box-image'> <div> <div class="badge">JMCA 2023</div> <img src='https://pubs.rsc.org/en/Image/Get?imageInfo.ImageType=GA&imageInfo.ImageIdentifier.ManuscriptID=D2TA09039B&imageInfo.ImageIdentifier.Year=2023' alt="sym" width="100%"> </div> </div> <div class='paper-box-text' markdown="1">

[Manganese-based oxides Electrocatalysts for the Oxygen Evolution Reaction A Review](https://pubs.rsc.org/en/content/articlelanding/2023/ta/d2ta09039b)

Peng Wang, Shiqi Zhang, Zhaobo Wang, Yuhan Mo, **Xiaoyang Luo**, Fan Yang, Meili Lv, Zhaoxiang Li and Xuanwen, Liu

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=-LBPTmIAAAAJ&citation_for_view=-LBPTmIAAAAJ:W7OEmFMy1HYC) <strong><span class='show_paper_citations' data='-LBPTmIAAAAJ:W7OEmFMy1HYC'></span></strong>

- This paper focuses on the impact of crystal structure, catalytic mechanisms, and design strategies on MnOx.

</div>
</div>

- [Manganese-based oxides Electrocatalysts for the Oxygen Evolution Reaction A Review](https://pubs.rsc.org/en/content/articlelanding/2023/ta/d2ta09039b), Peng Wang, Shiqi Zhang, Zhaobo Wang, Yuhan Mo, **Xiaoyang Luo**, Fan Yang, Meili Lv, Zhaoxiang Li and Xuanwen, Liu, **JMCA 2023**

# 📖 Educations
- *2021.09 - 2025.07*, 本科, 河北秦皇岛, 东北大学
- *2019.09 - 2021.07*, 高中, 湖南长沙, 长沙市第一中学
- *2019.04 - 2019.07*, 初中，湖南湘潭，长沙市一中九华中学
- *2017.09 - 2019.04*, 初中，湖南长沙, 长沙市一中岳麓中学
- *2016.09 - 2017.09*, 小学, 湖南娄底, 新化县铁牛小学
- *2014.09 - 2016.07*, 小学, 广东中山, 中山市小榄广源小学
- *2013.09 - 2014.07*, 小学, 湖南娄底, 新化县第一实验小学

# 🧑 Friends
- [Yi Ren (任意)](https://rayeren.github.io/) 
- [lmo / jyi2ya / Jiayi He (何佳奕)](https://www.cnblogs.com/jyi2ya/)
- [Henrik-Yao / Hui Yao (姚辉)](http://www.henrik-yao.cn/)