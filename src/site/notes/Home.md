---
{"dg-publish":true,"permalink":"/Home/","tags":["gardenEntry"],"created":"2026-04-24T14:36:59.227+02:00","updated":"2026-05-07T20:59:01.411+02:00","dg-note-properties":{}}
---

# Home

Benvenuti su [[Harret\|Harret]]... non c'è niente qui per ora... credo...


## Campagne
```base
filters:
  and:
    - file.hasTag("Campagna")
views:
  - type: cards
    name: "Campagne"
    image: immagine
    imageFit: cover
    order:
      - file.name
```

```base
filters:
  and:
    - file.hasTag("Campagna")
formulas:
  primaImmagine: file.embeds[0]
views:
  - type: cards
    name: "Campagne"
    imageFit: cover
    image: formula.primaImmagine
    order:
      - file.name
```

## Giocatori
```base
filters:
  and:
    - file.hasTag("Player")
views:
  - type: cards
    name: "Giocatori"
    image: immagine
    imageFit: cover
    order:
      - file.name
```
## Personaggi
```base
filters:
  and:
    - file.hasTag("PG")
views:
  - type: cards
    name: "Personaggi Giocanti"
    image: immagine
    imageFit: cover
    order:
      - file.name
```
> [!info] Titolo
> Questo è un callout informativo!

> [!warning] Attenzione
> Questo è un avviso!

> [!tip] Suggerimento
> Questo è un consiglio utile.