---
Title: 01 Colors
Description: This is our report page.
Template: report
---

Designorienterad analys över bankers hemsidor
=======================

Rapporten analyserar 3 hemsidors laddningstider.

Urval
-----------------------
Jag har valt hemsidorna youtube.com, blocket.se, och jesper.nu.
Jag valde hemsidorna eftersom att de är tre väldigt olika hemsidor. Alla tre sidor laddar in mycket data och jag misstänker att det kan vara intressant att se hur mycket de skiljer sig åt eftersom att de alla bär olika syften och är skapade i olika skicklighetsnivåer.

Metod
-----------------------
Jag använder främst två verktyg för att utföra min analys. Google Pagespeed är ett verktyg utvecklat av google för att testa hemsidors prestanda i olika kategorier. Verktyget är mycket simpelt då man endast behöver mata in en länk till en hemsida och sedan utförs testerna. Jag använder mig även av devtools där man under 'network' fliken kan se statestik angående laddningstider mm.
Resultaten presenteras sedan i ett excel-ark som infogas i analysen.

Resultat
-----------------------
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRIt85dm3bQ1BiShpWQEi0CN5Zca-AlMUR3yPoN2q65Zuc9W_VmvPDS3xTEazCopMJBRWHymVnCw1bs/pubhtml?widget=true&amp;headers=false"></iframe>

<b>Youtube</b>
<picture>
    <source media="(max-width: 750px)" srcset="%base_url%/image//kmom05/youtubesnap.jpg">
    <img src="%base_url%/image//kmom05/youtubesnap.jpg" alt="En bil" class="galimg">
</picture>

Youtube är en extremt stor och välutvecklad hemsida. Det finns mycket data som ska läsas in, ca 16mb, och då krävs det att sidan är bra optimerad för att hålla nere laddningstiderna. Med tanke på den stora mängd data som laddas in jämfört med laddningstiden som ligger på runt 1.5s är sidan mycket bra optimerad.

<b>Blocket</b>
<picture>
    <source media="(max-width: 750px)" srcset="%base_url%/image//kmom05/blocketsnap.png">
    <img src="%base_url%/image//kmom05/blocketsnap.png" alt="En bil" class="galimg">
</picture>

Blocket är även en hemsida om tillhör ett stort företag men det behöver inte betyda att hemsidan är bra optimerad. Jag mäter landningssidan där det inte laddas in en enorm mängd data i form av annonser men får även där ingen jättebra prestanda. Hur kan detta förbättras? Enligt PageSpeed bör man reducera JavaScript som inte används vilket hade gjort enorma besparingar på sidans laddningstider.

<b>Jesper.nu</b>
<picture>
    <source media="(max-width: 750px)" srcset="%base_url%/image//kmom05/jespersnap.png">
    <img src="%base_url%/image//kmom05/jespersnap.png" alt="En bil" class="galimg">
</picture>

Jesper.nu är en spelhemsida som vid detta laget är mycket gammal och utdaterad. Trots detta har sidan en väldigt bra optimerad sida. Sidan är mycket enkelt uppbyggd och har inte någon enorm data som ska laddas in. Även här tycker PageSpeed att man bör reducera JavaScript som inte används.

Analys
-----------------------
Jag blev lite chockad över att Jesper.nu hade den absolut bästa laddningstiden utav alla sidorna eftersom att den är äldst, men det kanske jag inte borde vara. Även om både Youtube och Blocket har stora team som konstant utvecklar och uppdaterar deras hemsidor så har de mycket mer som ska göras på hemsidan, ladda in tusentals av annonser, bilder och videor, vilket är mycket krävande. 
När jag kollade på hur hemsidorna skulle kunna förbättras så upptäckte jag att det nästan alltid var en faktor som saktade ner hemsidorna allra mest, oanvänd JavaScript-kod. Skulle man recudera denna så hade sidorna med stor sannolikehet kommit ännu högre upp i rankningarna.
Enligt mig bör en sida laddas inom 2s för att anses som snabb, längre än så kan man ibland börja bli lite frustrerad. Alla sidorna i denna analys skulle jag anse som snabba.

Topplista:
1. Jesper.nu
2. Youtube.com
3. Blocket.se

<br></br>
Övrigt
-----------------------
Rapport skriven av Alfred Almquist