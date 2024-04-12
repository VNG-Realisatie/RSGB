---
layout: page-with-side-nav
title: Introductie Informatiemodel Basis- en Kerngegevens (RSGB)
---

# Introductie

De gemeentelijke gegevenshuishouding omvat een diversiteit aan objecten, gegevens daarvan en relaties daartussen. In de praktijk mondt dit uit in een groot 
aantal eilanden met eigen specificaties die uitwisseling, koppeling, meervoudig en ‘gemeentebreed’ gebruik van gegevens belemmeren. Eenduidigheid is daarom 
dringend gewenst. De kern hiervan wordt gevormd door de landelijke basisgegevens en de gemeentelijke kerngegevens. Het Referentiemodel Stelsel van 
Gemeentelijke Basisgegevens (RSGB) specificeert het informatie- of gegevensmodel van deze basis- en kerngegevens. Het RSGB wil eraan bijdragen dat gemeenten 
en daarmee samenwerkende organisaties de kern van hun gegevenshuishouding, de basis- en kerngegevens, eenmalig onderhouden en meervoudig gebruiken.

Het referentiemodel is een vertaling en een uitbreiding van het landelijk stelsel van basisregistraties met het oog op de gemeentelijke informatiebehoefte. 
Daarin is nadrukkelijk behoefte aan samenhang tussen de objecten en gegevens uit die basisregistraties èn behoefte aan specifieke gemeentelijke kerngegevens. 
Het RSGB is dan ook meer dan de optelsom van de landelijke basisregistraties. Op onderdelen verschilt het dan ook van het landelijk stelsel. Wel zijn de 
landelijke basisregistraties bijna volledig opgenomen in het referentiemodel.

<!-- De meest actuele versie van het RSGB is versie 2.1 ('in gebruik'). Deze is echter niet beschikbaar als PDF en is ook niet geïmplementeerd in StUF-BG. Lijkt me goed om daar geen aandacht meer aan te besteden. -->
De actuele versie van het RSGB is versie 2.02 ('in gebruik'). Dat is ook de versie die is geïmplementeerd in [StUF-BG 3.10](https://vng-realisatie.github.io/StUF-BG/). 
Het RSGB is één van de Informatiemodellen van de Gegevens- en berichtenarchitectuur.

## Totstandkoming RSGB
De invoering van een stelsel van basisregistraties bij de gehele overheid is zonder twijfel een van de meest ingrijpende ontwikkelingen waar gemeenten mee te 
maken hebben. Onder het motto ‘De overheid vraagt niet naar de bekende weg’, is wettelijk vastgelegd dat burgers en bedrijven basisgegevens nog maar éénmaal 
aan de overheid hoeven te verstrekken. Alle overheidsorganisaties zijn verplicht deze gegevens te gebruiken.

Voor gemeenten zijn de basisregistraties dáárom zo belangrijk, omdat zij niet alleen gebruiker ervan zijn, maar ook bronhouder van bijvoorbeeld de basisregistraties 
van Personen, Adressen en Gebouwen, WOZ-waarden Grootschalige topografie. De basisgegevens vormen nog maar het topje van de ijsberg van wat gemeenten aan gegevens 
nodig hebben om hun processen uit te voeren.

Om grip te krijgen op de meervoudig gebruikte gegevens, heeft een aantal Voorhoedegemeenten onder leiding van EGEM i-teams medio 2007 versie 1.0 uitgebracht van 
het RSGB. Dit model was de opvolger van het ‘oude’ GFO-Basisgegevens van de Vereniging Nederlandse Gemeenten (VNG). Voortschrijdend inzicht, de eerste ervaringen 
met het RSGB, ontwikkelingen in de (catalogi van de) landelijke basisregistraties en het ontwikkelen van de berichtenstandaard StUF-BG gaven aanleiding om in 
2009 versie 2.0 van het RSGB uit te brengen.

Versie 2.0 van het RSGB is gebaseerd op de volgende, al dan niet definitieve, versies van de catalogi en vergelijkbare beschrijvingen van basisregistraties:

* Catalogus BasisRegistratie Adressen (BRA versie 4.0; Vrom, 2-2006),
* Catalogus Basis Gebouwen Registratie (BGR versie 4.0; Vrom, 2-2006),
* Logisch Ontwerp GBA versie 3.6 (11-2007) en concept-versie 3.7 v.w.b. de relatie GBA – BAG,
* Programma van eisen Handelsregister (HR; EZ, 6-2008 versie. 1.6) en de Gegevenscatalogus Nieuw HandelsRegister (concept; VVKvK, 7-2008),
* Catalogus BasisRegistratie Kadaster (BRK; Kadaster, 3-2009 versie. 1.0.4),
* Catalogus Basisregistratie WOZ (BRWOZ; Waarderingskamer, 4-2008, versie 1.3)

en in aanvulling hierop het

* GFO Basisgegevens (VNG, 1998).

De basisregistratie Topografie is niet in het referentiemodel opgenomen. We zijn uitgegaan van grootschalige geo-objecten, met andere woorden de toekomstige 
Basisregistratie Grootschalige Topografie. Daarvoor gebruikten we het document:

* Informatiemodel Geografie (concept IMGeo; Geonovum v/h Ravi, 3-2007 vs. 2.0).

## Berichtenarchitectuur
Het RSGB beschrijft de structuur en semantiek van (uit te wisselen) basis- en kerngegevens. Om deze gegevens daadwerkelijk uit te kunnen wisselen, zijn berichten nodig. 
Hiertoe is het RSGB uitgewerkt in de [berichtenstandaard Sectormodel Basisgegevens](https://vng-realisatie.github.io/StUF-BG/) (StUF-BG). Basis- en kerngegegevens zijn 
tevens opgenomen in enkele, [StUF-BG-gerelateerde, koppelvlakken](https://vng-realisatie.github.io/Standaarden/Basis-en-kerngegevens).
