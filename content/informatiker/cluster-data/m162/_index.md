---
title: M162 Daten analysieren und modellieren
modul: m162
cluster: cluster-data
date: '2025-07-02T10:05:24Z'
draft: false
kompetenzbaender:
- id: A
  titel: Formen und Struktur von Daten erkennen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann Formen von Daten aufzählen und diese beschreiben (numerisch, Text, Medien).
    fortgeschritten: Ich kann die Form der Speicherung verschiedener Daten unterscheiden (Dateitypen / Datentypen).
    erweitert: Ich kann die Auswertbarkeit von Daten, deren Möglichkeiten und Grenzen vergleichen.
- id: B
  titel: Merkmale eines Datenbestandes
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann die Konsequenz der Struktur auf die Möglichkeit der Auswertbarkeit (Text tiefe Auswertbarkeit, Tabelle mittel, DB hoch) erläutern.
    fortgeschritten: Ich kann abhängig von der Struktur eine Auswertung durchführen (Text, Tabelle usw.).
    erweitert: Ich kann aufzeigen, wie mit Hilfe einer Strukturtransformation Daten in eine besser auswertbare Form gebracht werden können.
- id: C
  titel: Daten- und Skalentypen
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann verschiedene Datentypen (ganze Zahl, rationale Zahlen, Zeit, Datum, Text, Boolean usw.) sowie die Unterschiede der Skalentypen (nominal, ordinal und metrisch) erläutern.
    fortgeschritten: Ich kann für vorliegende Daten den richtigen Datentyp bestimmen und die Skalentypen auf Daten anwenden.
    erweitert: Ich kann Daten eines bestimmten Typs zu einem anderen Datentyp transformieren und einen bestimmten Skalentyp begründet auswählen.
- id: D
  titel: Daten auswerten und visualisieren
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann gängige Diagrammtypen (Balken, Säule, Kreis, Netz, Linie) und ihre typischen Einsatzgebiete erläutern sowie die wichtigsten statistischen Kenngrössen (Minimum, Maximum, Mittelwert, Anzahl, Median) und ihre Voraussetzungen (Skalentypen, Anzahl Beobachtungen, Datenqualität usw.) erklären.
    fortgeschritten: Ich kann aus vorliegenden Daten Diagramme erstellen und Daten mit gegebenen Anforderungen mittels passenden Kenngrössen auswerten sowie eine Statistik mit geeigneten Skalentypen erstellen.
    erweitert: Ich kann Tendenzen in Auswertungsergebnissen ableiten und beschreiben sowie eine Statistik mit passenden Kenngrössen und Skalentypen kritisch hinterfragen und Verbesserungen vorschlagen.
- id: E
  titel: Datenschutz in Auswertungen
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann erläutern, wieso personenbezogene Daten nicht ohne Weiteres in Auswertungen und Statistiken eingesetzt, weitergeleitet oder publiziert werden dürfen.
    fortgeschritten: Ich kann bei einer gegebenen Auswertung beurteilen, ob personenbezogene Daten angemessen geschützt sind.
    erweitert: Ich kann Massnahmen vorschlagen, um personenbezogene Daten in Auswertungen und Statistiken zu anonymisieren oder zu pseudonymisieren.
- id: F
  titel: Konzeptionelles Datenmodell anwenden
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann Elemente eines konzeptionellen Datenmodells (Entitätstyp, Attribut, Assoziation, unterschiedliche Kardinalität usw.) erläutern.
    fortgeschritten: Ich kann aus gegebenen Anforderungen ein konzeptionelles Datenmodell erstellen.
    erweitert: Ich kann ein konzeptionelles Datenmodell eigenständig entwerfen, auf Vollständigkeit prüfen und begründete Anpassungen vornehmen.
- id: G
  titel: Logisches relationales Datenmodell und Identifikationsschlüssel
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann Unterschiede von einem konzeptionellen und einem logischen relationalen Datenmodell aufzählen und beschreiben sowie Eigenschaften von Identifikationsmerkmalen (Eindeutigkeit, Definiertheit, Minimalität, Lebenslänglich usw.) an einem Beispiel erklären.
    fortgeschritten: Ich kann ein konzeptionelles Datenmodell in ein logisches relationales Datenmodell überführen (Schlüssel, Fremdschlüssel, Kardinalitäten, Zwischentabelle usw.) und für Entitäten einen geeigneten Schlüssel begründet auswählen (einfache, zusammengesetzte und künstliche Schlüssel).
    erweitert: Ich kann ein logisches relationales Datenbankmodell analysieren und daraus das konzeptionelle Modell ableiten (Reverse Engineering) sowie Schlüsselkandidaten auf ihre Eignung beurteilen und begründete Verbesserungsvorschläge formulieren (z. B. 8-stellige Artikelnummer, alte AHV-Nr., IPv4 usw.).
- id: H
  titel: Normalisierung auf bestehendes Datenmodell anwenden
  kompetenzen:
  - nr: 1
    hz: '6'
    grundlagen: Ich kann das Ziel der Normalisierung beschreiben.
    fortgeschritten: Ich kann die Normalisierung (1. bis 3. Normalform) anwenden.
    erweitert: Ich kann die Normalisierung kritisch hinterfragen, z. B. in Bezug darauf, wie sie sich auf die Performance auswirkt, und Verbesserungen vorschlagen.
- id: I
  titel: Datenmodell als ERD zeichnen
  kompetenzen:
  - nr: 1
    hz: '7'
    grundlagen: Ich kann ein einfaches ERD mit einem Tool zeichnen (bis 3 Entitäten).
    fortgeschritten: Ich kann ein Datenmodell mit Zwischentabellen, Attributen und Datentypen mit Hilfe eines Tools zeichnen (bis 10 Tabellen).
    erweitert: Ich kann mich selbständig in ein mir fremdes Tool einarbeiten und innert nützlicher Frist ein Datenmodell zeichnen.
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann Formen von Daten aufzählen… | 2 | Verstehen | aufzählen, beschreiben |
| A1F  | Ich kann die Form der Speicherung… | 2 | Verstehen | unterscheiden |
| A1E  | Ich kann die Auswertbarkeit von Daten… | 4 | Analysieren | vergleichen (Möglichkeiten/Grenzen) |
| B1G  | Ich kann die Konsequenz der Struktur… | 2 | Verstehen | erläutern |
| B1F  | Ich kann abhängig von der Struktur… | 3 | Anwenden | durchführen |
| B1E  | Ich kann aufzeigen, wie mit Hilfe… | 3 | Anwenden | aufzeigen |
| C1G  | Ich kann verschiedene Datentypen… | 2 | Verstehen | erläutern |
| C1F  | Ich kann für vorliegende Daten… | 3 | Anwenden | bestimmen, anwenden |
| C1E  | Ich kann Daten eines bestimmten Typs… | 5 | Bewerten | transformieren, begründet auswählen |
| D1G  | Ich kann gängige Diagrammtypen… | 2 | Verstehen | erläutern, erklären |
| D1F  | Ich kann aus vorliegenden Daten… | 3 | Anwenden | erstellen, auswerten |
| D1E  | Ich kann Tendenzen in Auswertungsergebnissen… | 5 | Bewerten | ableiten, hinterfragen, vorschlagen |
| E1G  | Ich kann erläutern, wieso personenbezogene… | 2 | Verstehen | erläutern |
| E1F  | Ich kann bei einer gegebenen Auswertung… | 5 | Bewerten | beurteilen |
| E1E  | Ich kann Massnahmen vorschlagen, um… | 5 | Bewerten | vorschlagen |
| F1G  | Ich kann Elemente eines konzeptionellen… | 2 | Verstehen | erläutern |
| F1F  | Ich kann aus gegebenen Anforderungen… | 6 | Erschaffen | erstellen |
| F1E  | Ich kann ein konzeptionelles Datenmodell… | 6 | Erschaffen | entwerfen, prüfen, vornehmen |
| G1G  | Ich kann Unterschiede von einem konzeptionellen… | 2 | Verstehen | aufzählen, beschreiben, erklären |
| G1F  | Ich kann ein konzeptionelles Datenmodell… | 5 | Bewerten | überführen, begründet auswählen |
| G1E  | Ich kann ein logisches relationales Datenbankmodell… | 5 | Bewerten | analysieren, ableiten, beurteilen, formulieren |
| H1G  | Ich kann das Ziel der Normalisierung… | 2 | Verstehen | beschreiben |
| H1F  | Ich kann die Normalisierung anwenden… | 3 | Anwenden | anwenden |
| H1E  | Ich kann die Normalisierung kritisch hinterfragen… | 5 | Bewerten | hinterfragen, vorschlagen |
| I1G  | Ich kann ein einfaches ERD mit einem Tool… | 3 | Anwenden | zeichnen |
| I1F  | Ich kann ein Datenmodell mit Zwischentabellen… | 3 | Anwenden | zeichnen |
| I1E  | Ich kann mich selbständig in ein mir… | 3 | Anwenden | einarbeiten, zeichnen |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Alle Zellen | Hanok-Referenzen ("Hanok X.X"-Verweise) entfernt | Produktneutralität |
| D3G, D3F, D3E (neu) | Ehemaliges Kompetenzband E (Geheimhaltung) aufgelöst; E1G in D3 integriert mit vollständigen Gütestufen | E1G hatte keine F/E-Stufen — Inhalt als D3 weitergeführt mit vollständiger Progression |
| Alle Bänder | Kompetenzbänder auf Format "Buchstabe - Thematische Zusammenfassung" umbenannt | Vorgabe Tabellenformat |
| Alle Bänder | Nach Auflösung von E (Geheimhaltung) neu durchnummeriert: F→E, G→F, H→G, I→H, J→I | Fortlaufende Buchstabenfolge |
| D1F, D2E, C1E, H1E, E1G | Grammatik- und Rechtschreibkorrekturen: "vorliegende"→"vorliegenden", "passende"→"passenden", "Types"→"Typs", "wie sich"→"wie sie sich", "Datenmodelles"→"Datenmodells" | Korrekte Grammatik |
| B1G, D1G, D2G, F1G, I1E | Doppelte Leerzeichen entfernt | Formatbereinigung |
| F1G, G1F | `<br />`-Tags entfernt | Keine HTML-Tags in Markdown-Tabellen |
| Alle Zellen | Interpunktion vereinheitlicht: "usw." statt ", usw." / "...", Punkte in Klammern entfernt | Konsistente Formatierung |
| Header | "Kompetenzband:" → "Kompetenzband" (Doppelpunkt entfernt), Spaltenausrichtung vereinheitlicht | Vorgabe |
| C1, C2 → C1 | Zeilen C1 (Datentypen) und C2 (Skalentypen) zusammengeführt zu einer Zeile C1 | Beide Zeilen gehören zu HZ 2 und behandeln eng verwandte Klassifikationskonzepte (Typen und Skalen von Daten); Zusammenführung reduziert Redundanz |
| D1, D2 → D1 | Zeilen D1 (Diagramme) und D2 (statistische Kenngrössen) zusammengeführt zu einer Zeile D1 | Beide Zeilen gehören zu HZ 3 und beschreiben komplementäre Aspekte der Datenauswertung und -visualisierung |
| F (ehem. G), G (ehem. H) → G | Ehemalige Bänder G (logisches Datenmodell) und H (Identifikationsschlüssel) zusammengeführt zu Band G | Beide Bänder gehören zu HZ 5 und behandeln zusammenhängende Aspekte des relationalen Datenmodells; Schlüssel sind integraler Bestandteil des logischen Modells |
| Alle Bänder | Nach Konsolidierung auf 9 Zeilen neu durchnummeriert: D3→E, E→F, F+G→G, H→H, I→I | Fortlaufende Buchstabenfolge nach Zusammenführungen |
| D1G | Bloom Regel 1: "begründet für die Darstellung von Daten auswählen" (Stufe 5) entfernt. Neu: "gängige Diagrammtypen ... und ihre typischen Einsatzgebiete erläutern ... erklären" (Stufe 2) | G-Zellen dürfen maximal Bloom-Stufe 3 erreichen; "begründet auswählen" entspricht Stufe 5 (Bewerten) |
| F1E | Bloom Regel 2: F1F ist Stufe 6 (Erschaffen), F1E war Stufe 5 (Bewerten) — nicht-monotone Abnahme. Neu: "Ich kann ein konzeptionelles Datenmodell eigenständig entwerfen, auf Vollständigkeit prüfen und begründete Anpassungen vornehmen." (Stufe 6) | Regel 2: Level(G) ≤ Level(F) ≤ Level(E) muss eingehalten werden |
| G1E | Bloom Regel 2: G1F ist Stufe 5 (Bewerten), G1E war Stufe 4 (Analysieren) — nicht-monotone Abnahme. Neu: "beurteilen und begründete Verbesserungsvorschläge formulieren" statt "analysieren und mögliche Probleme benennen" | Stufe auf 5 (Bewerten) angehoben |
| Bloom-Tabelle | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neue Anforderung |
