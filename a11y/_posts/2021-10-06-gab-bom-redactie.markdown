---
layout: post
title:  "Gab en Bom - acties redactie"
date:   2021-10-06 13:24:14 +0200
categories: gab bom redactie
---
Uit het rapport van Cardan kwamen een aantal zaken die Forum zelf moet oppakken. Deze zijn als volgt


# 1.3.1 info en relaties

Hieronder staat een lijst met links. Deze links kunnen in een (ongenummerde) lijst worden geplaatst.

Verder op deze pagina staat een genummerde lijst. Deze lijst is in de code echter niet als lijst opgemaakt, waardoor de relatie tussen deze lijst-onderdelen niet door hulpsoftware bepaald kan worden.

Op [nieuwe-harmonisatievoorstellen-geaccordeerd](https://gab.pleio.nl/news/view/1d567829-7206-4ab9-814c- b68413f9e5c9/nieuwe-harmonisatievoorstellen-geaccordeerd)  staan opsommingslijsten met schuin gedrukte teksten, die zijn opgemaakt met `<em>` elementen. Dit element is bedoeld om een deel van een tekst nadruk te geven. Teksten die zijn opgemaakt met het `<em>` element worden door hulpsoftware ook met nadruk voorgelezen en dat is hier niet gepast. Gebruik bij voorkeur CSS om de tekst anders weer te geven. Er zijn hier een aantal woorden die visueel onderstreept zijn. Dit zijn woorden die nadruk verdienen. Hier zou dus juist wel een em- of strong-element gebruikt kunnen worden. Hulpsoftware kan deze woorden dan nadruk geven bij het voorlezen. Zie bijvoorbeeld het woord “technische”.

Op dezelfde pagina staat een opsommingslijst die niet goed is genest. Visueel gezien springt punt 3a in naar rechts, maar in de code is nu niet duidelijk dat het vierde punt van boven punt 3a is en niet punt 4.

Op [pagina over afspraken](https://gab.pleio.nl/cms/view/20f32238-2aa1-409f-a855- bc0500b391a7/afspraken) staan onder de kop “GAB-werkgroep” een opsomming die niet als een opsommingslijst is opgemaakt. Dit geldt ook voor de opsommingen die daaronder staan. Voor het opmaken van een genummerde lijst moet het ol-element gebruikt worden.

WN - maak gebruik van een lijst element in de editor. ook andere elementen kunnen beter opgemaakt worden. Ik zal een sessie beleggen om betere pagina's te bouwen met Pleio.

## verbeteringspunt

Het volgende is niet fout maar kan wel verbeterd worden. Op pagina
https://gab.pleio.nl/news/view/1d567829-7206-4ab9-814c-b68413f9e5c9/nieuwe- harmonisatievoorstellen-geaccordeerd staan teksten die onderstreept zijn. Het is best practice om onderstreepte tekst alleen te gebruiken voor links. Een onderstreepte tekst die geen link is, kan verwarrend werken voor bezoekers van de website.

WN - zorg ervoor dat je je gebruikers niet in verwarring brengt.

# 1.4.3: Contrast (minimum) (Niveau AA)

Op pagina https://bom.pleio.nl/groups/view/24a054f2-3ad0-44d4-a02f- 253dc91def98/betrouwbare-overheidsmail heeft het actieve menu-onderdeel (“Overzicht”) een oranje kleur. De contrastverhouding van de oranje tekst ten opzichte van de witte achtergrond is 3,3:1, dit is te laag en moet minimaal 4,5:1 zijn. Gebruikers met visuele beperkingen kunnen problemen ervaren met het lezen van de tekst wanneer de contrastverhouding te laag is. Deze kleurencombinatie komt vaker voor op de pagina, zoals bijvoorbeeld onder de koptekst “Agenda” aan de rechterzijde van de pagina. Ook op andere pagina’s komt deze kleurencombinatie voor, zoals bijvoorbeeld op pagina https://bom.pleio.nl/news/view/b2f38cfe-6fa1-4975-b6a9-f6874976a396/overheden- moeten-starttls-en-dane-en-strikte-instellingen-voor-dmarc-en-spf-implementeren-voor- eind-2019 bij de links op deze pagina.

WN - Kleur kan in de admin worden aangepast