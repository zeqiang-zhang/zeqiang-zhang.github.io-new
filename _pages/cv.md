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
* Ph.D in Computer Science, Ulm University (Germany), 2027 (expected)
* M.S. in Cognitive Systems, Ulm University (Germany), 2021
* B.S. in Electronic Science & Technology, Southeast University (China), 2019

Work experience
======
* From 2022: Wissenschaftlicher Mitarbeiter
  * Ulm University


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
* Neurotechnology: Brain-Machine Interfacing
* Project Deep Reinforcement Learning
