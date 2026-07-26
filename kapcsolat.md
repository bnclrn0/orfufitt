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
    This is a working contact form. To receive email, 
    Replace YOUR_ACCESS_KEY_HERE with your actual Access Key.

    Create Access Key here 👉 https://web3forms.com/
       -->

<section class="contact-section">

  <form class="contact-form" action="https://api.web3forms.com/submit" method="POST">

    <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE" />
    <input type="hidden" name="subject" value="New Contact Form Submission from Web3Forms" />
    <input type="hidden" name="from_name" value="My Website" />
    <!-- More custom ization options available in the docs: https://docs.web3forms.com -->

    <div class="form-group-container">
      <div class="form-group">
        <label for="name" class="form-label">Név</label>
        <input id="name" name="name" class="form-input" placeholder="Your name" type="text" />
      </div>
      <div class="form-group">
        <label for="email" class="form-label">Email</label>
        <input id="email" name="email" class="form-input" placeholder="Your email" type="email" />
      </div>
      <div class="form-group">
        <label for="message" class="form-label">Üzenet</label>
        <textarea class="form-textarea" id="message" name="message" placeholder="Your message"></textarea>
      </div>
    </div>
    <button type="submit" class="btn btn--ember" style="border:none;cursor:pointer;justify-self:start;">Üzenet küldése</button>
  </form>

</section>

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
