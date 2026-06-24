---
title: M346 Cloudlösungen konzipieren und realisieren
modul: m346
cluster: cluster-cloud
date: '2025-07-02T10:05:14Z'
draft: false
kompetenzbaender:
- id: A
  titel: Anforderungen analysieren
  kompetenzen:
  - nr: 1
    hz: 1, 2
    grundlagen: Ich kann die Unternehmensziele bezüglich des IT-Betriebs benennen und deren Bedeutung für den Betrieb einer Applikation erläutern
    fortgeschritten: Ich kann aus den Unternehmenszielen die für den Applikationsbetrieb passende Strategie auswählen
    erweitert: Ich kann eine auf die Unternehmensziele ausgerichtete Strategie für den Applikationsbetrieb formulieren und positive Rückkopplungen für die Unternehmensziele aufzeigen
- id: B
  titel: Betriebsarten evaluieren
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann Service- und Betriebsmodelle des Cloud-Computings sowie deren Unterschiede beschreiben
    fortgeschritten: Ich kann passende Service- und Betriebsmodelle des Cloud-Computings für spezifische Anwendungsfälle auswählen
    erweitert: Ich kann die Cloud Service- und Betriebsmodelle des Cloud-Computings auf die Eignung für spezifische Anwendungsfälle abwägen und eine fundierte Empfehlung abgeben
- id: C
  titel: Aufwände schätzen
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann die Fremdkosten für die Betriebsarten kalkulieren
    fortgeschritten: Ich kann die Fremdkosten für die Betriebsarten kalkulieren sowie den nötigen Personalaufwand dafür abschätzen
    erweitert: Ich kann die Fremdkosten für die Betriebsarten kalkulieren, den nötigen Personalaufwand miteinbeziehen sowie anfallende Migrationsaufwände abschätzen
- id: D
  titel: Optionen auf dem Markt vergleichen
  kompetenzen:
  - nr: 1
    hz: 1, 2
    grundlagen: Ich kann die Unterschiede der verschiedenen Marktteilnehmer und deren Angeboten aufzeigen
    fortgeschritten: Ich kann aufgrund der Unterschiede der verschiedenen Marktteilnehmer und deren Angeboten passende Lösungsoptionen zusammenstellen
    erweitert: Ich kann die Optionen auf dem Markt zusammenstellen und aufgrund deren Unterschiede Optimierungen oder Alternativen aufzeigen
- id: E
  titel: Betriebsarchitektur konzipieren
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann die Bestandteile einer einfachen Betriebsarchitektur beschreiben und erklären, welche Anforderungen und Schutzziele dabei zu berücksichtigen sind
    fortgeschritten: Ich kann eine Betriebsarchitektur entwickeln, die den Anforderungen genügt, die Schutzziele einhält und einfach wartbar ist
    erweitert: Ich kann eine hochverfügbare Betriebsarchitektur entwickeln, die den Anforderungen genügt, die Schutzziele einhält, wartbar und resilient ist
- id: F
  titel: Applikation in Betrieb nehmen
  kompetenzen:
  - nr: 1
    hz: 3, 4
    grundlagen: Ich kann eine vorgegebene Applikation mittels vorgefertigten Scripts oder Rezepten in der Cloud in Betrieb nehmen
    fortgeschritten: Ich kann eine vorgegebene Applikation mittels selber erweiterten Scripts oder Rezepten individualisiert in der Cloud in Betrieb nehmen
    erweitert: Ich kann eine vorgegebene Applikation mittels selber erweiterten Scripts oder Rezepten individualisiert in der Cloud in Betrieb nehmen und dafür sorgen, dass diese automatisch skalieren kann
- id: G
  titel: Sicherheit implementieren
  kompetenzen:
  - nr: 1
    hz: 3, 4
    grundlagen: Ich kann einfache Default-Policies anwenden, um die Systemsicherheit zu gewährleisten, und einfache Backup-Massnahmen für die Datensicherheit umsetzen
    fortgeschritten: Ich kann eigene Policies implementieren, um die Systemsicherheit zu erhöhen, Backup-Massnahmen anwenden und mittels Restores das System wiederherstellen
    erweitert: Ich kann mit eigenen Policies und zusätzlichem Hardening die Systemsicherheit maximieren sowie eigene Backup-Lösungen implementieren und mittels gezielten Restores Teile des Systems wiederherstellen
- id: H
  titel: System testen
  kompetenzen:
  - nr: 1
    hz: 3, 4
    grundlagen: Ich kann einen Funktions- und Lasttest auf dem System durchführen
    fortgeschritten: Ich kann einen Funktionstest durchführen und mit einem Lasttest und gezielten Analysen die Schwächen des Systems eruieren
    erweitert: Ich kann einen Funktionstest durchführen und mit gezielten Lasttests das System an seine Grenzen bringen und die Skalierbarkeit aufzeigen
- id: I
  titel: System überwachen und skalieren
  kompetenzen:
  - nr: 1
    hz: 3, 4
    grundlagen: Ich kann mit einfachen Mitteln den Zustand des Systems überwachen und durch Hinzufügen von Ressourcen oder Speicher das System vertikal hochskalieren
    fortgeschritten: Ich kann den Zustand des Systems überwachen, mich mittels Benachrichtigungen über Probleme informieren lassen sowie das System vertikal skalieren und auf seine horizontale Skalierbarkeit beurteilen
    erweitert: Ich kann den Zustand des Systems überwachen, für allfällige Probleme entsprechende Massnahmen formulieren sowie das System vertikal skalieren und Möglichkeiten für die horizontale Skalierbarkeit aufzeigen
---

---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann die Unternehmensziele bezüglich… | 2 | Verstehen | benennen, erläutern |
| A1F  | Ich kann aus den Unternehmenszielen die… | 3 | Anwenden | auswählen |
| A1E  | Ich kann eine auf die Unternehmensziele… | 6 | Erschaffen | formulieren, aufzeigen |
| B1G  | Ich kann Service- und Betriebsmodelle des… | 2 | Verstehen | beschreiben |
| B1F  | Ich kann passende Service- und Betriebsmodelle… | 3 | Anwenden | auswählen |
| B1E  | Ich kann die Cloud Service- und Betriebsmodelle… | 5 | Bewerten | abwägen, Empfehlung abgeben |
| C1G  | Ich kann die Fremdkosten für die Betriebsarten… | 3 | Anwenden | kalkulieren |
| C1F  | Ich kann die Fremdkosten für die Betriebsarten… | 3 | Anwenden | kalkulieren, abschätzen |
| C1E  | Ich kann die Fremdkosten für die Betriebsarten… | 3 | Anwenden | kalkulieren, miteinbeziehen, abschätzen |
| D1G  | Ich kann die Unterschiede der verschiedenen… | 3 | Anwenden | aufzeigen |
| D1F  | Ich kann aufgrund der Unterschiede der… | 3 | Anwenden | zusammenstellen |
| D1E  | Ich kann die Optionen auf dem Markt zusammenstellen… | 3 | Anwenden | zusammenstellen, aufzeigen |
| E1G  | Ich kann die Bestandteile einer einfachen… | 2 | Verstehen | beschreiben, erklären |
| E1F  | Ich kann eine Betriebsarchitektur entwickeln… | 6 | Erschaffen | entwickeln |
| E1E  | Ich kann eine hochverfügbare Betriebsarchitektur… | 6 | Erschaffen | entwickeln |
| F1G  | Ich kann eine vorgegebene Applikation mittels… | 3 | Anwenden | in Betrieb nehmen |
| F1F  | Ich kann eine vorgegebene Applikation mittels… | 3 | Anwenden | in Betrieb nehmen |
| F1E  | Ich kann eine vorgegebene Applikation mittels… | 6 | Erschaffen | in Betrieb nehmen, skalieren |
| G1G  | Ich kann einfache Default-Policies anwenden… | 3 | Anwenden | anwenden, umsetzen |
| G1F  | Ich kann eigene Policies implementieren… | 3 | Anwenden | implementieren, wiederherstellen |
| G1E  | Ich kann mit eigenen Policies und zusätzlichem… | 5 | Bewerten | maximieren, implementieren, wiederherstellen |
| H1G  | Ich kann einen Funktions- und Lasttest auf… | 3 | Anwenden | durchführen |
| H1F  | Ich kann einen Funktionstest durchführen und… | 4 | Analysieren | durchführen, eruieren, analysieren |
| H1E  | Ich kann einen Funktionstest durchführen und… | 4 | Analysieren | durchführen, aufzeigen |
| I1G  | Ich kann mit einfachen Mitteln den Zustand… | 3 | Anwenden | überwachen, skalieren |
| I1F  | Ich kann den Zustand des Systems überwachen… | 5 | Bewerten | überwachen, beurteilen |
| I1E  | Ich kann den Zustand des Systems überwachen… | 5 | Bewerten | überwachen, formulieren, aufzeigen |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Tabellenheader | "Kompetenzband:" → "Kompetenzband" (Doppelpunkt entfernt) | Formatkonformität gemäss Vorgabe |
| Tabellenseparator | Korrigiert zu `\| --- \| --- \| :--- \| --- \| --- \|` | Formatkonformität gemäss Vorgabe |
| Alle Zellen | Alle `<br/>`-Tags zwischen Zell-ID und Deskriptor entfernt; Format ist nun "A1G: Ich kann..." | Einheitliches Format gemäss Vorlage |
| A1G | "Ich kenne die Unternehmensziele..." → "Ich kann die Unternehmensziele... benennen und deren Bedeutung... erläutern" | "Ich kann"-Format |
| B1G | "Ich kenne Service- und Betriebsmodelle..." → "Ich kann Service- und Betriebsmodelle... beschreiben" | "Ich kann"-Format |
| B1E | Doppelter Leerschlag vor "abgeben" entfernt | Formatbereinigung |
| C1G | Doppelter Leerschlag nach "Betriebsarten" entfernt | Formatbereinigung |
| C1F, C1E | ", sowie" → "sowie" (Komma entfernt) | Kein Komma vor "sowie" im Schweizer Hochdeutsch |
| D1F | Überflüssiges Komma nach "Angeboten," entfernt | Grammatikfehler behoben |
| D1E | Überflüssiges Komma nach "Unterschiede," entfernt | Grammatikfehler behoben |
| E1E | Doppelter Leerschlag vor "wartbar" entfernt | Formatbereinigung |
| F1F, F1E | Überflüssiges Komma nach "Rezepten," entfernt | Grammatikfehler behoben |
| G1E | "zusäztlichem" → "zusätzlichem" | Tippfehler behoben |
| H1E | Doppelter Leerschlag nach "implementieren" entfernt | Formatbereinigung |
| K1G | "hinzufügen" → "Hinzufügen" | Substantivierung korrekt grossgeschrieben |
| Diverse Zellen | Mehrere doppelte Leerschläge in Zellen bereinigt | Formatbereinigung |
| G + H (alt) → G (neu) | Kompetenzband "G - System-Sicherheit implementieren" und "H - Datensicherheit implementieren" zusammengeführt zu "G - Sicherheit implementieren"; Inhalte beider Bänder in je einer Zelle pro Gütestufe vereint; Zell-IDs G1G/G1F/G1E | Thematische Zusammenführung: Beide Bänder behandeln Sicherheitsaspekte (System- und Datensicherheit) mit identischen HZ (3, 4); Reduktion auf max. 9 Zeilen erforderlich |
| J + K (alt) → I (neu) | Kompetenzband "J - System überwachen" und "K - System skalieren" zusammengeführt zu "I - System überwachen und skalieren"; Inhalte beider Bänder in je einer Zelle pro Gütestufe vereint; Zell-IDs I1G/I1F/I1E | Thematische Zusammenführung: Beide Bänder betreffen den laufenden Betrieb (Monitoring und Skalierung) mit identischen HZ (3, 4); Reduktion auf max. 9 Zeilen erforderlich |
| I (alt) → H (neu) | Kompetenzband "I - System testen" umbenannt zu "H - System testen"; Zell-IDs angepasst (I1G/I1F/I1E → H1G/H1F/H1E) | Sequenzielle Neunummerierung nach Zusammenführungen |
| E1G | "entwickeln" (Bloom L6, zu hoch für Grundlagen) → "Bestandteile beschreiben und erklären, welche Anforderungen zu berücksichtigen sind" (Bloom L2) | Regel 1: G-Zellen dürfen maximal Bloom L3 erreichen; "entwickeln" ist L6 (Erschaffen) |
| C1F | Rückgängig: "begründen" (Bloom L5) → ursprüngliches "kalkulieren sowie abschätzen" (Bloom L3) wiederhergestellt | Korrektur: Gleiches Bloom-Niveau wie G-Stufe (L3=L3) ist zulässig (kein Verstoss gegen Regel 2) |
| C1E | Rückgängig: "fundierte Gesamtbeurteilung ableiten" (Bloom L5) → ursprüngliches "kalkulieren, miteinbeziehen sowie abschätzen" (Bloom L3) wiederhergestellt | Korrektur: Gleiches Bloom-Niveau wie F-Stufe (L3=L3) ist zulässig (kein Verstoss gegen Regel 2) |
| D1E | Rückgängig: "Eignung beurteilen" (Bloom L5) → ursprüngliches "zusammenstellen und aufzeigen" (Bloom L3) wiederhergestellt | Korrektur: Gleiches Bloom-Niveau wie F-Stufe (L3=L3) ist zulässig (kein Verstoss gegen Regel 2) |
| F1F | Rückgängig: "Konfigurationsschritte dokumentieren" entfernt → ursprüngliches "individualisiert in Betrieb nehmen" (Bloom L3) wiederhergestellt | Korrektur: Gleiches Bloom-Niveau wie G-Stufe (L3=L3) ist zulässig (kein Verstoss gegen Regel 2) |
| Bloom-Tabelle | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neu hinzugefügt gemäss Workflow |
