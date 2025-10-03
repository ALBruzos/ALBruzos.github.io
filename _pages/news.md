---
title: "Latest news of Bruzos lab"
permalink: /news/
author_profile: true
redirect_from: 
  - "/ag/"
---
<img src='/images/WebsiteSections_v1-08.png'>  

{% for post in site.awardsgrants %}
  {% include archive-single.html %}
{% endfor %}






<!---to comment ---> 

<!--- 
this does not work:
{% for post in site.news %}
  {% include archive-single.html %}
{% endfor %}


* **Get a PDF copy of our latest published research here**: [Bruzos AL, et al. (2023). Somatic evolution of marine transmissible leukemias in the common cockle, Cerastoderma edule. Nature Cancer 4, 1575–159](https://albruzos.github.io/publication/2023-10-02-PAPER-NatureCancer-EvolutionCockleTransmissibleCancers)
  
---> 
