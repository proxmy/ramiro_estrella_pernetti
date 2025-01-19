---
layout: default
title: "Servidor Casero con Nextcloud"
permalink: /proyectos/nextcloud/
---

# Servidor Casero con Nextcloud

## Introducción

Este proyecto consiste en la implementación de un servidor casero utilizando **Nextcloud** en una **Raspberry Pi 4**. El objetivo es crear una nube privada eficiente, escalable y con herramientas de monitoreo avanzadas.

### Objetivos:
- Almacenar y gestionar archivos de manera privada.
- Monitorear el rendimiento del servidor utilizando herramientas como **Prometheus** y **Grafana**.
- Mejorar la seguridad mediante prácticas recomendadas y herramientas como **Fail2ban**.

---

## Actualizaciones del Proyecto

{% for post in site.posts %}
{% if post.categories contains "nextcloud" %}
- [{{ post.title }}]({{ post.url }}) - _{{ post.date | date: "%d de %B de %Y" }}_
{% endif %}
{% endfor %}
