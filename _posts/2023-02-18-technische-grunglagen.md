---
title: "1 Technische Grundlagen"
date: 2023-02-13
---

Die erste Vorlesung drehte sich vorallem um die Einführung der Werkzeuge, welche wir für die Übungen und für unser Lerntagebuch benutzen werden. Zusätzlich wurden die Anforderungen an den Leistungsnachweis geklärt und die Lernziele vermittelt.

# Ansicht Lernziele
Die Lernziele des Kurses beziehen sich hauptsächlich auf das Verständnis von Bibliothekssoftware bzw. Archivsoftware. Es geht darum einen groben Überblick zu bekommen wie das Auswahlverfahren von Software für Bibliotheken und Archive ablaufen sollte. Dies finde ich besonders wichtig, da es eine Aufgabe ist, welche naheliegend vom Bibliothekspersonal ausgeführt werden sollte. Um die Bibliothekssoftware richtig einetzten zu können benötigt es Metadatenstandards. Wir sollen die Bekanntesten davon kennenlernen. Zudem wird aufgezeigt wie mittels Protokolle der Datenaustausch zwischen Systemen durgeführt wird. Sind jedoch unterschiedliche Metadatenstandards vorhanden, sollen wir in der Lage sein, Crosswalks für die Verbindung dieser anwenden zu können. Zuletzt lernen wir den Umgang mit Suchmaschinen.

# Ablauf der Lektionen
![Ablauf Kurs](/BAIN/assets/BAIN.png)
(Abbildung: Schaubild zu Lerninhatlen (https://pad.gwdg.de/MRhIEw88Rd-rrvzogVjpwA#))
Die Abbildung oben zeigt die Lernizele dargestellt als Prozessvorgänge. Der Unterricht folgt diesem Diagramm, beginnend mit der Bibliothekssoftware Koha. Bei Koha, ArchivesSpace und DSpace wird jeweils das Extrahieren, Aufbereiten und Integrieren von Metadatensets mit Open Archive Initaitive Protocol Metadata Harvesting (OAI-PMH) über VuFindHarvest  angeschaut. Diese werden in marcEdit vereinheitlicht und in der Suchmaschine Solr und VuFind eingesetzt. Zusätzlich lernen wir den umgang mit OpenRefine und wie dort Daten für den Metadatenstandard MARC21 aufbereitet werden können.

# Markdown
Für die Lektionsnotizen des Dozenten und mein Lerntagebuch wird Markdown verwendet. Dies ist eine Auszeichnungssprache welche es ermöglicht mit Hilfe einfacher Zeichen einen Text zu formatieren. Zum Beispiel wurde dieser Text mit Markdown geschrieben. Markdown kann auch als HTML ersatz für Websiten funktionieren. Damit habe ich bereits Erfahrung. Dafür wird für jede einzelne Unterseite ein neues Markdowndokument angelegt, welche über eine JSON datei hierarchisiert werden. 
Ein Tutorial zu Markdown: [Tutorial](https://www.markdowntutorial.com) 

# Github
Ich benutzte Github als Repository für mein Lerntagebuch. Dazu wurde uns mit Github Pages eine Vorlage zur Verfügung gestellt.  [Github Codespaces](https://github.com/features/codespaces) ist eine Möglichkeit Repositorys online in Entwicklungsumgebungen zu laden und auszuführen. Im Kurs benutzen wir Codespace als Entwicklungsraum für Übungen.
[Benutze Codespace](https://github.com/devcontainers/images/tree/main/src/universal)
Eine Codespace basiert auf dem Konzept der [Docker](https://phoenixnap.com/kb/docker-image-vs-container) Container. Dies ist eine alternative zur Virtual Machine. Der Vorteil besteht darin, dass alles auf 1 Betriebsystem lauft, verschiedene Anwendungen jedoch abgekapselt werden können, sodass nicht das ganze Betriebsystem korrupiert werden kann.

# What i learned
- Github besizt die möglichkeit Codespaces als Entwicklungsumgebung zu generieren.
- Markdown ist eine von vielen Systemen lesbare Auszeichnungssprache.