---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

 You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=XquZL9gAAAAJ">my Google Scholar profile</a></u> or <u><a href="https://arxiv.org/search/?query=Ranyiliu+Chen&searchtype=all&source=header">arXiv</a></u>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
