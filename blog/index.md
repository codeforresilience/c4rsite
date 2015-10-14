---
layout: default
title: Contact
banner_img: header-home.png
---

Code for Resilience Blog
========================

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a><br>
      {{ post.date }}
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
