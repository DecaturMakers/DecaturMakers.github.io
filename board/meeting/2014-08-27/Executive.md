---
layout: post
title: Executive
group:
  - board
  - meeting
  - report
priority: 1
---

{% assign titlecase = page.group | join ' ' %}{% include titlecase %}
{% assign url_date_node = page %}{% include url_date %}
# {{ page.title | capitalize }} {{ titlecase }}
## {{ url_date | date: "%A %B %-d, %Y" }}

* Membership Report
    * FB: 441, G: 129, MU: 179, MC: 535 
* Membership vote still not sent.
* FCCD
    * Working agreeement
    * calendar integration
* Bylaws
* Require commitee work?
* FIRST Robotics use of space this fall