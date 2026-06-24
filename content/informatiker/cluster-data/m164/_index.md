---
title: M164 Datenbanken erstellen und Daten einfügen
modul: m164
cluster: cluster-data
date: 2025-07-02T10:05:23Z
draft: false
kompetenzbaender:
  - id: A
    titel: Logisch relationales Modell interpretieren
    kompetenzen:
      - nr: 1
        hz: "1"
        grundlagen: Ich kann die Elemente eines logisch relationalen ERD erläutern (z.
          B. Entitäten, Attribute, Beziehungen, Kardinalitäten etc.).
        fortgeschritten: Ich kann eine Übersicht über ein einfaches ERD gewinnen,
          Zusammenhänge über mehrere Entitäten erkennen und erläutern.
        erweitert: Ich kann ein ERD mit Entitäten kritisch hinterfragen, Probleme
          erkennen und Verbesserungen vorschlagen.
  - id: B
    titel: Logisch relationales Modell umsetzen
    kompetenzen:
      - nr: 1
        hz: "2"
        grundlagen: Ich kann die Begriffe für die Elemente eines
          Datenbankmanagementsystems erläutern (z. B. Datenbank, Zeichensatz,
          Schema, Tablespace, Tabelle, Partition, Feld etc.).
        fortgeschritten: Ich kann ein logisch relationales Modell in eine relationale
          Datenbank implementieren (z. B. mit Hilfe eines Tools).
        erweitert: Ich kann ein logisch relationales Modell mit Hilfe der DDL in eine
          relationale Datenbank implementieren (z. B. direkt mit SQL).
      - nr: 2
        hz: "2"
        grundlagen: Ich kann die Datentypen von Attributen einer relationalen Datenbank
          unterscheiden (z. B. Ganzzahlen, Fliesskomma, Text, Datum, Zeit,
          Binärtypen etc.).
        fortgeschritten: Ich kann die Datentypen von Attributen einer relationalen
          Datenbank gezielt anwenden (z. B. Ganzzahlen, Fliesskomma, Text,
          Datum, Zeit, Binärtypen etc.).
        erweitert: Ich kann zusätzlich zu den Datentypen weitere Eigenschaften wie
          Defaultvalues, Not Null, Unique, Unsigned und Autoincrement etc.
          gezielt für Attributwerte einsetzen.
      - nr: 3
        hz: "3"
        grundlagen: Ich kann das Prinzip der Beziehung und Assoziationen erläutern (z.
          B. Primär- und Fremdschlüssel).
        fortgeschritten: Ich kann die Beziehungen und Assoziationen eines logisch
          relationalen Modells mit Hilfe eines Tools in einer relationalen
          Datenbank implementieren.
        erweitert: Ich kann die Beziehungen und Assoziationen eines logisch relationalen
          Modells mit Hilfe der DDL direkt mit SQL Constraints in einer
          relationalen Datenbank implementieren.
  - id: C
    titel: Mit Daten umgehen
    kompetenzen:
      - nr: 1
        hz: 4, 7
        grundlagen: Ich kann den Unterschied zwischen Struktur und Daten einer
          Datenbanktabelle erläutern.
        fortgeschritten: Ich kann Daten in eine relationale Datenbank mit Hilfe eines
          Tools einfügen.
        erweitert: Ich kann Daten direkt mit SQL in eine relationale Datenbank einfügen.
      - nr: 2
        hz: "5"
        grundlagen: Ich kann eine Datenbank exportieren und importieren.
        fortgeschritten: Ich kann mit einem Bulk-Import Daten aus externen Quellen (z.
          B. CSV, XML, JSON) importieren.
        erweitert: Ich kann Daten aufbereiten, damit sie danach mit einem Bulk-Import
          importiert werden können.
      - nr: 3
        hz: 3, 4, 7
        grundlagen: Ich kann das Prinzip der referentiellen Integrität erläutern.
        fortgeschritten: Ich kann die Auswirkungen von Löschen und Ändern von Daten auf
          die referenzielle Integrität erläutern.
        erweitert: Ich kann Regeln für das Löschen und Ändern von referenzierten Daten
          anwenden (z. B. Aktualisierungsweitergabe oder Löschweitergabe etc.),
          um die Datenbankkonsistenz zu gewährleisten.
  - id: D
    titel: Abfragen anwenden, Daten überprüfen
    kompetenzen:
      - nr: 1
        hz: "6"
        grundlagen: Ich kann eine einfache Abfrage für die Auswahl von Daten anwenden
          (z. B. Select, Group, Order etc.).
        fortgeschritten: Ich kann eine einfache Abfrage spezialisieren (z. B. Anwenden
          von Filtern und Kriterien wie Where, Join etc.).
        erweitert: Ich kann Überprüfungen von Datenbeständen in Datenbanktabellen
          anwenden (z. B. SQL Checksum, CHECKSUM_AGG, HASHBYTES, BINARY_CHECKSUM
          etc.).
---
