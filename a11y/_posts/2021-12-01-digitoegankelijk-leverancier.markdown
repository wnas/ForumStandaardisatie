---
layout: post
title:  "digitaaltoegankelijk.pleio.nl - acties leverancier"
date:   2021-12-15 11:50:14 +0200
categories: digitoegankelijk leverancier
---


# Leverancier

Bij deze punten is een actie van de leverancier nodig, code moet worden verbetert om deze punten op te lossen.

## toetser

Swink.

## Op te lossen (pleio)
Issues die in het Pleio platform moeten worden opgelost

Hieronder worden de issues uit het onderzoek van Swink genoemd die voortkomen uit de functionaliteit van het Pleio platform. Vermoedelijk is een groot deel van deze issues al opgelost.


## Opgelost
### 1.3.1 Info en relaties
Bevinding 8 : De kolom 'naam' in de tabel op de pagina met bestanden heeft als toegankelijke naam 'Sorteer op naam'. Screenreadergebruikers krijgen dus bij elk item in die kolom eerst 'Sorteer op naam (oplopend/aflopend)' te horen. Dit is verwarrend aangezien gebruikers in de rijen van de bestanden niet meer kunnen sorteren op naam. Dit kan wellicht met ARIA worden opgelost.

[issue 8717](https://gitlab.com/pleio/beheer/-/issues/8717)

Bevinding 10: De namen van de groepen op pagina digitaaltoegankelijk.pleio.nl/groups zien er als koppen uit, maar zijn niet opgemaakt als kop. Het zijn links, maar tegelijkertijd fungeert de tekst ook als kop boven de introductie tekst. Gebruik een headingselement, bijvoorbeeld h2, om dit probleem op te lossen.

[issue 8718](https://gitlab.com/pleio/beheer/-/issues/8718)

Bevinding 12

Op de wiki pagina Presentatie PDF en toegankelijkheid is de groepnaam 'Digitaal toegankelijke documenten (PDF)', linksboven van de pagina (link) opgemaakt als kop, terwijl het geen kop is.

[issue 8719](https://gitlab.com/pleio/beheer/-/issues/8719)

Bevinding 14

Best practice: Een duidelijke headingstructuur is belangrijk voor gebruikers die een website gebruiken met een screenreader. Op verschillende pagina's, zoals de vragen pagina, is deze headingstructuur niet optimaal, omdat de hoofditems op de pagina een h3 heading hebben in plaats van een h2 heading. Dit maakt deze items op de pagina voor hulpsoftware minder belangrijk.

### 1.4.11 Contrast van niet-tekstuele content

Bevinding 23

De blauwe focusrand om de links 'Log in' en 'Registreer' heeft een te lage contrastwaarde met de oranje achtergrond (1,4:1).

Dit issue lijkt opgelost te zijn.


### 3.1.2Taal van onderdelen

Bevinding 47

Op pagina de resultatenpagina voor zoekopdracht 'publiceren' kunnen gebruikers resultaten filteren met een kalenderfunctionaliteit. De knoppen voor volgende en vorige maand zijn hebben een aria-label met Engelstalige tekst. Voor woorden in een taal die afwijken van de hoofdtaal van de pagina moet een taalwisseling worden aangegeven. Echter, het is beter hier Nederlandstalige tekst te gebruiken. Er is een toegankelijk alternatief voor deze functionaliteit, doordat in het invoerveld handmatig een datum ingevoerd kan worden, maar het is beter voor de toegankelijkheid om bovenstaande bevinding op te lossen.

### 4.1.2 Naam, rol, waarde
Bevinding 51

Op de groepspagina 'Digitaal toegankelijke websites staat rechts in de sidebar een button '224 leden'. De toegankelijke naam van de button is '+219 224 leden', wat verwarrend is voor screenreader gebruikers. Dit komt ook voor op de landingspagina's van andere groepen zoals de landingspagina van de groep 'Marktaanbod digitale toegankelijkheid'.