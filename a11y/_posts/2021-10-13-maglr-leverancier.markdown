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

## 1.4.4 Herschalen van tekst

Op pagina [standaard samenwerken](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/cover) staat rechtsonder de knop “Naar overzicht” om terug te keren naar de homepage. Indien deze pagina herschaald wordt naar 200% zoom op de testresolutie 1024x768 is deze knop niet meer beschikbaar. Dit type probleem geldt ook voor de overige pagina's van de verschillende magazines zoals [meting informatieveiligheidstandaarden begin 2020](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/cover) en [digitale toegankelijkheid in de praktijk](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid).

## 1.4.5 Afbeeldingen van tekst

Op pagina [bevindingen](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/bevindingen) staat de knop “Lees verder” en de knop “Terug”. Dit zijn afbeeldingen van tekst.

## 1.4.10 Reflow

Bij succescriterium 1.4.4 is beschreven dat er verlies van content en/of functionaliteit is bij het inzoomen met 200% bij een resolutie van 1024x768 pixels. Dezelfde problemen treden ook op bij dit succescriterium, dat is getest bij een breedte van 320 pixels (of bij een breedte van 1280 pixels en 400% ingezoomd). Deze problemen zijn hier niet nogmaals beschreven, zie voor de beschrijving succescriterium 1.4.4. Bij het oplossen van deze problemen moet er dus op gelet worden dat dit ook gaat voldoen voor dit succescriterium. https://magazine.forumstandaardisatie.nl/

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

Op pagina [aanbestedingen](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/aanbestedingen) is de tekst in de legenda niet meer te lezen.

Op pagina [bevindingen](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/bevindingen) is een deel van de oranje kop niet meer te lezen, het gaat om de tekst “medio 2020”. Dit type probleem komt ook voor op andere pagina's zoals [adoptatie van de web standaarden](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/adoptie-van-de-webstandaarden) en [digitale toegankelijkheid](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid). 

Verdere voorbeelden van problemen die ontstaan als de gebruiker de tekstafstanden aanpast naar bovenstaande waarden worden niet gegeven.

## 2.1.1 Toetsenbord


Op pagina [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) is het niet mogelijk om de toetsenbordfocus op de bediening onderaan te zetten.

Op [alle pagina's](https://magazine.forumstandaardisatie.nl/) staat linksonder een link zonder href, doordat deze link ook niet werkt met de muis is dat niet fout onder de eisen van dit succescriterium. 

## 2.2.2 geen toetsenbordval

Op pagina [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) is een toetsenbordval aanwezig. Het is niet mogelijk om de bediening van de website via de knoppen rechtsonder te bereiken. De toetsenbordfocus zit vast in de inhoud van deze pagina.

## 2.1.4 enkel teken sneltoetsen

Op pagina [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) staat onder de kop “Informatiebeveiliging” een video die in beeld komt na het activeren van de knop “Bekijk de video over informatiebeveiliging”. Deze YouTube- video is te bedienen met enkel teken sneltoetsen zoals “k” en “f”. Deze bediening van YouTube-video’s voldoet niet aan de eisen van dit succescriterium. Voor de YouTube- videospeler is dit probleem op te lossen door de parameter `disablekb=1` te gebruiken. Op [deze pagina](https://developers.google.com/youtube/player_parameters#disablekb) staat meer informatie over hoe deze parameter werkt. Het gebruik van deze parameter heeft geen nadelige effecten voor andere succescriteria.

## 2.2.2 Pauzeren, stoppen, verbergen

Op pagina [uitleg](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/uitleg) beweegt de oranje knop “Open video”. Deze bewegende content voldoet niet aan de eisen van dit succescriterium. 

De bewegende content op pagina's [bevindingen](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/bevindingen) (Het vierkantje naast de tekst “De streefbeeldafspraken”), [digitale toegankelijkhei](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid) (De bewegende muis en de bewegende mobiel), [uitleg](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/uitleg) en [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) voldoen ook niet aan de eisen van dit succescriterium.

## 2.4.1 Blokken omzeilen

WN - skip navigatie

Er is geen mechanisme beschikbaar om blokken content die op meerdere webpagina's worden herhaald te omzeilen. In de meeste gevallen wordt hiervoor een skiplink gebruikt. Een dergelijke link staat aan het begin van de focus volgorde en hoeft alleen zichtbaar te zijn als deze toetsenbordfocus heeft. Bij activatie wordt de toetsenbordfocus dan verplaatst naar het begin van de unieke content op die pagina. Op die manier is het voor toetsenbordgebruikers mogelijk om de herhalende links aan het begin van de focus volgorde te omzeilen.
Dit probleem komt alleen voor op de pagina's die geen onderdeel zijn van een magazine zoals https://magazine.forumstandaardisatie.nl/, https://magazine.forumstandaardisatie.nl/?category=monitor_open_standaarden en https://magazine.forumstandaardisatie.nl/?category=speciale_uitgaven. Op de overige pagina's is het aanbieden van een methode om herhalende content te omzeilen niet nodig omdat er daar geen herhalende (focusbare) content voor de unieke content staat.

## 2.4.3 Focus volgorde

Op pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn) heeft de toetsenbordfocus een aparte volgorde. De toetsenbordfocus komt als eerste op de knop “Ga direct naar oprichting in 2006”. Daarna gaat deze naar het vijfde punt in de tijdlijn “2018 Wet digitale overheid”. Daarna komt de focus op het tweede bericht en daarna komt de toetsenbordfocus op de links van het derde bericht. Daarna gaat de focus naar de knop “blok02” bij de video “Veilige e-mailcoalitie Nederland”. De verschillende onderdelen van de tijdlijn hebben een verschillende verticale positie die informatie over de volgorde bevat. De relatieve positie waarin de verschillende links toetsenbordfocus krijgen bevat informatie deze afwijkende volgorde heeft invloed op de betekenis van de links. Hierboven is alleen het begin van de focus volgorde op deze pagina beschreven op deze pagina zijn meer problemen met de focus volgorde aanwezig. Soortgelijke problemen met de focus volgorde komen ook voor op pagina [digitale toegankelijkheid](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid). Het advies is om de focus volgorde en de visuele volgorde zoveel mogelijk overeen te laten komen.

Op pagina [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) opent de knop “Bekijk de video over informatiebeveiliging” een pop-up die de onderliggende pagina verbergt. Dergelijke vensters worden lightboxen genoemd (De term modal wordt ook gebruikt). Bij het openklappen van een lightbox gelden aanvullende eisen voor de focus volgorde. De toetsenbordfocus mag niet (zoals nu wel kan) op de onderliggende pagina komen zolang de lightbox open staat. Hiernaast moet bij het annuleren of sluiten van een lightbox de toetsenbordfocus op een logische plaats landen. In dit geval is dat terug op de knop die deze lightbox ook activeerde. Op die manier kan een gebruiker na het sluiten gewoon verder navigeren op deze pagina. Dit type probleem geldt ook voor de lightboxen op andere pagina's zoals die op [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn) en [uitleg](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/uitleg).

Op pagina [bevindingen](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/bevindingen) komt de toetsenbordfocus na het sluiten van “De streefbeeldafspraken” niet terug op de knop “De streefbeeldafspraken” die deze lightbox ook activeerde. Deze content telt als lightbox door het gebruikte gedrag van de toetsenbordfocus als de betreffende tabel in beeld staat. Als deze content niet als lightbox geïnterpreteerd zou worden is er een tweede probleem met succescriterium 2.1.2: Toetsenbordval.

## 2.4.4 linkdoel

Op [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) staan naast de kop “Informatiebeveiliging” meerdere links. Het gaat om de link in html en om de WAI-ARIA links. Deze links verwijzen naar nos.nl. Hulpsoftware is niet in staat om dat doel te bepalen. Deze links hebben geen namen die beschikbaar zijn voor hulpsoftware.

Links kunnen maar op enkele manieren context krijgen met andere content. Een link die onder een kop of tekst staat heeft niet automatisch context met die bovenstaande content. Op pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn) veroorzaakt dit veel problemen. Bijvoorbeeld de links “Best practices” en “New image (copy)” hebben geen context met elkaar en geen context met de bovenstaande en onderstaande content. Dit geldt dus ook voor de link “New image (copy2)”. Het linkdoel van de link “Webinar Digitoegankelijkheid: 'Zijn wij er als overheid klaar voor?'” is dan weer wel te bepalen. Twee van de vier links onder “Alle overheidswebsites verplicht toegankelijk” voldoen dus wel, maar de links “New image (copy)” en “New image (Copy) (copy)” voldoen niet. Het linkdoel van een link als “Bekijk nieuwsartikel” is bijvoorbeeld ook niet te bepalen, omdat niet duidelijk is om welk nieuwsartikel het gaat. “op Rijksoverheid.nl” en “op officiëlebekendmakingen.nl” voldoen samen met “New image” en “New image (Copy)” ook niet. Verdere voorbeelden op deze pagina worden niet gegeven.

Op pagina [afsluiting](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/afsluiting1) staan onder de kop “Hulp nodig of meer informatie?” vier afbeeldingen van tekst die ook als link naar de homepage werken. Het linkdoel van deze links is voor alle gebruikers onduidelijk en daarom niet fout onder dit succescriterium. Het advies is om dit wel te verbeteren.

## 2.4.7 focus zichtbaar

Door het vreemde gedrag van de toetsenbordfocus volgorde op pagina
[waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) komt de toetsenbordfocus op onderdelen te staan die buiten beeld staan. Die onderdelen zijn niet in beeld te zetten door op de normale manier verticaal te scrollen. Om die onderdelen moet de knoppen met de pijlen omlaag en omhoog gebruikt worden. De toetsenbordfocus kan hierdoor op elementen komen die niet in beeld te zetten zijn zonder de toetsenbordfocus weer van deze onderdelen af te halen. Het mag dus noodzakelijk zijn om verticaal te scrollen om het onderdeel waar de toetsenbordfocus op staat te vinden, maar door de scrollbaarheid van de pagina aan te passen werkt die zoektechniek niet zoals verwacht mag worden.

Op pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn) is de locatie van de toetsenbordfocus meerdere keren niet zichtbaar. De positie van de toetsenbordfocus is te bepalen als deze op de knop “Ga direct naar oprichting in 2006” staat. Daarna is de positie van de focus twaalf keer niet te bepalen voordat deze op de knop “blok02” komt. Tussen de videoblokken is de focus twee keer niet zichtbaar en na het tweede videoblok is de toetsenbordfocus 21 keer niet te bepalen voordat deze op de knop “Vorige pagina” weer zichtbaar is.

Op [afsluiting](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/afsluiting1) komt de toetsenbordfocus als eerste op een link waarvan de naam “shutterstock_39757475...” met aria-hidden=”true” is verborgen voor hulpsoftware. De toetsenbordfocus op deze link is niet zichtbaar.

Op pagina [aanbestedingen](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/aanbestedingen) is een soortgelijk probleem aanwezig. Daar komt de toetsenbordfocus als eerste op de knop “Open video”, terwijl er op deze pagina geen video staat.

Op pagina [adoptie van de webstandaarden](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/adoptie-van-de-webstandaarden) staan in het staafdiagram vijf knoppen zonder naam aan het begin van de toetsenbord focus volgende. De toetsenbordfocus op deze knoppen is niet zichtbaar.

Op pagina [digitale toegankelijkheid](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid) komt de toetsenbordfocus onzichtbaar op de links “praktijkcases digitaal toegankelijk publiceren” en “Pleio community website voor digitale toegankelijkheid”.

## 2.5.2 Aanwijzerannulering

Op pagina [tijdlijn](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/tijdlijn) heeft de knop “blok02” en de knop “blok04” geen aanwijzerannulering bij het aanklikken van de tekst onder het screenshot van de video. Na het aanklikken (down-event) is het niet meer mogelijk om te voorkomen dat de video begint af te spelen.

## 2.5.3 label in naam

Op [bevindingen](https://magazine.forumstandaardisatie.nl/meting-informatieveiligheidstandaarden-begin-2020/bevindingen) staat een afbeelding die is opgemaakt als knop. Deze knop heeft geen naam en bevat de zichtbare tekst “Lees verder”. De naam van deze knop moet die tekst bevatten om te voldoen aan dit succescriterium. De alt van de img is niet geldig als naam omdat deze img geen afbeelding meer is voor hulpsoftware. De eigenschappen van de afbeelding zijn overschreven door WAI-ARIA te gebruiken. De knop met de tekst “Terug” heeft hetzelfde probleem. Dit type probleem komt meer voor bijvoorbeeld ook op pagina [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie.)

Op pagina [digitale toegankelijkheid](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid) is veelvuldig gebruik gemaakt van aria-label attributen om knoppen een andere naam te geven. De zichtbare tekst op de knop moet terugkomen in die waarden om te voldoen aan de eisen van dit succescriterium. Het gaat bijvoorbeeld om de “Lees meer” knop onder de kop “Één op de vijf” met het aria-label “Open popup één op de vijf”. Een suggestie is om een aria-label in de vorm “Lees meer over ...” te gebruiken. In dit voorbeeld wordt het label dan “Lees meer over één op de vijf”. Let op dit geldt ook voor de verschillende “Lees meer” links op deze pagina.

## 3.3.1 Bij focus

Op pagina [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) is wordt de toetsenbordfocus verplaatst als deze op de bediening onderaan komt. Dit gedrag zorgt ervoor dat niet alle onderdelen op deze pagina bedienbaar zijn met het toetsenbord en zorgt er ook voor dat er een toetsenbordval aanwezig is op deze pagina. Als de toetsenbordfocus op de knop “Vorige pagina” komt te staan wordt deze automatisch verplaatst naar een ander element. Dit verplaatsen van de toetsenbordfocus geldt als contextwijziging en is onder de eisen van dit succescriterium niet toegestaan.

## 4.1.1 parsen

Op [pagina](https://magazine.forumstandaardisatie.nl/) staan drie knoppen met daarin een div-element. Het is niet toegestaan om een div-element te nesten in een openstaande button-element, het gebruik van bijvoorbeeld span is hier wel toegestaan. Dit type probleem komt voor op alle pagina's van de steekproef.

Op pagina [afsluiting](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/afsluiting1) staan twee koppen met daarin een p-element genest. Het nesten van een p-element in een koptekst zoals h1 of h2 is niet toegestaan. Dit type probleem komt ook voor op pagina's zoals [aanbestedingen](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/aanbestedingen) en [digitale toegankelijkheid](https://magazine.forumstandaardisatie.nl/digitale-toegankelijkheid-in-de-praktijk/digitale-toegankelijkheid). Dit zijn enkel voorbeelden dit komt meer voor.

Op pagina [monitor open standaarden 2019](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/) uitleg staan drie WAI-ARIA knoppen (role=”button”). Het is niet toegestaan om knoppen te nesten binnen knoppen. De html button-elementen zijn door dit verkeerd gebruik van WAI- ARIA rollen niet goed genest.

WN - valideer je code als onderdeel van je bouwprocess.

## 4.1.2 Naam, rol, waarde

Op [standaard samenwerken](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/cover) staat linksonder een link met het logo Forum Standaardisatie en de naam “Bezoek website:”. Deze link heeft geen href en daardoor onder de eisen van dit succescriterium geen waarde. Dit type probleem komt ook op andere pagina's voor zoals [afsluiting](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/afsluiting1) en [monitor open standaarden](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/cover) .

Het volgende is niet fout, maar kan wel verbeterd worden:

Op pagina [magazine](https://magazine.forumstandaardisatie.nl/) is een WAI-ARIA tablist gebruikt die aan de eisen van dit succescriterium voldoet. Het probleem met deze component van de gebruikersinterface is dat hier niet de standaard bediening met het toetsenbord is gebruikt, dit maakt het gebruik van dit type element hier meer complex en niet consistent. Op pagina [tabpanel](https://www.w3.org/TR/wai-aria-practices-1.2/#tabpanel) staat onder de kop “Keyboard Interaction” meer informatie over hoe deze bediening zou moeten werken om goed toegankelijk te zijn. Voor de duidelijkheid: dit aanpassen is niet verplicht, het gaat hier om een suggestie om de bediening te verbeteren voor gebruikers die naast hulpsoftware (zoals een screenreader) ook afhankelijk zijn van het gebruik van het toetsenbord. Hierbij is het advies ook om het menu rechtsonder op pagina's zoals [standaard samenwerken](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/cover) op een soortgelijke manier vorm te geven zodat de bediening consistent is over alle pagina's, let daar wel op met de extra knop “Naar overzicht”.

Op pagina [standaard samenwerken](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/cover) staat de knop “Open pagina navigatie” midden onderaan. Op het moment dat de aanvullende content in beeld komt als de muis op deze knop staat wordt de toestand (aria-expanded) niet aangepast naar “true”. Het advies is om de twee verschillende overzichten samen te voegen tot één variant. Dit type probleem komt op meerdere pagina's voor. Dit succescriterium geldt voor alle componenten van de gebruikersinterface en dus ook voor onderdelen die alleen werken voor muisgebruikers.

Op pagina [waarom standaardisatie](https://magazine.forumstandaardisatie.nl/standaard-samenwerken/waarom-standaardisatie) staan knoppen die aanvullende content in beeld zetten na activatie. Deze knoppen hebben een toestand zoals aria-expanded nodig die aangeeft of een knop op dit moment actief is of niet. Het gaat om de knoppen onder de kop “Waarom standaardisatie”. De knop “Bekijk de video over informatiebeveiliging” zet een lightbox in beeld als deze wordt geactiveerd. Doordat deze knop niet beschikbaar is als de video actief is is het instellen van twee verschillende toestanden niet noodzakelijk. Het aankondigen dat deze knop een lightbox in beeld zet is wel een eigenschap die gegeven moet worden. Dit kan door aria-hashpopup=”dialog” te gebruiken. Andere oplossingen voor deze problemen zijn mogelijk, er kan bijvoorbeeld ook gebruik gemaakt worden van een visueel verborgen teksten om deze toestanden en eigenschap aan hulpsoftware te presenteren. Deze typen problemen komen ook voor op pagina [uitleg](https://magazine.forumstandaardisatie.nl/monitor-open-standaarden-2019/uitleg).

## 4.1.3 status berichten

Op alle pagina's is de zoekfunctie te bereiken. Bij het uitvoeren van een zoekopdracht komt het aantal resultaten of de tekst “Geen resultaten gevonden” in beeld. Dit zijn beide statusberichten die iets zeggen over de uitkomst van de uitgevoerde zoekopdracht. Deze informatie moet gepresenteerd kunnen worden aan hulpsoftware. Deze informatie komt in beeld zonder dat de toetsenbordfocus verplaatst wordt. 

Er zijn verschillende opties mogelijk. Een hiervan is om de statusbericht-tekst een tabindex=”-1” te geven en na het zoeken de toetsenbordfocus op die tekst te zetten zodat die wordt gepresenteerd. 

Ook is het mogelijk om WAI-ARIA te gebruiken. Hier kan dan aria-live=”polite” of role=”status” gebruikt worden om het resultaat aan te geven let er wel op dat het element met dit attribuut in de DOM staat bij het laden van de pagina zodat hulpsoftware weet waar een statusbericht kan verschijnen. Op pagina's https://www.w3.org/WAI/WCAG21/Understanding/status-messages en https://www.w3.org/WAI/WCAG21/Techniques/failures/F103 staat meer informatie over hoe de techniek met focus verplaatsen moet werken en meer informatie over hoe WAI- ARIA gebruikt kan worden om dit op te lossen als de focus niet verplaatst wordt.