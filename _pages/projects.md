---
layout: archive
lang: zh
ref: projects
title: "科研课题"
permalink: /projects/
author_profile: true
---

{% assign projects = site.projects | where:"lang", page.lang %}
{% assign from_govs = projects | where:"sponsor", 'government' %}
{% assign from_comps = projects | where:"sponsor", 'company' %}

## 纵向项目
{% for post in from_govs reversed %}
  {% include archive-single.html %}
{% endfor %}

## 横向项目
{% for post in from_comps reversed %}
  {% include archive-single.html %}
{% endfor %}