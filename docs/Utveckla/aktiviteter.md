## Systemutveckling
**Beskrivning:**
Skapande av källkod

**Input:**
Källkodsinmatning

**Output:**
Källkod

**Verktygsbehov:**
Integrerad utvecklingsmiljö (IDE)


## Utveckling av Infrastruktur som kod
**Beskrivning:**
Kodifiering av infrastrukturkomponenter och uppskapande av skript

**Input:**
Källkodsinmatning

**Output:**
Källkod

**Verktygsbehov:**
Integrerad utvecklingsmiljö (IDE)


## Utveckla kodifierad säkerhetsefterlevnad (policy as code)
**Beskrivning:**
Säkerställ efterlevnad av riktlinjer, utveckla skript

**Input:**
Källkodsinmatning

**Output:**
Källkod

**Verktygsbehov:**
Integrerad utvecklingsmiljö (IDE)


## Utveckling av testmetodik och testmiljöer
**Beskrivning:**
Utveckla testmetoder, testdata, testskript, konfiguration av testscenarion för specifika verktyg

**Input:**
Testplanering

**Output:**
Dokumenterade testflöden, testdata, testskript

**Verktygsbehov:**
Integrerad utvecklingsmiljö (IDE), testverktyg


## Databasutveckling
**Beskrivning:**
Implementera datamodellen mha ett datadefinitionsspråk eller datastruktur som stödjs av databasen, Implementera avlösare (triggers), vyer eller applicerbara skript, Implementera testskript, skrift för att generera testdata

**Input:**
Datamodell

**Output:**
Databasartefakter (datadefinitioner, triggers/avlösare, definierade vyer, testdata, skript för generering av testdata, testskript etc)

**Verktygsbehov:**
Integrerad utvecklingsmiljö (IDE) eller system för databashantering (ex SQL Server Management Studio - SSMS)


## Incheckning av källkod (code commit)
**Beskrivning:**
Checka in källkod i versionshanteringssystem

**Input:**
Källkod

**Output:**
Versionshanterad källkod

**Verktygsbehov:**
Depå för versionshanterad källkod (code repository)


## Scanning av incheckad källkod
**Beskrivning:**
Granskar kodändringar för att upptäcka känslig information innan incheckning  av koden, Om misstänkta sårbarheter upptäcks notifieras utvecklaren och incheckning blockeras

**Input:**
Lokalt incheckad källkod

**Output:**
Upptäckt av sårbarheter i källkod 
och varningar

**Verktygsbehov:**
Säkerhetsplugin till versionshanteringssystem 
(git) eller IDE


## Kodgranskning
**Beskrivning:**
Genomför granskning av all källkod, Även parprogrammering är tillämpbar

**Input:**
Källkod

**Output:**
Granskningskommentarer

**Verktygsbehov:**
Verktyg för granskning av kodkvalitet
  

## Dokumentation
**Beskrivning:**
Detaljerad dokumentation av implementering

**Input:**
Användarinput, Källkod

**Output:**
Dokumentation, automatiskt genererad API-dokumentation

**Verktygsbehov:**
Integrerad utvecklingsmiljö (IDE) eller annat verktyg för hantering av dokumentation


## Statisk källkodsanalys före inchecking
**Beskrivning:**
Scannar och granskar källkoden i takt med att utvecklaren matar in den, Notifiera utvecklare om potentiella svagheter och rekommendera åtgärder

**Input:**
Källkod, Kända sårbarheter

**Output:**
Upptäckt av sårbarheter i källkod

**Verktygsbehov:**
Säkerhetsplugin till IDE


## Förstärkning av container och VM-säkerhet
**Beskrivning:**
Förstärk leveranser inför driftsättning i produktion

**Input:**
Körning av virtuell maskin eller container

**Output:**
Sårbarhetsrapport och rekommenderade åtgärder

**Verktygsbehov:**
Verktyg för säkerhetsgranskning av containers, Verktyg för att säkerställa efterlevnad av riktlinjer