---
layout: archive
lang: en
ref: publications
title: "Publications"
permalink: /en/publications/
author_profile: true
---

You can also find my publications on: 
<ul>
{% if site.author.googlescholar %}
  <li><a href="{{site.author.googlescholar}}">My Google Scholar profile</a></li>
{% endif %}

{% if site.author.researchgate %}
  <li><a href="{{site.author.researchgate}}">My ResearchGate profile</a></li>
{% endif %}

{% if site.author.orcid %}
  <li><a href="{{site.author.orcid}}">My ORCID</a></li>
{% endif %}
</ul>

{% include base_path %}

{% assign publications = site.publications | where:"lang", page.lang %}
{% assign journals = publications | where:"category", 'journal' %}
{% assign proceedings = publications | where:"category", 'conference' %}

<h2>Journal Publications</h2>
{% for post in journals reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Conference Publications</h2>
{% for post in proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}
