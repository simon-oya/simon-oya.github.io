---
layout: archive
title: ""
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
* **Sept 2006 - Nov 2012** - BSc in Telecommunication Engineering *(University of Vigo, Spain)*


Journal Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'journal' %}
      <li>{% include archive-single-simon.html %}</li>
    {% endif %}
  {% endfor %}</ul>

Conference Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.type == 'conference' %}
      <li>{% include archive-single-simon.html %}</li>
    {% endif %}
  {% endfor %}</ul>

PhD Thesis
======
<ul>{% for post in site.publications reversed %}
  {% if post.type == 'thesis' %}
    <li>{% include archive-single-simon.html %}</li>
  {% endif %}
{% endfor %}</ul>

Tutorials
======
  <ul>{% for post in site.talks reversed %}
    {% if post.type == 'tutorial' %}
      <li>{% include archive-single-talk-simon.html %}</li>
    {% endif %}
  {% endfor %}</ul>

Conference Talks
======
<ul>{% for post in site.publications reversed %}
  {% if post.type == 'conference' and post.slidesurl %}
    <li>{% include archive-single-talk-simon.html %}</li>
  {% endif %}
{% endfor %}</ul>


Academic Service
======
**PC member**
* **2023**
  * ACM Conference on Computer and Communications Security (CCS’23)
  * USENIX Security (SEC’23)
  * Privacy Enhancing Technologies Symposium (PETS’23)
* **2022**
  * ACM Conference on Computer and Communications Security (CCS’22)
  * Privacy Enhancing Technologies Symposium (PETS’22)
* **2021**
  * ACM Conference on Computer and Communications Security (CCS’21)
  * Privacy Enhancing Technologies Symposium (PETS’21)
  * Financial Cryptography (FC’21)
* **2020**
  * Financial Cryptography (FC’20)
  * Workshop on Privacy in the Electronic Society (WPES’20)
* **2019**
  * Financial Cryptography (FC’19)

**Journal reviews**
* **2023**
  * IEEE Transactions on Information Forensics and Security (TIFS)
* **2022**
  * IEEE Transactions on Information Forensics and Security (TIFS)
* **2021** 
  * ACM Transactions on Privacy and Security (TOPS)
* **2020** 
  * IEEE Transactions on Information Forensics and Security (TIFS)
  * Journal on Computer Security (JCS)
  * IEEE Transactions on Dependable and Secure Computing (TDSC)
* **2019**
  * Proceedings on Privacy Enhancing Technologies (PoPETs)
  * IEEE Transactions on Information Forensics and Security (TIFS)
  * ACM Transactions on Privacy and Security (TOPS)
  * IEEE Transactions on Dependable and Secure Computing (TDSC)
* **2018**
  * IEEE/ACM Transactions on Networking (TNET)
  * Proceedings on Privacy Enhancing Technologies (PoPETs)
  * IEEE Transactions on Information Forensics and Security (TIFS)
  * ACM Transactions on Privacy and Security (TOPS)
  * IEEE Transactions on Dependable and Secure Computing (TDSC)
* **2017**
  * Proceedings on Privacy Enhancing Technologies (PoPETs)
  * IEEE Transactions on Information Forensics and Security (TIFS)
  * ACM Transactions on Privacy and Security (TOPS)
  * ACM Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT)
  * ACM Transactions on Internet Technology (TOIT)
* **2016**
  * IEEE Transactions on Information Forensics and Security (TIFS)
* **2014**
  * IEEE Transactions on Dependable and Secure Computing (TDSC)
* **2013**
  * International Journal of Information Security (IJIS)



Grants
======
* **2020**
  * University of Waterloo UW-Fields Postdoctoral Fellowship (25,000 CAD).
* **2015**
  * PhD Grant Formación de Profesorado Universitario (FPU) from the Spanish Ministry of Education (61,544€ over 4 years, personal).
  * Grant to undertake a predoctoral fellowship of 6 months at Rutgers, The State University of New Jersey, given by the Fundación Barrié (2,600€, personal).
  * PhD Grant from the Regional Government of Galicia.

* **2011**
  * Erasmus grant to study abroad, given by the Spanish Ministry of Education.
* **2009**
  * Séneca grant to study in another province of Spain, given by the Spanish Ministry of Education.


Awards
======
* **2022**
  * CCS 2022 Best Reviewer Award
* **2014**
  * Best Student Award from the Galician Government.
  * Best Student Award (Premio Extraordinario Fin de Carrera) from the University of Vigo (≈ 3,000€, personal).
* **2006**
  * Best Student Award (secondary education) from the Galician Government (3,000€, personal).

  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    <li>{% include archive-single-teaching-simon.html %}</li>
  {% endfor %}</ul>
