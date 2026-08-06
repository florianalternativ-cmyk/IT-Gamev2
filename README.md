https://florianalternativ-cmyk.github.io/IT-Gamev2/


# IT-SURVIVAL — Mobile Edition V2

Diese Version ist konsequent für Smartphones im Hochformat gebaut. Die veröffentlichte `index.html` ist vollständig selbstständig: CSS, Pixel-Art und JavaScript sind direkt eingebettet. Dadurch kann das Spiel nicht mehr wegen fehlender oder veralteter `style.css`-/JavaScript-Dateien auf der Startseite hängen bleiben.

## Schnellste Veröffentlichung

1. Öffne dein GitHub-Pages-Repository.
2. Ersetze die vorhandene **`index.html` im Repository-Hauptverzeichnis** durch die neue `index.html`.
3. Committe die Änderung und warte kurz auf GitHub Pages.
4. Öffne die Seite einmal mit `?v=mobile-v2`, beispielsweise `https://alternativ-cmyk.github.io/?v=mobile-v2`.

Nur `index.html` ist zum Spielen erforderlich. Das ZIP enthält zusätzlich die lesbaren Quelldateien.

## Wichtig

- Die Dateien aus dem ZIP liegen bereits auf der obersten Ebene. **Keinen zusätzlichen Unterordner** in das Repository hochladen.
- Wenn weiterhin die alte grüne, unformatierte Seite erscheint, wird noch eine alte `index.html` ausgeliefert. Prüfe Branch/Ordner in den GitHub-Pages-Einstellungen und lade die Seite danach im Inkognito-Modus.
- Auf dem korrekten Startscreen steht in der Terminalzeile: `touch.ready = true`.

## Mobile Änderungen

- feste Hochformat-App mit maximal 480 px Breite
- Smartphone-Layout auch auf großen Bildschirmen
- kompakter Touch-HUD mit Kaffee, Brumm, Uhr und Ton
- einspaltiges Quest-Board
- Touch-Ziele ab 52 px
- direkter Start über `pointerup`, `touchend` und Click-Fallback
- Startbutton mit sichtbarer Lade-/Fehlerdiagnose
- keine Maus-Hinweise mehr in der Oberfläche
- kontrolliertes Scrollen nur innerhalb von Board und Minigame-Panel
- Safe-Area-Unterstützung für Geräte mit Notch
- selbstständige `index.html` ohne externe Requests

## Quelldateien

```text
index.html          # fertige selbstständige GitHub-Pages-Datei
index.source.html   # ungebündelte Quellfassung
style.css           # Mobile-V2-Styles
characters.js       # Pixelportraits
story.js            # Story und Quests
minigames.js        # Minigames
game.js             # State-Machine und Touch-Start
QA.md               # Testprotokoll
DEPLOY-MOBILE.txt   # Kurz-Anleitung
```
