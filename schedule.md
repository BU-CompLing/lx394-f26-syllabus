---
title: Schedule
layout: page
nav_order: 4
permalink: /schedule
---

# Schedule

The course schedule may be subject to change. 

## Dates and Deadlines

Three types of dates are listed on the schedule.

<span>BU Deadlines</span>{:.label.label-red} Important dates from the [BU academic calendar](https://www.bu.edu/reg/calendars/)<br />
<span>Assignment Released</span>{:.label.label-green} On Blackboard<br />
<span>Assignment Due</span>{:.label.label-blue} On Mondays at 9:00 AM unless stated otherwise

## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}
