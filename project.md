---
layout: default
title: projects
---

<div id="all">
  <h1>Project Posts</h1>
  <ul class="posts">
    {% for category in site.categories %}
      {% if category[0] == 'project' %}
        {% for post in category[1] %}
          <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
      {% endif %}
    {% endfor %}
  </ul>
</div>