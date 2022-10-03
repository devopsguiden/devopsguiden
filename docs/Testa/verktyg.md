## Testverktyg under utveckling 
**Funktioner:**
Hjälpmedel för hantering av testscenarion, testskript och utveckling av testdata. Olika verktyg beroende på typ av test och typ av applikation.

**Fördelar:**
Ökad automation och testfrekvens

**Input:**
Testplanering

**Output:**
Testscenarion, testskript, testdata
  
## Verktyg för att generera testdata
**Funktioner:**
Generera testdata för systemet (t.ex. nätverksanrop och data i databas)

**Fördelar:**
Förbättrad träffsäkerhet i tester

**Input:**
Testscenarier, testdata

**Output:**
Data från systemet som testas
  
## Testsvit
**Funktioner:**
Svit av verktyg för att utföra enhets-, integrations-, prestanda-, acceptanstest m.m. Generera testrapport. Kan vara olika verktyg för olika typer av tester

**Fördelar:**
Automatisera tester i högre grad, Tidsbesparing

**Input:**
Testscenarier, testdata, testskript

**Output:**
Testrapport, testresultat
  
## Verktyg för att se testtäckning
**Funktioner:**
Mäter hur mycket av källkoden som testas

**Fördelar:**
Visar testernas precision

**Input:**
Källkod, automatiserade tester

**Output:**
Procent av källkoden som testas
  
## Teststyrningsverktyg
**Funktioner:**
Kravhantering, Utforma testfall enligt krav, Planera testaktiviteter, Förvalta testmiljö, Bevakning av teststatus och resultat

**Fördelar:**
Effektivare testprocesser och ökat samarbeta kring testning

**Input:**
Krav, testfall, testresultat

**Output:**
Hur tester har fortskridit, Statistik från testresultat
  
## Efterlevnad av krav
**Funktioner:**
Efterlevnad av krav som inte är relaterade till säkerhet

**Fördelar:**
Säkerställer efterlevnad av krav

**Input:**
Artefakter

**Output:**
Rapport
  
## Kontroll av mjukvarulicenser
**Funktioner:**
Inventera mjukvarulicenser, granska efterlevnad

**Fördelar:**
Efterlevnad enligt mjukvarulicenser och hantering av mjukvarutillgångar

**Input:**
Info om köpta licenser, Mjukvaruinstanser i drift 

**Output:**
Efterlevnadsrapport
  
## DAST - verktyg för dynamiska säkerhetstester
**Funktioner:**
Analyserar applikationer under körning och kan på ett dynamiskt sätt identifiera sårbarheter och eventuella svagheter i miljön

**Fördelar:**
Upptäck sårbarheter/svagheter under körning i specifika miljökonfigurationer. Identifiera och åtgärda problem i den kontinuerliga integrationen

**Input:**
Kör applikation, varierad/slumpmässig input (fuzz test)

**Output:**
Rapport från dynamiskt scannad kod och rekommenderade åtgärder
  
## IAST - Interactive Application Security Test
**Funktioner:**
Granska kod för säkerhetsbrister medan applikationen kör automatiska tester, manuella tester eller annan aktivitet som interagerar med applikationen

**Fördelar:**
Testresultat som bidrar till snabb och effektiv felsökning och för upptäckt av sårbarheter

**Input:**
Exekverad applikation, OS, varierad/slumpmässig input (fuzz test)

**Output:**
Rapport och rekommenderade åtgärder

  
## Verktyg för bedömning av containersäkerhet
**Funktioner:**
Scanna och granska containeravbild

**Fördelar:**
Förenklar arbetet att säkra upp container

**Input:**
Containeravbilder och exekverade containrar

**Output:**
Sårbarhetsrapport och rekommenderade åtgärder
  
## Säkerställ efterlevnad av riktlinjer för containerriktlinjer
**Funktioner:**
Stöd för SCAP - Security Content Automation Protocol och riktlinjer för konfiguration av containers

**Fördelar:**
Automatiskt säkerställande av riktlinjer

**Input:**
Riktlinjer i SCAP-format

**Output:**
Rapport gällande efterlevnad av riktlinjer
  
## Verktyg: Efterlevnad av säkerhetsriktlinjer
**Funktioner:**
Beror på organisationens säkerhetsriktlinjer.

**Fördelar:**
Säkerhetsriktlinjer är inte blott ett dokument bra formuleringar.

**Input:**
Containeravbilder, policy as code

**Output:**
Sårbarhetsrapport och rekommenderade åtgärder

  
## Vektyg: Test av nätverkssäkerhet
**Funktioner:**
Simulera realistisk nätverkstrafik, DDOS, attacker, slumpmässiga anrop

**Fördelar:**
Validera systemets säkerhet, ökat försvar mot attacker, reducerad risk att systemets funktioner degraderas

**Input:**
Testkonfiguration

**Output:**
Testtrafik
  
## Testverktyg för databas
**Funktioner:**
Verktyg som möjliggör databastest, Inkluderar att generera testdata, Funktionella tester mot databas, Prestandatest av databas.

**Fördelar:**
Automatiska/semiautomatiska databastester

**Input:**
Testdata, testscenarion

**Output:**
Testresultat
  
## Verktyg: Scanna och testa databassäkerhet
**Funktioner:**
Upptäcka sårbarheter/säkerhetsbrister i databas så som svaga lösenord, kända risker i konfiguration, Ej applicerade uppdateringar/säkerhetspatchningar, Verktyg för att testa injicering av SQL, test av dataåtkomst, test av användaråtkomst, DOS - denial of service test

**Fördelar:**
Reducera säkerhetsrisker

**Input:**
Testscenarier, testdata

**Output:**
Upptäckta sårbarheter, Rekommendera åtgärdspunkter