---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Department of Informations and Communications Engineering, Tokyo Institute of Technlogy, 2024.04
* B.S. in School of Automation, Beijing Institute of Technlogy, 2021.06

Work experience
======
* 2025.01 - Present: Researcher & Algorithm Developer
  * SINOMACH Sensing Technology Co., Ltd, Shenyang Academy of Instrumentation and Science Co., Ltd
  * Research Topics: Pipeline Magnetic Flux Leakage Detection, Computer Vision, Deep Learning


Skills
======
* Python
* Pytorch
* C#

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

