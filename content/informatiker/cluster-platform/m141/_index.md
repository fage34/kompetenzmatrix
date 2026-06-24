---
title: M141 Datenbanksystem in Betrieb nehmen
modul: m141
cluster: cluster-platform
date: '2025-07-02T10:06:43Z'
draft: false
kompetenzbaender:
- id: A
  titel: Inbetriebnahme
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann ein einfaches relationales Datenbankmanagementsystem in Betrieb nehmen
    fortgeschritten: Ich kann verschiedene Arten von Datenbankmanagementsystemen in Betrieb nehmen
    erweitert: Ich kann für eine gegebene Anforderung den passenden Typ eines Datenbankmanagementsystems evaluieren
  - nr: 2
    hz: '1'
    grundlagen: Ich kann das Datenbankmanagementsystem so bereitstellen, dass die Funktionalität gewährleistet ist
    fortgeschritten: Ich kann wichtige Parameter des Datenbankmanagementsystems fachgerecht setzen, um die Funktionalität und Performance zu gewährleisten
    erweitert: Ich kann in einer anspruchsvollen DBMS-Umgebung Einflussfaktoren (hoher Speicherbedarf, hohes Transaktionsvolumen und hohe Verfügbarkeit) erkennen und Mittel nennen, um die hohen Anforderungen zu erfüllen
- id: B
  titel: DB/Tabellen einrichten
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann Daten (Dump) in ein Datenbankmanagementsystem laden
    fortgeschritten: Ich kann Daten von einem bisherigen Datenbankmanagementsystem migrieren, ins vorliegende DBMS-Schema überführen und ins System integrieren
    erweitert: Ich kann typenfremde Daten ins vorliegende DBMS-Schema migrieren, validieren und ins System integrieren
- id: C
  titel: Operativer Betrieb
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann das Datenbankmanagementsystem mit Standard-Tools absichern
    fortgeschritten: Ich kann das Datenbankmanagementsystem absichern und dabei DBMS-Funktionen mit Systemdesign-Möglichkeiten wie z. B. RAID oder Cluster ergänzen
    erweitert: Ich kann das Datenbankmanagementsystem mit einer ganzheitlich durchdachten Lösung absichern, die mehrere Sicherheitsebenen berücksichtigt
  - nr: 2
    hz: 3, 7
    grundlagen: Ich kann einfache Tests durchführen und diese in einem vorgegebenen Schema festhalten
    fortgeschritten: Ich kann das Datenbankmanagementsystem mit spezifischen Tests überprüfen und das Resultat im Testprotokoll festhalten
    erweitert: Ich kann das Datenbankmanagementsystem mit Benchmarking messen und das Testprotokoll mit fachgerechten Verbesserungsvorschlägen ergänzen
- id: D
  titel: Berechtigungen
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann spezifische Zugriffsrechte auf DB-Ebene vergeben
    fortgeschritten: Ich kann spezifische Zugriffsrechte auf verschiedene Objekte der DB vergeben
    erweitert: Ich kann spezifische Zugriffsrechte in komplexen Umgebungen erteilen und fehlerhafte Vergaben korrigieren
  - nr: 2
    hz: '4'
    grundlagen: Ich kann Stored Procedures und Views nach Vorgabe einrichten
    fortgeschritten: Ich kann Stored Procedures und Views einsetzen, um die Zugriffsmöglichkeiten zu verbessern
    erweitert: Ich kann Stored Procedures und Views aus einer Praxis-Situation ableiten und einrichten
- id: E
  titel: Abnahme
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann ein Datenbankmanagementsystem fachgerecht dokumentieren
    fortgeschritten: Ich kann die Übergabe an den Betrieb planen und das Abnahmeprotokoll mit der fachgerechten Dokumentation bereitstellen
    erweitert: Ich kann die Übergabe an den Betrieb planen und das Abnahmeprotokoll mit der vollständigen fachgerechten Dokumentation bereitstellen
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann ein einfaches relationales Datenbankmanagementsystem… | 3 | Anwenden | in Betrieb nehmen |
| A1F  | Ich kann verschiedene Arten von Datenbankmanagementsystemen… | 3 | Anwenden | in Betrieb nehmen |
| A1E  | Ich kann für eine gegebene Anforderung den passenden Typ… | 5 | Bewerten | evaluieren |
| A2G  | Ich kann das Datenbankmanagementsystem so bereitstellen… | 3 | Anwenden | bereitstellen |
| A2F  | Ich kann wichtige Parameter des Datenbankmanagementsystems setzen… | 3 | Anwenden | setzen |
| A2E  | Ich kann in einer anspruchsvollen DBMS-Umgebung Einflussfaktoren erkennen… | 4 | Analysieren | erkennen (Muster), nennen |
| B1G  | Ich kann Daten (Dump) in ein Datenbankmanagementsystem laden… | 3 | Anwenden | laden |
| B1F  | Ich kann Daten von einem bisherigen Datenbankmanagementsystem migrieren… | 3 | Anwenden | migrieren, überführen, integrieren |
| B1E  | Ich kann typenfremde Daten ins vorliegende DBMS-Schema migrieren… | 5 | Bewerten | migrieren, validieren, integrieren |
| C1G  | Ich kann das Datenbankmanagementsystem mit Standard-Tools absichern… | 3 | Anwenden | absichern |
| C1F  | Ich kann das Datenbankmanagementsystem absichern und ergänzen… | 3 | Anwenden | absichern, ergänzen |
| C1E  | Ich kann das Datenbankmanagementsystem mit einer ganzheitlich durchdachten… | 3 | Anwenden | absichern |
| C2G  | Ich kann einfache Tests durchführen und festhalten… | 3 | Anwenden | durchführen, festhalten |
| C2F  | Ich kann das Datenbankmanagementsystem mit spezifischen Tests überprüfen… | 3 | Anwenden | überprüfen, festhalten |
| C2E  | Ich kann das Datenbankmanagementsystem mit Benchmarking messen… | 4 | Analysieren | messen, ergänzen |
| D1G  | Ich kann spezifische Zugriffsrechte auf DB-Ebene vergeben… | 3 | Anwenden | vergeben |
| D1F  | Ich kann spezifische Zugriffsrechte auf verschiedene Objekte vergeben… | 3 | Anwenden | vergeben |
| D1E  | Ich kann spezifische Zugriffsrechte in komplexen Umgebungen erteilen… | 3 | Anwenden | erteilen, korrigieren |
| D2G  | Ich kann Stored Procedures und Views nach Vorgabe einrichten… | 3 | Anwenden | einrichten |
| D2F  | Ich kann Stored Procedures und Views einsetzen… | 3 | Anwenden | einsetzen |
| D2E  | Ich kann Stored Procedures und Views aus einer Praxis-Situation ableiten… | 4 | Analysieren | ableiten, einrichten |
| E1G  | Ich kann ein Datenbankmanagementsystem fachgerecht dokumentieren… | 3 | Anwenden | dokumentieren |
| E1F  | Ich kann die Übergabe an den Betrieb planen… | 3 | Anwenden | planen, bereitstellen |
| E1E  | Ich kann die Übergabe an den Betrieb planen und das Abnahmeprotokoll… | 3 | Anwenden | planen, bereitstellen |

---

## Änderungsprotokoll V2

| Datum | Zelle / Bereich | Änderung | Regel |
| --- | --- | --- | --- |
| 2026-03-26 | Header | `Kompetenzband:` zu `Kompetenzband` korrigiert (Doppelpunkt entfernt) | Regel 5: Tabellenformat |
| 2026-03-26 | Separator | Dritte Spalte von `---` zu `:---` korrigiert | Regel 6: Tabellen-Separator |
| 2026-03-26 | Alle Kompetenzbänder | Buchstaben-Präfix hinzugefügt (A - Inbetriebnahme, B - DB/Tabellen einrichten, etc.) | Regel 9: Buchstaben-Präfix |
| 2026-03-26 | A1G | Produktnamen "MySQL/Maria-DB" durch "relationales Datenbankmanagementsystem" ersetzt | Regel 7: Produktneutralität |
| 2026-03-26 | A1E | "für den Kunden" durch "für eine gegebene Anforderung" ersetzt (produktneutral) | Regel 7: Produktneutralität |
| 2026-03-26 | A2E | Doppeltes Leerzeichen korrigiert; "auch" entfernt | Regel 3: Formulierung |
| 2026-03-26 | B1F | "migriert" zu "migrieren" korrigiert (Grammatik) | Regel 7: Schweizer Hochdeutsch |
| 2026-03-26 | C1F, C1E | Satzabhängigkeit aufgelöst; jede Zelle ist nun eigenständig formuliert | Regel 2: Eigenständigkeit |
| 2026-03-26 | C2G | "vorgegebenem" zu "vorgegebenen" korrigiert (Grammatik) | Regel 7: Schweizer Hochdeutsch |
| 2026-03-26 | Diverse Zellen | "DBMS" durch "Datenbankmanagementsystem" ersetzt, wo Langform klarer ist | Regel 7: Terminologie |
| 2026-03-26 | Alle Zellen | Abschliessende Punkte entfernt | Regel 10: Keine Punkte am Ende |
| 2026-04-02 | Alle Zellen | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neue Anforderung: Bloom-Analyse pro Zelle |
| 2026-04-02 | B1E | Bloom-Stufe korrigiert: L4 → L5 (Bewerten), da "validieren" Bloom-Stufe 5 entspricht | Bloom-Analyse-Korrektur |
