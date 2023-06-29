---
title: "2 OpenRefine"
date: 2023-02-16
---

OpenRefine (https://openrefine.org/ ) ist ein Open-Source-Tool, mit dem Daten bereinigt, neu formatiert und mit Webdiensten und externen Dateien angereichert werden können. Die Daten werden lokal auf dem Rechner gespeichert. Das Programm arbeitet, indem es lokal einen Server startet. Ursprünglich hiess das Projekt Google Refine und wurde von Google gepflegt, aber seit etwa 2013 wird es von der OpenRefine-Community betreut.

Es wird als Interactive Data Transformation Tool betrachtet. OpenRefine ähnelt in Aufbau und Aussehen einer Excel-Tabelle. OpenRefine ermöglicht seit der Betaversion vom Juni 2022 auch den Upload von Dateien zu Wikimedia Commons und kann aus einem Tool heraus Wikidata und Wikimedia Commons beschreiben. 

# Snapshot 3.7
Mit OpenRefine können nun auch Dateien auf Wikimedia Commons hochgeladen werden. Bisher war es nur möglich, strukturierte Daten in Form von RDF-Tripeln für Wikibase-Instanzen wie Wikidata mit OpenRefine zu erstellen. Dies bedeutet, dass es nun auch möglich ist, Mediendateien selbst inklusive beschreibendem Wiki-Text und strukturierten Daten zu Grafikdateien in OpenRefine zu bearbeiten und diese dann nach Wikimedia Commons zu exportieren (bisher war nur ein Export nach Wikidata möglich). Die Upload-Funktion befindet sich noch in der Beta-Phase. 

Der Upload von Grafikdateien erfolgt über die Reconciliation-Funktion. Diese kann auf den Datenbestand von Wikimedia Commons zugreifen und die Zelleninhalte mit diesem abgleichen. Wurde eine Übereinstimmung gefunden, wird in OpenRefine ein Link in der Zelle hinterlegt. Darüber hinaus ist es möglich, für Zellen, die noch keinen Eintrag in Wikimedia Commons haben, einen solchen zu erstellen. 

## Upload nach Wikimedia Commons
Grafiken können mit Metadaten auf Wikimedia Commons hochgeladen werden. Dazu wird zunächst für die Spalte mit dem Dokumenttitel ein Abgleich mit dem Datenbestand von Wikimedia Commons durchgeführt. Das bedeutet, dass OpenRefine prüft, ob der im Datensatz angegebene Name bereits als Dateiname auf Wikimedia Commons existiert. Falls dies nicht der Fall ist, kann ein neuer Eintrag erzeugt werden. Anschliessend muss die Wikibase «Wikimedia Commons» ausgewählt werden. Diese stellt ein Schema zum Hochladen der Datei inklusive Metadaten zur Verfügung. Dieses ist in der folgenden Abbildung zu sehen. 
![Schema zum Upload nach Wikimedia Commons](/BAIN/assets/Scr_OpenRefine_WCschema.PNG)

Durch Anklicken und Ziehen der Spaltennamen in die gewünschten Felder kann das Schema ausgefüllt werden. Damit wird festgelegt, welche Spalten den Dateinamen, den Dateipfad zum Hochladen der Grafik und den Wikitext mit Beschreibung enthalten. Der Wikitext ist die ausführliche Beschreibung, die auf Wikimedia Commons angezeigt wird. Um den Vorgang zu starten, wird ein Wikimedia-Login benötigt. Nach dem Start werden die Dateien automatisch in die Datenbank von Wikimedia Commons geladen.

# What i learned
- OpenRefine ist ursprünglich von Google entwickelt worden.
- OpenRefine ist ein vielseitiges Datenbearbeitungstool und kann anstelle Python(pandas) verwendet werden.
- Gerade für Wikimedia Datenbestände empfiehlt es sich OpenRefine zu benutzen.