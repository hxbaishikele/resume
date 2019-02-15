---
layout: archive
lang: en
ref: cv
title: "CV"
permalink: /en/cv/
author_profile: true
redirect_from:
  - /en/resume
---

{% include base_path %}

Education
======
* B.S. in Department of Civil Engineering, Tsinghua University, 2007-2011
* Ph.D in Department of Civil Engineering, Tsinghua University, 2011-2016

Work experience
======
* Aug, 2011-Jun, 2016: Research Assistant
  * Tsinghua University
  * Duties included: Building Information Modeling and Building Lifecycle Management
  * Supervisor: Professor Jian-Ping Zhang

* Spring 2012: Teaching Assistant
  * Tsinghua University
  * Course: Computer-Aided Engineering Drawings

* Spring 2013: Teaching Assistant
  * Tsinghua University
  * Course: Computer-Aided Engineering Drawings  

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  {% assign publications = site.publications | where:"lang", page.lang %}
  <ul>{% for post in publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  {% assign talks = site.talks | where:"lang", page.lang %}
  <ul>{% for post in talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  {% assign teaching = site.teaching | where:"lang", page.lang %}
  <ul>{% for post in teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
