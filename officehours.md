---
layout: default
keywords:
comments: false

title: Office Hours
description: Times and locations may occasionally change each week; please check this page often.
buttons: [project_appt_calendly, google_cal]
micro_nav: false
---

## Office Hours Table <a name="table"></a>

| Course Staff |     Office Hour Signup     | Zoom URL |
|--------------|:--------------------------:|----------|
{% assign people = site.course.staff | concat: site.course.ca -%}
{% for ca in people -%}
{% unless ca.zoom_id == null or ca.calendly == null -%}

| {{ ca.name }} {% if ca.type == 'Mentor' %} (Project only) {% endif %} | [Click to book]({{ ca.calendly }}) | [{{ ca.zoom_id }}]({{ ca.zoom_link }}) |
{% endunless -%}
{% endfor %}

## Google Calendar <a name="calendar"></a>

**All Office Hours are held remotely over Zoom. Use the Zoom link above for the respective TA.**

<div>
<iframe src="https://calendar.google.com/calendar/u/0/embed?src=2085mq43dah8dv92ndoq6un2nc@group.calendar.google.com&ctz=America%2FLos_Angeles" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
</div>
