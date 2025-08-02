# 🤖 ClayNow - Intelligenter KI-Assistent

<div align="center">

![ClayNow Logo](https://img.shields.io/badge/ClayNow-AI%20Assistant-blue?style=for-the-badge&logo=robot)
[![Version](https://img.shields.io/badge/Version-5.0.4-green?style=for-the-badge)](https://github.com/claytechnologie/ClayNowCode)
[![License](https://img.shields.io/badge/License-ClayTechnologies-orange?style=for-the-badge)](https://claytechnologies.com)

**Der fortschrittlichste deutschsprachige KI-Assistent für Windows**

[🚀 Download](#-installation) • [📖 Funktionen](#-hauptfunktionen) • [🎤 Sprachsteuerung](#-sprachsteuerung) • [⚙️ Konfiguration](#-konfiguration) • [🆘 Support](#-support)

</div>

---

## 📋 Inhaltsverzeichnis

- [� Was ist ClayNow?](#-was-ist-claynow)
- [✨ Hauptfunktionen](#-hauptfunktionen)
- [🚀 Installation](#-installation)
- [🎤 Sprachsteuerung](#-sprachsteuerung)
- [🌐 Web-Interface](#-web-interface)
- [💡 LED-Unterstützung](#-led-unterstützung)
- [📧 Email-Manager](#-email-manager)
- [⚙️ Konfiguration](#-konfiguration)
- [🔧 Systemanforderungen](#-systemanforderungen)
- [🆘 Support](#-support)

---

## 🎯 Was ist ClayNow?

ClayNow ist ein **intelligenter KI-Assistent**, der speziell für deutschsprachige Benutzer entwickelt wurde. Er kombiniert modernste **Spracherkennung**, **KI-gestützte Antworten** und **automatisierte Aufgaben** in einem benutzerfreundlichen System.

### 🌟 Warum ClayNow?

- **🇩🇪 Vollständig auf Deutsch** - Perfekte deutsche Spracherkennung und -ausgabe
- **🧠 KI-Powered** - Integration mit OpenAI GPT für intelligente Antworten
- **🎤 Natürliche Sprache** - Sprechen Sie mit ClayNow wie mit einem Menschen
- **🔧 Automatisierung** - Übernimmt lästige Aufgaben für Sie
- **🎨 Modern & Intuitiv** - Elegante Benutzeroberfläche mit Dark Mode
- **🔒 Datenschutz** - Ihre Daten bleiben lokal gesichert

---

## ✨ Hauptfunktionen

### 🎤 **Intelligente Sprachsteuerung**
- **Adaptive Spracherkennung** - Hört zu, bis Sie fertig gesprochen haben
- **Natürliche Konversation** - Sprechen Sie in ganzen Sätzen
- **Personalisierte Befehle** - Erstellen Sie eigene Sprachbefehle
- **Mehrere Wake-Words** - "Hey ClayNow", "Computer" oder benutzerdefiniert

### 🤖 **KI-Assistent Funktionen**
- **Fragen & Antworten** - Stellen Sie beliebige Fragen auf Deutsch
- **Internetsuche** - Automatische Recherche mit Brave Search
- **Textverarbeitung** - Zusammenfassungen, Übersetzungen, Analysen
- **Kreative Aufgaben** - Geschichten, Gedichte, Ideen generieren

### 🌐 **Web-Interface**
- **Moderne Benutzeroberfläche** - Zugänglich über jeden Browser
- **Chat-Interface** - Schriftliche Kommunikation mit ClayNow
- **Dashboard** - Übersicht über Status und Aktivitäten
- **Mobile Optimiert** - Funktioniert auf Smartphone und Tablet

### 🔧 **Automatisierung & Tools**
- **System-Integration** - Steuert Windows-Funktionen
- **Timer & Erinnerungen** - Persönlicher Zeitmanager
- **Email-Manager** - Professionelle Email-Verwaltung mit Templates
- **Datei-Operationen** - Organisiert und verwaltet Ihre Dateien

### 💡 **LED-Unterstützung**
- **Visuelle Statusanzeige** - LED-Strips zeigen ClayNow's Status
- **Atmosphärische Beleuchtung** - Stimmungsvolle Raumbeleuchtung
- **Reaktive Effekte** - LEDs reagieren auf Sprache und Musik
- **Anpassbare Farben** - Wählen Sie Ihr persönliches Farbschema

---

## 🚀 Installation

### 📦 **Einfache Installation**

1. **Download** - Laden Sie die neueste Version von GitHub herunter
2. **Entpacken** - Extrahieren Sie das ZIP-Archiv
3. **Installer ausführen** - Starten Sie `ClayNow_Installer.exe`
4. **Konfiguration** - Folgen Sie dem Setup-Assistenten
5. **Fertig!** - ClayNow ist bereit für den Einsatz

### ⚡ **Schnellstart**

```
1. Öffnen Sie ClayNow
2. Sagen Sie "Hey ClayNow"
3. Stellen Sie eine Frage oder geben Sie einen Befehl
4. ClayNow antwortet automatisch
```

### 🔑 **API-Konfiguration**

Für die volle Funktionalität benötigen Sie:
- **OpenAI API Key** - Für KI-Funktionen
- **Brave Search API Key** - Für Internetsuche (optional)
- **Picovoice Access Key** - Für erweiterte Spracherkennung (optional)

*Alle API-Keys werden sicher lokal gespeichert.*

3. **Dependencies installieren**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Konfiguration**:
   - OpenAI API Key in `config/openai_config.json` eintragen
   - Weitere Einstellungen in `config.py` anpassen

5. **Starten**:
   ```bash
   python main.py
   ```

## 📋 Hauptkomponenten

### **Adaptive Speech Detection**
```python
# modules/speech_recognition/adaptive_speech_detector.py
- Intelligente Pausenerkennung
- Wort-basierte Timeout-Berechnung  
- Kontextbewusste Anpassungen
- Lernende Algorithmen
```

### **Voice Command System**
```python
# modules/command/voice_command_processor.py
- 10 Automatisierungstypen
- Fuzzy String Matching
- Command Execution Engine
- AI-basierte Validierung
```

### **Qt5 Overlay System**
```python
# modules/utils/qt_overlay.py
- Transparente System-Integration
- Animierte Status-Anzeigen
- Kontextmenü-System
- Thread-sichere GUI
```

### **Conversation Processing**
```python
# main_process/conversation_processor.py
- OpenAI GPT Integration
- Kontext-Management
- Intent Recognition
- Response Generation
```

## 🎯 Neueste Updates

### **Smart Listening System (v5.10)**
- ✅ **Keine Unterbrechungen** mehr bei längeren Sätzen
- ✅ **Intelligente Timeout-Anpassung** basierend auf Satzlänge
- ✅ **Kontexterkennung** für Such-Anfragen und komplexe Befehle
- ✅ **Lernfähige Algorithmen** für personalisierte Anpassung

### **Voice Command Creation (v5.9)**
- ✅ **GUI-basierte Command-Erstellung**
- ✅ **AI-Validierung** und Optimierung
- ✅ **10 Automatisierungstypen** verfügbar
- ✅ **Pipeline-Integration** ohne Doppelverarbeitung

## 🔧 Konfiguration

### **Adaptive Listening**
```python
# config.py
ADAPTIVE_LISTENING_ENABLED = True
ADAPTIVE_BASE_SILENCE_TIMEOUT = 1.2  # Basis-Pause
ADAPTIVE_MAX_SILENCE_TIMEOUT = 4.0   # Maximum für komplexe Sätze
ADAPTIVE_MIN_SILENCE_TIMEOUT = 0.6   # Minimum für schnelle Commands
```

### **Voice Recognition**
```python
WHISPER_MODEL = "whisper-1"
GPT_MODEL = "gpt-3.5-turbo" 
TTS_MODEL = "tts-1"
TTS_VOICE = "onyx"
```

## 📁 Projektstruktur

```
ClayNowCode/
├── main.py                     # Haupteinstiegspunkt
├── config.py                   # Zentrale Konfiguration
├── requirements.txt            # Python Dependencies
├── 
├── modules/
│   ├── speech_recognition/     # Spracherkennung & Adaptive Logic
│   ├── command/               # Voice Command System
│   ├── utils/                 # Qt5 Overlay & Utilities
│   └── ...
├── 
├── main_process/              # Conversation Processing
├── config/                    # Konfigurationsdateien
├── data/                      # Daten, Cache, Assets
├── logs/                      # System-Logs
└── docs/                      # Dokumentation
```

## 🛠️ Entwicklung

### **Testing**
```bash
# Unit Tests
python -m pytest tests/

# Integration Tests  
python test_integrated_system.py

# Voice Command Tests
python test_voice_commands.py
```

### **Debugging**
- Detaillierte Logs in `logs/`
- Debug-Modi in `config.py`
- Performance-Monitoring verfügbar

## 📝 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert - siehe [LICENSE](LICENSE) für Details.

## 🤝 Beitragen

1. Fork das Repository
2. Erstelle einen Feature-Branch (`git checkout -b feature/AmazingFeature`)
3. Committe deine Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen Pull Request

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/claytechnologie/ClayNowCode/issues)
- **Dokumentation**: [Wiki](https://github.com/claytechnologie/ClayNowCode/wiki)
- **Website**: [claytechnologie.com](https://claytechnologie.com)

---
**Entwickelt von ClayTechnologie** | **Powered by OpenAI & Qt5**
