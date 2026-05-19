# BWL Fonts

Officiële huisstijl-fonts van BitesWeLove. Deze fonts worden gebruikt in presentaties, websites, social en alle digitale uitingen.

## Beschikbaar

| Map | Font | Gewichten | Gebruik |
|---|---|---|---|
| `obviously-narrow/` | Obviously Narrow (OH no Type Co) | Regular, Italic, Bold | Hoofd-huisstijl — headings, body, accenten |
| `mudstone-sans/` | Mudstone Sans | Black | Protein-productlijn |

## Hoe gebruiken (web / presentaties)

Voeg dit toe aan je HTML/CSS:

```html
<style>
  @font-face {
    font-family: 'Obviously Narrow';
    src: url('https://biteswelove.github.io/bwl-assets/fonts/obviously-narrow/ObviouslyNarrow-Regular.otf') format('opentype');
    font-weight: 400;
    font-style: normal;
  }
  @font-face {
    font-family: 'Obviously Narrow';
    src: url('https://biteswelove.github.io/bwl-assets/fonts/obviously-narrow/ObviouslyNarrow-Italic.otf') format('opentype');
    font-weight: 400;
    font-style: italic;
  }
  @font-face {
    font-family: 'Obviously Narrow';
    src: url('https://biteswelove.github.io/bwl-assets/fonts/obviously-narrow/ObviouslyNarrow-Bold.otf') format('opentype');
    font-weight: 700;
    font-style: normal;
  }
  @font-face {
    font-family: 'Mudstone Sans';
    src: url('https://biteswelove.github.io/bwl-assets/fonts/mudstone-sans/MudstoneSans-Black.otf') format('opentype');
    font-weight: 900;
    font-style: normal;
  }

  body {
    font-family: 'Obviously Narrow', 'Helvetica Neue', sans-serif;
  }
</style>
```

## Licentie & gebruik

> ⚠️ **Belangrijk**
>
> **Obviously Narrow** is een commerciële font van [OH no Type Co](https://ohnotype.co/). De licentie staat op naam van BitesWeLove.
>
> **Mudstone Sans** komt van [fonnts.com](https://fonnts.com/) — controleer de licentie-voorwaarden van de specifieke variant.
>
> Deze fonts mogen **uitsluitend** worden gebruikt voor BWL-projecten. Niet redistribueren of doorverkopen. Wel toegestaan: embedden in BWL-websites, decks, ads, en social.

## Source

Originelen staan in BWL Google Drive → `BitesWeLove NL (Shared Drive)/BWL Design/Brand Assets/Fonts/`. Bij twijfel of een nieuwe versie: daar kijken.

## Vragen

Onduidelijkheden over licentie of gebruik? Contact Marleen.
