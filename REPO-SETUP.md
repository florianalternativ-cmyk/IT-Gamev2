# Neues GitHub-Repository: Schritt für Schritt

1. Das ZIP entpacken.
2. Auf GitHub **New repository** wählen und ein leeres Repository erstellen. GitHub dort nicht zusätzlich README, `.gitignore` oder License erzeugen lassen.
3. Sämtliche entpackten Dateien direkt hochladen. `index.html` muss im Repository-Root liegen; `.github/workflows/deploy-pages.yml` muss erhalten bleiben.
4. Zu **Settings → Pages** wechseln.
5. Unter **Build and deployment → Source** die Option **GitHub Actions** auswählen.
6. Unter **Actions** den Workflow „Deploy IT-SURVIVAL to GitHub Pages“ abwarten oder manuell starten.
7. Die dort angezeigte Pages-URL öffnen.

## Alternative ohne Workflow

Unter Settings → Pages kann auch **Deploy from a branch**, Branch `main`, Ordner `/(root)` gewählt werden. `index.html` ist vollständig selbstständig und funktioniert auch in dieser Variante.

## Kontrolle

Die richtige Version zeigt:

- `TIPPE ZUM STARTEN`
- `SFX` oben rechts
- `touch.ready = true`
- beim Router den Button `SIGNALTEST STARTEN`

Bei einer alten Ansicht die Pages-Einstellungen prüfen und die URL einmal mit `?v=mobile-v3` öffnen.
