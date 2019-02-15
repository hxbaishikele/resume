---
layout: archive
lang: en
ref: publications
title: "Publications"
permalink: /en/publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign publications = site.publications | where:"lang", page.lang %}
{% for post in publications reversed %}
  {% include archive-single.html %}
{% endfor %}
