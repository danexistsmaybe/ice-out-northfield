---
layout: default
title: Announcements
permalink: /announcements/
nav: true
---

{% for post in site.posts %}

## {{ post.title }}
*{{ post.date }}*
{{ post.excerpt }}
___

{% endfor %}