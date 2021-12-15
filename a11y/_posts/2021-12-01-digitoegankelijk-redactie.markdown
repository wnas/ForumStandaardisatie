---
layout: post
title:  "digitaaltoegankelijk.pleio.nl - acties redactie"
date:   2021-12-01 11:20:14 +0200
categories: digitoegankelijk redactie
---
# Redactie 

Dit zijn de acties die de redactie zelf moet (laten) doen.

## opgelost

Issues die door de redacteur zijn opgelost naar aanleiding van [deze toets](https://toegankelijkheidsrapport.swink.nl/pleio-content/audit/issues/).

### 1.1.1 Niet-tekstuele content
Op elke pagina staat linksbovenin een icoon van een boek. Dit heeft nu alleen 'Home' als tekstalternatief. Dat lijkt voldoende, als dit slechts een decoratief icoon is. Mocht het gaan om een logo, dan moet dit ook duidelijk worden in het tekstalternatief. 

> We hebben het tekstalternatief van het icoon rechtsboven veranderd in "Site icoon met link naar homepage".

De afbeelding boven het artikel dat digitaaltoegankelijk.pleio.nl/blog/view/cdefe5c2-0f01-44dd-… in de zoekresultaten verschijnt op pagina digitaaltoegankelijk.pleio.nl/search/results, heeft geen alternatieve tekst. Dit geldt ook voor de afbeelding op digitaaltoegankelijk.pleio.nl/events/view/ff95daf9-d7d1-4dde-…, die in de zoekresultaten verschijnt.
Deze afbeeldingen lijken niet puur decoratief, en hebben dan wel een tekstalternatief nodig.

> De betreffende artikelen zijn verwijderd.


De afbeeldingen op pagina digitaaltoegankelijk.pleio.nl/groups/view/86895394-4aed-4a31-… hebben een alternatieve tekst, maar worden onder de afbeelding met precies dezelfde tekst beschreven. Dit maakt de alternatieve tekst overbodig en hinderlijk voor screenreadergebruikers, die de tekst twee keer te opgelezen krijgen.

> Het onderschrift van de figuren is verwijderd.

Op pagina digitaaltoegankelijk.pleio.nl/groups/view/86895394-4aed-4a31-… staat een afbeelding van een tabel (met smileys) die omschrijft wanneer je welk bestandsformaat gebruikt. Deze informatie staat niet uitgeschreven op de pagina. De alternatieve tekst 'Afbeelding van een tabel die documentformats afzet tegen overwegingen over de content' is daarmee niet voldoende beschrijvend. Zie ook 1.4.5.

> De afbeelding met de tabel is verwijderd en vervangen door tekst met een link waar dezelfde informatie in tekstuele vorm te vinden is.

### 1.2.2 Ondertitels voor doven en slechthorenden (vooraf opgenomen)

De video van webinar 'PDF en digitale toegankelijkheid' op pagina digitaaltoegankelijk.pleio.nl/news/view/308270ed-c744-4279-… heeft geen ondertiteling voor doven en slechthorenden.>

> De video zonder ondertiteling is verwijderd.

### 1.2.3 Audiodescriptie of media-alternatief (vooraf opgenomen)
Op pagina digitaaltoegankelijk.pleio.nl/news/view/308270ed-c744-4279-… staat een webinar. Voor alle belangrijke visuele informatie die niet terugkomt in het audiospoor moet een audiodescriptie of media-alternatief worden geboden.
Op pagina digitaaltoegankelijk.pleio.nl/groups/view/86895394-4aed-4a31-… staat de informatie uit de slides online, dus dit zou kunnen dienen als media-alternatief. Echter, omdat de eigenaar van de video alle bedieningsknoppen heeft uitgeschakeld, is niet goed te onderzoeken of er nog meer belangrijke visuele informatie in de presentatie voorkomt.
(Overigens kan door het uitschakelen van de bedieningsknoppen ook niet gepauzeerd of teruggespoeld worden, wat niet erg gebruiksvriendelijk is.)

> De video zonder ondertiteling is verwijderd.

### 1.2.5 Audiodescriptie (vooraf opgenomen)

Op pagina digitaaltoegankelijk.pleio.nl/news/view/308270ed-c744-4279-… staat een webinar. Voor alle belangrijke visuele informatie die niet terugkomt in het audiospoor, zoals de slides, moet een audiodescriptie worden geboden.
Omdat de eigenaar van de video alle bedieningsknoppen heeft uitgeschakeld, is niet goed te onderzoeken of er nog meer belangrijke visuele informatie in de presentatie voorkomt.

> De video zonder ondertiteling is verwijderd.

### 1.3.1 Info en relaties

Op pagina digitaaltoegankelijk.pleio.nl/news/view/308270ed-c744-4279-… staat een visuele kop 'Meer weten?', maar deze tekst is niet opgemaakt als kop. Gebruik een headingselement, zoals een h2 of h3, om dit probleem op te lossen.

> Deze 'nepkop' die niet als kop was opgemaakt, is verwijderd.
 
Bevinding 11: Op pagina digitaaltoegankelijk.pleio.nl/groups/view/86895394-4aed-4a31-… staan een aantal vetgedrukte teksten die nadruk geven, zoals 'als PDF bestand' en 'bewijst'. Deze moeten in de code een element meekrijgen dat die nadruk aangeeft, zoals het <strong> element.
Dit komt ook voor in de post van 6 november (de datum en tijd), te zien op pagina digitaaltoegankelijk.pleio.nl/groups/view/d582632b-ef12-41e2-… .

> We hebben de formatting van de vetgedrukte teksten verwijderd.

Bevinding 13: De PDF (digitaaltoegankelijk.pleio.nl/files/view/d093f170-0e2c-4734-…) heeft geen tags en daardoor is er voor hulpsoftware (zoals voorleessoftware) geen informatie beschikbaar om de PDF te interpreteren. Omdat tags ontbreken kan de PDF niet volledig onderzocht worden (alle succescriterium met betrekking tot de PDF codelaag zoals semantische koppen en alt teksten bij afbeeldingen). Let daarom op dat bij het oplossen van dit probleem nieuwe toegankelijkheidsproblemen kunnen ontstaan.

> We hebben het niet-getagde PDF bestand in kwestie verwijderd.

### 1.4.5 Afbeeldingen van tekst

Bevinding 21: Op pagina digitaaltoegankelijk.pleio.nl/groups/view/86895394-4aed-4a31-… staat een afbeelding van een tabel (met smileys) die omschrijft wanneer je welk bestandsformaat gebruikt. Dit is een afbeelding van tekst. De tekst kan nu niet aan de behoeften van slechtzienden worden aangepast. Het is beter de informatie gewoon als tabel op de pagina te plaatsen. Zie ook 1.1.1.

> De afbeelding met de tabel in kwestie is verwijderd en vervangen door een link naar een verklarend artikel. In het verklarende artikel "Welk document format moet ik gebruiken?" staat nog wel een aangepaste afbeelding van de tabel. Ik heb deze laten staan omdat we in Pleio geen tabellen kunnen invoegen op blog pagina's. Wel beschrijft de tekst van het artikel exact wat er in de tabel in de afbeelding te zien is. Dat wordt ook in de alternatieve tekst toegelicht. We willen de afbeelding met tabel graag handhaven omdat wij er veel positieve feedback over krijgen. Is dit acceptabel?

**Tabellen komen snel (december 2021) in pleio.**

### 2.4.2 Paginatitel

Bevinding 31: De titel van de pagina digitaaltoegankelijk.pleio.nl/ luidt 'Digitaal toegankelijk publiceren · Digitaal toegankelijk publiceren'. Deze titel kan duidelijker, door aan te geven dat dit de Homepage is. 

> We hebben de titel veranderd in "Welkom op de community website voor digitaal toegankelijk publiceren". Hiermee wordt het duidelijker dat het om een home page gaat.

Bevinding 32: De titel van de pdf digitaaltoegankelijk.pleio.nl/files/view/d093f170-0e2c-4734-… is niet ingesteld. Voeg een duidelijke titel toe om dit probleem op te lossen. Pas daarna aan dat niet de bestandsnaam maar de documenttitel getoond wordt, wanneer gebruikers het bestand openen.

> Wij hebben de betreffende PDF verwijderd.

### 2.4.4 Linkdoel
Bevinding 36: Op pagina digitaaltoegankelijk.pleio.nl/news/view/308270ed-c744-4279-… komt de linktekst 'Klik hier op de link' voor. Screenreadergebruikers kunnen een linklijst opvragen, waarin zij alle links van een pagina te zien krijgen. Deze tekst is te weinig beschrijvend en heeft daardoor geen duidelijk linkdoel. Zorg ervoor dat linkteksten beschrijven waar de link heengaat. Dit is een best practice. 

> We hebben de linktekst meer beschrijvend gemaakt.

Bevinding 37: Op pagina digitaaltoegankelijk.pleio.nl/events/view/31479e44-7a02-47dc-… staat een link naar www.ncdt.nl. De linktekst is 'Externe link'. Dit is onvoldoende beschrijvend.

> Dit leek nog een oud agenda item te zijn, dat nog volgens de oude CMS opmaak was gepubliceerd. We hebben dit agenda item verwijderd en een nieuw agenda item toegevoegd met dezelfde inhoud. Het probleem doet zich nu niet meer voor. De link naar https://ncdt.nl staat nu in de tekst zelf en niet meer onder de tekst 'Externe link'.

**Externe link is een overblijfsel van oude functionaliteit en is verwijderd, oude events kunnen deze nog bevatten. Dit om geen oude content te 'breken'.**

### 3.1.1 Taal van de pagina
Bevinding 44: De taal van de pdf digitaaltoegankelijk.pleio.nl/files/view/d093f170-0e2c-4734-… is niet ingesteld in de bestandseigenschappen.

> We hebben het PDF bestand in kwestie verwijderd.

### 3.1.2 Taal van onderdelen
Bevinding 45: Op pagina digitaaltoegankelijk.pleio.nl/search/results komt een nieuwsitem naar voren genaamd Toegankelijk op Gov.uk, waar de term 'Design of the Year' en een hele zin in het Engels staat. Hiervoor een taalwisseling in de code nodig. 

> We hebben het artikel in kwestie verwijderd, omdat dit ook al verouderd was.

Bevinding 46: Onderstaande bevinding is technisch van aard:
Op pagina digitaaltoegankelijk.pleio.nl/news/view/308270ed-c744-4279-… staat een videospeler, met daarin een button om de speler te openen op de hele pagina. De toegankelijke naam van die button is 'Enter full screen' (en vervolgens 'Exit full screen'). De knoppen Play, Share, Add to watch later en Like zijn ook in een andere taal dan de taal van de pagina.

> We hebben de video in kwestie verwijderd, omdat deze ook niet van ondertiteling voorzien was.

