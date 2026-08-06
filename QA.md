# Mobile-V3-Abnahme

## Geändertes Spieltempo

- [x] Kaffeeabzug von 1 Punkt je 2 Sekunden auf 1 Punkt je 6 Sekunden reduziert
- [x] kein Kaffeeabzug während Dialogen
- [x] nächste Aufgabe wird nach 3–8 Sekunden automatisch verbunden
- [x] maximale automatische Wartezeit bleibt unter 10 Sekunden
- [x] manuelles Sofortladen des nächsten Tickets möglich
- [x] feste Story-Ereignisse und Enden bleiben funktionsfähig

Gemessener Maximalfall mit erzwungen größtmöglicher Zufallsverzögerung: **8,34 Sekunden** bis zum nächsten Ticket.

## Minigames

- [x] Router-Sequenz startet erst nach explizitem Touch
- [x] sichtbarer 3-2-1-Countdown
- [x] verlangsamte Signalsequenz
- [x] selbst gestartete Wiederholung nach einem Fehler
- [x] HDMI-Puzzle per Touch-Auswahl und Drag geprüft
- [x] USB-Puzzle per Touch-Auswahl und Drag geprüft
- [x] Kaffee-Hold-Geste geprüft
- [x] alle 10 Minigames plus DRUCKO 5000 erfolgreich abgeschlossen

## Gestaltung

- [x] detaillierte PC-Rückseite und GPU-Anschlüsse
- [x] detaillierter HDMI-Type-A-Stecker
- [x] detaillierte Maus, USB-A-Stecker und Front-I/O
- [x] typische UI-Emojis reduziert bzw. ersetzt
- [x] eigene Pixel-Icons für Malware und Systemdateien
- [x] industrielle Retro-Panels statt generischer runder App-Karten

## Technische Tests

- selbstständige `index.html` allein in leerem Ordner gestartet
- 0 zusätzliche Netzwerk- oder Dateianfragen
- Touch-Start erfolgreich
- 13 Screens ohne horizontalen Overflow
- Story-Scheduler, Pflicht-Events, Enden und Restart geprüft
- keine Konsolenfehler

## Getestete Viewports

- 320 × 568
- 360 × 740 bei Device-Pixel-Ratio 3
- 390 × 844
- 412 × 915

## Visuelle Einzelprüfung

Start, Board, Router-Sequenz, HDMI, USB, Malware-Spiel und Endscreen wurden nach der V3-Überarbeitung einzeln geprüft. Alle 17 Mobile-Zustände wurden anschließend erneut ohne Konsolenfehler gerendert.
