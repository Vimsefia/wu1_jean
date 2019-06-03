# wu1_jean
*Jenny Andersson*

## Bakgrund

## Planering

### Innehåll
Hemsidan ska innehålla fem flikar: Home, about, contact, work och en sida för uppgiften "internets historia". <br>
Headern ska innehålla ett mönster, t.ex. marmor. Det ska även vara en horisontell navbar precis under mönstret som en del av headern.<br>
"Home" ska innehålla de senaste bilderna som är inlagda i "work". <br>
"About" ska innehålla en personlig bild och en text om mig själv. <br>
"Contact" ska innehålla ett kontaktformulär där man fyller i namn, land man kommer ifrån (för att man ska veta språk), e-mail, ämne och meddelande. <br>
"Work" ska innehålla alla bilder som är inlagda i portfolion. (Kanske indelade i kategorier t.ex fåglar, vilda djur mm. där man klickar på en bild och kommer in till alla inlagda bilder av den "sorten". <br>
"History of Internet" innehåller mina svar på en uppgift vi fått. <br>


### Layout
Se tidigare uppgift


### Färgval

##### Bakgrund - 
###### Användningsområde
###### HEX - #FFFFFF: ![alt-text](https://via.placeholder.com/20/FFFFFF/FFFFFF?Text=%20 "#FFFFFF")

##### Element - 
###### Användningsområde
###### HEX - #474947: ![alt-text](https://via.placeholder.com/20/474947/474947?Text=%20 "#474947")

##### Huvudsaklig färg - 
###### Användningsområde
###### HEX - #22292C: ![alt-text](https://via.placeholder.com/20/22292C/22292C?Text=%20 "#22292C")

##### Beteende -
###### Användningsområde
###### HEX - #4D7511: ![alt-text](https://via.placeholder.com/20/4D7511/4D7511?Text=%20 "#4D7511")

##### Text - 
###### Användningsområde
###### HEX - #000000: ![alt-text](https://via.placeholder.com/20/000000/000000?Text=%20 "#000000")


### Typsnitt
Oswald, Sans-serif


### Mockup
Se tidigare uppgift


### Tillgänglighet
Om jag ska vara ärlig så tänker jag inte så mycket på tillgängligheten. Det jag har tänkt mig är att lägga in "alt" på alla bilder så att även synskadade kan ta del av sidan genom att lyssna på vad bilderna föreställer. 


## Dokumentation

### Vad var uppgiften?
Syftet med uppgiften är att göra en webbplats i form av en portfolio eller en blogg. Jag har valt att göra en portfolio.


### Hur genomförde du uppgiften?

Till en början hade jag inte några speciella ideér. Det var inget som "poppade" upp i mitt huvud när jag fick reda på uppgiften, det ända som var självklart var att jag skulle göra en portfolio och inte en blogg. Till en början satt jag och sökte efter inspiration på nätet. Hur andra har utformat sina versioner av portfolio. De två som jag fastnade mest för var: <br>
http://nolbert.com/work och http://www.pandayoghurt.co.uk/  <br>
Det jag fastnade mest för var att designerna var väldigt "fräscha" och stilrena. Vit bakgrund och bilderna som man lägger in blir som små färgklickar. <br> <br>

När jag väl bestämt mig för att hämta inspiration från de två sidorna så gjorde jag en skiss och en mockup på de element som jag ville ha med. Därefter gick jag in på "w3schools" för att få ännu mer inspiration. Väl på w3schools så gick jag in på "how to", när man klickat på den så landar man automatiskt på "how to home" där det finns 8 sidor med olika grejer man kan lägga in på sin sida. Dessa 8 sidor gick jag igenom för att se om det var något intressant som jag skulle kunna tänka mig att ha på min sida. När jag hittade något som jag gillade så skrev jag upp det i ett html-dokument i atom (mall.html) för att lätt komma åt det medans jag kodar i ett annat dokument. <br> <br>

![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Atom.png) <br> <br>

Som man ser på bilden så skrev jag ut alla flikar som en kommentar och skrev sedan ner det jag ville ha med under varje flik. Därefter så började jag med att skapa en header. Till en början tänkte jag att det skulle vara marmor i headern (som man kan se på mockupen) men hittade sedan en snygg bild med vitt trä som jag bestämde mig för att ha istället. Lade in en rubrik med mitt namn och sedan en underrubrik, "min portfolio". Därefter gjorde jag navbaren med de flikar jag skulle ha och en sökruta med en sökknapp, ganska snabbt därefter började jag styla både headern och navbaren så att de såg ut som jag ville. Hade lite problem med att få till navbaren precis så som jag ville ha den då jag ville att knapparna skulle ändra färg när man håller pekaren över den och att färgen skulle täcka hela höjden på navbaren. Detta var lite krångligt att få till samtidigt som jag skulle få sökrutan och sökknappen att ligga i mitten i förhållande till höjden. Som man ser på resultatet nu så har jag inte riktigt fått till det ännu, efter ett tag så kände jag att jag skulle prioritera de andra grejerna för att hinna med de också. När jag kände mig någorlunda klar så lade jag över koden för headern till alla html-dokumenten som jag har använt mig av. <br> <br>

"About-sidan" (about.html) var väldigt lätt att fixa. Det var bara att lägga in en bild och en text. Sedan styla detta med hjälp av CSS för att bland annat lägga bilden och texten bredvid varandra samt att fixa texten så den är symmetrisk. <br> <br>

Därefter gick jag över till "contact-dokumentet" (contact.html) för att göra kontaktformuläret. Samma där, jag använde mig av w3schools för att få ihop formuläret men jag bytte ut vissa grejer för att det skulle passa just det jag ville ha. Formuläret var ganska lätt att få ihop, det var inget speciellt som krånglade och det var lätt att styla med CSS så att det blev så som jag tänkte. Sedan så hade jag tänkt ha en ruta med min information om hur man kan kontakta mig osv på annat sätt än formuläret. Men kom sedan på att det hade varit bra att ha den informationen på ala sidorna. Då började jag fundera på hur andra sidor är utformade och kom på att man kan ha en footer med informationen. Så jag satte mig och gjorde denna, det var väldigt lätt. Gjorde bara en "footer-tag" och en "p-tag" inuti med informationen i, sedan gick jag till CSS-filen och fixade så att färgen på texten blev grå och fixade lite placering och liknande. Även footer-tagen lade jag in i alla dokumenten. <br> <br>

När det var klart gick jag över till "home-dokumentet" (index.html) där jag planerat att lägga in de senaste bilderna som är upplagda. På w3schools hittade jag en tutorial på "slideshow gallery" som jag tyckte passade in på det jag tänkt mig. Denna var väldigt krånglig att få till. Jag kopierade texten från deras hemsida och lade in  i mitt dokument. Även här ändrade jag lite grejer för att det skulle passa mig. För att få denna att fungera var man även tvungen att lägga in ett javascript utöver HTML och CSS. När jag lagt in allt i html-dokumentet, CSS-filen och javascriptet och ändrat det jag ville så fungerade det inte. Jag tänkte och tänkte på vad det kunde vara, ändrade på saker som jag trodde att det kunde vara men utan resultat och efter lite rådfrågan med läraren så lade jag över scriptet i en "script-tag" direkt i html-dokumentet. Då fungerade scriptet helt plötsligt. Sedan var det lite krångel med CSSen också men det lyckades jag lista ut själv efter en stunds tänkande. Bilderna som är inlagda är inte mina egna bilder utan det är bilder tagna från hemsidan https://pixabay.com/ där bilderna är helt fria att använda. Sedan lade jag även in en välkomsttext över slideshowen för att jag tyckte det såg trevligare ut. <br> <br>

Sedan lade jag in "internets historia"-uppgiften i "history of internet-dokumentet" (history.html). Den var redan färdigskriven i en mall med kod för rubriker osv så det var bara att lägga in det jag skrivit i html-dokumentet. Sedan stylade jag lite grann med CSS för att centrera texten, ändra font, storlek och lite sånt. <br> <br>

"Work-dokumentet" (work.html) sparade jag till sist för jag visste att det skulle vara den jobbigaste av dom. Där planerade jag att jag skulle lägga in en "image grid" med alla bilder som är upplagda. Med image grid kan den som kollar på bilderna välja om 1, 2 eller 4 bilder ska visas samtidigt. Denna var jobbig att få till, som man ser på hemsidan så har jag fortfarande inte fått den att fungera riktigt. Även denna koden kopierade jag in direkt från w3schools och ändrade klasser och lite sånt för att passa mig. Men jag hittar inte vad det är som gör att det inte fungerar, varken i HTML, CSS eller JS. Jag var så sent ute med att börja på denna sidan också så jag har inte heller kunnat rådfråga läraren. Bilderna på denna sidan är också tagna från Pixabay. <br> <br>


### Vad blev resultatet?

Här kommer bilder på resultatet från Google Chrome samt Miscrosoft Edge. Jag kommer lägga först Chrme och sen samma bild fast från Edge. Som man ser på bilderna så är resultatet väldigt lika på de båda webbläsarna. Det finns en text under varje bild med beskrivning osv. <br> <br>

![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Chrome/Chrome_header.png)
![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Edge/Edge_header.png)
<br> <br> De två bilderna ovan är fokuserad på headern coh välkomsttexten. Som man ser så är sökområdet inte riktigt anpassat till mitten så det ser lite konstigt ut. Storleken är inte heller riktigt som den ska vara. När man klickar på sökknappen så ser det ut som att man söker men det händer ingenting då jag inte fixat det. Jag kunde alltså lagt lite mer tid på att fixa sökdelen av navbaren. Resten är jag ganska nöjd med, tycker det ser ut så som jag tänkt mig. <br> <br>

![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Chrome/Chrome_home.png)
![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Edge/Edge_home.png)
<br> <br> Här är samma sida som bilden på headern, alltså "home". På bilden ser man galleriet med de sex senaste bilderna från "work". Den visar en liten version av alla bilder underst och sedan visar den en stor bild på den som är vald samt att just den bilden är highlightad bland de mindre bilderna. Nu ser man inte det på bilderna ovan men när man hovrar över en av de mindre bilderna så highlightas även denna. Det går att klicka på varlfri liten bild för att välja denna och det går även att klicka på pilarna som är på varsin sida av den stora bilden för att byta bild till höger eller vänster. Uppe i vänstra hörnet står det även vilken bild man är på. Mellan de små bilderna och den stora bilden så står det en text om vad det är på bilden, denna text är även inlagd som "alt" så man kan lyssna  på den. I undeerkant kan man även se footern som jag lagt in med min information, denna kommer man se på nästan alla bilder som ligger här. Denna sida är jag väldigt nöjd med. Trodde inte att jag skulle lyckas fixa det så som jag ville ha det men jag tycker att jag lyckades ganska bra ändå. <br> <br>

![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Chrome/Chrome_about.png)
![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Edge/Edge_about.png)
<br> <br> Denna sida är ganska simpel. Den består av en bild till vänster som egentligen ska vara på mig men eftersom jag inte ska publicera sidan så lade jag in en exempelbild istället. Till höger om bilden så är det en lorem ipsum text där det egentligen ska vara en text om mig själv. <br> <br>

![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Chrome/Chrome_contact.png)
![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Edge/Edge_contact.png)
<br> <br> Ovan har vi en bild på kontaktformuläret. Som bilden visar så ska förnamn, efternamn, vilket land man kommer från, e-mail, ämne och meddelande fyllas i. Tanken är att det ska vara en såndär stjärna på alla som visar att man måste fylla i alla fält men det har jag inte hunnit fixa. Som man kanske kan skymta på det fältet där man ska fylla i land så visas en lista när man klickar på den där man kan välja bland några länder som jag lagt in eller klicka på "other" om man kommer från ett annat land än det som står. Meddelandefältet är från början bara en rad som man ser på bilderna men den vidgas om så behövs när man skriver. När man klickar på submitknappen så ser det ut som att man skickar, texten man skrivit försvinner men den hamnar ingenstans så det går att läsa. <br> <br>

![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Chrome/Chrome_work2.png)
![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Edge/Edge_work2.png)
<br> <br> På bilderna ovan kan man se hur "work-sidan" ser ut när man har klickat på "2". Anledningen till att jag inte har någon bild på "1" är för att de båda ser likadana ut. Det är ju inte riktigt tanken men som jag skrev tidigare så har jag inte lyckats få denna sida att fungera så som jag vill. Hade behövt lägga mer tid på denna sidan. Men tillbaka till bilden, som den visar så ser man bara en bild i taget även på "2". Denna ska ju då egentligen visa två bilder på varje rad. Då jag hade ont om tid på slutet så har jag inte lagt in någon "alt" text på bilderna som ligger under sidan "work", detta har jag bara<br> <br>

![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Chrome/Chrome_work4.png)
![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Edge/Edge_work4.png)
<br> <br> Här kan man se hur det ser ut när man trycker på "4". Nu har den iallafall ändrat sig men den visar bara tre bilder i bredd när den egentligen ska visa fyra. Men när man bläddrar ner en liten bit så ligger bilderna enoch en igen. Som sagt så hittar jag inte vad det kan bero på att den gör såhär. <br> <br>

![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Chrome/Chrome_history.png)
![alt text](https://github.com/Vimsefia/wu1_jean/blob/master/Assets/IMG/Edge/Edge_history.png)
<br> <br> Sista bilderna visar bara uppgiften som vi fick. Den låg redan i en mall med rubriker, punktlistor och liknande så det var inte jättemycket jobb med denna sidan. Det var bara att fixa lite med CSSen så att texten centrerades osv. <br> <br>

Jag har stött på ganska mycket fel. Allt från hur man enkelt lägger in en bild till hur man får t.ex. "work-sidan" att fungera. Alla fel har jag inte löst, t.ex. work. Men de flesta har jag löst på egen hand. Tyvärr har jag inte några före och efterbilder på detta då jag hade så mycket fokus på att fixa problemen. <br> <br>


### Utvärdering.

Jag är nöjd med hur förstasidan blev (home), jag förväntade mig inte alls att jag skulle lyckas med det resultatet. Jag hade en bild i huvudet om hur jag tänkte att det skulle se ut men jag var inte kåst vid det för att jag inte visste hur mycket jag kunde göra men det var i pricip så min bild var. Det jag kunde lagt ner mer tid på är sökfältet i headern, den är jag inte nöjd med. Jag tycker det är bra att jag lyckades skapa de element jag ville ha och att jag fick in bilden med ett förstoringsglas i sökrutan men stylingen är inte så som jag tänkt mig. <br> <br>

"About" var väldigt lätt att fixa. Det finns inte så mycket att säga där, det är en bild och en text och det är vad jag tänkte skulle finnas där. Kanske att man skulle fått in knappar som gick direkt till sociala medier osv men tiden räckte inte till då jag disponerat den fel. <br> <br>

"Contact" är jag också nöjd med. Jag frångick planeringen lite med att ta bort rutan med information, men informationen fick jag med ändå genom en footer. Det är lite blandat i kontaktformuläret, inte bara massa textrutor utan det är även en lista där man kan välja redan skrivna alternativ och meddelanderutan vidgar sig om så behövs. Detta är jag nöjd med, formuläret är inte så simpel utan det är lite varierat och seriöst. Det jag kunde gjort bättre här är att ha lagt in stjärnor på de fält som man ska vara tvungen att fylla i, som det finns på de flesta formulär man ser. <br> <br>

"Work" finns det mycket på som kan förbättras. Dels så fungerar ju inte sidan alls så som var planerat. Ja den visar bilderna men inte så som var tänkt. Knapparna som jag lagt in fungerar halvt, det händer inget om man klickar på "1" eller "2", när man klickar på "4" så ändras sidan med den visar bara tre bilder i rad plus att det är inte är alla rader som den visar så, en bit längre ner visar den bara en bild i taget igen. Tanken var också att knapparna ska ändra färg när man hovrar över dom och det har jag lyckas med. De ska även bli en annan färg när de är "active" och det blir de men den färgen ska ändras tillbaka när man klickar på en av de andra knapparna. Men den färgen ligger kvar så när man klickar på en annan knapp så är de båda den färgen. Så jag kan summera detta med att den här sidan hade behövt mycet mer tid än vad den fick. <br> <br>

Generellt så hade jag behövt disponera tiden mycket bättre. I början så kände jag att det var lätt och att jag kunde ta det lite lugnt. Detta har hängt i och det har visat sig nu i slutet. Alldeles för lite tid för att kunna leverera ett bra resultat. Jag hade även kunnat ha bättre kontakt med läraren för att kolla hur jag låg till men jag tycker att läraren kunde ha kommunicerat med mig också om hur jag låg till. T.ex. gått till varje individ som inte lämnat in vissa uppgifter och sagt till att de behöver komma in för att få ett godkänt betyg. Detta är ju en ansvar som jag som elev också har, att kolla med läraren vad som ska in och vad som krävs. <br> <br>
