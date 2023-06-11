---
layout: default
title: Cabrio Life
description: The adventures of white Yugo Cabrio.
---

# {{ page.title }}

{{ page.description }}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
