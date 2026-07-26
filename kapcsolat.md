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
            <div class="h-captcha" data-captcha="true"></div>
            <button class="form-submit" type="submit">Üzenet küldése</button>
          </form>
        </div>
        <script src="https://web3forms.com/client/script.js" async defer></script>
      </div>

      <div class="map-wrap">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2764.079908658503!2d18.134750741137754!3d46.1491548875973!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4742af5f9e13f373%3A0x9e88cca0ff226dd6!2sJurtat%C3%A1bor%20%C3%A9s%20Kemping!5e0!3m2!1shu!2shu!4v1785072972339!5m2!1shu!2shu"
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
          title="OrfűFitt Jurtatábor helyszíne térképen">
        </iframe>
      </div>
    </div>
  </div>
</section>
