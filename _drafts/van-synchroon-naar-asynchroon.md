---
title: "Van synchroon naar asynchroon"
author: EJD
layout: draft
date: 24-02-2015
---

* synchroon proces: gestuurd door een (gemeenschappelijke) klok
* voorbeelden:
    * verkeerslichtregeling (gestuurd door tijd, niet door aanbod van verkeer)
    * klassieke lopende band (de band is eigenlijk de klok)
    * school (dagelijks rooster, schoolbel; jaarlijks rooster)
* asynchroon proces: gestuurd door interactie van processen


### Wanneer synchroon?

* een synchrone aanpak is eenvoudig: in plaats van een interactie tussen de verschillende deelprocessen, heb je alleen te maken met een interactie tussen de deelprocessen en de klok.
    * een centrale klok is vaak eenvoudig te realiseren
* een synchrone aanpak is goed te gebruiken als de verschillende deelprocessen weinig variatie vertonen, en goed voorspelbaar zijn.

Als een deelproces te vroeg klaar is (ten opzichte van de deadline van de klok) dan levert dat enig verlies op (leegloop). Maar als een deelproces teveel tijd neemt, dan wordt de deadline van de klok niet gehaald: dit levert grote problemen op bij de vervolgprocessen.


### Waarom asynchroon?

* als de verschillende processen sterk variëren, dan moet je in een synchrone benadering een "worst case" benadering hanteren, waardoor er veel verlies (speling) ontstaat.
    * als de deelprocessen voorspelbaar/reproduceerbaar zijn, met weinig variatie, dan kun je een synchrone aanpak gebruiken.
    * de variatie in de deelprocessen wordt steeds groter: een synchrone benadering begint steeds meer te knellen.
    
* vgl voorbeelden:
    * verkeerlichtregeling: bepaald door aanbod van verkeer;
    * mogelijk door het gebruik van sensoren (en door meer flexibele besturing)
    

    
### Wat betekent de synchrone aanpak op school?

* de lessen duren allemaal even lang. De duur van een les wordt bepaald door het rooster, niet door de behoefte van de leerling of van het leerproces. Bij taalonderwijs is het wellicht handiger om elke dag les te hebben, maar dan eventueel korter. Bij praktisch werken wil je langere aaneengesloten periodes, enz.
* het tempo is voor alle leerlingen gelijk. Het rooster is als een voortdenderende trein. Als een leerling tijdelijk een probleem heeft, dan mist deze de trein (de boot). Als je zoveel speling in het rooster hebt dat je dit op kunt vangen, dan verspil je weer veel tijd voor de leerlingen die wel kunnen bijblijven.
    * leerlingen die sneller zijn dan de klok (het rooster) hebben last van "leegloop";
    * leerlingen die trager zijn dan de klok, hebben een serieus probleem (ook als dat eenmalig gebeurt, bijvoorbeeld door ziekte of een ander incident). 
    
De synchrone aanpak is gecombineerd met het uitdelen van cijfers: de test is op een vast verroosterd moment, en alleen de situatie op dat moment wordt gemeten. Daarna gaat het onderwijs verder met de impliciete aanname dat iedere leerling het materiaal voor de test beheerst.


