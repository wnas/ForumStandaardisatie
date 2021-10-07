---
layout: post
title:  "Gab en Bom - PDF"
date:   2021-10-06 13:24:14 +0200
categories: gab bom pdf
---
Uit het rapport van Cardan kwamen een aantal zaken die betrekking hebben op PDF bestanden. Deze zijn als volgt

# 1.1.1 niet tekstuele content

In het PDF-document op [deze pagina](https://bom.pleio.nl/files/view/c3722915-6156-473d-83d5- d3f252c5e31b/1556887360190411%20bom%2011-04%20v0.1%20(rvr).pdf)  staat op iedere pagina bovenaan een afbeelding van een logo. Om te voldoen aan dit succescriterium is het nodig dat de eerste afbeelding van het logo over een beschrijvend tekstalternatief beschikt. Dit is momenteel niet het geval. De keren dat het logo hierna herhaald wordt, mag de afbeelding worden genegeerd. Dit is mogelijk door de afbeeldingen als achtergrond (artefact) te markeren.

# 1.3.1 info en relaties

In [het PDF-document](https://bom.pleio.nl/files/view/c3722915-6156-473d-83d5- d3f252c5e31b/1556887360190411%20bom%2011-04%20v0.1%20(rvr).pdf)  zijn meerdere onderdelen niet getagd. Het gaat bijvoorbeeld om de afbeelding van het logo op de eerste pagina van het document.

In het PDF-document op [deze pagina](https://bom.pleio.nl/files/view/012b7b23-03f2-4a90-bebe- 9cb3f11a7d8e/1547052923181214%20notulen%20bom%2029-11%20v0.1%20(rvr).pdf)  hebben veel onderdelen de verkeerde tags gekregen. Zo staan er meerdere kopteksten die niet als koptekst getagd zijn, maar deze staan in een tabel. De relatie tussen deze kopteksten en de bijbehorende content is hierdoor niet beschikbaar voor hulpsoftware. Enkele voorbeelden hiervan zijn bij de kopteksten “Onderwerp”, “Datum” en “Locatie” op de eerste pagina van het document.

Onder de koptekst “Concept agenda” staat een genummerde lijst die niet als lijst is getagd. Verder zijn er meerdere h1-koppen gebruikt, het is best practice om maar één h1-kop per bestand te gebruiken. De overige koppen zijn dan van een lager niveau.

De twee PDF-documenten uit de steekproef die vallen onder het domein gab.pleio zijn beiden niet getagd. Dit wil zeggen dat er geen structuur is aangegeven in het bestand door middel van tags. Hulpsoftware (zoals een screenreader) kan hierdoor niet bepalen wat koppen, lijsten en dergelijke zijn en zal afbeeldingen negeren. Als het bestand correct getagd wordt, kan hulpsoftware beter de structuur en relaties bepalen. Bij koppen kan dan bijvoorbeeld worden voorgelezen dat dit koppen zijn. In veel gevallen kan dit probleem worden opgelost door het document vanuit het bronbestand (meestal in Word of InDesign) opnieuw te exporteren naar pdf, maar dan inclusief tags of labels. Omdat nu de tags ontbreken, kunnen andere succescriteria zoals 1.1.1 en 1.3.2 niet onderzocht worden. Let daarom op dat bij het oplossen van dit probleem nieuwe toegankelijkheidsproblemen kunnen ontstaan. https://gab.pleio.nl/files/view/15c098d2-43fa-4a55-8540-8aa089414dfb/1562308966gab %20jaarverslag%202018.pdf en https://gab.pleio.nl/files/view/81412373-2a6d-4767-98ce- 1909123db745/1559917495gab-harmonisatieafspraak%20bedrag%20v1.1.pdf.

# 1.3.2 Betekenisvolle volgorde

In het PDF-document op [pagina](https://bom.pleio.nl/files/view/c3722915-6156-473d-83d5- d3f252c5e31b/1556887360190411%20bom%2011-04%20v0.1%20(rvr).pdf) komt de visuele leesvolgorde niet altijd overeen met de volgorde van de tags. Een voorbeeld hiervan is op de tweede pagina van het document bij de koptekst “Aanwezigen” en de lijst met namen hieronder. Deze koptekst schetst de context voor de lijst met namen. Hierdoor is het van belang dat de volgorde klopt, zodat deze informatie ook beschikbaar is voor gebruikers van hulpsoftware. Dit type probleem komt vaker voor in het document, zoals bij de kopteksten “Agenda”, “Afmeldingen” en “Vorige bijeenkomst” en de lijsten onder deze kopteksten. Dit zijn slechts enkele voorbeelden van dit probleem, dat vaker voorkomt in het document.

# 1.4.3 contrast (minimum)

In [document](https://gab.pleio.nl/files/view/81412373-2a6d-4767-98ce- 1909123db745/1559917495gab-harmonisatieafspraak%20bedrag%20v1.1.pdf) staan op verschillende pagina’s lichtblauwe kopjes. Deze lichtblauwe kopjes geven onvoldoende contrast met de witte achtergrond. Gemeten is een contrast van 4:1 op pagina 1, op pagina twee is een andere kleur blauw gebruikt en meet het contrast nog lager namelijk; 2,9:1. Op pagina 9 staat een XML-schema met daarin groene tekst. De groene tekst heeft een contrast van 4,1:1 met de lichtgrijze achtergrond. Hier is minimaal een contrast van 4,5:1 vereist.
In het PDF-document dat te downloaden is via pagina
https://bom.pleio.nl/files/view/c3722915-6156-473d-83d5- d3f252c5e31b/1556887360190411%20bom%2011-04%20v0.1%20(rvr).pdf staat op bijna iedere pagina rechtsonder een paginanummer met een gemeten contrast van 2,4:1.

# 2.4.2 paginatitel A

Het PDF-document op [pagina](https://bom.pleio.nl/files/view/c3722915-6156-473d-83d5- d3f252c5e31b/1556887360190411%20bom%2011-04%20v0.1%20(rvr).pdf) heeft de titel “Dia 1”. Deze titel omschrijft niet het onderwerp van het document. De titel kan worden aangepast in de documenteigenschappen en in het bronbestand.

Dit type probleem doet zich ook voor bij het PDF-document op [pagina](https://bom.pleio.nl/files/view/012b7b23-03f2-4a90-bebe- 9cb3f11a7d8e/1547052923181214%20notulen%20bom%2029-11%20v0.1%20(rvr).pdf). Dit document heeft de titel “Notitie”. Tevens wordt bij dit document de bestandsnaam getoond in plaats van de titel van het document. Dit kan worden aangepast in de documenteigenschappen.

Het [document](https://gab.pleio.nl/files/view/81412373-2a6d-4767-98ce- 1909123db745/1559917495gab-harmonisatieafspraak%20bedrag%20v1.1.pdf) heeft een titel in de documenteigenschappen (GAB-Harmonisatieafspraak Bedrag v1.1) maar dit is niet de titel die wordt weergegeven in de titelbalk van het document (daar staat de bestandsnaam). Dit is in te stellen in de eigenschappen van het brondocument. Hetzelfde geldt voor het document https://gab.pleio.nl/files/view/81412373-2a6d-4767-98ce- 1909123db745/1559917495gab-harmonisatieafspraak%20bedrag%20v1.1.pdf.

# 2.4.4

In het [document](https://gab.pleio.nl/files/view/81412373-2a6d-4767-98ce- 1909123db745/1559917495gab-harmonisatieafspraak%20bedrag%20v1.1.pdf) staan onderaan pagina 6 diverse links waarvan het linkdoel niet duidelijk is. Dit komt doordat van de URL de linktekst is gemaakt. Het is beter om de links een beschrijvende titel te geven.

# 3.1.1

In de documenten [1](https://gab.pleio.nl/files/view/81412373-2a6d-4767-98ce- 1909123db745/1559917495gab-harmonisatieafspraak%20bedrag%20v1.1.pdf) en [2](https://gab.pleio.nl/files/view/81412373-2a6d-4767-98ce-1909123db745/1559917495gab- harmonisatieafspraak%20bedrag%20v1.1.pdf) is geen taal ingesteld in de documenteigenschappen. Door deze taal in te stellen weet hulpsoftware in welke taal het document moet worden voorgelezen.