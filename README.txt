# 24 kleine Weihnachtsfreuden – Adventskalender 2026

## Inhalt
- `index.html`: responsive Website mit automatischer datumsabhängiger Türchenfreischaltung
- `pdf/`: 24 druckfreundliche PDF-Anleitungen
- `README.txt`: diese Anleitung

## Kostenlos veröffentlichen mit GitHub Pages
1. Erstelle ein kostenloses Konto auf https://github.com/ (falls noch keines vorhanden ist).
2. Erstelle ein neues **öffentliches** Repository, z. B. `adventskalender-kollegium-2026`.
3. Lade `index.html` und den gesamten Ordner `pdf` in das Repository hoch. Wichtig: `index.html` muss direkt im obersten Ordner liegen.
4. Öffne im Repository **Settings → Pages**.
5. Unter **Build and deployment** wähle **Deploy from a branch**.
6. Wähle Branch `main` und Ordner `/(root)`, dann **Save**.
7. Warte auf die Veröffentlichung. GitHub zeigt dir anschließend die Website-Adresse im Bereich Pages an. Teile diesen Link mit dem Kollegium.

Offizielle Anleitung: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Datumslogik
Die Türchen werden im Browser automatisch nach dem Datum des Geräts freigeschaltet: 1.–24. Dezember 2026; danach sind alle Türchen geöffnet. Vor Dezember bleiben alle Türchen geschlossen. Stelle vor dem Teilen sicher, dass das Gerät die korrekte lokale Zeit verwendet.

## Wichtiger Hinweis
Diese Website ist eine statische Website. Die Freischaltung blendet Türchen auf der Seite aus bzw. ein, ist aber kein sicherer Zugriffsschutz: Dateien, die auf der Website liegen, können bei Kenntnis ihrer URL auch früher aufgerufen werden. Verwende daher keine vertraulichen Inhalte.

## Bearbeitung
- Die Titel, Zeitangaben und PDF-Pfade der Türchen stehen im JavaScript-Array `items` in `index.html`.
- Die Website ist mobil optimiert und benötigt keine externe Bibliothek.
- Du kannst die PDF-Dateien vor dem Hochladen austauschen, sofern die Dateinamen gleich bleiben.
