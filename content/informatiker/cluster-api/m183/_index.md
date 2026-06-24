---
title: M183 Applikationssicherheit implementieren
modul: m183
cluster: cluster-api
date: '2025-07-02T10:04:59Z'
draft: false
kompetenzbaender:
- id: A
  titel: Sicherheitsschwachstellen und Massnahmen verstehen
  kompetenzen:
  - nr: 1
    hz: 1, 2
    grundlagen: Ich kann erklären, was eine Sicherheitsschwachstelle bei einer Applikation ist
    fortgeschritten: Ich kann aktuelle Sicherheitsschwachstellen, deren Ursachen und Folgen erklären (z.B. OWASP Top Ten "description")
    erweitert: Ich kann Informationsquellen zu Sicherheitsschwachstellen in Bezug auf ihre Relevanz beurteilen
  - nr: 2
    hz: 1, 2
    grundlagen: Ich kann erklären, was in Bezug auf eine Sicherheitsschwachstelle unternommen werden muss (z.B. Sicherheitsschwachstelle identifizieren, Gegenmassnahmen definieren und umsetzen, Wirkung überprüfen)
    fortgeschritten: Ich kann Massnahmen gegen aktuelle Sicherheitsschwachstellen erklären (z.B. OWASP Top Ten "how to prevent")
    erweitert: Ich kann praktische Beispiele von Sicherheitsschwachstellen und Gegenmassnahmen vorführen (z.B. Beispiel recherchieren, nachvollziehen, praktisch vorführen, z.B. WebGoat)
- id: B
  titel: Authentisierungsverfahren einsetzen
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann die Funktionsweise von verschiedenen Authentisierungsverfahren erklären
    fortgeschritten: Ich kann Authentisierungsverfahren in einer Applikation umsetzen
    erweitert: Ich kann das für einen Use-Case geeignete Authentisierungsverfahren gegenüberstellen und begründet auswählen
- id: C
  titel: Logging und Monitoring-Mechanismen implementieren
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann die relevanten Informationen für das Monitoring und Logging sammeln
    fortgeschritten: Ich kann gesammelte Informationen für das Monitoring und Logging auswerten und relevante Informationen bestimmen
    erweitert: Ich kann Monitoring- und Logging-Systeme einrichten und die gesammelten Informationen auf Sicherheitsrelevanz analysieren sowie geeignete Massnahmen ableiten
  - nr: 2
    hz: '5'
    grundlagen: Ich kann den Aufbau und Inhalt von Logs und Audit-Trails erkennen und erklären
    fortgeschritten: Ich kann aufgrund des Aufbaus und Inhalts von Logs und Audit-Trails einzelne Massnahmen zur Behebung von möglichen Sicherheitsproblemen vorschlagen
    erweitert: Ich kann Alarmierungskonzepte für Logs und Audit-Trails kritisch beurteilen und begründet geeignete Formen der Alarmierung und Alarmauslösung auswählen
- id: D
  titel: Kryptographie
  kompetenzen:
  - nr: 1
    hz: 2, 3, 4
    grundlagen: Ich kann Kryptographieverfahren wie symmetrische und asymmetrische Verschlüsselungen sowie Hash-Funktionen einer Anwendung zuweisen und einordnen
    fortgeschritten: Ich kann symmetrische und asymmetrische Verschlüsselung sowie Hash-Funktionen in der Applikation zum Schutz sensibler Daten einsetzen
    erweitert: Ich kann in einer Applikation eingesetzte kryptographische Massnahmen auf deren Tauglichkeit beurteilen sowie Verbesserungsvorschläge anbringen und umsetzen
- id: E
  titel: Sicherheitslücken vermeiden und beheben
  kompetenzen:
  - nr: 1
    hz: 1, 3, 4
    grundlagen: Ich kann die Sicherheitsrisiken in der Entwicklung von Anwendungen auflisten und erklären
    fortgeschritten: Ich kann die Sicherheitsrisiken in der Entwicklung von Anwendungen erkennen und bei der Implementierung vermeiden
    erweitert: Ich kann Sicherheitsarchitekturen beim Design von Anwendungen analysieren und begründete Empfehlungen zur Verbesserung ableiten
  - nr: 2
    hz: 1, 3, 4
    grundlagen: Ich kann Massnahmen beschreiben, die Sicherheitslücken in Applikationen beheben
    fortgeschritten: Ich kann Massnahmen umsetzen, die Sicherheitslücken in Applikationen beheben
    erweitert: Ich kann Massnahmen vergleichen und umsetzen, die die Sicherheit von Systemen und Netzwerken optimieren
---

---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G | Ich kann erklären, was eine Sicherheitsschwachstelle… | 2 | Verstehen | erklären |
| A1F | Ich kann aktuelle Sicherheitsschwachstellen, deren Ursachen… | 2 | Verstehen | erklären |
| A1E | Ich kann Informationsquellen zu Sicherheitsschwachstellen… | 5 | Bewerten | beurteilen |
| A2G | Ich kann erklären, was in Bezug auf eine Sicherheitsschwachstelle… | 2 | Verstehen | erklären |
| A2F | Ich kann Massnahmen gegen aktuelle Sicherheitsschwachstellen… | 2 | Verstehen | erklären |
| A2E | Ich kann praktische Beispiele von Sicherheitsschwachstellen… | 3 | Anwenden | vorführen, nachvollziehen |
| B1G | Ich kann die Funktionsweise von verschiedenen Authentisierungsverfahren… | 2 | Verstehen | erklären |
| B1F | Ich kann Authentisierungsverfahren in einer Applikation… | 3 | Anwenden | umsetzen |
| B1E | Ich kann das für einen Use-Case geeignete Authentisierungsverfahren… | 5 | Bewerten | gegenüberstellen, begründet auswählen |
| C1G | Ich kann die relevanten Informationen für das Monitoring… | 3 | Anwenden | sammeln |
| C1F | Ich kann gesammelte Informationen für das Monitoring… auswerten… | 4 | Analysieren | auswerten, bestimmen |
| C1E | Ich kann Monitoring- und Logging-Systeme einrichten… analysieren… | 4 | Analysieren | analysieren, ableiten |
| C2G | Ich kann den Aufbau und Inhalt von Logs und Audit-Trails… | 2 | Verstehen | erkennen, erklären |
| C2F | Ich kann aufgrund des Aufbaus und Inhalts von Logs… vorschlagen… | 5 | Bewerten | vorschlagen |
| C2E | Ich kann Alarmierungskonzepte für Logs und Audit-Trails… beurteilen… | 5 | Bewerten | beurteilen, begründet auswählen |
| D1G | Ich kann Kryptographieverfahren wie symmetrische… zuweisen… | 3 | Anwenden | zuweisen, einordnen |
| D1F | Ich kann symmetrische und asymmetrische Verschlüsselung… einsetzen… | 3 | Anwenden | einsetzen |
| D1E | Ich kann in einer Applikation eingesetzte kryptographische Massnahmen… | 5 | Bewerten | beurteilen |
| E1G | Ich kann die Sicherheitsrisiken in der Entwicklung… auflisten… | 2 | Verstehen | auflisten, erklären |
| E1F | Ich kann die Sicherheitsrisiken in der Entwicklung… erkennen… | 4 | Analysieren | erkennen, vermeiden |
| E1E | Ich kann Sicherheitsarchitekturen beim Design… analysieren… | 4 | Analysieren | analysieren, ableiten |
| E2G | Ich kann Massnahmen beschreiben, die Sicherheitslücken… | 2 | Verstehen | beschreiben |
| E2F | Ich kann Massnahmen umsetzen, die Sicherheitslücken… beheben… | 3 | Anwenden | umsetzen |
| E2E | Ich kann Massnahmen vergleichen und umsetzen, die die Sicherheit… | 4 | Analysieren | vergleichen, umsetzen |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Header | "Kompetenzband:" → "Kompetenzband"; "Grundkompetenz" → "Grundlagen"; "Fortgeschrittene-Kompetenz" → "Fortgeschritten"; "Erweiterte-Kompetenz" → "Erweitert" | Vorgabe Tabellenformat |
| Separator | → `| --- | --- | :--- | --- | --- |` | Vorgabe |
| D1F | "Kann symmetrische..." → "Ich kann symmetrische..." | "Ich kann"-Format |
| D1E | "Kann in einer Applikation..." → "Ich kann in einer Applikation..." | "Ich kann"-Format |
| Band E (HZ-Spalte) | `<p>4, 1, 3</p><p></p>` → "1, 3, 4" | HTML-Tags entfernt, Werte sortiert |
| C2, E2 (HZ-Spalte) | Fehlende HZ-Werte ergänzt | Vollständige Angabe der Handlungsziele |
| Kompetenzband A, B | "Sicherheits-schwachstellen" → "Sicherheitsschwachstellen"; "Authentisierungs-verfahren" → "Authentisierungsverfahren" | Silbentrennungen entfernt |
| Alle Zellen | Trailing Periods entfernt | Keine abschliessenden Punkte |
| A1F, A2F | `<br/>`-Tags entfernt; Klammern integriert | Keine HTML-Tags in Markdown-Tabellen |
| C1F | "gesammelten" → "gesammelte" | Grammatikfehler |
| D1G | "Kryptographie Verfahren wie Symmetrische- und Asymmetrische Verschlüsselungen" → "Kryptographieverfahren wie symmetrische und asymmetrische Verschlüsselungen" | Korrekte Schreibweise |
| Alle Zellen | Inkonsistente Leerzeichen bereinigt | Formatbereinigung |
| C1E | "Monitoring- und Logging-Systeme einrichten, überwachen und Informationen zur Behebung von Sicherheitsproblemen verwenden" → "Monitoring- und Logging-Systeme einrichten und die gesammelten Informationen auf Sicherheitsrelevanz analysieren sowie geeignete Massnahmen ableiten" | Bloom-Regel 2: C1F ist Stufe 4 (Analysieren), C1E muss ≥ Stufe 4 sein |
| C2E | "zu Logs und Audit-Trails situativ verschiedene Formen der Alarmierung und Alarmauslösung umsetzen" → "Alarmierungskonzepte für Logs und Audit-Trails kritisch beurteilen und begründet geeignete Formen der Alarmierung und Alarmauslösung auswählen" | Bloom-Regel 2: C2F ist Stufe 5 (Bewerten), C2E muss ≥ Stufe 5 sein |
| E1E | "Sicherheitsarchitekturen beim Design von Anwendungen berücksichtigen" → "Sicherheitsarchitekturen beim Design von Anwendungen analysieren und begründete Empfehlungen zur Verbesserung ableiten" | Bloom-Regel 2: E1F ist Stufe 4 (Analysieren), E1E muss ≥ Stufe 4 sein |
