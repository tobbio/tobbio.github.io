---
categories:
  - News
comment: 
comments: true
date: '2016-01-27'
excerpt: 'Grandi novità: sono passato da Wordpress a Jekyyl: cosa è cambiato?'
header:
  image_fullwidth: panorama-pana.jpg
image:
  caption: null
  caption_url: null
  thumb: jekyll-logo.png
  title: jekyll-logo.png
info: 
layout: article
published: true
sha: 94ced487ca3be3f89dd9808da12aaca35d29df1b
sidebar: right
slug: esce-wordpress-entra-jekyll
subheadline: Sito
tags:
  - Sito
  - blog
  - Jekyll
  - Wordpress
title: 'Esce Wordpress, entra Jekyll'

---



Da un po' di tempo andavo pensandoci:  
WordPress è un gran bel CMS, molto potente e flessibile, probabilmente eccessivo per queste poche pagine che mi ritrovo, passiamo a qualcosa di più performante e snello, magari anche senza database.

Così, nel -poco- tempo libero ho iniziato a guardarmi in giro per trovare alternative: ho valutato, più o meno velocemente, l'utilizzo di diversi CMS sviluppati sempre in PHP, ma, appunto, *databaseless*:

- *RazorCMS* 
- *Monstra*
- *Pluck*
- *Flatpress*
- *GetSimple CMS*
- *Kirby ($$)*
- *Statamic ($$)* 

...e sicuramente ne dimentico altri. 

Mi sono poi soffermato di più su *Nibbleblog* e *Htmly*, pensando di aver trovato quello che cercavo: velocità, facilità di utilizzo, personalizzazione sufficiente senza dover perdere tempo a metterci troppo le mani.

Qui però entra in gioco la mia voglia di complicarmi un pochino la vita...

### E Jekyll?!
Così mi è venuto in mente *Jekyll*, il famoso generatore di siti statici scritto in *Ruby* che è alla base di *Github Pages*.

> *Ruby*? Oddio, non saprei dove mettere le mani! :/

Calma, basta editare pochi file di configurazione, post e pagine si trovano su singoli file, scritti semplicemente in **Markdown**.  
D'accordo, non sarà come usare un editor WYSIWYG, ma una volta imparata la sintassi, è comodissimo.  

Infine basta eseguire ```jekyll build``` e voilà, delle belle paginette html pronte a essere caricate sul server.

> Però aspetta, vuol dire che per usare Jekyll devo installarmi Ruby!

Non necessariamente, perchè ora entra in gioco **Github Pages**: hosting gratuito per pagine statiche (il PHP non è supportato) ma anche... Jekyll installato sui loro server: ergo per aggiornare il nostro blog basterà *pushare* il nostro file .md nella cartella **_posts** e automaticamente nel giro di pochi secondi sarà stato generato e pubblicato.  

Comodo, no? Hosting praticamente a costo zero, potete configurare i DNS del vostro dominio e farli puntare alla tua repository su Github.

Postare in mobilità? Per Android esiste l'ottima app [*MrHyde*](https://play.google.com/store/apps/details?id=org.faudroids.mrhyde), che fa sia il lavoro di un editor sia quello di un client GIT.  

Dopo aver provato -diverse volte- parecchi temi, ho trovato in *[Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll)* quello che fa per me: qualche modifica qua e là  ed ecco che il mio nuovo blog inizia a prendere forma.