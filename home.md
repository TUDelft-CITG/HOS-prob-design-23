---
layout: home
title: CIE42X0 Prob Design
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: CIE42X0 Probabilistic Design course materials
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

## Welcome to CIEM42X0: Probabilistic Design 

This page shows the most recent Accouncement and the Calendar. For more information check the appropriate pages on the left. Links to Brightspace and the course textbooks are at the top.

<!--Read the ["Getting Started" announcement]({{site.url}}{{ site.baseurl }}/announcements) to know what to do before the first day of class.-->
<!--[Jump to the current week]({{ site.url }}{{ site.baseurl }}/calendar#week-1){: .btn .btn-blue }-->

{% if site.announcements %}
{{ site.announcements.last }}
[Previous Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

## Calendar

{% for module in site.modules %}
{{ module }}
{% endfor %}