---
layout: page
title:

section : Home
---

I'm a lecturer at Departament of Computing and Information Systems of
[Federal University of Ouro Preto](http://www.ufop.br), Minas Gerais, Brasil.

## Research Interests

- Type theory.
- Programming languages design and implementation.
- Formal verification.

## Teaching Activities

All course information and materials are avaliable at
[Piazza](www.piazza.com). If you don't attend to any of my classes and
want access to the material, please [drop me a line](rodrigo@decsi.ufop.br).

## Blog

In my blog,  _Ex Falsum Quod Libet_, I write about my research activities.

Recent posts:

<ul class="posts">
  {% for post in site.posts limit 10 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Publications

- Mechanized Metatheory for a Lambda-Calculus with Trust
  Types.
  Rodrigo Ribeiro,
  [Lucília Figueiredo](http://www.decom.ufop.br/prof/lucilia),
  [Carlos Camarão](http://www.dcc.ufmg.br/~camarao).
  Journal of the Brazilian Computer Society, 19(4), 433-443, 2013.
  DOI: 10.1007/s13173-013-0119-5. [Coq formalization](http://https://github.com/rodrigogribeiro/trust-calculus).
- Ambiguity and Context-Dependent Overloading.
  Rodrigo Ribeiro, [Carlos Camarão](http://www.dcc.ufmg.br/~camarao).
  Journal of the Brazilian Computer Society, 19(3), 313-324, 2013.
  DOI: 10.1007/s13173-013-0103-0. [Haskell implementation](http://https://github.com/rodrigogribeiro/mptc).
- Terminating Constraint Set Satisfiability and Simplification Algorithms for Context-Dependent Overloading.
   Rodrigo Ribeiro,  [Carlos Camarão](http://www.dcc.ufmg.br/~camarao),
   [Lucília Figueiredo](http://www.decom.ufop.br/prof/lucilia).
   Journal of the Brazilian Computer Society, 19(4), 423-432, 2013.
   DOI: 10.1007/s13173-013-0107-9. [Haskell implementation](http://https://github.com/rodrigogribeiro/mptc).
- Resolvedores SAT para Verificação de Consistência em Modelos de
  Características. Thieres Dias, Eduardo Figueiredo, Rodrigo Ribeiro. In: Simpósio Mineiro de Computação, 2012, Juiz de Fora. Anais do Simpósio Mineiro de Computação, 2012.
- Problema da Programação de Horários Escolares através de SAT e
   Metaheurísticas. George Fonseca, Rodrigo Ribeiro, Flávio Martins. In: 10th Brazilian Congress on Computational Intelligence, 2011, Fortaleza.
   10th Brazilian Congress on Computational Intelligence. , 2011.
- Uma Abordagem Híbrida de SAT e Busca Tabu para o Problema da Programação de Horários Escolares. In: XLIII Simpósio Brasileiro de Pesquisa Operacional, 2011, Ubatuba.
   George Fonseca, Rodrigo Ribeiro, Flávio Martins. XLIII Simpósio
   Brasileiro de Pesquisa Operacional. , 2011.
- A Solution to Haskell's Multi-paramemeter Type Class Dilemma
   [Carlos Camarão](http://www.dcc.ufmg.br/~camarao), Rodrigo Ribeiro, [Lucília Figueiredo](http://www.decom.ufop.br/prof/lucilia), Cristiano Vasconcellos,
   SBLP'2009 (13th Brazilian Symposium on Programming Languages), Gramado, August 19-21, pgs. 5-18, 2009.
