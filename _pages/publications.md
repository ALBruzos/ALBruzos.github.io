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

| Topic  | Year | Journal | Impact Factor<sup>*</sup> | First authorship |
| ------------- | ------------- | ------------- | ------------- |------------- |
| Contagious cancers in clams | 2022<sup>#</sup>  | Elife  | 8.14 (2020) | yes |
| [Fingerprints of cockle shells](https://albruzos.github.io/publication/2022-01-08-PAPER_STOTEN_CockleShellsFingerprints) | 2022  | STOTEN  | 7.96 (2020)  | no |
| [Viral integrations in cancer](https://albruzos.github.io/publication/2021-10-25-PAPER_NatureCommunications_HeptatitisBintegrations) | 2021  | Nature Communications  | 14.92 (2020) | no |
| [Cancer retrotransposition](https://albruzos.github.io/publication/2020-02-05-PAPER2_NatureGenetics_PCAWG-retrotransposition) | 2020  | Nature Genetics  | 38.33 | no |
| [Cancer genomics analysis](https://albruzos.github.io/publication/2020-02-05-PAPER1_Nature_PCAWG) | 2020  | Nature  | 49.96 | no |

<sup># Accepted manuscript, pending publication</sup> 
<sup>* IF taken from Web of Science on the data relative to the publication unless otherwise stated year</sup>

**More information:**  
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
