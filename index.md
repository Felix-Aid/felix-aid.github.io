---
---
layout: default
title: "📘 Blog"
---

# 📘 Welcome to My Data Science Blog

Explore articles, tutorials, and project insights.

<ul>
  {% for post in site.posts %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong> — <em>{{ post.date | date: "%B %d, %Y" }}</em>
    </li>
  {% endfor %}
</ul>

