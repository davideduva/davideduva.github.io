---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can find a detailed version of my CV [here](/files/Davide_Pietro_Duva_CV.pdf).

Education
======
* Ph.D in Applied Mathematics
  * Title: Divergence-free finite elements for direct and inverse problems
  * Advisors: Guillaume Delay, Miguel A. Fernández
  * LJLL (Sorbonne Université) - INRIA (Centre de Paris), December 2024 - today
* MSc in Mathematical Engineering and Mathématiques de la Modélisation
  * Politecnico di Milano - Sorbonne Université
  * September 2022 - July 2025
* BSc in Ingegneria Matematica
  * Politecnico di Milano
  * September 2019 - September 2022


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
