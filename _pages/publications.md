---
layout: archive
title: "Publications and Reviews"
permalink: /publications/
author_profile: true
---
{% include base_path %}  

{% include toc %}

## Publications 
I’ve been fortunate to have worked on several international and interesting research projects in the field of *cancer genomics*. Keep an eye on the space below to see the list of publications my work has contributed to (hopefully!) grow the knowledge of the field...

* Bruzos, AL; Santamarina, M; García, D; ... Tubío, JMC. (2022) The evolution of two transmissible leukaemias colonizing the coasts of Europe. Biorxiv. * denotes first authorship. DOI: doi.org/10.1101/2022.08.06.503021. [Available in BioRxiv](https://www.biorxiv.org/content/10.1101/2022.08.06.503021v1). Accepted on Nature Cancer (publication due in early October).  

 <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Peer-review
My scientific expertise has led me to several invitations to take part in the peer-review system that ensures the rigorous standards of the scientific process. In particular, I have reviewed articles for the following journals:  
<ul class="fa-ul">
  <li><i class="fa-li fa fa-check-square"></i>1 Science. IF(2021)=63.8</li>
  <li><i class="fa-li fa fa-check-square"></i>1 Science Advances. IF(2021)=14.9</li>
  <li><i class="fa-li fa fa-check-square"></i>1 Wiley Molecular Ecology. IF(2022)=6.2 </li>
  <li><i class="fa-li fa fa-check-square"></i>1 Proceedings of the Royal Society B - Biological Sciences. IF(2022)=5.5 </li>
</ul>

All stated reviews have been certified by Publons / Web of Science: [D-7235-2018](https://publons.com/researcher/1404866/alicia-l-bruzos/).


<!---
Este es invertido pero muy largo:

 {% for post in site.publications reversed %}
   {% include archive-single.html %}
 {% endfor %}

Este es invertido pero pequeño:
 {% for post in site.publications reversed %}
   {% include archive-single-cv.html %}
{% endfor %}

Este es orden normal y pequeño:
 <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
--->

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
