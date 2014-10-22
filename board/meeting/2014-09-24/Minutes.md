---
layout: post
date: 2014-09-24 08:30:00 -0500
title: Minutes
group:
  - board
  - meeting
  - minutes
---

{% assign titlecase = page.group | join ' ' %}{% include titlecase %}
{% assign url_date_node = page %}{% include url_date %}
# {{ titlecase }}
## {{ url_date | date: "%A %B %-d, %Y" }}

Present: Lew, Garrett

### Adjourned

Noting a lack of a majority of board members.
