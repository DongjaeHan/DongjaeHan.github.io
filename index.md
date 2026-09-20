---
layout: default
title: Home
---

Physics, research, and programming notes.

## Posts

{% for post in site.posts %}

- [{{ post.title }}]({{ post.url | relative_url }})  
  {{ post.date | date: "%Y-%m-%d" }}

{% endfor %}
