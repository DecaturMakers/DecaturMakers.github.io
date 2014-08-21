---
layout: post
title: Agenda
group:
  - board
  - meeting
  - agenda
---

{% assign titlecase = page.group | join ' ' %}{% include titlecase %}
{% assign url = page.url %}{% include url_date %}
{% assign path_popped = page.url %}{% include path_popped %}
# {{ titlecase }}
## {{ url_date | date: "%A %B %-d, %Y" }}

1.  Call to order
1.  Roll Call
1.  Agenda: revisions and approval
1.  Minutes
    1. [07/23/2014]({{ site.baseurl }}/board-meeting/2014-07-23-Minutes.html)
1.  Reports
{% assign agenda_item = 'report' %}{% include agenda_item_list %}
1.  Consent Items
{% assign agenda_item = 'consent' %}{% include agenda_item_list %}
1.  Action Items
{% assign agenda_item = 'action' %}{% include agenda_item_list %}
1.  New Business
1.  Future Dates
1.  Adjourn
