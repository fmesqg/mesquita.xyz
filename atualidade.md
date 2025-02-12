---
layout: default
title: Atualidade

permalink: /atualidade/
---

## Interesting external news/content:

<ul>
  {% assign sorted_shorts = site.shorts | sort: 'date' | reverse %}
  {% for post in sorted_shorts %}
  {% if post.sitemap != false and post.date and post.title %}

    <li>
      <a href="{{ post.link }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>

  {% endif %}
  {% endfor %}
</ul>