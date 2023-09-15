---
layout: schedule
title: Schedule
---

<p>The conference will run from Friday 22nd till Monday 25th September 2023.</p>


{% if site.schedule_ready == true %}
<p>All ticket holders are entitled to join the sprints day at no additional charge.</p>
<p>If you can't see the schedule widget, you can <a href="https://pretalx.com/pyconuk-{{ site.con_year }}/schedule/">view the schedule here.</a> On some screens you may need to scroll left or right to see all the tracks.</p>

<script type="text/javascript" src="https://pretalx.com/pyconuk-{{ site.con_year }}/schedule/widget/v2.en.js"></script>
{% else %}
<p>The conference will be made up of 3 days of talks and workshops from Friday - Sunday and a single day of sprints on Monday. All ticket holders are entitled to join the sprints day at no additional charge.</p>

<p>We will be holding a Young Coder’s day on Saturday 23rd September suitable for young people aged from about 8 years old to 16 years old. Young Coder’s tickets are available at £6 for a young coder and an accompanying adult. The adult will accompany and be responsible for their young coder for the duration of the day.</p>

<p>We will also be holding a Django Girls workshop on Saturday 23rd September. This workshop will have its own application process which we will update here shortly. It will not be a general access workshop within the the broader conference programme.</p>

<p>The full schedule will be posted here when it is prepared.</p>
<p>To aid in planning transport and accommodation, the expected start and end times are given below.</p>
<p>Each day of the conference will begin at <strong>09:00</strong>, except the first ({{ site.con_start }}), which will begin at <strong>11:00</strong></p>
<p>Each day of the conference will end at <strong>18:00</strong></p>
{% endif %}
