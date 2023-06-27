---
title: "9 Metadaten modellieren und Schnittstellen nutzen 2"
date: 2023-05-10
---

Teil 1 der Metadatenmodellierung hat sich mit Austauschprotokollen für die Metadatenübertragung befasst. Im Teil 2 geht es um die Transformation der Metadaten.

# Transformation von Metadaten
Metadatentransformation ist der Prozess der Umwandlung von Metadaten von einem Format oder Schema in ein anderes. Sie ermöglicht die Integration, Harmonisierung und Veröffentlichung von Metadaten in verschiedenen Umgebungen und gewährleistet die Interoperabilität zwischen verschiedenen Systemen und Standards.

## ETL-Prozess
Der ETL-Prozess steht für Extract, Transform und Load und beschreibt eine Methode zum Extrahieren, Transformieren und Speichern von Daten zwischen verschiedenen Systemen oder Datenquellen. Durch den ETL-Prozess können Daten in konsistenter und strukturierter Form übertragen und bereitgestellt werden, was die Datenqualität verbessert und die Nutzung und Analyse der Daten erleichtert.

Extraktion (Extract): In diesem Schritt werden Daten aus Quellen (Datenbanken, Dateien oder APIs) extrahiert. Die Extraktion kann vollständig oder inkrementell erfolgen, je nachdem, ob alle Daten oder nur geänderte Daten abgerufen werden sollen.

Transformation (Transform): Der Transformationsprozess wandelt die extrahierten Daten um. Dies umfasst das Zusammenführen von Daten aus verschiedenen Quellen.

Speicherung(Load): Nach der Transformation werden die Daten in das Zielsystem. Dies kann eine Datenbank, ein Data Warehouse, eine Datei oder eine andere Datenstruktur sein. Beim Laden werden die transformierten Daten entsprechend dem Datenmodell und den Anforderungen des Zielsystems organisiert und gespeichert.

## Tools zur Metadatentransformation

Alternativen zu OpenRefine

**Catmandu** ist ein auf Perl basierendes Datenmanipulations-Toolkit für die Arbeit mit strukturierten Daten. Es unterstützt verschiedene Datenformate, kann mit externen Diensten integriert werden und bietet flexible und erweiterbare Funktionen wie eine leistungsfähige Abfragesprache und regelbasierte Verarbeitung. 

**Metafacture** ist ein Open-Source-Framework für die Verarbeitung und Manipulation von Metadaten. Es bietet Werkzeuge und Bibliotheken für Aufgaben wie Datentransformation, Validierung und Anreicherung. Dazu unterstützt es verschiedene Datenformate und bietet eine flexible Architektur für die Definition von Verarbeitungssequenzen. Mit der Sprache Flux können Benutzer Pipelines aus miteinander verbundenen Modulen für eine effiziente Metadatenverarbeitung erstellen. 

## JSON-APIs
JSON-API ist eine Spezifikation für die Erstellung von Web-APIs mit JSON als Datenformat. Sie enthält Richtlinien für die Strukturierung und Verwaltung von Ressourcen. Dazu soll JSON-API die Konsistenz fördern und Best Practices bei der Entwicklung von APIs garantieren. JSON-API ermöglicht den effizienten Abruf zusammengehöriger Daten, unterstützt die Paginierung grosser Datensätze und enthält standardisierte Fehlerbehandlungs- und Metadatenfunktionen. 

# What I learned
- Metadatentransformation ist Teil eines ETL-Prozesses
- Der ETL-Prozess besteht aus Entnahme der Daten, Transformierung der Daten und Speicherung der Daten.
- Ein bekanntes Tool für die Transformierung ist OpenRefine. Es gibt aber auch Catmandu, Metafacture und MarcEdit.
- JSON-API ist eine Spezifikation für das arbeiten mit mehreren APIs.
