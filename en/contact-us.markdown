---
layout: default
lang: en
title: Contact us
description: Contact us and find our opening hours
slug: contact
published: true
---


<div class="row">
  <div class="col-md-5">
    <h4 itemprop="name">Cabinet Dentaire Barthelemy</h4>
    {% include full-address.html %}

    <h4>Opening hours</h4>
    <table class="table">
      <tr>
        <th>Monday</th>
        <td itemprop="openingHours" content="Mo 10:00-20:00">8am - 5pm</td>
      </tr>
      <tr>
        <th>Tuesday</th>
        <td itemprop="openingHours" content="Tu 08:00-19:00">8am - 7pm</td>
      </tr>
      <tr>
        <th>Wednesday</th>
        <td>8am - 6pm</td>
      </tr>
      <tr>
        <th>Thursday</th>
        <td>8am - 5pm</td>
      </tr>
      <tr>
        <th>Friday</th>
        <td>8am - 5pm</td>
      </tr>
      <tr>
        <th>Saturday</th>
        <td itemprop="openingHours" content="Sa 08:00-13:00">8am - 1pm</td>
      </tr>
    </table>
  </div>
  <div class="col-md-7">
    <h4>Find us</h4>
    <ul>
      <li>Perdtemps parking at 150 meters</li>
      <li>1 minute walk from the station</li>
    </ul>

    <p class="hidden-xs">
      <a href="{{ site.gmap_url }}" itemprop="map">
        <img src="/photos/map.jpg" alt="Find us" />
      </a>
    </p>

    <p class="hidden-xs"><a href="{{ site.gmap_url }}">Open in Google map</a></p>
    <p class="visible-xs">
      <a href="{{ site.gmap_url }}" class="btn btn-default btn-block">Open in Google map</a>
    </p>
  </div>
</div>
