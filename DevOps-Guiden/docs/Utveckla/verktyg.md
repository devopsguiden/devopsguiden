# Verktyg

  
## Integrerad Utvecklingsmiljö (IDE)
**Funktioner:**
Integrerad utvecklingsmiljö, Intelligent automatisk kodkomplettering, Kompilator eller kodtolk, Debugger, Byggautomation (integration med byggverktyg)

**Fördelar:**
Visuell representation förbättrar effektivitet, Snabbare och effektivare systemutveckling, Snabbare åtgärd av buggar, Reproducerbara byggen mha skript

**Input:**
Inmatning av källkod 

**Output:**
Källkod

  
## Integrerad Utvecklingsmiljö (IDE) och säkerhetsplugin
**Funktioner:**
Scanna och granska källkod i takt med att den matas in, notifiera utvecklaren om potentiella sårbarheter i källkoden. Potentiellt kan verktyget även föreslå förbättringar

**Fördelar:**
Åtgärda sårbarheter i källkod och hjälp utvecklare att arbeta på ett mer defensivt sätt

**Input:**
Källkod, Kända sårbarheter

**Output:**
Upptäcka sårbarheter i källkod

  
## Depå för versionshanterad källkod (code repository)
**Funktioner:**
Versionshantering av källkod, Förgrening och integrering, Gemensam kodgranskning

**Fördelar:**
Jämför filer, identifiera skillnader innan integrering/leverans, håll reda på byggen av applikationer

**Input:**
Källkod, konfiguration (infrastruktur som kod)

**Output:**
Versionshanterad källkod

  
## Lokalt installerat versionshanteringssystem eller integrerad Utvecklingsmiljö (IDE)
**Funktioner:**
Identifiera förändringar på uppseendeväckande ställen så som SSH-nycklar, auktoriseringstoken, lösenord eller annan känslig information innan förändringarna laddas upp till en central versionshanteringsstjänst

**Fördelar:**
Avhjälper att lösenord och annan känslig data lagras tillsammans med den versionshanterade källkoden

**Input:**
Källkod som skapas av utvecklaren på dennes egen dator 

**Output:**
Upptäckta varningar och brister

  
## Verktyg för granskning av kodkvalitet
**Funktioner:**
Se kodförändringar, identifiera defekter, stöt bort eller godkänn förändringar, skapa upp kommentarer på berörda rader i källkoden, Bestäm regler för granskning och notifiera per automatik för att tillse att granskning utförs inom ett rimligt tidsintervall

**Fördelar:**
Automatisera granskningsprocessen vilket minimerar arbetstid för manuell granskning

**Input:**
Källkod

**Output:**
Granska resultat (slå ifrån eller godkänn) kommentarer i källkoden