---
title: "8 Metadaten modellieren und Schnittstellen nutzen 1"
date: 2023-05-01
---

m Beitrag 3 "Funktion und Aufbau von Bibliothekssystemen Teil 1" werden Austauschprotokolle kurz Angesprochen. In diesem Beitrag werden sie detaillierter beschrieben.
# Austauschprotokolle für Metadaten (OAI-PMH, SRU)

**Z39.50** ist ein Standardprotokoll für die Suche und den Abruf von Informationen aus Datenbanken und Bibliothekskatalogen. Es ermöglicht Benutzern, komplexe Suchvorgänge über verschiedene Systeme hinweg durchzuführen und die Abfrage verschiedener Datensatzformate. Obwohl neuere Protokolle entwickelt wurden, ist Z39.50 nach wie vor relevant, um die Suche und das Retrieval in Bibliotheks- und Informationssystemen zu erleichtern.

**SRU** (Search/Retrieve via URL) ist ein Standardprotokoll, das es Benutzern ermöglicht Suchergebnisse von Datenbanken oder Repositorien abzurufen. Es verwendet URLs und XML. Zudem unterstützt es flexible Suchanfragen, produziert standardisierte XML-Antworten und fördert die Interoperabilität zwischen verschiedenen Systemen. SRU wird in der Bibliotheks- und Informationswissenschaft weit verbreitet eingesetzt.

**OAI-PMH** (Open Archives Initiative Protocol for Metadata Harvesting) ist ein Protokoll, das vorallem im Bibliotheks- und Kulturerbebereich verwendet wird, um den Austausch von Metadaten zwischen digitalen Repositorien zu ermöglichen. OAI-PMH arbeitet nach einem Client-Server-Modell, bei dem der Client (Harvester) über HTTP-Protokolle Anfragen an den Server (Repository) stellt. OAI-PMH fördert die Interoperabilität und Zusammenarbeit, indem es das Auffinden und die Integration von Metadaten aus verschiedenen Repositorien erleichtert und so die Zugänglichkeit und Sichtbarkeit digitaler Ressourcen verbessert.

# Vufind Harvest
VuFind Harvest ist eine Funktion der VuFind-Software, die es ermöglicht, Metadaten aus verschiedenen Quellen in einem zentralen Index zu sammeln. Es unterstützt das Harvesting von Metadaten durch die Verwendung von Protokollen wie OAI-PMH und Z39.50. Die gesammelten Metadaten können in VuFind konvertiert und indiziert werden, so dass Benutzer Ressourcen aus verschiedenen Sammlungen über eine einzige Schnittstelle suchen und abrufen können.

# XSLT Crosswalks
Bei XSLT-Crosswalks werden Daten mit Hilfe von XSLT von einem Format in ein anderes umgewandelt. XSLT (Extensible Stylesheet Language Transformations) ermöglicht die Erstellung von Regeln und Transformationen für Umwandlung von Datenelementen zwischen verschiedenen Schemas oder Standards. Crosswalks oder Mappings werden verwendet, um Daten zu migrieren, integrieren oder zu harmonisieren und dabei die Interoperabilität von Daten zu gewährleisten.

# MarcEdit
MarcEdit ist eine kostenlose Softwareanwendung, welche Werkzeuge für die Anreicherung, Bearbeitung, Bereinigung, Validierung und Konvertierung von Metadaten zwischen verschiedenen Formaten bereitstellt. Es verfügt über eine umfassende Unterstützung der MARC-Standards und die Möglichkeit Batch-Operationen durchzuführen, welche zur Optimierung des Workflows und zur Verbesserung des Datenmanagements beiträgt.

# What i learned
- IT-Berufe können auch in Verlagen (DSpace) und verwandten Branchen relevant sein.
- Z39.50 und SRU sind Protokolle um Metadaten zu durchsuchen. OAI-PMH wird für den Austausch von Metadaten verwendet.
- VuFind ist eine Software die den Austausch von Metadaten vereinfacht/nutzerfreundlicher macht.
- Mit XSLT-Crosswalks und MarcEdit können Metadatenformate umgewandelt werden.
