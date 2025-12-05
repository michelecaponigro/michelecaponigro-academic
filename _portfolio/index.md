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
