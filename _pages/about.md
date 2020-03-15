---
permalink: /
title: "个人简介"
lang: zh
ref: about
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

林佳瑞，现任清华大学土木系防灾减灾所助理研究员，兼任清华大学力学实验教学中心力学计算与仿真实验室主任。先后于清华大学土木系获得学士（2011年）、博士学位（2016年），2018年博士后出站后加入清华大学土木系防灾减灾新技术研究团队。斯坦福大学、亚琛工业大学、南加州大学访问学者。

主要研究方向为土木工程信息技术、建筑信息模型（BIM）与数字防灾技术，致力于通过先进信息技术提升工程建造、管理及防灾过程的自动化与科学决策水平。获得2016-2018年度中国科协“青年人才托举工程”资助，获得2018年华夏建设科学技术二等奖、2018年北京市科学技术三等奖以及2018年清华大学青年教师教学大赛一等奖、2019年北京市高校青年教师教学基本功大赛三等奖等荣誉。

近5年来，主持国家自然科学基金、重点研发计划子课题、北京市自然科学基金及企业合作研究课题共9项，承担完成了国家863计划、自然科学基金、北京市科技计划等10余项国家及地区重点课题的关键理论技术研究，在国内外学术刊物和会议发表相关论文50余篇，取得软件著作权10项。主要包括如下：
* 全生命期BIM架构：建立了集成BIM、物联网感知及性能仿真数据于一体的全生命期BIM模型架构，实现了建筑能源消耗、结构受力有关仿真、监测数据的集成与统一管理
* 基于BIM和云的工程大数据平台：基于NoSQL数据库及云架构，设计了云端工程大数据平台，提出分布式BIM数据处理、计算与智能检索算法，实现PB级海量数据处理；支持工程多参与方虚拟数据融合，保障各方数据所有权、控制权
* BIM时空-语义数据挖掘方法：综合利用人工智能、语义网、文本挖掘等技术，提出BIM户型相似度计算、质量安全检查文本挖掘、混合运维数据挖掘等系列算法，提升设计、施工与运维决策水平

{% include base_path %}
## 新闻
{% assign posts = site.posts | where:"lang", page.lang %}
{% assign posts = posts | sort: 'date' %}
{% assign posts = posts | reverse %}
<ul>{% for post in posts limit:3 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
## 近期论文
{% assign publications = site.publications | where:"lang", page.lang %}
{% assign publications = publications | reverse %}
<ul>{% for post in publications limit:4 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
## 近期报告
{% assign talks = site.talks | where:"lang", page.lang %}
{% assign talks = talks | reverse %}
<ul>{% for post in talks limit:2 %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
## 近期项目
{% assign projects = site.projects | where:"lang", page.lang %}
{% assign projects = projects | reverse %}
<ul>{% for post in projects limit:2 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
## 近期教学
{% assign teaching = site.teaching | where:"lang", page.lang %}
{% assign teaching = teaching | reverse %}
<ul>{% for post in teaching limit:2 %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>