37% av alla mjukvaruutvecklingsprojekt har problem med krav. Att kunna samla in, hantera och analysera krav genom hela utvecklingsprocessen är vitalt för att kunna leverera högkvalitativ mjukvara. Som mjukvaruutvecklare möter man ofta krav på många olika sätt; ibland kanske man pratar direkt med slutanvändare eller kund, i andra fall måste man förlita sig på dokumentation som kommunikationsmedel.

Att ha förmågan att dokumentera mjukvarukrav på ett tydligt och effektivt sätt är viktigt för alla mjukvaruutvecklare.

Målet med denna uppgift är att öva på att hitta och dokumentera funktionella krav för ett system. Detta görs med hjälp av användningsfall (Use Cases).

## Deadline och Redovisning

Uppgiften skall redovisas senast v.50
Uppgiften skall godkännas senast v.51

Uppgiften redovisas genom att kraven visas för och diskuteras med handledare.

## Föreslå ändringar

Denna handledning ligger på [GitHub](https://github.com/1dv404/Laborationer) om du vill föreslå ändringar eller hålla koll på vad de senaste uppdateringarna innebar.

## Förberedelse

Läs kap 5, 6 och 7 i kurslitteraturen så är du väl förberedd på att klara laborationens moment. Kolla gärna igenom den föreläsning som tar upp användningsfall.

## Genomförande

I denna laboration ska du givet den vision du skrev i en tidigare laboration dokumentera funktionella krav på systemet. Se till att dina krav går att komma åt via din fork av [ https://github.com/1dv404/Uppgift-234]( https://github.com/1dv404/Uppgift-234).


1. Du ska hitta och dokumentera systemets aktörer.
2. Du ska finna användningsfall som löser problemet och namge dessa på ett lämpligt sätt (begränsa dig till maximalt 15 användningsfall).
3. Du skall beskriva några av dina viktigaste användningsfall i kort format.
4. Du ska skriva ett detaljerat användningsfall (omnämns som “fully dressed” i boken) för ett viktigt/riskfyllt krav (viktig innebär i detta fall mest komplicerade; dvs stora med både input och output, flertalet extensions och kanske inblandning av sekundära aktörer)
5. Den dokumentation du producerar ska vara välstrukturerad och gärna hyperlänkad på lämpligt sätt.
6. Granska det du gjort. Några saker att titta på:

* Namngivning av aktörer, ska vara i passiv form singular (en/ett)
* Har alla UC ett tydligt namn i form av en aktiv verbfras (något man gör eller vill åstadkomma)
* Tydlig triger i UC
* Klarar UC “the boss test”?
* Efterlevs EBP regeln (1 aktör, 1 tidpunkt, 1 plats)
* Klarar UC storlekstestet?
* Har aktör – system varannan punkt i scenarios
* Finns det vettiga extensions och är de korrekt formaterade?
* Finns det tydliga krav på vad systemet ska presentera eller göra i UC (t.ex. bara “bekräftar” eller ska något lagras, sparas, förändras)
* Är det tydligt vilken typ av information som aktören matar in i systemet?
* Är det tydligt vilken typ av information som systemet presenterar?
* Kan man förstå du vad som händer i de olika stegen? Hade du vetat vad du ska implementera?
* Stavning och formatering

## Tips

Några frågeställningar man kan ha hjälp av om man kör fast.

### Aktörer
* Vilka aktörer hittar ni direkt i systemet, visionen?
* Vilka aktörer bör finnas så att systemet kan fungera?
* Vilka mål (goals, needs) har dessa aktörer?
* Vilka aktörer är primära- och vilka är stödjande-aktörer?
* Finns det någon offstage-aktör som ska beaktas i systemet?
* Vilka övriga mål (goals, needs) skulle ett dylikt system kunna uppfylla, vilken aktör passar dessa mål in på?
* Vem använder systemet?
* Vem installerar systemet?
* Vem startar systemet?
* Vem underhåller systemet?
* Vem stoppar systemet?
* Vilka andra system använder systemet?
* Vem förser systemet med information?
* Händer vissa saker automatiskt vid en viss tid?


###Användningsfall
* Blir ditt användningsfall långt och komplicerat? Kanske är det helt enkelt två eller flera användningfall.
* Blir dina användningfall väldigt små? Kanske ska du slå ihop några för att bilda ett större.
* Gå igenom målen för varje aktör du har och hitta ett eller ofta flera användnignsfall som uppfyller detta mål.
* Finns det aktörer som inte har något användningsfall eller kommer Du på användningsfall som inte har någon aktör? Detta tyder på att du inte fått full koll på vad systemet ska göra och vad systemet inte ska göra vilket är helt naturligt i början på ett projekt. Man bör inte ta bort dessa ”överflödiga” delar av modellen i detta skede, utan diskutera med varandra och eventuell kund/slutanvändare för att reda ut det hela. Visar det sig att denna del av systemet ska tas bort bör man vara noga med att dokumentera detta så att man inte kommer på att man ”glömt” denna bit igen efter en tid.