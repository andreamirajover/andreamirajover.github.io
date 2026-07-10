---
layout: page
title: About Me
permalink: /
---

# Hi! I'm Andrea👋

Making my progress with this stuffs 🐢

<img src="{{ '/assets/img/la-meua-foto.jpg' | relative_url }}" style="width:180px; border-radius:50%; float:right; margin-left:20px; margin-bottom:20px;">


<div style="clear: both;"></div> ---

## 📝 Latest Posts

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — <i>{{ post.date | date: "%d/%m/%Y" }}</i>
    </li>
  {% endfor %}
</ul>
