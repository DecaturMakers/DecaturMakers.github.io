---
layout: post
title: Board
---

# {{ page.title }}

## [Meetings]({{ site.baseurl }}/board/meeting/index.html)  
<ul>
  {% assign meetings = (site.pages | where: 'title', 'Agenda' | sort: 'date' ) %}
  {% for page in meetings reversed %}
    {% if page.url contains 'board-meeting' %}
  <li><a href="{{ page.url }}">{{ page.date | date: "%Y-%m-%d" }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

## [Policy]({{ site.baseurl }}/board/policy/index.html)  
<ul>
  {% assign policy_pages = (site.pages | sort: 'title') %}
  {% for page in policy_pages %}
    {% if page.url contains 'board-policy' %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

