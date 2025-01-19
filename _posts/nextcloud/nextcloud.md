---
layout: default
title: "Servidor Casero con Nextcloud"
permalink: /proyectos/nextcloud/
---

# Servidor Casero con Nextcloud

Este proyecto documenta la configuración de un servidor casero utilizando Nextcloud y herramientas avanzadas de monitoreo.

### Actualizaciones del Proyecto

{% for post in site.posts %}
{% if post.categories contains "nextcloud" %}
- [{{ post.title }}]({{ post.url }}) - _{{ post.date | date: "%d de %B de %Y" }}_
{% endif %}
{% endfor %}
