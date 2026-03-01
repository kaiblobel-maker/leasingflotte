# 🚗 Leasingflotte PWA – Kai Blobel · DVAG

Progressive Web App zur Verwaltung aller Leasingfahrzeuge.
Installierbar auf iPhone, iPad, Android und Desktop.

---

## 📦 Enthaltene Dateien

```
leasing-pwa/
├── index.html          ← Haupt-App
├── manifest.json       ← PWA-Konfiguration
├── sw.js               ← Service Worker (Offline-Support)
├── icons/
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-180x180.png  ← Apple Touch Icon
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
└── README.md
```

---

## 🚀 Schritt-für-Schritt: Auf GitHub Pages veröffentlichen

### Schritt 1 – GitHub-Konto anlegen (falls noch nicht vorhanden)
→ https://github.com → „Sign up"

### Schritt 2 – Neues Repository erstellen
1. Auf GitHub: grüner Button **„New"** oben links
2. Repository-Name: `leasingflotte` (oder beliebig)
3. Sichtbarkeit: **Public** (Pflicht für kostenloses GitHub Pages)
4. ✅ **„Add a README file"** anhaken
5. **„Create repository"** klicken

### Schritt 3 – Dateien hochladen
1. Im Repository auf **„Add file"** → **„Upload files"**
2. Alle Dateien aus dem `leasing-pwa/`-Ordner hochladen:
   - `index.html`, `manifest.json`, `sw.js`
   - Den kompletten `icons/`-Ordner (alle PNGs)
3. Unten: **„Commit changes"** klicken

### Schritt 4 – GitHub Pages aktivieren
1. Im Repository oben: **„Settings"**
2. Links: **„Pages"**
3. Unter „Branch": **`main`** auswählen, Ordner **`/ (root)`**
4. **„Save"** klicken
5. Nach ~1-2 Minuten erscheint die URL:
   `https://DEIN-USERNAME.github.io/leasingflotte/`

### Schritt 5 – Auf iPhone installieren
1. URL im **Safari** öffnen (wichtig: nicht Chrome!)
2. Unten: **Teilen-Button** (Quadrat mit Pfeil nach oben) tippen
3. Nach unten scrollen → **„Zum Home-Bildschirm"** tippen
4. Name ggf. anpassen → **„Hinzufügen"**
5. ✅ Die App erscheint als Icon auf dem Home-Bildschirm

---

## 📱 Funktionen der App

| Funktion | Beschreibung |
|---|---|
| **Dashboard** | 5 KPI-Kacheln, Live-Übersicht aller Fahrzeuge |
| **Fahrzeuge** | Verwalten, bearbeiten, löschen – mit Restlaufzeit-Ampel |
| **Notizen** | Telefonprotokolle, Gesprächsnotizen, To-Dos mit Erledigt-Status |
| **Export** | CSV (Excel-kompatibel) + JSON-Backup + Backup-Import |
| **Offline** | App funktioniert ohne Internet (Service Worker) |
| **Dark/Light** | Automatisch je nach iPhone-Systemeinstellung |

---

## 💾 Datenspeicherung

Alle Daten werden im **localStorage** des Browsers gespeichert.
Sie bleiben dauerhaft erhalten, auch nach Neustart.

> **Wichtig:** Daten sind gerätespezifisch. Für Synchronisation
> zwischen iPhone und PC → CSV/JSON-Export nutzen.

---

## 🔄 Updates einspielen

Neue Version der `index.html` einfach auf GitHub hochladen
(„Add file" → „Upload files" → vorhandene Datei überschreiben).
Der Service Worker aktualisiert sich automatisch beim nächsten Start.

---

*Erstellt für Kai Blobel · Deutsche Vermögensberatung (DVAG) · 2026*
