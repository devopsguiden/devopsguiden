## Styrsystem för Virtualisering
**Funktioner:**
Styrning av VM-instanser, bevakning av resurser

**Fördelar:**
Centraliserad VM-styrning, bevakning, anpassa kapacitet efter behov

**Input:**
Specifikation av VM-instans och riktlinjer för bevakning

**Output:**
Virtuell maskin i drift
  
## CNCF-certifierad Kubernetes distribution
**Funktioner:**
Gruppera containers i "pods", Hälsocheck och självläkning, Horisontell kapacitetsjustering av infrastruktur, Automatisk styrning av containerinstanser, DNS styrning, Lastbalansering, Rullande uppdateringar och rollback, Bevaka resursanvändning och loggar

**Fördelar:**
Förenklad drift mha automatiserad driftsättning och uppdateringar, Skala infrastrukturresurser och applikationer i realtid, Spara pengar genom att optimera användningen av infrastrukturresurser

**Input:**
Specifikation av containerinstanser och riktlinjer för bevakning/larmsättning

**Output:**
Container i drift
  
## Datamaskeringsverktyg
**Funktioner:**
Dölj personligt identifierbar information och annan konfidentiell data

**Fördelar:**
Dataintegritet, Reducera risk för dataläckage

**Input:**
Originaldata

**Output:**
Maskerad data
  
## Verktyg: Kryptering av databas
**Funktioner:**
Kryptera data vid transport

**Fördelar:**
Dataintegritet och säkerhet, Reducera risk för dataläckage

**Input:**
Originaldata

**Output:**
Krypterad data
  
## Automationsverktyg för databas
**Funktioner:**
Automatisera manuella arbetsuppgifter kopplade till databasdrift (exempelvis driftsättning, uppgraderingar, upptäckt och felsökning av missförhållanden, återhämtning efter krasch, backupkörningar m.m.)

**Fördelar:**
Förenklar databasdrift och minimera fel pga den mänskliga faktorn

**Input:**
Databaseartefakter, Data; Körstatus och händelser

**Output:**
Statusrapport, varningar, larm
  
## Automationsverktyg för konfiguration
**Funktioner:**
Kör konfigurationsskript för att provisionera infrastruktur, säkerhetsriktlinjer, miljöer och applikationens komponenter

**Fördelar:**
Automatisera konfiguration, Pålitlig och stabil provisionering av infrastruktur

**Input:**
Konfigurationsskript och data som beskriver önskad infrastruktur

**Output:**
Provisionerad infrastruktur för drift
  
## Service mesh (ett kluster av mikrotjänster)
**Funktioner:**
Möjliggör uppskapande av ett kluster av tjänster med lastbalansering, tjänst-till-tjänst-autenticering och bevakning

**Fördelar:**
Stöd för mikrotjänster, tvingad kryptering mellan tjänster

**Input:**
Kontrollpanel, riktlinjer för routing av kommunikationen mellan mikrotjänster, certifikat för autentisering m.m.

**Output:**
Statusrapport från tjänster, routad kommunikationsdata m.m.