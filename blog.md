---
layout: default
title: Blog
permalink: /blog/
---

## My blog posts:

<ul>

{% for post in site.posts %}
{% unless post.draft %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>
{% endunless %}

  {% endfor %}
</ul>

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