---
layout: default
title: Tickets
---

<link rel="stylesheet" type="text/css" href="https://pretix.eu/pyconuk/PyConUK{{ site.con_year }}/widget/v1.css">
<script type="text/javascript" src="https://pretix.eu/widget/v1.en.js" async></script>
<pretix-widget event="https://pretix.eu/pyconuk/PyConUK{{ site.con_year }}/"></pretix-widget>

<p>If you can't see the tickets widget, you can <a href="https://pretix.eu/pyconuk/PyConUK{{ site.con_year }}/">buy your PyConUK {{ site.con_year }} tickets here.</a></p>

<div class="box box_blue">
  <h3>How to select your ticket rate</h3>
  <p>If your tickets are being paid for by your employer, please select the <strong>Standard</strong> rate.</p>
  <p>If you are paying for your ticket out of your own pocket, please select the <strong>Individual</strong> rate.</p>
  <p>If you are unwaged (for example in full-time education), please select the <strong>Unwaged</strong> rate.</p>
  <a href="/tickets/about-our-ticket-prices/">About our ticket prices</a>
</div>

<div class="box box_yellow">
  <h3>Ticket prices</h3>
  <table class="table">
    <thead>
      <th scope="col">Ticket type</th>
      <th scope="col">Ticket price</th>
    </thead>
    <tbody>
      <tr>
        <th scope="row">Standard</th>
        <td>{{ site.con_standard_ticket_price }}</td>
      </tr>
      <tr>
        <th scope="row">Individual</th>
        <td>{{ site.con_individual_ticket_price }}</td>
      </tr>
      <tr>
        <th scope="row">Unwaged</th>
        <td>{{ site.con_unwaged_ticket_price }}</td>
      </tr>
    </tbody>
  </table>

  <p>All prices in this table <strong>include</strong> VAT at 20%<br />
  VAT number: GB249244982</p>
</div>
