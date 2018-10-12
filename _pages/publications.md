---
layout: archive
title: "Publications [(Google Scholar Profile)](https://scholar.google.com/citations?user=Ixg9n-EAAAAJ&hl=en)"
permalink: /publications/
author_profile: true
---


<br/>**Zhe Li**, *Towards the next generation of multi-criteria recommender systems,* <br> 
ACM Conference on Recommender Systems, **RecSys'18** (Doctoral Symposium Paper)<br>
\[[<u>pdf</u>](https://roger-zhe-li.github.io/files/recsys18.pdf)\]\[[<u>poster</u>](https://roger-zhe-li.github.io/files/poster_recsys18.pdf)\]

<br/> Wei Lu, **Zhe Li**, Jinghui Chu, *Adaptive ensemble undersampling-boost: a novel learning framework for imbalanced data,* <br>
Journal of Systems and Software, 2017, 132: 272-282. **(SCI, IF=2.401)**<br>
\[[<u>pdf</u>](https://roger-zhe-li.github.io/files/JSS.pdf)\]

<br/> Wei Lu, **Zhe Li**, Jinghui Chu, *Adaptive ensemble undersampling-boost: a novel learning framework for imbalanced data,* <br>
Computers in Biology and Medicine, 2017, 83: 157-165. **(SCI, IF=2.115)**<br>
\[[<u>pdf</u>](https://roger-zhe-li.github.io/files/CBM.pdf)\]



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
