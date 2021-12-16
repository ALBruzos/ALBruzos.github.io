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

| Year  | Journal | Impact Factor<sup>*</sup> | Topic | First authorship |
| ------------- | ------------- | ------------- | ------------- |------------- |
| 2022<sup>#</sup>  | Elife  | 8.14 (2020) | Contagious cancers in clams | yes |
| 2022<sup>#</sup>  | STOTEN  | 7.96 (2020)  | Fingerprints of cockle shells | no |
| 2021  | Nature Communications  | 14.92(2020) | Viral integrations in cancer | no |
| 2020  | Nature Genetics  | 38.33 | Cancer retrotransposition | no |
| 2020  | Nature  | 49.96 | Cancer genomics analysis | no |

<sup># Accepted manuscript, pending publication</sup> 
<sup>* IF taken from Web of Science on the data relative to the publication unless otherwise stated year</sup>

**More information:**  
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
