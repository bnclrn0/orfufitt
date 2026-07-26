# OrfűFitt — új honlap (Jekyll)

Statikus, 5 oldalas váz: Kezdőlap, Árak, Programok, Galéria, Kapcsolat.

## Mit kell még pótolni

- **Szövegek**: az `arak.md`, `programok.md` oldalakon lévő szövegek és árak
  helyőrzők — cseréld le a régi `orfufitt.hu` tartalmára.
- **Fotók**: töltsd fel a `assets/images/` mappába, majd a `galeria.md` és
  `index.md` fájlokban lévő helyőrző csempéket cseréld valódi `<img>`
  elemekre (a fájlban jelölve, hol).
- **Kapcsolatform**: regisztrálj egy ingyenes űrlapot a
  [formspree.io](https://formspree.io) oldalon, és írd be a saját
  form-azonosítót a `kapcsolat.md` fájl `<form action="...">` sorába —
  statikus oldalon nincs szerver oldali levélküldés, ez oldja meg helyette.

## Helyi futtatás

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Ezután a `http://localhost:4000` címen nézhető meg élőben, szerkesztés
közben automatikusan frissül.

## Publikálás GitHub Pages-re

1. Hozz létre egy GitHub repót, és told fel ezt a mappát.
2. A repóban: **Settings → Pages → Build and deployment → Source: Deploy
   from a branch**, branch: `main`, mappa: `/ (root)`.
3. Pár perc múlva él az oldal a `https://FELHASZNALONEV.github.io/REPONEV/`
   címen.
4. **Saját domain (orfufitt.hu) bekötése:**
   - Hozz létre egy `CNAME` nevű fájlt a repó gyökerében, benne egyetlen
     sorban: `www.orfufitt.hu`
   - A domain-szolgáltatónál állíts be egy `CNAME` rekordot:
     `www` → `FELHASZNALONEV.github.io`
   - A gyökér domainhez (`orfufitt.hu`, `www` nélkül) 4 db `A` rekord kell
     a GitHub Pages IP-jeire (ezek a GitHub Pages dokumentációjában
     találhatók, jelenleg: 185.199.108.153, 185.199.109.153,
     185.199.110.153, 185.199.111.153).
   - A GitHub `Settings → Pages` alatt írd be a custom domaint, és
     kapcsold be a "Enforce HTTPS" opciót, amint a DNS él.

## Struktúra

```
_config.yml        site adatok, navigáció
_layouts/           oldalváz (default.html)
_includes/           header, footer, hullám-motívum
assets/css/          style.css — design tokenek, tipográfia
assets/images/       saját fotók helye
index.md             Kezdőlap
arak.md               Árak
programok.md          Programok
galeria.md            Galéria
kapcsolat.md          Kapcsolat
```
