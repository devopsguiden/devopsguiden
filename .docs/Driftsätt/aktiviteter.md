## Nedladdning av containers (eller andra artefakter)
**Beskrivning:**
Ladda ner levererade releasepaket från en central databas för artefakter (ex Gitlabs containerregister)

**Input:**
Begärd nedladdning av artefakt

**Output:**
Begärd artefakt

**Verktygsbehov:**
Central databas för artefakter (ex Gitlabs containerregister)


## Automatiserad provisionering av infrastruktur
**Beskrivning:**
Automatiserad provisionering av infrastruktur så som mjukvarudefinierat nätverk, brandväggar, DNS, loggningssystem, rättighetsstyrning för användare m.m.

**Input:**
Skript för infrastrukturprovisionering, "recept", manifest (ex. kubernetes yaml), playbooks (ex Ansible playbooks)

**Output:**
Provisionerad infrastruktur

**Verktygsbehov:**
Automationsverktyg


## Instantiera en länkad klon av VM-masteravbild
**Beskrivning:**
Instantiera en VM-instans genom att skapa en länkad klon av masteravbild

**Input:**
Masteravbild, nya instansparametrar för VM

**Output:**
Ny VM-instans

**Verktygsbehov:**
Virtualiseringsplattform


## Leverera container till containerregister (ex i Gitlab)
**Beskrivning:**
Ladda upp en container med förstärkt säkerhet och associerade artefakter till containerregister 

**Input:**
Container med förstärkt säkerhet

**Output:**
Ny containerinstans

**Verktygsbehov:**
CNCF-certified Kubernetes distribution, containerregister (eller motsvarande databas för artefakter)


## Säkerhetsscanning efter driftsättning
**Beskrivning:**
Säkerhetsscanning av system och infrastruktur

**Input:**
Åtkomst till systemets komponenter och infrastruktur

**Output:**
Upptäckter av sårbarheter

**Verktygsbehov:**
Verktyg för säkerställande att riktlinjer efterlevs


## Check efter driftsättning
**Beskrivning:**
Kör automatiska tester för att säkerställa att den grundläggande funktionaliteten i systemet fungerar som förväntat

**Input:**
"Smoke test" och testskript

**Output:**
Testresult

**Verktygsbehov:**
Testskript


## Installation och driftsättning av databas och tillhörnade artefakter 
**Beskrivning:**
Databasinstallation, Uppsättning av redundanta kluster, Driftsätt databasartefakter och ladda in data

**Input:**
Artefakter i central databas, Data

**Output:**
Köra databassystemet

**Verktygsbehov:**
Databas för containers/artefakter, verktyg för automation av databasaktiviteter, datamaskering och kryptering vid behov