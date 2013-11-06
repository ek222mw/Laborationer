## Inledning
I denna laboration skall du komma igång med versionshantering och sedan öva på black- och white-box testning. Du skall givet en applikation skapa ett antal testfall. Dessa testfall skall användas för att “black box”-testa applikationen och göra en testrapport. Du skall sedan inspektera källkoden för en del av applikationen (en klass som vi tillhandahåller) och skapa ett antal automatiska enhetstester. Använd dina enhetstester för att testa klassen och åtgärda alla fel du finner.

Arkiv (zip) med exekverbarfil, källkod, samt manual/specifikation och en tutorial över Testning i VisualStudio 2012.

VS2012_Test_Tutorial.mp4 2012-11-228.51 MB
Triangel.zip 2012-11-135.82 kB
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

### VPN och Versionshantering
1. Koppla upp dig på vpn200 enligt instruktionerna.
2. Installera klientmjukvara för subversion, t.ex. TortoiseSVN eller motsvarande om du inte redan har tillgång till det. subversion.apache.org
3. Läs introduktionstexten till versionshantering samt de delar av din klients hjälpdokumentation som du känner att du behöver.
4. Till kursen finns ett respositorium på http://172.16.202.2/1dv404/svn gör en lokal kopia (checkout) av detta respositorium på din dator.
5. Lägg in en underkatalog till “Trunk” med ditt användarnamn.
6. Lägg in en underkatalog till din katalog med namn “labb1″.
7. Lägg in en testfil (labb1.txt) med något innehåll din “labb1″ mapp.

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

[Mono](http://www.mono-project.com/)<br/>
[Code coverage](http://www.mono-project.com/Code_Coverage)<br/>
[NUnit](http://www.nunit.org/)<br/>
[Stack Overflow](http://stackoverflow.com/questions/tagged/mono+nunit)
