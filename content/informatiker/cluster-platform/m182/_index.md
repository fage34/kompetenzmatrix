---
title: M182 Systemsicherheit implementieren
modul: m182
cluster: cluster-platform
date: '2025-07-02T10:41:27Z'
draft: false
kompetenzbaender:
- id: A
  titel: Angriffsmöglichkeiten erkennen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann aufgrund der System-Dokumentation und des Netzwerkschemas einzelne Angriffsmöglichkeiten aufzeigen
    fortgeschritten: Ich kann mittels System-Dokumentation und Netzwerkschema unterschiedliche Angriffsmöglichkeiten aufzeigen
    erweitert: Ich kann aus einer System-Dokumentation und einem Netzwerkschema unterschiedliche Angriffsmöglichkeiten analysieren und deren mögliche Auswirkungen auf das System beurteilen
- id: B
  titel: Massnahmen ausarbeiten
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann einfache Massnahmen zur Stärkung der Systemsicherheit aufzeigen
    fortgeschritten: Ich kann verschiedene Massnahmen zur Stärkung der Systemsicherheit fachgerecht konfigurieren und deren Wirkung auf das System erläutern
    erweitert: Ich kann selbständig Massnahmen zur Stärkung der Systemsicherheit aufzeigen, die vertiefte Kenntnisse über die verwendeten Dienste erfordern
- id: C
  titel: Implementation und Dokumentation
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann Massnahmen implementieren und in einer bestehenden Dokumentation ergänzen
    fortgeschritten: Ich kann Massnahmen fachgerecht auf das jeweilige System individuell konfigurieren und dokumentieren
    erweitert: Ich kann selbständig die Konfiguration der Implementation konzipieren, umsetzen und komplexere Sicherheitsmassnahmen begründet dokumentieren
- id: D
  titel: HIDS in Betrieb nehmen
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann ein HIDS in Betrieb nehmen
    fortgeschritten: Ich kann ein geeignetes HIDS auswählen und auf eine bestimmte Systemsituation konfigurieren
    erweitert: Ich kann ein HIDS in Betrieb nehmen, dessen Grenzen beurteilen, es angepasst konfigurieren und mit zusätzlichen Massnahmen (Schulung, Intrusion Prevention, Passwort-Tooling) ergänzen
- id: E
  titel: Logdaten-Analyse
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann ein HIDS nach Vorgabe an ein Monitoring-System anbinden
    fortgeschritten: Ich kann System- und Tool-Meldungen selbständig an ein Monitoring-System anbinden
    erweitert: Ich kann den Prozess von System- und Tool-Meldungen aufzeigen und mögliche konzeptionelle Probleme in diesem Zusammenhang erklären
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann aufgrund der System-Dokumentation einzelne Angriffsmöglichkeiten… | 3 | Anwenden | aufzeigen |
| A1F  | Ich kann mittels System-Dokumentation unterschiedliche Angriffsmöglichkeiten… | 3 | Anwenden | aufzeigen |
| A1E  | Ich kann aus einer System-Dokumentation Angriffsmöglichkeiten analysieren… | 5 | Bewerten | analysieren, beurteilen |
| B1G  | Ich kann einfache Massnahmen zur Stärkung der Systemsicherheit… | 3 | Anwenden | aufzeigen |
| B1F  | Ich kann verschiedene Massnahmen zur Stärkung der Systemsicherheit konfigurieren… | 3 | Anwenden | konfigurieren, erläutern |
| B1E  | Ich kann selbständig Massnahmen zur Stärkung der Systemsicherheit aufzeigen… | 3 | Anwenden | aufzeigen |
| C1G  | Ich kann Massnahmen implementieren und in einer bestehenden Dokumentation… | 3 | Anwenden | implementieren, ergänzen |
| C1F  | Ich kann Massnahmen fachgerecht auf das jeweilige System konfigurieren… | 3 | Anwenden | konfigurieren, dokumentieren |
| C1E  | Ich kann selbständig die Konfiguration der Implementation konzipieren… | 6 | Erschaffen | konzipieren, umsetzen, dokumentieren |
| D1G  | Ich kann ein HIDS in Betrieb nehmen… | 3 | Anwenden | in Betrieb nehmen |
| D1F  | Ich kann ein geeignetes HIDS auswählen und konfigurieren… | 5 | Bewerten | auswählen, konfigurieren |
| D1E  | Ich kann ein HIDS in Betrieb nehmen, dessen Grenzen beurteilen… | 5 | Bewerten | in Betrieb nehmen, beurteilen, konfigurieren |
| E1G  | Ich kann ein HIDS nach Vorgabe an ein Monitoring-System anbinden… | 3 | Anwenden | anbinden |
| E1F  | Ich kann System- und Tool-Meldungen selbständig anbinden… | 3 | Anwenden | anbinden |
| E1E  | Ich kann den Prozess von System- und Tool-Meldungen aufzeigen… | 3 | Anwenden | aufzeigen, erklären |

---

## Änderungsprotokoll V2

| Datum | Zelle / Bereich | Änderung | Regel |
| --- | --- | --- | --- |
| 2026-03-26 | Header | `Kompetenzband:` zu `Kompetenzband` korrigiert (Doppelpunkt entfernt) | Regel 5: Tabellenformat |
| 2026-03-26 | Separator | Gesamte Separator-Zeile normalisiert; dritte Spalte von `----------` zu `:---` korrigiert | Regel 6: Tabellen-Separator |
| 2026-03-26 | Alle Kompetenzbänder | Buchstaben-Präfix hinzugefügt (A - Angriffsmöglichkeiten erkennen, B - Massnahmen ausarbeiten, etc.) | Regel 9: Buchstaben-Präfix |
| 2026-03-26 | A1G | "Netzwerkschema" zu "des Netzwerkschemas" korrigiert (Grammatik) | Regel 7: Schweizer Hochdeutsch |
| 2026-03-26 | A1E | "und Netzwerkschema" zu "und einem Netzwerkschema" korrigiert (Grammatik) | Regel 7: Schweizer Hochdeutsch |
| 2026-03-26 | B1G | "oberflächlich" entfernt (vager Begriff) | Regel 8: Keine vagen Begriffe |
| 2026-03-26 | B1E | "vertieftere" zu "vertiefte" korrigiert; "benötigen" zu "erfordern" | Regel 7: Schweizer Hochdeutsch |
| 2026-03-26 | C1E | Zwei Sätze zu einem eigenständigen Satz zusammengeführt | Regel 2: Eigenständigkeit |
| 2026-03-26 | D1F | "ein bestimmte" zu "eine bestimmte" korrigiert (Grammatik) | Regel 7: Schweizer Hochdeutsch |
| 2026-03-26 | D1E | Satzabhängigkeit aufgelöst; zu einem eigenständigen, kompakten Deskriptor zusammengeführt | Regel 2: Eigenständigkeit |
| 2026-03-26 | Alle Zellen | Abschliessende Punkte entfernt | Regel 10: Keine Punkte am Ende |
| 2026-04-02 | A1E | "erklären" (Bloom L2) ersetzt durch "analysieren und deren mögliche Auswirkungen beurteilen" (Bloom L5) | Bloom-Regel: E-Zelle muss ≥ F-Zelle (A1F = Bloom L3); A1E war L2 < L3 |
| 2026-04-02 | B1F | "fachgerecht erklären" (Bloom L2) ersetzt durch "fachgerecht konfigurieren und deren Wirkung erläutern" (Bloom L3) | Bloom-Regel: F-Zelle muss ≥ G-Zelle (B1G = Bloom L3); B1F war L2 < L3 |
| 2026-04-02 | Alle Zellen | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neue Anforderung: Bloom-Analyse pro Zelle |
| 2026-04-02 | C1E | Bloom-Stufe korrigiert: L5 → L6 (Erschaffen), da "konzipieren" Bloom-Stufe 6 entspricht | Bloom-Analyse-Korrektur |
