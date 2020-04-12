---
layout: archive
title: "Sitemap"
lang: en
ref: sitemap
permalink: /en/sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

<h2>Pages</h2>
{% assign pages = site.pages | where:"lang", page.lang %}
{% for post in pages %}
  {% include archive-single.html %}
{% endfor %}

<h2>Posts</h2>
{% assign posts = site.posts | where:"lang", page.lang %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
{% unless collection.output == false or collection.label == "posts" %}
  {% capture label %}{{ collection.label }}{% endcapture %}
  {% if label != written_label %}
  <h2>{{ site.data.ui-text[page.lang][label] }}</h2>
  {% capture written_label %}{{ label }}{% endcapture %}
  {% endif %}
{% endunless %}
{% assign docs = collection.docs | where:"lang", page.lang %}
{% for post in docs %}
  {% unless collection.output == false or collection.label == "posts" %}
  {% include archive-single.html %}
  {% endunless %}
{% endfor %}
{% endfor %}
