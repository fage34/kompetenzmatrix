---
title: M321 Verteilte Systeme programmieren
modul: m321
cluster: cluster-api
date: '2025-07-02T10:05:00Z'
draft: false
kompetenzbaender:
- id: A
  titel: Software analysieren und überführen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann die Strukturen unterschiedlicher Softwaresysteme beschreiben
    fortgeschritten: Ich kann Softwaresysteme hinsichtlich ihrer Eignung für verteilte Systeme analysieren
    erweitert: Ich kann Softwaresysteme in verteilte Systeme überführen und die Auswirkungen auf Struktur und Schnittstellen analysieren
  - nr: 2
    hz: '1'
    grundlagen: Ich kann die Grundlagen verteilter Systemarchitekturen erläutern
    fortgeschritten: Ich kann bestehende Applikationen für die Integration in verteilte Systeme vorbereiten
    erweitert: Ich kann Lösungsstrategien für die Systemintegration umsetzen
- id: B
  titel: Datenhaltung verstehen und planen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann die Anforderungen an die Datenhaltung in verteilten Systemen erklären
    fortgeschritten: Ich kann Datenmanagementsysteme in verteilten Systemen einsetzen
    erweitert: Ich kann ein geeignetes Datenmanagementsystem auswählen
- id: C
  titel: Komponenten erklären, implementieren und evaluieren
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann die Rolle von Systemkomponenten in verteilten Systemen erklären
    fortgeschritten: Ich kann Systemkomponenten lokal und in einem verteilten System implementieren und testen
    erweitert: Ich kann Systemkomponenten für die Integration in verteilten Systemen evaluieren
- id: D
  titel: Datenaustausch erklären und umsetzen
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann die Prinzipien des Datenaustausches erklären
    fortgeschritten: Ich kann gemäss der Grundkonzepte den Datenaustausch umsetzen und testen
    erweitert: Ich kann aufgrund von Anforderungen eine konkrete Umsetzung für den Datenaustausch wählen
  - nr: 2
    hz: '3'
    grundlagen: Ich kann verschiedene Arten von Schnittstellenprotokollen unterscheiden
    fortgeschritten: Ich kann Protokolle für die Datenübertragung zwischen Systemkomponenten anwenden
    erweitert: Ich kann die Angemessenheit von Schnittstellenprotokollen für spezifische Anwendungsfälle beurteilen
- id: E
  titel: Authentisierung und Autorisierung implementieren
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann die Mechanismen der Authentisierung und Autorisierung in verteilten Systemen erklären
    fortgeschritten: Ich kann Authentisierung und Autorisierung in verteilten Systemen implementieren und testen
    erweitert: Ich kann geeignete Lösungen für die Authentisierung und Autorisierung in verteilten Systemen vorschlagen
- id: F
  titel: Überwachungswerkzeuge einsetzen
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann Werkzeuge für die Überwachung von verteilten Systemen erklären
    fortgeschritten: Ich kann Werkzeuge für die Überwachung von verteilten Systemen einsetzen
    erweitert: Ich kann sinnvolle Anforderungen für die Überwachung definieren und die Konfiguration der Werkzeuge entsprechend umsetzen
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G | Ich kann die Strukturen unterschiedlicher Softwaresysteme beschreiben… | 2 | Verstehen | beschreiben |
| A1F | Ich kann Softwaresysteme hinsichtlich ihrer Eignung… analysieren… | 4 | Analysieren | analysieren |
| A1E | Ich kann Softwaresysteme in verteilte Systeme überführen… analysieren… | 4 | Analysieren | überführen, analysieren |
| A2G | Ich kann die Grundlagen verteilter Systemarchitekturen erläutern… | 2 | Verstehen | erläutern |
| A2F | Ich kann bestehende Applikationen für die Integration… vorbereiten… | 3 | Anwenden | vorbereiten |
| A2E | Ich kann Lösungsstrategien für die Systemintegration umsetzen… | 3 | Anwenden | umsetzen |
| B1G | Ich kann die Anforderungen an die Datenhaltung… erklären… | 2 | Verstehen | erklären |
| B1F | Ich kann Datenmanagementsysteme in verteilten Systemen einsetzen… | 3 | Anwenden | einsetzen |
| B1E | Ich kann ein geeignetes Datenmanagementsystem auswählen… | 3 | Anwenden | auswählen |
| C1G | Ich kann die Rolle von Systemkomponenten… erklären… | 2 | Verstehen | erklären |
| C1F | Ich kann Systemkomponenten lokal und in einem verteilten System… | 3 | Anwenden | implementieren, testen |
| C1E | Ich kann Systemkomponenten für die Integration… evaluieren… | 5 | Bewerten | evaluieren |
| D1G | Ich kann die Prinzipien des Datenaustausches erklären… | 2 | Verstehen | erklären |
| D1F | Ich kann gemäss der Grundkonzepte den Datenaustausch umsetzen… | 3 | Anwenden | umsetzen, testen |
| D1E | Ich kann aufgrund von Anforderungen eine konkrete Umsetzung… wählen… | 5 | Bewerten | wählen (begründet) |
| D2G | Ich kann verschiedene Arten von Schnittstellenprotokollen unterscheiden… | 2 | Verstehen | unterscheiden |
| D2F | Ich kann Protokolle für die Datenübertragung… anwenden… | 3 | Anwenden | anwenden |
| D2E | Ich kann die Angemessenheit von Schnittstellenprotokollen… beurteilen… | 5 | Bewerten | beurteilen |
| E1G | Ich kann die Mechanismen der Authentisierung… erklären… | 2 | Verstehen | erklären |
| E1F | Ich kann Authentisierung und Autorisierung… implementieren… | 3 | Anwenden | implementieren, testen |
| E1E | Ich kann geeignete Lösungen für die Authentisierung… vorschlagen… | 5 | Bewerten | vorschlagen |
| F1G | Ich kann Werkzeuge für die Überwachung… erklären… | 2 | Verstehen | erklären |
| F1F | Ich kann Werkzeuge für die Überwachung… einsetzen… | 3 | Anwenden | einsetzen |
| F1E | Ich kann sinnvolle Anforderungen für die Überwachung definieren… | 3 | Anwenden | definieren, umsetzen |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Spaltenüberschriften | "Grund-Kompetenz (Wissen/Verstehen)", "Fortgeschrittene-Kompetenz (Anwenden/Analysieren)", "Erweiterte-Kompetenz (Evaluieren/Schaffen)" → "Grundlagen", "Fortgeschritten", "Erweitert" | Standardkonformes Format |
| Separator-Zeile | Tabellen-Separator korrigiert auf Format mit `:---` für Grundlagen-Spalte | Standardkonformes Format |
| Header | Tab-Zeichen entfernt | Einheitliches Format |
| Alle Zellen | Trailing Periods entfernt | Konsistenz |
| F1G | "Ich kenne Werkzeuge ... und kann diese erklären" → "Ich kann Werkzeuge ... erklären" | "Ich kann"-Format |
| A1G | "verstehen" → "beschreiben" | Konkret beobachtbares Kriterium statt vager Begriff |
| B1F | "Datenmanagement Systeme" → "Datenmanagementsysteme" | Korrekte Zusammenschreibung |
| B1E | "Datamanagement System" → "Datenmanagementsystem" | Deutsches Wort, korrekte Zusammenschreibung |
| F1E | Doppeltes Leerzeichen vor "Überwachung" entfernt | Einheitliches Format |
| A1E | "Softwaresysteme in verteilte Systeme überführen" → "…überführen und die Auswirkungen auf Struktur und Schnittstellen analysieren" | Bloom-Regel 2: A1F ist Stufe 4 (Analysieren), A1E muss ≥ Stufe 4 sein |
| Bloom-Tabelle | Neu hinzugefügt | Bloom-Taxonomie-Analyse für alle G/F/E-Zellen ergänzt |
