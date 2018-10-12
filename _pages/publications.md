---
layout: archive
title: "Publications [(Google Scholar Profile)](https://scholar.google.com/citations?user=_GDQBHcAAAAJ&hl=en)"
permalink: /publications/
author_profile: true
---


<br/>**Zhe Li**, *Towards the next generation of multi-criteria recommender systems* </br> 
ACM Conference on Recommender Systems, **RecSys'18** (Doctoral Symposium Paper)<br>
\[[<u>pdf</u>](https://roger-zhe-li.github.io/files/recsys18.pdf)\]\[[<u>poster</u>\](https://roger-zhe-li.github.io/files/poster_recsys18.pdf)\]



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
