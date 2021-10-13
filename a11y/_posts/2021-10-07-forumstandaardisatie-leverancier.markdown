---
layout: post
title:  "Forum standaardisatie - acties leverancier"
date:   2021-10-07 09:24:14 +0200
categories: forumstandaardisatie leverancier
---
# Nog op te lossen

## 1.1.1 niet tekstuele content

Op alle pagina's staat bovenaan de banner rijksoverheid. Deze afbeelding is een logo en logo’s hebben altijd betekenis en hebben daarom altijd een tekstalternatief nodig.

Op alle pagina's hebben meerdere link de class ‘ext’. Het gaat onder andere om de links ‘Twitter’, ‘LinkedIn’ en ‘Archief website’. Het gebruik van deze class voegt een afbeelding toe die aangeeft dat deze link verwijst naar een externe website. Deze afbeeldingen hebben geen tekstalternatief. Dit probleem komt meer voor dat alleen op deze drie links. 

Let op: er staat content die verborgen is met display:none. Deze eigenschap verbergt deze content voor iedereen en dus ook voor gebruikers van hulpsoftware. Deze content op een andere manier verbergen lost dit probleem op. https://prod-dictu.forumstandaardisatie.nl/

## 1.3.1 info en relaties

Op pagina https://www.forumstandaardisatie.nl/open-standaarden/in-behandeling staan naast de tabel drie lijsten met links en daarboven de koppen ‘Domein’, ‘Europese status (MSP) (field_europese_status_msp_)’ en ‘Trefwoorden’. Deze teksten zijn nu opgemaakt als label-elementen en de links hebben een presentatie die er door de inspringing uitziet als een lijst.

Op pagina https://prod-dictu.forumstandaardisatie.nl/open-standaarden/in- behandeling staat een tabel met meer dan twee kolommen. De gegevens in de eerste kolom moeten opgemaakt worden als tabelkoppen. De td-elementen met links moeten vervangen worden door th-elementen.

Op pagina https://prod-dictu.forumstandaardisatie.nl/zoeken?search_api_fulltext= +Veilig+internet staan 10 van de 99 zoekresultaten. Deze zoekresultaten zijn onterecht opgemaakt als koptekst. Een kop moet namelijk altijd content bevatten. Dit is een lijst met links die groot weergegeven worden (gebruik zodoende ook het HTML lijst element). Gebruik bij voorkeur CSS om links groot weer te geven.

** kop is wel weg, nu de lijst nog...**

Op pagina https://prod-dictu.forumstandaardisatie.nl/agenda/meet-kennisplatform- api is de tekst ‘Erbij zijn?’ opgemaakt met strong. Deze tekst moet opgemaakt worden als koptekst (HTML header element).

## 1.4.13 Content bij aanwijzen of focussen

Op alle pagina's staat content die beschikbaar komt als de muis of toetsenbordfocus op de juiste plaats staat. Het gaat om een aantal links in het hoofdmenu met aria-label ‘Toggle navigation’. In dit menu staan de link ‘Standaardisatie’ tot en met ‘Forum Standaardisatie’. Wanneer de muis of de toetsenbordfocus op een van deze vijf links landt, komt rechts andere content in beeld. Het is mogelijk dat deze nieuwe content andere (oude content) verbergt. Deze content moet daardoor voldoen aan alle drie de bovenstaande eisen. De eisen hoverable en persistent zijn geen probleem. Het probleem is de eis dismissable, de aanvullende content moet te verwijderen zijn zonder de muis of toetsenbordfocus te verplaatsen. Hoe deze content in beeld is gekomen, maakt voor deze eis niet uit. Ook de huidige plaats van de toetsenbordfocus mag geen invloed hebben op de werking van het mechanisme. In de meeste gevallen wordt de Escape-toets gebruikt om dit mogelijk te maken. Het indrukken van deze toets heeft dan tot gevolg dat al deze content verborgen wordt. https://prod-dictu.forumstandaardisatie.nl/

# Opgelost

## 1.3.1 info en relaties

Op alle pagina's staat in de footer de visueel verborgen kop ‘Voet’. Deze kop wordt in de code direct gevolgd door een andere kop van hetzelfde niveau. De kop ‘Voet’ bevat hierdoor geen content. Wanneer de kop ‘Voet’ wordt omgezet van h3 naar h2, is dit probleem opgelost. De vraag is ook of het nodig is om deze kop hier te plaatsen.
https://prod-dictu.forumstandaardisatie.nl/

Op pagina https://prod-dictu.forumstandaardisatie.nl/contact-en-netwerk/BFS- medewerkers staat een overzicht met negen medewerkers. Alle content onder de kop ‘Medewerkers en forumleden’ is in de code opgemaakt als gewone tekst. De namen van de verschillende medewerkers zijn anders weergegeven dan de overige content en deze teksten zeggen iets over de content die eronder staat. Deze namen moeten daarom opgemaakt worden als koppen om de relatie tussen de naam, functie en verschillende contactmogelijkheden goed aan te geven. Tip: wanneer deze content wordt aangepast, is het een optie om de typefout in naam ‘Bertwn Altheer’ ook meteen te corrigeren.

Op pagina https://prod-dictu.forumstandaardisatie.nl/thema/wat-betekent-dit-voor- mij staat het h4-element ‘Downloads’. Deze kop heeft geen content, omdat deze kop in de code direct opgevolgd wordt door een kop van gelijk niveau. Op het moment dat de tweede kop een ander (bij voorkeur lager) niveau heeft, is dit probleem opgelost. Dit probleem komt ook voor bij de kop ‘Downloads’ op pagina https://prod- dictu.forumstandaardisatie.nl/open-standaarden/toetsen-en-aanmelden.

Op pagina https://prod-dictu.forumstandaardisatie.nl/thema/veilig-internet staan twee koppen van gelijk niveau direct achter elkaar. Op deze pagina gaat het om de koppen ‘Betrouwbaarheidsniveaus digitale dienstverlening’ en ‘Handreiking betrouwbaarheidsniveaus’. Dit probleem is alleen aanwezig als de eerstgenoemde knop is uitgeklapt.

Op pagina https://prod-dictu.forumstandaardisatie.nl/vergaderingen-en-stukken staat het label ‘Kies een datum voor de vergaderstukken’ en de knop ‘Filter resultaten’. Het select-element dat het mogelijk moet maken om de resultaten te filteren, is verborgen met display:none. Het label is hierdoor niet geassocieerd met een invoerveld. Een label-element moet altijd gekoppeld zijn aan een invoerveld om te voldoen. Geadviseerd wordt om deze filteroptie te repareren of om deze te verwijderen.

## 1.3.5 inputdoel

Op pagina https://prod-dictu.forumstandaardisatie.nl/form/contact staan invoervelden die aan dit succescriterium moeten gaan voldoen. Het autocomplete- attribuut kan gebruikt worden om hulpsoftware in staat te stellen het doel van een invoerveld te bepalen. Het goed gebruik van autocomplete maakt het mogelijk om deze gegevens in een keer goed in te vullen. Op deze pagina gaat het om de invoervelden ‘Voornaam’, ‘Achternaam’, ‘E-mailadres’ en ‘Telefoon’. Op de Engelstalige pagina https://www.w3.org/TR/WCAG21/#input-purposes staat meer informatie over de mogelijke waarden van dit html5-attribuut. De waarden die gebruikt moeten worden, zijn ‘given-name’, ‘family-name’, ‘email’ en ‘tel’ of ‘tel- national’.

## 1.4.3 contrast minimum

Op alle pagina's hebben de link ‘home’ en de knop ‘Toggle navigation’ (met de zichtbare tekst ‘Menu’) onvoldoende contrast. De oranje achtergrond heeft een contrast van 3,2:1 met de witte tekst. Witte tekst op een oranje achtergrond met onvoldoende contrast komt op andere pagina's op meer plaatsen voor. Binnen de steekproef gaat het om pagina's https://prod-dictu.forumstandaardisatie.nl/, https:// prod-dictu.forumstandaardisatie.nl/form/contact, https://prod- dictu.forumstandaardisatie.nl/thema en https://prod-dictu.forumstandaardisatie.nl/ vergaderingen-en-stukken. Opvallend hierbij is dat de oranje koppen op pagina https://prod-dictu.forumstandaardisatie.nl/ wel voldoen. Deze koppen gelden als grote tekst en hebben met een contrast van 3,2:1 voldoende contrast.

## 1.4.10 Dynamisch aanpassen

Op pagina https://prod-dictu.forumstandaardisatie.nl/vergaderingen-en-stukken staan zes lijsten met vergaderstukken. Deze lijsten hebben een ingestelde breedte (width), het gevolg is dat de links in deze lijsten niet over meerdere regels worden verdeeld als de viewport wordt ingesteld op een breedte van 320px. Horizontaal scrollen zou niet noodzakelijk moeten zijn om de volledige tekst van deze links te lezen.

## 2.1.1 Toetsenbord

Op pagina's https://prod-dictu.forumstandaardisatie.nl/thema/wat-betekent-dit-voor- mij, https://prod-dictu.forumstandaardisatie.nl/open-standaarden/toetsen-en- aanmelden en https://prod-dictu.forumstandaardisatie.nl/thema/veilig-internet staat uitklapbare div-elementen die niet met het toetsenbord te bedienen zijn. Deze elementen met role=”button” kunnen geen toetsenbordfocus ontvangen. Hiervoor zijn meerdere oplossingen mogelijk. Eén van de oplossingen is om gebruik te maken van de html5-elementen details en summary. Deze elementen zijn in html5 gecreëerd om als disclosure-elementen te gebruiken. De implementatie van deze elementen is eenvoudiger dan de implementatie van volledige en correcte WAI-ARIA code.

## 2.4.1 Blokken omzeilen

Zorg ervoor dat blinde bezoekers en toetsenbordgebruikers blokken herhalende content kunnen overslaan, zodat zij direct bij de hoofdcontent kunnen komen. Denk bij blokken herhalende content aan alles dat zich op meerdere pagina's herhaalt: menu's, een zoekveld, logo etc. De beste manier om het overslaan van herhalende content mogelijk te maken, is door bovenaan de pagina een skiplink te bieden die direct naar de hoofdcontent leidt. Zorg ervoor dat de link zichtbaar wordt, wanneer deze met het toetsenbordfocus ontvangt. Zie onze website als voorbeeld: www.accessibility.nl.

## 2.4.2 Paginatitel

Pagina's https://prod-dictu.forumstandaardisatie.nl/contact en https://prod- dictu.forumstandaardisatie.nl/form/contact hebben beide de paginatitel ‘Contact | Bureau Forum Standaardisatie’. De eerste pagina geeft een overzicht van de verschillende manieren om contact op te nemen en de tweede pagina bevat het online contactformulier. Dit verschil in onderwerp of doel moet blijken uit een verschil in paginatitel.
Pagina https://prod-dictu.forumstandaardisatie.nl/over-ons heeft met ‘Forum Standaardisatie | Bureau Forum Standaardisatie’ ook geen paginatitel die het doel of onderwerp van deze pagina goed beschrijft. De tekst in de URL is wel duidelijk. De paginatitel ‘Over ons | Bureau Forum Standaardisatie’ zou wel voldoende zijn.

## 2.4.3 focus volgorde

Op alle pagina's staat in het hoofdmenu een knop met de zichtbare tekst ‘Menu’. Na het activeren van de knop ‘Toggle navigation’ komt een lightbox in beeld. Een lightbox (ook wel modal of dialog genoemd) heeft een aantal eisen met betrekking tot de focusvolgorde. De toetsenbordfocus mag, zolang dit venster open staat, niet op de achterliggende pagina komen. Ook moet de toetsenbordfocus eerst naar de nieuwe content gaan, voordat deze op de zoekfunctie landt. De derde eis is dat bij het sluiten van deze lightbox de toetsenbordfocus moet landen op een logische plaats; in dit geval de knop met de tekst ‘Menu’.
https://prod-dictu.forumstandaardisatie.nl/