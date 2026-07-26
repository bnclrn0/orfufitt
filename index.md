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
      <svg class="hero-art" viewBox="0 0 480 360" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Jurták a tóparton, domboktól övezve, vízparti tükröződéssel">
        <defs>
          <linearGradient id="heroSky" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#16333C"/>
            <stop offset="100%" stop-color="#2E6274"/>
          </linearGradient>
          <linearGradient id="heroWater" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#2E6274"/>
            <stop offset="100%" stop-color="#132B33"/>
          </linearGradient>
        </defs>

        <rect width="480" height="360" fill="url(#heroSky)"/>

        <!-- távoli dombok -->
        <path d="M0,150 C50,95 120,115 190,85 C260,55 330,105 400,75 C430,60 460,85 480,75 L480,220 L0,220 Z" fill="#5C7A55" opacity="0.55"/>
        <!-- közelebbi domb/hegyvonulat -->
        <path d="M0,190 C60,125 140,155 220,105 C300,65 370,145 480,115 L480,222 L0,222 Z" fill="#3C5A34" opacity="0.85"/>

        <circle cx="380" cy="66" r="44" fill="#C96A2C" opacity="1"/>

        <!-- tópart sávja -->
        <rect x="0" y="200" width="480" height="22" fill="#D8C9A3"/>

        <!-- tó -->
        <rect x="0" y="220" width="480" height="140" fill="url(#heroWater)"/>

        <!-- dombok tükröződése a vízben -->
        <g opacity="0.16" transform="translate(0,440) scale(1,-1)">
          <path d="M0,190 C60,125 140,155 220,105 C300,65 370,145 480,115 L480,222 L0,222 Z" fill="#3C5A34"/>
        </g>
        <!-- napkorong csillogása a vízen -->
        <ellipse cx="378" cy="248" rx="30" ry="6" fill="#C96A2C" opacity="0.35"/>
        <ellipse cx="378" cy="264" rx="46" ry="5" fill="#C96A2C" opacity="0.22"/>

        <!-- vízfodrok -->
        <path d="M20,290 q30,-8 60,0 t60,0 t60,0" stroke="#F3EEDC" stroke-width="2" fill="none" opacity="0.2"/>
        <path d="M260,314 q30,-8 60,0 t60,0 t60,0" stroke="#F3EEDC" stroke-width="2" fill="none" opacity="0.18"/>
        <path d="M40,336 q30,-8 60,0 t60,0 t60,0 t60,0" stroke="#F3EEDC" stroke-width="2" fill="none" opacity="0.15"/>

        <g transform="translate(20,184)">
          <path d="M0,34 C3,10 16,0 28,0 C40,0 53,10 56,34 Z" fill="#F3EEDC"/>
          <rect x="23" y="0" width="10" height="12" fill="#C96A2C"/>
          <path d="M0,34 C3,10 16,0 28,0 C40,0 53,10 56,34 Z" fill="none" stroke="#16333C" stroke-width="1.5" opacity="0.15"/>
        </g>
        <g transform="translate(95,176)">
          <path d="M0,42 C3.5,12.6 19.6,0 35,0 C50.4,0 66.5,12.6 70,42 Z" fill="#EDE3C8"/>
          <rect x="28" y="0" width="13" height="15" fill="#C96A2C"/>
          <path d="M0,42 C3.5,12.6 19.6,0 35,0 C50.4,0 66.5,12.6 70,42 Z" fill="none" stroke="#16333C" stroke-width="1.5" opacity="0.15"/>
        </g>
        <g transform="translate(185,162)">
          <path d="M0,56 C4.8,16.8 26.9,0 48,0 C69.1,0 91.2,16.8 96,56 Z" fill="#F3EEDC"/>
          <rect x="40" y="0" width="17" height="20" fill="#C96A2C"/>
          <path d="M0,56 C4.8,16.8 26.9,0 48,0 C69.1,0 91.2,16.8 96,56 Z" fill="none" stroke="#16333C" stroke-width="1.5" opacity="0.15"/>
        </g>
        <g transform="translate(300,176)">
          <path d="M0,42 C3.5,12.6 19.6,0 35,0 C50.4,0 66.5,12.6 70,42 Z" fill="#EDE3C8"/>
          <rect x="28" y="0" width="13" height="15" fill="#C96A2C"/>
          <path d="M0,42 C3.5,12.6 19.6,0 35,0 C50.4,0 66.5,12.6 70,42 Z" fill="none" stroke="#16333C" stroke-width="1.5" opacity="0.15"/>
        </g>
        <g transform="translate(390,184)">
          <path d="M0,34 C3,10 16,0 28,0 C40,0 53,10 56,34 Z" fill="#F3EEDC"/>
          <rect x="23" y="0" width="10" height="12" fill="#C96A2C"/>
          <path d="M0,34 C3,10 16,0 28,0 C40,0 53,10 56,34 Z" fill="none" stroke="#16333C" stroke-width="1.5" opacity="0.15"/>
        </g>
      </svg>
    </div>
  </div>
  <div class="wave" style="background:transparent;" aria-hidden="true">
    <svg viewBox="0 0 1200 48" preserveAspectRatio="none"><path d="M0,24 C150,48 300,0 450,20 C600,40 750,4 900,22 C1050,40 1150,16 1200,24 L1200,48 L0,48 Z" fill="#E4E9DE"></path></svg>
  </div>
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
  <div class="wave" style="background:#E4E9DE;" aria-hidden="true">
    <svg viewBox="0 0 1200 48" preserveAspectRatio="none"><path d="M0,24 C150,48 300,0 450,20 C600,40 750,4 900,22 C1050,40 1150,16 1200,24 L1200,48 L0,48 Z" fill="#16333C"></path></svg>
  </div>
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
