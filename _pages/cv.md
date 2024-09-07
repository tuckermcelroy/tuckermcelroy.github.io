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
* Ph.D in Mathematics, University of California San Diego, 2001
* B.A. in Mathematics, Columbia University, 1996

Work experience
======
* January 2018 - Present: Senior Time Series Mathematical Statistician
  * U.S. Census Bureau
  * Time series research, consulting, and mentoring

* April 2007 - January 2018: Principal Researcher 
  * U.S. Census Bureau
  * Time series research, consulting, and mentoring

* September 2003 - April 2007: Mathematical Statistician
  * U.S. Census Bureau
  * Time series research and consulting
  
Skills
======
* Statistical research
* Writing and publishing scientific papers
* R, RCPP, R Markdown, ...

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
* Council of sections representative for Business and Economics Section of the American Statistical Association
