# 🎯 Blacklist V Scripts - Image to Lua Converter

<div align="center">

![Blacklist V Scripts](https://img.shields.io/badge/Blacklist%20V-Scripts-blue?style=for-the-badge&logo=python)
![Python](https://img.shields.io/badge/Python-3.8%2B-green?style=for-the-badge&logo=python)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**Ein modernes, professionelles Tool zur automatischen Generierung von ox_inventory Lua-Dateien aus Bildern**

[🌐 Website](https://blacklistv-scripts.tebex.io/) • [📖 Dokumentation](#dokumentation) • [🚀 Installation](#installation) • [💡 Features](#features)

</div>

---

## 📋 Überblick

**Blacklist V Scripts** ist ein leistungsstarkes Windows-Tool, das Bilder automatisch analysiert und daraus realistische `items.lua`-Dateien für das ox_inventory System generiert. Mit modernem Material Design, Light/Dark Mode und intelligenter Bilderkennung macht es die Erstellung von Inventar-Items zum Kinderspiel.

### 🎯 Hauptzweck
- **Automatische Bilderkennung** - Erkennt Objekte in Bildern und kategorisiert sie
- **Realistische Gewichte** - Generiert realistische Gewichte basierend auf Objektkategorien
- **ox_inventory Kompatibel** - Erstellt perfekt formatierte Lua-Dateien
- **Benutzerfreundlich** - Moderne UI mit Drag & Drop und Live-Preview

---

## ✨ Features

### 🖼️ **Intelligente Bilderkennung**
- **OpenCV Integration** - Fortgeschrittene Computer Vision (optional)
- **Keyword-basierte Erkennung** - Funktioniert auch ohne OpenCV
- **Mehrsprachig** - Unterstützt deutsche und englische Keywords
- **Kategorisierung** - Automatische Einordnung in Waffen, Fahrzeuge, Items, etc.

### 🎨 **Moderne Benutzeroberfläche**
- **Material Design** - Professionelles, modernes Design
- **Light & Dark Mode** - Umschaltbare Themes
- **Responsive Layout** - Funktioniert in verschiedenen Fenstergrößen
- **Scrollbar Support** - Alle Inhalte sind immer erreichbar
- **Live Preview** - Sofortige Vorschau der generierten Lua-Datei

### 🌍 **Internationalisierung**
- **Deutsch & Englisch** - Vollständige Sprachunterstützung
- **Dynamische UI** - Alle Texte werden automatisch übersetzt
- **Konsistente Terminologie** - Einheitliche Übersetzungen

### 🔧 **Technische Features**
- **Batch-Verarbeitung** - Verarbeitet mehrere Bilder gleichzeitig
- **Thumbnail-Ansicht** - Übersichtliche Bildvorschau
- **Fehlerbehandlung** - Robuste Fehlerbehandlung und Logging
- **EXE-Support** - Kann als standalone .exe-Datei ausgeführt werden

---

## 🚀 Installation

### Option 1: Python-Installation (Empfohlen)

```bash
# Repository klonen
git clone https://github.com/yourusername/blacklist-v-scripts.git
cd blacklist-v-scripts

# Abhängigkeiten installieren
pip install -r requirements.txt

# Programm starten
python blv_converter.py
```

### Option 2: Windows Batch-Installation

```bash
# Vollständige Installation (mit OpenCV)
install.bat

# Oder einfache Installation (ohne OpenCV)
install_simple.bat
```

### Option 3: EXE-Datei (Standalone)

```bash
# EXE-Datei herunterladen und direkt ausführen
BlacklistVScripts.exe
```

---

## 📖 Verwendung

### 1. **Bilder auswählen**
- Klicken Sie auf "Select Images" oder "Select Folder"
- Wählen Sie Ihre Bilder aus (PNG, JPG, JPEG unterstützt)

### 2. **Bilder analysieren**
- Klicken Sie auf "Analyze Images"
- Das System erkennt automatisch Objekte und kategorisiert sie

### 3. **Lua-Datei generieren**
- Klicken Sie auf "Generate Lua"
- Die `items.lua`-Datei wird automatisch erstellt

### 4. **Vorschau anzeigen**
- Nutzen Sie die Live-Preview-Funktion
- Überprüfen Sie die generierten Items vor dem Export

---

## 🎯 Unterstützte Objektkategorien

| Kategorie | Beispiele | Gewicht |
|-----------|-----------|---------|
| **Waffen** | Pistole, Gewehr, Messer | 0.5 - 3.0 kg |
| **Fahrzeuge** | Auto, Motorrad, Fahrrad | 50 - 2000 kg |
| **Drogen** | Kokain, Heroin, Marihuana | 0.1 - 0.5 kg |
| **Geld** | Bargeld, Gold, Schmuck | 0.01 - 1.0 kg |
| **Medizin** | Verband, Medikamente | 0.1 - 0.3 kg |
| **Elektronik** | Handy, Laptop, Kamera | 0.2 - 2.0 kg |
| **Kleidung** | Shirt, Hose, Schuhe | 0.3 - 1.5 kg |
| **Werkzeuge** | Hammer, Schraubendreher | 0.5 - 2.0 kg |
| **Sonstiges** | Verschiedene Items | 0.1 - 5.0 kg |

---

## 🔧 Technische Details

### **Systemanforderungen**
- **Betriebssystem**: Windows 10/11
- **Python**: 3.8+ (optional, wenn EXE verwendet wird)
- **RAM**: 4 GB empfohlen
- **Speicher**: 100 MB freier Speicherplatz

### **Abhängigkeiten**
- `tkinter` - GUI Framework
- `Pillow (PIL)` - Bildverarbeitung
- `opencv-python` - Computer Vision (optional)
- `numpy` - Numerische Operationen
- `pathlib` - Pfadverwaltung
- `webbrowser` - Web-Integration

### **Unterstützte Bildformate**
- PNG (.png)
- JPEG (.jpg, .jpeg)
- BMP (.bmp)
- TIFF (.tiff)

---

## 🎨 Screenshots

<div align="center">

### Light Mode
![Light Mode Interface](docs/screenshots/light-mode.png)

### Dark Mode
![Dark Mode Interface](docs/screenshots/dark-mode.png)

### Live Preview
![Live Preview](docs/screenshots/live-preview.png)

</div>

---

## 🤝 Beitragen

Wir freuen uns über Beiträge! Hier ist, wie Sie helfen können:

### **Bug Reports**
- Erstellen Sie ein Issue mit detaillierter Beschreibung
- Fügen Sie Screenshots und Log-Dateien hinzu
- Beschreiben Sie die Schritte zur Reproduktion

### **Feature Requests**
- Beschreiben Sie Ihre Idee detailliert
- Erklären Sie den Nutzen für andere Benutzer
- Fügen Sie Mockups oder Beispiele hinzu

### **Code Contributions**
1. Forken Sie das Repository
2. Erstellen Sie einen Feature-Branch
3. Committen Sie Ihre Änderungen
4. Erstellen Sie einen Pull Request

---

## 📄 Lizenz

Dieses Projekt steht unter der MIT-Lizenz. Siehe [LICENSE](LICENSE) für Details.

---

## 🙏 Danksagungen

- **ox_inventory** - Für das großartige Inventar-System
- **OpenCV** - Für die Computer Vision-Funktionalität
- **Pillow** - Für die Bildverarbeitung
- **tkinter** - Für das GUI-Framework

---

<div align="center">

**Entwickelt mit ❤️ für die FiveM Community**

[⬆ Nach oben](#-blacklist-v-scripts---image-to-lua-converter)

</div>
