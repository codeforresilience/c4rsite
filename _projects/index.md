---
layout: default
title: Projects 
---

Projects
========

<ul>
  {% for post in site.projects %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
