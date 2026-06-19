# BWL Assets

Publieke afbeeldingenmap voor BitesWeLove. Hier staan logo's, productfoto's, sfeerbeelden en huisstijl-elementen die we vrij mogen gebruiken in presentaties, websites, social, persberichten, etc.

> **Let op:** deze repo is **publiek**. Plaats hier alleen materiaal dat openbaar gebruikt mag worden. Geen interne foto's, geen vertrouwelijke documenten.

## Mappenstructuur

| Map | Wat erin komt |
|---|---|
| `logos/` | BWL-logo's in alle varianten (kleur, zwart, wit, met/zonder payoff) |
| `products/` | Productfoto's (pack-shots, pack op transparant, renders) |
| `packaging/` | Verpakkings-shots, BOP-foto's |
| `lifestyle/` | Sfeerfoto's, mensen, eetmomenten |
| `patterns/` | Brand-patronen, achtergrondtexturen |
| `icons/` | Pictogrammen, illustraties |

## Hoe je een afbeelding gebruikt

Elke afbeelding krijgt een vaste publieke URL volgens dit patroon:

```
https://biteswelove.github.io/bwl-assets/<map>/<bestandsnaam>
```

Voorbeelden (deze bestaan echt en werken):

```
https://biteswelove.github.io/bwl-assets/logos/bwl-logo.png
https://biteswelove.github.io/bwl-assets/logos/bwl-logo-1x1-transparant.png
https://biteswelove.github.io/bwl-assets/products/chewy-oat-bars/multipacks/chewy-oat-bars-vanilla-multipack-01.jpg
```

> **Belangrijk:** het domein is `biteswelove.github.io` (de BitesWeLove-organisatie), **niet** `marleen-basart.github.io`. De oude marleen-URL werkt niet meer sinds de repo naar de organisatie is verhuisd.

Deze URL's werken in:
- HTML / websites (`<img src="...">`)
- Presentaties (BWL deck-template)
- Markdown-documenten (`![alt](url)`)
- Mails met inline afbeeldingen

> **Tip:** weet je de exacte bestandsnaam niet? Blader door de mappen op github.com/BitesWeLove/bwl-assets, of kijk op de index: https://biteswelove.github.io/bwl-assets/ . Verzin geen bestandsnamen — gebruik alleen bestanden die er echt staan, anders laadt de afbeelding niet.

## Hoe je een nieuwe afbeelding toevoegt

1. Ga naar deze repo op github.com
2. Open de juiste map (bv. `lifestyle/`)
3. Klik op **Add file → Upload files**
4. Sleep je afbeelding erin
5. Onderaan klik je op **Commit changes**

Klaar. Na ~1 minuut is hij beschikbaar op het URL hierboven.

## Naamgevingsconventies

- Lowercase, geen spaties: gebruik `-` tussen woorden
- Beschrijvend: `chewy-oat-bar-matcha.png` ✓, niet `IMG_2934.jpg` ✗
- Versies: voeg een datum toe als je een nieuwere variant hebt: `bwl-logo-v2-2026.png`
- Bestandsformaten:
  - **Logo's**: `.svg` (schaalbaar) of `.png` met transparante achtergrond
  - **Foto's**: `.jpg` (klein, voor web) of `.png` (als je transparantie nodig hebt)
  - **Patronen**: `.svg` of `.png`

## Bestandsgrootte

Houd het redelijk:
- Foto's: ideaal onder 500 KB, max 2 MB
- Logo's: onder 100 KB
- Heel grote foto's (RAW, print-resolutie): elders bewaren, niet in deze repo

GitHub blokkeert bestanden boven de 100 MB sowieso.
