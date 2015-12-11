---
layout: page
title: Archive
---

## Blog Posts

{% for post in site.posts %}
  * {{ post.date | date: '0x%Y%m%d' }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
