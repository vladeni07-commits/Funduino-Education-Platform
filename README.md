# Funduino Tutorial-Generator

Schritt-für-Schritt-Anleitungen, Lernpfade, Arbeitsblätter und Kindermodus für den Funduino Cube, den Funduino Cube 32 und das Funduino Starterkit.

Die Seite ist eine einzelne HTML-Datei (`index.html`) und braucht keinen Server und keine Datenbank. Fortschritt und Einstellungen werden nur im Browser der Nutzer gespeichert.

## Inhalt

| Datei / Ordner | Zweck |
|---|---|
| `index.html` | Die komplette Website |
| `fonts/` | Schrift Montserrat, lokal eingebunden (keine Verbindung zu Google Fonts) |
| `.nojekyll` | Sagt GitHub Pages, dass die Dateien unverändert ausgeliefert werden sollen |

## Veröffentlichen mit GitHub Pages

1. Neues Repository auf GitHub anlegen, zum Beispiel `tutorial-generator`.
2. Den gesamten Inhalt dieses Ordners in das Repository hochladen (nicht den Ordner selbst, sondern was darin liegt).
3. Im Repository: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, Branch `main`, Ordner `/ (root)`, speichern.
4. Nach 1–2 Minuten ist die Seite erreichbar unter `https://<github-name>.github.io/tutorial-generator/`.

Das Begleitheft (PDF) ist bewusst nicht enthalten, weil es nicht frei verfügbar ist. In der Seite ist der Schalter `HEFT_PDF` deshalb auf `false` gesetzt.

## Rechtliches

Impressum und Datenschutz verlinken auf die Seiten von funduino.com.

© Funduino GmbH, Bornestraße 22, 48529 Nordhorn
