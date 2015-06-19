---
layout: default
title: The Logic Of Science
---

<div id="all">
  <h1>Blog Posts</h1>
  <ul class="posts">
  {% for category in site.categories %}
    {% if category[0] == 'blog' %}
      {% for post in category[1] %}
        <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
    {% endif %}
  {% endfor %}
  </ul>
</div>