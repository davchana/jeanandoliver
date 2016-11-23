---
title: Home
layout: default
permalink: /
---

  {% for post in site.posts %}
  <article class="item">{{ post.date | date_to_string }} – <a href="{{ post.url }}">{{ post.title }}</a></article>
  {% endfor %}
