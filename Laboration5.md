I denna laboration så skall du genomföra minst en SCRUM sprint och utveckla en liten enkel applikation. Du ska givet ett antal “user stories” planera din sprint, uppskatta dina “tasks” och kontinuerligt uppdatera din “sprint backlog” och ditt “burndown chart” allteftersom du arbetar med applikationen.

**OBS! Du inleder laborationen med att planera din sprint och måste således ha kunskap kring SCRUM innan du påbörjar implementationen.**

## Deadline och Redovisning

Laborationen skall godkännas senast v3.

Vid redovisning så ska applikationen visas, källkoden redovisas samt sprint backlog och burndown chart presenteras. För högre betyg skall du redogöra för hur du har använt SCRUM och de lärdomar/förändringar du gjort i ditt arbetssätt.

## Föreslå ändringar

Denna handledning ligger på [GitHub](https://github.com/1dv404/Laborationer) om du vill föreslå ändringar eller hålla koll på vad de senaste uppdateringarna innebar.


## Genomförande

1. Läs igenom labbhandledningen
2. Kolla föreläsningen om Scrum
3. Bestäm hur många sprints du ska köra och din sprintlängd i dagar (t.ex. 5-10), se dock till att du kan redovisa innan deadline.
4. Skapa en prioriterad Product Backlog baserat på nedanstående krav
5. Skapa en Sprint Backlog baserat på nedanstående krav. Tänk dock på att du är fri att lägga in alla uppgifter du anser nödvändiga för att slutföra projektet, t.ex. test.
6. Skatta dina uppgifter med “Planning Poker” konceptet, se över din totalsumma så att den inte överskrider den tid du faktiskt kan arbeta.
7. Summan av dina skattade tider dag 1 är utgångspunkten för beräkning av ideal tid och helt enkelt så många timmar du anser dig tror att du behöver.
8. Skapa ett Burndown Chart
9. Din Sprint Backlog och Sprint Burndown Chart ska versionshanteras t.ex. i subversion under “trunk/anvnamn/labb5/”
10. Arbeta med dina uppgifter i din sprint backlog
11. Uppdatera Sprint Backlog baserat på ny kunskap varje dag du arbetar, ditt Burndown Chart ska då givetvis också uppdateras.
12. Se till att versionshantera förändringar
13. Repetera från 10 tills din sprint är färdig
14. Gå igenom din applikation, uppfyllde du målen? Kunde du jobbat mer, mindre? Vad har ändrats i kraven (product backlog)? Något som ska bort eller läggas till i kraven? Vad ska prioriteras om? Vad gick bra vad gick dåligt? (Sprint Review, Sprint Retrospective)
15. Repetera från 5 tills ditt projekt är färdigt
16. Kontakta handledare och redovisa


### Applikationen

Du har här ett val; om du läser kursen Webteknik I parallellt och satsar på betyg 4 eller 5 i den kursens projektuppgift så kan du istället välja att göra din sprint för det projektet. I annat fall är det nedanstående krav som gäller:

Applikationen som skall utvecklas är ett enkelt medlemsregister i form av en grafiskt enkel applikation (t.ex. en C# konsolapplikation).

All källkod skall vara väl strukturerad och följa en genomgående kodstandard.

### User Stories

1. Som användare vill jag kunna registrera nya medlemmar med förnamn, efternamn och telefonnummer, ett unikt medlemsnummer skall automatiskt tilldelas medlemmarna.

2. Som användare vill jag kunna få ut en lista på alla medlemmar så att jag enkelt kan få en överblick över alla medlemmar.

3. Som användare vill jag kunna ändra på en befintlig medlem så att jag kan korrigera eventuella fel.

4. Som användare vill jag kunna ta bort en befintlig medlem ur registret så att jag inte behöver hålla reda på gamla medlemmar.

5. Som användare vill jag kunna se en specifik medlems information på ett tydligt sätt så att jag kan få detaljerad information om en medlem.

### Sprint Backlog

I din sprint backlog så för du in alla “tasks” du planerar att genomföra för att nå fram till en fungerande produkt. Alla “tasks” skall skattas (använd 0, 1, 2, 3, 5, 8, 13, 20, 40, 100) när de förs in och uppdateras när arbete skett. Om en “task” uppskattas vara krävande (i detta fall mer än 5) så skall den delas upp i mindre “tasks” så snart du har mer information/känsla för vad som behöver göras.

Utgå ifrån de user stories som presenterats ovan och dela upp dessa i lämpliga “tasks”. Tänk dock på att det kan finnas “tasks” som inte är direkt kopplade till en “user story”.

Ett utökning av sprint backlock vi ska göra i denna kurs är att lägga in faktiskt arbetad tid för varje “task”. Dvs i slutet på sprinten vill vi veta hur mycket du faktiskt har arbetat och hur långt tid som varje “task” egentligen tog.

Ett enkelt sätt att hantera sin “sprint backlog” är helt enkelt att använda en tabell i ett kalkylark. Med en liknande struktur.

<table>
<tr><th>Task</th><th>Day 1</th><th>Day 2</th><th>...</th><th>Total Time Worked</th></tr>
<tr><td>A</td><td>3</td><td>5</td><td>...</td><td>...</td></tr>
<tr><td>B</td><td>5</td><td>1</td><td>...</td><td>...</td></tr>
<tr><td>...</td><td></td><td></td><td>...</td><td>...</td></tr>
<tr><td>Estimated Time</td><td>...</td><td>...</td><td>...</td><td>...</td></tr>
<tr><td>Ideal Time</td><td>...</td><td>...</td><td>...</td><td>...</td></tr>
</table>

Varje dag går du igenom dina “tasks” och uppdaterar ditt “burndown chart”. I de fall du har större inblick i uppgiften så tilldelar du den ett nytt skattat värde. 0 innebär att “tasken” är “done”. Det är även troligt att du glömt någon uppgift när du startade sprinten och då får du föra in denna i efterhand med skattad storlek “0″ från första dan och fram till nuvarande dag då du gör den verkliga skattningen.

Tänk på att tanken med ett burndownchart är att kontinuerligt visa hur mycket du uppskattar att det är kvar att göra. Den ideala kurvan visar hur mycket du trodde att det var att göra från dag 1. Den verkliga kurvan kommer alltså att avvika från den ideala kurvan både positivt och negativt allteftersom du får större inblick i uppgiften.

Ett vanligt misstag är att man tar det uppskattade värdet och helt enkelt bara subtraherar den arbetade tiden, istället för att göra en ärlig uppskattning av hur mycket man bedömer att det är kvar att göra.