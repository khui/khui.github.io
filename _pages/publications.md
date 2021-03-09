---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}

# You can also find my articles on <u><a href="{{https://scholar.google.com/citations?hl=en&user=VorTj3AAAAAJ}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Year of 2019
======


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
