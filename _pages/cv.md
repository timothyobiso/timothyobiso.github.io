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
* Ph.D in Computer Science, Brandeis University, (in progress)
* M.S. in Computational Linguistics <i>with High Honors</i>, Brandeis University, 2024
* B.A. in Linguistics <i>with Honors</i> and Chinese Language and Literature, Boston University, 2022

Awards
======
* Award for Outstanding Contributions to Research and Teaching by a Computational Linguistics MS Student, 2024
* Barbara Argote Senior Award in Chinese Language and Literature, 2022
* Barbara Argote Junior Award in Linguistics, 2021

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
