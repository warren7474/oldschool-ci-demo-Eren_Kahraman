 Dokumentation – OldSchool CI Demo

1. Was macht das Dockerfile?
   
 Das Dockerfile legt fest, wie der Docker-Container
 gebaut wird.
 Es kopiert das Skript app.sh in den Container,
 macht es ausführbar und startet es automatisch,
 wenn der Container läuft.
 Dadurch entsteht eine einfache Anwendung,
 die immer die gleiche Ausgabe liefert.

 2. Was ist der Zweck der Pipeline?

 Die Pipeline übernimmt den
 Build und Testprozess automatisch.
 Bei jedem Push wird:
 - das Repository ausgecheckt,
 - das Docker-Image gebaut,
 - der Container gestartet und geprüft, ob die Ausgabe korrekt ist.
  So fallen Fehler sofort auf und Änderungen können sicher getestet werden.

 3. Was war der schwierigste Teil der Aufgabe?

 Am schwierigsten war für mich das starten
 des Containers.
 Kleine Dinge wie ein zusätzliches Leerzeichen
 oder ein Zeilenumbruch können schon dafür sorgen,
 dass der Test fehlschlägt.
 Deshalb musste ich genau arbeiten und etwas
 ausprobieren, bis alles richtig funktioniert hat.



