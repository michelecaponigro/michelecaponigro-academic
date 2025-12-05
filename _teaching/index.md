---
title: "Teaching"
layout: default
permalink: /teaching/
---
# Teaching Activities
{% for item in site.teaching %}
  - [**{{ item.title }}**]({{ item.permalink }}) ({{ item.date | date: "%Y-%m-%d" }})
{% endfor %}
