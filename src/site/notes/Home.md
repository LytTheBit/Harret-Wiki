---
{"dg-publish":true,"permalink":"/Home/","tags":["gardenEntry"],"created":"2026-04-24T14:36:59.227+02:00","updated":"2026-05-08T09:50:43.532+02:00","dg-note-properties":{}}
---

# Home

Benvenuti su [[Harret\|Harret]]... non c'è niente qui per ora... credo... 

## Campagne
Lista delle campagne della ambientazione.
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

---
## Giocatori
Lista dei giocatori che hanno partecipato alle campagne.
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

---
## Personaggi
Lista dei PG creati dai giocatori nel corso delle campagne.
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
