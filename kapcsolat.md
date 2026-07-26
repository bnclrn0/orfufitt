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
          Kapcsolati form.
        -->
        <div class="contact-form-wrap">
          <form class="contact-form" action="https://api.web3forms.com/submit" method="POST">
            <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE" />
            <input type="hidden" name="subject" value="Új üzenet az orfufitt.hu kapcsolati űrlapról" />
            <input type="hidden" name="from_name" value="OrfűFitt weboldal" />

            <div class="form-group-container">
              <div class="form-group">
                <label for="name" class="form-label">Név</label>
                <input id="name" name="name" class="form-input" placeholder="Neved" type="text" required />
              </div>
              <div class="form-group">
                <label for="email" class="form-label">E-mail</label>
                <input id="email" name="email" class="form-input" placeholder="E-mail címed" type="email" required />
              </div>
              <div class="form-group">
                <label for="message" class="form-label">Üzenet</label>
                <textarea class="form-textarea" id="message" name="message" placeholder="Írd meg, miben segíthetünk" required></textarea>
              </div>
            </div>
            <button class="form-submit" type="submit">Üzenet küldése</button>
          </form>
        </div>
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
