# Geplante Features

1. **Schachbrett darstellen:** Das Spielfeld besteht aus 8 × 8 Feldern. Die
   Dateien werden mit `a` bis `h`, die Reihen mit `1` bis `8` bezeichnet. Die
   Anzeige enthält Koordinaten und stellt leere Felder sowie Figuren eindeutig
   dar.
2. **Startposition aufbauen:** Zu Beginn werden für beide Farben je acht
   Bauern und die sechs übrigen Figuren in der offiziellen Grundstellung
   aufgestellt.
3. **Aktuellen Spieler anzeigen:** Das Programm zeigt deutlich an, ob Weiß
   oder Schwarz am Zug ist. Nach einem gültigen Zug wechselt der Spieler.
4. **Züge über Koordinaten eingeben:** Ein Zug besteht aus Start- und Zielfeld,
   beispielsweise `e2 e4`. Die Eingabe wird in Brettkoordinaten umgewandelt.
5. **Eingaben kontrollieren:** Das Programm weist Eingaben zurück, wenn sie
   unvollständig sind, Felder außerhalb des Bretts nennen, ein leeres
   Startfeld auswählen oder eine gegnerische Figur bewegen wollen. Nach einem
   Fehler bleibt derselbe Spieler am Zug.
6. **Bewegung der Figuren prüfen:** Bauern bewegen sich grundsätzlich vorwärts
   und schlagen diagonal; Türme ziehen gerade, Läufer diagonal, Damen gerade
   oder diagonal, Springer in einer L-Form und Könige jeweils ein Feld. Für
   Figuren, die nicht springen dürfen, wird geprüft, ob der Weg frei ist.
7. **Züge ausführen und schlagen:** Nur ein gültiger Zug verändert das Brett.
   Zieht eine Figur auf ein Feld mit einer gegnerischen Figur, wird diese
   geschlagen und entfernt. Eigene Figuren können nicht geschlagen werden.
8. **König schützen:** Ein Zug darf den eigenen König nicht im Schach stehen
   lassen. Das Programm soll erkennen, wenn ein König angegriffen wird, und
   einen Zug verhindern, der den eigenen König ungeschützt zurücklässt.
9. **Schach und Schachmatt melden:** Wird ein König angegriffen, wird „Schach“
   angezeigt. Gibt es für den betroffenen Spieler keinen erlaubten Zug, der
   den Angriff beendet, endet die Partie mit Schachmatt und der andere Spieler
   gewinnt.
10. **Partie beenden:** Die Spieler können die Partie über eine klar
    dokumentierte Eingabe aufgeben oder beenden. Das Programm meldet, dass die
    Partie abgebrochen wurde.
11. **Sonderzüge ergänzen:** Als Erweiterung können Rochade, En-passant und
    Bauernumwandlung umgesetzt werden. Bei der Umwandlung wird ein Bauer, der
    die letzte Reihe erreicht, in eine Dame, einen Turm, Läufer oder Springer
    umgewandelt.
12. **Remis berücksichtigen:** Eine spätere Erweiterung kann Remis durch
    Patt oder eine einvernehmliche Entscheidung der Spieler erkennen.

Diese Punkte beschreiben Anforderungen und Erweiterungsmöglichkeiten, nicht
bereits vorhandenen Programmcode. Für die erste Version können die Features
schrittweise umgesetzt werden; Sonderzüge und Remis sind Erweiterungen.
