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
* Ph.D in Biostatistics, Harvard University, 2006
* M.S. in Biostatistics, Harvard University, 2003
* B.S. in Math and Statistics, Utah State University, 2001

Academic Positions
======
* Professor of Biostatistics, Boston University, 2006-Present
* Associate Director, Center for Health Data Science
* Co-director, Surveillance and Data Science Core, Center on Emerging Infectious Diseases
* Co-director, Graduate Program in Biostatistics, 2016-Present
  
Skills
======
* Advanced statistical methods
* Mentorship
* Academic Leadership

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

