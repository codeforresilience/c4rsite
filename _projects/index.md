---
layout: default
title: Projects 
---

Projects
========

2015
----

<ul>
  {% for post in site.projects %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

2014
----

<ul>
<li><a href='{{site.baseurl}}/pdfs/CFR_OVERVIEWpdf.pdf'>Overview</a>
<li><a href='{{site.baseurl}}/pdfs/CFR_BANGLADESH.pdf'>Bangladesh</a>
<li><a href='{{site.baseurl}}/pdfs/CFR_HAITI.pdf'>Haiti</a>
<li><a href='{{site.baseurl}}/pdfs/CFR_INDIA.pdf'>India</a>
<li><a href='{{site.baseurl}}/pdfs/CFR_INDONESIA.pdf'>Indonesia</a>
<li><a href='{{site.baseurl}}/pdfs/CFR_JAPAN.pdf'>Japan</a>
<li><a href='{{site.baseurl}}/pdfs/CFR_PAKISTAN.pdf'>Pakistan</a>
<li><a href='{{site.baseurl}}/pdfs/CFR_PHILIPPINES.pdf'>Philippines</a>
<li><a href='{{site.baseurl}}/pdfs/CFR_VIETNAM.pdf'>Vietnam</a>
</ul>

