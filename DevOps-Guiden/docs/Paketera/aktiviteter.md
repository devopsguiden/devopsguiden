# Aktiviteter

## Bygg
**Beskrivning:**
Kompilera och länka

**Input:**
Källkod, beroenden

**Output:**
Binära artefakter

**Verktygsbehov:**
Byggverktyg/byggserver, Kodstilsgranskning (linting-plugin), Artefaktregister/containerregister


## Verktyg för scanning och test av applikationens säkerhet 
**Beskrivning:**
Genomför SAST av mjukvarusystemet (Static Application Security Testing)

**Input:**
Källkod, kända sårbarheter och svagheter

**Output:**
Rapport från SAST och rekommenderade åtgärder

**Verktygsbehov:**
SAST-verktyg


## Granskning av sårbarheter i beroenden
**Beskrivning:**
Identifiera publicerade sårbarheter i beroenden 

**Input:**
Lista över mjukvarubibliotek som applikationen är beroende av

**Output:**
Sårbarhetsrapport

**Verktygsbehov:**
Verktyg för att granska sårbarheter i beroenden


## Bygg containeravbild
**Beskrivning:**
Paketerar alla nödvändinga komponenter (OS, källkod, bibliotek etc) i en säkerhetsanpassad container

**Input:**
Basavbild för container, Bygginstruktionsfil (ex Dockerfile)

**Output:**
Containeravbild

**Verktygsbehov:**
Byggverktyg/byggserver för containeravbilder


## Releasepaketering
**Beskrivning:**
Paketera binära artefakter, container- eller VM-avbilder, Konfigurationsskript för infrastruktur, Testskript, Dokumentation, Checksummor, Digitala signaturer, Release notes som paket

**Input:**
Binära artefakter, skript, Dokumentation, Release anteckningar

**Output:**
Paketerad release med checksumma och digital signatur

**Verktygsbehov:**
Verktyg för att paketera releaser


## Lagra artefakter (ex containeravbilder)
**Beskrivning:**
Lagra artefakter i en central databas

**Input:**
Binära artefakter, databasartefakter, skript, Dokumentation, Containeravbilder

**Output:**
Versionshanterade artefakter 

**Verktygsbehov:**
Databas för artefakter (ex. Gitlabs containerregister)


## Granskning av byggkonfiguration
**Beskrivning:**
Historik över byggresultat, SAST och analys/rapport av beroenden, Skapa upp åtgärdspunkter, Ta "Go or no go"-beslut för nästa fas

**Input:**
Byggresultat, SAST-rapport, Rapport från beroendegranskning

**Output:**
Versionshanterade byggrapporter, Åtgärdspunkter, Go/No go-beslut

**Verktygsbehov:**
Samarbetssystem (ex Office365), Ärendehanteringssystem, CI/CD-orkestrator