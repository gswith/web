---
layout: default
title: "Getting Started !"
---
<h1 style="text-align:center"><span style="color:#DDD">http://</span>gswith.in</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
