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
  <ul>{% for post in journals reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<h2>Conference Publications</h2>
  <ul>{% for post in proceedings reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
====
  {% assign talks = site.talks | where:"lang", page.lang %}
  <ul>{% for post in talks reversed%}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
====
  {% assign teaching = site.teaching | where:"lang", page.lang %}
  <ul>{% for post in teaching reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Honors&Awards
====

<h2>Research</h2>
* Jan, 2019, Second Prize of the 2018 China Construction Science and Technology Award (rank 3)
* Nov, 2018, Third Prize of the 2018 Beijing Science and Technology Award (rank 4)
* Oct, 2016, Young Elite Scientists Sponsorship Program by the China Association for Science and Technology
* Oct, 2016, RWTH Aachen – Tsinghua Senior Research Fellowship
* Nov, 2014, Best Paper of 17th Conference on Computing in Civil Engineering in China
* Nov, 2014, Best Presentation of Tsinghua University Doctoral Academic Forum

<h2>Teaching</h2>
* Dec, 2019, Excellent Advisor (First Prize) of Student Research Trainning Program of Tsinghua University
* Jul, 2019, Third Prize of the 11th Teaching Competition for Young Faculties in Beijing
* Dec, 2018, First Prize of 8th Teaching Competition for Young Faculties in Tsinghua
* Oct, 2017, Second Prize of Teaching Competition in School of Civil Engineering
* Dec, 2014, Tsinghua “12.9” Graduate Assistant Award
* Aug, 2012, Best Teaching Assistant in School of Civil Engineering, Tsinghua

<h2>Practice</h2>
* Apr, 2016, First Prize of the 4th "Longtu Cup" National Building Information Model (BIM) Competition
* Dec, 2015, Excellence Project Award of the China Construction Industry Association
* May, 2014, First Prize of the 4th "Longtu Cup" National Building Information Model (BIM) Competition

<h2>Education</h2>
* Nov, 2015, Excellent Scholarship for Graduates in Tsinghua
* Jul, 2011, Outstanding Undergraduates of Tsinghua University and the Beijing City
* Dec, 2010, Rising Star of Science & Innovation (undergraduate) in Tsinghua, candidate for the Special Scholarship of Tsinghua (Top 10 in the university)
* Dec, 2009, First Prize of the 15th Structure Design Competition in Tsinghua
* Oct, 2009, Academic Gold Medal from School of Aerospace Engineering in Tsinghua
* Aug, 2009, Special Award of the 7th National Zhou Peiyuan Mechanics Competition for College Students
  
Service and leadership
====
* Member of building information modeling committee of China Graphics Society
* Special Expert of building information modeling center of Beijing City Planning Society
* Reviewer of _Automation in Construction_
* Reviewer of _Journal of Computing in Civil Engineering_
* Reviewer of _IEEE Transactions on Systems, Man and Cybernetics: Systems_
* Reviewer of _Journal of Management in Engineering_
* Reviewer of _Journal of Structural Integrity and Maintenance_
* Reviewer of _Frontiers of Engineering Management_
* Reviewer of _Mobile Information Systems_
* Reviewer of _Journal of Tsinghua University (Science & Technology)_
* Reviewer of _China Civil Engineering Journal_
* Reviewer of _Journal of Graphics_
* Reviewer of _Construction Technology_
* Reviewer of _Journal of Information Technology in Civil Engineering and Architecture_
