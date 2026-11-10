# MAGIC FORCE SYSTEM

Eine eigenständige, deutschsprachige Zauber-Web-App für Close-up-Magier und Mentalisten.

## Starten
- `index.html` im Browser öffnen (einige Browserfunktionen wie Service Worker/PWA sind bei `file://` eingeschränkt).
- Für Installation und Offline-Caching über HTTPS oder `localhost` bereitstellen, z. B. mit `python -m http.server 8000`.
- Anschließend `http://localhost:8000` öffnen. Auf dem Smartphone dieselbe App über eine HTTPS-Adresse aufrufen und „Zum Home-Bildschirm“ / „Installieren“ wählen.

## Magier-Menü
- Über das Menü-Symbol oben rechts, einen langen Druck auf das Logo oder das Logo-Menü öffnen.
- Erststart-PIN: **2580**. Bitte in **My Settings** ändern.
- Die PIN ist eine lokale Bedienungsschranke, keine starke Verschlüsselung gegen technisch versierte Nutzer.

## Module
- Image Force: Bilder importieren, Zielbild festlegen, Enthüllung starten. Bilder werden in IndexedDB gespeichert.
- Stranger System: eigene Auswahlmöglichkeiten und geheimes Ergebnis.
- Phone Call: kontrollierte Anruf-Simulation ohne echte Telefonverbindung.
- Card / Number / Word Force: konfigurierbare Zielwerte und Enthüllungsabläufe.
- Prediction: Vorhersagetext vorbereiten und enthüllen.
- Routines: Effekte als Schritte kombinieren, speichern und als Ablauf präsentieren.
- Settings: PIN, Akzentfarbe, Backup-Export/-Import und lokales Zurücksetzen.

## Speicherung & Datenschutz
Einstellungen und Routinen liegen in `localStorage`, Bilder in `IndexedDB`. Die App verwendet keine externen APIs und sendet keine Inhalte an einen Server. Backup-Dateien enthalten die exportierten Bilder und Konfigurationen; bewahre sie sicher auf.

## Hinweise
Die Force-Ansichten sind bewusst als kontrollierte Bühnenabläufe gestaltet. Für eine faire und klare Präsentation kann der Vorführende die Auswahl und den Zeitpunkt der Enthüllung selbst steuern. Der Phone-Call-Bereich ist ausdrücklich als Simulation gekennzeichnet und löst niemals echte Anrufe aus.
