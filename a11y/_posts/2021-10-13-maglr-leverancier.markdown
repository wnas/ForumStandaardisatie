---
layout: post
title:  "Maglr - acties leverancier"
date:   2021-10-13 11:20:14 +0200
categories: maglr leverancier
---
# Leverancier

Bij deze punten is een actie van de leverancier nodig, code moet worden verbetert om deze punten op te lossen.

## 1.1.1 niet-tekstuele content 

Op alle pagina's staat op een of meerdere plaatsen de banner rijksoverheid. In geen van de gevallen heeft dit logo een tekstalternatief. Dat logo geeft visueel aan dat het Forum Standaardisatie onderdeel is van de rijksoverheid en dat moet ook voor gebruikers die dit logo niet kunnen zien duidelijk worden.
[Magazine](https://magazine.forumstandaardisatie.nl/)

Het logo van Forum Standaardisatie linksboven heeft geen tekstalternatief. Twee van de knoppen rechtsboven (“share” en “search”) hebben goede Engelse tekstalternatieven. Gebruik Nederlandstalige tekstalternatieven op een Nederlandse pagina om het doel van deze knoppen goed over te brengen.
[Magazine](https://magazine.forumstandaardisatie.nl/)

Op [deze pagina](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/cover) staat linksonder het logo met het tekstalternatief “Bezoek website”. Dat is geen goed tekstalternatief voor het logo van Forum Standaardisatie. De bovenstaande suggestie om alleen Nederlandstalige tekstalternatieven te gebruiken geldt ook voor de icoontjes rechtsonder op deze pagina.

Op de [start pagina](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/cover) heeft de decoratieve achtergrondafbeelding onterecht het tekstalternatief “banner_van_utrecht_- _...” meegekregen.

Op [het voorwoord](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/voorwoord) staat de afbeelding “achtergrond.jpg”. Dat is geen geldig tekstalternatief voor de foto van “Larissa Zegveld”. De decoratieve afbeeldingen van aanhalingstekens op de achtergrond hebben onterecht het tekstalternatief “New image”.

Op pagina [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) staat aan het begin van de pagina de knop “New image”. Deze afspeelknop heeft een beter tekstalternatief nodig. Dit geldt ook voor de knop “New image” eronder. Op het volgende deelvenster staan nog acht afbeeldingen met ditzelfde tekstalternatief. “markiemark.png”, “nos.png” en dergelijke zijn geen tekstalternatieven, op een link kan het alt attribuut niet gebruikt worden om een tekstalternatief te geven. Deze img-elementen zijn geen afbeeldingen, maar links er is immers role=”link” gebruikt om de rol van deze elementen met WAI-ARIA aan te passen. Verdere voorbeelden van problemen met tekstalternatieven op deze pagina worden niet gegeven.

Op pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn) hebben de achtergrondafbeeldingen tekstalternatieven zoals “bg1” tot en met “bg5”. De afbeeldingen met het tekstalternatief “New image” of “New image (copy)” hebben allemaal geen goed tekstalternatief. Deze tekstalternatieven moeten allemaal aangepast worden tenzij het om afbeeldingen gaat die altijd zijn verborgen voor hulpsoftware. Tekstalternatieven in de vorm “linkicon_blue.svg” voldoen bijvoorbeeld ook niet. De afbeelding met het tekstalternatief “New image (Copy) (Copy) (Copy) (Copy) (Copy) (Copy)” onder de kop “2008 Rijksinstructie bij aanschaf ICT” voldoet ook niet. Dit logo van de Staatscourant heeft een goed tekstalternatief nodig. Dit zijn enkele voorbeelden van enkele van de problemen met tekstalternatieven op deze pagina.

Op pagina [monitor open standaarden 2019](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/cover) heeft de verkeerde afbeelding het tekstalternatief “Foto van Michiel Steltman” gekregen. De zichtbare afbeelding van de cover is opgemaakt als achtergrondafbeelding en de afbeelding met dit tekstalternatief is van de monitor van 2016.

Op pagina [aanbestedingen](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/aanbestedingen) staan drie schijfdiagrammen. Deze afbeeldingen hebben geen goed tekstalternatief voor de combinatie van tekst en afbeelding. Dit type probleem geldt ook voor het staafdiagram en de schijfdiagrammen op [adoptie van de webstandaarden](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/adoptie-van-de-webstandaarden). 

**Verdere voorbeelden van problemen met het laten negeren van decoratieve afbeeldingen en het aangeven van goede tekstalternatieven voor informatieve afbeeldingen worden niet gegeven. Dit overzicht bevat enkel voorbeelden en kan niet gebruikt worden als volledig overzicht.**

## 1.3.1 info en relaties

Op pagina [standaard samenwerken](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/cover) staat onderaan de tekst “1 / 8”. Deze tekst geeft aan welke van de pagina's op dit moment in beeld staat. Alleen deze notatie maakt die informatie niet goed duidelijk voor gebruikers van hulpsoftware. Er zijn verschillende manieren om dit op te lossen, een hiervan is om deze tekst te koppelen aan de knop “Open pagina navigatie”, maar het toevoegen van een visueel verborgen tekst is ook mogelijk. 

Op pagina [voorwoord](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/voorwoord) zijn de namen “Vorige pagina” en “Volgende bladzijde” niet consistent dit kan verwarring veroorzaken. Het advies is om die teksten consistent te maken en om dan “pagina” of “bladzijde” te gebruiken om de tekst “2 / 8” de juiste relatie met deze knoppen te geven. Dit type probleem komt ook op andere pagina's voor.

Op pagina [voorwoord](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/voorwoord) is de tekst “Open standaarden horen bij de digitale ambities van de overheid” opgemaakt als kop. Deze tekst heeft een relatie met de onderstaande content. Door van de oranje tekst een koptekst te maken zijn de twee blokken tekst eronder ook aan de quote gekoppeld, andere oplossingen zijn mogelijk. Soortgelijke problemen komen ook voor op andere pagina's zoals de teksten “Waarom standaardisatie” en “Standaard samenwerken” op [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie).

Op pagina [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) zijn onder “Standaard samenwerken” verschillende teksten visueel anders opgemaakt om nadruk aan te geven. Deze visuele informatie is niet aanwezig in de code. Door deze teksten op te maken met strong of em is het voor hulpsoftware mogelijk om deze teksten met nadruk te presenteren. De tekst “Platform Internetstandaarden” is dan weer onterecht opgemaakt met strong, dat element mag niet gebruikt worden om een hele tekst (kop) nadruk te geven is dit element geeft deze tekst geen relatie met de onderstaande tekst. Het advies daar is dus ook om de strong te vervangen door een koptekst (zoals h3 of h4).

Op pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn) heeft de tekst “Tijdlijn Forum Standaardisatie” geen relatie met de onderstaande content. Het gebruik van één kop, waarbinnen dan de tekst “Tijdlijn” nadruk heeft met strong en een br is gebruikt om twee regels te maken is een van de mogelijke oplossingen.
Alle jaartallen staan visueel boven de teksten die opgemaakt zouden moeten zijn als kopteksten zoals “2020” en “Digitoegankelijkheid”. Het is noodzakelijk dat alle onderdelen van elk van de tijdlijn punten die in één blok staan een relatie met elkaar krijgen en de onderdelen van elk van deze blokken moeten ook in een logische volgorde geplaatst worden. Zie [succescriterium 1.3.2](https://www.w3.org/TR/WCAG21/#meaningful-sequence): Betekenisvolle volgorde voor meer informatie. De informatie binnen de blokken is te koppelen op verschillende manieren het gebruik van een duidelijke kop als eerste punt gevolgd door de verschillende onderdelen zoals jaartal, afbeelding tekst en link (in die volgorde) is een manier om de relaties tussen deze onderdelen aan te geven. Indien afbeeldingen genegeerd worden door hulpsoftware, omdat deze decoratief zijn hoeven die afbeeldingen niet gekoppeld te zijn aan de kop of tekst waar zij bij horen. Op deze pagina geldt ook dat het gebruik van strong geen relatie geeft aan de onderstaande content en dat een hele tekst op kop niet nadruk mag hebben. Gebruikt bij voorkeur HTML met de juiste semantische betekenis of ander CSS om teksten anders te stylen.

Op pagina [afsluiting](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/afsluiting1) is de tekst “Hulp nodig of meer informatie?” volledig opgemaakt als kop van niveau 1 met nadruk door ook strong te gebruiken. Het gebruik van strong is hier een probleem. Dit geldt ook voor de kop “Neem contact op”. Dit onjuist gebruik van strong komt bijvoorbeeld ook voor op pagina [uitleg](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/uitleg) op de teksten in de drie uitklapbare knoppen onder de goed opgemaakte kop “Achtergrondinformatie”. Verdere voorbeelden van het onjuist gebruik van strong en het ontbreken van koppen worden niet gegeven.

Op pagina [aanbestedingen](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/aanbestedingen) staan een aantal schijfdiagrammen. De percentages in de tekstalternatieven hebben geen relatie met de bovenstaande kop en de percentages in witte tekst hebben ook geen relatie. Het advies is om de teksten bij de diagrammen te verbergen voor hulpsoftware en de tekstalternatieven zo aan te passen dat de bovenstaande koppen ook onderdeel zijn van die tekst. Op die manier staan er hier drie afbeeldingen met een tekstalternatief dat alle visuele informatie overbrengt aan hulpsoftware. Om zichtbare teksten te verbergen voor hulpsoftware kan het attribuut aria- hidden=”true” gebruikt worden. Op pagina [adoptie van webstandaarden](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/adoptie-van-de-webstandaarden) komen soortgelijke problemen voor.

Op pagina [digitale toegankelijkheid](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid) heeft de tekst “In de praktijk” geen relatie met de onderstaande kop.

## 1.3.2 Betekenisvolle volgorde

Op pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn) staan meerder fouten in de betekenisvolle volgorde. Het in de leesvolgorde eerste blok in de tijdlijn is het blok met de grote tekst “Wet digitale overheid” begint met het jaartal “2020” en de tekst “Wet digitale overheid”. Daarna komt de link “op Rijksoverheid.nl” en de link “New image” gevolgd door de tekst “Bekijk ontwerpwetgeving” en daarna komen de links “New image (Copy)” en “op officiëlebekendmakingen.nl” naar voren in de leesvolgorde die gebruikt wordt door hulpsoftware. Deze volgorde wijkt zo sterk af van de visuele volgorde dat dit aangepast moet worden. Ook niet nu niet duidelijk welke van de punten van 2020, 2019 en dergelijke eerder en later binnen dat jaar op de tijdlijn staan.

Op pagina [digitale toegankelijkheid](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid) zijn ook problemen met de leesvolgorde. De kop “Informeren Ondersteunen en handhaven” staat in de leesvolgorde op een totaal andere plaats dan die tekst in de visuele volgorde staat. Deze kop lijkt nu iets te zeggen over het tekstblok “Bied informatie aan ... HTML en PDF.” Deze tekst staat visueel halverwege de pagina naast een bewegende afbeelding onder de kop “Ondersteunen, Hoe pak je dit aan?”. Dit soort verschillen tussen de volgorde waarin content wordt gepresenteerd en de leesvolgorde die door software bepaald wordt heeft invloed op de betekenis.

## 1.4.1 Gebruik van kleur

Op pagina [aanbestedingen](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/aanbestedingen) is in de schijfdiagrammen kleur gebruikt om aan te geven welk punt van de legenda bij welk percentage hoort. Kleur is op dit moment het enige visuele middel om deze relatie te bepalen. Indien de verschillende kleuren onderling allemaal een contrast zouden hebben van 3,0:1 of meer dan zou contrast tellen als tweede visuele middel. Andere oplossingen zoals arceren en dergelijke zijn natuurlijk ook mogelijk. Een soortgelijk probleem komt ook voor op [de pagina adoptie van de webstandaarden](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/adoptie-van-de-webstandaarden).

## 1.4.3 Contrast (minimum)

Op pagina [magazine](https://magazine.forumstandaardisatie.nl/) staat aan de linkerzijde witte tekst op een blauwe achtergrond met een contrast van 3,9:1. De kop heeft daarmee voldoende contrast maar dat geldt niet voor de kleinere tekst eronder. Die tekst heeft een contrast van 4,5:1 of meer nodig. Aan de rechterzijde staat een uitklapbaar menu met de onderdelen “Informatie”, “Delen” en “Zoeken”. De kleinere witte teksten in die blokken hebben ook met 3,9:1 te weinig contrast. De oranje tekst op deze vensters heeft met een contrast van 2,0:1 ook te weinig contrast. Deze kleurcombinatie is op alle pagina's gebruikt.

Op pagina's zoals [standaard samenwerken](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/cover) komt onderaan een overzicht in beeld als de muis op de knop “1 / 8” staat. De nummers bij de verschillende afbeeldingen, de witte teksten en de oranje tekst hebben allemaal onvoldoende contrast. Dit type probleem komt terug op alle pagina's met een dergelijk overzicht onderaan. Deze pagina is enkel als voorbeeld gebruikt.

Op pagina [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) staat oranje tekst op een witte achtergrond met onvoldoende contrast (3,2:1). Het gaat onder andere om de oranje teksten onder de kop “Standaard samenwerken” en om de twee oranje teksten onder “Informatiebeveiliging”. Soortgelijke problemen zijn aanwezig op pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn). Daar is op meerdere plaatsen gebruik gemaakt van kleinere tekst in de kleurcombinatie wit-oranje met een contrast van 3,2:1.

Op pagina [afsluiting](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/afsluiting1) staan vier afbeeldingen van tekst met daarin witte tekst op een gekleurde achtergrond. Deze teksten hebben alle vier een contrast van minimaal 4,5:1 nodig. Op dit moment is het contrast van de tekst “Hoe werkt dit in een aanbesteding?” 3,2:1 en het contrast van de tekst “Moet ik me verantwoorden voor het gebruik van open standaarden?” is 1,8:1.

Op pagina [monitor open standaarden](https://magazine.forumstandaardisatie.nl/?category=monitor_open_standaarden) worden te teksten in de afbeeldingen gezien als screenshots van de verschillende coverpagina’s. Het contrast van die teksten hoeft zolang de zwarte tekst onder de afbeelding voldoet niet te voldoen.

Op pagina [monitor open standaarden 2019](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/) aanbestedingen staan er in het schijfdiagram verschillende teksten met onvoldoende contrast. Het gaat om de koppen boven de schijven (4,2:1) en om de percentages in de oranje schijven (3,2:1). Problemen met de kleurcombinatie wit/grijs-oranje en blauw-wit zijn ook op deze pagina aanwezig. Een soortgelijk geldt voor een deel van de witte percentages op pagina [adoptie van de webstandaarden 2020](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/adoptie-van-de-webstandaarden).

Op pagina [digitale toegankelijkheid](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid) hebben de kleinere oranje teksten met 3,2:1 onvoldoende contrast het gaat om de kleinere oranje links en knoppen op deze pagina zoals “Wet Digitale Overheid”, “Leg verantwoordelijkheden vast”, “Lees meer” en dergelijke.

WN - kijk op [deze pagina](https://contrast-ratio.com/) wat goede contrasten zijn...

## 1.4.4 Herschalen van tekst {#1.4.4}

Op pagina [standaard samenwerken](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/cover) staat rechtsonder de knop “Naar overzicht” om terug te keren naar de homepage. Indien deze pagina herschaald wordt naar 200% zoom op de testresolutie 1024x768 is deze knop niet meer beschikbaar. Dit type probleem geldt ook voor de overige pagina's van de verschillende magazines zoals [meting informatieveiligheidstandaarden begin 2020](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/cover) en [digitale toegankelijkheid in de praktijk](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid).

## 1.4.5 Afbeeldingen van tekst

Op pagina [bevindingen](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/bevindingen) staat de knop “Lees verder” en de knop “Terug”. Dit zijn afbeeldingen van tekst.

## 1.4.10 Reflow

Bij succescriterium 1.4.4 is beschreven dat er verlies van content en/of functionaliteit is bij het inzoomen met 200% bij een resolutie van 1024x768 pixels. Dezelfde problemen treden ook op bij dit succescriterium, dat is getest bij een breedte van 320 pixels (of bij een breedte van 1280 pixels en 400% ingezoomd). Deze problemen zijn hier niet nogmaals beschreven, zie voor de beschrijving succescriterium [1.4.4](1.4.4). Bij het oplossen van deze problemen moet er dus op gelet worden dat dit ook gaat voldoen voor dit succescriterium. https://magazine.forumstandaardisatie.nl/

Op pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn) is het jaartal bovenaan 2020, maar als deze pagina bekeken wordt op een weergave met 320 CSS-pixels is dat jaartal 2018. Ook vallen in deze weergave van de tijdlijn twee punten (“2020 Alle overheidswebsites verplicht toegankelijk” en “2019 Kamerbrief”) weg.

Het volgende is niet fout, maar kan wel verbeterd worden:
Op pagina https://magazine.forumstandaardisatie.nl/ staat een lijst met links. Bij een breedte van 320 CSS-pixels is het nodig om horizontaal te scrollen om al deze links te zien. Deze verschillende links kunnen zonder verlies van informatie of functionaliteit ook onder elkaar geplaatst worden. Dit is hier niet afgekeurd, omdat de individuele links een voor een helemaal in beeld kunnen komen. Deze situatie komt ook voor op de overige weergaven van de homepage zoals [monitor open standaarden](https://magazine.forumstandaardisatie.nl/?category=monitor_open_standaarden) en [speciale uitgaven](https://magazine.forumstandaardisatie.nl/?category=speciale_uitgaven).

## 1.4.11 Contrast van niet-tekstuele content

Op pagina [monitor open standaarden 2019](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/) aanbestedingen staan drie schijfdiagrammen. Het contrast tussen de verschillende kleuren en het contrast tussen de cirkel en de achtergrond moeten allemaal minimaal 3,0:1 of meer zijn om te voldoen. Dat laatste contrast is hier voldoende maar de contrasten tussen de drie kleuren zijn 1,7:1, 1,4:1 en 1,2:1. 

De cirkeldiagrammen op pagina [adoptie van de webstandaarden](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/adoptie-van-de-webstandaarden) moeten ook aan deze eisen gaan voldoen. Indien op een andere manier duidelijk wordt dat er begin 2020 een gemiddelde adoptie van de webstandaarden van 94% was geldt die tekst, tabel eventueel als alternatief voor die informatie in dit schijfdiagram. Er zijn voor de verschillende (contrast)problemen met deze diagrammen dus meerdere oplossingen waarbij weergave in tekst of tabel ook mogelijke oplossingen zijn.

## 1.4.12 Tekstafstand

WN - probeer alle pagina's te bekijken in firefox met de tekst zoom instelling aan en op meer dan 200%

Op pagina [waarom standaardistatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) vallen op het tweede venster van deze pagina teksten over elkaar heen als de bovenstaande afstanden van tekst worden ingesteld door de gebruiker. Een deel van de tekst van de eerste knop onder de kop “Waarom standaardisatie” valt over deze kop heen.

Het verticaal scrollen bij deze instelling is toegestaan, maar dat moet dan wel mogelijk zijn voor alle content de gedeeltelijk wegvalt. Op pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn) is niet alle content op deze manier te scrollen en sommige teksten vallen over elkaar heen. Bijvoorbeeld de tekst “Alle overheidswebsites verplicht toegankelijk” is niet meer goed zichtbaar. Bij de kop “Wet digitale overheid” is de kop niet goed zichtbaar en de zichtbare tekst van de eerste link is “op Rijksoverheid.nl” en bij de tweede link is alleen de tekst “de” beschikbaar.

Op pagina [monitor open standaarden 2019](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/cover) valt de tekst “Standaarden” achter de link om het rapport te downloaden. 

## 1.4.13 Content bij hover of focus

Op pagina's zoals [standaard samenwerken](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/cover) komt een overzicht van de verschillende pagina's van het magazine in beeld als de muis op de knop “1 / 8” midden onderaan komt te staan. Deze content komt in beeld op hover en moet aan de eisen van dit succescriterium voldoen. Op deze pagina is er geen probleem met dit mechanisme, maar op enkele andere pagina's wel.

Het gaat bijvoorbeeld om pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn). Op die pagina valt deze aanvullende content over informatie die in beeld staat heen, daardoor moet dit mechanisme daar ook voldoen aan de eis “Sluiten”. De bedoeling daarvan is dat als de aanvullende content onbedoeld in beeld komt deze te verbergen moet zijn zonder dat het noodzakelijk is om de muis of toetsenbordfocus te verplaatsen. Dat is in dit geval niet mogelijk. In de meeste gevallen wordt hiervoor de escape-toets gebruikt. Het indrukken van die toets heeft dan tot gevolg dat de aanvullende content weer verborgen wordt zodat de informatie op de achtergrond weer in beeld staat. 

Dit probleem komt ook voor op pagina's [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) (de knop “New image” wordt daar verborgen) en [digitale toegankelijkheid](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid).

Let op: op het moment dat deze balk wordt opengeklapt met het toetsenbord (via de knop “Open pagina navigatie”) in plaats van met de hover van de muis komt een alternatieve versie van deze content in beeld. Die pop-up is wel te “Sluiten” met de escape-toets.



Op pagina [meting informatiestandaarden begin 2020](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/cover) valt de koptekst over de link om de PDF te downloaden heen.

Op pagina https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/
aanbestedingen is de tekst in de legenda niet meer te lezen.
Op pagina https://magazine.forumstandaardisatie.nl/meting- informatieveiligheidstandaarden-begin-2020/bevindingen is een deel van de oranje kop niet meer te lezen, het gaat om de tekst “medio 2020”. Dit type probleem komt ook voor op andere pagina's zoals https://magazine.forumstandaardisatie.nl/meting- informatieveiligheidstandaarden-begin-2020/adoptie-van-de-webstandaarden en https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale- toegankelijkheid. Verdere voorbeelden van problemen die ontstaan als de gebruiker de tekstafstanden aanpast naar bovenstaande waarden worden niet gegeven.