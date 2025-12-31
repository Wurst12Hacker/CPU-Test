# CPU-Test

Ein einfaches Web-basiertes Tool zum Testen der CPU-Leistung deines lokalen Geräts. Der Test führt endlos wiederholte mathematische Berechnungen aus, um die CPU zu belasten und ihre Leistung zu messen.

## Funktionen

- **Endloser CPU-Lasttest**: Führt wiederholte Schleifen mit Berechnungen (z. B. Quadratwurzeln und Zufallszahlen) aus.
- **Anpassbare Parameter**:
  - Anzahl der Berechnungen pro Durchgang.
  - Zeitverzögerung zwischen den Durchläufen (in Millisekunden).
- **Start/Stop-Steuerung**: Einfache Buttons zum Starten und Stoppen des Tests.
- **Status-Anzeige**: Zeigt den aktuellen Status des Tests an.

## Verwendung

1. **Vorbereitung**:
   - Stelle sicher, dass du einen lokalen Webserver hast (z. B. mit Node.js oder einem anderen Server).
   - Beispiel mit Node.js: Erstelle eine `server.js` mit Express, um statische Dateien zu servieren.

2. **Ausführen**:
   - Öffne die Datei `.html` in einem Webbrowser (z. B. über `http://localhost:8080/.html`).
   - Passe die Eingabefelder an:
     - **Anzahl der Berechnungen pro Durchgang**: Wie viele CPU-intensive Aufgaben pro Intervall ausgeführt werden.
     - **Zeit zwischen den Durchläufen**: Verzögerung in ms zwischen den Durchläufen.
   - Klicke auf "Start Endlos Test", um den Test zu beginnen.
   - Überwache die CPU-Auslastung mit einem Systemmonitor (z. B. Task-Manager).
   - Klicke auf "Stop Test", um den Test zu beenden.

3. **Hinweise**:
   - Der Test läuft clientseitig im Browser und belastet die CPU deines Geräts.
   - Bei zu hoher Belastung kann der Browser einfrieren – verwende moderate Werte.
   - Für genauere Messungen kannst du Tools wie Chrome DevTools verwenden, um die Performance zu analysieren.

## Technologien

- **HTML/CSS/JavaScript**: Reine clientseitige Implementierung, kein Server erforderlich für den Test selbst.
- **Browser-Kompatibilität**: Funktioniert in modernen Browsern wie Chrome, Firefox, etc.

## Lizenz

Dieses Projekt ist Open-Source. Verwende es auf eigene Gefahr.