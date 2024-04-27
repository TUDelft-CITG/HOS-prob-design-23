---
layout: home
title: CIE42X0 Prob Design
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: CIE42X0 Probabilistic Design course materials
---

# Welcome to {{ site.tagline }}
<!-- {: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 } -->

This website is for the 2022-23 academic year and is no longer maintained. Current HOS students should visit Brightspace or contact Robert Lanzafame directly.
{: .warning }

CIEM42X0 is a unit that is part of three B modules ([CIEM4210](https://studiegids.tudelft.nl/a101_displayCourse.do?course_id=63755), [CIEM4220](https://studiegids.tudelft.nl/a101_displayCourse.do?course_id=63756), [CIEM4230](https://studiegids.tudelft.nl/a101_displayCourse.do?course_id=63757)) offered in Q4 of the Hydraulic and Offshore Structures (HOS) track in the Civil Engineering MSc program at TU Delft.

*This page shows the most recent announcement and the calendar. For more information check the appropriate pages on the left. Links to Brightspace and the course textbooks are at the top.*

<!-- Read the ["Getting Started" announcement]({{site.url}}{{ site.baseurl }}/announcements) to know what to do during the first week of class. -->
<!--[Jump to the current week]({{ site.url }}{{ site.baseurl }}/calendar#week-1){: .btn .btn-blue }-->

{% if site.announcements %}
{{ site.announcements.last }}
[Previous Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## Calendar

*See Calendar page for explanation of lecture halls, course structure and notation.*

{% for module in site.modules %}
{{ module }}
{% endfor %}