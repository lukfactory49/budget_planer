# Budget 2026 – PWA

Persönliche Budget-App als Progressive Web App. Läuft offline auf iPhone und Android.

## Dateien

```
budget-2026/
├── index.html      ← Die App
├── sw.js           ← Service Worker (Offline-Support)
├── manifest.json   ← PWA-Manifest
├── icon-192.png    ← App-Icon
├── icon-512.png    ← App-Icon gross
└── README.md       ← Diese Datei
```

## Deployment auf GitHub Pages

### 1. GitHub Repository erstellen
- Gehe zu [github.com/new](https://github.com/new)
- Name: `budget-2026` (oder was du willst)
- Public setzen
- "Create repository" klicken

### 2. Dateien hochladen
- Im neuen Repo auf **"uploading an existing file"** klicken
- Alle 5 Dateien (index.html, sw.js, manifest.json, icon-192.png, icon-512.png) hochladen
- "Commit changes" klicken

### 3. GitHub Pages aktivieren
- Im Repo: **Settings** → **Pages**
- Source: **"Deploy from a branch"**
- Branch: **main** / Ordner: **/ (root)**
- **Save** klicken
- Nach ca. 1 Minute ist die App live unter:
  `https://DEIN-USERNAME.github.io/budget-2026/`

## Auf dem Handy installieren

### iPhone (Safari)
1. URL in Safari öffnen
2. **Teilen-Button** (Quadrat mit Pfeil nach oben) tippen
3. **"Zum Home-Bildschirm"** wählen
4. Fertig – die App läuft jetzt offline!

### Android (Chrome)
1. URL in Chrome öffnen
2. **Drei-Punkte-Menü** → **"App installieren"** oder **"Zum Startbildschirm hinzufügen"**
3. Fertig – läuft offline!

## Features

- **12 Monats-Budgets** mit Einnahmen, Fixkosten, Variable Kosten, Sparen
- **Jahresübersicht** mit Tabelle und Balkendiagramm
- **Variablekosten-Kategorien**: Essen, Hobby, Freizeit, Ferien, Haushalt
- **CHF-Formatierung**
- **Komplett offline** nach erstmaligem Laden
- **Daten lokal** auf dem Gerät gespeichert (kein Server, kein Account)
