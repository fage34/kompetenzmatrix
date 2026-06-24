---
title: Umsetzungsvorschlag
weight: 10
draft: false
---

# Umsetzungsvorschlag Modul 323


## Lektionenplan Vorschlag

| Anzahl Lektionen | Themen                                                                                                                                  | Kompetenzen   | Tools                    |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------ |
| 2                | **Einführung** <br> Aufgaben aus imperativer Praxis, dann die Beispiele funktional aufzeigen                                       | A, C           | Visual Studio Code o.ä. |
| 2                |  Was sind pure Functions, wie werden Daten gehandabt (immutable data), allgem. Begriffe funktionaler Programmierung | A, C           |                          |
| 2                | Entscheidungen und Loops in funktionaler Programmierung                                                           | A, C           |                          |
| 2                | Algorithmen in funktionaler Programmierung (Rekursion), filer-map-reduce                                                                | A, C           |                          |
| 2                | Praxisnahe Beispiel mit Algorithmen durch funktionale Programmierung umsetzen <br> Vor und Nachteile funktionaler Programmierung                                                           | A, C           |                          |
| 2                | Prüfung 1                                                                                                                      | A, C       |                          |
| 2                | **Anforderungen und Design** <br> Wie beschreibe ich Probleme so dass sie deklarativ umgesetzt werden können – Übungen Text transfer in Code                           | B, C           |                          |
| 2                | Anforderungen definieren, damit diese als Funktionen umgesetzt werden können                                                           | B, C           |                          |
| 2                | Entwurfsmuster und funktionale Programmierung                                                                                           | B, C           |                          |
| 2                | Entwurfsmuster und funktionale Programmierung                                                                                           | B, C           |                          |
| 2                | Prüfung 2                                                                                                |  |                          |
| 2                | **Refactoring** <br>Bestehender Code verbessern (u.a. evtl. Code von MitschülerInnen verbessern etc.)                                        | D           |                          |
| 2                | Parallele prozesse in funktionaler Programmierung                                                                                       | C           |                          |
| 2                | Diverse Übungen in funktionaler Programmierung                                                                                       | C           |                          |
| 2                | **Projekt** <br> Kombination imperativ und funktional (oder nur funktional)                                                              |               |                          |
| 2                | ""                                                              |               |                          |
| 2                | ""                                                              |               |                          |
| 2                | Feedback Projekt (evtl. mit Refactoring)                                              |            |                          |
| 4                | Reserve                                                                                                                                 |               |                          |
<br>
<hr>
<br>

## Gedanken und Themen für das Modul

### Programmierparadigma funktionales Programmieren vs. imperatives Programmieren

* Unterschiede mittels Beispiele und Aufgaben aufzeigen
* Bsp. Fibonacci Reihe imperativ und funktional umsetzen
* OO-Bsp. in Funktionales Programm umwandeln

### Grundlagen der funktionalen Programmierung

* Was sind Funktionen (Merkmale von pure functions, können aneinander gereiht werden, etc.)
* Funktionen als Werte (functions as values)
* Wie werden Daten gehandabt (Stichwort: immutable data)
* Wie werden Entscheidungen und Schleifen umgesetzt (oder eben nicht); loops vs rekursion
* Auswirkungen von Funktionen (No side effects)
* Lambda-Ausdrücke als Funktionen
* Error-Handling

### Deklarative Beschreibungen

* Wie erstelle ich Beschreibungen anhand denen ich funktionale Programme ableiten kann?

### Unterschied deklarativ vs. Imperativ (erwähnt in HK 3.2)

* Deklarativ: beschreibt was getan werden muss, nicht wie (!= imperativ)
* Funktionen und Big Data (parallelles Programmieren)

### Algorithmen in funktionalen Programmen

* Rekursion anstatt Schleifen
* Filter-Map-Reduce
* Such-Algorithmen
* Pipeline-basierte Algorithmen

### Entwurfsmuster und funktionales Programmieren

* Builder-Pattern
* Factory Pattern ?

### Refactoring von prozeduralem Code

* Code verbessern durch Anwendung funktionaler Programmierung

### Qualitätsprüfung von funktionalen Programmen

* Qualitätsmerkmale für funktionalen Code
* Prüfung von funktionalen Code (evtl. in Kombination mit Modul 450)
