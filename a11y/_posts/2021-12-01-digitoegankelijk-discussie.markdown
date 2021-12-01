---
layout: post
title:  "digitaaltoegankelijk.pleio.nl - discussiepunten"
date:   2021-12-01 11:50:14 +0200
categories: digitoegankelijk discussie
---

# Discussie

Niet alle punten zijn duidelijk, over onderstaande wil ik graag nog wat feedback.

## toetser

[Swink](https://toegankelijkheidsrapport.swink.nl/pleio-content/audit/issues/)

## Punten

### 1.3.1 info en relaties

Bevinding 15: De volgende bevinding is technisch van aard:
Op pagina digitaaltoegankelijk.pleio.nl/search/results kunnen bezoekers gebruik maken van een kalenderfunctie om zoekresultaten te filteren op datum. In de kalender wordt met een punt (en een andere kleur) aangegeven dat die datum de huidige dag is, maar die informatie wordt niet doorgegeven aan screenreadergebruikers, zij krijgen alleen de datum zelf te horen. Hierdoor krijgt niet iedere gebruiker dezelfde informatie.
Er is een toegankelijk alternatief voor deze functionaliteit, doordat in het invoerveld handmatig een datum ingevoerd kan worden, maar het is beter voor de toegankelijkheid om bovenstaande bevinding op te lossen.

### 2.4.4 Linkdoel (in context)
Bevinding 38

Afbeeldingen in de nieuwsfeed, zoals boven het bericht 'Hoe eet je een olifant' en 'WCAG vs. Usability', fungeren als link, maar hebben geen linktekst door een leeg aria-label. Het beste is om de link van dit gebied af te halen en met Javascript het klikbare gebied te vergroten. Dit komt voor op meerdere pagina's, waaronder digitaaltoegankelijk.pleio.nl/search/results.

> Wat we hebben gedaan is het image een `aria-hidden="true"` gegeven, daardoor is deze opmerking volgens ons niet relevant meer.
