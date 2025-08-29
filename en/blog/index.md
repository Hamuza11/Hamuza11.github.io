---
layout: default
title: Blog
permalink: /en/blog/
lang: en
---

# Blog

Welcome to the devlog. Updates, behind‑the‑scenes, and tutorials.

## Latest posts

{% assign en_posts = site.posts | where: 'lang', 'en' %}
{% if en_posts and en_posts.size > 0 %}
{% for post in en_posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
{% else %}
No English posts yet.
{% endif %}
