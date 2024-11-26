---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: #949494;
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
  background-color: #d7d7d7;
}

.content {
  padding: 0 18px;
  display: none;
  overflow: hidden;
  background-color: #eaeaea;
}
</style>
</head>
<body>


<p>I am broadly interested in computer security and privacy problems.
My research studies these problems from a <em>statistical perspective</em>, using theoretical tools to quantify the privacy leakage of different systems and design strong defenses.
Click on the following research lines to learn more about them.</p>

<button type="button" class="collapsible">Machine Learning Privacy</button>
<div class="content">
    <img src="/images/topic-ml.png" alt="ML topic">
  <p>This is a description of the ML research line</p>
</div>
<button type="button" class="collapsible">Privacy-Preserving Searchable Encryption</button>
<div class="content">
    <img src="/images/topic-sse.png" alt="SSE topic">
  <p>Description of SSE.</p>
</div>
<button type="button" class="collapsible">Anonymous Communications</button>
<div class="content">
    <img src="/images/topic-anon.png" alt="Anonymous coms topic">
  <p>Description of location privacy.</p>
</div>
<button type="button" class="collapsible">Location Privacy</button>
<div class="content">
    <img src="/images/topic-location.png" alt="Location privacy topic">
  <p>Description of mixes.</p>
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

</body>
</html>
