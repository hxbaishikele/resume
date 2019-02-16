---
layout: archive
lang: zh
ref: cv
title: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
====
* 2011年8月-2016年6月，清华大学土木系，工学博士
* 2007年8月-2011年7月，清华大学土木系，工学学士

工作经历
====
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

发表论著
====
  {% assign publications = site.publications | where:"lang", page.lang %}
  <ul>{% for post in publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
学术报告
====
  {% assign talks = site.talks | where:"lang", page.lang %}
  <ul>{% for post in talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
课程教学
====
  {% assign teaching = site.teaching | where:"lang", page.lang %}
  <ul>{% for post in teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
社会服务
====
* 中国图学学会 BIM 专委会委员
