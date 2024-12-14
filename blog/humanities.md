---
layout: default
title: Humanities
permalink: /blog/humanities/
---

# Humanities 🌍

Explore reflections, reading notes, and tools for teaching Humanities in an engaging way.

---

## Sections
- [Teaching Reflections](#teaching-reflections)
- [Reading Notes](#reading-notes)
- [Blog Posts](#blog-posts)

---

### Teaching Reflections 💡
Insights and strategies to teach Humanities effectively:
- **Critical Thinking**: How to foster debate and discussion in the classroom.
- **Engagement Strategies**: Tools to make history, geography, and civics exciting for students.

---

### Reading Notes 📚
Here are my notes and reflections on humanities readings:

{% for post in site.categories.humanities_reading %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
  - **Key Takeaway**: {{ post.excerpt }}
{% endfor %}

---

### Blog Posts 📝
Reflections and tools for teaching Humanities:

{% for post in site.categories.humanities %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
