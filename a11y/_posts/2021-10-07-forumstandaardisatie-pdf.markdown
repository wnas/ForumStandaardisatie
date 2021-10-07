---
layout: post
title:  "Forum standaardisatie - PDF"
date:   2021-10-07 09:24:14 +0200
categories: forumstandaardisatie pdf
---

# 1.3.1 info en relaties

In het PDF-bestand op pagina https://prod-dictu.forumstandaardisatie.nl/sites/ default/files/2019-11/FS-191009.1A-Agenda-Forum-Standaardisatie-9-oktober-2019.pdf staan verschillende fouten in de gebruikte tags. De teksten ‘Agenda’ en ‘FORUM STANDAARDISATIEWOENSDAG 9 OKTOBER 2019’ zijn visueel opgemaakt als koppen. Deze teksten moeten in de code ook opgemaakt worden als koptekst. Veel van de overige content is visueel opgedeeld in tabellen, met content verdeeld over verschillende regels. In de code bestaat deze content echter uit p-elementen. Dit is op zich geen groot probleem. Het probleem is dat elke tabelcel maximaal bestaat uit één p-element. De visuele scheiding van content door op een nieuwe regel verder te gaan en de lay-out (die veel weg heeft van een lijst) gaan hiermee in de tags van de PDF helemaal verloren. Een voorbeeld: de informatie uit de laatste tabelcel onder de kop ‘2.Standaardisatie-agenda’ wordt voor hulpsoftware gepresenteerd als één aaneengesloten tekst. De hele visuele indeling met twee tekstblokken en de verschillende gecodeerde agendapunten gaat verloren. Wanneer hier een tabel gebruikt wordt met drie tabelcellen en in de verschillende tabelcellen meerdere p- elementen, gaat deze informatie uit de presentatie niet verloren.

De volgende PDF heeft geen tags en daardoor is voor hulpsoftware (zoals voorleessoftware) geen informatie beschikbaar om de PDF te interpreteren. Omdat tags ontbreken, kan de PDF niet volledig onderzocht worden (alle succescriteria met betrekking tot de PDF-codelaag, zoals semantische koppen en alt teksten bij afbeeldingen. Let daarom op dat bij het oplossen van dit probleem nieuwe toegankelijkheidsproblemen kunnen ontstaan. https://prod-dictu.forumstandaardisatie.nl/sites/default/files/bestanden/website/ FS-191009.3A2-Sheet-FS-als-Autoriteit%2C-Kennisinstituut-en-Netwerkorganisatie.pdf

# 2.4.2 Paginatitel

Het PDF-bestand op pagina https://prod-dictu.forumstandaardisatie.nl/sites/default/ files/2019-11/FS-191009.1A-Agenda-Forum-Standaardisatie-9-oktober-2019.pdf heeft de paginatitel ‘Agenda Forum Standaardisatie’. Deze titel is niet voldoende onderscheidend om aan te geven om welke agenda het gaat.

Het PDF-bestand op pagina https://prod-dictu.forumstandaardisatie.nl/sites/default/ files/bestanden/website/FS-191009.3A2-Sheet-FS-als-Autoriteit%2C-Kennisinstituut-en- Netwerkorganisatie.pdf heeft de titel ‘Microsoft PowerPoint – Presentatie1’. Deze titel is ook onvoldoende beschrijvend. De titel van een PDF is onderdeel van de documenteigenschappen van het bestand en daardoor onafhankelijk van de bestandsnaam.