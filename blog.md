---
layout: default
title: Blog
permalink: /blog/
---

## Esboços (comentários bem-vindos):

<ul>

{% for post in site.posts %}
{% if post.draft and post.show_wip %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>
{% endif %}

  {% endfor %}
</ul>

## Texto publicados no Açoriano Oriental:

<ul>

{% for post in site.posts %}
{% if post.ao %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>
{% endif %}

  {% endfor %}
</ul>

## Outros textos:

<ul>

{% for post in site.posts %}
{% unless post.ao or post.draft %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>
{% endunless %}

  {% endfor %}
</ul>
