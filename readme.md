# Java-Schachspiel

## Überblick

Dieses Projekt ist ein Schachspiel in Java für das Modul „Strukturierte
Programmierung“. Zwei Personen spielen abwechselnd auf einem Schachbrett
gegeneinander. Ziel ist es, den gegnerischen König mattzusetzen.

## Geplanter Ablauf

1. Zu Beginn stellt das Programm die Figuren in der üblichen Grundstellung auf
   und zeigt, dass Weiß am Zug ist.
2. Das Brett wird nach jedem Zug mit den Koordinaten von a bis h und 1 bis 8
   angezeigt. Leere Felder und die weißen und schwarzen Figuren sollen klar
   unterscheidbar sein.
3. Der aktuelle Spieler gibt die Koordinaten des Start- und Zielfelds ein,
   zum Beispiel `e2 e4`.
4. Das Programm prüft die Eingabe und die Bewegungsregeln der ausgewählten
   Figur. Ein ungültiger Zug wird erklärt; derselbe Spieler darf erneut
   eingeben.
5. Nach einem gültigen Zug wird das Brett aktualisiert. Eine geschlagene
   gegnerische Figur wird vom Brett entfernt und der andere Spieler ist am Zug.
6. Das Spiel läuft weiter, bis Schachmatt erreicht ist oder die Partie
   ausdrücklich beendet wird.

## Technische Vorgaben

Die Lösung soll die Grundlagen der strukturierten Programmierung verwenden:

- sequenzielle Anweisungen, Bedingungen und Schleifen,
- ein zweidimensionales Array mit 8 Zeilen und 8 Spalten zur Darstellung des
  Bretts,
- einfache Zeichen oder Werte zur Unterscheidung der sechs Figurentypen und
  ihrer Farben,
- überschaubare Methoden für die Brettanzeige, Eingabe, Zugprüfung und
  Zugausführung,
- Records oder einfache Klassen nur dann, wenn Figuren- oder Zugdaten dadurch
  verständlicher zusammengefasst werden.

Abstraktionen, Vererbung, Collections und andere höherwertige Java-Funktionen
sollen nicht verwendet werden. Der Programmablauf soll direkt nachvollziehbar
und für den Kurs leicht verständlich bleiben.

## Umfang und aktueller Stand

Die Markdown-Dateien beschreiben den geplanten Funktionsumfang. Im Projekt
liegen derzeit noch keine Java-Quelldateien; das Schachspiel selbst ist daher
noch nicht implementiert. Die erste Version kann sich auf die Grundaufstellung,
abwechselnde Züge, die Bewegungsregeln und das Schlagen von Figuren
konzentrieren. Schachmattprüfung und Sonderzüge wie Rochade, En-passant und
Bauernumwandlung können schrittweise ergänzt werden.

## Ausführen

Das Projekt enthält derzeit die Dokumentation der geplanten Anwendung und
noch keinen ausführbaren Java-Code. Sobald eine Java-Klasse mit einer
`main`-Methode erstellt wurde, können der genaue Compiler- und Startbefehl
ergänzt werden.

## Autor

**Autor:** Ravneet Bajwa  
**Hobby:** Schach
