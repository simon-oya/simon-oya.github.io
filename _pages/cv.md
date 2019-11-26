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

Tutorials
======
  <ul>{% for post in site.talks %}
    {% if post.type == 'tutorial' %}
      {% include archive-single-talk-simon.html %}
    {% endif %}
  {% endfor %}</ul>

Conference Talks
======
<ul>{% for post in site.publications %}
  {% if post.type == 'conference' and post.slidesurl %}
    {% include archive-single-talk-simon.html %}
  {% endif %}
{% endfor %}</ul>

<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
