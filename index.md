---
title: stuff
layout: default
---

Other Docs
======
* [README](README.html)

Presentations
=============
{% for post in site.posts %}
  {% if post.title != 'README' %}
* [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
