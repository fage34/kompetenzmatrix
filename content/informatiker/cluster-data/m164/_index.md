---
title: M164 Datenbanken erstellen und Daten einfügen
modul: m164
cluster: cluster-data
date: '2025-07-02T10:05:23Z'
draft: false
kompetenzbaender:
- id: A
  titel: Logisch relationales Modell interpretieren
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann die Elemente eines logisch relationalen ERD erläutern (z. B. Entitäten, Attribute, Beziehungen, Kardinalitäten etc.).
    fortgeschritten: Ich kann eine Übersicht über ein einfaches ERD gewinnen, Zusammenhänge über mehrere Entitäten erkennen und erläutern.
    erweitert: Ich kann ein ERD mit Entitäten kritisch hinterfragen, Probleme erkennen und Verbesserungen vorschlagen.
- id: B
  titel: Logisch relationales Modell umsetzen
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann die Begriffe für die Elemente eines Datenbankmanagementsystems erläutern (z. B. Datenbank, Zeichensatz, Schema, Tablespace, Tabelle, Partition, Feld etc.).
    fortgeschritten: Ich kann ein logisch relationales Modell in eine relationale Datenbank implementieren (z. B. mit Hilfe eines Tools).
    erweitert: Ich kann ein logisch relationales Modell mit Hilfe der DDL in eine relationale Datenbank implementieren (z. B. direkt mit SQL).
  - nr: 2
    hz: '2'
    grundlagen: Ich kann die Datentypen von Attributen einer relationalen Datenbank unterscheiden (z. B. Ganzzahlen, Fliesskomma, Text, Datum, Zeit, Binärtypen etc.).
    fortgeschritten: Ich kann die Datentypen von Attributen einer relationalen Datenbank gezielt anwenden (z. B. Ganzzahlen, Fliesskomma, Text, Datum, Zeit, Binärtypen etc.).
    erweitert: Ich kann zusätzlich zu den Datentypen weitere Eigenschaften wie Defaultvalues, Not Null, Unique, Unsigned und Autoincrement etc. gezielt für Attributwerte einsetzen.
  - nr: 3
    hz: '3'
    grundlagen: Ich kann das Prinzip der Beziehung und Assoziationen erläutern (z. B. Primär- und Fremdschlüssel).
    fortgeschritten: Ich kann die Beziehungen und Assoziationen eines logisch relationalen Modells mit Hilfe eines Tools in einer relationalen Datenbank implementieren.
    erweitert: Ich kann die Beziehungen und Assoziationen eines logisch relationalen Modells mit Hilfe der DDL direkt mit SQL Constraints in einer relationalen Datenbank implementieren.
- id: C
  titel: Mit Daten umgehen
  kompetenzen:
  - nr: 1
    hz: 4, 7
    grundlagen: Ich kann den Unterschied zwischen Struktur und Daten einer Datenbanktabelle erläutern.
    fortgeschritten: Ich kann Daten in eine relationale Datenbank mit Hilfe eines Tools einfügen.
    erweitert: Ich kann Daten direkt mit SQL in eine relationale Datenbank einfügen.
  - nr: 2
    hz: '5'
    grundlagen: Ich kann eine Datenbank exportieren und importieren.
    fortgeschritten: Ich kann mit einem Bulk-Import Daten aus externen Quellen (z. B. CSV, XML, JSON) importieren.
    erweitert: Ich kann Daten aufbereiten, damit sie danach mit einem Bulk-Import importiert werden können.
  - nr: 3
    hz: 3, 4, 7
    grundlagen: Ich kann das Prinzip der referentiellen Integrität erläutern.
    fortgeschritten: Ich kann die Auswirkungen von Löschen und Ändern von Daten auf die referenzielle Integrität erläutern.
    erweitert: Ich kann Regeln für das Löschen und Ändern von referenzierten Daten anwenden (z. B. Aktualisierungsweitergabe oder Löschweitergabe etc.), um die Datenbankkonsistenz zu gewährleisten.
- id: D
  titel: Abfragen anwenden, Daten überprüfen
  kompetenzen:
  - nr: 1
    hz: '6'
    grundlagen: Ich kann eine einfache Abfrage für die Auswahl von Daten anwenden (z. B. Select, Group, Order etc.).
    fortgeschritten: Ich kann eine einfache Abfrage spezialisieren (z. B. Anwenden von Filtern und Kriterien wie Where, Join etc.).
    erweitert: Ich kann Überprüfungen von Datenbeständen in Datenbanktabellen anwenden (z. B. SQL Checksum, CHECKSUM_AGG, HASHBYTES, BINARY_CHECKSUM etc.).
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann die Elemente eines logisch… | 2 | Verstehen | erläutern |
| A1F  | Ich kann eine Übersicht über ein einfaches… | 4 | Analysieren | erkennen (Zusammenhänge), erläutern |
| A1E  | Ich kann ein ERD mit Entitäten kritisch… | 5 | Bewerten | hinterfragen, erkennen, vorschlagen |
| B1G  | Ich kann die Begriffe für die Elemente… | 2 | Verstehen | erläutern |
| B1F  | Ich kann ein logisch relationales Modell… | 3 | Anwenden | implementieren |
| B1E  | Ich kann ein logisch relationales Modell… | 3 | Anwenden | implementieren |
| B2G  | Ich kann die Datentypen von Attributen… | 2 | Verstehen | unterscheiden |
| B2F  | Ich kann die Datentypen von Attributen… | 3 | Anwenden | gezielt anwenden |
| B2E  | Ich kann zusätzlich zu den Datentypen… | 3 | Anwenden | gezielt einsetzen |
| B3G  | Ich kann das Prinzip der Beziehung… | 2 | Verstehen | erläutern |
| B3F  | Ich kann die Beziehungen und Assoziationen… | 3 | Anwenden | implementieren |
| B3E  | Ich kann die Beziehungen und Assoziationen… | 3 | Anwenden | implementieren |
| C1G  | Ich kann den Unterschied zwischen Struktur… | 2 | Verstehen | erläutern |
| C1F  | Ich kann Daten in eine relationale Datenbank… | 3 | Anwenden | einfügen |
| C1E  | Ich kann Daten direkt mit SQL… | 3 | Anwenden | einfügen |
| C2G  | Ich kann eine Datenbank exportieren… | 3 | Anwenden | exportieren, importieren |
| C2F  | Ich kann mit einem Bulk-Import Daten… | 3 | Anwenden | importieren |
| C2E  | Ich kann Daten aufbereiten, damit sie… | 3 | Anwenden | aufbereiten |
| C3G  | Ich kann das Prinzip der referentiellen… | 2 | Verstehen | erläutern |
| C3F  | Ich kann die Auswirkungen von Löschen… | 2 | Verstehen | erläutern |
| C3E  | Ich kann Regeln für das Löschen und Ändern… | 3 | Anwenden | anwenden |
| D1G  | Ich kann eine einfache Abfrage für die… | 3 | Anwenden | anwenden |
| D1F  | Ich kann eine einfache Abfrage spezialisieren… | 3 | Anwenden | spezialisieren |
| D1E  | Ich kann Überprüfungen von Datenbeständen… | 3 | Anwenden | anwenden |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| --- | --- | --- |
| Tabellenformat | Separator-Zeile an Qualitätsvorgaben-Vorgabe angepasst; Kompetenzband-Spalte mit Buchstabe + Thema ergänzt (z. B. "A - ...") | Konsistenz mit Tabellenformat-Vorgabe |
| A1G | "Kardinalitäten..." durch "Kardinalitäten etc.)." ersetzt; "Z. B." zu "z. B." korrigiert | Feedback: Ellipsen durch "etc." ersetzen; Rechtschreibung |
| A1G | "Model" zu "Modell" korrigiert (Kompetenzband-Titel) | Tippfehler |
| B1G | "Datenbankmanagmentssystem" zu "Datenbankmanagementsystems" korrigiert | Tippfehler |
| B1G | Beispiele aus separatem `<br/>`-Block in Klammer integriert | Einheitliche Formatierung |
| B1F | Doppeltes Leerzeichen entfernt; `<br/>Z. B.`-Anhang in Klammer integriert | Formatierung und Konsistenz |
| B1E | `<br/>Z. B.`-Anhang in Klammer integriert | Konsistenz |
| B2G | Beispiele aus separatem `<br/>`-Block in Klammer mit "z. B." integriert | Einheitliche Formatierung |
| B2F | Inline-Erklärung "Wertebereiche, Datentypen von ..." entfernt; auf reine Beispielliste reduziert; "usw, )" zu "etc.)." korrigiert | Feedback-Prinzip: keine Erklärungen im Deskriptor |
| B2E | "..." durch "etc." ersetzt; "usw," zu Satz ohne Klammer umformuliert; Doppeltes Leerzeichen entfernt | Feedback: Ellipsen ersetzen; Formatierung |
| B3G | Beispiele aus separatem `<br/>`-Block in Klammer integriert | Einheitliche Formatierung |
| B3F/B3E | "relationale Datenbank" zu "relationalen Datenbank" korrigiert (Dativ) | Grammatik |
| C1E | Fehlendes Verb "einfügen" ergänzt | Feedback: fehlendes Wort |
| C2F | Inline-Erklärung "(Bulk-Import = Massenimport von Daten)" entfernt; "z. B." vor Beispielliste ergänzt | Feedback: keine Erklärungen im Deskriptor |
| C2E | "Manipulation bei Bulk-Import: Ich kann..." umformuliert zu "Ich kann..." (Präfix entfernt) | "Ich kann..."-Regel: Deskriptor muss mit "Ich kann" beginnen |
| C3E | "..." durch "etc." ersetzt; "Z. B." zu "z. B." korrigiert; doppeltes Leerzeichen entfernt | Feedback: Ellipsen ersetzen; Rechtschreibung |
| D1G | "..." durch "etc." ersetzt; Beispiele in Klammer mit "z. B." formatiert | Feedback: Ellipsen ersetzen |
| D1F | "Abfragen" zu "Abfrage" korrigiert (Singular); "zBps" zu "z. B." korrigiert; ".." und "..." durch "etc." ersetzt; `<br/>`-Umbruch entfernt | Feedback: Ellipsen ersetzen; Tippfehler; Formatierung |
| D1E | "Verifikation von Datenbeständen:`<br/>`" Präfix entfernt; Deskriptor beginnt nun mit "Ich kann..." | "Ich kann..."-Regel: Deskriptor muss mit "Ich kann" beginnen |
| Bloom-Tabelle | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neue Anforderung |
