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
{% assign books = publications | where:"category", 'book' %}
{% assign chapters = publications | where:"category", 'chapter' %}

{% include pub_chart stacked="true" %}

{% if journals.size>0 %}
## Journal Papers
{% for post in journals reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if books.size>0 %}
## Books
{% for post in books reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if proceedings.size>0 %}
## Conference Papers
{% for post in proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if chapters.size>0 %}
## Book Chapters
{% for post in chapters reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}