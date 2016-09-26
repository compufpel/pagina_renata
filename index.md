---
layout: single
author_profile: true
header:
  image: bannerlups.jpg
sidebar:
---
## About me
Renata Hax Sander Reiser received her B.Sc. degree in Mathematics from the Catolic University of Pelotas (1981), M.Sc. degree in Computer Science from the Federal University of Rio Grande do Sul (1997) and Ph.D. in Computer Science from the Federal University of Rio Grande do Sul (2002).
  At present, she is an Associate Professor in the Federal University of Pelotas, Cen-tre for Technological Development. Her research experience covers Foundations of Computing, Scientific Computing, and Parallel and Distributed Computing. Her main research interests include Models of Parallel and Distributive Computation, Fuzzy Logic, Interval Mathematics, Quantum Computing, Domain Theory, and their applications.

## Address

Computação -- CDTEC <br>
R. Gomes Carneiro, 1 <br>
Centro <br>
96010-610 <br>
Pelotas, RS, Brazil <br>


{% include base_path %}
<!--
<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3> -->

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
