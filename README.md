# Website für Food Idle (GitHub Pages)

Diese Dateien werden **nicht** mit dem Spiel ausgeliefert. Sie liegen als Vorlage im Projekt und werden in ein
eigenes, öffentliches GitHub-Repository kopiert.

| Datei | Adresse nach dem Veröffentlichen |
|---|---|
| `index.html` | https://andysch99.github.io/ (Entwickler-Website für App Store und Google Play) |
| `foodidle/privacy.html` | https://andysch99.github.io/foodidle/privacy.html (Datenschutzerklärung, 6 Sprachen, `?lang=de` wählt die Sprache) |
| `app-ads.txt` | https://andysch99.github.io/app-ads.txt (Zeilen aus dem LevelPlay-Dashboard einfügen) |

## Veröffentlichen
1. Auf github.com ein neues **öffentliches** Repository mit dem Namen **`AndySch99.github.io`** anlegen (genau so).
2. `index.html`, `app-ads.txt` und den Ordner `foodidle/` hochladen (`Add file > Upload files`). Diese README nicht nötig.
3. Repository `Settings > Pages`: Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)`, Save.
4. Nach 1–2 Minuten die drei Adressen oben im Browser prüfen.

## Pflege
- Ändert sich, was das Spiel an Daten verarbeitet (neues Werbenetzwerk, In-App-Käufe, Login …), die Datenschutzerklärung
  in **allen 6 Sprachen** anpassen und das Datum („Stand“) aktualisieren.
- Die URL im Spiel steht in `Assets/Data/Ads/AdSettings.asset` (Privacy Policy Url).
