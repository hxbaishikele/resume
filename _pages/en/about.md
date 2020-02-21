---
permalink: /en/
title: "About me"
lang: en
ref: about
excerpt: "About me"
author_profile: true
redirect_from: 
  - /en/about/
  - /en/about.html
---

Dr. Jia-Rui Lin is currently a research assistant professor at the Disaster Prevention and Mitigation Institute of Tsinghua University, and concurrently the director of the Mechanics Computing and Simulation Laboratory of the Mechanics Experimental Teaching Center of Tsinghua University. He obtained his bachelor's degree (2011) and Ph.D. (2016) from the Department of Civil Engineering of Tsinghua University. After finished his postdoctoral research in 2018, he joined the New Technologies for Disaster Prevention and Mitigation Group of Tsinghua University. Dr. Lin was also visiting scholars of Stanford University, RWTH-Aachen University and University of Southern California.

His research interests are information technology for building and civil engineering, including building information model (BIM), augmented reality (AR) ,cloud computing and internet of things (IoT). He is committed to optimizing performance and improving decision-making process in the construction, operation, maintenance, and disaster prevention of buildings and infrastructures through advanced information technology. In 2016, he was selected as a receiver of Young Elite Scientists Sponsorship Program by the China Association for Science and Technology. At the end of 2018, Dr. Lin was awarded the second prize of the China Construction Science and Technology Award and the third prize of Beijing Science and Technology Award. He also won  the first prize of 8th Teaching Competition for Young Faculties in Tsinghua and the third prize of the 11th Teaching Competition for Young Faculties in Beijing in 2018 and 2019 respectively.

Recently, he was granted by the national natural science foundation, national key R&D program, Beijing natural science foundation, etc. for abount 9 projects, and he has successfully finished about 10 projects funded by the national key R&D Program, national science foundation of China and other organizations, and has published more than 50 peer-reviewed journal and conference papers. He also holds 8 software copyrights. Main contributions include:

* A BIM model targets the whole building lifecycle, which can integrate design information, performance simulation, and sensing data into a single model. The model was tested in the simulation and sensing of building performance and structural performance of bridges.
* BIM-based cloud platform for buildings and infrastructures: a hybrid cloud platform is designed and implemented based on NoSQL databases (including MongoDB and HBase), which can process, search and visualize large-scale information models, and can also integrate data from multi-stakeholders while keeps their data ownership.
* Spatial-semantic data mining of BIM: proposed a series methods for multi-aspect similarity evaluation of BIM models, operation & maintenance data mining, and on-site inspection data mining, which can improve the efficiency of residential design, construction management, and maintenance.

{% include base_path %}

<h2>News</h2>
{% assign news = site.news | where:"lang", page.lang %}
{% assign news = news | slice: -2,2 %}
<ul>{% for post in news reversed%}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
<h2>Recent Publications</h2>
{% assign publications = site.publications | where:"lang", page.lang %}
{% assign publications = publications | slice: -4,4 %}
<ul>{% for post in publications reversed%}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
<h2>Recent Talks</h2>
{% assign talks = site.talks | where:"lang", page.lang %}
{% assign talks = talks | slice: -2,2 %}
<ul>{% for post in talks reversed%}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
<h2>Recent Projects</h2>
{% assign projects = site.projects | where:"lang", page.lang %}
{% assign projects = projects | slice: -2,2 %}
<ul>{% for post in projects reversed%}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
<h2>Recent Teaching Activities</h2>
{% assign teaching = site.teaching | where:"lang", page.lang %}
{% assign teaching = teaching | slice: -2,2 %}
<ul>{% for post in teaching reversed%}
  {% include archive-single-cv.html %}
{% endfor %}</ul>