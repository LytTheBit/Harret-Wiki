---
{"dg-publish":true,"permalink":"/Home/","tags":["gardenEntry"],"created":"2026-04-24T14:36:59.227+02:00","updated":"2026-05-07T18:12:04.557+02:00","dg-note-properties":{}}
---

# Harret

Benvenuti ad Harret... non c'è niente qui per ora...


## Campagne
```base
filters:
  and:
    - file.hasTag("Campagna")
views:
  - type: cards
    name: "Sessioni"
    image: immagine
    imageFit: cover
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
    name: "Sessioni"
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