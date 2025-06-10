---
permalink: /
title: "Shashwat Goel"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an AI researcher, currently co-advised by [Jonas Geiping](https://jonasgeiping.github.io/) and [Douwe Kiela](https://douwekiela.github.io/) through the ELLIS PhD program. I am interested in novel ways to scale **supervision** for models, to make them more *useful* and *safe*. My current work focuses on improving evaluations, as I believe any capability that can be measured can be optimized. As we exhaust performance that can be achieved by training on human demonstrations, I am interested in making models learn from scalable, yet grounded rewards in open-ended, long-horizon settings. The goal is to build AI capabilities that can accelerate research: 
- Reasoning: planning tool-use, and about conflicting evidence or uncertainty
- Curiosity: seeking information by asking the right questions
- Falsifying: identifying mistakes in claims, hypotheses, solutions
- Novelty: coming up with creative solutions to challenging problems
- Personalization: memory, increasing productivity in human-AI collaboration

If you're interested in any of these problems, [reach out](mailto:shashwatnow@gmail.com), I like getting E-Mail!

<h2>News</h2>
{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse | slice: 0, 7 %}
{% include news.html news=news %}


<h2>Selected Publications</h2>
{% include publications.html
    publications=site.data.publications
    numbering=false
%}
* denotes equal contribution.

I love problem solving, and learnt a lot from ecosystems like the International Olympiads of Informatics and Linguistics, Exun Clan, and the broader tech circuit in Delhi. I'm also grateful for mentorship from [Amartya Sanyal](https://amartya18x.github.io/), [Ameya Prabhu](https://drimpossible.github.io/), [Dan Hendrycks](https://people.eecs.berkeley.edu/~hendrycks/), [Dominik Peters](https://dominik-peters.de/), [Mikel Forcada](https://www.dlsi.ua.es/~mlf/), [Mukesh Kumar](https://www.ikkumpal.com/), [Jérôme Lang](https://www.lamsade.dauphine.fr/~lang/), [Jorge Gracia](http://jogracia.url.ph/web/), [Ponnurangam Kumaraguru](https://precog.iiit.ac.in/), [Saujas Vaduguru](https://saujasv.github.io/), and [Tanmoy Bhattacharya](https://sites.santafe.edu/~tanmoy/cv.html). Thanks to them, I have been able to explore a diverse range of research areas, including Machine Learning, Interpretability of LLMs, Social Choice Theory, Machine Translation, Semantic Evolution and Algorithm Design.
