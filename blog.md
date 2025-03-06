---
layout: default
title: Blog
permalink: /blog/
---
{% assign drafts = site.posts | where: "draft", true | where: "show_wip", true | sort: "date" | reverse %}
{% if  drafts.size > 0 %}

## Esboços (comentários bem-vindos):

<ul>

{% for post in drafts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>

  {% endfor %}
</ul>
{% endif %}

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
