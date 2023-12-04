---
layout: default
title: Blog
permalink: /blog/
---

### Below are my blog posts. Knock yourself out!
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>