---
layout: post
title: Board Meetings
---

# {{ page.title }}

<ul>
  {% assign meetings = (site.pages | where: 'title', 'Agenda' | sort: 'date' ) %}
  {% for page in meetings reversed %}
    {% if page.url contains 'board-meeting' %}
  <li><a href="{{ page.url }}">{{ page.date | date: "%Y-%m-%d" }}</a></li>
    {% endif %}
  {% endfor %}
</ul>


