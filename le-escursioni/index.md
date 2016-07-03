---
layout: article
title: Escursioni
tags: 
  - escursioni
  - montagna
  - appennini
comments: false
share: false
header: 
  
  image_fullwidth: panorama-pana.jpg
permalink: /escursioni/
published: true
---



> Eppure, le Alpi sono solo la cornice esterna del paese.  
Gli Appennini invece ne sono l'anima, lo stomaco, la colonna vertebrale. E sono lunghi quasi il doppio. Senza di loro, la patria si affloscerebbe come uno Zeppelin senza gas nella pancia. <cite>Paolo Rumiz, La leggenda dei monti naviganti, Feltrinelli</cite>

Fin da piccolo ho amato la montagna e il camminare in genere. Però, nonostante sia nato a due passi dalla Grigna, il mio sguardo si è sempre rivolto a sud anzichè a nord.

L'appennino mi ha sempre affascinato di più. Qui sotto trovate i miei due sogni, sottoforma di trekking a medio raggio e, più giù, un elenco delle mie ultime escursioni.

####[La via del sale, da Montalto Pavese a Portofino](/le-escursioni/via-del-sale/): itinerario recuperato da un numero di Airone di trentanni fa...

####[La via del mare, da Tortona a Portofino](/le-escursioni/via-del-mare/).

Ecco le ultime escursioni, in ordine di regione:

##### PIEMONTE
{% for post in site.categories.Piemonte %}
<li><time class="icon-calendar pr20" datetime="{{ post.date | date: "%d-%m-%Y" }}" itemprop="datePublished"> {{ post.date | date: "%d-%m-%Y" }}</time> <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

##### LIGURIA
{% for post in site.categories.Liguria %}
<li><time class="icon-calendar pr20" datetime="{{ post.date | date: "%d-%m-%Y" }}" itemprop="datePublished"> {{ post.date | date: "%d-%m-%Y" }}</time> <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}