Testning av mjukvara är utmanande och tidskrävande. I iterativa projekt där varje iteration avslutas med en leverans av systemet under utveckling så har testning en mycket mer framträdande roll och det är viktigt att både komma igång med testningen och att kunna testa effektivt.

Målet med denna uppgift är att öva på att skriva testfall för det krav som du gjort ett detaljerat användningsfall för (alltså testfall för ett krav) i föregående laboration.

## Deadline

Uppgiften skall redovisas senast v.51

Uppgiften skall godkännas senast v.1


Uppgiften redovisas genom att testfall och krav visas för och diskuteras med handledare.

## Förberedelse

Läs kap 21 i kurslitteraturen samt föreläsningsmaterialet kring testning så är du väl förberedd på att klara laborationens moment.

## Genomförande

Konstruera ett antal testfall för det detaljerade krav du specificerat enligt uppgift 3 (du bör således vara godkänd på denna uppgift innan du gör detta moment)

Tänk på att testa så komplett som möjligt, alla scenarios och viktiga val i ditt användningsfall ska testas. Om du behöver förändra, förbättra de ingående kravet så gör det.
Se till att dina krav går att komma åt via din fork av [https://github.com/1dv404/Uppgift-234](https://github.com/1dv404/Uppgift-234).


### Exempel
Nedan följer ett enkelt exempel på ett krav och de testfall som testar kravet

#### UC1 Autentisiera Användare
##### Huvudscenario

1. Starar när en användare vill atuentisiera sig som en roll
2. Systemet ber om användarens användarnamn och lösenord
3. Användaren anger användarnamn och lösenord.
4. Systemet autentisierar användaren som en användarroll (admin eller styrelsemedlem) och presenterar att autentisieringen lyckades.

##### Alternativa scenarios

4a. Användaren kunde inte autentisieras
1. Systemet presenterar felmeddelande
2. Gå till steg 2 i huvudscenario.

För att testa alla scenarios och val i detta användningsfall behövs minst 3 testfall (1. aut. som admin, 2. aut. som styrelsemedlem, felaktig aut). Detta är dock givetvis inte en komplett testning då det kan finnas många intressanta indata att fundera kring.

#### Testfall
##### TF 1.1 Huvudscenario aut. som admin

1. Gå till inloggninssidan (www.exempel.test/login);
2. Inloggningsformulär presenteras
3. Användarnamn: admin, Lösenord: nimda
4. Lyckad inloggning som admin

##### TF 1.2 Huvudscenario; aut. som sturelsemedlem

1. Gå till inloggninssidan (www.exempel.test/login)
2. Inloggningsformulär presenteras
3. Användarnamn: user, Lösenord: resu
4. Lyckad inloggning som styrelsemedlem

##### TF 1.3 Alt. Scenario 4a; misslyckad aut

1. Gå till inloggninssidan (www.exempel.test/login)
2. Inloggningsformulär presenteras
3. Användarnamn: error, Lösenord: rorre
4a1. Misslyckad inloggning Felmeddelande presenteras.
4a2. Inloggningsformulär presenteras

Vissa delar återupprepas i alla testfall och man vill kanske därför ha något smart sätt att skriva detta (t.ex. en tabell) men i grund och botten är det detta vi vill komma åt. Dvs vad ska man som testare skriva in och vad ska man som testare kunna se som resultat för att kunna avgöra om testfallet är lyckat eller ej.