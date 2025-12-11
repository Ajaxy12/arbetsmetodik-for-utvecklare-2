# 📊 Rapport: Kanban Board - Webbshop Projekt

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

## 📋 Innehållsförteckning

1. [Inledning](#inledning)
2. [Syfte och Bakgrund](#syfte-och-bakgrund)
3. [Teoretisk Bakgrund - Kanban](#teoretisk-bakgrund---kanban)
4. [Metod - Implementering](#metod---implementering)
5. [Resultat - Kanban Board Struktur](#resultat---kanban-board-struktur)
6. [Analys och Diskussion](#analys-och-diskussion)
7. [Slutsats](#slutsats)
8. [Referenser](#referenser)

---

## 1. Inledning

Denna rapport dokumenterar skapandet och användningen av vår Kanban board för webbshop-projektet. Istället för att använda Trello (som rekommenderades i uppgiften) valde vi att skapa en Kanban board i markdown-format med GitHub som versionshantering, vilket passar bättre för vårt arbetsflöde.

### 1.1 Tidigare Kunskap

Innan vi började arbetet med Kanban board hade vi lärt oss om:
- Kanban som visuell metod för att hantera arbetsflöden
- Kolumner som representerar olika steg i processen
- Kort som representerar uppgifter som flyttas genom kolumnerna
- Viktigheten av att visualisera arbete för att identifiera flaskhalsar
- Hur Kanban används tillsammans med Scrum i agil utveckling

---

## 2. Syfte och Bakgrund

### 2.1 Syfte

Syftet med att skapa en Kanban board är att:
- Visualisera arbetsflödet och se vad som händer
- Identifiera flaskhalsar och problem i processen
- Hålla koll på vad som är i arbete, vad som väntar och vad som är klart
- Ge överblick över hela projektet
- Hantera user stories och uppgifter effektivt

### 2.2 Bakgrund

Enligt kravspecifikationen skulle vi använda Trello för att hantera user stories. Vi valde istället att skapa en Kanban board i markdown-format eftersom:
- Vi använder GitHub för versionshantering
- Markdown-filer är lättare att hantera i Git
- Vi kan dokumentera och spåra ändringar bättre
- Det passar bättre med vårt arbetsflöde

---

## 3. Teoretisk Bakgrund - Kanban

### 3.1 Vad är Kanban?

Kanban är en visuell metod för att hantera arbetsflöden genom att dela in arbetet i kolumner på en tavla. Varje kolumn representerar ett steg i processen, till exempel "Att göra", "Pågående" och "Klart".

### 3.2 Kanban Huvudkomponenter

- **Kanban-tavla:** En visuell anslagstavla (fysisk eller digital) som visar arbetsflödet
- **Kolumner:** Representerar olika steg i processen
- **Kort:** Varje kort representerar en specifik uppgift som flyttas genom kolumnerna
- **Work in Progress (WIP) Limits:** Begränsar mängden arbete i varje stadie

### 3.3 Kanban vs. Trello

Trello är ett verktyg som använder Kanban-metodiken. Vi implementerar samma metodik men i markdown-format istället för Trello-plattformen.

---

## 4. Metod - Implementering

### 4.1 Val av Kolumner

Vi valde följande kolumner för vår Kanban board:
1. **Product Backlog:** Alla user stories prioriterade efter värde
2. **Sprint Backlog:** User stories valda för aktuell sprint
3. **Doing:** Arbete som pågår just nu
4. **Test:** Klart arbete som väntar på testning/granskning
5. **Done:** Slutfört och accepterat arbete

### 4.2 Struktur

Vi organiserade Kanban board i markdown med:
- Tydliga sektioner för varje kolumn
- User stories listade med status, prioritet och information
- Checkboxar för att spåra framsteg
- Tabeller för statistik och överblick

### 4.3 Versionshantering

Kanban board-filen versioneras i Git tillsammans med resten av projektet, vilket ger oss:
- Historik över ändringar
- Möjlighet att se hur boarden utvecklats över tid
- Samarbete genom Git (pull requests, reviews)

---

## 5. Resultat - Kanban Board Struktur

### 5.1 Product Backlog

Product Backlog innehåller alla 23 user stories organiserade efter prioritet:
- **🔴 Hög prioritet:** 10 user stories (grundläggande funktionalitet)
- **🟡 Medel prioritet:** 7 user stories (förbättringar)
- **🟢 Lägre prioritet:** 6 user stories (admin-funktioner)

### 5.2 Sprint Backlog

Sprint Backlog är tom i början och fylls under sprintplanering när vi väljer user stories för varje sprint.

### 5.3 Doing (Pågående)

Doing-kolumnen är tom i början och fylls när vi börjar arbeta med user stories under sprintarna.

### 5.4 Test

Test-kolumnen används för arbete som är klart men väntar på granskning eller testning.

### 5.5 Done

Done-kolumnen är uppdelad per sprint för att spåra vad som slutförts i varje sprint.

### 5.6 Sprint Statistics

Vi har en tabell för att spåra sprint-statistik:
- Start- och slutdatum
- Antal planerade user stories
- Antal slutförda user stories
- Velocity (hastighet)

---

## 6. Analys och Diskussion

### 6.1 Fördelar med Markdown Kanban Board

**Fördelar:**
- ✅ Versionshantering i Git
- ✅ Lätt att dokumentera och kommentera
- ✅ Fungerar bra med GitHub
- ✅ Ingen extern tjänst behövs
- ✅ Kan inkluderas i projektrapporter

**Nackdelar:**
- ⚠️ Mindre visuellt än Trello
- ⚠️ Kräver manuell uppdatering (men ger bättre kontroll)
- ⚠️ Ingen realtidsuppdatering (men fungerar bra för vårt team)

### 6.2 Jämförelse med Trello

| Aspekt | Trello | Vår Markdown Kanban |
|--------|--------|---------------------|
| **Visuellt** | ✅ Mycket visuellt | ⚠️ Mindre visuellt |
| **Versionshantering** | ⚠️ Begränsat | ✅ Full Git-integration |
| **Dokumentation** | ⚠️ Kommentarer | ✅ Rik markdown-format |
| **Kostnad** | ✅ Gratis (begränsat) | ✅ Helt gratis |
| **Samarbete** | ✅ Realtid | ✅ Via Git |
| **Anpassning** | ⚠️ Begränsat | ✅ Full kontroll |

### 6.3 Användning under Projektet

Kanban board kommer att användas:
- **Under sprintplanering:** För att välja user stories till sprint backlog
- **Under sprinten:** För att flytta user stories genom kolumnerna
- **Under daily scrum:** För att diskutera vad som är i Doing
- **Under sprint review:** För att visa vad som är i Done
- **Under sprint retrospective:** För att analysera flödet och identifiera problem

---

## 7. Slutsats

Genom att skapa en Kanban board i markdown-format har vi:
- ✅ Skapat en visuell representation av vårt arbetsflöde
- ✅ Organiserat alla 23 user stories i Product Backlog
- ✅ Förberett strukturen för sprintplanering
- ✅ Integrerat med vårt Git-baserade arbetsflöde
- ✅ Skapat en lösning som passar vårt team bättre än Trello

Kanban board är en viktig del av vår agila process och hjälper oss att:
- Hålla översikt över projektet
- Identifiera flaskhalsar
- Prioritera arbete
- Följa framsteg

Vi är nu redo att börja använda Kanban board under sprintplanering och genom hela projektet.

---

## 8. Referenser

- Kursmaterial: Arbetsmetodik 02 - AgilScrumKanban.pdf
- Kursmaterial: Arbetsmetodik 03 - Uppgiften.pdf
- Kanban – Wikipedia
- The Scrum Guide (2020)

---

*Rapport skapad: 2025-12-11*  
*Författare: Projektgrupp*  
*Kurs: Arbetsmetodik för utvecklare 2*

