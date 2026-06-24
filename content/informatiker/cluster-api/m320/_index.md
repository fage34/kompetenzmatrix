---
title: M320 Objektorientiert Programmieren
modul: m320
cluster: cluster-api
date: '2025-07-02T10:05:07Z'
draft: false
kompetenzbaender:
- id: A
  titel: Objektorientiertes Design erstellen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann aus einer einfachen Situationsbeschreibung mögliche Klassenkandidaten, Attribute und Methoden ableiten
    fortgeschritten: Ich kann unter Berücksichtigung von Delegation mögliche Klassenkandidaten, Attribute und Methoden aus einer Situationsbeschreibung ermitteln und abbilden
    erweitert: Ich kann komplexere Situationsbeschreibungen analysieren und Klassenkandidaten, Attribute und Methoden in einer Vererbungshierarchie abbilden
- id: B
  titel: Objektorientiert modellieren
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann den Aufbau einer Applikation anhand vorhandener Unterlagen interpretieren und erläutern (z.B. UML-Diagramme)
    fortgeschritten: Ich kann den Aufbau einer Software modellieren (z.B. Klassen-, Aktivitäten- und Sequenzdiagramm)
    erweitert: Ich kann das Modell einer Software analysieren, kritische Punkte erkennen und Korrekturen vorschlagen (z.B. statische und dynamische Aspekte, Vererbung, Assoziationen)
- id: C
  titel: Objektorientiert implementieren
  kompetenzen:
  - nr: 1
    hz: 1,2,3
    grundlagen: Ich kann Klassen unter Verwendung von Konstruktoren und Methoden definieren und Objekte instanziieren
    fortgeschritten: Ich kann ein- und zweiseitige Beziehungen gemäss dem statischen Entwurf implementieren
    erweitert: Ich kann Interaktionen zwischen Objekten unter Berücksichtigung des dynamischen Entwurfs umsetzen (z.B. Delegation)
- id: D
  titel: Objektorientiert mit Vererbung implementieren
  kompetenzen:
  - nr: 1
    hz: 1,2,3
    grundlagen: Ich kann Klassen und deren Super-Klassen implementieren und deren Objekte instanziieren
    fortgeschritten: Ich kann Methoden in den Sub-Klassen ergänzen oder überschreiben, um die Fähigkeiten der Klasse zu erweitern oder anzupassen
    erweitert: Ich kann eine Vererbungshierarchie entwerfen und dabei gezielt entscheiden, welche Attribute und Methoden in der Super-Klasse und welche in den Sub-Klassen angesiedelt werden
  - nr: 2
    hz: 1,2,3
    grundlagen: Ich kann eigene Klassen unter Nutzung von Interfaces und abstrakten Klassen aus Bibliotheken implementieren
    fortgeschritten: Ich kann eigene abstrakte Klassen oder Interfaces gemäss Entwurf implementieren
    erweitert: Ich kann Lösungsansätze für komplexe Problemstellungen durch Anwendung der Polymorphie umsetzen
- id: E
  titel: Qualitätssicherung
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann Code-Konventionen anwenden und den Quellcode entsprechend implementieren
    fortgeschritten: Ich kann Code in einer Codereview-Sitzung auf dessen Qualität überprüfen
    erweitert: Ich kann die Qualität von Code anhand von automatisierten Tests und Review-Ergebnissen beurteilen und begründete Verbesserungen vorschlagen
  - nr: 2
    hz: '2'
    grundlagen: Ich kann den Zweck eines Software-Dokumentationswerkzeugs erklären und dieses einsetzen (z.B. Tags anwenden, Dokumentation generieren)
    fortgeschritten: Ich kann Software mit Hilfe eines Dokumentationswerkzeugs dokumentieren (z.B. Tags anwenden, Dokumentation generieren)
    erweitert: Ich kann die Kommentare in einer Software hinterfragen und Verbesserungen vorschlagen (z.B. Kommentare durch bessere Struktur vermeiden, Clean-Code-Regeln anwenden)
---

Die Handlungsziele erwähnen Exceptions und Exceptionhandling nicht, die Autoren der Kompetenzmatrix erachten dieses Thema allerdings als wichtig.

| Kompetenzband | HZ | Grundlagen | Fortgeschritten | Erweitert |
| --- | --- | :--- | --- | --- |
| X - Exceptionhandling | nicht vorhanden | X1G: Ich kann bei der Benutzung von Methoden Exceptions abfangen und behandeln | X1F: Ich kann in meinen Implementierungen im Fehlerfall geeignete Exceptions werfen | X1E: Ich kann für eine Applikation die Fehlerbehandlung einheitlich umsetzen |

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G | Ich kann aus einer einfachen Situationsbeschreibung… ableiten… | 3 | Anwenden | ableiten |
| A1F | Ich kann unter Berücksichtigung von Delegation… ermitteln… | 3 | Anwenden | ermitteln, abbilden |
| A1E | Ich kann komplexere Situationsbeschreibungen analysieren… | 4 | Analysieren | analysieren, abbilden |
| B1G | Ich kann den Aufbau einer Applikation anhand… interpretieren… | 2 | Verstehen | interpretieren, erläutern |
| B1F | Ich kann den Aufbau einer Software modellieren… | 3 | Anwenden | modellieren |
| B1E | Ich kann das Modell einer Software analysieren, kritische Punkte… | 4 | Analysieren | analysieren, erkennen, vorschlagen |
| C1G | Ich kann Klassen unter Verwendung von Konstruktoren… definieren… | 3 | Anwenden | definieren, instanziieren |
| C1F | Ich kann ein- und zweiseitige Beziehungen… implementieren… | 3 | Anwenden | implementieren |
| C1E | Ich kann Interaktionen zwischen Objekten… umsetzen… | 3 | Anwenden | umsetzen |
| D1G | Ich kann Klassen und deren Super-Klassen implementieren… | 3 | Anwenden | implementieren, instanziieren |
| D1F | Ich kann Methoden in den Sub-Klassen ergänzen oder überschreiben… | 3 | Anwenden | ergänzen, überschreiben |
| D1E | Ich kann eine Vererbungshierarchie entwerfen und… entscheiden… | 5 | Bewerten | entwerfen, entscheiden |
| D2G | Ich kann eigene Klassen unter Nutzung von Interfaces… implementieren… | 3 | Anwenden | implementieren |
| D2F | Ich kann eigene abstrakte Klassen oder Interfaces… implementieren… | 3 | Anwenden | implementieren |
| D2E | Ich kann Lösungsansätze für komplexe Problemstellungen… umsetzen… | 3 | Anwenden | umsetzen |
| E1G | Ich kann Code-Konventionen anwenden und… implementieren… | 3 | Anwenden | anwenden, implementieren |
| E1F | Ich kann Code in einer Codereview-Sitzung… überprüfen… | 5 | Bewerten | überprüfen (validieren) |
| E1E | Ich kann die Qualität von Code anhand… beurteilen… | 5 | Bewerten | beurteilen, vorschlagen |
| E2G | Ich kann den Zweck eines Software-Dokumentationswerkzeugs erklären… | 2 | Verstehen | erklären, einsetzen |
| E2F | Ich kann Software mit Hilfe eines Dokumentationswerkzeugs dokumentieren… | 3 | Anwenden | dokumentieren |
| E2E | Ich kann die Kommentare in einer Software hinterfragen… | 5 | Bewerten | hinterfragen, vorschlagen |
| X1G | Ich kann bei der Benutzung von Methoden Exceptions abfangen… | 3 | Anwenden | abfangen, behandeln |
| X1F | Ich kann in meinen Implementierungen im Fehlerfall… werfen… | 3 | Anwenden | werfen |
| X1E | Ich kann für eine Applikation die Fehlerbehandlung… umsetzen… | 3 | Anwenden | umsetzen |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| D1E | Fehlende Erweitert-Stufe ergänzt | Vollständige Progression G/F/E |
| Alle Bänder | Buchstaben-Präfix ergänzt (A - ..., B - ..., etc.) | Vorgabe |
| Header, Separator (beide Tabellen) | Normalisiert auf Vorgabeformat | Vorgabe Tabellenformat |
| Alle Zellen | Trailing Periods entfernt | Keine abschliessenden Punkte |
| A1G | "schliessen" → "ableiten" | Präzisere Formulierung |
| A1F | "eruieren" → "ermitteln" | Verständlichere Formulierung |
| B1G | "erkläutern" → "erläutern"; "auf Grund" → "anhand" | Tippfehler; idiomatischer Ausdruck |
| C1E | "Delegation" als Beispiel in Klammern verschoben | Klarere Struktur |
| D2G | Produktnamen "AbstractList, Comparator, Comparable" entfernt | Produktneutralität |
| D2E | Vages "effizient" entfernt | Keine vagen Begriffe |
| E1G | "Ich kenne" → "Ich kann ... anwenden" | "Ich kann"-Format |
| E1E | Produktname "junit" entfernt | Produktneutralität |
| E2G | "wie man es einsetzt" → "Ich kann ... erklären und dieses einsetzen"; "JavaDoc" entfernt | "Ich kann"-Format; Produktneutralität |
| E2F | Produktname "JavaDoc" entfernt; `<br/>` entfernt | Produktneutralität; keine HTML-Tags |
| E2E | "Vorschläge zur Verbesserung machen" → "Verbesserungen vorschlagen" | Direktere Aktivformulierung |
| X-Tabelle | Header/Separator normalisiert; Buchstaben-Präfix ergänzt; Trailing Periods entfernt | Vorgabe |
| E1E | "Code mit vorgegebenen, automatisierten Tests überprüfen" → "die Qualität von Code anhand von automatisierten Tests und Review-Ergebnissen beurteilen und begründete Verbesserungen vorschlagen" | Bloom-Regel 2: E1F ist Stufe 5 (Bewerten), E1E muss ≥ Stufe 5 sein |
| Bloom-Tabelle | Neu hinzugefügt | Bloom-Taxonomie-Analyse für alle G/F/E-Zellen beider Tabellen ergänzt |
