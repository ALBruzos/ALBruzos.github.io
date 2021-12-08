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

| Year  | Journal | Impact Factor<sup>*</sup> | First authorship |
| ------------- | ------------- | ------------- | ------------- |
| 2021  | Nature Communications  | NA  | Álvarez, E. G. et al. |
| 2020  | Nature Genetics  | 38.33 | Rodriguez-Martin, B. et al. |
| 2020  | Nature  | 49.96 | The ICGC/TCGA Pan-Cancer Analysis of Whole Genomes Consortium. |

<sup>*</sup>Web of Science IF data relative to the publication year

**More information:**  
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
