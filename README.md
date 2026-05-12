# S. Laarman Schilderwerken

Statische website voor S. Laarman Schilderwerken (Klussenbedrijf Laarman) in Heemstede.

## Bedrijfsgegevens

- **Naam (logo/posters):** S. Laarman Schilderwerken
- **Officieel:** S. Laarman Klussenbedrijf
- **Adres:** Dr. Droogplein 7, 2101 XM Heemstede
- **Telefoon:** 06 14819224
- **KvK:** 86275526
- **Eigenaar:** Stefan Laarman

## Stack

- HTML + Tailwind CSS (CDN)
- Statische site, geen build step
- Gehost op GitHub Pages

## Lokaal bekijken

Open `index.html` direct in een browser, of start een eenvoudige webserver:

```bash
python3 -m http.server 8000
```

## Deployment

1. Push naar `main` branch
2. In GitHub: Settings → Pages → Source: `main` branch, root folder
3. Site staat op `https://pelejb.github.io/laarman-schilderwerken/`

## Foto's

Plaats foto's in `assets/images/`. Bestandsnamen:

- `hero.jpg` — hero-foto op homepage (schilder aan het werk)
- `stefan.jpg` — portretfoto voor Over Ons pagina
- `og.jpg` — Open Graph preview-afbeelding (1200×630)
- `werk-binnen-*.jpg` — binnenschilderwerk voorbeelden
- `werk-buiten-*.jpg` — buitenschilderwerk voorbeelden

## TODO

- [ ] Foto's plaatsen (Laarman1–16 van klant)
- [ ] Google-reviews verwerken in `#reviews` sectie op `index.html`
- [ ] Contactformulier-endpoint instellen (FormSubmit of vergelijkbaar)
- [ ] Optioneel: aangepaste domeinnaam koppelen via CNAME
