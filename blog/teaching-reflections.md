---
layout: default
title: Teaching Reflection
permalink: /blog/teaching-reflection/
---

# 🧑‍🏫 Teaching Reflection

Reflections from my school placements, lessons I observed, and things I’ve learned on my teaching journey.

---

## 📘 Recent Reflections

{% for post in site.categories.teaching %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
