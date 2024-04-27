---
layout: page
title: Instructors
nav_order: 4
description: A listing of all the course staff members.
---

# Instructors

This website is for the 2022-23 academic year and is no longer maintained. Current HOS students should visit Brightspace or contact Robert Lanzafame directly.
{: .warning }

A number of instructors are involved in this unit. Your primary point of contact is Robert Lanzafame.
## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Teaching Assistants

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
