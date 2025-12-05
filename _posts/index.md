---
title: "Blog"
layout: default
permalink: /blog/
---
# Blog Posts

{% for post in site.posts %}
- [**{{ post.title }}**]({{ post.permalink }}) ({{ post.date | date: "%Y-%m-%d" }})
  {{ post.excerpt }}
{% endfor %}
---
title: "Titolo del Post"
date: 2023-01-01
layout: post
permalink: /blog/2023/01/01/titolo-post/
excerpt: "Breve anteprima del post."
---
## Contenuto
Testo del post...
