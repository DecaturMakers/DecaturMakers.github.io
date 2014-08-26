---
layout: post
date: 2014-08-27 08:30:00 -0500
title: Minutes
---

{% assign titlecase = page.group | join ' ' %}{% include titlecase %}
{% assign url_date_node = page %}{% include url_date %}
# {{ titlecase }}
## {{ url_date | date: "%A %B %-d, %Y" }}
