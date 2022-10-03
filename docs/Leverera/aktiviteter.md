# Aktiviteter

## Release go / no- go beslut
**Beskrivning:**
Säkerställ efterlevnad av riktlinjer, besluta huruvida artefakt/paket är redo för driftsättning i produktionsmiljö 

**Input:**
Designdokumentation, Testrapporter, Säkerhetstester och rapporter, Artefakter

**Output:**
Go / no-go beslut; Artefakter taggas med release tagg om  go-beslut tagits

**Verktygsbehov:**
CI/CD-server/orkestrator


## Driftsätt release
**Beskrivning:**
Ladda upp releaseartefakter till artefaktrepositorie

**Input:**
Release-paket

**Output:**
Ny release i artefaktrepositorie (ex containerregister)

**Verktygsbehov:**
Artefaktrepositorie (ex containerregister)


## Replicera artefakter
**Beskrivning:**
Replicera nya releaseartefakter till regionala containerregister

**Input:**
Artefakt/container

**Output:**
Artefakter i alla regionala containerregister

**Verktygsbehov:**
Containerregister