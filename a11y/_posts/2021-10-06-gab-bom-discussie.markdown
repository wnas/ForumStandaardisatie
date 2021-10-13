---
layout: post
title:  "Gab en Bom - discussiepunten"
date:   2021-10-06 13:24:14 +0200
categories: gab bom discussie

---
Uit het rapport van Cardan kwamen een aantal zaken die discutable zijn, Ik neem hierover met cardan contact op.

# 1.1.1 niet tekstuele content

> Op [deze groepspagina](https://bom.pleio.nl/groups/view/24a054f2-3ad0-44d4-a02f- 253dc91def98/betrouwbare-overheidsmail staat ) pagina (als er is ingelogd) aan de rechterzijde van de koptekst “Betrouwbare OverheidsMail” een knop met een aria-label attribuut met de waarde “Beheer”. Deze waarde geldt als tekstalternatief, maar is geen duidelijke omschrijving van de knop.

WN - waarom is dit niet duidelijk, de knop gaat over beheer taken...

# 1.3.1 info en relaties ook 2.5.3

> Op [pagina met settings](https://bom.pleio.nl/user/63d3bfde-e6d2-4cde-93cb-e2df4e6bd897/settings) staan meerdere visuele schakelknoppen (in de code checkboxen) die aria-labels hebben met de waarde “Schakel in” of “Schakel uit”. Een aria-label overschrijft de originele waarde van de schakelknop/checkbox. Hierdoor kan software de relatie met het label niet meer bepalen (in dit geval “Nieuwsbrief” of “Notificaties”). Zie ook pagina https://bom.pleio.nl/events/add.

WN - er staat een label voor iedere checkbox met een duidelijke omschrijving...

# 1.4.10 reflow

Wanneer je de [pagina over bestanden](https://gab.pleio.nl/groups/view/3f6561dd-f895-4b2b-9570- b605194c1d5d/gedeelde-presentaties-en-verslagen/files) bekijkt bij een breedte van 320 pixels en vervolgens het tabblad “Bestanden” opent dan valt een deel van de tekst weg in de rechterkolom “Eigenaar”. De tekst is daardoor niet meer volledig te lezen.

WN - wat is de aanrader, deze tabel wordt niet duidelijker als ie over meerdere regels komt... en in de specs staat:
> Voorbeeld van content die een tweedimensionale lay-out vereisen, zijn afbeeldingen, kaarten, schema's, video's, games, presentaties, gegevenstabellen en interfaces waarbij de werkbalken zichtbaar moeten blijven tijdens het manipuleren van de content.

# 2.5.3

Op [profiel-pagina](https://bom.pleio.nl/user/63d3bfde-e6d2-4cde-93cb-e2df4e6bd897/profile) staat (als er is ingelogd) de tekst “Cardan Technobility” met een icoon van een potlood ernaast. Dit is een link met een aria-label met de waarde “Bewerk gebruikersnaam (opent in nieuw venster)”. Dit is de naam van deze link. De naam van de link bevat de zichtbare tekst nu niet.

WN - De naam van de link is correct en beschrijft het linkdoel...

# 3.1.2 taal van de pagina

Op [groeps-pagina](https://gab.pleio.nl/groups/view/3f6561dd-f895-4b2b-9570- b605194c1d5d/gedeelde-presentaties-en-verslagen/files) staat een knop “Log in om lid te worden”. Wanneer hier op geklikt wordt, kom je in een inlogscherm met een invoerveld voor het e-mailadres. Wanneer deze niet of niet juist wordt ingevuld komt de volgende melding in beeld “We could not find a valid account for this email adress. Register your email adress to proceed.” Omdat het een Nederlandse website is, is het beter als de foutmelding ook in het Nederlands is. Als deze foutmelding Engels blijft, moet er een taalwisseling worden aangegeven. Dit kan door lang=”en” te gebruiken in een HTML element dat de Engelse taal bevat.

WN - Dit is een engelse pagina. Dit gaat over Account.pleio.nl en zou geen onderdeel moeten uitmaken van het content onderzoek.

# algemene vraag over PDF documenten

WN - Als de informatie in het document ook op een andere, toegankelijke, manier wordt aangeboden, mag je dan een ontoegankelijke pdf aanbieden op je site?