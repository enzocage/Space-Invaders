# Space Invaders 🛸

Ein klassisches Space Invaders Spiel, komplett in HTML5 Canvas und JavaScript implementiert. Zerstöre die feindlichen Invasoren, sammle Punkte und überlebe so viele Level wie möglich!

## ✨ Features

- **Klassisches Gameplay**: Authentisches Space Invaders Erlebnis mit modernen Verbesserungen
- **Mehrere Gegnertypen**: Drei verschiedene Gegnertypen mit unterschiedlichen Farben und Verhaltensweisen
- **Progressive Schwierigkeit**: Jedes Level wird schwieriger mit mehr Gegnern und schnellerer Bewegung
- **Soundeffekte**: Integrierte Soundeffekte mit Web Audio API (keine externen Dateien benötigt)
- **Partikeleffekte**: Visuelle Explosionen und Effekte für besseres Feedback
- **Responsive Design**: Funktioniert auf Desktop und mobilen Geräten
- **Touch-Steuerung**: Optimierte Touch-Controls für mobile Geräte
- **Tastaturunterstützung**: Vollständige Tastatursteuerung für Desktop
- **Score-System**: Punkte, Leben und Level-Boni
- **Deutschsprachige UI**: Komplette deutsche Benutzeroberfläche

## 🎮 Spielablauf

- Bewege dein Raumschiff mit den Pfeiltasten oder Touch-Buttons
- Schieße automatisch auf die Gegner
- Zerstöre alle Gegner, um das Level zu beenden
- Sammle Punkte und überlebe so lange wie möglich
- Bei Game Over kannst du ein neues Spiel starten

## 🕹️ Steuerung

### Desktop (Tastatur)
- **← / →** oder **A / D**: Raumschiff bewegen
- **Leertaste**: Schießen (optional, Auto-Schuss ist aktiviert)

### Mobile (Touch)
- **◀ Links / Rechts ▶ Buttons**: Raumschiff mit Buttons steuern
- **Direkte Touch-Steuerung**: Tippe auf linke/rechte Bildschirmhälfte
- **Mehrfach-Touch**: Bei gleichzeitiger Berührung zählt die letzte Touch-Position
- **Tippen auf Canvas**: Audio aktivieren

## 🚀 Installation & Verwendung

### Lokale Ausführung
1. Lade die Datei `<!DOCTYPE html>.html` herunter
2. Öffne die Datei in einem modernen Webbrowser
3. Das Spiel startet automatisch

### Webserver (empfohlen)
Für die beste Erfahrung, besonders für Audio-Funktionen:
```bash
# Mit Python (falls installiert)
python -m http.server 8000

# Oder mit Node.js
npx http-server

# Dann öffne http://localhost:8000/<!DOCTYPE%20html>.html
```

## 🛠️ Technische Details

### Technologien
- **HTML5 Canvas**: Für 2D-Grafik-Rendering
- **JavaScript (ES6+)**: Spiel-Logik und Interaktivität
- **Web Audio API**: Für prozedurale Soundeffekte
- **CSS3**: Responsive Design und Styling

### Browser-Kompatibilität
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile Safari
- ✅ Chrome Mobile

### Dateistruktur
```
Space-Invaders/
├── <!DOCTYPE html>.html    # Hauptspiel-Datei
└── README.md              # Diese Dokumentation
```

### Spielmechanik
- **Canvas-Größe**: Automatisch angepasst (max. 800x600px)
- **Frame-Rate**: 60 FPS mit requestAnimationFrame
- **Kollisionserkennung**: AABB (Axis-Aligned Bounding Box)
- **Partikelsystem**: Für visuelle Effekte
- **Level-Progression**: Dynamische Gegner-Erzeugung

## 🎨 Visuelle Features

- **Animierte Sterne**: Parallax-Hintergrund mit pulsierenden Sternen
- **Farbige Gegner**: Rot, Orange und Lila Gegnertypen
- **Glüh-Effekte**: Leuchtende Schüsse und Effekte
- **Partikelexplosionen**: Bei Zerstörung von Gegnern oder Spieler
- **Responsive UI**: Anpassung an verschiedene Bildschirmgrößen

## 🔊 Audio-System

- **Prozedurale Sounds**: Alle Sounds werden programmatisch generiert
- **Web Audio API**: Für präzise Soundsteuerung
- **Soundtypen**:
  - Schüsse: Quadratwellen (hohe Frequenz)
  - Gegner-Schüsse: Sägezahnwellen (mittlere Frequenz)
  - Explosionen: Verschiedene Wellenformen
  - Level-Complete: Mehrfach-Töne

## 📱 Mobile Optimierung

- **Touch-Controls**: Große, leicht zu bedienende Buttons
- **Responsive Canvas**: Automatische Größenanpassung
- **Touch-Events**: Verhinderung von Standard-Scroll-Verhalten
- **Mobile UI**: Optimierte Button-Größen für Touch-Geräte

## 🏆 Score-System

- **Basis-Punkte**: 10 Punkte pro zerstörtem Gegner
- **Level-Bonus**: Zusätzliche Punkte je Level
- **Lebens-Bonus**: 100 Punkte pro verbleibendem Leben
- **Level-Complete-Bonus**: Zusätzliche Punkte für Level-Abschluss

## 🔧 Anpassungen

Das Spiel kann durch Änderung der JavaScript-Variablen angepasst werden:
- `gameState.shootCooldown`: Schuss-Abklingzeit
- `player.speed`: Spieler-Geschwindigkeit
- `enemy.speed`: Gegner-Geschwindigkeit
- `gameState.lives`: Anzahl Leben

## 🤝 Mitwirken

Beiträge sind willkommen! Mögliche Verbesserungen:
- Neue Gegnertypen
- Power-Ups
- Mehr Soundeffekte
- Highscore-System
- Mehr Levels
- Zusätzliche Spielmodi

## 📄 Lizenz

Dieses Projekt ist Open Source. Die Nutzung ist frei für private und kommerzielle Zwecke.

## 🎯 Zukünftige Features

- [ ] Highscore-Tabelle
- [ ] Verschiedene Schwierigkeitsgrade
- [ ] Power-Ups (Leben, Waffen-Upgrades)
- [ ] Mehr Gegnertypen
- [ ] Boss-Kämpfe
- [ ] Mehrere Spielmodi
- [ ] Soundeffekte anpassen

---

**Viel Spaß beim Spielen! 🚀**