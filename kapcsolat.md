---
layout: default
title: Kapcsolat
permalink: /kapcsolat/
description: Elérhetőségek és ajánlatkérés az OrfűFitt Jurtatáborhoz.
---

<section class="section--canvas" style="padding-top:56px;">
  <div class="container">
    <span class="eyebrow">Kapcsolat</span>
    <h1>Kérj ajánlatot</h1>

    <div class="contact-grid" style="margin-top:32px;">
      <div>
        <dl class="contact-info">
          <dt>Cím</dt>
          <dd>{{ site.address }}</dd>
          <dt>Telefon</dt>
          <dd><a href="tel:{{ site.phone | replace: ' ', '' }}">{{ site.phone }}</a></dd>
          <dt>E-mail</dt>
          <dd><a href="mailto:{{ site.email }}">{{ site.email }}</a></dd>
        </dl>

        <!--
          Csere: a form action egy saját Formspree (formspree.io) végpontra,
          mert statikus oldalon nincs szerver oldali levélküldés.
          Regisztráció után az action="https://formspree.io/f/XXXXXXX" -re módosítandó.
        -->
        <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" style="margin-top:32px;display:grid;gap:14px;max-width:420px;">
          <label>
            Név
            <input type="text" name="name" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #cfc9b4;margin-top:4px;">
          </label>
          <label>
            E-mail
            <input type="email" name="email" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #cfc9b4;margin-top:4px;">
          </label>
          <label>
            Üzenet
            <textarea name="message" rows="4" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #cfc9b4;margin-top:4px;"></textarea>
          </label>
          <button type="submit" class="btn btn--ember" style="border:none;cursor:pointer;justify-self:start;">Üzenet küldése</button>
        </form>
      </div>

      <div class="map-wrap">
        <iframe
          src="https://www.google.com/maps?q=Orf%C5%B1%2C+Doll%C3%A1r+utca+36&output=embed"
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
          title="OrfűFitt Jurtatábor helyszíne térképen">
        </iframe>
      </div>
    </div>
  </div>
</section>
