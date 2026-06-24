---
title: M450 Applikationen testen
modul: m450
cluster: cluster-api
date: '2025-07-02T10:05:01Z'
draft: false
kompetenzbaender:
- id: A
  titel: Testkonzept erstellen
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann die Komponenten eines Testumfelds identifizieren und erklären (z.B. Test- und Entwicklungsumgebung, Hard- und Softwareanforderungen, Datenquellen, Testwerkzeuge)
    fortgeschritten: Ich kann die Unterschiede und Gemeinsamkeiten verschiedener Umgebungen erklären und deren Eignung für bestimmte Testaktivitäten begründen (z.B. DEV, TEST, INT/STAGE, PROD)
    erweitert: Ich kann die Anforderungen an ein Test- und Produktivumfeld auf Basis der Projektanforderungen ableiten und definieren (z.B. Konfiguration, Überwachung, Fehlerbehebung)
  - nr: 2
    hz: '1'
    grundlagen: Ich kann die Anforderungen einer Software erfassen und mögliche Schritte eines Testkonzeptes aufzählen
    fortgeschritten: Ich kann verschiedene Testarten unterscheiden und erklären, welche für die Anforderungen des Projekts geeignet sind
    erweitert: Ich kann ein Testkonzept zusammenstellen, in dem die für das Projekt relevantesten Testarten begründet ausgewählt werden
- id: B
  titel: Tests definieren
  kompetenzen:
  - nr: 1
    hz: 3, 5, 6
    grundlagen: Ich kann aufgrund der Strategie im Testkonzept geeignete Testmethoden und -werkzeuge nennen und erläutern
    fortgeschritten: Ich kann Testfälle formulieren, um einzelne Funktionen oder Aspekte der Software zu prüfen
    erweitert: Ich kann Testszenarien definieren, die festlegen, wie das System in einer bestimmten Reihenfolge oder Kombination von Funktionen und Prozessen reagieren soll
- id: C
  titel: Tests automatisieren
  kompetenzen:
  - nr: 1
    hz: 5, 6
    grundlagen: Ich kann Kriterien für die Wahl der Testdaten und Mock-Objekte aufzählen und den Begriff Testabdeckung erklären
    fortgeschritten: Ich kann Testfälle programmieren, die positive und negative Fälle, Grenzwerte und Spezialfälle abdecken
    erweitert: Ich kann Testdaten strukturieren, Mock-Objekte und Hilfsmethoden erstellen und Funktionen des Test-Frameworks gezielt einsetzen
  - nr: 2
    hz: 5, 7
    grundlagen: Ich kann den Unterschied zwischen Unit-Testing und Integration-Testing erklären und zwischen manuellen und automatisierten Tests unterscheiden
    fortgeschritten: Ich kann Unit-Testing und Integration-Testing im Rahmen von Test Driven Development (TDD) anwenden (z.B. mit einem Testing-Framework)
    erweitert: Ich kann eine CI/CD-Pipeline so konfigurieren, dass Unit- und Integration-Tests automatisiert durchgeführt werden und die Resultate den Deployment-Prozess steuern
  - nr: 3
    hz: 5, 8
    grundlagen: Ich kann grundlegende Tests von Schnittstellen durchführen
    fortgeschritten: Ich kann umfangreichere Tests von Schnittstellen mit verschiedenen Szenarien durchführen
    erweitert: Ich kann komplexe Tests von Schnittstellen planen, durchführen und die Ergebnisse dokumentieren
- id: D
  titel: Review durchführen
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann Clean-Code-Prinzipien erklären und anhand von Code-Beispielen aufzeigen (z.B. Single Responsibility Principle, DRY)
    fortgeschritten: Ich kann in der Rolle als Gutachter:in an einem Code-Review teilnehmen und Mängel festhalten
    erweitert: Ich kann Verbesserungen und Optimierungen auf Basis der im Review aufgezeigten Mängel vorschlagen
  - nr: 2
    hz: '4'
    grundlagen: Ich kann grundlegende Testergebnisse interpretieren
    fortgeschritten: Ich kann Zusammenhänge zwischen Testergebnissen erkennen
    erweitert: Ich kann fundierte Schlussfolgerungen aus Testergebnissen ziehen und Handlungsempfehlungen ableiten
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G | Ich kann die Komponenten eines Testumfelds identifizieren und erklären… | 2 | Verstehen | identifizieren, erklären |
| A1F | Ich kann die Unterschiede und Gemeinsamkeiten… erklären… begründen… | 5 | Bewerten | erklären, begründen |
| A1E | Ich kann die Anforderungen an ein Test- und Produktivumfeld… ableiten… | 5 | Bewerten | ableiten, definieren |
| A2G | Ich kann die Anforderungen einer Software erfassen und… aufzählen… | 2 | Verstehen | erfassen, aufzählen |
| A2F | Ich kann verschiedene Testarten unterscheiden und erklären… | 2 | Verstehen | unterscheiden, erklären |
| A2E | Ich kann ein Testkonzept zusammenstellen… begründet ausgewählt werden… | 5 | Bewerten | zusammenstellen, begründet auswählen |
| B1G | Ich kann aufgrund der Strategie… Testmethoden und -werkzeuge nennen… | 2 | Verstehen | nennen, erläutern |
| B1F | Ich kann Testfälle formulieren, um einzelne Funktionen… zu prüfen… | 3 | Anwenden | formulieren |
| B1E | Ich kann Testszenarien definieren, die festlegen… | 3 | Anwenden | definieren |
| C1G | Ich kann Kriterien für die Wahl der Testdaten… aufzählen… erklären… | 2 | Verstehen | aufzählen, erklären |
| C1F | Ich kann Testfälle programmieren, die positive und negative Fälle… | 3 | Anwenden | programmieren |
| C1E | Ich kann Testdaten strukturieren, Mock-Objekte… erstellen… einsetzen… | 3 | Anwenden | strukturieren, erstellen, einsetzen |
| C2G | Ich kann den Unterschied zwischen Unit-Testing und Integration-Testing… | 2 | Verstehen | erklären, unterscheiden |
| C2F | Ich kann Unit-Testing und Integration-Testing… anwenden… | 3 | Anwenden | anwenden |
| C2E | Ich kann eine CI/CD-Pipeline so konfigurieren… | 3 | Anwenden | konfigurieren |
| C3G | Ich kann grundlegende Tests von Schnittstellen durchführen… | 3 | Anwenden | durchführen |
| C3F | Ich kann umfangreichere Tests von Schnittstellen… durchführen… | 3 | Anwenden | durchführen |
| C3E | Ich kann komplexe Tests von Schnittstellen planen… dokumentieren… | 3 | Anwenden | planen, durchführen, dokumentieren |
| D1G | Ich kann Clean-Code-Prinzipien erklären und anhand von Code-Beispielen… | 2 | Verstehen | erklären, aufzeigen |
| D1F | Ich kann in der Rolle als Gutachter:in an einem Code-Review teilnehmen… | 3 | Anwenden | teilnehmen, festhalten |
| D1E | Ich kann Verbesserungen und Optimierungen auf Basis… vorschlagen… | 5 | Bewerten | vorschlagen |
| D2G | Ich kann grundlegende Testergebnisse interpretieren… | 2 | Verstehen | interpretieren |
| D2F | Ich kann Zusammenhänge zwischen Testergebnissen erkennen… | 4 | Analysieren | erkennen |
| D2E | Ich kann fundierte Schlussfolgerungen aus Testergebnissen ziehen… | 5 | Bewerten | ziehen, ableiten |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Alle Zellen | "Kann" → "Ich kann" | Durchgehend "Ich kann"-Format |
| Alle Zellen | `</br>` und `<br/>` Tags entfernt | Einheitliches Format |
| Alle Kompetenzbänder | Buchstaben-Präfix ergänzt (A - ..., B - ..., etc.) | Standardkonformes Format |
| Tabellenheader | Separator normalisiert | Standardkonformes Format |
| Alle Zellen | Trailing-Punkte entfernt | Konsistenz |
| A1G | "beschreiben" → "erklären" | Aktiver, beobachtbarer Deskriptor |
| A1F | "aufzeigen" → "erklären und deren Eignung für bestimmte Testaktivitäten begründen" | Schliesst die Lücke zwischen Wissen und Anwenden |
| A1E | "Anforderungen definieren" ergänzt mit "auf Basis der Projektanforderungen ableiten" | Inhaltliche Brücke: G=erklären → F=begründen → E=ableiten und definieren |
| A2G | "verstehen" → "erfassen" | Beobachtbarer Deskriptor |
| B1E | "legt damit fest" (Mischkonstruktion) → "die festlegen" | Eigenständiger, in sich geschlossener Satz |
| C1E | "erstellt Mock-Objects, Hilfsmethoden und verwendet Features" → "Ich kann ... erstellen und ... einsetzen" | Mischkonstruktion aufgelöst |
| C1G, C1E | "Mock-Objects" → "Mock-Objekte" | Deutsches Wort |
| C2G | "unterscheidet" → "unterscheiden" | Mischkonstruktion aufgelöst |
| C3G, C3F, C3E | Schnittstellen-testen-Band in Band C integriert; C3F/C3E konkretisiert | War separates Band, gehört thematisch zu Tests automatisieren |
| D1F | "eines Gutachters" → "als Gutachter:in" | Genderneutrale Sprache |
| D2E | "Handlungsempfehlungen ableiten" ergänzt | Konkretere Erweitert-Stufe |
| B1G | "geeignete Testmethoden und -werkzeuge vorschlagen" → "nennen und erläutern" | Bloom-Regel 1: G-Zelle enthielt "vorschlagen" (Stufe 5); korrigiert auf Stufe 2 (Verstehen) |
| Bloom-Tabelle | Neu hinzugefügt | Bloom-Taxonomie-Analyse für alle G/F/E-Zellen ergänzt |
