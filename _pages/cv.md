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

PhD Thesis
======
<ul>{% for post in site.publications reversed %}
  {% if post.type == 'thesis' %}
    {% include archive-single-simon.html %}
  {% endif %}
{% endfor %}</ul>

Tutorials
======
  <ul>{% for post in site.talks reversed %}
    {% if post.type == 'tutorial' %}
      {% include archive-single-talk-simon.html %}
    {% endif %}
  {% endfor %}</ul>

Conference Talks
======
<ul>{% for post in site.publications reversed %}
  {% if post.type == 'conference' and post.slidesurl %}
    {% include archive-single-talk-simon.html %}
  {% endif %}
{% endfor %}</ul>


Academic Service
======
**Journal reviews**
* IEEE/ACM Transactions on Networking (TNET) (2018).
* Proceedings on Privacy Enhancing Technologies (PoPETs) (2017, 2018, 2019).
* ACM Transactions on Privacy and Security (TOPS) (2017, 2018, 2019).
* ACM Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT) (2017).
* ACM Transactions on Internet Technology (TOIT) (2017).
* IEEE Transactions on Information Forensics and Security (TIFS) (2016, 2017, 2018, 2019).
* Computers \& Security (COSE) (2016).
* Sensors (2016).
* IEEE Transactions on Dependable and Secure Computing (TDSC) (2014, 2018, 2019).
* International Journal of Information Security (IJIS) (2013).
* Computer Communications (2013, 2014).

**Conference reviews as PC member**
* Financial Cryptography (FC) (2019, 2020)

**Conference reviews as external reviewer**
* IEEE Symposium on Security and Privacy (S\&P) (2016, 2017).
* ACM Conference on Computer and Communications Security (CCS) (2013, 2014, 2017, 2018).
* European Symposium on Research in Computer Security (ESORICS) (2013).
* Privacy Enhancing Technologies (PETS) (2013, 2015, 2018, 2019).
* ACM Workshop on Privacy in the Electronic Society (WPES) (2015).
* International Information Security and Privacy Conference (IFIP) (2016).
* IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (2020).
* IEEE International Conference on Multimedia and Expo (ICME) (2015).
* Financial Cryptography and Data Security (FC) (2015, 2016).
* IEEE Workshop on Information Forensics and Security (WIFS) (2014, 2015).
* International Conference on Information Security (ISC) (2014, 2015).

Awards and Grants
======
* PhD Grant *Formación de Profesorado Universitario (FPU)* from the Spanish Ministry of Education (Sept 2015).
* Grant to undertake a predoctoral fellowship of 6 months at Rutgers, The State University of New Jersey, given by the *Fundación Barrié* (July 2015).
* PhD Grant from the Regional Government of Galicia (Apr 2015).
* Best Student Award from the Galician Government (Sept 2014).
* Best Student Award (Premio Extraordinario Fin de Carrera) from the University of Vigo (Jan 2014).
* *Erasmus* grant to study abroad, given by the Spanish Ministry of Education (Sept 2011).
* *Séneca* grant to study in another province of Spain, given by the Spanish Ministry of Education (Sept 2009).
* Best Student Award (secondary education) from the Galician Government (Oct 2006).

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-teaching-simon.html %}
  {% endfor %}</ul>
