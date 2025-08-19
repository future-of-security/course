---
layout: home
title: Announcements
nav_order: 1
permalink: /:path/
seo:
  type: Course
  name: Future of Security
---


# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}