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
* **Oct 2019 - Present** - Postdoctoral Fellowship *(University of Waterloo, Canada)*
* **July 2019 - Aug 2019** - Research Associate *(University of Vigo, Spain)*
* **Sept 2014 - July 2019** - PhD Program on Information Technologies and Communications *(University of Vigo, Spain)*
* **April 2018 - June 2018** - Predoctoral Research Fellowship *(École polytechnique fédérale de Lausanne, Switzerland)*
* **Nov 2015 - May 2016** - Predoctoral Research Fellowship *(Rutgers, the State University of New Jersey)*
* **Nov 2012 - Sept 2014** - MSc in Signal Theory and Communications *(University of Vigo, Spain)*
* **Sept 2016 - Nov 2012** - BSc in Telecommunication Engineering *(University of Vigo, Spain)*


<!-- Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Journal Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'journal' %}
      {% include archive-single-simon.html %}
    {% endif %}
  {% endfor %}</ul>

Conference Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'conference' %}
      {% include archive-single-simon.html %}
    {% endif %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
