---
layout: default
title: About Me
nav_enabled: true
nav_order: 1
permalink: /index/
---

# Hi! I'm Andrea 👋
Be patient 🐢

<img src="{{ '/assets/img/DSCN1810.JPG' | relative_url }}" style="width: 180px; float: right; margin-left: 20px; margin-bottom: 20px; border-radius: 0 !important;">

<div style="clear: both;"></div>

---

## 📝 Latest Posts

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — <i>{{ post.date | date: "%d/%m/%Y" }}</i>
    </li>
  {% endfor %}
</ul>
