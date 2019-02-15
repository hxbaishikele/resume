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
{% for post in publications reversed %}
  {% include archive-single.html %}
{% endfor %}
