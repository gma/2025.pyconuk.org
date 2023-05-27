---
layout: default
title: Schedule
---

{% if site.schedule_ready == true %}
<script type="text/javascript" src="https://pretalx.com/pycon-uk-{{ site.con_year }}/schedule/widget/v2.en.js"></script>
<pretalx-schedule event-url="https://pretalx.com/pycon-uk-{{ site.con_year }}/" locale="en" style="--pretalx-clr-primary: #3aa57c"></pretalx-schedule>

<p>If you can't see the schedule widget, you can <a href="https://pretalx.com/pycon-uk-{{ site.con_year }}/schedule/">view the schedule here.</a></p>
{% else %}
<p>The full schedule will be posted here when it is prepared.</p>
<p>To aid in planning transport and accommodation, the expected start and end times are given below.</p>
<p>Each day of the conference will begin at <strong>09:00</strong>, except the first ({{ site.con_start }}), which will begin at <strong>11:00</strong></p>
<p>Each day of the conference will end at <strong>18:00</strong></p>
{% endif %}
