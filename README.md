# 🧊 Structura - RegEx Wizard

Ein benutzerfreundlicher, visueller RegEx-Builder und Analyzer für Compliance-Berichte und Datenvalidierung – ganz ohne Programmierkenntnisse!

## 📋 Inhaltsverzeichnis

- [Überblick](#überblick)
- [Features](#features)
- [Verwendung](#verwendung)
- [Installation](#installation)
- [Technische Details](#technische-details)
- [Browser-Unterstützung](#browser-unterstützung)
- [Lizenz](#lizenz)
- [Mitwirken](#mitwirken)

## 🎯 Überblick

**Structura - RegEx Wizard** ist ein leistungsfähiger, bewusst eingeschränkter RegEx-Wizard, der speziell für Lern- und Trainingszwecke konzipiert wurde. Die Anwendung ist vollständig offline-fähig und datenschutzfreundlich.

### Zielgruppe

- **Nicht-technische Anwender**, die RegEx-Patterns verstehen und erstellen möchten
- **Business Analysten**, die Compliance-Berichte und Datenvalidierung durchführen
- **Lernende**, die RegEx-Konzepte visuell erlernen möchten

### Philosophie

Reguläre Ausdrücke (RegEx) wirken auf viele Nutzer abstrakt und abschreckend. Dieses Tool senkt diese Barriere und fördert ein grundlegendes Verständnis – besonders bei nicht-technischen Anwendern.

> **Hinweis:** Für produktionsreife RegEx-Ausdrücke empfehlen wir den Einsatz KI-gestützter Assistenten. Dieser Wizard dient als Lernwerkzeug – nicht als Ersatz für professionelle Tools.

## ✨ Features

### 🧩 RegEx Builder

- **Visuelle Pattern-Erstellung**: Erstellen Sie RegEx-Patterns durch Zusammenfügen von Bausteinen
- **Vorlagen**: Vorgefertigte Patterns für häufige Anwendungsfälle (E-Mail, IBAN, Telefonnummern, etc.)
- **Live-Vorschau**: Sehen Sie Ihr Pattern in Echtzeit
- **Test-Funktion**: Testen Sie Ihre Patterns direkt in der Anwendung
- **Bausteine**: Verschiedene Typen von Pattern-Komponenten:
  - Text (exakt)
  - Zahlen
  - Buchstaben
  - Gemischt (Buchstaben, Zahlen, Sonderzeichen)
  - Sonderzeichen
  - Auswahl (Choice)
  - Trennzeichen
  - Whitelist/Blacklist

### 🔍 RegEx Analyzer

- **Pattern-Analyse**: Verstehen Sie bestehende RegEx-Patterns
- **Komponenten-Erklärung**: Zerlegung komplexer Patterns in verständliche Komponenten
- **Flag-Erklärung**: Erklärung der verwendeten RegEx-Flags
- **Visuelle Darstellung**: Übersichtliche Darstellung aller Pattern-Komponenten

> **Hinweis:** In dieser Version wurde bewusst auf den Einsatz von KI verzichtet. Daher bestehen gewisse Einschränkungen bei der Analyse komplexerer Ausdrücke. Bei sehr komplexen RegEx-Patterns wird empfohlen, eine KI-gestützte Anwendung zu nutzen.

### 🎨 Benutzerfreundlichkeit

- **Zweisprachig**: Deutsch und Englisch
- **Dark Mode**: Unterstützung für dunkles Design
- **Barrierefreiheit**: WCAG 2.1 AA konform
- **Responsive Design**: Funktioniert auf Desktop, Tablet und Smartphone
- **Schriftgrößen**: Anpassbare Schriftgrößen für bessere Lesbarkeit
- **Offline-fähig**: Funktioniert vollständig ohne Internetverbindung
- **Datenschutz**: Keine Datenübertragung an externe Server

## 🚀 Verwendung

### Schnellstart

1. Öffnen Sie `index.html` in Ihrem Browser
2. Wählen Sie eine Vorlage oder beginnen Sie von Grund auf
3. Fügen Sie Bausteine hinzu und konfigurieren Sie diese
4. Testen Sie Ihr Pattern in der Live-Vorschau
5. Kopieren Sie das fertige Pattern

### RegEx Builder verwenden

1. **Vorlage wählen**: Klicken Sie auf eine Vorlage (z.B. "E-Mail", "IBAN")
2. **Bausteine hinzufügen**: Wählen Sie einen Baustein-Typ aus der Liste
3. **Konfigurieren**: Passen Sie die Einstellungen für jeden Baustein an
4. **Testen**: Verwenden Sie das Testfeld, um Ihr Pattern zu testen
5. **Kopieren**: Kopieren Sie das fertige Pattern mit einem Klick

### RegEx Analyzer verwenden

1. Klicken Sie auf "🔍 Starte Analyzer"
2. Geben Sie ein RegEx-Pattern ein (z.B. `/[A-Z]{2}[0-9]{9}/gmu`)
3. Klicken Sie auf "Analysieren"
4. Sehen Sie die Zerlegung des Patterns in Komponenten

## 📦 Installation

### Einfache Installation

1. Laden Sie das Repository herunter:
   ```bash
   git clone https://github.com/ihr-username/structura-regex-wizard.git
   ```

2. Öffnen Sie `index.html` in Ihrem Browser

Das war's! Keine zusätzlichen Abhängigkeiten oder Installationen erforderlich.

### Lokaler Webserver (empfohlen)

Für die beste Erfahrung empfehlen wir, die Anwendung über einen lokalen Webserver zu starten:

```bash
# Mit Python 3
python -m http.server 8000

# Mit Node.js (http-server)
npx http-server -p 8000

# Mit PHP
php -S localhost:8000
```

Öffnen Sie dann `http://localhost:8000` in Ihrem Browser.

## 🔧 Technische Details

### Technologie-Stack

- **HTML5**: Struktur
- **CSS3**: Styling mit CSS-Variablen für Theming
- **Vanilla JavaScript**: Keine externen Frameworks oder Bibliotheken
- **LocalStorage**: Persistierung von Einstellungen (optional)

### Architektur

- **Single-Page-Application**: Alle Funktionen in einer HTML-Datei
- **Modularer Code**: Organisiert in logische Funktionen
- **Event-Delegation**: Effiziente Event-Handling
- **State Management**: Zentraler State für die Anwendung

### Browser-Unterstützung

- ✅ Chrome/Edge (neueste Versionen)
- ✅ Firefox (neueste Versionen)
- ✅ Safari (neueste Versionen)
- ✅ Opera (neueste Versionen)

### Bekannte Einschränkungen

- Der Analyzer hat Einschränkungen bei sehr komplexen RegEx-Patterns
- Keine Unterstützung für alle erweiterten RegEx-Features
- Optimiert für Lernzwecke, nicht für Produktionsumgebungen

## 🌐 Browser-Unterstützung

Die Anwendung wurde getestet mit:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📄 Lizenz

Dieses Projekt steht unter der MIT-Lizenz. Siehe [LICENSE](LICENSE) für Details.

## 🤝 Mitwirken

Beiträge sind willkommen! Bitte beachten Sie:

1. Forken Sie das Repository
2. Erstellen Sie einen Feature-Branch (`git checkout -b feature/AmazingFeature`)
3. Committen Sie Ihre Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Pushen Sie zum Branch (`git push origin feature/AmazingFeature`)
5. Öffnen Sie einen Pull Request

### Entwicklungsrichtlinien

- Code sollte kommentiert und dokumentiert sein
- Neue Features sollten barrierefrei sein (WCAG 2.1 AA)
- Tests sollten für neue Features hinzugefügt werden
- Code-Style sollte konsistent sein

## 📞 Kontakt & Support

Bei Fragen oder Problemen:
- Öffnen Sie ein [Issue](https://github.com/ihr-username/structura-regex-wizard/issues)
- Erstellen Sie einen [Pull Request](https://github.com/ihr-username/structura-regex-wizard/pulls)

## 🙏 Danksagungen

- Erstellt für Lern- und Trainingszwecke
- Speziell entwickelt für Business Analysten und nicht-technische Anwender
- Inspiriert von der Notwendigkeit, RegEx zugänglicher zu machen

---

**Wichtig**: Dieses Tool ist für Lern- und Trainingszwecke gedacht. Für produktionsreife RegEx-Ausdrücke sollten Sie professionelle Tools oder KI-gestützte Assistenten verwenden.

