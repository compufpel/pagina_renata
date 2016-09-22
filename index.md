---
layout: single
author_profile: true
header:
  image: bannerlups.jpg
sidebar:
---
## About me

Possui graduação em Matemática - Licenciatura Plena pela Universidade Católica de Pelotas (1981), mestrado em Ciências da Computação pela Universidade Federal do Rio Grande do Sul (1997) e doutorado em Ciências da Computação pela Universidade Federal do Rio Grande do Sul (2002). Atualmente é professor adjunto da [Universidade Federal de Pelotas](http://www.ufpel.edu.br). Tem experiência na área de [Ciência da Computação](http://inf.ufpel.edu.br/ccomp/), sendo que as linhas de pesquisa em que atualmente está atuando são Fundamentos da Computação, Computação Científica e Processamento Paralelo e Distribuído. Os principais temas são Modelos Computacionais Paralelos e Distribuídos, Lógica Fuzzy, Matemática Intervalar, Computação Quântica e Teoria dos Domínios e Aplicações. 


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
