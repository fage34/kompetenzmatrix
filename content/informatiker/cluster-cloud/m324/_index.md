---
title: M324 DevOps-Prozesse mit Tools unterstützen
modul: m324
cluster: cluster-cloud
date: '2025-07-02T10:05:16Z'
draft: false
kompetenzbaender:
- id: A
  titel: DevOps Nutzen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann eine kontinuierliche und toolunterstützte Applikationsentwicklung erklären
    fortgeschritten: Ich kann den Nutzen einer kontinuierlichen, toolunterstützten Applikationsentwicklung anhand konkreter Beispiele aufzeigen und begründen
    erweitert: Ich kann eine toolunterstützte Applikationsentwicklung bewerten und geeignete Tools für spezifische Projektanforderungen auswählen und deren Einsatz begründen
- id: B
  titel: Management von Anforderungen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann Anforderungen beschreiben und weiss, wo man diese verwaltet
    fortgeschritten: Ich kann Anforderungen nach bestimmter Vorgehensweise schreiben und kategorisieren sowie an einem bestimmten Ort verwalten
    erweitert: Ich kann Anforderungen auf Vollständigkeit/Richtigkeit prüfen und Unklarheiten formulieren sowie nachvollziehbar verwalten
- id: C
  titel: Nachvollziehbarkeit von Entwicklungen
  kompetenzen:
  - nr: 1
    hz: 1, 3
    grundlagen: Ich kann Vorgehensweisen für nachvollziehbare Applikationsentwicklung beschreiben
    fortgeschritten: Ich kann Vorgehensweisen für nachvollziehbare Applikationsentwicklung anwenden
    erweitert: Ich kann Vorgehensweisen für nachvollziehbare Applikationsentwicklung anwenden und gezielt einsetzen
- id: D
  titel: Entwicklungsumgebung
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann eine einfache Entwicklungsumgebung mit Tools anwenden
    fortgeschritten: Ich kann eine Entwicklungsumgebung mit automatisierenden Tools anwenden und die Ergebnisse der Tools analysieren
    erweitert: Ich kann eine Entwicklungsumgebung mit automatisierenden Tools anwenden, erweitern, optimieren und die Ergebnisse der Tools klassifizieren
- id: E
  titel: Sourcecode Verwaltung
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann mit einfachen Praktiken den Sourcecode verwalten
    fortgeschritten: Ich kann erweiterte Praktiken anwenden, um den Sourcecode featurebasiert zu verwalten
    erweitert: Ich kann erweiterte Praktiken kombiniert anwenden, um den Sourcecode featurebasiert und nachhaltig zu verwalten
- id: F
  titel: Artefakt Verwaltung
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann Artefakte beschreiben und diese in einem Artefakt-Repository verwalten
    fortgeschritten: Ich kann ein einfaches Artefakt-Repository erstellen und dessen Struktur für die Verwaltung unterschiedlicher Artefakte einrichten
    erweitert: Ich kann ein Artefakt-Repository für verschiedene Artefakt-Typen erstellen, konfigurieren und die entsprechenden Artefakt-Typen darin gezielt verwalten
- id: G
  titel: Continuous Integration
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann mit einfachen Praktiken Applikationen und Komponenten automatisiert kompilieren und testen
    fortgeschritten: Ich kann mit erweiterten Praktiken Applikationen und Komponenten automatisiert kompilieren, testen und analysieren
    erweitert: Ich kann mit bewährten Praktiken und Methoden Applikationen und Komponenten automatisiert kompilieren, testen, analysieren und auswerten
- id: H
  titel: Continuous Delivery
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann mit einfachen Praktiken Applikationen automatisiert deployen, konfigurieren und testen
    fortgeschritten: Ich kann mit erweiterten Praktiken Applikationen automatisiert deployen, konfigurieren und testen
    erweitert: Ich kann mit bewährten Praktiken und Methoden Applikationen automatisiert deployen, konfigurieren, testen, überwachen und validieren
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann eine kontinuierliche und tool… | 2 | Verstehen | erklären |
| A1F  | Ich kann den Nutzen einer kontinuierlichen… | 5 | Bewerten | aufzeigen, begründen |
| A1E  | Ich kann eine toolunterstützte Applikations… | 5 | Bewerten | bewerten, auswählen, begründen |
| B1G  | Ich kann Anforderungen beschreiben und… | 2 | Verstehen | beschreiben |
| B1F  | Ich kann Anforderungen nach bestimmter… | 3 | Anwenden | schreiben, kategorisieren, verwalten |
| B1E  | Ich kann Anforderungen auf Vollständigkeit… | 5 | Bewerten | prüfen, formulieren |
| C1G  | Ich kann Vorgehensweisen für nachvollziehbare… | 2 | Verstehen | beschreiben |
| C1F  | Ich kann Vorgehensweisen für nachvollziehbare… | 3 | Anwenden | anwenden |
| C1E  | Ich kann Vorgehensweisen für nachvollziehbare… | 3 | Anwenden | anwenden, einsetzen |
| D1G  | Ich kann eine einfache Entwicklungsumgebung… | 3 | Anwenden | anwenden |
| D1F  | Ich kann eine Entwicklungsumgebung mit… | 4 | Analysieren | anwenden, analysieren |
| D1E  | Ich kann eine Entwicklungsumgebung mit… | 4 | Analysieren | anwenden, erweitern, klassifizieren |
| E1G  | Ich kann mit einfachen Praktiken den… | 3 | Anwenden | verwalten |
| E1F  | Ich kann erweiterte Praktiken anwenden… | 3 | Anwenden | anwenden |
| E1E  | Ich kann erweiterte Praktiken kombiniert… | 3 | Anwenden | anwenden |
| F1G  | Ich kann Artefakte beschreiben und diese… | 2 | Verstehen | beschreiben, verwalten |
| F1F  | Ich kann ein einfaches Artefakt-Repository… | 6 | Erschaffen | erstellen, einrichten |
| F1E  | Ich kann ein Artefakt-Repository für… | 6 | Erschaffen | erstellen, konfigurieren, verwalten |
| G1G  | Ich kann mit einfachen Praktiken Applikationen… | 3 | Anwenden | kompilieren, testen |
| G1F  | Ich kann mit erweiterten Praktiken Applikationen… | 4 | Analysieren | kompilieren, testen, analysieren |
| G1E  | Ich kann mit bewährten Praktiken und Methoden… | 5 | Bewerten | analysieren, auswerten |
| H1G  | Ich kann mit einfachen Praktiken Applikationen… | 3 | Anwenden | deployen, konfigurieren, testen |
| H1F  | Ich kann mit erweiterten Praktiken Applikationen… | 3 | Anwenden | deployen, konfigurieren, testen |
| H1E  | Ich kann mit bewährten Praktiken und Methoden… | 5 | Bewerten | deployen, überwachen, validieren |

## Hinweise
<sup>A</sup> Qualitätssicherung, Nachhaltige und konsistente Softwareentwicklung, Risikoreduktion, Senkung der Entwicklungskosten, Erhöhung der Entwicklungsgeschwindigkeit

<br/><sup>B</sup> Epic, Userstory, Productbacklog Item, Issues, Task, 3-C Technik, DoD vs Akzeptanzkriterien, MoSCoW-Priorisierung

<br/><sup>C</sup> Pull-Request, Code-Review (4-Augenprinzip), Verlinkung von Work-Items zu commits, Dokumentation, Teamkommunikation, Know-How sharing (z.B. Dev-Exchange)

<br/><sup>D</sup> Statische Code-Analyse, Dependency-Management, Testautomatisierung, Build-Tools, Dokumentations-Tools, Task-Runner, Versionskontrolle

<br/><sup>E</sup> Release Branches, Feature Branches, Pull-Requests, Merging, Rebase, Semantic Versioning

<br/><sup>F</sup> Speicherung von Binärdateien(DLL,war,jar usw.), Dependeny-Management, Integration mit Build-Tools, public/private Artefakt-Repository, nuget-Repository, maven-Repository, javascript-Repository, container-Repository

<br/><sup>G</sup> Integration-Pipelines, YAML, Automatisierte Builds, Automatisierte Tests, Code-Analyse, Code-Qualität-Metriken, Frühe Fehlererkennung, Schnelle Feedbackschleifen 

<br/><sup>H</sup> Deployment-Pipelines, YAML, Infrastructure as Code, Automatisierte Bereitstellung (Deployment), Automatisierte Tests, Konstante Überwachung, Konstante Validierung

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung                                                                                                             |
| --- | --- |------------------------------------------------------------------------------------------------------------------------|
| A1G | "toolunterstütze" korrigiert zu "toolunterstützte" | Tippfehler behoben                                                                                                     |
| A1F | Komplett überarbeitet: von "erklären" zu "aufzeigen und begründen" mit konkreten Beispielen | Feedback: Fortgeschritten muss höher als nur "erklären" sein; klare Niveausteigerung gegenüber Grundlagen              |
| A1E | Komplett überarbeitet: von "erklären" zu "bewerten und auswählen" | Feedback: Erweitert muss deutlich über Fortgeschritten liegen; nun Bewertungs- und Entscheidungskompetenz              |
| D1F | "Entwickungsumgebung" korrigiert zu "Entwicklungsumgebung" | Tippfehler behoben                                                                                                     |
| F1F | Komplett überarbeitet: von "Artefakte verwalten" zu "Repository erstellen und Struktur einrichten" | Feedback: F1F war nicht von F1G differenziert; nun liegt der Fokus auf Erstellen und Strukturieren statt nur Verwalten |
| F1E | "eine Artefakt-Repository" korrigiert zu "ein Artefakt-Repository"; "verschieden" zu "verschiedene"; "konfigurieren" und "gezielt" ergänzt | Grammatikfehler (Genus) behoben; Niveausteigerung gegenüber F1F verdeutlicht                                           |
| G1G | "builden" ersetzt durch "kompilieren" | Feedback: "builden" ist kein korrektes deutsches Wort und für Fachfremde unverständlich                                |
| G1F | "builden" ersetzt durch "kompilieren"; "komponenten" korrigiert zu "Komponenten" | Gleiche Begründung wie G1G; zusätzlich Grossschreibung korrigiert                                                      |
| G1E | "builden" ersetzt durch "kompilieren" | Gleiche Begründung wie G1G                                                                                             |
| Tabellenheader | "Kompetenzband:" zu "Kompetenzband" (Doppelpunkt entfernt) | Formatkonformität gemäss Vorlage                                                                                       |
| C1F | Überflüssige Leerzeichen nach `<br/>` entfernt | Formatbereinigung                                                                                                      |
| HZ-Spalte C | "1,3" zu "1, 3" | Einheitliche Formatierung der HZ-Verweise                                                                              |
| Gesamte Tabelle | Leerzeichen in Zellen vereinheitlicht | Konsistente Formatierung                                                                                               |
| C1E, E1E, H1F | Keine Änderung vorgenommen — Bloom-Niveau F=G bzw. E=F ist per Regel 2 zulässig (gleich ist kein Verstoss) | Rückgängig: vorherige Overcorrection wurde nicht angewendet |
| Bloom-Tabelle | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neu hinzugefügt gemäss Workflow                                                                                        |
