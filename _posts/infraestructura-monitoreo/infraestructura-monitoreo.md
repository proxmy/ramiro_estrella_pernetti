---
layout: default
title: "Infraestructura de Monitoreo"
permalink: /proyectos/infraestructura-monitoreo/
---

# Infraestructura de Monitoreo Empresarial

Este proyecto describe la creación de una infraestructura escalable para monitorear redes empresariales.

### Actualizaciones del Proyecto

{% for post in site.posts %}
{% if post.categories contains "infraestructura-monitoreo" %}
- [{{ post.title }}]({{ post.url }}) - _{{ post.date | date: "%d de %B de %Y" }}_
{% endif %}
{% endfor %}
