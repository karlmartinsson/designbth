---
---
Rapport laddningstider
=========================

Det här är en rapport som ska undersöka färger och typgrafi för tre webbsidor.

Urval
-----------------------

Jag har fortsatt på temat från det förra kursmomentet och valt ut tre journalistiska nyhetssajter för min rapport. När en läsare vill ha en snabb nyhetsuppdatering tror jag att det det är viktigt att sidan känns responsiv och snabbladdad för att behålla intresset hos läsaren. Jag valde en stor kvällstidning: ([Aftonbladet](https://www.aftonbladet.se), en stor morgontidning: [Svenska Dagbladet](https://www.svd.se)) samt Sveriges största lokaltidning ([Göteborgsposten](https://www.gp.se))

De tre webbplatserna har samma fokus: Att få läsaren att läsa så mycket som möjligt för att kunna visa så mycket annonser som möjligt. Svd och GP vill också sälja prenumerationer till läsaren.

För varje sajt valde jag att granska huvudsidan, en underkategorisida (tex kultur eller sport) samt en artikelsida.

Metod
-----------------------

Jag använder mig av Googles PageSpeed Insights för att kontrollera laddningstider av olika dela av sajterna samt för att få indikationer på förbättringspotential. Jag använder mig också av Chromes dev-tools för att se hur många requests som inkommer till sajten samt sidans storlek.

Jag använder också Google Spreadsheets för att dokumentera mina resultat.

Resultat
-----------------------

För varje webbplats, gör följande:

Ta en snapshot (bild) på webbplatsen.
Välj ut tre sidor (bifoga länkarna) som skall mätas med Google Pagespeed. Mät på både Mobile och Desktop. Notera de betyg som ges.
För varje sida, mät med devtools flik networks och notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida gör mätningen tre gånger och ta snittet av mätvärdena.
Diskutera och skriv en mening om hur webbplatsen kan förbättra sig.

## aftonbladet.se

[FIGURE src=img/aftonbladetladdtid.png class="center big w50" caption="aftonbladet.se"]

### länkar

* [https://www.aftonbladet.se/nyheter/a/Jo2o5X/storbrand-i-halmstad-stor-spridningsrisk](https://www.aftonbladet.se/nyheter/a/Jo2o5X/storbrand-i-halmstad-stor-spridningsrisk)
* [https://www.aftonbladet.se/sportbladet](https://www.aftonbladet.se/sportbladet)
* [https://www.aftonbladet.se](https://www.aftonbladet.se)

Tiden till interaktivt tillstånd för aftonbladets sidor på mobilen låg mellan ca 14 och 19 sekunder. Den första meningsfulla skärmuppritningen tog ungefär 2 sekunder för alla tre sidor.

På desktop tog det mellan 4,7 och sex sekunder att komma till ett interaktivt tillstånd och den första meningsfulla skärmuppritningen tog mellan 0,6 och 0,8 sekunder. Antalet requests låg i snitt mellan 96 och 173 stycken och sajten var mellan 2,5 och 7,8 mb stor att ladda ner.

Enligt PageSpeed Insights skulle Aftonbladet tjäna på att skicka bilder i modernare bildformat och koda dem effektivt. Man skulle också tjäna på att ta bort resurser som blockerar inläsningen och skjuta upp inläsning av bilder som inte visas på skärmen.

## gp.se

[FIGURE src=img/gpladdtid.png class="center big" caption="gp.se"]

### länkar

* [https://www.gp.se](https://www.gp.se)
* [https://www.gp.se/sport](https://www.gp.se/sport)
* [https://www.gp.se/sport/fotboll/s%C3%A5-blev-borussia-dortmund-st%C3%B6rst-i-hela-europa-1.21547135](https://www.gp.se/sport/fotboll/s%C3%A5-blev-borussia-dortmund-st%C3%B6rst-i-hela-europa-1.21547135)

Gp.se dröjde mellan 11,8 och 19,4 sekunder till ett interaktivt tillstånd på mobilen. På desktop gick det lite fortare: Mellan 1,8 och 3,4 sekunder. Den första meningsfulla skärmuppritningen tig mellan 5,7 och 8,2 sekunder på mobil och mellan 1,5 och 1,9 sekunder på desktop. GP använder sig av väldigt många requests på sin förstasida, i snitt 438 stycken. Sidan är också väldigt tung, i snitt 23 mb.

Gp.se skulle enligt PageSpeed kunna tjäna väldigt mycket (hela 29 sekunder) på att använda bilder med rätt storlek. Bildhanteringen här verkar brista lite efterom de också skulle kunan tjäna omkring 4 sekunder på att koda bilderna mer effektivt. Man verkar inte heller använda minifierad css vilket känns lite överraskande.

GP rekommenderas också att ta bort resurser som blockerar inläsningen. Med sina omkring 430 requests känns inte det helt överraskande. Inte heller förslaget att "undvika enorm nätverksbelastning".

## svd.se

[FIGURE src=img/svdladdtid.png class="center big" caption="svd.se"]

### länkar

* [https://www.svd.se](https://www.svd.se)
* [https://www.svd.se/kultur](https://www.svd.se/kultur)
* [https://www.svd.se/riksratten-riskerar-att-polarisera-usa-ytterligare](https://www.svd.se/riksratten-riskerar-att-polarisera-usa-ytterligare)

Tiden till interaktivt tillstånd för aftonbladets sidor på mobilen låg mellan ca 10,9 och 18,6 sekunder. Den första meningsfulla skärmuppritningen tog ungefär 4 sekunder för alla tre sidor.

På desktop tog det mellan 2,4 och 3,7 sekunder att komma till ett interaktivt tillstånd och den första meningsfulla skärmuppritningen tog mellan 1 och 1,6 sekunder. Antalet requests låg i snitt mellan 94 och 154 stycken och sajten var mellan 1,7 och 7,8 mb stor att ladda ner.

Svd skulle, precis som de andra sajterna kunna spara laddtid genom att använda mer moderna bildformat samt skjuta upp bildladdning som inte syns på skärmen. Även här skulle man spara tid genom att ladda bilder i rätt storlek samt plocka bort oanvänd css.

Analys
-----------------------

[Länk till rapporten i google docs](https://docs.google.com/spreadsheets/d/1_uAJpADX0gmSiFL-Z24Wfn7d_i8hTpbY94hMbGmzH08/edit?usp=sharing)

Alla tre nyhetssajterna var relativt tunga och har många requests. Kanske inte helt överraskande då de både består av många bilder och har mycket reklam så både är requesttung och i sig består av stora bilder och också mycket film. GP:s storlek och enorma mängder requests var ändå överraskande. Också det faktum att gp inte minifierat sin css känns ju rent ut sagt lite slappt.

Alla sajterna hade oanvänd css vilket också känns lite onödigt. En bättre bildhantering med skalning på servern skulle nog kunna minska laddtiderna rejält. Också att se över de stora mängder utomstående resurser som plockas in till sajterna.

Referenser
-----------------------

* [GooglePage Insights](https://developers.google.com/speed/pagespeed/insights/)
* [https://www.gp.se](https://www.gp.se)
* [https://www.gp.se/sport](https://www.gp.se/sport)
* [https://www.gp.se/sport/fotboll/s%C3%A5-blev-borussia-dortmund-st%C3%B6rst-i-hela-europa-1.21547135](https://www.gp.se/sport/fotboll/s%C3%A5-blev-borussia-dortmund-st%C3%B6rst-i-hela-europa-1.21547135)
* [https://www.gp.se](https://www.gp.se)
* [https://www.gp.se/sport](https://www.gp.se/sport)
* [https://www.gp.se/sport/fotboll/s%C3%A5-blev-borussia-dortmund-st%C3%B6rst-i-hela-europa-1.21547135](https://www.gp.se/sport/fotboll/s%C3%A5-blev-borussia-dortmund-st%C3%B6rst-i-hela-europa-1.21547135)
* [https://www.svd.se](https://www.svd.se)
* [https://www.svd.se/kultur](https://www.svd.se/kultur)
* [https://www.svd.se/riksratten-riskerar-att-polarisera-usa-ytterligare](https://www.svd.se/riksratten-riskerar-att-polarisera-usa-ytterligare)

Övrigt
-----------------------

Jag har valt att utföra undersökningen och skriva rapporten själv, då jag jobbar heltid och och ofta pluggar sent på kvällen och märkliga tiden. Jag skulle därför få svårt att samordna ett grupparbete med andra på kursen på ett vettigt sätt. Jag som skrivit rapporten heter Karl Martinsson.
