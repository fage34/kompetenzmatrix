---
title: M319 Applikationen entwerfen und implementieren
modul: m319
cluster: cluster-api
date: '2025-07-02T10:05:10Z'
draft: false
kompetenzbaender:
- id: A
  titel: Probleme erfassen und Lösungsansätze entwickeln
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann eine vorgegebene Aufgabenstellung lesen, die wesentlichen Anforderungen beschreiben und die Lösung in logische Schritte gliedern
    fortgeschritten: Ich kann eine grob beschriebene Aufgabenstellung durch Rückfragen an Stakeholder detaillieren und in logische Schritte gliedern
    erweitert: Ich kann ein Problem unter Berücksichtigung unterschiedlicher Stakeholder-Anforderungen in eine Aufgabenstellung überführen und einen begründeten Lösungsansatz ableiten
- id: B
  titel: Anforderungen visuell darstellen
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann einen grafisch dargestellten Ablauf nachvollziehen (z.B. Activity-Diagramm, Sequenz-Diagramm)
    fortgeschritten: Ich kann einen vorgegebenen Programmablauf grafisch darstellen (z.B. Activity-Diagramm, Sequenz-Diagramm)
    erweitert: Ich kann einen textuell beschriebenen Ablauf in einen Programmablauf überführen und grafisch darstellen (z.B. Activity-Diagramm, Sequenz-Diagramm)
- id: C
  titel: Daten, Datentypen und Variablen ableiten und einsetzen
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann die Unterschiede zwischen den elementaren Datentypen identifizieren und erklären, für welche Art von Daten welcher Datentyp geeignet ist
    fortgeschritten: Ich kann den passenden elementaren Datentyp für eine Variable aufgrund der Aufgabenstellung ermitteln, diesen deklarieren, initialisieren und Zuweisungen vornehmen
    erweitert: Ich kann den Zweck von Containern erläutern und diese deklarieren, initialisieren und Zuweisungen vornehmen (z.B. Array, List)
  - nr: 2
    hz: '3'
    grundlagen: Ich kann eine einfache Modellklasse bestehend aus mehreren Attributen definieren, deklarieren und initialisieren
    fortgeschritten: Ich kann das Prinzip der Kapselung unter Verwendung von Zugriffsmodifikatoren, Gettern, Settern und Konstruktoren umsetzen
    erweitert: Ich kann Klassen durch Funktionen ergänzen und diese innerhalb und ausserhalb der Klasse verwenden
- id: D
  titel: Programm ausführen und überprüfen
  kompetenzen:
  - nr: 1
    hz: 4,6
    grundlagen: Ich kann ein von mir erstelltes Programm in einer Entwicklungsumgebung ausführen
    fortgeschritten: Ich kann die vom Compiler/Interpreter angezeigten Fehler- und Warnmeldungen interpretieren und deren Ursachen beheben
    erweitert: Ich kann einen Debugger zur Programmausführung anwenden und diesen gezielt zur Fehleranalyse einsetzen (z.B. Breakpoints setzen, Variablenleiste nutzen)
- id: E
  titel: Applikation implementieren
  kompetenzen:
  - nr: 1
    hz: 2,3,4
    grundlagen: Ich kann den Aufbau, die Syntax und die Kontrollstrukturen eines einfachen Programms erklären und ein solches umsetzen
    fortgeschritten: Ich kann einen detailliert vorgegebenen Ablauf mit einer Programmiersprache umsetzen
    erweitert: Ich kann einen grob beschriebenen Ablauf detaillieren und mit einer Programmiersprache umsetzen
  - nr: 2
    hz: 2,3,4
    grundlagen: Ich kann den Aufbau und den Aufruf einer Funktion erklären (z.B. Parameter, lokale Variablen, Rückgabewerte)
    fortgeschritten: Ich kann eine Funktion korrekt deklarieren, implementieren und aufrufen (z.B. mit Parametern, lokalen Variablen, Rückgabewerten)
    erweitert: Ich kann Programmteile identifizieren, die sinnvollerweise in eine eigene Funktion ausgelagert werden, und diese entsprechend refaktorisieren
- id: F
  titel: Konventionen einhalten
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann mein Programm mit ein- und mehrzeiligen Kommentaren ergänzen
    fortgeschritten: Ich kann Kommentare mit gängigen Annotationen versehen und formatieren (z.B. FIXME, TODO)
    erweitert: Ich kann Konventionen für sauberen Sourcecode anwenden (z.B. Namenskonventionen, Coding-Guidelines)
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G | Ich kann eine vorgegebene Aufgabenstellung lesen… | 3 | Anwenden | beschreiben, gliedern |
| A1F | Ich kann eine grob beschriebene Aufgabenstellung detaillieren… | 3 | Anwenden | detaillieren, gliedern |
| A1E | Ich kann ein Problem unter Berücksichtigung… Lösungsansatz ableiten | 5 | Bewerten | überführen, ableiten *(begründeten)* |
| B1G | Ich kann einen grafisch dargestellten Ablauf nachvollziehen… | 2 | Verstehen | nachvollziehen |
| B1F | Ich kann einen vorgegebenen Programmablauf grafisch darstellen… | 3 | Anwenden | darstellen |
| B1E | Ich kann einen textuell beschriebenen Ablauf… grafisch darstellen | 3 | Anwenden | überführen, darstellen |
| C1G | Ich kann die Unterschiede zwischen den elementaren Datentypen… | 2 | Verstehen | identifizieren, erklären |
| C1F | Ich kann den passenden elementaren Datentyp… ermitteln… | 3 | Anwenden | ermitteln, deklarieren, initialisieren |
| C1E | Ich kann den Zweck von Containern erläutern… | 3 | Anwenden | erläutern, deklarieren, initialisieren |
| C2G | Ich kann eine einfache Modellklasse… definieren… | 3 | Anwenden | definieren, deklarieren, initialisieren |
| C2F | Ich kann das Prinzip der Kapselung… umsetzen | 3 | Anwenden | umsetzen |
| C2E | Ich kann Klassen durch Funktionen ergänzen… verwenden | 3 | Anwenden | ergänzen, verwenden |
| D1G | Ich kann ein von mir erstelltes Programm… ausführen | 3 | Anwenden | ausführen |
| D1F | Ich kann die… Fehler- und Warnmeldungen interpretieren… beheben | 4 | Analysieren | interpretieren, beheben |
| D1E | Ich kann einen Debugger… gezielt zur Fehleranalyse einsetzen | 4 | Analysieren | anwenden, einsetzen *(Fehleranalyse)* |
| E1G | Ich kann den Aufbau, die Syntax… erklären und umsetzen | 3 | Anwenden | erklären, umsetzen |
| E1F | Ich kann einen detailliert vorgegebenen Ablauf… umsetzen | 3 | Anwenden | umsetzen |
| E1E | Ich kann einen grob beschriebenen Ablauf detaillieren… umsetzen | 3 | Anwenden | detaillieren, umsetzen |
| E2G | Ich kann den Aufbau und den Aufruf einer Funktion erklären… | 2 | Verstehen | erklären |
| E2F | Ich kann eine Funktion korrekt deklarieren… aufrufen | 3 | Anwenden | deklarieren, implementieren, aufrufen |
| E2E | Ich kann Programmteile identifizieren… refaktorisieren | 4 | Analysieren | identifizieren, refaktorisieren |
| F1G | Ich kann mein Programm mit… Kommentaren ergänzen | 3 | Anwenden | ergänzen |
| F1F | Ich kann Kommentare mit gängigen Annotationen versehen… formatieren | 3 | Anwenden | versehen, formatieren |
| F1E | Ich kann Konventionen für sauberen Sourcecode anwenden… | 3 | Anwenden | anwenden |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| A1G | "analysieren, identifizieren und gliedern" → "beschreiben und gliedern" | Bloom-Regel 1: G-Zelle war Stufe 4 (Analysieren); korrigiert auf Stufe 3 (Anwenden); "benennen" → "beschreiben" (Level 1 → Level 2) |
| Bloom-Tabelle | Bloom-Taxonomie-Analyse-Tabelle eingefügt und aktualisiert | Neu hinzugefügt gemäss Workflow |
| Band A | Buchstaben-Präfix ergänzt ("A - Probleme erfassen und Lösungsansätze entwickeln") | Einheitliche Bezeichnung gemäss Tabellenformat |
| A1G/A1F/A1E | Stakeholder-Aspekt in bestehende Zeile A1 integriert | Vollständigere Abdeckung der Handlungsziele |
| Tabelle | "Kompetenzband:" → "Kompetenzband" (Tabellenheader normalisiert) | Formatkonformität |
| A1G/A1F/A1E | Satzzeichen am Ende entfernt | Konsistenz |
| Band B | Buchstaben-Präfix ergänzt; "zBsp" → "z.B."; Trailing-Punkte/Ellipsen entfernt | Formatkonformität |
| B1E | Fehlenden Artikel ergänzt ("einen textuell beschriebenen Ablauf") | Grammatikkorrektur |
| Band C | Buchstaben-Präfix ergänzt; Trailing-Punkte entfernt | Formatkonformität |
| C1G | "weiss, für welche" (Mischkonstruktion) → "Ich kann ... erklären" | "Ich kann"-Format |
| C2G | "dekarieren" → "deklarieren"; "Modelklasse" → "Modellklasse" | Tippfehlerkorrektur |
| C2F | "Ich setze" → "Ich kann ... umsetzen" | "Ich kann"-Format |
| C2E | "Ich ergänze" → "Ich kann ... ergänzen" | "Ich kann"-Format |
| Band D | Buchstaben-Präfix ergänzt | Einheitliche Bezeichnung gemäss Tabellenformat |
| D1F | Formulierung gestrafft | Klarere, beobachtbare Beschreibung |
| D1E | "zBsp" → "z.B."; Grossschreibung korrigiert ("Breakpoints setzen, Variablenleiste nutzen") | Formatkonformität |
| Band E | Buchstaben-Präfix ergänzt | Einheitliche Bezeichnung gemäss Tabellenformat |
| E1G | "Ich kenne" → "Ich kann ... erklären und ... umsetzen" | "Ich kann"-Format |
| E1F | "vorgegeben" → "vorgegebenen" | Grammatikkorrektur |
| E2 | Leere HZ-Spalte mit "2,3,4" befüllt | Vollständigkeit |
| E2G/E2F | "zBsp" entfernt; Formulierung präzisiert | Formatkonformität |
| E2E | "auslagern" → "refaktorisieren" | Klarere Beschreibung |
| Band F | Buchstaben-Präfix ergänzt; "zBsp" → "z.B."; Trailing-Punkte entfernt | Formatkonformität |
| F1F | "Ich kenne" → "Ich kann ... versehen und formatieren" | "Ich kann"-Format |
| F1E | "Ich setze" → "Ich kann ... anwenden" | "Ich kann"-Format |
