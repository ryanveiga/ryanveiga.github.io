---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

* Ph.D in Economics, University of Wisconsin - Madison, 2020
* B.S. in Physics, Tufts University, 2008

# Work experience

* October 2024 - Present: Data Science Specialist
  * Tufts University
  * Duties include: 
    * Consultation Services for Researchers in Statistics and Data Science
    * Teaching an Introductory R Course
    * Presenting Workshops on R Programming
  * Supervisor: Kyle M. Monahan

  
# Skills

* R
* Python
* Statistics
* Github

# Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
# Talks

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
# Teaching

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
