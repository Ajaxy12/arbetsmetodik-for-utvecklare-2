# 📝 Individuell Projektrapport - Arbetsmetodik för utvecklare 2 (A4-version)

**Student:** Amir Hemmatnia  
**Grupp:** Grupp 8  
**Kurs:** Arbetsmetodik för utvecklare 2  
**Datum:** 2025-12-11

---

## 📋 Sammanfattning

Denna rapport reflekterar över min erfarenhet av agil systemutveckling genom gruppprojektet där vi byggde en webbshop-mockup. Jag analyserar agila metoder (Scrum/Kanban), jämför med icke-agila modeller, reflekterar över utvecklingsverktyg och versionshantering, samt analyserar gruppens arbetsprocess och samarbete.

---

## 1. Agila Projektmetoder

### Agil Manifestet
Agil systemutveckling bygger på fyra värderingar: 1) Individer och interaktioner framför processer och verktyg, 2) Fungerande programvara framför omfattande dokumentation, 3) Kundsamarbete framför kontraktsförhandling, 4) Anpassning till förändring framför att följa en plan.

### Scrum
Scrum är ett ramverk med roller (Product Owner, Scrum Master, Developers), events (Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective) och artifacts (Product Backlog, Sprint Backlog, Increment). Vi använde Scrum med fyra sprints där varje sprint hade tydliga mål och valda user stories.

### Kanban
Kanban är en visuell metod för att hantera arbetsflöden. Vi använde en Kanban board i markdown-format (istället för Trello) med kolumner: Product Backlog, Sprint Backlog, Doing, Test, Done. Detta gav oss översikt och hjälpte identifiera flaskhalsar.

### User Stories och Personas
Vi skapade 23 user stories kopplade till tre personas (Emma Andersson - student, Marcus Johansson - IT-konsult, Lisa Bergström - pensionär). Detta hjälpte oss att fokusera på användarens behov istället för tekniska detaljer.

---

## 2. Icke-Agila Projektmodeller

### Vattenfallsmetoden
Vattenfallsmetoden är en sekventiell process med faser: Förberedelse → Etablering → Analys → Design → Konstruktion → Test → Produktionssättning → Underhåll. Fördelar: Kostnadskontroll, resursplanering, kvalitetssäkring. Nackdelar: Kvalitetsproblem, svårt att hantera förändringar, ingen kundnytta förrän i slutet, mer riskabelt.

### Skillnader
| Aspekt | Vattenfallsmetoden | Agil Metodik |
|--------|-------------------|--------------|
| Process | Sekventiell | Iterativ |
| Förändringar | Svåra | Välkomnas |
| Leverans | I slutet | Kontinuerlig |
| Kundinvolvering | I början/slutet | Kontinuerlig |

**Varför agil är bättre för vårt projekt:** Vi kunde börja arbeta direkt, anpassa oss när vi lärde oss mer, leverera värde kontinuerligt, prioritera baserat på användarvärde, och fokusera på användaren från början.

---

## 3. Utvecklingsverktyg och Versionshantering

### Versionshantering med Git
Versionshantering spårar ändringar i filer över tid. Det låter dig se historik, återgå till tidigare versioner, samarbeta utan att skriva över varandras arbete, och hantera olika versioner (branches).

**Varför viktigt:** Säkerhet (kan alltid gå tillbaka), samarbete (flera personer kan arbeta på samma projekt), historik (se vad som ändrats), backup (koden är säker).

**Vår Git-workflow:**
1. Arbeta lokalt på filer
2. `git add .` - Lägg till ändringar
3. `git commit -m "Beskrivande meddelande"` - Spara ändringar
4. `git push origin main` - Skicka till GitHub
5. Andra i gruppen gör `git pull` för att hämta ändringar

**Reflektion:** Versionshantering är viktigare än jag trodde. Det ger inte bara säkerhet utan också möjlighet att se projektets utveckling över tid. Git är essentiellt för samarbete i systemutveckling.

---

## 4. Gruppens Arbetsprocess

### Arbetsprocess
Vi följde en agil arbetsprocess med sprintplanering, daily scrum, mob programming, sprint reviews och sprint retrospectives. Kommunikation skedde via [plattform] med tydliga tider (9-16 varje vardag).

### Vad fungerade bra
- ✅ Tydlig struktur och organisation
- ✅ Bra användning av personas för att fokusera på användaren
- ✅ Tydliga user stories med acceptance criteria
- ✅ Versionshantering fungerade bra
- ✅ Kommunikation var tydlig och regelbunden

### Utmaningar
- ⚠️ Prioritering av user stories var svår - många känns viktiga
- ⚠️ Tidsplanering var utmanande med korta sprints
- ⚠️ Balansera mellan dokumentation och arbete
- ⚠️ Mob programming kräver koordination

---

## 5. Personlig Reflektion

### Min Erfarenhet
Innan projektet hade jag teoretisk kunskap om agila metoder men begränsad praktisk erfarenhet. Genom projektet lärde jag mig hur Scrum fungerar i praktiken, viktigheten av personas, hur user stories hjälper att bryta ner arbete, värdet av daily scrum, och viktigheten av sprint retrospectives.

### Tekniska Färdigheter
- ✅ Förbättrad förståelse för Git och versionshantering
- ✅ Bättre förståelse för agila metoder
- ✅ Lärt mig att skriva user stories
- ✅ Lärt mig att skapa personas

### Mjuka Färdigheter
- ✅ Bättre kommunikationsförmåga
- ✅ Förbättrad samarbetsförmåga
- ✅ Bättre på att reflektera och förbättra
- ✅ Mer strukturerat tänkande

---

## 6. Slutsats och Förbättringsförslag

### Slutsats
Genom detta projekt har jag lärt mig att agila metoder fungerar för att hantera komplexitet och förändringar, användaren är central (personas och user stories hjälper att fokusera på rätt saker), versionshantering är viktigt (Git är essentiellt för samarbete), kommunikation är nyckeln till framgång, och kontinuerlig förbättring (retrospectives hjälper att bli bättre).

### Förbättringsförslag
**För gruppen:** Förbättra prioritering, tydligare Definition of Done, bättre tidsuppskattning, mer aktiv användning av Kanban, tydligare roller, bättre kommunikation om hinder, använd branches mer, bättre commit-meddelanden.

**För mig själv:** Bättre planering, mer proaktiv kommunikation, bättre dokumentation, mer självständighet, förbättra Git-kunskaper, bättre förståelse för agila metoder.

### Framtida Tillämpning
Jag kommer att använda det jag lärt mig i framtida projekt: använda agila metoder från början, skapa personas för att fokusera på användaren, använda user stories för att definiera funktionalitet, använda versionshantering konsekvent, kommunicera tydligt och regelbundet, reflektera och förbättra kontinuerligt.

---

**Referenser:** Kursmaterial (Arbetsmetodik 01-04), The Scrum Guide (2020), Agil manifestet (2001), Git Documentation

---

*Amir Hemmatnia | Grupp 8 | Arbetsmetodik för utvecklare 2 | 2025-12-11*

