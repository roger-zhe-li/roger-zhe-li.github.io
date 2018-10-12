---
layout: archive
title: "Publications [(Google Scholar Profile)](https://scholar.google.com/citations?user=_GDQBHcAAAAJ&hl=en)"
permalink: /publications/
author_profile: true
---


**Zhe Li**, *Towards the next generation of multi-criteria recommender systems*, ACM Conference on Recommender Systems, **RecSys'18** (Doctoral Symposium Paper)<br>
\[[pdf](https://roger-zhe-li.github.io/files/recsys18.pdf)\]\[poster\]



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
