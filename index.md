---
layout: default
title: Kezdőlap
description: Jurtatábor és sporteszköz-kölcsönző Orfűn, a Pécsi-tó partján.
---

<section class="hero">
  <div class="container">
    <div>
      <span class="eyebrow">Orfű · Pécsi-tó partján</span>
      <h1>Jurta, tópart, szabad ég</h1>
      <p class="lead">
        Kilenc kazah jurta, saját sporteszköz-kölcsönző és percekre a Pécsi-tó vize —
        az OrfűFitt Jurtatábor otthonos bázis osztálykirándulásoknak, családoknak és
        csapatépítő programoknak.
      </p>
      <div class="cta-row">
        <a class="btn btn--ember" href="{{ '/arak/' | relative_url }}">Árak megtekintése</a>
        <a class="btn btn--outline" href="{{ '/kapcsolat/' | relative_url }}">Ajánlatkérés</a>
      </div>
    </div>
    <div>
      <!-- Csere: saját fotó a jurtatáborról vagy a tópartról -->
      <svg class="hero-art" viewBox="0 0 480 360" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Jurták a tóparton, naplementében">
        <rect width="480" height="360" fill="#1B4552"/>
        <circle cx="380" cy="70" r="46" fill="#C96A2C" opacity="0.85"/>
        <path d="M0,230 C80,205 160,250 240,225 C320,200 400,240 480,220 L480,360 L0,360 Z" fill="#244F5C"/>
        <path d="M0,260 C90,240 170,280 260,255 C340,235 410,265 480,250 L480,360 L0,360 Z" fill="#16333C"/>
        <g transform="translate(90,205)">
          <polygon points="40,0 0,60 80,60" fill="#F3EEDC"/>
          <rect x="34" y="0" width="12" height="16" fill="#3C5A34"/>
        </g>
        <g transform="translate(220,195)">
          <polygon points="50,0 0,72 100,72" fill="#EDE3C8"/>
          <rect x="43" y="0" width="14" height="18" fill="#3C5A34"/>
        </g>
        <g transform="translate(340,215)">
          <polygon points="36,0 0,54 72,54" fill="#F3EEDC"/>
          <rect x="30" y="0" width="12" height="14" fill="#3C5A34"/>
        </g>
      </svg>
    </div>
  </div>
  {% include wave.html from="transparent" fill="#E4E9DE" %}
</section>

<section class="section--mist">
  <div class="container">
    <div class="section-head">
      <span class="eyebrow">Amit kínálunk</span>
      <h2>Minden, ami a tábori élményhez kell</h2>
    </div>
    <div class="grid-cards">
      <div class="card">
        <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M12 3 3 21h18L12 3Z"/><path d="M8 21v-6h8v6"/></svg>
        <h3>Jurtatábor</h3>
        <p>9 hangulatos, fa padlós kazah jurta, 54 férőhellyel, modern vizesblokkal és főzőfülkével.</p>
      </div>
      <div class="card">
        <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><circle cx="6" cy="17" r="3"/><circle cx="18" cy="17" r="3"/><path d="M9 17 12 7l5 2M9 17h9"/></svg>
        <h3>Fitt Klub</h3>
        <p>Kerékpár, kajak és kenu kölcsönzés — fedezd fel Orfűt és a Pécsi-tavat saját tempódban.</p>
      </div>
      <div class="card">
        <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M3 12h18M3 6h18M3 18h18"/></svg>
        <h3>Csoportoknak</h3>
        <p>Osztálykirándulás, táborozás és céges csapatépítés — szervezett programokkal.</p>
      </div>
      <div class="card">
        <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M12 2v20M5 9l7-7 7 7M5 15l7 7 7-7"/></svg>
        <h3>Tópart</h3>
        <p>Percekre a Pécsi-tótól — úszás, strandolás és a nyári sárkányhajó fesztivál helyszíne.</p>
      </div>
    </div>
  </div>
  {% include wave.html from="#E4E9DE" fill="#16333C" %}
</section>

<section class="section--lake">
  <div class="container" style="text-align:center;">
    <span class="eyebrow" style="color:#F3EEDC;">Foglalj most</span>
    <h2>Tervezd meg a táborozást velünk</h2>
    <p style="max-width:56ch;margin:0 auto 28px;color:rgba(243,238,220,0.85);">
      Küldj nekünk pár sort a csoport létszámáról és a tervezett időpontról,
      mi pedig személyre szabott ajánlattal jelentkezünk.
    </p>
    <a class="btn btn--ember" href="{{ '/kapcsolat/' | relative_url }}">Kapcsolatfelvétel</a>
  </div>
</section>
