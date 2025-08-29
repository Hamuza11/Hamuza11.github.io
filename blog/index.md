---
layout: default
title: Blog
permalink: /blog/
---

# CMD Blog

Willkommen im CMD‑Devlog! Hier teile ich Updates, Einblicke hinter die Kulissen und gelegentlich Tutorials.

## Neueste Beiträge

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
  {% if post.excerpt %}
  
  {{ post.excerpt | strip_html | strip_newlines }}
  {% endif %}
{% endfor %}
