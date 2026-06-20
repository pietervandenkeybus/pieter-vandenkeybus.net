# pieter-vandenkeybus.net

Persoonlijke site van Pieter Van den Keybus — **UX-strategie — niche-dienst (teal ontwerp)**.
Statische single-page site (HTML/CSS, geen build). Klaar om in een GitHub-repo te zetten.

## Inhoud van deze map
- `index.html` — de volledige pagina (CSS en JS inline)
- `robots.txt` — verwijst naar de sitemap
- `sitemap.xml` — homepage-URL, hreflang nl-BE
- `CNAME` — bevat `pieter-vandenkeybus.net` (zet automatisch het custom domain in GitHub Pages)
- `.nojekyll` — zegt GitHub Pages dat de bestanden ongewijzigd geserveerd mogen worden

## Deployen op GitHub Pages
1. Maak een nieuwe repo (bv. `net-site`) en upload **de inhoud van deze map** (niet de map zelf) naar de root.
2. Repo → **Settings → Pages** → Source: *Deploy from a branch* → branch `main`, map `/ (root)`.
3. Het `CNAME`-bestand zet het domein `pieter-vandenkeybus.net` automatisch klaar.
4. Zet bij je domeinregistrar de DNS:
   - `A`-records naar GitHub Pages: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - of een `CNAME` voor `www` naar `<jouw-gebruikersnaam>.github.io`
5. Vink in Settings → Pages **"Enforce HTTPS"** aan (kan even duren tot het certificaat klaar is).

## Alternatief: Vercel
Import de repo → framework "Other" → Add Domain `pieter-vandenkeybus.net`. Verder geen config nodig.

## Na deploy (SEO)
1. Maak een property aan in **Google Search Console** voor `pieter-vandenkeybus.net`.
2. Dien `sitemap.xml` in.
3. Werk `lastmod` in `sitemap.xml` bij na elke inhoudelijke wijziging.

## Wat in deze versie is rechtgezet
- **Zichtbaarheidsfix:** de inhoud is nu standaard zichtbaar. De fade-in-animatie draait
  alleen nog als JavaScript actief is (`body.js`). Daardoor zien crawlers, PDF-export en
  bezoekers zonder JS altijd alle secties — eerder konden tussenliggende secties onzichtbaar blijven.
- **Wederzijdse `sameAs`:** het Person-schema linkt nu alle vier de domeinen + LinkedIn + Uflow,
  zodat Google ze als één persoon herkent.

## Volledige sameAs-lijst (staat al in index.html)
- https://pieter-van-den-keybus.be
- https://pieter-vandenkeybus.be
- https://pieter-vandenkeybus.eu
- https://pieter-vandenkeybus.net
- https://www.linkedin.com/in/pietervandenkeybus
- https://uflow.be
