---
layout: post
title:  "Forum standaardisatie - acties leverancier"
date:   2022-01-12 13:21:14 +0200
categories: forumstandaardisatie leverancier
---
# Nog op te lossen


## 1.1.1 niet tekstuele content

### Forum standaardisatie
Op alle pagina's staat bovenaan de banner rijksoverheid. Deze afbeelding is een logo en logo’s hebben altijd betekenis en hebben daarom altijd een tekstalternatief nodig.

Op alle pagina's hebben meerdere link de class ‘ext’. Het gaat onder andere om de links ‘Twitter’, ‘LinkedIn’ en ‘Archief website’. Het gebruik van deze class voegt een afbeelding toe die aangeeft dat deze link verwijst naar een externe website. Deze afbeeldingen hebben geen tekstalternatief. Dit probleem komt meer voor dat alleen op deze drie links.

Let op: er staat content die verborgen is met display:none. Deze eigenschap verbergt deze content voor iedereen en dus ook voor gebruikers van hulpsoftware. Deze content op een andere manier verbergen lost dit probleem op. https://prod-dictu.forumstandaardisatie.nl/

### Beslisboom

In verschillende stappen van het proces staat er bij sommige opties een oranje symbool van de letter “i”. Dit symbool heeft geen alternatieve tekst. Er moet een alternatieve tekst komen die dezelfde informatie overbrengt als het symbool, bijvoorbeeld “Meer informatie”. Zie bijvoorbeeld bij [stap 1](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/1) bij de checkbox “Gemeente of gemeenschappelijke regeling”.

In [stap 8](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/8) kan er in het formulier de foutmelding “Het e-mailadres ... is ongeldig” verschijnen. Deze kan worden verborgen door op het kruisje te klikken. Dit is een knop met als naam “x”. Er moet een alternatieve tekst als “Sluiten” of iets dergelijks komen.

## 1.3.1 info en relaties

### Forum standaardisatie

Onderaan de [pagina](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden) staat boven de footer de tekst “Standaard Samenwerken”. Het div- element waar deze tekst in staat, is verborgen met aria-hidden=”true”. Hierdoor kan hulpsoftware deze informatie niet voorlezen.

Op [deze pagina](https://www.forumstandaardisatie.nl/open-standaarden/in-behandeling) staan naast de tabel drie lijsten met links en daarboven de koppen ‘Domein’, ‘Europese status (MSP) (field_europese_status_msp_)’ en ‘Trefwoorden’. Deze teksten zijn nu opgemaakt als label-elementen en de links hebben een presentatie die er door de inspringing uitziet als een lijst.

Op [deze pagina](https://prod-dictu.forumstandaardisatie.nl/open-standaarden/in-behandeling) staat een tabel met meer dan twee kolommen. De gegevens in de eerste kolom moeten opgemaakt worden als tabelkoppen. De td-elementen met links moeten vervangen worden door th-elementen.

Op [zoekpagina](https://prod-dictu.forumstandaardisatie.nl/zoeken?search_api_fulltext=+Veilig+internet) staan 10 van de 99 zoekresultaten. Deze zoekresultaten zijn onterecht opgemaakt als koptekst. Een kop moet namelijk altijd content bevatten. Dit is een lijst met links die groot weergegeven worden (gebruik zodoende ook het HTML lijst element). Gebruik bij voorkeur CSS om links groot weer te geven.

** kop is wel weg, nu de lijst nog...**

Op [deze evenementpagina](https://prod-dictu.forumstandaardisatie.nl/agenda/meet-kennisplatform-api) is de tekst ‘Erbij zijn?’ opgemaakt met strong. Deze tekst moet opgemaakt worden als koptekst (HTML header element).

### Beslisboom

In meerdere stappen van het proces staan rechts op de pagina links naar standaarden (zie onder de kop “Relevante standaarden voor u” (bijvoorbeeld op [stap 5](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/5)). Tijdens het doorlopen van de beslisboom, worden niet relevante standaarden doorgehaald. Dit is duidelijk door de visuele presentatie. Software kan dit niet bepalen. Hulpsoftware kan nu niet voorlezen welke standaarden relevant zijn en welke niet. Er zijn meerdere oplossingen mogelijk. Er kan bijvoorbeeld bij doorgehaalde links een verborgen tekst worden geplaatst die dezelfde informatie overbrengt als de presentatie.

Bij de stappen in het proces staat er telkens een vraag die bij de groep checkboxen hoort. Deze is opgemaakt met een strong-element. Een strong-element is bedoeld om nadruk aan tekst te geven, niet om te stylen. Deze tekst kan opgemaakt worden met CSS. Zie bijvoorbeeld de tekst “Er is een bepaalde vorm van ICT ...” op pagina [stap 1](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/1). Dit komt bij meerdere stappen voor.

Onder de vraag staat een groep checkboxen. Software moet kunnen bepalen dat deze groep bij elkaar hoort en dat de overkoepelende vraag bij deze groep hoort. Dit kan door een fieldset-element om de groep heen te zetten en de vraag in een legend-element te zetten. Software kan dan de relaties bepalen die visueel duidelijk zijn.
Dit komt bij meerdere stappen voor, zie bijvoorbeeld [stap 1](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/1).

Bij [stap 6](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open- standaarden/step/6) worden er meerdere vragen gesteld met telkens drie keuzes. Ook hier moet software kunnen bepalen welke groepen radiobuttons bij elkaar horen en wat de overkoepelende vraag is. Hier kan dus voor elke vraag een fieldset en legend combinatie worden gebruikt. Nu leest voorleessoftware voor dat alle radiobuttons bij één groep horen (bij vier vragen wordt er bij een radiobutton bijvoorbeeld voorgelezen “Keuzerondje 1 van 12”).

Bij een groep radiobuttons kan er altijd één van de groep geselecteerd worden. Een groep radiobuttons die bij elkaar hoort heeft normaal gesproken een gelijke waarde voor het name-atttribuut. Dan kan er ook met de pijltjestoetsen tussen opties worden geschakeld en zitten niet alle radiobuttons apart in de tabvolgorde, zoals hier het geval is.
De zichtbare teksten “Vraag”, “Ja”, “Nee” en “Weet ik niet” (boven de radiobuttons) zouden verborgen kunnen worden voor hulpsoftware. De radiobuttons hebben verborgen labels en als deze aan de overkoepelende vraag gekoppeld worden, kan software de relaties bepalen.

De vragen zijn ook hier telkens met strong-elementen opgemaakt, dit is niet de bedoeling.

In verschillende stappen van het proces staat er bij sommige opties een oranje symbool van de letter “i”. Als de toetsenbordfocus hier op staat of er wordt met de muis overheen gegaan (hover), dan verschijnt er meer informatie. Deze informatie wordt niet meteen voorgelezen door voorleessoftware. Deze informatie staat in de code pas na alle andere content. De informatie is wel gekoppeld met aria-describedby, maar wordt waarschijnlijk niet voorgelezen omdat dit symbool van de “i” een div-element is zonder rol. Dit zou opgelost kunnen worden door hier een knop van te maken die in- en uitgeklapt kan worden, zie ook succescriterium 4.1.2.

Zie bijvoorbeeld bij [stap 1](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/1) bij de checkbox “Gemeente of gemeenschappelijke regeling”.

Het volgende kan de toegankelijkheid nog verbeteren.
Onder de kop “Relevante standaarden voor u” staan onder de [koppen](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden) zoals “Bouw” telkens een paar links naar standaarden. Er is geen opmaak met opsommingstekens, maar het zou wel goed zijn als dit in de code als lijst wordt opgemaakt. Hulpsoftware kan dan voorlezen dat het een lijst is en hoeveel items de lijst heeft.

## 1.4.4 Herschalen van tekst

### Beslisboom

In het proces van de beslisboom staan de stappen 1 tot en met 6 aangegeven boven de voortgangsbalk. De stappen die voltooid zijn werken als knoppen om terug te gaan naar die stap. Als er wordt ingezoomd met 200% bij een resolutie van 1024x768, is alleen de huidige stap te zien. Dit is een verlies van content en functionaliteit. Zie bijvoorbeeld [stap 6](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/6).

## 1.4.10 Reflow

### Beslisboom

In het proces van de beslisboom staan de stappen 1 tot en met 6 aangegeven boven de voortgangsbalk. De stappen die voltooid zijn werken als knoppen om terug te gaan naar die stap. Bij een breedte van 320 pixels is alleen de huidige stap te zien. Dit is een verlies van content en functionaliteit. Zie bijvoorbeeld [stap 6](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/6).

## 1.4.11 Contrast van niet tekstuele content

### Beslisboom

In verschillende stappen van het proces staat er bij sommige opties een symbool van de letter “i”. Dit oranje symbool op de grijze achtergrond heeft een contrast van 2,9:1. Dit is net te laag, het contrast moet minstens 3,0:1 zijn.
Zie bijvoorbeeld bij[stap 1])https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/1) bij de checkbox “Gemeente of gemeenschappelijke regeling”.

In [stap 8](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/8) staat er een formulier met twee velden. Deze velden hebben een grijze rand. Het contrast van het witte veld met de grijze rand is 1,5:1. Dit is te laag, dit moet minstens 3,0:1 zijn. Slechtzienden kunnen moeite hebben om de velden te onderscheiden.

## 1.4.13 Content bij aanwijzen of focussen

### Forum standaardisatie
Op alle pagina's staat content die beschikbaar komt als de muis of toetsenbordfocus op de juiste plaats staat. Het gaat om een aantal links in het hoofdmenu met aria-label ‘Toggle navigation’. In dit menu staan de link ‘Standaardisatie’ tot en met ‘Forum Standaardisatie’. Wanneer de muis of de toetsenbordfocus op een van deze vijf links landt, komt rechts andere content in beeld. Het is mogelijk dat deze nieuwe content andere (oude content) verbergt. Deze content moet daardoor voldoen aan alle drie de bovenstaande eisen. De eisen hoverable en persistent zijn geen probleem. Het probleem is de eis dismissable, de aanvullende content moet te verwijderen zijn zonder de muis of toetsenbordfocus te verplaatsen. Hoe deze content in beeld is gekomen, maakt voor deze eis niet uit. Ook de huidige plaats van de toetsenbordfocus mag geen invloed hebben op de werking van het mechanisme. In de meeste gevallen wordt de Escape-toets gebruikt om dit mogelijk te maken. Het indrukken van deze toets heeft dan tot gevolg dat al deze content verborgen wordt. https://forumstandaardisatie.nl/

### Beslisboom

In verschillende stappen van het proces staat er bij sommige opties een oranje symbool van de letter “i”. Als de toetsenbordfocus hier op staat of er wordt met de muis overheen gegaan (hover), dan verschijnt er meer informatie. Content die onder focus of hover verschijnt moet aan drie voorwaarden voldoen. Er wordt nu niet voldaan aan de voorwaarde “Sluiten”. De content die verschijnt kan over andere content heen vallen. De content moet dan gesloten kunnen worden zonder de focus of muis te verplaatsen. Dit is nu niet mogelijk. Dit moet bijvoorbeeld kunnen met de `Escape` toets.

Zie bijvoorbeeld bij [stap 1](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/2) bij de checkbox “Weet ik niet”.

## 2.4.3 focus volgorde

### Beslisboom

Bovenaan de pagina staat de knop “Menu”. Als hier op geklikt wordt, klapt het menu uit. Als er met het toetsenbord wordt genavigeerd, moet de toetsenbordfocus daarna naar de uitgeklapte content gaan. Nu gaat de toetsenbordfocus eerst naar de knop “Zoeken”, dat is niet logisch. https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/

## 2.4.4 Linkdoel

### Beslisboom

In [stap 7](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/7) wordt er een overzicht gegeven van standaarden die uit de beslisboom zijn gekomen. Onder elke standaard staat er een link “Leer meer”. Deze links hebben geen context met de bovenstaande paragraaf of kop. Een blinde kan een lijst met links maken of naar een link navigeren. Deze links zijn dan hetzelfde, het verschil is niet duidelijk. Er zijn meerdere oplossingen mogelijk. Er kan bijvoorbeeld een (verborgen) linktekst of een title-attribuut worden geplaatst met meer informatie.

Het zou ook beter zijn om deze content niet onder hover of focus te laten verschijnen, maar door er op te klikken.

WN - pas ook op met het openen van content in een nieuw venster, zie op deze [pagina meer informatie](https://webaim.org/techniques/hypertext/hypertext_links)
## 2.5.3 Label in naam

### Beslisboom

 Links boven aan de pagina staat het broodkruimelpad. Hierin staat de link “Forum Standaardisatie”. Deze link heeft een aria-label met de waarde “Back to homepage”. Dit overschrijft de originele linktekst. Hierdoor bevat de naam van de link de zichtbare tekst niet.
https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden 

## 4.1.2 Naam, rol, waarde

### Beslisboom

In verschillende stappen van het proces staat er bij sommige opties een oranje symbool van de letter “i”. Dit is een interactief item. Software kan de interactieve rol niet bepalen. Onder hover of focus verschijnt er informatie. Het zou beter zijn om hier een knop van te maken, waarop geklikt kan worden om de informatie in- of uit te klappen. De status van de knop zou dan aangegeven kunnen worden met aria-expanded.

Zie bijvoorbeeld bij [stap 1](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/1) bij de checkbox “Gemeente of gemeenschappelijke regeling”.

## 4.1.3 Statusberichten

### Beslisboom

De voortgangsbalk die bij elke stap aangeeft bij welke stap je bent, is een statusbericht. Software moet kunnen bepalen dat dit statusbericht er is, zodat hulpsoftware hier de aandacht naar toe kan brengen. Hier zou role=”progressbar” gebruikt kunnen worden ([voorbeeld](https://www.w3.org/TR/wai-aria-1.2/#progressbar). Meerdere oplossingen zijn mogelijk. Dit komt bij meerdere stappen voor, zie bijvoorbeeld [stap 4](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/4)).

In het formulier op pagina [stap 8](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/8) kan een foutmelding verschijnen: “Het e-mailadres ... is ongeldig.”. Deze is opgemaakt met role=”alert”. Het element met role=”alert” is **niet aanwezig in de code** voordat deze melding verschijnt. Dit kan problemen opleveren met het voorlezen van deze melding. In de browser Chrome wordt deze wel voorgelezen, maar in Firefox niet (met de voorleessoftware NVDA). Dit zou mogelijk opgelost kunnen worden door gebruik van deze techniek: https://www.w3.org/WAI/WCAG21/Techniques/aria/ARIA19.

Er is ook een verborgen Engelse foutmelding die opgemaakt is met aria-live=”polite”. Deze wordt wel voorgelezen, maar kan moeilijk te begrijpen zijn omdat dit Engels is dat op een Nederlandse manier wordt voorgelezen door de screenreader.

WN - er komen op meer plaatsen engelse teksten terug op deze nederlandse website, beter is het om ze allemaal te vertalen naar het nederlands.

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

## 2.5.3 Label in naam

Links boven aan de pagina staat het broodkruimelpad. Hierin staat de link “Forum Standaardisatie”. Deze link heeft een aria-label met de waarde “Back to homepage”. Dit overschrijft de originele linktekst. Hierdoor bevat de naam van de link de zichtbare tekst niet.
https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden
