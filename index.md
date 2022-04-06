---
layout: page
title: Welcome!
---

{% for post in site.posts limit:1 %}
  {{post.content}}
{% endfor %}
