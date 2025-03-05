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
* M.Cs in Information System, Diponegoro University, 2024
* B.Cs in Informatics, Telkom University Purwokerto, 2016
  
Work experience
======
* 2025-now: Informatics Lecturer
  * Karya Husada University
  * Duties includes: Education and teaching, research and development, and community service.

* 2022-2024: Information Technology Teacher
  * Telkom Vocational High School Purwokerto
  * Duties included: Education and teaching, student academic improvement
  
Skills
======
* Machine Learning
* Deep Learning
* Natural Language Processing
* Big Data Analytics
* Network Engineering

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
