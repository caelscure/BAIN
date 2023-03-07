---
title: "3 Aufbau Bibliotheksysteme"
date: 2023-03-06
---
# Metadatenstandard MARC21
MARC21 gilt als allgemeines austauschformat von Bibliotheksbeständen. Das Datenformat bildet .mrc-Dateien. Ein älteres Format ist MARC und MAP. Mit RDA wurde vom Metadatenstandard MAP auf MARC21. MARC21 ist international sehr weit verbreitet, wird jedoch nicht weltweit gleich umgesetzt. 
--> Daher wichtig: MARC21 Daten zuerst zu analysieren, um diese richtig zu interpretieren und anwenden zu können.

Es ist sehr schwer damit zu arbeiten und software dafür zu schreiben, da schnell fehler passieren können.

Ältere Metadatenstandards, welche manchmal noch in kleineren Bibliotheken benutzt werden sind KIDS und AT7.

## Marc21 xml
Die XML-Darstellung von MARC21 sieht etwa so aus.
![BAIN_MARC21_xml.PNG](/BAIN/assets/BAIN_MARC21_xml.png)

**[Leader](https://www.loc.gov/marc/bibliographic/bdleader.html)-Tag:** Jede Position hat eine Bedeutung 
Kann nur mit Regelwerk entschlüsselt werden, nitcht mehr zeitgemäss

**[Controlfield](https://www.loc.gov/marc/bibliographic/bd00x.html)-Tag:** 

**Tag-attribut:** Feldid

**Subfield:** gibt an welcher subtyp dargestellt wir z.B. Titiel

## Bibframe
BIBFRAME gilt als Nachfolgemodel. Es basiert auf RDF und soll weniger dopplung von Angaben beinhalten. Autoren können in eigene Datensätzen hinterlegt werden und sind über linked Data mit dem Bestand verknüpfbar. So muss nicht mehr überall einzeln Autor mit Vor- und Nachnamen + GND angebenben werden

# DublinCore
Ein Metadatenstandard mit 15 Coreelements.
Mehrmals vorkommende Felder werden einfach wiederholt.

### Übungen
Vergleich von Dublin Core und MARC21

**Beide**
- identisch bis zum Tag recordDATA 
- beschreiben verwendetes Schema
- gleiche mmSID


**MARC21**
- beinhaltet im recordData nochmals record-Tag
- verschachtelter
- kann detailierter beschrieben werden, mehr unterkategorien

**Dublin Core**
- ist menschenlesbar, kleine einstiegsschwelle
- allgemeiner weiniger Angaben, weniger detailiert

## SRU vs OAI
Die SRU(Search/Retrieve via URL) Schnitstelle wird benutz, um spontane/kurzfristige Datenabfragen durchzuführen oder Abfragen mit vielen Parameter. Diese werden in kleineren Treffermengen dargestellt und laufend aktualisiert.
--> gibt es neue/veränderte Einträge werden diese aktualisiert.

OAI-PMH Schnittstelle stellt den Gesammtdatensatzt dar.

## Regelwerk vs Datenformat
Ein Regelwerk ist die Anleitung (theoretisch) von Metadatenstandards. Ein Datenformat stellt die Darstellung (praktisch) des Metadatenstandards fest.

Oder für **D&D Begeisterte** das Regelwerk ist das Playershandbook und das Datenformat ist das Charakter-Sheet.

# Koha
Es ist eine Open Source Software aus New Zeeland. Die Bibliothekssoftware wird von freiwilligen wie auch Unternehmen mitentwickelt.

Beteiligung von Unternehmen: Sie verdienen an Dienstleistungen um Koha Geld. ( Installation, Konfiguration, Support, etc.)
-> in Papers gelesen, dass viele Bibliotheken Support für Open Source Software dazukaufen. 

# What i learned
- Kennenlernen von Kohasoftware inkl. Interface
- Mit Marc21 zu katalogisieren ist umständlich, zudem ist das Interface von Koha funktional aufgebaut. Es fehlt meiner Meinung nach jedoch ein "frequently used fields" Fenster, in welchem die meistens gefüllten Felder auf einen Blick überschaubar sind.
- MARC21 ist sehr ausführlich und deailorientiert. Ist aber, obwohl in kleineren Bibliotheken noch nicht vollständig umgesetzt, in der Entwicklung schon wieder als "Alt" eingestuft.
- OAI und SRU sind beides Schnittstellen um Metadaten auszulesen. OAI wird hauptsächlich für Massenverarbeitung gebraucht und SRU ist für Einzelsuchen geeignet, wobei mir der konkrete Use-Case davon noch nicht klar ist.