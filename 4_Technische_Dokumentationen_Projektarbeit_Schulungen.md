## Technische Dokumentationen/Projektarbeit/Schulungen

### Aufgabe und Strukturierung von Testläufen

#### Schritte:

* Testplan erstellen
    * Teststrategie, Testumfang, Testabdeckung, Risikoabschätzung, Testziele und Kriterien für Testbeginn, Testende und
      Testabbruch – für alle Teststufen
* Testvorbereitung
    * Bereitstellen der Dokumente, Verfügbar machen von Werkzeugen für das Testfall- und Fehlermanagement; Aufbauen der
      Testumgebung
* Testspezifikation
    * Festlegen und Erstellen der Eingabedaten; Festlegungen zum Testablauf und zur Testreihenfolge; Festlegen
      Soll-Ergebnis; Bedingungen für 'Test erfüllt'; ...
* Testdurchführung
    * Bereitstellen der Testdaten und des Ist-Ergebnisses zur Auswertung, Umgebungsinformationen für den Testlauf
      archivieren
* Testauswertung
    * Bei Fehle:
        * Klassifizierung (z. B. nach Fehlerursache, Fehlerschwere etc., siehe auch Fehlerklassifizierung), angemessene
          Fehlerbeschreibung und -Erläuterung, Überleitung ins Fehlermanagement, Testfall bleibt offen
    * Bei OK:
        * Testfall gilt als erledigt
    * Für alle Tests
        * Dokumentation, Historisieren / Archivieren von Unterlagen
* Testabschluss
    * Der Status zum Abschluss von Teststufen wird (z. B. mit Hilfe von Teststatistiken) dokumentiert und kommuniziert,
      Entscheidungen sind herbeizuführen und Unterlagen zu archivieren.

### Protokollieren technischer Arbeiten Inhalt einer technischen Dokumentation/technisches Protokoll (z.B. FAQ, …) Aufbereitung einer technischen Dokumentation/technisches Protokoll

Protokoll einer Tätigkeit im Zusammenhang mit einem Projekt. Werden üblicherweise versioniert (Sharepoint). Enthält
unter anderem Datum, Version, (technische) Beschreibung, getroffene Entscheidungen, nächste Schritte, Ansprechpersonen,
Information zur Verwendung und Wartung, … -> mitprotokollieren was gemacht wurde. Oft unterteilt in Ergebnisprotokoll
und Verlaufsprotokoll (auch: Benutzerhandbuch, README, Changelog-Dokumente, …)

### Kenntnis über Abläufe und Prozessschritte zum Roll-out von Applikationen (z.B. Einführungsvorgehen, Sicherheitsanforderungen, evtl. Abbruch und Rückführung, Datenmigration/Konvertierung, Anwenderschulung, Übergabe, Abnahme)

#### Rollout (Beispiel Kassensoftware:)

1. Software wurde ausreichend getestet und vom Kunden abgesegnet
2. Software wird in einer Pilotfiliale installiert, für ein paar Tage produktiv getestet.
3. Produktivtest ist erfolgreich: in kleinen Schritten bekommen immer mehr Filialen die neue Software
4. Produktivtest nicht erfolgreich, arbeiten damit möglich: Verbesserungen in der Entwicklung, keine anderen Filialen bekommt die neue Software. Update wird intern getestet und vom Kunden abgesegnet, wird in der Pilotfiliale installiert und produktiv getestet.
5. Produktivtest nicht erfolgreich, arbeiten damit nicht möglich: Umstellung auf das alte System, mit dem Kunden neue Funktionen und Verbesserungen besprechen, große Änderungen in der Entwicklung.


#### Zu betrachten

* Welche Hardware steht zur Verfügung? Welche Betriebssysteme?
* Stromunterbrechungen Konsequenzen
* Netzwerk? Wer hat von wo Zugriff darauf? Fernwartung?
* Benutzernamen, Passwörter, ...
* Daten(bank) Einrichtung, Backups, …
* Anbindungen an Kundensysteme
* Performance-Tests in real Situation
* ...

### Gestaltung und Vorbereitung von Präsentationen

* Ziel der Präsentation Überlegen (Verkauf der Software, Funktionen verständlich machen, …)
* Tools vorbereiten (PowerPoint, Flipchart, Unterlagen, …)
* Wenig Fachausdrücke, versuchen einfach zu erklären

