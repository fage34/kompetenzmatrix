---
title: M293 Webauftritt erstellen und veröffentlichen
modul: m293
cluster: cluster-api
date: '2025-07-02T10:05:08Z'
draft: false
kompetenzbaender:
- id: A
  titel: Gestaltungsentwurf verstehen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann den Zweck eines Gestaltungsentwurfs erklären (z.B. Wireframe, Mockup, klickbarer Prototyp)
    fortgeschritten: Ich kann einen Gestaltungsentwurf erfassen und die darin enthaltenen Elemente erläutern (z.B. Wireframe, Mockup, klickbarer Prototyp)
    erweitert: Ich kann einen Gestaltungsentwurf hinterfragen und Verbesserungen zur Machbarkeit einbringen
- id: B
  titel: HTTP-Protokoll verstehen
  kompetenzen:
  - nr: 1
    hz: 1,2
    grundlagen: Ich kann den Ablauf einer HTTP-Anfrage (Request/Response) zwischen Client und Server erklären
    fortgeschritten: Ich kann den Aufbau einer HTTP-Verbindung (Request/Response) erklären (z.B. Header, Body, Key-Value, Cookies, Caching)
    erweitert: Ich kann den Inhalt einer HTTP-Anfrage mit geeigneten Werkzeugen analysieren (z.B. Browser-Entwicklerwerkzeuge, HTTP-Analyse-Tools)
- id: C
  titel: HTTP-Anfragemethoden anwenden
  kompetenzen:
  - nr: 1
    hz: 1,2
    grundlagen: Ich kann die Anfragemethoden des HTTP-Protokolls erläutern und deren Eigenheiten erklären (z.B. GET, POST)
    fortgeschritten: Ich kann die Anfragemethoden des HTTP-Protokolls in einer Webapplikation anwenden (z.B. GET, POST)
    erweitert: Ich kann eine HTTP-Anfragemethode für einen gegebenen Anwendungsfall begründet auswählen
- id: D
  titel: Werkzeug-Unterstützung
  kompetenzen:
  - nr: 1
    hz: 1,2
    grundlagen: Ich kann eine Entwicklungsumgebung für die Webentwicklung einrichten und für grundlegende Aufgaben verwenden (z.B. Dateien erstellen, bearbeiten, speichern)
    fortgeschritten: Ich kann die Entwicklerwerkzeuge des Browsers gezielt zur Analyse und Fehlersuche einsetzen (z.B. DOM-Inspektor, Netzwerk-Tab, Konsole)
    erweitert: Ich kann verschiedene Entwicklungswerkzeuge kombiniert einsetzen, um den Entwicklungsprozess zu unterstützen (z.B. Scaffolding, Linting, Browser-Konsole, Tastaturkürzel)
- id: E
  titel: Webseite aufbauen
  kompetenzen:
  - nr: 1
    hz: 2,3
    grundlagen: Ich kann den Aufbau einer Webseite erklären (z.B. Header, Body, Footer, Tags, Metatags)
    fortgeschritten: Ich kann eine grundlegende Webseite mit den erforderlichen Strukturelementen aufbauen (z.B. Header, Body, Footer, Tags, Metatags)
    erweitert: Ich kann einen Webauftritt aus mehreren Teilen aufbauen (z.B. Multipage, Templates, Komponenten)
- id: F
  titel: Formulare anwenden
  kompetenzen:
  - nr: 1
    hz: 2,3
    grundlagen: Ich kann den Aufbau und die Funktion eines Webformulars sowie die gängigen Formularelemente und deren Einsatzzweck erläutern (z.B. Eingabefeld, Dropdown, Checkbox, Radio-Button)
    fortgeschritten: Ich kann ein Formular gemäss Vorgabe umsetzen und Formularelemente gezielt einsetzen und konfigurieren (z.B. Eingabefeld, Dropdown, Checkbox, Radio-Button)
    erweitert: Ich kann ein bestehendes Formular auf Benutzerfreundlichkeit und Funktionalität prüfen sowie Formularelemente mit Validierung und Benutzerführung ergänzen (z.B. Pflichtfelder, Fehlermeldungen, Platzhaltertexte)
- id: G
  titel: Styling und Layout anwenden
  kompetenzen:
  - nr: 1
    hz: 2,3
    grundlagen: Ich kann den Zweck und die Grundprinzipien eines Layouts für Webseiten sowie den Zweck von CSS-Styling für die visuelle Gestaltung einer Webseite erklären
    fortgeschritten: Ich kann ein einfaches Layout mit HTML und CSS umsetzen und ein einheitliches Styling mit CSS anwenden
    erweitert: Ich kann ein bestehendes Layout analysieren, Verbesserungen zur Struktur und Benutzerführung vorschlagen und eine responsive Webseite gemäss Vorgaben umsetzen
- id: H
  titel: Umsetzung validieren und verbessern
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann Methoden zum Überprüfen und zur Verbesserung eines Webauftrittes erläutern (z.B. Konventionen, Validatoren, automatisierte Tools)
    fortgeschritten: Ich kann überprüfen, ob die Anforderungen an den Webauftritt umgesetzt wurden, und Konventionen bei der Webentwicklung einsetzen (z.B. Anforderungsliste, Coding-Guidelines, Style-Guidelines)
    erweitert: Ich kann den Webauftritt kritisch hinterfragen, konkrete Verbesserungen vorschlagen und automatisierte Überprüfungen einsetzen (z.B. Validatoren, Linter)
- id: I
  titel: Webauftritt veröffentlichen
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann den Prozess der Veröffentlichung eines Webauftrittes erklären
    fortgeschritten: Ich kann einen Webauftritt veröffentlichen (z.B. FTP, SFTP)
    erweitert: Ich kann einen Webauftritt automatisiert veröffentlichen (z.B. Continuous Integration)
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G | Ich kann den Zweck eines Gestaltungsentwurfs erklären… | 2 | Verstehen | erklären |
| A1F | Ich kann einen Gestaltungsentwurf erfassen und die… erläutern… | 2 | Verstehen | erfassen, erläutern |
| A1E | Ich kann einen Gestaltungsentwurf hinterfragen und Verbesserungen… | 5 | Bewerten | hinterfragen |
| B1G | Ich kann den Ablauf einer HTTP-Anfrage… erklären… | 2 | Verstehen | erklären |
| B1F | Ich kann den Aufbau einer HTTP-Verbindung… erklären… | 2 | Verstehen | erklären |
| B1E | Ich kann den Inhalt einer HTTP-Anfrage… analysieren… | 4 | Analysieren | analysieren |
| C1G | Ich kann die Anfragemethoden des HTTP-Protokolls erläutern… | 2 | Verstehen | erläutern, erklären |
| C1F | Ich kann die Anfragemethoden des HTTP-Protokolls… anwenden… | 3 | Anwenden | anwenden |
| C1E | Ich kann eine HTTP-Anfragemethode für einen… begründet auswählen… | 5 | Bewerten | begründet auswählen |
| D1G | Ich kann eine Entwicklungsumgebung… einrichten und… verwenden… | 3 | Anwenden | einrichten, verwenden |
| D1F | Ich kann die Entwicklerwerkzeuge des Browsers… einsetzen… | 3 | Anwenden | einsetzen |
| D1E | Ich kann verschiedene Entwicklungswerkzeuge kombiniert einsetzen… | 3 | Anwenden | kombiniert einsetzen |
| E1G | Ich kann den Aufbau einer Webseite erklären… | 2 | Verstehen | erklären |
| E1F | Ich kann eine grundlegende Webseite… aufbauen… | 3 | Anwenden | aufbauen |
| E1E | Ich kann einen Webauftritt aus mehreren Teilen aufbauen… | 3 | Anwenden | aufbauen |
| F1G | Ich kann den Aufbau und die Funktion eines Webformulars… erläutern… | 2 | Verstehen | erläutern |
| F1F | Ich kann ein Formular gemäss Vorgabe umsetzen… einsetzen… | 3 | Anwenden | umsetzen, einsetzen |
| F1E | Ich kann ein bestehendes Formular auf Benutzerfreundlichkeit… prüfen… | 5 | Bewerten | prüfen, validieren |
| G1G | Ich kann den Zweck und die Grundprinzipien eines Layouts… erklären… | 2 | Verstehen | erklären |
| G1F | Ich kann ein einfaches Layout mit HTML und CSS umsetzen… | 3 | Anwenden | umsetzen, anwenden |
| G1E | Ich kann ein bestehendes Layout analysieren, Verbesserungen… vorschlagen… | 4 | Analysieren | analysieren, vorschlagen |
| H1G | Ich kann Methoden zum Überprüfen und zur Verbesserung… erläutern… | 2 | Verstehen | erläutern |
| H1F | Ich kann überprüfen, ob die Anforderungen… umgesetzt wurden… | 3 | Anwenden | überprüfen, einsetzen |
| H1E | Ich kann den Webauftritt kritisch hinterfragen… vorschlagen… | 5 | Bewerten | hinterfragen, vorschlagen |
| I1G | Ich kann den Prozess der Veröffentlichung… erklären… | 2 | Verstehen | erklären |
| I1F | Ich kann einen Webauftritt veröffentlichen… | 3 | Anwenden | veröffentlichen |
| I1E | Ich kann einen Webauftritt automatisiert veröffentlichen… | 3 | Anwenden | automatisiert veröffentlichen |

**Bemerkung**

Die rechtlichen und sicherheitstechnischen Aspekte, die bei einem Webauftritt berücksichtigt und eingehalten werden müssen, sowie die rechtlichen und sicherheitstechnischen Abhängigkeiten, die im Zusammenhang mit dem geographischen Standort des Webservers stehen (z.B. europäischer Datenschutz, amerikanischer Datenschutz, Schweizer Datenschutz) enstehen, werden im Modul 231 abgedeckt.

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Alle Bänder | Buchstaben-Präfix ergänzt (A - ..., B - ..., etc.) | Einheitliche Bezeichnung gemäss Tabellenformat |
| Tabelle | Standard-Markdown-Separator normalisiert | Formatkonformität |
| Tabelle | Nachgestellte `...` in Beispielen durch saubere Klammern ersetzt | Sauberere Darstellung |
| A1G | "Gestaltungsentwurf" → "Gestaltungsentwurfs" | Genitiv-Korrektur |
| B1E | Produktname "Hookbin" → "Browser-Entwicklerwerkzeuge, HTTP-Analyse-Tools" | Produktneutralität |
| C1F | Konkretisiert mit "in einer Webapplikation anwenden" | Beobachtbarere Formulierung |
| C1E | Konkretisiert mit "für einen gegebenen Anwendungsfall begründet auswählen" | Beobachtbarere Formulierung |
| D1G | "Ich kenne" → "Ich kann"-Formulierung; konkrete Beispiele ergänzt | "Ich kann"-Format |
| D1F | Konkretisiert mit spezifischen Werkzeugbeispielen (DOM-Inspektor, Netzwerk-Tab, Konsole) | Beobachtbarere Formulierung |
| D1E | Vage Formulierung "alle Werkzeuge effizient einsetzen" → konkrete, beobachtbare Beschreibung | Keine vagen Begriffe |
| E1F | Konkretisiert mit "mit den erforderlichen Strukturelementen" | Beobachtbarere Formulierung |
| F1G | "HTML Forms" → "Webformulars" | Produktneutralität |
| F1E | Vage Formulierung → konkrete Prüfkriterien (Benutzerfreundlichkeit, Funktionalität) | Keine vagen Begriffe |
| F2E | "komplexere Formularelemente (z.B. Label)" → Validierung, Pflichtfelder, Fehlermeldungen, Platzhaltertexte | Konkretere, beobachtbare Beschreibung |
| G1G | Vage Formulierung → mit Beispiel (Anordnung von Inhaltsbereichen) konkretisiert | Keine vagen Begriffe |
| G2G | Vage Formulierung → "Zweck von CSS-Styling für die visuelle Gestaltung" | Keine vagen Begriffe |
| H1/H2 | Spaltenreihenfolge korrigiert (F und E waren vertauscht) | Korrekte Gütestufen-Reihenfolge |
| H1F/H1E | Inhaltlich präzisiert | Beobachtbarere Formulierung |
| I1 | Spaltenreihenfolge korrigiert (F und E waren vertauscht) | Korrekte Gütestufen-Reihenfolge |
| I1E | "Continous" → "Continuous" | Tippfehlerkorrektur |
| F (Zeilen F1+F2) | Zwei Zeilen zu einer Zeile F1 zusammengeführt | Konsolidierung auf max. 9 Zeilen: F1 (Formularaufbau) und F2 (Formularelemente) thematisch zusammengeführt |
| G (Zeilen G1+G2) | Zwei Zeilen zu einer Zeile G1 zusammengeführt | Konsolidierung auf max. 9 Zeilen: G1 (Layout) und G2 (CSS-Styling) thematisch zusammengeführt |
| H (Zeilen H1+H2) | Zwei Zeilen zu einer Zeile H1 zusammengeführt | Konsolidierung auf max. 9 Zeilen: H1 (Validierung) und H2 (Verbesserung/Konventionen) thematisch zusammengeführt |
| Bloom-Tabelle | Neu hinzugefügt | Bloom-Taxonomie-Analyse für alle G/F/E-Zellen ergänzt; keine Bloom-Regelverletzungen gefunden |
