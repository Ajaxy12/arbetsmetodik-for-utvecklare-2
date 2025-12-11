# 📊 Grupprapport - Webbshop Projekt

## Arbetsmetodik för utvecklare 2

```
⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜
⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛⬛
⬜⬛⬛⬜⬜⬛🟩🟩🟩⬛🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩
⬜⬛⬛⬜⬜⬛🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩
⬜⬛⬛⬜⬜⬛🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩🟩
⬜⬛⬛⬜⬜⬜⬛🟩🟩🟩🟩🟩⬛⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜
⬜⬛⬛⬜⬜⬜⬜⬛🟩🟩🟩⬛⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜
⬛⬛⬛⬛⬜⬜⬜⬜⬛⬛⬛⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜
⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜⬜
```

**Kurs:** Arbetsmetodik för utvecklare 2  
**Projekt:** Webbshop Mockup med Agil Metodik  
**Grupp:** Grupp 8  
**Datum:** 2025-12-11  
**Betyg:** IG/G

---

## 📋 Innehållsförteckning

1. [Sammanfattning](#sammanfattning)
2. [Inledning](#inledning)
3. [Projektbeskrivning](#projektbeskrivning)
4. [Agil Metodik - Teoretisk Bakgrund](#agil-metodik---teoretisk-bakgrund)
5. [Metod och Genomförande](#metod-och-genomförande)
6. [Resultat](#resultat)
7. [Diskussion](#diskussion)
8. [Slutsats](#slutsats)
9. [Referenser](#referenser)
10. [Bilagor](#bilagor)

---

## 1. Sammanfattning

Detta projekt dokumenterar utvecklingen av en webbshop-mockup för elektronik och teknikprodukter genom användning av agila metoder (Scrum och Kanban). Projektet genomfördes i fyra sprints med fokus på agil process istället för design. Vi skapade tre personas, 23 user stories, och organiserade arbetet med en Kanban board i markdown-format. Projektet demonstrerar praktisk tillämpning av agila principer inklusive sprintplanering, daily scrum, sprint reviews och sprint retrospectives.

**Nyckelord:** Agil utveckling, Scrum, Kanban, User Stories, Personas, Webbshop, Mockup

---

## 2. Inledning

### 2.1 Bakgrund

Detta projekt är en del av kursen "Arbetsmetodik för utvecklare 2" där vi ska lära oss att arbeta med agila metoder i praktiken. Uppgiften var att bygga en webbshop-mockup med fokus på den agila processen istället för designen.

### 2.2 Syfte

Syftet med projektet är att:
- Praktiskt tillämpa agila metoder (Scrum/Kanban)
- Skapa personas och user stories
- Genomföra arbetet i sprints med alla Scrum-events
- Använda versionshantering (Git)
- Dokumentera hela processen

### 2.3 Tidigare Kunskap

Innan projektet började hade vi lärt oss om:
- Agil manifestet och agila principer
- Scrum som ramverk (roller, events, artifacts)
- Kanban som visuell metod
- User stories och personas
- Versionshantering med Git

---

## 3. Projektbeskrivning

### 3.1 Webbshop-typ

Vi valde att skapa en webbshop för **elektronik och teknikprodukter** (datormus, tangentbord, skärmar, webkameror, etc.) istället för kläder eftersom:
- Det ger mer variation i användningsfall
- Det passar bättre med våra personas (tekniska användare)
- Det ger mer intressanta user stories
- Det är mer relevant för vår utbildning (Frontend Developer)

### 3.2 Kravspecifikation

Webbshoppen ska ha följande funktionalitet:

**Startsida:**
- Välkomsttext och bild
- Inloggningsruta med användarnamn och lösenord
- Tre utvalda produkter

**Shop-sida:**
- Minst tre kategorier (~5 produkter varje)
- Fritextsökning med Submit-knapp
- Klickbara produkter för detaljer
- Köp-knapp på varje produkt
- Produktinfo: beskrivning, pris, bild

**Varukorg:**
- Lista med valda produkter
- Knappar för att ändra antal
- Möjlighet att ta bort produkter
- Totalpris längst ner
- Frakt-knapp

**Checkout:**
- Formulär: namn, adress, etc.
- Minst två fraktalternativ (olika priser)
- Betala-knapp
- Produkter med priser
- Pris med frakt och moms
- Minst två betalningsmetoder

**Admin:**
- Lägga till nya produkter
- Redigera produkter (namn, text, bild, pris, utvald, lagersaldo)

**Försäljningsstatistik (Butiksägare):**
- Total försäljning
- Försäljning per dag
- Försäljning per kategori
- Lagersaldo
- Produkter som är slut
- Produkter med för mycket lager

### 3.3 Tekniska Krav

- Byggd med enkelt ritprogram (Canva, Figma, etc.)
- Enklast möjliga design (fokus på funktionalitet, inte design)
- Ser ut som en webbshop men saknar interaktiv funktionalitet (mockup)
- Använd riktiga produktbilder

---

## 4. Agil Metodik - Teoretisk Bakgrund

### 4.1 Agil Manifestet

Agil systemutveckling bygger på Agil manifestet (2001) med fyra värderingar:
1. **Individer och interaktioner** framför processer och verktyg
2. **Fungerande programvara** framför omfattande dokumentation
3. **Kundsamarbete** framför kontraktsförhandling
4. **Anpassning till förändring** framför att följa en plan

### 4.2 Scrum

Scrum är ett ramverk för att utveckla komplexa produkter. Det inkluderar:

**Roller:**
- **Product Owner:** Ansvarar för produktbacklog och värde
- **Scrum Master:** Ansvarar för processen och att ta bort hinder
- **Developers:** Ansvarar för att skapa inkrement

**Events:**
- **Sprint Planning:** Planerar vad som ska göras
- **Daily Scrum:** Daglig synkronisering (max 15 min)
- **Sprint Review:** Presenterar vad som åstadkommits
- **Sprint Retrospective:** Reflekterar och förbättrar

**Artifacts:**
- **Product Backlog:** Alla user stories prioriterade
- **Sprint Backlog:** User stories för aktuell sprint
- **Increment:** Slutfört arbete från sprinten

### 4.3 Kanban

Kanban är en visuell metod för att hantera arbetsflöden:
- **Kanban-tavla:** Visar arbetsflödet i kolumner
- **Kort:** Representerar uppgifter
- **Work in Progress (WIP) Limits:** Begränsar arbete i varje stadie
- **Kontinuerligt flöde:** Ingen fast sprint-struktur

### 4.4 User Stories

User stories är byggstenar i agil utveckling:
- Format: "Som [persona], vill jag [what?], så att [why?]"
- Fokuserar på användarens behov
- Små nog att slutföras i en sprint
- Har acceptance criteria

### 4.5 Personas

Personas är fiktiva representationer av ideala kunder:
- Baserade på verkliga användargrupper
- Inkluderar demografiska uppgifter, utmaningar, behov
- Hjälper teamet att fokusera på användaren
- Används för att skapa relevanta user stories

---

## 5. Metod och Genomförande

### 5.1 Projektstruktur

Vi organiserade projektet i strukturerade mappar:
```
group-project/
├── README.md                 # Projektöversikt
├── KANBAN_BOARD.md          # Kanban board (markdown)
├── PERSONAS.md               # 3 Personas
├── USER_STORIES.md           # 23 User Stories
├── SPRINT_PLANNING.md        # Sprintplanering & retrospectives
├── RAPPORT_PERSONAS.md       # Rapport om personas
├── RAPPORT_USER_STORIES.md   # Rapport om user stories
├── RAPPORT_KANBAN_BOARD.md   # Rapport om Kanban board
├── RAPPORT_SPRINT_PLANNING.md # Rapport om sprintplanering
└── GRUPPRAPPORT.md           # Denna rapport
```

### 5.2 Versionshantering

Vi använder Git och GitHub för versionshantering:
- Alla filer versioneras i Git
- Commits med tydliga meddelanden
- GitHub repository för samarbete
- Branches för features (om behövs)

### 5.3 Arbetsmetod

Vi arbetar enligt följande:
- **Mob programming:** Huvudsaklig arbetsmetod
- **Daily scrum:** Varje dag kl 9:00 (max 15 min)
- **Sprintplanering:** I början av varje sprint
- **Sprint review:** I slutet av varje sprint
- **Sprint retrospective:** Efter sprint review

### 5.4 Kommunikation

Vi kommunicerar via:
- [Plattform vald av gruppen]
- Tider: 9-16 varje vardag
- Alla måste vara tillgängliga
- Gruppkontrakt skapades i början

---

## 6. Resultat

### 6.1 Personas

Vi skapade tre personas:

1. **Emma Andersson** - 22-årig student (Datavetenskap, KTH)
   - Budgetmedveten, behöver tydlig information
   - 8 user stories kopplade till henne

2. **Marcus Johansson** - 38-årig IT-konsult (Göteborg)
   - Tidsmedveten, behöver snabbhet och effektivitet
   - 7 user stories kopplade till honom

3. **Lisa Bergström** - 67-årig pensionär (Malmö)
   - Behöver enkelhet och trygghet
   - 8 user stories kopplade till henne

### 6.2 User Stories

Vi skapade **23 user stories** (överstiger målet på ~20):

**Fördelning:**
- 🔴 Hög prioritet: 10 user stories
- 🟡 Medel prioritet: 7 user stories
- 🟢 Lägre prioritet: 6 user stories

**Täckning:**
- ✅ Alla krav från kravspecifikationen täckta
- ✅ User stories kopplade till personas
- ✅ Acceptance criteria definierade för varje story
- ✅ Tasks identifierade för varje story

### 6.3 Kanban Board

Vi skapade en Kanban board i markdown-format med:
- **Product Backlog:** Alla 23 user stories prioriterade
- **Sprint Backlog:** User stories för aktuell sprint
- **Doing:** Arbete som pågår
- **Test:** Klart arbete som väntar på granskning
- **Done:** Slutfört arbete (uppdelat per sprint)

**Fördelar med markdown-format:**
- Versionshantering i Git
- Lätt att dokumentera
- Fungerar bra med GitHub
- Ingen extern tjänst behövs

### 6.4 Sprintplanering

Vi planerade fyra sprints:

**Sprint 1 (Tis 9/12 - Tor 11/12):** Förberedelse
- Personas, user stories, startsida och shop-sida

**Sprint 2 (Tor 11/12 - Tis 16/12):** Utveckling
- Shop-funktionalitet och varukorg

**Sprint 3 (Tis 16/12 - Tor 18/12):** Slututveckling
- Checkout-processen

**Sprint 4 (Tor 18/12 - Sön 28/12):** Finalisering
- Admin-funktioner och försäljningsstatistik

### 6.5 Mockup Status

*[Detta fylls i när mockup är klar]*

---

## 7. Diskussion

### 7.1 Val av Webbshop-typ

Vi valde elektronik istället för kläder eftersom:
- Det ger mer variation i användningsfall
- Det passar bättre med våra personas
- Det är mer relevant för vår utbildning
- Det ger mer intressanta user stories

### 7.2 Markdown Kanban vs. Trello

Vi valde markdown-format istället för Trello eftersom:
- ✅ Bättre versionshantering med Git
- ✅ Lättare att dokumentera
- ✅ Fungerar bättre med vårt arbetsflöde
- ✅ Ingen extern tjänst behövs

**Nackdelar:**
- ⚠️ Mindre visuellt än Trello
- ⚠️ Kräver manuell uppdatering

### 7.3 Antal User Stories

Vi skapade 23 user stories istället för ~20 eftersom:
- Vi ville täcka alla krav från kravspecifikationen
- Vi ville ha flexibilitet att välja de viktigaste för varje sprint
- Det ger oss bättre översikt över hela projektet

### 7.4 Agil Process

Genom att följa agil process:
- Vi fokuserar på användaren (personas)
- Vi prioriterar baserat på värde (user stories)
- Vi arbetar i små steg (sprints)
- Vi reflekterar och förbättrar (retrospectives)

### 7.5 Utmaningar

Några utmaningar vi stötte på:
- **Prioritering:** Det var svårt att prioritera user stories - många känns viktiga
- **Tid:** Sprintarna är korta, vi måste vara effektiva
- **Samarbete:** Mob programming kräver koordination
- **Dokumentation:** Mycket att dokumentera, men viktigt för lärandet

---

## 8. Slutsats

Genom detta projekt har vi:
- ✅ Praktiskt tillämpat agila metoder (Scrum/Kanban)
- ✅ Skapat tre personas baserade på verkliga användargrupper
- ✅ Skapat 23 user stories som täcker alla krav
- ✅ Organiserat arbetet med Kanban board i markdown-format
- ✅ Planerat fyra sprints med tydliga mål
- ✅ Förberett oss för agilt arbete genom hela projektet

**Viktiga Lärdomar:**
- Agil metodik fokuserar på användaren och värde
- Personas hjälper oss att fatta bättre beslut
- User stories gör arbete hanterbart och fokuserat
- Kanban board ger översikt och hjälper identifiera problem
- Sprintplanering är viktig för att hålla fokus

**Framtida Förbättringar:**
- Fortsätta dokumentera daily scrum och retrospectives
- Använda velocity för bättre planering
- Förbättra WIP limits i Kanban board
- Kontinuerligt reflektera och förbättra processen

Projektet demonstrerar praktisk tillämpning av agila metoder och visar hur Scrum och Kanban kan användas tillsammans för att hantera ett webbutvecklingsprojekt.

---

## 9. Referenser

- Kursmaterial: Arbetsmetodik 01 - Intro.pdf
- Kursmaterial: Arbetsmetodik 02 - AgilScrumKanban.pdf
- Kursmaterial: Arbetsmetodik 03 - Uppgiften.pdf
- Kursmaterial: Arbetsmetodik 04 - Om Grupparbete.pdf
- The Scrum Guide (2020) - Ken Schwaber & Jeff Sutherland
- Agil manifestet (2001)
- Kanban – Wikipedia

---

## 10. Bilagor

### Bilaga A: Personas
Se filen `PERSONAS.md` för detaljerad information om alla tre personas.

### Bilaga B: User Stories
Se filen `USER_STORIES.md` för komplett lista över alla 23 user stories.

### Bilaga C: Kanban Board
Se filen `KANBAN_BOARD.md` för aktuell status på Kanban board.

### Bilaga D: Sprintplanering
Se filen `SPRINT_PLANNING.md` för detaljerad sprintplanering och retrospective-anteckningar.

### Bilaga E: Gruppkontrakt
*[Gruppkontrakt läggs till här när det är skapat]*

### Bilaga F: Sprint Retrospective Noteringar
*[Noteringar från retrospectives läggs till efter varje sprint]*

---

**Projektstatus:** Pågående  
**Senast uppdaterad:** 2025-12-11  
**Nästa steg:** Börja Sprint 1 - Förberedelse

---

*Rapport skapad: 2025-12-11*  
*Författare: Projektgrupp*  
*Kurs: Arbetsmetodik för utvecklare 2*  
*Handledare: Micke Engström*

