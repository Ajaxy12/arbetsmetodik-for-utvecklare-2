# Arbetsmetodik för utvecklare 2

Detta repository innehåller material och dokumentation för kursen "Arbetsmetodik för utvecklare 2".

## Innehåll

Detta repository innehåller:
- Kursmaterial och presentationer
- PDF-dokument om agil metodik, Scrum och Kanban
- Video-lektioner om projektmetoder
- The Scrum Guide

## Projektstruktur

```
Arbetsmetodik-för-utvecklare-2/
├── 05. Arbetsmetodik 2.pdf
├── Arbetsmetodik 01 - Intro.pdf
├── Arbetsmetodik 02 - AgilScrumKanban.pdf
├── Arbetsmetodik 03 - Uppgiften.pdf
├── Arbetsmetodik 04 - Om Grupparbete.pdf
├── Lektion 1 - Projektmetoder - Del 1.mp4
├── Lektion 1 - Projektmetoder - Del 2.mp4
├── The Scrum Guide.pdf
├── README.md
├── LICENSE
└── .gitignore
```

## Kursinnehåll

### Lektioner och material
- **Arbetsmetodik 01 - Intro**: Introduktion till arbetsmetodik
- **Arbetsmetodik 02 - AgilScrumKanban**: Översikt över agil metodik, Scrum och Kanban
- **Arbetsmetodik 03 - Uppgiften**: Information om kursuppgiften
- **Arbetsmetodik 04 - Om Grupparbete**: Riktlinjer för grupparbete
- **Lektion 1 - Projektmetoder**: Video-lektioner om projektmetoder (Del 1 och Del 2)
- **The Scrum Guide**: Officiell guide för Scrum-metodiken

## Versionshantering

Projektet använder Git för versionshantering. Alla ändringar committas med tydliga commit-meddelanden.

### Git-kommandon som används i projektet:

```bash
# Kontrollera status
git status

# Lägg till filer
git add .

# Committa ändringar
git commit -m "Beskrivande commit-meddelande"

# Pusha till GitHub
git push origin main

# Hämta senaste ändringar
git pull origin main
```

### Hantera stora filer

Detta projekt innehåller video-filer som är större än GitHub's rekommenderade gräns på 50 MB. Om du stöter på problem när du pushar stora filer:

#### Snabb lösning: Öka HTTP buffer

```bash
git config http.postBuffer 524288000
git push origin main
```

#### Rekommenderad lösning: Använd Git LFS

För bättre hantering av stora filer i framtida projekt, överväg att använda [Git Large File Storage (LFS)](https://git-lfs.github.com/):

```bash
# Installera och initialisera Git LFS
git lfs install
git lfs track "*.mp4"

# Lägg till och pusha
git add .gitattributes
git add .
git commit -m "Add large files with Git LFS"
git push origin main
```

Se [PUSH_TO_GITHUB.md](PUSH_TO_GITHUB.md) för mer detaljerad information om hantering av stora filer.

## Licens

Detta projekt är licensierad under MIT License. Se [LICENSE](LICENSE) filen för mer information.

## Kontakt

För frågor om projektet, kontakta projektägaren:
- **Utvecklare**: Amir Hemmatnia
- **GitHub**: [Ajaxy12](https://github.com/Ajaxy12)

