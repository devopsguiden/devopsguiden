## Release go / no- go beslut
**Beskrivning:**
Säkerställ efterlevnad av riktlinjer, besluta huruvida artefakt/paket är redo för driftsättning i produktionsmiljö 

**Input:**
Designdokumentation, Testrapporter, Säkerhetstester och rapporter, Artefakter

**Output:**
Go / no-go beslut; Artefakter taggas med release tagg om go-beslut tagits

**Verktygsbehov:**
CI/CD-server/orkestrator


## Driftsätt release
**Beskrivning:**
Ladda upp releaseartefakter till artefaktrepositorie

**Input:**
Release-paket

**Output:**
Ny release i ex ett containerregister (eller annan databas för releasepaket)

**Verktygsbehov:**
Container registry så som Harbour eller det inbyggda i Gitlab (eller motsvarande)


## Replicera artefakter
**Beskrivning:**
Replicera nya releasepaket till regionala containerregister (för storskalig produktion som spänner över stora geografiska områden)

**Input:**
Artefakt/container

**Output:**
Artefakter i alla regionala containerregister

**Verktygsbehov:**
Multipla containerregister i olika geografiska områden