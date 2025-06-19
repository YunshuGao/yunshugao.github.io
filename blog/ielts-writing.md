---
layout: default
title: IELTS Writing Practice
permalink: /blog/ielts-writing/
---

# IELTS Writing practice 🌏

This is where I log my writing Task 1 and Task 2 practices.

---

## Latest Writing Posts

{% for post in site.categories.ielts_writing %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}



