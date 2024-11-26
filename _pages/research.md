---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 18px;
  display: none;
  overflow: hidden;
  background-color: #f1f1f1;
}
</style>
</head>

I am broadly interested in computer security and privacy problems.
My research studies these problems from a *statistical perspective*, using theoretical tools to quantify the privacy leakage of different systems and design strong defenses.
Click on the following research lines to learn more about them.
<!-- - Privacy-preserving searchable encryption.
- Privacy-preserving machine learning.
- Anonymous communication systems.
- Differential privacy. -->

<button type="button" class="collapsible">Privacy-Preserving Searchable Encryption</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>
<button type="button" class="collapsible">Open Section 2</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>
<button type="button" class="collapsible">Open Section 3</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>



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

<img src="/images/image-alignment-580x300.jpg" alt="Drawings Sprite">

<img src="/images/image-alignment-1200x4002.jpg" alt="Drawings Sprite">


<ul>{% for post in site.publications reversed %}
    {% if post.area == 'ml' %}
        <li>{% include archive-single-simon.html %}</li>
    {% endif %}
{% endfor %}</ul>


</details>
