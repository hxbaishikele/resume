---
layout: archive
lang: en
ref: projects
title: "Research Projects"
permalink: /en/projects/
author_profile: true
---

{% assign projects = site.projects | where:"lang", page.lang %}
{% assign from_govs = projects | where:"sponsor", 'government' %}
{% assign from_comps = projects | where:"sponsor", 'company' %}

<h2>Sponsored by Government</h2>
{% for post in from_govs reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Sponsored by Companies</h2>
{% for post in from_comps reversed %}
  {% include archive-single.html %}
{% endfor %}