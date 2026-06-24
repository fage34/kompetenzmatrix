---
title: M323 Funktional Programmieren
modul: m323
cluster: cluster-api
date: '2025-07-02T10:05:03Z'
draft: false
kompetenzbaender:
- id: A
  titel: Unterschiede zwischen funktionaler Programmierung und anderen Programmierparadigmen aufzeigen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann die Eigenschaften von Funktionen beschreiben (z.B. pure function) und den Unterschied zu anderen Programmierstrukturen erläutern (z.B. zu Prozedur)
    fortgeschritten: Ich kann das Konzept von immutable values erläutern und dazu Beispiele anwenden sowie dieses Konzept funktionaler Programmierung im Unterschied zu anderen Programmiersprachen erklären (z.B. im Vergleich zu referenzierten Objekten)
    erweitert: Ich kann aufzeigen, wie Probleme in den verschiedenen Konzepten (OO, prozedural und funktional) gelöst werden, und diese miteinander vergleichen
- id: B
  titel: Anforderungen und Design der deklarativen Programmierung beschreiben
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann den Unterschied zwischen imperativer und deklarativer Programmierung erklären und die Elemente des Functional Design benennen (z.B. immutable data types, constructors, composable operators)
    fortgeschritten: Ich kann deklarative Anforderungen formulieren und für eine Problemstellung ein Functional Design entwerfen
    erweitert: Ich kann Anforderungen und Design einer imperativen Lösung in eine deklarative Lösung transferieren und die Vor- und Nachteile beider Ansätze begründet bewerten
- id: C
  titel: Funktionale Programmierung umsetzen
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann einen Algorithmus erklären
    fortgeschritten: Ich kann Algorithmen in funktionale Teilstücke aufteilen
    erweitert: Ich kann Funktionen in zusammenhängende Algorithmen implementieren und deren Struktur auf Korrektheit und Lesbarkeit analysieren
  - nr: 2
    hz: ''
    grundlagen: Ich kann Funktionen als Objekte behandeln (in Variablen speichern, weitergeben) und die grundlegenden Higher-Order Functions (Map, Filter, Reduce) einzeln auf Listen anwenden
    fortgeschritten: Ich kann Funktionen als Argumente einsetzen, Lambda-Ausdrücke schreiben und Map, Filter sowie Reduce kombiniert verwenden, um komplexere Datentransformationen durchzuführen
    erweitert: Ich kann Higher-Order Functions, Lambda-Ausdrücke und Funktionskomposition einsetzen, um komplexe Datenverarbeitungsaufgaben zu lösen und den Programmfluss zu steuern (z.B. Aggregation, Sortierung nach benutzerdefinierten Kriterien)
- id: D
  titel: Refactoring und bestehenden Code optimieren
  kompetenzen:
  - nr: 1
    hz: 3, 4
    grundlagen: Ich kann Refactoring-Techniken sowie Massnahmen zur Leistungsverbesserung aufzählen und deren Zweck erklären
    fortgeschritten: Ich kann Refactoring-Techniken anwenden, um Code lesbarer zu machen, und vorgegebene Massnahmen zur Leistungsverbesserung umsetzen
    erweitert: Ich kann die Auswirkungen des Refactorings einschätzen, unerwünschte Nebeneffekte vermeiden und geeignete Algorithmen oder Datenstrukturen auswählen, um die Leistung zu verbessern
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G | Ich kann die Eigenschaften von Funktionen beschreiben… | 2 | Verstehen | beschreiben, erläutern |
| A1F | Ich kann das Konzept von immutable values erläutern… erklären… | 2 | Verstehen | erläutern, erklären, anwenden |
| A1E | Ich kann aufzeigen, wie Probleme in den verschiedenen Konzepten… | 4 | Analysieren | aufzeigen, vergleichen |
| B1G | Ich kann den Unterschied zwischen imperativer und deklarativer Programmierung… | 2 | Verstehen | erklären, benennen |
| B1F | Ich kann deklarative Anforderungen formulieren und… entwerfen… | 6 | Erschaffen | formulieren, entwerfen |
| B1E | Ich kann Anforderungen und Design einer imperativen Lösung… transferieren… bewerten… | 5 | Bewerten | transferieren, begründet bewerten |
| C1G | Ich kann einen Algorithmus erklären… | 2 | Verstehen | erklären |
| C1F | Ich kann Algorithmen in funktionale Teilstücke aufteilen… | 4 | Analysieren | aufteilen |
| C1E | Ich kann Funktionen in zusammenhängende Algorithmen implementieren… analysieren… | 4 | Analysieren | implementieren, analysieren |
| C2G | Ich kann Funktionen als Objekte behandeln… anwenden… | 3 | Anwenden | behandeln, anwenden |
| C2F | Ich kann Funktionen als Argumente einsetzen… verwenden… | 3 | Anwenden | einsetzen, schreiben, verwenden |
| C2E | Ich kann Higher-Order Functions, Lambda-Ausdrücke… einsetzen… lösen… | 3 | Anwenden | einsetzen, lösen, steuern |
| D1G | Ich kann Refactoring-Techniken… aufzählen und… erklären… | 1 | Erinnern | aufzählen, erklären |
| D1F | Ich kann Refactoring-Techniken anwenden, um Code lesbarer zu machen… | 3 | Anwenden | anwenden, umsetzen |
| D1E | Ich kann die Auswirkungen des Refactorings einschätzen… auswählen… | 5 | Bewerten | einschätzen, auswählen |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| B1+B2 → B1 | Zwei Zeilen zu einer zusammengeführt: imperative/deklarative Anforderungen und Functional Design vereint | Beide Zeilen adressierten dasselbe Thema (deklarative Programmierung), gleiche HZ 1 |
| C2+C3 → C2 | Higher-order functions und Lambda-Ausdrücke in eine Zeile zusammengeführt | Lambda-Ausdrücke sind die primäre Syntax für Funktionen als Objekte — thematisch untrennbar |
| D1+D2 → D1 | Refactoring-Techniken und Leistungsverbesserung in eine Zeile zusammengeführt | Beide Zeilen behandeln dasselbe übergeordnete Ziel: bestehenden Code verbessern |
| B - Bandname | "Anforderungen und Design beschreiben" → "Anforderungen und Design der deklarativen Programmierung beschreiben" | Präzisierung nach Zusammenführung |
| C4 → C3 | Bisherige Zeile C4 (Map/Filter/Reduce) umbenannt zu C3 nach Wegfall der alten C3 | Fortlaufende Nummerierung |
| C2+C3 → C2 | Higher-Order Functions, Lambda-Ausdrücke und Map/Filter/Reduce in eine Zeile zusammengeführt | Map/Filter/Reduce sind die bekanntesten konkreten Higher-Order Functions — thematisch untrennbar |
| B1E | "in eine deklarative Lösung transferieren" → "…transferieren und die Vor- und Nachteile beider Ansätze begründet bewerten" ergänzt | Bloom-Regel 2: B1F ist Stufe 6 (Erschaffen), B1E muss ≥ Stufe 6 sein; Stufe 5 als nächstmögliche Stufe mit starkem Bewertungscharakter gewählt |
| C1E | "Funktionen in zusammenhängende Algorithmen implementieren" → "…implementieren und deren Struktur auf Korrektheit und Lesbarkeit analysieren" ergänzt | Bloom-Regel 2: C1F ist Stufe 4 (Analysieren), C1E muss ≥ Stufe 4 sein |
| Bloom-Tabelle | Neu hinzugefügt | Bloom-Taxonomie-Analyse für alle G/F/E-Zellen ergänzt |
