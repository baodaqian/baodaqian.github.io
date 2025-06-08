---
layout: archive
title: "Publications & Preprints"
permalink: /publications/
author_profile: true
---

{% include base_path %}

You can also find a full list of my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=EW_hy6cAAAAJ).

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Preprints

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}