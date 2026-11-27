# Fixkosten

Kleine Web-App (PWA) für die Fixkosten: Posten mit Betrag und Frequenz anlegen, monatlich abhaken, sehen was noch offen ist.
Alle Daten bleiben lokal auf dem Gerät (localStorage). Es gibt keinen Server und kein Konto.

## Dateien
- `index.html`: die komplette App
- `manifest.webmanifest`, `icon-180.png`, `icon-512.png`: App-Name und Icon für den Home-Bildschirm
- `sw.js`: macht die App offline-fähig

## Auf GitHub Pages veröffentlichen
1. Auf github.com ein neues Repository anlegen, z. B. `fixkosten`.
2. „uploading an existing file“ wählen und die fünf Dateien oben hochladen. README optional.
3. Im Repo unter **Settings → Pages**: Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)`, dann **Save**.
4. Nach ca. 1 Minute läuft die App unter `https://<dein-github-name>.github.io/fixkosten/`.

> Bei einem kostenlosen GitHub-Account muss das Repository für Pages **öffentlich** sein. Öffentlich ist nur der Code, deine Zahlen nicht.

## Aufs iPhone
1. Den Link in **Safari** öffnen.
2. **Teilen → „Zum Home-Bildschirm“**.
3. Ab jetzt die App immer über das Icon öffnen. Das Icon und der Safari-Tab haben getrennte Speicher.

## Sicherung
Im Tab „Posten“ unter **Exportieren** die Daten als JSON speichern, z. B. in der Dateien-App/iCloud. Mit **Importieren** stellst du sie wieder her, z. B. auf einem neuen Handy.

## Update einspielen
Geänderte `index.html` im Repo ersetzen. Die App lädt beim nächsten Öffnen mit Internet automatisch die neue Version. Deine Daten bleiben erhalten.
