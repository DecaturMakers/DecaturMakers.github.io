---
layout: post
title: B.EL - Executive Limitations
group:
  - board
  - policy
---

# Board Policy

## {{ page.title }}

{% assign group = 'board|policy' | split: '|' %}
group: {{ group }}  
page.group: {{ group }}  
{% if group == page.group %}ok{% else %}nok{% endif %}

