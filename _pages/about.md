---
permalink: /
title: "Shashwat Goel"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an incoming PhD student at the ELLIS Institute and Max Planck Institute for Intelligent Systems, Tübingen, co-advised by [Jonas Geiping](https://jonasgeiping.github.io/) and [Douwe Kiela](https://douwekiela.github.io/) through the ELLIS PhD program. I am interested in how to make ML systems learn when humans can't provide unambgious ground-truth: whether it be handling conflicting preferences, asking information-seeking questions, or solving novel problems. Feel free to get in touch if you want to chat about ideas! I'm excited about:
- The science of pretraining task design, data, and evaluations
- Enabling iterative improvement of ML models
- Using AI to democratize education and research

<h3>News</h3>
{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse | slice: 0, 7 %}
{% include news.html news=news %}


<h3>Publications</h3>
{% include publications.html
    publications=site.data.publications
    numbering=false
%}

I have been fortunate to have excellent collaborators from whom I've learnt a lot. I'm grateful for mentorship from [Amartya Sanyal](https://amartya18x.github.io/), [Ameya Prabhu](https://drimpossible.github.io/), [Dan Hendrycks](https://people.eecs.berkeley.edu/~hendrycks/), [Dominik Peters](https://dominik-peters.de/), [Mikel Forcada](https://www.dlsi.ua.es/~mlf/), [Mukesh Kumar](https://www.ikkumpal.com/), [Jérôme Lang](https://www.lamsade.dauphine.fr/~lang/), [Jorge Gracia](http://jogracia.url.ph/web/), [Ponnurangam Kumaraguru](https://precog.iiit.ac.in/), [Saujas Vaduguru](https://saujasv.github.io/), and [Tanmoy Bhattacharya](https://sites.santafe.edu/~tanmoy/cv.html). Thanks to them, I have been able to explore a diverse range of research areas, including Machine Learning, Interpretability of LLMs, Social Choice Theory, Machine Translation, Semantic Evolution and Algorithm Design.
