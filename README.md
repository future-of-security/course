---
layout: home
title: Home
nav_order: 1
permalink: /:path/
seo:
  type: Course
  name: Future of Security
---

<!-- # Just the Class -->

**Future of Security: Integrative Solutions to Complex Security Systems** is the capstone course for the Integrated Security Pathways minor. It is a cross-disciplinary capstone course spanning multiple colleges and departments incorporating learning objectives from Pathways Learning Core Outcomes/Integrative Outcomes, Quantitative and Computational Thinking, Reasoning within the Social Sciences, and Intercultural and Global Awareness.


## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}