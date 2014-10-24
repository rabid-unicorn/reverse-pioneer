---
layout: page
title: Memoir of a Reverse Pioneer
tagline: A Physioemotional Examination of the Fiber of my Being
---
{% include JB/setup %}

## Chapters

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.category }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


