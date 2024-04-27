---
layout: page
title: Announcements
nav_order: 3
nav_exclude: false
description: A feed containing all of the class announcements.
---

# Announcements

This website is for the 2022-23 academic year and is no longer maintained. Current HOS students should visit Brightspace or contact Robert Lanzafame directly.
{: .warning }

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
