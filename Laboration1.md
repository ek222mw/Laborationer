## Inledning
I denna laboration skall du komma igång med versionshantering och sedan öva på black- och white-box testning. Du skall givet en applikation skapa ett antal testfall. Dessa testfall skall användas för att “black box”-testa applikationen och göra en testrapport. Du skall sedan inspektera källkoden för en del av applikationen (en klass som vi tillhandahåller) och skapa ett antal automatiska enhetstester. Använd dina enhetstester för att testa klassen och åtgärda alla fel du finner.

Arkiv (zip) med exekverbarfil, källkod, samt manual/specifikation och en tutorial över Testning i VisualStudio 2012.

[VS2012_Test_Tutorial.mp4 2012-11-22 8.51 MB](http://orion.lnu.se/pub/education/course/1DV404/ht12/filer/labb/labb1/VS2012_Test_Tutorial.mp4)

[Triangel.zip 2012-11-13 5.82 kB](http://orion.lnu.se/pub/education/course/1DV404/filer/labb/labb1/Triangel.zip)

För närvarande finns kod för C# och Java (tack till Johannes Löhnn för Javadelen). Koden har samma funktionalitet och struktur men innehåller naturligtvis mindre språkspecifika skillnader. Välj det språk du själv känner dig mest bekväm med dock står man lite mer på egen hand om man väljer något annat än C# och VisualStudio som utvecklingsmiljö.

## Deadline och redovisning

Uppgiften skall redovisas senast v.48
Uppgiften skall godkännas senast v.49

Följande skall redovisas och finnas versionshanterat i ditt github konto:

* Dina “black box”-testfall (med motivering/beskrivning, input och förväntad output)
* Utfall/rapport av “black box”-testning (faktisk output) jämförelse med förväntad output samt en sammanfattning av de fel du hittade (om du hittade några)
* Dina automatiska-enhetstester (som även skall kompileras och exekveras under redovisning)
* Den åtgärdade klassen (för chans till högre betyg)

## Genomförande

### GitHub och Versionshantering

1. Logga först och främst in på GitHub och besök uppgiftens repro: [] (https://github.com/1dv404/Uppgift-1/)
2. För att göra en "fork" av reprot så klickar du på "Fork" i övre högra delen av webbsidan.
![Fork][github-fork]
3. Nu finns en kopia av ursprungsreprot på ditt GitHub-konto.
4. Använd valfri git client för att göra en clon av ditt repro till den lokala datorn du sitter och jobbar på.


### Blackbox-testning

1. Analysera applikationen och skapa ett antal testfall. Använd t.ex. ekvivalensklasser och gränsvärdesanalys.
2. Utför dina testfall, d.v.s. kör applikationen och mata in den indata du skapat enligt ovan.
3. Granska och dokumentera utfallet (lyckat/misslyckat ev. kommentar).
4. Upprepa steg från steg 1 tills du är nöjd.
5. Analysera ev. felaktigheter och sammanfatta i din testrapport.

### Whitebox-testning
1. Analysera koden för den givna klassen (Triangle).
2. Implementera enhetstester som täcker funktionaliteten i klassen.
3. Utför enhetstesterna och korrigera de fel/defekter/brister du hittar om du satsar på betyg över 3.
4. Upprepa steg från steg 1 tills du är nöjd.

#### Tips
För att kunna förstå koden och korrigera ev. defekter så kan det vara bra att repetera Pythagoras sats och lite om det tvådimensionella Kartesiska koordinatsystemet.

Laborationen bör gå att genomföra med mono och nunit (för den som inte vill köra visual studio). Det är dock upp till dig att lista ut hur man gör. Används (t.ex.) följande resurser som utgångspunkt:

* [Mono](http://www.mono-project.com/)
* [Code coverage](http://www.mono-project.com/Code_Coverage)
* [NUnit](http://www.nunit.org/)
* [Stack Overflow](http://stackoverflow.com/questions/tagged/mono+nunit)

[github-fork]: https://raw.github.com/1dv404/Laborationer/master/pics/github-fork.png