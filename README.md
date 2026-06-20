# pieter-vandenkeybus.net

Niche-dienstsite van Pieter Van den Keybus, volledig rond **UX-strategie**.
Bewust een ander onderwerp en andere zoekintentie dan de andere domeinen, zodat de site
naast (niet tegen) de andere kan ranken — voor zoekopdrachten als "UX-strategie" of "UX-strateeg".
Statische single-page site (HTML/CSS), te deployen via GitHub Pages of Vercel.

## Bestanden
- `index.html` — de volledige pagina (inline CSS, geen build nodig)
- `robots.txt` — verwijst naar de sitemap
- `sitemap.xml` — één URL (homepage), hreflang nl-BE

## Deploy
**GitHub Pages:** repo → Settings → Pages → branch `main`, map `/root`. Custom domain `pieter-vandenkeybus.net` instellen, "Enforce HTTPS" aanzetten.
**Vercel:** import repo → framework "Other" → custom domain toevoegen.

## SEO-checklist na deploy
1. Domein koppelen en HTTPS forceren.
2. Property aanmaken in Google Search Console voor `pieter-vandenkeybus.net`.
3. `sitemap.xml` indienen.
4. `lastmod` updaten bij wijzigingen.

## Hoe deze versie onderscheidend is
- **Eigen onderwerp:** volledig rond UX-strategie (Wat / Traject / Voor wie / FAQ / Contact) i.p.v. een algemene profielpagina. Dit is de belangrijkste factor om naast de andere sites te kunnen verschijnen i.p.v. weggeclusterd te worden.
- **Extra structured data:** naast Person/WebSite ook **Service**-schema en een **FAQPage**-schema (kan rich results / FAQ-snippets opleveren).
- **Eigen copy & ontwerp:** teal/deep-palet met Newsreader + Libre Franklin — vierde visuele richting.
- **Eigen canonical** (`https://pieter-vandenkeybus.net/`) en eigen schema `@id`'s op het `.net`-domein.
- **`sameAs`** linkt alle vier de domeinen + LinkedIn + Uflow.

## Belangrijk: maak de koppeling op ALLE sites wederzijds
Voeg op elk van de andere drie sites de ontbrekende domeinen toe aan hun `sameAs`-lijst,
zodat alle vier de domeinen naar elkaar verwijzen. Volledige sameAs-lijst:
- https://pieter-van-den-keybus.be
- https://pieter-vandenkeybus.be
- https://pieter-vandenkeybus.eu
- https://pieter-vandenkeybus.net
- https://www.linkedin.com/in/pietervandenkeybus
- https://uflow.be

## Over het doel: pagina één vullen met eigen sites
Google toont meestal max. 1–2 resultaten per domein en clustert near-duplicate sites van
dezelfde eigenaar samen. Méér plekken op pagina één krijg je dus NIET door kopieën, maar door
bronnen met elk een eigen onderwerp/zoekintentie — plus niet-eigen vindplaatsen zoals LinkedIn,
de Uflow-pagina, gastartikels of interviews. Deze .net-site is daarom bewust op één niche gebouwd.
