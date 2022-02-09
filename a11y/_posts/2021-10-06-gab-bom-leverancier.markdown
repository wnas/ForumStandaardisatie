---
layout: post
title:  "Bom - acties leverancier"
date:   2021-1-17 10:25:14 +0200
categories: bom leverancier
---
Uit het rapport van Cardan kwamen een aantal zaken die de leverancier moet oppakken. Deze zijn als volgt

# Nog op te lossen

wordt aangepakt voor einde februari van 2022.


## 3.3.1 fout identificatie

<!-- Wanneer op de [pagina](https://gab.pleio.nl/groups/view/3f6561dd-f895-4b2b-9570-b605194c1d5d/gedeelde-presentaties-en-verslagen/files) wordt geklikt op de knop “Log in om lid te worden” en vervolgens op de knop “Maak een account aan” opent een webformulier met diverse invoervelden. Wanneer je deze velden niet of niet correct invult komen er rode foutmeldingen bij de invoervelden te staan met de tekst “Dit veld is vereist”. Een goede foutmelding vertelt wat er fout is gegaan en in welk veld dit is. Een suggestie voor een foutmelding zou kunnen zijn “Het veld Voor- en achternaam is niet ingevuld”. Bij het E-mailadres is een bepaalde invoer vereist, wanneer dit veld nu niet correct wordt ingevuld komt de foutmelding “Voer een geldig e-mailadres in” bij het invoerveld te staan. Dit is een instructie en geen foutmelding. Een goede foutmelding zou zijn “U heeft geen geldig e-mailadres ingevuld”. -->

Als op pagina [event toevoegen](https://bom.pleio.nl/events/add) verplichte velden niet worden ingevuld, verschijnt de melding “Dit is verplicht”. Dit zijn geen foutmeldingen, maar instructies.

[issue 8281](https://gitlab.com/pleio/beheer/-/issues/8281)

## 3.3.2 labels of instructies

Op [deze pagina](https://bom.pleio.nl/groups/view/24a054f2-3ad0-44d4-a02f-253dc91def98/betrouwbare-overheidsmail) staat een veld met daarin de placeholdertekst “Deel een update”. Dit veld heeft geen visueel label. De placeholdertekst verdwijnt tijdens het typen. Dan is er geen visueel label meer aanwezig voor dit veld.

[issue 8282](https://gitlab.com/pleio/beheer/-/issues/8282)

## 4.1.2 naam, rol, waarde

Op de onderzochte pagina's staat een zoekveld. Deze kan worden opengeklapt door op de knop van de loep te klikken. Dit zoekveld heeft geen naam. Er is wel een verborgen label aanwezig (“Zoek”), maar deze is niet aan het veld gekoppeld.

[issue 8850](https://gitlab.com/pleio/beheer/-/issues/8850)

# Opgelost


## 1.1.1 niet tekstuele content en 4.1.2 naam, rol, waarde

Op [deze](https://bom.pleio.nl/groups/view/24a054f2-3ad0-44d4-a02f- 253dc91def98/betrouwbare-overheidsmail) pagina staat (als er is ingelogd) een blok met de tekst “Achter het tabblad Agenda staan ...”. Rechtsboven de tekst staat een knop met een kruisje. Dit symbool heeft geen alternatieve tekst.

[issue](https://gitlab.com/pleio/beheer/-/issues/8197)

## 1.3.1 info en relaties

Op [deze pagina](https://bom.pleio.nl/news/view/1eac60a3-44e3-4049-b53d- 670a04161f16/overheid-uiterlijk-eind-2021-bereikbaar-via-ipv6)  staat onder de koptekst “Overheid uiterlijk eind 2021 bereikbaar via IPv6” een alinea tekst waarbij incorrect gebruik is gemaakt van het strong-element. Dit element mag alleen gebruikt worden om de nadruk te leggen op enkele woorden in de tekst. Het element mag niet gebruikt worden om een hele zin of alinea nadruk te geven.

<!-- 
## 1.4.3: Contrast (minimum) (Niveau AA)

Op pagina https://gab.pleio.nl/groups staan blokken met links naar groepen. Onder deze blokken staat grijze tekst die het aantal leden laat zien. Deze grijze tekst heeft te weinig contrast met de witte achtergrond. Gemeten is een contrastverhouding van 3,0:1. -->


## 2.4.4 linkdoel en 2.5.3 label in naam

In het hoofdmenu dat terugkeert op alle pagina’s van het domein gab.pleio staat de link “Home”. Deze heeft met het aria-label de naam “false” gekregen. Daarom is “false” nu de naam die door hulpsoftware wordt uitgesproken wanneer de toetsenbordfocus op deze link komt. Deze naam geeft niet duidelijk het doel van de link weer.
