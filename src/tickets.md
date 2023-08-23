---
layout: default
title: Tickets
---
{% if site.tickets_open != true %}<div class="box box_red"><p><strong>Well done, you found the tickets page, but they're not on sale yet- you'll have to wait a little longer!</strong></p></div>{% endif %}

<div class="box box_red">
  <p><strong>NOTE:</strong>If you are travelling from overseas, <strong>including the EU</strong>, please remember to check all required documentation for entry into the UK.</p>
</div>

<p>If you need to know the start and finish times on each day before you get your ticket, for travel or other reasons, see the <a href="/schedule/">schedule</a>.</p>

<link rel="stylesheet" type="text/css" href="https://pretix.eu/ukpatl/pyconuk-{{ site.con_year }}/widget/v1.css">
<script type="text/javascript" src="https://pretix.eu/widget/v1.en.js" async></script>
<pretix-widget event="https://pretix.eu/ukpatl/pyconuk-{{ site.con_year }}/"></pretix-widget>

<p>If you can't see the tickets widget, you can <a href="https://pretix.eu/ukpatl/PyConUK-{{ site.con_year }}/">buy your PyCon UK {{ site.con_year }} tickets here.</a></p>

<div class="box box_blue">
  <h3>How to select your ticket rate</h3>
  <p>If your tickets are being paid for by your employer, please select the <strong>Standard</strong> rate.</p>
  <p>If you are paying for your ticket out of your own pocket, please select the <strong>Individual</strong> rate.</p>
  <p>If you are unwaged (for example in full-time education), please select the <strong>Unwaged</strong> rate.</p>
  <p>If you have a young coder (aimed at ages 8 - 16) who wants to come to the <strong>Young Coders</strong> day, please select that rate. You can accompany them at no extra charge.</p>
  <p>If you are happy to pay extra to help support the conference, you may select one of the <strong>Supporter</strong> rates.</p>
  <p>The sprint day is accessible to all ticket holders at no extra charge.</p>
  <a href="/tickets/about-our-ticket-prices/">About our ticket prices</a>
</div>

<div class="box box_red">
  <p>Please note that anyone under 18 must be accompanied by an identifiable adult.</p>
  <p>This adult has responsibility for the minor at all times and must be in attendence whenever the minor is, and contactable by the event organisers.</p>
</div>

<div class="box box_yellow">
  <h3>Ticket prices</h3>
  <p>The sprint day is accessible to all ticket holders at no extra charge.</p>
  <table class="table">
    <thead>
      <th scope="col">Number of days</th>
      <th scope="col">1</th>
      <th scope="col">2</th>
      <th scope="col">3</th>
    </thead>
    <tbody>
      <tr>
        <th scope="row">Standard</th>
        <td>£132</td>
        <td>£246</td>
        <td>£360</td>
      </tr>
      <tr>
        <th scope="row">Individual</th>
        <td>£70</td>
        <td>£120</td>
        <td>£204</td>
      </tr>
      <tr>
        <th scope="row">Unwaged</th>
        <td>£39.60</td>
        <td>£75</td>
        <td>£100</td>
      </tr>
      <tr>
        <th scope="row">Young coders (aimed at ages 8 - 16, with accompanying adult)</th>
        <td>£6</td>
        <td>-</td>
        <td>-</td>
      </tr>
      <tr>
        <th scope="row">Supporter Standard</th>
        <td>-</td>
        <td>-</td>
        <td>£600</td>
      </tr>
      <tr>
        <th scope="row">Supporter Individual</th>
        <td>-</td>
        <td>-</td>
        <td>£260</td>
      </tr>
    </tbody>
  </table>

  <p>All prices in this table <strong>include</strong> VAT at 20%<br />
  VAT number: {{ site.con_vat_number }}</p>
</div>
