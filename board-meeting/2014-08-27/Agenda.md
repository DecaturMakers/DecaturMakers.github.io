---
layout: post
title: Agenda
group:
  - board
  - meeting
  - agenda
---

{% assign titlecase = page.group | join ' ' %}{% include titlecase %}
{% assign url_date_node = page %}{% include url_date %}
{% assign path_popped = page.url %}{% include path_popped %}
{% assign agenda_date = url_date %}
# {{ titlecase }}
## {{ agenda_date | date: "%A %B %-d, %Y" }}

1.  Call to order
1.  Roll Call
1.  Agenda: revisions and approval
1.  Minutes
{% include agenda_minutes %}
1.  Reports
{% assign agenda_item = 'report' %}{% include agenda_item_list %}
1.  Consent Items
{% assign agenda_item = 'consent' %}{% include agenda_item_list %}
1.  Action Items
{% assign agenda_item = 'action' %}{% include agenda_item_list %}
1.  New Business
1.  Future Dates
1.  Adjourn
