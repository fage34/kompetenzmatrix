---
title: M129 LAN-Komponenten in Betrieb nehmen
modul: m129
cluster: cluster-platform
date: '2025-07-02T10:06:40Z'
draft: false
kompetenzbaender:
- id: A
  titel: Grundlagen und Standard
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann wesentliche Technologien und Standards zuordnen und ein Netzwerkschema interpretieren.
    fortgeschritten: Ich kann Technologien (im Bereich LAN, WLAN) und Standards (ISO/OSI, Protokolle) zuordnen und erklären, sowie Details aus einem Netzwerkschema entnehmen.
    erweitert: Ich kann die Wirkung von Technologien und Standards in konkreten Praxisanwendungen analysieren und die Angaben eines Netzwerkschemas fachlich begründet erläutern.
- id: B
  titel: Funktion und Konfiguration
  kompetenzen:
  - nr: 1
    hz: 1, 3
    grundlagen: Ich kann die Funktionsweise von Switches und Routern erklären sowie diese in Betrieb nehmen.
    fortgeschritten: Ich kann wesentliche Eigenschaften eines Switches aufzeigen, einen Router fachgerecht konfigurieren und grundlegende Sicherheitseinstellungen (Default Password, Grundhärtung) vornehmen.
    erweitert: Ich kann erweiterte Switch-Funktionen (Manageable, Stackable, Auto-Sense, Spanning Tree, Mirroring, Bridging) gezielt einsetzen und ein umfassendes Sicherheitskonzept (Passwortverwaltung, Deaktivierung ungenutzter Protokolle, Logging) planen und umsetzen.
- id: C
  titel: Adressierung und Subnettierung
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann in einem Subnetz ein fachgerechtes IP-Adresskonzept für verschiedene Gerätegruppen erstellen.
    fortgeschritten: Ich kann die IP-Adressierung für mehrere Subnetze in einem LAN fachgerecht planen und umsetzen.
    erweitert: Ich kann ein IP-Adresskonzept mit dedizierten Bereichen für Dienste, Geräte (statische IP-Adressierung) und Spezialanwendungen entwerfen sowie zukünftige Erweiterungsmöglichkeiten aufzeigen.
- id: D
  titel: Routing
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann einfache statische Routingtabellen umsetzen.
    fortgeschritten: Ich kann die Vor- und Nachteile von statischem und dynamischem Routing erklären und statische Routingtabellen für ein LAN mit mehreren Subnetzen fachgerecht planen und umsetzen.
    erweitert: Ich kann Spezialfälle im Routing (z. B. Redundanz, Load Balancing) erklären, potenzielle Schwachstellen identifizieren und geeignete Erweiterungsmassnahmen aufzeigen.
- id: E
  titel: Fehleranalyse und -behebung
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann grundlegende Befehle zur Fehlersuche anwenden.
    fortgeschritten: Ich kann verschiedene Werkzeuge zur Analyse der Netzwerkfunktion einsetzen und damit Fehlfunktionen eingrenzen und beheben.
    erweitert: Ich kann Fehlfunktionen systematisch (Ausschlussverfahren, OSI-Schichtenmodell) und effizient (zielgerichteter Werkzeugeinsatz) eingrenzen und beheben sowie die Dienstgüte (Bandbreitenmanagement) beurteilen.
- id: F
  titel: Netzwerkdokumentation
  kompetenzen:
  - nr: 1
    hz: '6'
    grundlagen: Ich kann ein einfaches Netzwerkschema erstellen und wesentliche Aspekte dazu dokumentieren.
    fortgeschritten: Ich kann ein vollständiges Netzwerkschema erstellen sowie Konfigurationen und wesentliche Aspekte nachvollziehbar dokumentieren.
    erweitert: Ich kann in der Dokumentation wichtige Designentscheide und Überlegungen festhalten, damit Ergänzungen geplant oder ein Neuaufbau effizient bewerkstelligt werden kann.
- id: G
  titel: Test- und Abnahmeprotokoll
  kompetenzen:
  - nr: 1
    hz: '7'
    grundlagen: Ich kann mit einfachen Tests die Funktion eines Netzwerkes prüfen und dies mit einem Protokoll belegen.
    fortgeschritten: Ich kann mit gut gewählten Testfällen die Funktion eines Netzwerkes prüfen, notwendige Massnahmen umsetzen sowie ein angemessenes Abnahmeprotokoll erstellen.
    erweitert: Ich kann Testfälle zur Prüfung der Funktion und der Grenzen (Lasttest, Spezialfälle) eines Netzwerkes entwerfen und notwendige Massnahmen daraus ableiten.
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann wesentliche Technologien und Standards zuordnen… | 2 | Verstehen | zuordnen, interpretieren |
| A1F  | Ich kann Technologien und Standards zuordnen und erklären… | 2 | Verstehen | zuordnen, erklären, entnehmen |
| A1E  | Ich kann die Wirkung von Technologien und Standards analysieren… | 4 | Analysieren | analysieren, erläutern |
| B1G  | Ich kann die Funktionsweise von Switches und Routern erklären… | 3 | Anwenden | erklären, in Betrieb nehmen |
| B1F  | Ich kann wesentliche Eigenschaften eines Switches aufzeigen… | 3 | Anwenden | aufzeigen, konfigurieren, vornehmen |
| B1E  | Ich kann erweiterte Switch-Funktionen gezielt einsetzen… | 5 | Bewerten | einsetzen, planen, umsetzen |
| C1G  | Ich kann in einem Subnetz ein fachgerechtes IP-Adresskonzept… | 3 | Anwenden | erstellen |
| C1F  | Ich kann die IP-Adressierung für mehrere Subnetze planen… | 3 | Anwenden | planen, umsetzen |
| C1E  | Ich kann ein IP-Adresskonzept mit dedizierten Bereichen entwerfen… | 6 | Erschaffen | entwerfen, aufzeigen |
| D1G  | Ich kann einfache statische Routingtabellen umsetzen… | 3 | Anwenden | umsetzen |
| D1F  | Ich kann die Vor- und Nachteile von statischem und dynamischem Routing… | 3 | Anwenden | erklären, planen, umsetzen |
| D1E  | Ich kann Spezialfälle im Routing erklären, Schwachstellen identifizieren… | 4 | Analysieren | erklären, identifizieren, aufzeigen |
| E1G  | Ich kann grundlegende Befehle zur Fehlersuche anwenden… | 3 | Anwenden | anwenden |
| E1F  | Ich kann verschiedene Werkzeuge zur Analyse einsetzen… | 3 | Anwenden | einsetzen, eingrenzen, beheben |
| E1E  | Ich kann Fehlfunktionen systematisch eingrenzen und beheben… | 5 | Bewerten | eingrenzen, beheben, beurteilen |
| F1G  | Ich kann ein einfaches Netzwerkschema erstellen… | 3 | Anwenden | erstellen, dokumentieren |
| F1F  | Ich kann ein vollständiges Netzwerkschema erstellen… | 3 | Anwenden | erstellen, dokumentieren |
| F1E  | Ich kann in der Dokumentation wichtige Designentscheide festhalten… | 3 | Anwenden | festhalten |
| G1G  | Ich kann mit einfachen Tests die Funktion eines Netzwerkes prüfen… | 3 | Anwenden | prüfen, belegen |
| G1F  | Ich kann mit gut gewählten Testfällen die Funktion prüfen… | 3 | Anwenden | prüfen, umsetzen, erstellen |
| G1E  | Ich kann Testfälle zur Prüfung der Funktion und Grenzen entwerfen… | 6 | Erschaffen | entwerfen, ableiten |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| A1G | Doppelten Punkt am Satzende entfernt | Formatbereinigung |
| A1E | Wiederholung aus A1F entfernt; Fokus auf Analyse der Wirkung in Praxisanwendungen; Doppeltes Leerzeichen entfernt | Eigenständigkeit der Gütestufen |
| B1F | Wiederholung der Inbetriebnahme aus B1G entfernt; Fokus auf fachgerechte Konfiguration und Sicherheitseinstellungen | Eigenständigkeit der Gütestufen |
| B1E | Wiederholung aus B1G/B1F entfernt; Fokus auf erweiterte Switch-Funktionen und umfassendes Sicherheitskonzept; Doppeltes Leerzeichen entfernt | Eigenständigkeit der Gütestufen |
| C1E | Wiederholung aus C1F entfernt; Fokus auf dedizierte Bereiche und Erweiterungsmöglichkeiten | Eigenständigkeit der Gütestufen |
| D1E | Wiederholung aus D1F entfernt; Fokus auf Spezialfälle und Schwachstellen | Eigenständigkeit der Gütestufen |
| E1E | Wiederholung aus E1F entfernt; Fokus auf systematische Methodik und Dienstgüte | Eigenständigkeit der Gütestufen |
| F1E | Wiederholung aus F1F entfernt; Fokus auf Designentscheide und Nachvollziehbarkeit | Eigenständigkeit der Gütestufen |
| G1E | Wiederholung aus G1F entfernt; Fokus auf Grenztests und Ableitung von Massnahmen | Eigenständigkeit der Gütestufen |
| Alle Bänder | Einheitliches Format "Buchstabe - Beschreibung" angewendet | Vorgabe Tabellenformat |
| Alle Zellen | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neue Anforderung: Bloom-Analyse pro Zelle |
| B1G | Bloom-Stufe korrigiert: L2 → L3 (Anwenden), da "in Betrieb nehmen" Bloom-Stufe 3 entspricht | Bloom-Analyse-Korrektur |
| C1E | Bloom-Stufe korrigiert: L5 → L6 (Erschaffen), da "entwerfen" Bloom-Stufe 6 entspricht | Bloom-Analyse-Korrektur |
| E1E | Bloom-Stufe korrigiert: L4 → L5 (Bewerten), da "beurteilen" Bloom-Stufe 5 entspricht | Bloom-Analyse-Korrektur |
| G1E | Bloom-Stufe korrigiert: L5 → L6 (Erschaffen), da "entwerfen" Bloom-Stufe 6 entspricht | Bloom-Analyse-Korrektur |
