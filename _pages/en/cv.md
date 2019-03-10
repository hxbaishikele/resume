---
layout: archive
lang: en
ref: cv
title: "Curriculum Vitae"
permalink: /en/cv/
author_profile: true
redirect_from:
  - /en/resume
---

{% include base_path %}

Education
====
* Aug, 2011-Jun, 2016: Ph.D in Department of Civil Engineering, Tsinghua University
* Aug, 2007-Jul, 2011: B.S. in Department of Civil Engineering, Tsinghua University

Work experience
====
* Aug, 2018-Now: Research Assistant Professor, Tsinghua University
* Jul, 2016-Aug, 2018: Postdoctoral Research Associate, Tsinghua University
  * Research area: Maintenance of buildings and infrastructures based on BIM and IoT
  * Mentor: Professor Jian-Ping Zhang
* Jan, 2018-Jun, 2018: Visiting Scholar, Stanford University
* Nov, 2016-Dec, 2016: Visiting Scholar, RWTH-Aachen University
* Aug, 2011-Jun, 2016: Research Assistant, Tsinghua University
  * Research area: Building Information Modeling and Building Lifecycle Management
  * Supervisor: Professor Jian-Ping Zhang
* Jul, 2015-Aug, 2015: Visiting Scholar, University of Southern  California
* Jul, 2010-Sept, 2010: Structural Engineer Internship, Singapore CPG Co. Ltd.

Publications
====
  {% assign publications = site.publications | where:"lang", page.lang %}
  {% assign journals = publications | where:"category", 'journal' %}
  {% assign proceedings = publications | where:"category", 'conference' %}

<h2>Journal Publications</h2>
  <ul>{% for post in journals %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<h2>Conference Publications</h2>
  <ul>{% for post in proceedings %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
====
  {% assign talks = site.talks | where:"lang", page.lang %}
  <ul>{% for post in talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
====
  {% assign teaching = site.teaching | where:"lang", page.lang %}
  <ul>{% for post in teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
====
* Member of building information modeling committee of China Graphics Society
