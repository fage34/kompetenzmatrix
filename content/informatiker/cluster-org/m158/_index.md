---
title: M158 Software-Migration planen und durchführen
modul: m158
cluster: cluster-org
date: '2025-07-02T10:06:07Z'
draft: false
kompetenzbaender:
- id: A
  titel: Release-Situation analysieren
  kompetenzen:
  - nr: 1
    hz: 1, 6
    grundlagen: Ich kann die Architektur eines Softwaresystems und nötige Schritte zur Release-Migration erfassen
    fortgeschritten: Ich kann die Architektur eines mehrstufigen Softwaresystems und nötige Schritte für eine komplexe Release-Migration erfassen
    erweitert: Ich kann die Architektur eines mehrstufigen Softwaresystems erfassen und in eine andere Zielumgebung überführen
  - nr: 2
    hz: 1, 5
    grundlagen: Ich kann Elemente einer System-Konfiguration interpretieren
    fortgeschritten: Ich kann Elemente einer bestehenden System-Konfiguration in das Zielsystem überführen
    erweitert: Ich kann die Korrektheit einer System-Konfiguration durch geeignete Testfälle nachweisen
- id: B
  titel: Software in Testumgebung in Betrieb nehmen
  kompetenzen:
  - nr: 1
    hz: 2, 3, 7
    grundlagen: Ich kann eine Zielumgebung gemäss Vorgabe aufbauen
    fortgeschritten: Ich kann eine neue Zielumgebung aufbauen, diese mit dem alten System vergleichen und daraus einen allfälligen Handlungsbedarf festhalten
    erweitert: Ich kann die Erstellung eines Zielsystems so planen, wählen und umsetzen, dass Wartbarkeit und Skalierbarkeit verbessert werden
- id: C
  titel: Umstellung und Schritte planen
  kompetenzen:
  - nr: 1
    hz: '6'
    grundlagen: Ich kann Arbeitsschritte für eine Umstellung formulieren und erklären, wer im Zusammenhang mit der Umstellung informiert werden muss
    fortgeschritten: Ich kann die Arbeitsschritte für die Umstellung formulieren, ein Wartungsfenster wählen und erklären, welche Anspruchsgruppe welche Informationen erhalten soll
    erweitert: Ich kann aufgrund der Erfahrungen aus dem Testsystem die Schritte für die Umstellung und ein passendes Wartungsfenster planen und begründen sowie sinnvolle Informationen für verschiedene Anspruchsgruppen erstellen
- id: D
  titel: Datenmigration durchführen
  kompetenzen:
  - nr: 1
    hz: 3, 4, 7
    grundlagen: Ich kann erklären, wie Daten extrahiert, transformiert und importiert werden können
    fortgeschritten: Ich kann analysieren, wie und wo eine Applikation Daten ablegt (Datenbank, Dateisystem) und die Schritte zur Übernahme der Daten manuell durchführen und entscheiden, welche Anpassungen nötig sind
    erweitert: Ich kann die Korrektheit einer Datenmigration beurteilen und das beste Vorgehen vorschlagen (Migrationsstrategie, Programmierung, ETL-Tools etc.). Ich kann Scripte und Methoden zur automatisierten Migration des Systems entwickeln
- id: E
  titel: Korrektheit der Migration nachweisen
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann Kriterien für Testfälle formulieren, welche die Richtigkeit der Migration bestätigen
    fortgeschritten: Ich kann Testfälle aufstellen und ausführen, welche die Richtigkeit der Migration bestätigen
    erweitert: Ich kann die Korrektheit der Migration nach erfolgtem Testdurchlauf aus Mikro- (Datensicht) und Makrosicht (Prozesssicht) beurteilen
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann die Architektur eines Softwaresystems… | 2 | Verstehen | erfassen |
| A1F  | Ich kann die Architektur eines mehrstufigen… | 2 | Verstehen | erfassen |
| A1E  | Ich kann die Architektur eines mehrstufigen… | 3 | Anwenden | erfassen, überführen |
| A2G  | Ich kann Elemente einer System-Konfiguration… | 2 | Verstehen | interpretieren |
| A2F  | Ich kann Elemente einer bestehenden System-Konfiguration… | 3 | Anwenden | überführen |
| A2E  | Ich kann die Korrektheit einer System-Konfiguration… | 5 | Bewerten | nachweisen |
| B1G  | Ich kann eine Zielumgebung gemäss Vorgabe… | 3 | Anwenden | aufbauen |
| B1F  | Ich kann eine neue Zielumgebung aufbauen… | 3 | Anwenden | aufbauen, vergleichen, festhalten |
| B1E  | Ich kann die Erstellung eines Zielsystems… | 5 | Bewerten | planen, wählen, umsetzen |
| C1G  | Ich kann Arbeitsschritte für eine Umstellung… | 3 | Anwenden | formulieren, erklären |
| C1F  | Ich kann die Arbeitsschritte für die Umstellung… | 3 | Anwenden | formulieren, wählen, erklären |
| C1E  | Ich kann aufgrund der Erfahrungen aus dem… | 5 | Bewerten | planen, begründen, erstellen |
| D1G  | Ich kann erklären, wie Daten extrahiert… | 2 | Verstehen | erklären |
| D1F  | Ich kann analysieren, wie und wo eine… | 4 | Analysieren | analysieren, entscheiden |
| D1E  | Ich kann die Korrektheit einer Datenmigration… | 6 | Erschaffen | beurteilen, vorschlagen, entwickeln |
| E1G  | Ich kann Kriterien für Testfälle formulieren… | 3 | Anwenden | formulieren |
| E1F  | Ich kann Testfälle aufstellen und ausführen… | 3 | Anwenden | aufstellen, ausführen |
| E1E  | Ich kann die Korrektheit der Migration nach… | 5 | Bewerten | beurteilen |

---

## Änderungsprotokoll V2

| Datum | Zelle / Bereich | Änderung |
| --- | --- | --- |
| 2026-03-26 | Tabellenheader | Leerzeichen in Header-Zellen normalisiert für einheitliche Formatierung |
| 2026-03-26 | Tabellenseparator | Separator korrigiert: dritte Spalte (Grundlagen) auf `:---` geändert gemäss Vorgabe |
| 2026-03-26 | A, B, C, D, E (Kompetenzband) | Trennzeichen von `:` auf ` - ` geändert (z. B. `A: Release-Situation` → `A - Release-Situation`) |
| 2026-03-26 | Alle Deskriptoren | Abschliessende Punkte entfernt (keine Trailing Periods gemäss Vorgabe) |
| 2026-03-26 | C1E | Kleinbuchstabe `ich kann` korrigiert zu `Ich kann` |
| 2026-03-26 | C1E | Überflüssiges Komma nach `ich kann,` entfernt und Satzstruktur bereinigt; Komma vor `sowie` entfernt |
| 2026-03-26 | C1F | Doppeltes Leerzeichen vor `formulieren` entfernt |
| 2026-03-26 | A2 (HZ) | Fehlende Leerstelle ergänzt: `1,5` → `1, 5` |
| 2026-03-26 | D1E | Eckige Klammern um ETL entfernt (`[ETL-]Tools` → `ETL-Tools`), da keine Erklärung nötig |
| 2026-04-02 | Bloom-Taxonomie-Analyse | Bloom-Analyse-Tabelle hinzugefügt. Keine Bloom-Verstösse festgestellt (alle G-Zellen ≤ Stufe 3, G≤F≤E monoton). |
