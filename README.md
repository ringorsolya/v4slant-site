# V4 Media Slant – projektoldal

A Visegrad Fund 22310057 számú projektjének (Identifying News Slant in Crisis Communication Using Artificial Intelligence) honlapja. Statikus Jekyll-oldal, amit a GitHub Pages magától lefordít és kiszolgál, külön build-lépés vagy szerver nélkül.

## Felépítés

| Hely | Mi van benne |
|---|---|
| `index.html` | Főoldal: projektleírás, nyílt kimenetek, legutóbbi hírek, blog, partnerek |
| `about.md` | Projektleírás, módszertani lépések, a 20 témakategória, csapat |
| `_news/` | Hírek és események, egy fájl egy hír (`ÉÉÉÉ-HH-NN-rovid-nev.md`) |
| `_blog/` | Blogposztok, egy fájl egy poszt; a sorrendet az `order` mező adja |
| `_drafts/` | Félkész anyag, nem jelenik meg (itt van a 10., LGBTQI+-os poszt váza) |
| `publications.md` | Publikációk, előadások, disszemináció |
| `dashboard/` | A dashboard oldala; a `v4_dashboard.html` fájlt kell kicserélni a valódira |
| `assets/img/` | Képek: `events/` (fotók), `blog/` (ábrák), `logos/` |
| `_layouts/`, `assets/css/` | Sablonok és stílus, tartalomszerkesztéshez nem kell hozzányúlni |

## Új hír felvétele

Hozz létre a `_news/` mappában egy új fájlt, például `_news/2026-11-20-new-article.md`:

```markdown
---
title: "Shared Agenda, Distinct Realities"
date: 2026-11-20
type: Publication          # Publication / Workshop / Conference / Event / Media / Milestone
summary: Egy mondat, ez jelenik meg a listában.
link: https://doi.org/...   # nem kötelező: gomb a hír alján
link_label: Read the article
image: /assets/img/events/kep.jpg   # nem kötelező: nagy kép a hír tetején
place: Budapest                     # nem kötelező
---
A hír szövege Markdownban.
```

A főoldal és a hírlista automatikusan frissül, dátum szerint rendezve.

## Új blogposzt

Ugyanígy a `_blog/` mappába, `title`, `order` (sorszám) és `summary` mezővel. Ábra beillesztése:

```markdown
<figure>
  <img src="{{ '/assets/img/blog/abra.png' | relative_url }}" alt="Az ábra leírása">
  <figcaption>Ábrafelirat.</figcaption>
</figure>
```

A 4–6. posztban `<!-- FIGURE ... MISSING -->` megjegyzések jelölik a hiányzó ábrák helyét.

## Közzététel GitHub Pages-en

1. Hozz létre egy új, nyilvános repót (például `ringorsolya/v4slant-site`), és töltsd fel ennek a mappának a teljes tartalmát.
2. A repó **Settings → Pages** menüjében a *Source* legyen „Deploy from a branch”, a branch `main`, a mappa `/ (root)`.
3. Pár perc múlva az oldal elérhető a `https://ringorsolya.github.io/v4slant-site/` címen. **Ezen a próbacímen** állítsd be a `_config.yml`-ben a `baseurl: "/v4slant-site"` értéket, különben a stílus és a linkek nem töltődnek be.

## Saját tk.hu-s domain

1. Kérd meg a TK informatikusait, hogy vegyenek fel egy CNAME rekordot: `visegradmediaslant.tk.hu  CNAME  ringorsolya.github.io.`
2. Ha a DNS él, a repó **Settings → Pages → Custom domain** mezőjébe írd be: `visegradmediaslant.tk.hu`, majd kapcsold be az **Enforce HTTPS** opciót. A GitHub ekkor létrehoz egy `CNAME` fájlt a repóban.
3. A `_config.yml`-ben állítsd vissza: `baseurl: ""`.
4. Biztonsági lépés: a GitHub-fiókod **Settings → Pages → Verified domains** menüjében igazold a `tk.hu` domaint (ehhez egy TXT rekord kell, ezt is az IT veszi fel). Így más nem tudja a tk.hu-s aldomaint a saját GitHub-oldalára irányítani.

## Teendők

- [x] `dashboard/v4_dashboard.html` cseréje a valódi fájlra
- [ ] A 10. (LGBTQI+) poszt szövege → `_drafts/lgbtqi-framing.md`, utána át a `_blog/` mappába
- [ ] A 4–6. poszt ábrái
- [ ] A 2025. február 14-i workshop helyszíne és programja
- [ ] Az új, elfogadott cikk felvétele hírként, amikor megjelenik
