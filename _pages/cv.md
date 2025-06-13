---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Publications
======
 <ul>{% for post in site.publications %}
   {% include archive-single-cv.html %}
 {% endfor %}</ul>

Writing Examples
======
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

Education
======
* M.A. in Mass Communication, Texas Tech University, 2023
* B.A. in Electronic Media & Communication, Texas Tech University, 2014