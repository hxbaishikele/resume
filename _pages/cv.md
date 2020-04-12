---
layout: archive
lang: zh
ref: cv
title: "个人简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
{% include toc icon="cog" title="目录" %}

## 教育经历
* 2011年8月-2016年6月，清华大学土木系，工学博士
* 2007年8月-2011年7月，清华大学土木系，工学学士

## 工作经历
* 2018年8月-今，清华大学土木系，助理研究员
* 2016年6月-2018年8月，清华大学土木系，博士后
  * 研究方向：基于BIM和物联网的大型基础设施运维管理技术
  * 合作导师：张建平 教授
* 2018年1月-2018年6月，斯坦福大学土木与环境系，访问学者
* 2016年11月-2016年12月，亚琛工业大学E3D研究所，访问学者
* 2015年7月-2015年8月，南加州大学土木与环境系，访问学者
* 2011年8月-2016年6月，清华大学土木系，博士生研究助理
  * 研究方向：基于BIM的建筑全生命期管理技术与平台
  * 指导老师：张建平 教授
* 2010年7月-2010年9月，新加坡CPG公司，结构工程师实习

## 荣誉获奖
### 科学研究
* 2019年01月，《图学学报》2018-2019年度优秀论文
* 2019年01月，2018年华夏建设科学技术二等奖（排名3）
* 2018年11月，2018年北京市科学技术三等奖（排名4）
* 2016年10月，中国科协2016-2018年度“青年人才托举工程”
* 2016年10月，清华大学-亚琛工业大学高级访问学者奖学金
* 2014年11月，第十七届全国工程计算机应用大会优秀论文奖
* 2014年11月，清华大学博士生学术论坛优秀报告奖

### 教育教学
* 2019年12月，清华大学2019年大学生研究训练（SRT）计划优秀指导教师一等奖
* 2019年07月，北京市高校第十一届青年教师教学基本功大赛（工科A）三等奖
* 2018年12月，清华大学第八届青年教师教学大赛（工科组）一等奖
* 2017年10月，清华大学土水学院青年教师教学基本功大赛二等奖
* 2014年12月，清华大学“一二·九”辅导员
* 2012年08月，清华大学土水学院2011-2012学年度优秀助教

### 工程应用
* 2016年04月，第四届“龙图杯”全国BIM（建筑信息模型）大赛一等奖
* 2015年12月，2014-2015年度中国建筑业协会卓越工程项目奖
* 2014年05月，第二届“龙图杯”全国BIM（建筑信息模型）大赛一等奖

### 学业荣誉
* 2015年11月，2014-2015学年度清华大学学业优秀一等奖（信和奖学金）
* 2011年07月，清华大学优秀毕业生、北京市优秀毕业生
* 2010年12月，清华大学蒋南翔奖学金（本科生特等奖学金提名）、学生“科创之星”、优秀学生干部
* 2009年12月，清华大学第十五届结构设计大赛专业组一等奖
* 2009年10月，清华大学航空航天学院学术金质奖章
* 2009年08月，第七届全国周培源大学生力学竞赛团体赛特等奖、第七届全国周培源大学生力学竞赛二等奖

## 发表论著
{% assign publications = site.publications | where:"lang", page.lang %}
{% assign journals = publications | where:"category", 'journal' %}
{% assign proceedings = publications | where:"category", 'conference' %}

### 期刊论文
<ul>{% for post in journals reversed%}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
### 会议论文
<ul>{% for post in proceedings reversed%}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
## 学术报告
{% assign talks = site.talks | where:"lang", page.lang %}
<ul>{% for post in talks reversed%}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

## 科研项目
{% assign projects = site.projects | where:"lang", page.lang %}
{% assign from_govs = projects | where:"sponsor", 'government' %}
{% assign from_comps = projects | where:"sponsor", 'company' %}
### 纵向项目
<ul>{% for post in from_govs reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
### 横向项目
<ul>{% for post in from_comps reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
## 课程教学
{% assign teaching = site.teaching | where:"lang", page.lang %}
<ul>{% for post in teaching reversed%}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
## 社会服务
* 中国图学学会 BIM 专委会委员
* 北京城市规划学会BIM研究与应用中心特聘专家
* Automation in Construction 审稿人
* Journal of Computing in Civil Engineering 审稿人
* IEEE Transactions on Systems, Man and Cybernetics: Systems 审稿人
* Journal of Management in Engineering 审稿人
* Engineering, Construction and Architectural Management 审稿人
* Mobile Information Systems 审稿人
* Canadian Journal of Civil Engineering 审稿人
* Journal of Structural Integrity and Maintenance 审稿人
* Frontiers of Engineering Management 审稿人
* Energy and Built Environment 审稿人
* 《清华大学学报（自然科学版）》 审稿人
* 《土木工程学报》 审稿人
* 《工程力学》 审稿人
* 《中国公路学报》 审稿人
* 《图学学报》 审稿人
* 《施工技术》 审稿人
* 《土木建筑工程信息技术》 审稿人
