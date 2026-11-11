<div align="center">

# 🍬 CandyTool

**Leistungsdaten in Echtzeit – direkt im Spiel.**
Performance-Overlay, Lüftersteuerung und GPU-Tuning in einem Tool für Windows.

[![Download](https://img.shields.io/github/v/release/CandyManHype/CandyTool-Releases?label=Download&style=for-the-badge&color=FF4FA3)](https://github.com/CandyManHype/CandyTool-Releases/releases/latest/download/CandyTool.exe)
&nbsp;
[![Downloads](https://img.shields.io/github/downloads/CandyManHype/CandyTool-Releases/total?style=for-the-badge&color=D63CFF)](https://github.com/CandyManHype/CandyTool-Releases/releases)

### [⬇️ CandyTool.exe herunterladen](https://github.com/CandyManHype/CandyTool-Releases/releases/latest/download/CandyTool.exe)

Eine einzige Datei – keine Installation, kein .NET, kein HWiNFO nötig.

</div>

---

## ✨ Was CandyTool kann

### 📊 In-Game-Overlay
- Zeigt FPS, Temperaturen, Auslastung, Takt, Leistung und mehr **live im Spiel**
- **Eigene Sensor-Erkennung** (LibreHardwareMonitor eingebaut) – keine Zusatzsoftware
- **Eigene FPS-Messung** – immer genau das Programm im Vordergrund, inkl. *Native FPS* ohne Frame-Generation-Zwischenbilder
- Werte frei auswählen, per Drag & Drop sortieren, umbenennen – als Zahl, Balken, Ring, Säulen oder Kurve
- **Warnschwellen** pro Sensor: kurzer Hinweis neben dem Overlay, ohne dem Spiel den Fokus zu stehlen
- Sensor-Sets speichern, z. B. „Rennen“ oder „Benchmark“
- Overlay immer sichtbar oder **nur in bestimmten Spielen**, frei platzierbar mit Einrasten an Rändern

### 🎨 Designs
- Design-Galerie mit Vorlagen, Farben und Größe frei anpassbar
- Eigene Designs speichern und mit einem Klick wechseln
- Eigene Farbschemata für das App-Fenster

### 🎮 Spielprofile
- Pro Spiel ein eigenes Sensor-Set, Design und Lüfterprofil
- Startet das Spiel, **schaltet CandyTool automatisch um**
- **Sitzungsbericht** nach dem Spielen: Ø FPS, 1 % Low, Höchsttemperaturen, Leistung und FPS-Verlauf – alle Sitzungen im Verlauf

### 🌀 Lüftersteuerung
- Mainboard-, Pumpen- und GPU-Lüfter über **eigene Kurven** steuern
- **Einrichtungsassistent**: prüft alle PWM-Ausgänge, ordnet Drehzahlsensoren zu und misst Min/Max automatisch
- Kurventypen: Graph, Linear, Fest, Trigger (Leerlauf/Last), Mix (Max/Min/Ø) und Sync
- Hysterese, Reaktionszeit, Start-/Stopp-Schwellen und Minimum pro Ausgang
- **Lüfterprofile** wie „Leise“, „Gaming“ oder „Benchmark“ – mit einem Klick wechseln
- Beim Beenden übernimmt automatisch wieder BIOS/Treiber

### ⚡ GPU-Tuning (NVIDIA)
- Powerlimit, Takt-Offsets, Taktbereiche und GPU-Lüfterkurve einstellen
- **V/F-Kurven-Editor** für Undervolting – Punkte einzeln ziehen oder ganze Kurve verschieben
- **Auto-Tune** (RTX 50): findet automatisch den besten stabilen Undervolt bzw. Takt mit einer selbstprüfenden Last (~5 Min.)
- **Tuning-Profile** wie „Effizienz“ oder „Leistung“
- **Sicherheitsnetz**: Nach dem Anwenden 15 Sekunden bestätigen – sonst wird automatisch zurückgesetzt, auch bei schwarzem Bild
- Über die offizielle NVIDIA-Schnittstelle (NVML) – jeder Wert wird nach dem Setzen zurückgelesen und geprüft
- Optional beim Windows-Start anwenden, jederzeit komplett abschaltbar

### 🟢 NVIDIA DLSS-Infos
- DLSS-Version, Modus, Preset, Render-Auflösung, Frame Generation und Ray Reconstruction im Spiel anzeigen
- Daten kommen direkt vom NVIDIA-Treiber – **kein Eingriff ins Spiel**

### 🛠️ Komfort
- **Systemcheck** beim Start – ein roter Punkt am Tray-Symbol zeigt Probleme
- Frei belegbare Tastenkürzel, Suche in allen Einstellungen (Strg + F)
- Deutsch & Englisch
- Einstellungen exportieren und importieren (Backup)
- Autostart, minimiert im Infobereich

---

## 💻 Voraussetzungen

| | |
|---|---|
| **System** | Windows 10 / 11 (64-Bit) |
| **Overlay & Lüfter** | Jede Hardware |
| **CPU-/Mainboard-Sensoren** | Kostenloser [PawnIO-Treiber](https://github.com/namazso/PawnIO.Setup/releases/latest) – CandyTool zeigt den Download-Link direkt in der App |
| **GPU-Tuning & DLSS-Infos** | NVIDIA-Grafikkarte · Auto-Tune & V/F-Kurve: RTX 50 |
| **Spiele** | Im Modus *Randloses Fenster* – exklusives Vollbild verdeckt jedes Overlay |

## 🚀 Loslegen
1. [**CandyTool.exe herunterladen**](https://github.com/CandyManHype/CandyTool-Releases/releases/latest/download/CandyTool.exe)
2. Starten und Lizenzschlüssel eingeben
3. Der Einrichtungsassistent führt dich durch den Rest

> **Hinweis:** Windows SmartScreen kann beim ersten Start warnen, weil die Datei neu ist. Klick auf *Weitere Informationen → Trotzdem ausführen*.

> ⚠️ GPU-Tuning kann bei zu hohen Werten zu Instabilität führen. Werte in kleinen Schritten ändern und andere Tuning-Tools (z. B. MSI Afterburner) vorher beenden.

---

## 📋 Updates
Alle Versionen und Änderungen findest du unter [**Releases**](https://github.com/CandyManHype/CandyTool-Releases/releases).
Neue Versionen werden außerdem automatisch auf dem Discord angekündigt.

<div align="center">
<sub>© 2026 CandyManHype</sub>
</div>
