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

竞赛方面，我经验丰富，国家级获奖颇丰。我从初中开始接触编程参加信息竞赛，高中代表湖南省参加 NOI 获得国家级铜牌，大学期间 5 次获得 ICPC/CCPC 国家级银牌。

开发方面，我有产品思维，产出高效且持续。我在腾讯实习期间，主导完成了三个不同方向的项目，从立项开始到投入运营的全过程，项目的完成度和效果得到了 leader 的高度评价，并顺利向 +2 完成了汇报。实习之外，我还全栈实现过多个项目。高中时维护了学校的 Online Judge，保证了学校竞赛队三年的日常竞赛训练；大学时接下了学校导师的横向项目，实现了“中小学在线做题网站”项目的竞标 demo。

团队方面，我能和他人高效协同，且极具领导力。在“挑战杯”比赛中，我加入学长组建的团队，独立负责“农村畜牧废水”子项目，并协助发表了相关论文，目前该项目已经进入国家赛。在“三下乡“活动中，我从零招募起一个 7 人团队走入井冈山的农户的家里，带领团队完成了从前期的选题立项、行程规划、政府对接，到中期的实地考察、拍摄记录，到后期的汇报路演、总结复盘的全过程，获得了校优秀团队的称号。

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
- *2024.06 - 2024.09*, 腾讯科技（深圳）有限公司, 企业 IT 部, 安全开发
  - 负责风险测绘的策略建设与漏洞运营，完成安全运营、平台化建设、武器化开发工作。
  - 完成“基于大模型的情报能力建设“项目，月均解析情报 1 万+，成功率达到 95%+
  - 完成“内网管理端后台弱口令扫描”项目，自动支持框架 200+ 种，覆盖率达到 100%
  - 完成”社区策略监控与自动化跟进”项目，完成每日策略跟进，每月巡检资产 10 万+


# 🏗 Projects

- *2024.08 - 2024.09*, 社区策略监控与自动化跟进
  - 为避免 1day 及 nday 漏洞的利用，同时完成情报向策略的转化，需要自动化完成每日社区增量策略的跟进和定期全量策略的验证
  - 内网需要监控的资产量级 10 万+，直接扫描进行策略验证耗时无法接受
  - 经过优化，最终完成单日新增策略 1h 内完成扫描，每月巡检 24h 内完成
- *2024.07 - 2024.08*, 内网管理端后台弱口令扫描
  - 内网存在未经人工覆盖的小众框架管理后台 200+ 种，部分存在弱口令，容易成为攻击突破口
  - 不同种类的框架管理后台，登录方式存在差异，同时存在动态加载、前端加密等安全措施
  - 经过调研，最终研发出的扫描器能够自动支持框架 200+ 种，覆盖率达到 100%，且支持弱密码、默认密码、泄露密码的检测
- *2024.05 - 2024.07*, 基于大模型的情报能力建设
  - 情报的字段缺失率高达约 70%，存在缺失的情报月均 1 万+，需要自动化的方式进行补充
  - 情报来源不同、格式各异，无法通过爬虫精确提取字段，经过调研后选择使用混元大模型来提取标准化、结构化的情报
  - 经过两轮迭代，月均解析情报 1 万+，成功率达到 95%+，并整合进原有工作流能力中
- *2023.10 - 2024.02*, 中小学在线做题网站, 全栈开发
  - 目前市面上关于中小学的试卷资源，都只提供面向教师的下载功能，无法满足学生在线做题评测的需求
  - 横向项目竞标时间紧迫，需要低成本快速进行验证，完成基础逻辑的全栈开发。其中，在线做题页面需要兼容多种题型。
  - 经过开发，使用 3 个月的空余时间，完成了试卷筛选、在线做题、题目研判、用户管理等功能
  - 如果有迭代机会，考虑引入大模型进行主观题的研判，目前需要同学自行进行，无法获得精确成绩，仅起到辅导作用。
- *2023.05 - 2023.08*, “没落 FORGET” 物品丢失提醒 APP, 产品经理
  - 如苹果“查找”等功能，配合上 AirTag 等硬件，大大提高了物品丢失后的找回概率，市场存在需求
  - 现有硬件价格昂贵且自研成本高，考虑通过软件方法来提高丢失物品找回概率
  - 经过调研，确定了软件的逻辑。通过检测并间隙记录用户位置，当检测到用户“从一个地方去到另一个地方”时，提醒用户检查预设的物品清单，确认是否有丢失，并支持回溯检查，方便用户定位物品。
  - 完成策划案撰写 50 余页，独立招募并组建开发团队，完成了项目的 demo 开发，参加了“挑战杯”中国大学生创业计划竞赛
- *2022.10 - 2022.12*, 河北省大学生创新创业年会专题网站开发, 前端开发
  - 学校承办了河北省大学生创新创业年会，需要参考历年专题网站的风格，进行独立创新设计制作，构建一个官方专题网站。
  - 项目需要实现首页通知公告、日程时间线列表制作、年会视频展示、成果作品展示、相关单位展示，还需要实现一整套注册登录系统、后台报名管理系统。
  - 经过开发，顺利完成了项目的部分前端需求，包括首页通知公告、年会视频展示。
- *2022.03 - 2022.04*, H5 掘金客户端复现, 前端开发
  - “字节跳动字学计划v2.0“青训营结营项目，提供 Mock 数据源，要求实现一个单页 Web 应用，复现稀土掘金客户端的大部分功能
  - 完成文章列表与文章两个模块，包括首页、文章页、评论区、登录页、个人信息页、创作后台等页面，需要支持无限滚动逻辑，支持查看历史页面
  - 经历开发，完成了项目，通过了相关负责团队验收

# 📝 Publications 

<div class='paper-box'> <div class='paper-box-image'> <div> <div class="badge">JMCA 2023</div> <img src='https://pubs.rsc.org/en/Image/Get?imageInfo.ImageType=GA&imageInfo.ImageIdentifier.ManuscriptID=D2TA09039B&imageInfo.ImageIdentifier.Year=2023' alt="sym" width="100%"> </div> </div> <div class='paper-box-text' markdown="1">

[Manganese-based oxides Electrocatalysts for the Oxygen Evolution Reaction A Review](https://pubs.rsc.org/en/content/articlelanding/2023/ta/d2ta09039b)

Peng Wang, Shiqi Zhang, Zhaobo Wang, Yuhan Mo, **Xiaoyang Luo**, Fan Yang, Meili Lv, Zhaoxiang Li and Xuanwen, Liu

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=-LBPTmIAAAAJ&citation_for_view=-LBPTmIAAAAJ:W7OEmFMy1HYC) <strong><span class='show_paper_citations' data='-LBPTmIAAAAJ:W7OEmFMy1HYC'></span></strong>

- This paper focuses on the impact of crystal structure, catalytic mechanisms, and design strategies on MnOx.

</div>
</div>

<div class='paper-box'> <div class='paper-box-image'> <div> <div class="badge">JEC 2023</div> <img src='https://ars.els-cdn.com/content/image/1-s2.0-S1572665723005635-ga1.jpg' alt="sym" width="100%"> </div> </div> <div class='paper-box-text' markdown="1">

[Recent progress on NiFe2O4 spinels as electrocatalysts for the oxygen evolution reaction](https://www.sciencedirect.com/science/article/abs/pii/S1572665723005635)

Zihang Feng, Peng Wang, Ying Cheng, Yuhan Mo, **Xiaoyang Luo**, Pan Liu, Rui Guo, Xuanwen Liu

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=-LBPTmIAAAAJ&citation_for_view=-LBPTmIAAAAJ:YsMSGLbcyi4C) <strong><span class='show_paper_citations' data='-LBPTmIAAAAJ:YsMSGLbcyi4C'></span></strong>

- As the main energy supply of human social activities, fossil fuels have caused serious pollution to the global environment, so it is extremely urgent to find new green renewable energy.

</div>
</div>

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