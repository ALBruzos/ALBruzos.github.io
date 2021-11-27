---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}  

**List:**  

| Year  | Journal | First authorship |
| ------------- | ------------- | ------------- |
| 2021  | Nature Communications  | Álvarez, E. G. et al. |
| 2020  | Nature Genetics  | Rodriguez-Martin, B. et al. |
| 2020  | Nature  | The ICGC/TCGA Pan-Cancer Analysis of Whole Genomes Consortium. |



**More information:**  
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
