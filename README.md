---
layout: home
title: Just the Class
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Just the Class
---

# Calendar

This page gives an overview of the in-class sessions, homework assignments and reading material. Unless otherwise noted, our "typical" in-class sessions will always be on Friday at Bouwcampus Hall 1 (26.B0.030). The sessions are scheduled from 9:45-12:30, but we will try to wrap up by 12:00 most days.

See the [About](about.md) page for more information about the unit. Required reading is noted in the third column below, where "OT" and "ADK" refer to the online textbook and textbook by Armen der Kiureghian, respectively.

{% for module in site.modules %}
{{ module }}
{% endfor %}
