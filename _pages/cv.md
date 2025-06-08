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
* Ph.D in Machine Learning, Georgia Institute of Technology, 2028 (expected)
* M.S. in Electrical and Computer Engineering, Georgia Institute of Technology, 2023
* B.S. in Applied Mathematics, University of California Los Angeles, 2020
* B.S. in Material Science and Engineering (Electronics), University of California Los Angeles, 2020


Skills
======
* Machine Learning (I guess?)


Publications
======
*A selection of my publications is listed below. Please note that some the previous publications I am in are not pertinent to my current field. For a complete list, please see my [Google Scholar profile](https://scholar.google.com/citations?user=EW_hy6cAAAAJ).*

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>