# IT-SURVIVAL — Mobile Edition V3

Ein vollständiges, statisches Mobile-Browsergame im Retro-Pixelstil. Keine Installation, kein Build-Schritt und keine externen Abhängigkeiten: `index.html` enthält das komplette Spiel.

## Neues GitHub-Repository veröffentlichen

### Variante A — direkt im Browser

1. Auf GitHub ein **neues leeres Repository** anlegen.
2. Alle Dateien aus diesem Paket einschließlich `.github` und `.nojekyll` direkt in die oberste Ebene hochladen.
3. Unter **Settings → Pages → Build and deployment** als Source **GitHub Actions** auswählen.
4. Den Workflow **Deploy IT-SURVIVAL to GitHub Pages** ausführen lassen.
5. Die veröffentlichte URL steht anschließend im Workflow und unter Settings → Pages.

### Variante B — mit Git

```bash
git init
git add .
git commit -m "Initial IT-SURVIVAL Mobile V3"
git branch -M main
git remote add origin https://github.com/DEIN-NAME/DEIN-REPO.git
git push -u origin main
```

Danach in GitHub Pages als Source **GitHub Actions** wählen. Bei einem normalen Projekt-Repository lautet die URL typischerweise `https://DEIN-NAME.github.io/DEIN-REPO/`.

## Was Mobile V3 ändert

- Kaffee sinkt nur noch um **1 Punkt alle 6 Sekunden** und pausiert in Dialogen.
- Nach einer gelösten Aufgabe kommt die nächste variabel nach **3–8 Sekunden**; optional sofort über „NÄCHSTES TICKET JETZT“.
- Der Router-Blinktest startet erst nach eigenem Touch und besitzt einen 3-2-1-Countdown.
- HDMI und USB wurden als detaillierte Retro-Hardware neu gezeichnet.
- Anschlüsse funktionieren per Touch-Auswahl oder Drag.
- Typische UI-Emojis wurden durch Textcodes und eigene Pixel-Icons ersetzt.
- Die komplette Website bleibt touch-first und für Smartphone-Hochformat optimiert.

## Repository-Struktur

```text
.github/workflows/deploy-pages.yml  Automatisches GitHub-Pages-Deployment
.nojekyll                           Statische Dateien unverändert ausliefern
index.html                          Fertige selbstständige Website
index.source.html                   Lesbare ungebündelte HTML-Fassung
style.css                           Styles und Retro-Hardwaregrafik
characters.js                      Pixelportraits
story.js                           Story und Quests
minigames.js                       Minigames
game.js                            State-Machine und Scheduler
QA.md                              Testprotokoll
REPO-SETUP.md                      Ausführliche Veröffentlichung
VERSION.txt                        Build-Information
```

## Lokaler Test

`index.html` kann direkt im Browser geöffnet werden. Es sind kein Webserver und kein Paketmanager erforderlich.
