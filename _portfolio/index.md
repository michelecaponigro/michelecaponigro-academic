---
title: "Portfolio"
layout: default
permalink: /portfolio/
---
# My Portfolio

Ecco alcuni dei miei progetti:

{% for project in site.portfolio %}
- [**{{ project.title }}**]({{ project.permalink }})
  {{ project.excerpt }}
{% endfor %}
---
title: "Nome del Progetto"
date: 2023-01-01
layout: portfolio
permalink: /portfolio/2023-project/
excerpt: "Breve descrizione del progetto."
---
## Descrizione
Dettagli sul progetto...
