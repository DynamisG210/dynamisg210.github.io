---
layout: page
title: Blog
permalink: /blog/
---

# Blog

{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }} · [{{ post.title }}]({{ post.url }})
{% endfor %}
