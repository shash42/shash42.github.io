---
permalink: /
title: "Shashwat Goel"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an AI researcher, interested in building [general, open-ended training environments](https://shash42.substack.com/p/automated-scientific-discovery-as) that incentivize the emergence of [capabilities today's agents struggle with](https://shash42.substack.com/p/counting-down-capabilities-to-agi). These include decision making<sup><a href="https://openforecaster.github.io/">1</a></sup>, self-verification<sup><a href="https://falsifiers.github.io/">2</a></sup>, collaborative planning<sup><a href="https://www.alphaxiv.org/abs/2512.23707">3</a></sup>, long-horizon execution<sup><a href="https://www.alphaxiv.org/overview/2509.09677v2">4</a></sup>, and efficiently learning from interactions<sup><a href="https://openreview.net/pdf?id=vIddey7z1I">5</a></sup>. I'm pursuing a PhD co-advised by [Jonas Geiping](https://jonasgeiping.github.io/) and [Douwe Kiela](https://douwekiela.github.io/). I write on [Substack](https://shash42.substack.com/), and [X](https://x.com/ShashwatGoel7). I like honest feedback and technical discussions, [reach out](mailto:shashwatnow@gmail.com).

<h2>Highlights</h2>
{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse | slice: 0, 7 %}
{% include news.html news=news %}

<h2>Featured Work</h2>
{% include featured_grid.html
    publications=site.data.publications
%}


<h2>Education</h2>
I love problem solving, and learnt a lot from ecosystems like the International Olympiads of Informatics and Linguistics, Exun Clan, and the broader tech circuit in Delhi. I'm also grateful for mentorship from [Amartya Sanyal](https://amartya18x.github.io/), [Ameya Prabhu](https://drimpossible.github.io/), [Dan Hendrycks](https://people.eecs.berkeley.edu/~hendrycks/), [Dominik Peters](https://dominik-peters.de/), [Mikel Forcada](https://www.dlsi.ua.es/~mlf/), [Mukesh Kumar](https://www.ikkumpal.com/), [Jérôme Lang](https://www.lamsade.dauphine.fr/~lang/), [Jorge Gracia](http://jogracia.url.ph/web/), [Ponnurangam Kumaraguru](https://precog.iiit.ac.in/), [Saujas Vaduguru](https://saujasv.github.io/), and [Tanmoy Bhattacharya](https://sites.santafe.edu/~tanmoy/cv.html). Thanks to them, I have been able to explore a diverse range of research areas, including Machine Learning, Interpretability of LLMs, Social Choice Theory, Machine Translation, Semantic Evolution and Algorithm Design.
