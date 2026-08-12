---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

 You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=XquZL9gAAAAJ">my Google Scholar profile</a></u> or <u><a href="https://arxiv.org/a/chen_r_3.html">arXiv</a></u>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
