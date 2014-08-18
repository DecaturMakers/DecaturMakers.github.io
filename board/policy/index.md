---
layout: post
title: Board Policy
---

# {{ page.title }}

<ul>
  {% assign policy_pages = (site.pages | sort: 'title') %}
  {% for page in policy_pages %}
    {% if page.url contains 'board-policy' %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

