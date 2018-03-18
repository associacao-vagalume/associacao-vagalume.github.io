---
title: Propósito
permalink: "/proposito/"
layout: pagina
imagem: "/assets/img/paginas/proposito.jpg"
imagem_mobile: "/assets/img/paginas/proposito.jpg"
description: Conheça o propósito do nosso projeto, nossos valores e entenda os oito
  princípios que seguimos para atingir nossa principal missão.
principios:
- nome: Humanismo
  descricao: São as pessoas que transformam sua realidade.
- nome: Criança
  descricao: Tudo começa com ela.
- nome: Leitura
  descricao: Empodera e possibilida a transformação social.
- nome: Mediação
  descricao: Construímos pontes entre as pessoas, comunidades, gerações e os diversos
    saberes.
- nome: Escuta
  descricao: Compreendemos o outro e construímos junto, estabelecendo um diálogo verdadeiro.
- nome: Interesse
  descricao: Toda mudança acontece de dentro para fora.
- nome: Diversidade cultural
  descricao: Conhecer as diferenças e reconhecer as semelhanças para melhor conviver
    em um mundo plural.
- nome: Cultura local
  descricao: Valorização da memória, ancestralidade e saber tradicional nutrem nossas
    raízes e nos fortalecem.
---

{::options parse_block_html="true" /}

<div class="container pagina-proposito">

  Trabalhamos na Amazônia Legal brasileira, uma região muito importante para
  o Brasil, pois ela cobre 61% do nosso território e é o lar de 24 milhões de
  brasileiros. Além disso, ela tem 1/5 da reserva florestal do planeta e 1/5 da
  água doce disponível na Terra.

  Mas, ao mesmo tempo, tem baixos Índices de Desenvolvimento Humano. Por
  exemplo, o IDH do Brasil é 0,754 e o IDH da Região Norte é 0,667. E mais, os
  10 municípios com os piores IDH estão na região Norte[^1] e 20% da sua
  população é analfabeta funcional[^2].

  Fonte: Atlas de Desenvolvimento Humano do Brasil (PNUD - 2013).
  {: .fonte }

  [^1]: Dentre os 5.565 municípios presentes no Atlas do Desenvolvimento Humano no
        Brasil, em 2013, os 10 piores estão na região Norte.

  [^2]: PNAD 2015: Média Brasil é 17%.

</div>

{::options parse_block_html="false" /}

{% include_relative _includes/proposito.html proposito=site.data.proposito.descricao %}
{% include_relative _includes/principios.html %}