---
layout: page
title: Prior Meetings
permalink: /prior/
---

<ul>
  {% for post in site.posts offset:1 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
