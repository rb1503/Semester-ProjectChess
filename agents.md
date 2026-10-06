# Hinweise für Coding Agents

## Projektziel

Das Projekt ist ein Schachspiel in Java für ein Kursprojekt zu strukturierter
Programmierung. Lies zuerst die vorhandenen Quelldateien und Dokumentation und
richte Änderungen an deren tatsächlichem Stand aus. Es handelt sich um das
Schachspiel selbst, nicht um ein Quiz über Schach.

## Verbindliche Programmierregeln

- Verwende strukturierte Programmierung mit Sequenz, Auswahl und Wiederholung.
- Nutze Records oder einfache Klassen nur, wenn sie Figuren oder Züge
  verständlicher darstellen.
- Verwende keine Vererbung, Collections oder sonstige höherwertige
  Java-Funktionen.
- Stelle das Schachbrett mit einem zweidimensionalen Array aus 8 × 8 Feldern
  dar.
- Bevorzuge einfache Variablen, Schleifen, Bedingungen und klar abgegrenzte
  Methoden für Anzeige, Eingabe, Zugprüfung und Zugausführung.
- Prüfe Eingaben vor dem Zugriff auf Array-Felder, damit ungültige Koordinaten
  keine Fehler verursachen.
- Trenne die Prüfung eines Zuges von dessen Ausführung: Ein ungültiger Zug
  darf den Brettzustand nicht verändern.
- Achte darauf, dass ein Spieler nach einer ungültigen Eingabe erneut ziehen
  kann und der Spielerwechsel erst nach einem gültigen Zug erfolgt.
- Halte den Kontrollfluss direkt und für Anfängerinnen und Anfänger gut
  nachvollziehbar.
- Füge keine Bibliotheken oder Abhängigkeiten hinzu, wenn die Aufgabe sie nicht
  ausdrücklich verlangt.

## Änderungen und Qualität

- Ändere nur Dateien, die für die angefragte Aufgabe relevant sind.
- Passe die Dokumentation an, wenn sich das geplante oder implementierte
  Verhalten ändert.
- Kennzeichne Anforderungen als geplant, solange sie nicht im Quellcode
  umgesetzt sind. Aktualisiere die Dokumentation, sobald der tatsächliche
  Funktionsumfang feststeht.
- Führe passende vorhandene Kompilierungs- oder Testscripte aus, wenn Java-Code
  geändert wurde; melde klar, wenn die Prüfung nicht möglich ist.
