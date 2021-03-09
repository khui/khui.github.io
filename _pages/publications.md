---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}

# You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
Publications
======

Year of 2021
======
Simplified TinyBERT: Knowledge distillation for document retrieval
X. Chen, B. He, Hui, Kai, L. Sun, and Y. Sun
in European Conference on Information Retrieval, ECIR 2021 (To Appear), Springer

Year of 2020
======
BERT-QE: Contextualized queryexpansion for document re-ranking
Z. Zheng, Hui, Kai, B. He, X. Han, L. Sun, and A. Yates
in Proceedings of the 2020 Conference on EmpiricalMethods in Natural Language Processing: Findings, (Online), pp. 4718–4728, Association for Computational Linguistics, Nov. 2020.




Year of 2019
======


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
