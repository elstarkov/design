---
Title: Page speed
Description: This is my page speed analysis page.
Template:
---

Kmom05 - En analys av olika webbplatsers laddningstid.
=======================

En analys av laddningstiden hos Sveriges mest besökta svenska webbplatser 2021 enligt data
från Semrush[1] (via TopDog[2]).

Urval
-----------------------
Webbplatserna som kommer analyseras är Aftonbladet(1), Expressen(2) och Ica(3). Dessa sidor är utvalda för
att samtliga tillhör Sveriges mest besökta svenska webbplatser. I den här analysen kommer sidornas
laddningstid att undersökas och jämföras med varandra.

Metod
-----------------------
För att mäta laddningstiden kommer det inbyggda DevTools-verktyget att användas via Google Chrome.
Inladdningstiden mäts i millisekunder (ms) och varje hemsida kommer att mätas tre gånger. Sedan
anges ett snitt som det slutgiltiga svaret för laddningshastigheten. Varje resultat kommer dock att
dokumenteras i ett kalkylark. Webbplatsen "PageSpeed Insights[3]" kommer också att användas
för att betygsätta webbplatsernas förmåga att ladda in innehåll. Här kommer både hemsidornas desktop-
och mobil-version att analyseras. Därefter ges en kort kommentar om potentiella förbättringsmöjligheter
innan en slutgiltig vinnare koras utifrån resultatet på de olika metoderna. Längst ner på sidan
kan man studera samtliga mätningar.

Resultat:
-----------------------
#### Aftonbladet [4]

![aftonbladet](%assets_url%/img/aftonbladet.JPG)

Aftonbladet var 2021 Sveriges mest besökta svenska hemsida. Aftonbladet är en av Sveriges största tidningar
och förekommer både digitalt och i pappersformat.

Aftonbladets innehåll hämtades med ett snitt av 725ms enligt DevTools-verktyget i Google Chrome.
PageSpeed ger desktop-varianten ger desktop-versionen 83 av 100 poäng medan mobilvarianten
landade på 75 poäng.

PageSpeed lämnar även feedback på förslag till förbättringar. På den mobila sidan ser
PageSpeed som störst förbättringspotential i att reducera JavaScript som inte används.
Det skulle ge en uppskattad tidsbesparing på 1,8 sekunder. Andra förbättringar vore att
reducera CSS som inte används och undvika att skicka äldre JavaScript till moderna webbläsare.
I desktop föreslås Aftonbladet att använda bilder med rätt storlek och att skicka dem i ett
modernare bildformat.

#### Expressen [5]

![expressen](%assets_url%/img/expressen.JPG)

Expressen är nästa stora tidning av undersökas. Under 2021 var det Sveriges näst mest besökta svenska
webbplats. Precis som Aftonbladet förekommer även denna nyhetskälla både digitalt och i papper.

Expressen hämtades med en snitthastighet av 482ms. Desktop-versionen fick betyget 87 medan
mobil-versionen landade på 75 poäng.

PageSpeed ser för desktop störst förbättringsmöjligheter i att minska serverns första svarstid
men föreslår också att JavaScript som inte används bör reduceras. Detta är även vad som föreslås
för den mobila hanteraren. Gällande reducering av JavaScript på mobilversionen uppskattas
tidsbesparingen vara 1,66 sekunder. Även för Expressen föreslås det också att äldre JavaScript till
moderna webbläsare bör undvikas.

#### Ica [6]

![ica](%assets_url%/img/ica.JPG)

Från tidningar till mat. Ica kom på tredjeplats bland mest besökta svenska webbplatser i Sverige 2021.
Ica säljer mat i sina fysiska butiker men även på hemsidan kan användaren beställa mat både för
upphämtning och hemkörning.

Innehållet på Icas webbplats hämtades med en snitthastighet av 1040ms. PageSpeed gav desktop ett genomsnitt
på 89 poäng och mobilversionen 79 poäng.

Gällande förbättringar så föreslår PageSpeed även här att man ser över JavaScript som inte används. Detta gäller
främst den mobila varianten där uppskattad tidsbesparing sätts till 1.65 sekunder. Övriga förbättringsområden
är att ta bort resurser som blockerar renderingen och att reducera CSS som inte används.

Analys
-----------------------

Gemensamt för alla tre webbplatser är hur JavaScript som inte används kraftigt ökar tiden för inläsning av innehållet.
För nyhetssidor som vill nå ut till så många som möjligt så snabbt som möjligt så är första tanken att man borde vara
mer medveten om och se över så tydliga begränsningar. Det går endast att spekulera i varför man inte åtgärdat detta
men en möjlig tanke är att man har så stort fokus på att leverera just nyheter att man låter gammal kod ligga kvar
så länge hemsidan ändå fungerar som förväntat. Man kanske inte vågar riskera att förstöra delar av hemsidan eftersom
man ständigt uppdaterar den med nya nyheter som behöver komma ut snabbt. Att inte webbplatsen då skulle fungera under bara
några minuter skulle kunna innebära att konkurrenter tar över besökarna. En annan möjlig anledning skulle kunna vara att
man helt enkelt inte är medveten om hur mycket "skräpande kod" påverkar prestandan. Övrigt gemensamt är att desktop-versionen
av de undersökta webbplatserna fungerar bättre än mobil-versionen enligt PageSpeeds undersökning. I en värld där användingen
av mobila enheter idag är väldigt hög är även detta ett utropstecken. Många får nyheter direkt i mobilen via push-notiser
så kanske borde man lite extra se över prestandan i sina mobilappar.

Resultat
----------------------

För att helt rättvist kunna jämföra sidornas resultat skulle det kanske helst ha varit tre stycken nyhets-sidor eftersom
webbplatsernas syfte då vore som allra mest gemensamt. Nu sticker Ica ut då man inte verkar inom samma bransch men om
man vänder på det så ger det också en möjlig krydda till analysen. Syns det i resultatet? Kanske. Sett till inladdningshastighet
så är Ica klart långsammare än de bägge nyhetssidorna. Däremot får Ica en bättre betyg både vid mobil-
och desktop-användning. Vi väljer att göra två resultatlistor:

#### Ranking - Laddningshastighet
1. Expressen
2. Aftonbladet
3. Ica

#### Ranking - Användarvänlighet och prestanda
1. Ica
2. Expressen
3. Aftonbladet

Nedan finns samtliga mätningar dokumenterade i ett kalkyl-blad:

<iframe class="calc" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTWRsic5uTPiKXfl4HbKDLZqeDjXNEXHtR4MQEhm2jJ8-e0FV9nd5pMom9JvPWGNF1nVlu_k3Kilh83/pubhtml?widget=true&amp;headers=false"></iframe>

Avslutande ord
-----------------------

På förhand hade jag läst att optimal inladdningstid för en webbplats bör ligga på runt 200ms[7]. Detta hade jag därför i bakhuvudet när jag genomförde
analysen. Så här i efterhand tänker jag att eftersom responstiden påverkas av trafiken som webbsidan får så bör man kanske ha lite överseende gällande
just dessa sajter. Det är svårt att dra några riktiga slutsatser med endast tre webbsidor analyserade och trots att jag lite löst hade 200ms som gräns
så skulle jag kunna tänka om och lyfta fram att Expressens 482ms inte är så dumt i alla fall. Å andra sidan kan man hävda att det inte alls sticker
ut då antalet resurser som laddades in enbart uppgick till 36st medan Ica låg på runt 60st och Aftonbladet 80-90st. Om man sedan övergår till att titta
på total storlek så laddar Ica och Aftonbladet in dubbelt så många megabyte som Expressen. Det blir därmed svårt att dra några egentliga slutsatser
och för att göra en mer rättvis och djupgående analys så bör rimligtvis fler webbplatser och endast från samma bransch analyseras och jämföras. Det
skulle generera en mer representativ och jämförelsebar data.

Referenser
-----------------------
1. https://www.semrush.com/ (Besökt 2022-12-10)
2. https://topdog.nu/storsta-sajterna-google/ (Besökt 2022-12-10)
3. https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect (Besökt 2022-12-10)
4. https://www.aftonbladet.se/ (Besökt 2022-12-10)
5. https://www.expressen.se/ (Besökt 2022-12-10)
6. https://www.ica.se/ (Besökt 2022-12-10)
7. https://moz.com/learn/seo/page-speed (Besökt 2022-12-10)

Av: Samuel Ward, 2022-12-11
