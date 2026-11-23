# Bibi Blocksberg Tracker (PWA)

Dark-mode Hörspiel-Tracker für alle Folgen 1–159.  
Fortschritt wird lokal im Browser gespeichert.

## Dateien

| Datei            | Beschreibung              |
|------------------|---------------------------|
| `index.html`     | Die App                   |
| `manifest.json`  | PWA Manifest              |
| `sw.js`          | Service Worker (offline)  |
| `icon-192.png`   | App-Icon 192×192          |
| `icon-512.png`   | App-Icon 512×512          |

## Auf GitHub Pages hosten (kostenlos)

### 1. Neues Repository erstellen
1. Gehe zu [github.com/new](https://github.com/new)
2. Name z. B. `bibi-tracker`
3. **Public** wählen → **Create repository**

### 2. Dateien hochladen
1. Im leeren Repo auf **uploading an existing file** klicken  
   **oder** lokal:
   ```bash
   git clone https://github.com/DEIN-USERNAME/bibi-tracker.git
   cd bibi-tracker
   # alle Dateien hier reinkopieren (index.html, manifest.json, sw.js, icon-*.png)
   git add .
   git commit -m "Bibi Tracker PWA"
   git push
   ```

### 3. GitHub Pages aktivieren
1. Im Repo → **Settings** → **Pages** (linke Seite)
2. Unter **Source**: **Deploy from a branch**
3. Branch: `main` (oder `master`), Ordner: `/ (root)`
4. **Save**

Nach 1–2 Minuten ist die App erreichbar unter:
```
https://DEIN-USERNAME.github.io/bibi-tracker/
```

### 4. Als App installieren

**Chrome / Edge (Desktop)**  
- Seite öffnen → Adressleiste rechts das **Installieren**-Symbol  
  oder Menü ⋮ → **App installieren / Cast, save and share → Install page as app**

**Chrome (Android)**  
- Menü ⋮ → **App installieren** / **Zum Startbildschirm hinzufügen**

**Safari (iPhone/iPad)**  
- Teilen-Button → **Zum Home-Bildschirm**

**Firefox**  
- Menü → **Installieren** (erscheint, sobald die Seite über HTTPS läuft)

---

Danach öffnet sich die App in einem eigenen Fenster ohne Browser-Leiste und funktioniert auch offline (Cover-Bilder brauchen Internet).
