# Mobile-V2-Abnahme

## Behobene Probleme

- [x] Fehlende/veraltete Styles oder Scripts können den Build nicht mehr zerstören: `index.html` ist vollständig selbstständig.
- [x] Touch auf den Startbutton löst den Spielstart unmittelbar aus.
- [x] Sichtbare Diagnose statt stiller, nicht reagierender Startseite.
- [x] Layout ist nicht mehr desktop-orientiert und bleibt überall eine Hochformat-App.
- [x] Keine horizontale Seite und keine außerhalb des Viewports liegenden Hauptaktionen.

## Getestete Viewports

- 320 × 568
- 360 × 740 bei Device-Pixel-Ratio 3
- 390 × 844
- 412 × 915
- 1440 × 900 als zentrierte Mobile-App

## Funktionstests

- selbstständige `index.html` allein in einem leeren Ordner gestartet
- 0 zusätzliche Netzwerk-/Dateianfragen
- Touch-Start erfolgreich
- 13 Screens ohne horizontalen Overflow
- alle 10 Minigames plus DRUCKO 5000 abgeschlossen
- Touch-Drag für HDMI und USB geprüft
- Touch-Hold für KAFFEMAT geprüft
- Story-Scheduler, Eskalationen und Pflicht-Events geprüft
- alle Enden und Restart geprüft
- keine Konsolenfehler

## Visuelle Prüfung

Start, Dialog, Board, Quiz, WLAN, HDMI, USB, Passwort, Triage, Logs, Viren, Phishing, KAFFEMAT, Drucker-Boss und Endscreen wurden einzeln bei 360 × 740 visuell geprüft. Die Startseite wurde zusätzlich bei 320 × 568 und 412 × 915 geprüft.
