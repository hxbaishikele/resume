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
======
* 工学学士，清华大学土木工程系，2007-2011
* 工学博士，清华大学土木工程系，2011-2016

工作经历
======
* 2011年08月-2016年06月，博士生研究助理
  * 清华大学
  * 主要方向：建筑信息模型与建筑全生命期管理
  * 指导老师：张建平 教授

* 2012年春：课程助教
  * 清华大学
  * 课程名称：工程计算机制图

* 2013年春：课程助教
  * 清华大学
  * 课程名称：工程计算机制图

发表论著
======
  {% assign publications = site.publications | where:"lang", page.lang %}
  <ul>{% for post in publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
学术报告
======
  {% assign talks = site.talks | where:"lang", page.lang %}
  <ul>{% for post in talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
课程教学
======
  {% assign teaching = site.teaching | where:"lang", page.lang %}
  <ul>{% for post in teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
社会服务
======
* 中国图学学会 BIM 专委会委员
