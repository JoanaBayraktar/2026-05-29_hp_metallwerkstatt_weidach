# Metallwerkstatt Weidach – Website

Statische Homepage für Metallwerkstatt Weidach GmbH, Feldkirchen-Westerham.

## Struktur

```
release/
├── index.html      # Haupt-HTML-Datei
├── images/         # Alle verwendeten Bilder
├── .gitignore
└── README.md
```

Externe Abhängigkeiten (werden live geladen, kein Download nötig):
- **Font Awesome 6** – Icons (cdnjs CDN)
- **Hind** – Schriftart (fonts.gstatic.com)

## Veröffentlichen via GitHub Pages

1. Neues Repository auf [github.com](https://github.com) anlegen
2. Diesen Ordner (`release/`) als Repo-Inhalt hochladen:
   ```bash
   cd release
   git init
   git add .
   git commit -m "Initial release"
   git branch -M main
   git remote add origin https://github.com/DEIN-USERNAME/REPO-NAME.git
   git push -u origin main
   ```
3. Im Repository: **Settings → Pages → Source: main / (root)** → Save
4. Die Seite ist unter `https://DEIN-USERNAME.github.io/REPO-NAME/` erreichbar

## Lokale Vorschau

Einfach `index.html` im Browser öffnen – funktioniert ohne Server.
