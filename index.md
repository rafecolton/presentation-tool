---
title: stuff
layout: default
---

Other Docs
======
* [README.md](README.html)

Presentations
=============
{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}
