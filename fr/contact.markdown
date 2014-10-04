---
layout: default
lang: fr
title: Contact
description: Contactez nous et trouvez nos heures d'ouverture
slug: contact
---

<div class="row">
  <div class="col-md-5">
    <h4>Cabinet Dentaire Barthelemy</h4>
    {% include full-address.html %}

    <h4>Heures d'ouverture</h4>
    <table class="table">
      <tr>
        <th>Lundi</th>
        <td itemprop="openingHours" content="Mo 08:00-17:00">8h - 17h</td>
      </tr>
      <tr>
        <th>Mardi</th>
        <td itemprop="openingHours" content="Tu 08:00-19:00">8h - 19h</td>
      </tr>
      <tr>
        <th>Mercredi</th>
        <td>8h - 18h</td>
      </tr>
      <tr>
        <th>Jeudi</th>
        <td>8h - 17h</td>
      </tr>
      <tr>
        <th>Vendredi</th>
        <td>8h - 17h</td>
      </tr>
      <tr>
        <th>Samedi</th>
        <td itemprop="openingHours" content="Sa 08:00-13:00">8h - 13h</td>
      </tr>
    </table>
  </div>
  <div class="col-md-7">
    <h4>Nous trouver</h4>
    <ul>
      <li>Parking Perdtemps à 150 m</li>
      <li>1 minute à pied de la gare</li>
    </ul>

    <p>
      <a href="{{ site.gmap_url }}" itemprop="map" class="hidden-xs">
        <img src="/photos/map.jpg" alt="Nous trouver" />
      </a>
    </p>

    <p class="hidden-xs"><a href="{{ site.gmap_url }}">Ouvrir dans Google map</a></p>
    <p class="visible-xs">
      <a href="{{ site.gmap_url }}" class="btn btn-default btn-block">Ouvrir dans Google map</a>
    </p>
  </div>
</div>
