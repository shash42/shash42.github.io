---
permalink: /
title: "Shashwat Goel"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an AI researcher, currently co-advised by [Jonas Geiping](https://jonasgeiping.github.io/) and [Douwe Kiela](https://douwekiela.github.io/) through the ELLIS PhD program. I want to find novel ways to scale **supervision** for models, to make them more *useful* and *safe*.  I believe any capability that can be measured can be optimized. Thus my work focuses on evaluating model capabilities beyond knowledge. Currently, I'm working on tasks which require inductive reasoning to plan under uncertainty, asking better questions, and long-horizon execution.

[See this blog](https://shash42.substack.com/p/counting-down-capabilities-to-agi) for research I'm excited to work on towards building generally intelligent agents. If you're interested in any of these problems, [reach out](mailto:shashwatnow@gmail.com), I like getting E-Mails!

<h2>News</h2>
{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse | slice: 0, 7 %}
{% include news.html news=news %}


<h2>Selected Publications</h2>
{% include publications.html
    publications=site.data.publications
    numbering=false
%}
\* denotes equal contribution.

I love problem solving, and learnt a lot from ecosystems like the International Olympiads of Informatics and Linguistics, Exun Clan, and the broader tech circuit in Delhi. I'm also grateful for mentorship from [Amartya Sanyal](https://amartya18x.github.io/), [Ameya Prabhu](https://drimpossible.github.io/), [Dan Hendrycks](https://people.eecs.berkeley.edu/~hendrycks/), [Dominik Peters](https://dominik-peters.de/), [Mikel Forcada](https://www.dlsi.ua.es/~mlf/), [Mukesh Kumar](https://www.ikkumpal.com/), [Jérôme Lang](https://www.lamsade.dauphine.fr/~lang/), [Jorge Gracia](http://jogracia.url.ph/web/), [Ponnurangam Kumaraguru](https://precog.iiit.ac.in/), [Saujas Vaduguru](https://saujasv.github.io/), and [Tanmoy Bhattacharya](https://sites.santafe.edu/~tanmoy/cv.html). Thanks to them, I have been able to explore a diverse range of research areas, including Machine Learning, Interpretability of LLMs, Social Choice Theory, Machine Translation, Semantic Evolution and Algorithm Design.
