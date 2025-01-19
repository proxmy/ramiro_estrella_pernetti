---
layout: home
title: "Inicio"
---

### ¡Hola, soy Ramiro Estrella Pernetti!

Bienvenido a mi sitio web profesional. Soy técnico de redes y microinformática, apasionado por la tecnología y con experiencia en administración de servidores, gestión de infraestructuras y desarrollo de proyectos IT.

---

### 🌐 Encuéntrame

<a href="https://www.linkedin.com/in/ramiropernetti" target="_blank">
  <img src="{{ site.baseurl }}/assets/images/linkedin-icon.png" alt="LinkedIn" style="width: 30px; margin-right: 10px;">
</a>
<a href="mailto:tomasestrellaramiro@gmail.com">
  <img src="{{ site.baseurl }}/assets/images/email-icon.png" alt="Correo" style="width: 30px;">
</a>

---

### 🚀 Proyectos Destacados

1. **Servidor Casero con Nextcloud en Raspberry Pi 4**
   - Implementación de un servidor privado utilizando Docker y monitoreo con Prometheus y Grafana.
   - [Leer más](/blog/servidor-casero-nextcloud/)

2. **Infraestructura de Monitoreo para Redes Empresariales**
   - Creación de una solución escalable con VMware y herramientas de análisis.
   - [Leer más](/blog/infraestructura-monitoreo-redes/)

---

### 📚 Últimas Publicaciones

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - _{{ post.date | date: "%d de %B de %Y" }}_
{% endfor %}
