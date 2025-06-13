# 🌐 Lokale Startseiten-Sammlung (🇩🇪 Deutsch)

Dieses Repository enthält eine Sammlung minimalistischer und individuell gestalteter **Startpages**, die lokal im Browser als Startseite genutzt werden können. Jede Startpage besteht aus einer einzigen HTML-Datei – mit eingebettetem CSS und JavaScript (keine Abhängigkeiten, keine CDNs, keine externen Skripte).

---

## 📁 Struktur

```bash
/
├── minimal-dark.html
├── dashboard-tech.html
├── retro-terminal.html
├── productivity-grid.html
└── README.md
```

---

## 🚀 Verwendung

1. Dieses Repository herunterladen oder klonen:
   ```bash
   git clone https://github.com/USERNAME/startpages.git
   ```
2. Wähle eine Datei (z. B. `minimal-dark.html`) und öffne sie im Browser.
3. Speichere die Datei an einem unauffälligen lokalen Ort, z. B.:

   - `C:\Users\<Name>\.startpages\`
   - `~/Documents/.homepages/`

   > Verzeichnisse mit `.` am Anfang sind unter Unix-Systemen oft versteckt – ideal für minimalen visuellen „Footprint“.

4. Lege die Datei als Startseite im Browser fest:

### 🔧 Startseite im Browser einstellen

#### 🦊 Firefox

- Einstellungen → Startseite
- „Benutzerdefinierte URL“ → `file:///C:/Users/<Name>/.startpages/minimal-dark.html`

#### 🌐 Chrome / Chromium / Edge

- Einstellungen → Beim Start → „Bestimmte Seite oder Seiten öffnen“
- Seite hinzufügen → `file:///...`

> Pfad muss lokal exakt zur Datei passen. Alternativ: Datei im Browser öffnen → Rechtsklick → „Als Startseite festlegen“ (sofern unterstützt).

---

## 🎯 Features

- ✅ Komplett offline nutzbar
- 🎨 Verschiedene Themes und Layouts
- 🛠️ Einfach modifizierbar (alle Ressourcen inline)
- 🔐 Keine externen Skripte, keine Datenübertragung
- 🧑‍💻 Ideal für Homelab-Setups, Dev-Umgebungen oder personalisierte Dashboards

---

## 🛠️ Anpassung

HTML öffnen → direkt editieren:
- Links, Icons, Farben, Widgets, Suchleisten usw.
- Keine speziellen Tools erforderlich

---

## 📄 Lizenz

MIT-Lizenz – freie Nutzung & Anpassung erlaubt.

---

---

# 🌐 Local Startpages Collection (🇬🇧 English)

This repository contains a collection of minimal, customizable **local startpages**, each written in a single HTML file (with embedded CSS and JavaScript). Designed for offline use as a personal browser homepage.

---

## 📁 Structure

```bash
/
├── minimal-dark.html
├── dashboard-tech.html
├── retro-terminal.html
├── productivity-grid.html
└── README.md
```

---

## 🚀 Usage

1. Download or clone this repository:
   ```bash
   git clone https://github.com/USERNAME/startpages.git
   ```
2. Choose a file and open it in your browser.
3. Save it somewhere discreet, e.g.:

   - `C:\Users\<Name>\.startpages\`
   - `~/Documents/.homepages/`

   > Dotfolders (`.foldername`) are usually hidden and reduce visual noise.

4. Set the file as your browser's homepage:

### 🔧 Set as Start Page

#### 🦊 Firefox

- Settings → Home → Custom URL → `file:///C:/Users/<Name>/.startpages/minimal-dark.html`

#### 🌐 Chrome / Chromium / Edge

- Settings → On startup → Open a specific page
- Add the full `file:///...` path to the HTML file

> Alternatively: Open the file in the browser → Right-click → Set as homepage (if supported)

---

## 🎯 Features

- Fully offline & self-contained
- Multiple themes and layouts
- All logic & styles are inline
- No tracking, no external calls
- Perfect for Homelab, Dev, Productivity, or Clean Dashboards

---

## 🛠️ Customization

Just open the HTML in your editor and change:

- Links, icons, colors, layouts
- No build step or tools required

---

## 📄 License

Licensed under MIT – free to use, modify, and distribute.
