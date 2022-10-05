## Unit testing
**Beskrivning:**
Assistera utveckling och körning av enhetstester, Enhetstester skrivs i samma programspråk som applikationen utvecklats i

**Input:**
Enhetstestskript, specika enheter i källkoden som ex en funktion eller en metod, Inputdata för test och förväntad output

**Output:**
Testrapport för att avgöra om specifika enheter i källkoden presterar enligt krav 

**Verktygsbehov:**
Verktyg för testsvit, testtäckningsverktyg


## DAST - verktyg för dynamisk säkerhetstestning
**Beskrivning:**
Utför DAST eller IAST-tester

**Input:**
Exekvera applikationen och underliggande OS, slumpmässig (fuzzy) input 

**Output:**
Sårbarheter, svagheter enligt statisk/dynamisk kodanalys och rekommenderade åtgärdspunkter 

**Verktygsbehov:**
DAST eller IAST-verktyg


## Integrationstest
**Beskrivning:**
Utveckla integrationstester för att testa flera mjukvarukomponenter/tjänster exempelvis externt API eller databas) och granska hur väl interaktionen fungerar däremellan

**Input:**
Skript för integrationstest, de enheter av koden som testas, testdata och förväntad output

**Output:**
Testrapport för att avgöra om de integrerade komponenterna i applikationen presterar enligt krav 

**Verktygsbehov:**
Verktyg för testsvit


## Systemtest
**Beskrivning:**
För systemtest nyttjas en svit av verktyg för att förstå hur väl interaktionen fungerar mellan hela systemet och även interaktionen med användare och externa system

**Input:**
Skript för systemtest, mjukvarusystemet och externa beroenden, Testa inputdata och förväntad output 

**Output:**
Testresultat och förutsättningarna för att avgöra om systemet fungerar enligt förväntningar

**Verktygsbehov:**
Verktyg för testsvit  


## Manuell säkerhetstest
**Beskrivning:**
Ex penetrationstest där cyberattacker simuleras gentemot systemet. CI/CD automatiserar inte testet men resultat från testen kan användas som kontrollpunkter i CI/CD

**Input:**
Körande applikation, underliggande OS, driftmiljö

**Output:**
Sårbarhetsrapport och rekommenderade åtgärdspunkter 

**Verktygsbehov:**
Diverse verktyg och skript


## Prestandatest
**Beskrivning:**
Säkerställ att applikationer preseterar väl vid förväntat belastning. Fokus för testet är applikationens responstid, pålitlighet, resursanvändning och möjligheten att anpassa kapacitet efter belastning

**Input:**
Testfall, testdata och applikationen

**Output:**
Prestandaresultat

**Verktygsbehov:**
Verktyg för testsvit, verktyg för att generera testdata


## Regressiontest
**Beskrivning:**
En typ av test med avsikt att säkerställa att nyligen gjorda ändringar i koden/applikationen inte påverkar befintlig funktionalitet

**Input:**
Funktionella och icke-funktionella regressionstestfall, Applikationen

**Output:**
Testrapport

**Verktygsbehov:**
Verktyg för testsvit


## Acceptanstest
**Beskrivning:**
Utför test som ska säkerställa att systemet är redo för driftsättning, Testar ex tillgänglighet och användbarhet, redundans/failover, systemets förmåga till återhämtning, stresstest, säkerhets och penetrationstest, Kompatibilitet och integration med andra system, Hur lätt blir det att förvalta och supportera systemet?

**Input:**
Testdata

**Output:**
Testrapport

**Verktygsbehov:**
Verktygssvit för testning, Scanning för att säkerställa efterlevnad av riktlinjer   


## Säkerställ att riktlinjer för containers efterlevs
**Beskrivning:**
Kontrollera att containers följer angivna riktlinjer

**Input:**
Container, Riktlinjer i SCAP-format

**Output:**
Rapport gällande efterlevnad av riktlinjer

**Verktygsbehov:**
Tvingad efterlevnad av riktlinjer


## Scanna efter efterlevnad av riktlinjer
**Beskrivning:**
Efterlevnadsgranskning

**Input:**
Artefakter, applikationsinstanser, systemets komponenter

**Output:**
Efterlevnadsrapport

**Verktygsbehov:**
Granskning/scanning av efterlevnad av icke-säkerhetsmässiga riktlinjer Kontroll av mjukvarulicenser. Verktyg: säkerställ efterlevnad av säkherhetsriktlinjer


## Testgranskning
**Beskrivning:**
Granska när de olika testerna körs och kontrollera lagrade testresultatet

**Input:**
Testaktivitet och testresultat

**Output:**
Testgranskning

**Verktygsbehov:**
Teststyrningsverktyg


## Utveckling av tester
**Beskrivning:**
Driftsätt applikationen i testmiljö mha infrastruktur som kod

**Input:**
Artefakter, Infrastruktur som kod

**Output:**
Körklar testmiljö

**Verktygsbehov:**
Verktyg för automatisering av konfiguration


## Funktionella tester av databas
**Beskrivning:**
Utför enhetstester och funktionella tester mot databas för att verifiera datadefinitioner, triggers, begränsningar är implementerade enligt förväntan

**Input:**
Testdata

**Output:**
Testrapport

**Verktygsbehov:**
Testverktyg för databaser

## Icke-funktionella tester av databas
**Beskrivning:**
Utför prestandatest, failover-test, Stresstesta

**Input:**
Testscenarier, testdata

**Output:**
Testrapport

**Verktygsbehov:**
Testverktyg för databaser

## Säkerhetstest av databas
**Beskrivning:**
Säkerhetsscanning, säkerhetstest

**Input:**
Testscenarier, testdata

**Output:**
Testrapport

**Verktygsbehov:**
Upptäckter av sårbarheter, Rekommenderade åtgärder

## Granska testkonfiguration
**Beskrivning:**
Spåra scanningsresultat från test och säkerhetsanalys, Ta fram åtgärdspunkter, Ta go/no go-beslut för nästa fas

**Input:**
Testresultat, rapport från säkerhetscanning och kontroll av efterlevnad enligt riktlinjer 

**Output:**
Versionshanterade testresultat, Åtgärdspunkter, Ta go/no go-beslut

**Verktygsbehov:**
Samarbetssystem, Ärendehanteringssystem, CI/CD-server, orkestrator