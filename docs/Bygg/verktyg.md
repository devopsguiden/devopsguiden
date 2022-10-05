## Byggverktyg
**Funktioner:**
Integrering med IDE, Kodstilsgranskning (linting)

**Fördelar:**
Minimerar mänskliga misstag, Sparar tid

**Input:**
Versionshanterad källkod, Artefakter (paketerad programvara, containers)

**Output:**
Kompilerade mjukvarupaket och/eller containers lagrade i artefaktregister (ex container registry så som Gitlabs inbyggda registry)

  
## Verktyg för kodstilsgranskning (linting)
**Funktioner:**
Granska källkod och varna vid misstag och potentiella misstag, buggar, formateringsfel etc. Applicerbart både på kompilerade språk och tolkade skriptspråk.

**Fördelar:**
Förbättra källkodens läsbarhet, Förhandsgranskning, Hitta syntaxfel innan körning av skript

**Input:**
Källkod och skript

**Output:**
Granska resultat
  
## Verktyg för att bygga containers
**Funktioner:**
Bygg container baserat på bygginstruktion (ex Dockerfile)

**Fördelar:**
Automatiserade containerbyggen

**Input:**
Basavbild för container, Bygginstruktionsfil (ex Dockerfile)

**Output:**
Container enligt OCI-standarden
  
## Lagringssystem för artefakter (container registry)
**Funktioner:**
Container registry

**Fördelar:**
Separera hantering av kompilerade paket och/eller containers från hanteringen av källkoden för att undvika att extern part har åtkomst till versionshanteringssystemet, Förbättrad stabilitet av byggprocesser med minskat beroende av externa lagringssystem för artefakter

**Input:**
Artefakter/Containers

**Output:**
Versionshanterade artefakter
  
## Verktyg för statisk säkerhetsanalys (SAST)
**Funktioner:**
SAST analyserar applikationens statiska kod så som källkod, bytecode och binär kod när applikationen exekveras för att upptäckta scenarion som kan visa på svagheter

**Fördelar:**
Upptäck sårbarheter tidigt, Kontinuerlig bedömning under pågående utveckling

**Input:**
Källkod, Kända sårbarheter och svagheter

**Output:**
Rapport från analys och rekommenderade åtgärder
  
## Kontroll och redovisning av beroenden/mjukvarubibliotek (BOM - bill of materials)
**Funktioner:**
Identifiera sårbarheter i beroenden baserat på publicerade sårbarheter

**Fördelar:**
Höj applikationens säkerhet, Hantera riskmoment i värdekedjan (supply chain)

**Input:**
Lista över mjukvarubibliotek som applikationen är beroende av

**Output:**
Sårbarhetsrapport