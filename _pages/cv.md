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
* M.S. in AI, IIT Delhi, 2026
* B.Tech. in Mechanical Engineering, IIT Indore, 2023

Work experience
======
* 2023- 2024: Fractal Analytics
  * Quantum Computing Research Lab
  * Duties includes: Updates and improvements to template
  
Skills
======
* C++
* Python
  * PyTorch
  * Huggingface
  * Pennylane
* Machine Learning

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
  
Service and leadership
======
* Ex-President, Debating Society, IIT Indore
