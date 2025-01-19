---
layout: page
title: "Blog"
permalink: /blog/
---

### Publicaciones del Blog

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - _{{ post.date | date: "%d de %B de %Y" }}_
{% endfor %}
