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
* PhD in Biological Sciences, University of Liverpool, 2020 
* Bsc (hons) in Zoology, University of Glasgow, 2015

Work history
======
* February 2023 - Present: Research Fellow
  * London School of Hygiene and Tropical Medicine
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* July 2019 - February 2023: Research Assistant
  * University of Glasgow
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Society Memberships
======
* Royal Statistical Society (Fellow)
  * Committee Member, Glasgow Local Group
* British Ecological Society (2015 - 2021)
  * Committee Member, Quantitative Ecology Special Interest Group (2016 -2021)

Service and leadership
======
* Currently signed in to 43 different slack teams


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
  

