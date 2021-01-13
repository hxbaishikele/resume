---
layout: archive
lang: zh
ref: publications
title: "发表论著"
permalink: /publications/
author_profile: true
---

您可以通过以下学术主页/链接查看我的论著信息：
<ul>
{% if site.author.googlescholar %}
  <li><a href="{{site.author.googlescholar}}">我的 Google Scholar 个人主页</a></li>
{% endif %}

{% if site.author.researchgate %}
  <li><a href="{{site.author.researchgate}}">我的 ResearchGate 个人主页</a></li>
{% endif %}

{% if site.author.orcid %}
  <li><a href="{{site.author.orcid}}">我的 ORCID 链接</a></li>
{% endif %}
</ul>

{% include base_path %}

{% assign publications = site.publications | where:"lang", page.lang %}
{% assign journals = publications | where:"category", 'journal' %}
{% assign proceedings = publications | where:"category", 'conference' %}
{% assign books = publications | where:"category", 'book' %}
{% assign chapters = publications | where:"category", 'chapter' %}

{% include pub_chart stacked="true" %}

{% if journals.size>0 %}
## 期刊论文
{% for post in journals reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if books.size>0 %}
## 专著
{% for post in books reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if proceedings.size>0 %}
## 会议论文
{% for post in proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if chapters.size>0 %}
## 专著章节
{% for post in chapters reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}