---
permalink: /
title: "Shashwat Goel"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an AI researcher, currently co-advised by [Jonas Geiping](https://jonasgeiping.github.io/) and [Douwe Kiela](https://douwekiela.github.io/) through the ELLIS PhD program. I work on novel ways to scale **supervision** for models, to make them more *useful* and *safe*. As we exhaust performance that can be achieved by training on human demonstrations, I am interested in learning from ground-truth rewards in open-ended tasks, and leveraging the generator-verifier gap. I think a lot about designing evaluations for different aspects of intelligence, as I believe any capability that can be measured can be optimized.Capabilities I am currently interested in include: 
- Seeking information by asking the right questions
- Falsifying wrong claims
- Reasoning about conflicting evidence and preferences
- Solving novel problems
- Personalization

If you're interested in these problems too, [reach out](mailto:shashwatnow@gmail.com), I like getting E-Mail!

<h2>News</h2>
{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse | slice: 0, 7 %}
{% include news.html news=news %}


<h2>Selected Publications</h2>
{% include publications.html
    publications=site.data.publications
    numbering=false
%}

I love problem solving, and benefitted a lot from ecosystems like International Olympiads (Informatics and Linguistics), Exun Clan, and the broader tech circuit in Delhi. I'm also grateful for mentorship from [Amartya Sanyal](https://amartya18x.github.io/), [Ameya Prabhu](https://drimpossible.github.io/), [Dan Hendrycks](https://people.eecs.berkeley.edu/~hendrycks/), [Dominik Peters](https://dominik-peters.de/), [Mikel Forcada](https://www.dlsi.ua.es/~mlf/), [Mukesh Kumar](https://www.ikkumpal.com/), [Jérôme Lang](https://www.lamsade.dauphine.fr/~lang/), [Jorge Gracia](http://jogracia.url.ph/web/), [Ponnurangam Kumaraguru](https://precog.iiit.ac.in/), [Saujas Vaduguru](https://saujasv.github.io/), and [Tanmoy Bhattacharya](https://sites.santafe.edu/~tanmoy/cv.html). Thanks to them, I have been able to explore a diverse range of research areas, including Machine Learning, Interpretability of LLMs, Social Choice Theory, Machine Translation, Semantic Evolution and Algorithm Design.
