---
layout: archive
title: "Publications & Preprints"
permalink: /publications/
author_profile: true
---

{% include base_path %}

You can also find a full list of my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=EW_hy6cAAAAJ).

## Journal Publications
{% assign journal_papers = site.publications | where: "pubtype", "Journal" | sort: "date" | reverse %}
{% for post in journal_papers %}
  {% include archive-single.html %}
{% endfor %}

## Conference Publications
{% assign conference_papers = site.publications | where: "pubtype", "Conference" | sort: "date" | reverse %}
{% for post in conference_papers %}
  {% include archive-single.html %}
{% endfor %}

## Preprints
{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}