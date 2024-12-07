---
layout: default
title: Humanities
permalink: /blog/humanities/
---

# Humanities

Reflections and tools for teaching Humanities in an engaging way:

## Blog Posts
{% for post in site.categories.humanities %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
