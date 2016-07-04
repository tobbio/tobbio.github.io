---
layout: article
title: "Esce Wordpress, entra Jekyll"
subheadline: Sito
excerpt: "Grandi novità: sono passato da Wordpress a Jekyyl: cosa è cambiato?"
categories: 
  - News
tags: 
  - Sito
  - blog
  - Jekyll
  - Wordpress
header: 
  image_fullwidth: "panorama-pana.jpg"
image: 
  title: "jekyll-logo.png"
  thumb: "jekyll-logo.png"
  caption: null
  caption_url: null
sidebar: right
comments: true
published: true
---

Da un po' di tempo andavo pensandoci:

> Wordpress è un gran bel CMS, molto potente e flessibile, probabilmente eccessivo per queste poche pagine che mi ritrovo, passiamo a qualcosa di più performante e snello, magari anche senza database.

Così, nel -poco- tempo libero ho iniziato a guardarmi in giro per trovare alternative: ho valutato, più o meno velocemente, l'utilizzo di diversi CMS sviluppati sempre in PHP, ma, appunto, *databaseless*:

- *RazorCMS* 
- *Monstra*
- *Pluck*
- *Flatpress*
- *GetSimple CMS*
- *Kirby (pagamento)*
- *Statamic (pagamento)* 

...e sicuramente ne dimentico altri. 

Mi sono poi soffermato di più su *Nibbleblog* e *Htmly*, pensando di aver trovato quello che cercavo: velocità, facilità di utilizzo, personalizzazione sufficiente senza dover metterci troppo le mani...

Forse però la facilità di utilizzo era troppa, così giustamente ho pensato che potevo complicarmi un pochino la vita!

### E Jekyll?!
Così mi è venuto in mente *Jekyll*, il famoso generatore di siti statici scritto in *Ruby* che è alla base di *Github Pages*. 
*Ruby*? Oddio, non saprei dove mettere le mani! :/
Calma, basta editare pochi file di configurazione, post e pagine si trovano su singoli file, scritti semplicemente in **Markdown**.
D'accordo, non è come usare un editor WYSIWYG, ma ci si abitua velocemente.
Infine basta eseguire ```jekyll build``` e voilà, delle belle paginette html pronte a essere caricate sul server.
Però aspetta, vuol dire che per usare Jekyll devo installare Ruby sul pc! Non necessariamente, perchè ora entra in gioco **Github Pages**: hosting gratuito per pagine statiche (PHP non supportato) ma anche... Jekyll installato sui loro server: ergo per aggiornare il nostro blog basterà *pushare* il nostro file .md nella cartella **_posts** e automaticamente nel giro di poche manciate di secondi sarà stato generato e pubblicato. Comodo, no? Hosting praticamente a costo zero, potete sempre configurare i DNS del vostro dominio e  farli puntare a Github.
Per Android esiste l'ottima app [*MrHyde*](https://play.google.com/store/apps/details?id=org.faudroids.mrhyde), che fa sia il lavoro di un editor sia quello di un client GIT. 
Dopo aver provato diversi temi, ho trovato in *Feeling responsive* quello che fa per me: qualche modifica qua e là  ed ecco che il mio nuovo blog/sito inizia a prendere forma.
