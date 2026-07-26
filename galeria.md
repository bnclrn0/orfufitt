---
layout: default
title: Galéria
permalink: /galeria/
description: Fotók a jurtatáborról, a Pécsi-tóról és a táborozási programokról.
---

<section class="section--canvas" style="padding-top:56px;">
  <div class="container">
    <span class="eyebrow">Galéria</span>
    <h1>Tábor és tópart képekben</h1>
    <p style="max-width:60ch;margin-bottom:32px;">
      Ide kerülnek majd a saját fotók a jurtákról, a tóról és a programokról.
      A csempék egyelőre helyőrzők — mindegyik <code>&lt;img&gt;</code> elemre cserélhető
      a <code>assets/images/</code> mappába feltöltött fotókkal.
    </p>

    <!--
      Csere: minden .g-tile div-en belülre kerüljön egy
      <img src="{{ '/assets/images/SAJAT-FOTO.jpg' | relative_url }}" alt="...">
      a helyőrző háttérszín helyett.
    -->
    <div class="gallery-grid">
      <div class="g-tile wide tall" <img src="{{ '/assets/images/jurta.jpg' | relative_url }}" alt="Jurták">
        <span>Jurtatábor</span>
      </div>
      <div class="g-tile" style="background:linear-gradient(135deg,#3C5A34,#244F5C);">
        <span>Pécsi-tó</span>
      </div>
      <div class="g-tile" style="background:linear-gradient(135deg,#C96A2C,#3C5A34);">
        <span>Sárkányhajózás</span>
      </div>
      <div class="g-tile tall" style="background:linear-gradient(135deg,#16333C,#244F5C);">
        <span>Jurta belülről</span>
      </div>
      <div class="g-tile wide" style="background:linear-gradient(135deg,#3C5A34,#C96A2C);">
        <span>Kajak-kenu túra</span>
      </div>
      <div class="g-tile" style="background:linear-gradient(135deg,#244F5C,#3C5A34);">
        <span>Esti tábortűz</span>
      </div>
      <div class="g-tile" style="background:linear-gradient(135deg,#C96A2C,#16333C);">
        <span>Osztálykirándulás</span>
      </div>
    </div>
  </div>
</section>
