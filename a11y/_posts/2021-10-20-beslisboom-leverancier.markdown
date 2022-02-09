---
layout: post
title:  "Beslisboom - acties leverancier"
date:   2022-01-12 13:20:14 +0200
categories: beslisboom leverancier
---

# Leverancier

Bij deze punten is een actie van de leverancier nodig, code moet worden verbetert om deze punten op te lossen.

## toetser

Cardan technobility, Marijn Brilman en Gerard Copinga op 28 juni 2021.

## Op te lossen (dictu)

### 1.1.1 Niet tekstuele content

<!--Bovenaan de [pagina](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden) staat het logo van de Rijksoverheid. Deze afbeelding heeft een goede alternatieve tekst. Het div-element waar deze afbeelding in staat, is echter verborgen met aria-hidden=”true”. Hierdoor kan hulpsoftware deze informatie niet voorlezen. Een logo is informatief en heeft daarom een alternatieve tekst nodig. -->

In verschillende stappen van het proces staat er bij sommige opties een oranje symbool van de letter “i”. Dit symbool heeft geen alternatieve tekst. Er moet een alternatieve tekst komen die dezelfde informatie overbrengt als het symbool, bijvoorbeeld “Meer informatie”. Zie bijvoorbeeld bij [stap 1](https://www.forumstandaardisatie.nl/beslisboom/beslisboom- open-standaarden/step/1) bij de checkbox “Gemeente of gemeenschappelijke regeling”.

In [stap 8](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open- standaarden/step/8) kan er in het formulier de foutmelding “Het e-mailadres ... is ongeldig” verschijnen. Deze kan worden verborgen door op het kruisje te klikken. Dit is een knop met als naam “x”. Er moet een alternatieve tekst als “Sluiten” of iets dergelijks komen.

### 1.3.1 info en relaties

<!--Onderaan de [pagina](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden) staat boven de footer de tekst “Standaard Samenwerken”. Het div- element waar deze tekst in staat, is verborgen met aria-hidden=”true”. Hierdoor kan hulpsoftware deze informatie niet voorlezen.-->

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

### 1.4.4 Herschalen van tekst

In het proces van de beslisboom staan de stappen 1 tot en met 6 aangegeven boven de voortgangsbalk. De stappen die voltooid zijn werken als knoppen om terug te gaan naar die stap. Als er wordt ingezoomd met 200% bij een resolutie van 1024x768, is alleen de huidige stap te zien. Dit is een verlies van content en functionaliteit. Zie bijvoorbeeld [stap 6](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/6).

### 1.4.10 Reflow

In het proces van de beslisboom staan de stappen 1 tot en met 6 aangegeven boven de voortgangsbalk. De stappen die voltooid zijn werken als knoppen om terug te gaan naar die stap. Bij een breedte van 320 pixels is alleen de huidige stap te zien. Dit is een verlies van content en functionaliteit. Zie bijvoorbeeld [stap 6](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/6).

### 1.4.11 Contrast van niet tekstuele content

In verschillende stappen van het proces staat er bij sommige opties een symbool van de letter “i”. Dit oranje symbool op de grijze achtergrond heeft een contrast van 2,9:1. Dit is net te laag, het contrast moet minstens 3,0:1 zijn.
Zie bijvoorbeeld bij[stap 1])https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/1) bij de checkbox “Gemeente of gemeenschappelijke regeling”.

In [stap 8](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/8) staat er een formulier met twee velden. Deze velden hebben een grijze rand. Het contrast van het witte veld met de grijze rand is 1,5:1. Dit is te laag, dit moet minstens 3,0:1 zijn. Slechtzienden kunnen moeite hebben om de velden te onderscheiden.

### 1.4.13 Content bij hover of focus

In verschillende stappen van het proces staat er bij sommige opties een oranje symbool van de letter “i”. Als de toetsenbordfocus hier op staat of er wordt met de muis overheen gegaan (hover), dan verschijnt er meer informatie. Content die onder focus of hover verschijnt moet aan drie voorwaarden voldoen. Er wordt nu niet voldaan aan de voorwaarde “Sluiten”. De content die verschijnt kan over andere content heen vallen. De content moet dan gesloten kunnen worden zonder de focus of muis te verplaatsen. Dit is nu niet mogelijk. Dit moet bijvoorbeeld kunnen met de `Escape` toets.

Zie bijvoorbeeld bij [stap 1](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/2) bij de checkbox “Weet ik niet”.

### 2.4.3 focus volgorde

Bovenaan de pagina staat de knop “Menu”. Als hier op geklikt wordt, klapt het menu uit. Als er met het toetsenbord wordt genavigeerd, moet de toetsenbordfocus daarna naar de uitgeklapte content gaan. Nu gaat de toetsenbordfocus eerst naar de knop “Zoeken”, dat is niet logisch. https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/

### 2.4.4 Linkdoel

In [stap 7](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/7) wordt er een overzicht gegeven van standaarden die uit de beslisboom zijn gekomen. Onder elke standaard staat er een link “Leer meer”. Deze links hebben geen context met de bovenstaande paragraaf of kop. Een blinde kan een lijst met links maken of naar een link navigeren. Deze links zijn dan hetzelfde, het verschil is niet duidelijk. Er zijn meerdere oplossingen mogelijk. Er kan bijvoorbeeld een (verborgen) linktekst of een title-attribuut worden geplaatst met meer informatie.

Het zou ook beter zijn om deze content niet onder hover of focus te laten verschijnen, maar door er op te klikken.

WN - pas ook op met het openen van content in een nieuw venster, zie op deze [pagina meer informatie](https://webaim.org/techniques/hypertext/hypertext_links)
### 2.5.3 Label in naam

 Links boven aan de pagina staat het broodkruimelpad. Hierin staat de link “Forum Standaardisatie”. Deze link heeft een aria-label met de waarde “Back to homepage”. Dit overschrijft de originele linktekst. Hierdoor bevat de naam van de link de zichtbare tekst niet.
https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden 

### 4.1.2 Naam, rol, waarde

In verschillende stappen van het proces staat er bij sommige opties een oranje symbool van de letter “i”. Dit is een interactief item. Software kan de interactieve rol niet bepalen. Onder hover of focus verschijnt er informatie. Het zou beter zijn om hier een knop van te maken, waarop geklikt kan worden om de informatie in- of uit te klappen. De status van de knop zou dan aangegeven kunnen worden met aria-expanded.

Zie bijvoorbeeld bij [stap 1](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/1) bij de checkbox “Gemeente of gemeenschappelijke regeling”.

### 4.1.3 Statusberichten

De voortgangsbalk die bij elke stap aangeeft bij welke stap je bent, is een statusbericht. Software moet kunnen bepalen dat dit statusbericht er is, zodat hulpsoftware hier de aandacht naar toe kan brengen. Hier zou role=”progressbar” gebruikt kunnen worden ([voorbeeld](https://www.w3.org/TR/wai-aria-1.2/#progressbar). Meerdere oplossingen zijn mogelijk. Dit komt bij meerdere stappen voor, zie bijvoorbeeld [stap 4](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/4)).

In het formulier op pagina [stap 8](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/8) kan een foutmelding verschijnen: “Het e-mailadres ... is ongeldig.”. Deze is opgemaakt met role=”alert”. Het element met role=”alert” is **niet aanwezig in de code** voordat deze melding verschijnt. Dit kan problemen opleveren met het voorlezen van deze melding. In de browser Chrome wordt deze wel voorgelezen, maar in Firefox niet (met de voorleessoftware NVDA). Dit zou mogelijk opgelost kunnen worden door gebruik van deze techniek: https://www.w3.org/WAI/WCAG21/Techniques/aria/ARIA19.

Er is ook een verborgen Engelse foutmelding die opgemaakt is met aria-live=”polite”. Deze wordt wel voorgelezen, maar kan moeilijk te begrijpen zijn omdat dit Engels is dat op een Nederlandse manier wordt voorgelezen door de screenreader.

WN - er komen op meer plaatsen engelse teksten terug op deze nederlandse website, beter is het om ze allemaal te vertalen naar het nederlands.

## Opgelost (content)

### 1.3.1 info en relaties

Bij [stap 5](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/5) staat er in de uitgeklapte tekst van dit oranje symbool van de “i” (bij de checkbox “Beveiliging en privacy speelt een rol bij de nieuwe voorziening”) een lijst. Deze is in de code niet opgemaakt als lijst.

### 1.3.3: Zintuiglijke eigenschappen (Niveau A)

In [stap 7](https://www.forumstandaardisatie.nl/beslisboom/beslisboom-open-standaarden/step/7) staat onderaan de knop “Complete”. Op de pagina staat de tekst “Als u op de knop Volgende klikt, kunt u deze lijst naar uw e-mailadres toesturen.”. Er is geen knop met de tekst “Volgende”. Dit kan dus beter aangepast worden.
