---
layout: default
title: IELTS Speaking Part 1
permalink: /ielts-speaking/part1/
---

# 🗣️ IELTS Speaking – Part 1: Introduction & Interview

Short personal questions about hobbies, studies, work, hometown...

---

{% for post in site.categories.ielts_speaking_part1 %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

