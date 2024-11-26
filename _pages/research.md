---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I am broadly interested in computer security and privacy problems.
My research studies these problems from a *statistical perspective*, using theoretical tools to quantify the privacy leakage of different systems and design strong defenses.
- Privacy-preserving searchable encryption.
- Privacy-preserving machine learning.
- Anonymous communication systems.
- Differential privacy.

<details>
<summary><b>Privacy-preserving Searchable Encryption</b></summary>

<img src="/images/sprites-v0.png" alt="Drawings Sprite">

{% include base_path %}

<ul>{% for post in site.publications reversed %}
    {% if post.area == 'sse' %}
        <li>{% include archive-single-simon.html %}</li>
    {% endif %}
{% endfor %}</ul>


</details>



<details>
<summary><b>Privacy-preserving machine learning</b></summary>

<img src="/images/image-alignment-150x150.jpg" alt="Drawings Sprite">

<img src="/images/image-alignment-300x200.jpg" alt="Drawings Sprite">

<img src="/images/image-alignment-310x150.jpg" alt="Drawings Sprite">

<img src="/images/image-alignment-310x310.jpg" alt="Drawings Sprite">


<ul>{% for post in site.publications reversed %}
    {% if post.area == 'ml' %}
        <li>{% include archive-single-simon.html %}</li>
    {% endif %}
{% endfor %}</ul>


</details>
