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
* 2021.09 - 2026.09 (expected): Ph.D. in Computer Science and Technology, Nanjing University
* 2017.09 - 2021.06: B.S. in Computer Science and Technology, Nanjing University

Publications
======
<sup>&#42;</sup> denotes first authorship; multiple starred authors indicate equal contribution.

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Academic Services
======
* Conference reviewer: ACL/EMNLP, 2023-2024; ICLR, ICML, and NeurIPS (NIPS), 2025-now
* Teaching assistant: Advanced Programming
