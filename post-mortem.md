# TE19 Kampanj Port mortem

Jacob Wennebro, 2021-02-15

## Inledning

Målet med uppgiften var att skapa en kampanj sida som passade temat man var given. I mitt fall så skapade jag en kampanj sida åt en påhittad kampanj "Fuck Corona" som var ute efter att lära människor om coronaviruset.

## Bakgrund

Först gjorde jag och min grupp en planering ihop som skulle bli basen för vår hemsida, saker som färg, målgrupp osv. 

Sedan började vi jobba individuellt där jag startade med att skapa en figma skiss, tidigare i planeringsfasen så ville jag utmana mig själv rent designmässigt så jag valde färgerna blå och gul som primära. 

Då jag var nöjd med min skiss påbörjade jag sidans struktur med HTML and samt därefter med CSS. Jag valde för just detta projektet att använda ren CSS istället för t.ex Sass vilket jag ångrar litegrann i efterhand då det känns som det kunde gått snabbare och mina filer blivit mindre kladdiga ifall jag inte gjort det.

Jag jobbade på sidan utifrån mobile first principen och på grund av lite tidsbrist så hann jag aldrig riktigt optimisera sidan för desktop så mycket som jag hade velat, men nedan är en preview av sidan på mobil. 👇

![Fuck Corona Mobile Preview PNG](/mobile-preview.png)

## Positiva erfarenheter

Att få "LATEST ARTICLE" boxen att centrera emellan två sektioner var lite kruligt men tror jag lyckades få fram effekten ganska bra även om det säkert finns bättre sätt att göra det på. Jag tycker att jag lyckades bra med färgschemat och med att få fram en fungerande design.

Upplägget av uppgiften i allmänhet tycker jag fungerade bra. Det var hjälpsamt att kunna planera och dela tankar i början av uppgiften innan man började jobba individuellt.

## Negativa erfarenheter

Sidan känns väldigt oavslutad, den är inte speciellt responsiv från mobile till desktop och det finns heller inga undersidor eller en meny funktion. Det känns som jag kunde ha varit flitigare med min tid, dock så gick mycket tid åt research på just detta projekt så åtminstone har jag lärt mig något.

## Validering & tester

### CSS Validering
All CSS är validerad och utmärkt med hjälp utav [W3's CSS Validator](https://jigsaw.w3.org/css-validator/). Till en början hade validatorn problem med att jag använde "max/min-device-width" för mina media queries vilket nämligen var deprecated. Men med en lätt Googling fann jag de moderna alternativen och bytte ut dem för att få ett perfekt resultat ifrån validatorn.

### Användbarhetstest
Sidan är väldigt basic och håller sig till diverse design principer vilket för en sidas funktioner igenkännbara. Personen jag anlitat för att testa sidan hade inga problem med att förstå eller föreställa sig hur man navigerar på sidan.

### Tillgänglighetstest
Sidan har testats för tillgänglihet med Web Disability Simulator och är klart användbar och lätt att förstå för alla synnedsättningar som testats tack vare färgerna och konstrasterna som valts för sidan.

## Sammanfattning

Jag tror definitivt sidan har potential, om jag hade haft mera tid och kanske lite intresse för ämnet så hade jag nog kommit längre än enbart en homepage. Men jag är ändå nöjd med min design och slutprodukt.

Jag tror för framtida projekt av denna skala kommer jag vilja använda ramverk för att underlätta struktur och utveckling såvidare det är tillåtet.