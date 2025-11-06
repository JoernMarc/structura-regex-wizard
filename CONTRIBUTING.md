# Contributing to Structura - RegEx Wizard

Vielen Dank für Ihr Interesse, zu diesem Projekt beizutragen! 🎉

## Code of Conduct

- Seien Sie respektvoll und konstruktiv
- Helfen Sie anderen, zu lernen und zu wachsen
- Fokus auf Barrierefreiheit und Benutzerfreundlichkeit

## Wie kann ich beitragen?

### Fehler melden

Wenn Sie einen Fehler finden:
1. Prüfen Sie, ob der Fehler bereits gemeldet wurde
2. Erstellen Sie ein neues Issue mit:
   - Klarer Beschreibung des Problems
   - Schritten zur Reproduktion
   - Erwartetes vs. tatsächliches Verhalten
   - Browser und Version

### Features vorschlagen

Für neue Features:
1. Erstellen Sie ein Issue mit dem Label "enhancement"
2. Beschreiben Sie:
   - Was das Feature tun soll
   - Warum es nützlich wäre
   - Wie es die Benutzerfreundlichkeit verbessert

### Code beitragen

1. **Forken** Sie das Repository
2. **Erstellen** Sie einen Feature-Branch:
   ```bash
   git checkout -b feature/mein-feature
   ```
3. **Entwickeln** Sie Ihr Feature:
   - Folgen Sie dem bestehenden Code-Style
   - Fügen Sie Kommentare hinzu, wo nötig
   - Testen Sie Ihre Änderungen
4. **Committen** Sie Ihre Änderungen:
   ```bash
   git commit -m "Add: Beschreibung des Features"
   ```
5. **Pushen** Sie zum Branch:
   ```bash
   git push origin feature/mein-feature
   ```
6. **Öffnen** Sie einen Pull Request

## Entwicklungsrichtlinien

### Code-Style

- Verwenden Sie aussagekräftige Variablennamen
- Kommentieren Sie komplexe Logik
- Halten Sie Funktionen kurz und fokussiert
- Folgen Sie dem bestehenden Einrückungsstil (2 Leerzeichen)

### Barrierefreiheit

- Alle interaktiven Elemente sollten Tastatur-navigierbar sein
- Verwenden Sie semantisches HTML
- Stellen Sie sicher, dass der Kontrast WCAG 2.1 AA entspricht
- Fügen Sie `aria-label` Attribute hinzu, wo nötig

### Internationalisierung

- Alle Texte sollten in `i18n.de` und `i18n.en` verfügbar sein
- Verwenden Sie die `t()` Funktion für alle Benutzer-Texte
- Testen Sie beide Sprachen

### Testing

- Testen Sie Ihre Änderungen in verschiedenen Browsern
- Prüfen Sie die Responsive Darstellung
- Testen Sie die Barrierefreiheit mit Screenreadern

## Pull Request Prozess

1. Stellen Sie sicher, dass Ihr Code funktioniert
2. Aktualisieren Sie die Dokumentation, falls nötig
3. Beschreiben Sie Ihre Änderungen im Pull Request
4. Warten Sie auf Review und Feedback

## Fragen?

Bei Fragen können Sie:
- Ein Issue erstellen
- Einen Pull Request mit "WIP" (Work in Progress) Label öffnen

Vielen Dank für Ihre Beiträge! 🙏

