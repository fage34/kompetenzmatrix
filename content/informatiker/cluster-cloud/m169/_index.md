---
title: M169 Dienste mit Containern bereitstellen
modul: m169
cluster: cluster-cloud
date: '2025-07-02T10:05:17Z'
draft: false
kompetenzbaender:
- id: A
  titel: Container-Umgebung definieren
  kompetenzen:
  - nr: 1
    hz: 1,2,8
    grundlagen: Ich kann zwischen Containern und virtuellen Maschinen unterscheiden sowie deren Vor- und Nachteile aufzählen
    fortgeschritten: Ich kann bestehende Container einsetzen und deren Konfiguration anpassen
    erweitert: Ich kann eine Container-Umgebung mit einem oder mehreren Services planen und aufsetzen
- id: B
  titel: Microservice-Architektur erläutern
  kompetenzen:
  - nr: 1
    hz: 1,2
    grundlagen: Ich kann den Unterschied zwischen einer monolithischen und einer Microservice-Architektur beschreiben
    fortgeschritten: Ich kann eine Microservice-Architektur mit Eigenschaften eines verteilten Systems, wie Schnittstellen und Vernetzung, erläutern
    erweitert: Ich kann den Einfluss des Microservice-Paradigmas auf eine Zielarchitektur analysieren und geeignete Massnahmen vorschlagen
- id: C
  titel: Synchrone und asynchrone Services unterscheiden
  kompetenzen:
  - nr: 1
    hz: 1,2,5
    grundlagen: Ich kann Eigenschaften von synchronen und asynchronen Services beschreiben und deren Unterschiede erläutern
    fortgeschritten: Ich kann Beispiele für synchrone und asynchrone Anwendungsfälle nennen und diese einem Verwendungszweck zuordnen
    erweitert: Ich kann für einen gegebenen Anwendungsfall geeignete Schnittstellen vorschlagen und den Zusammenhang zwischen verteilten Systemen und asynchronen Services erklären
- id: D
  titel: Codebasierten Serviceaufbau einsetzen
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann Werkzeuge und Methoden zur Beschreibung von Services mittels Infrastructure as Code (IaC) beschreiben und deren Einsatzzweck erklären
    fortgeschritten: Ich kann den Ablauf zur Erstellung von codebasierten Services beschreiben und Werkzeuge mit Syntaxunterstützung sowie Prüfung der Codekonsistenz verwenden
    erweitert: Ich kann Service-Konfigurationen codebasiert in Containern bereitstellen und mit IaC dokumentieren
- id: E
  titel: Qualität für codebasierte Service-Bereitstellung sicherstellen
  kompetenzen:
  - nr: 1
    hz: 3,4
    grundlagen: Ich kann Methoden zur Sicherstellung der Qualität bei der Verwendung von Code beschreiben
    fortgeschritten: Ich kann den Nutzen und Einsatzzweck eines Versionsverwaltungssystems erläutern, insbesondere hinsichtlich Qualität für codebasierte Service-Bereitstellung
    erweitert: Ich kann ein Versionsverwaltungssystem zur Verwaltung und Erstellung von versioniertem, kommentiertem Code anwenden
- id: F
  titel: Sicherheitsanforderungen berücksichtigen
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann Massnahmen und Methoden zur Umsetzung von Sicherheitsanforderungen beschreiben
    fortgeschritten: Ich kann Sicherheitsanforderungen umsetzen und auf ihre Wirksamkeit prüfen
    erweitert: Ich kann bei unzureichenden Sicherheitsanforderungen zusätzliche Massnahmen definieren und umsetzen, um die Sicherheit zu erhöhen
- id: G
  titel: Datenverbindungen zwischen Services konfigurieren
  kompetenzen:
  - nr: 1
    hz: 4,5
    grundlagen: Ich kann bereits konfigurierte Datenverbindungen unterscheiden und ihrem Nutzen zuordnen
    fortgeschritten: Ich kann Konfigurationen für Datenverbindungen nach Vorgaben umsetzen, um einen sicheren Datenaustausch zwischen Services zu ermöglichen
    erweitert: Ich kann eigene Datenverbindungen gemäss Anforderungen zur Sicherheit und Persistenz konfigurieren
- id: H
  titel: Services in Containern bereitstellen
  kompetenzen:
  - nr: 1
    hz: 6,7,8
    grundlagen: Ich kann vorgegebene Container bereitstellen und ihre Funktionsfähigkeit mit geeigneten Mitteln überprüfen
    fortgeschritten: Ich kann einen oder mehrere Services in Containern bereitstellen und geeignete Mittel zur Behebung von Fehlern einsetzen
    erweitert: Ich kann über eine Registry Container-Images wiederverwenden und eigene Images in der Registry verfügbar machen
- id: I
  titel: Services administrieren und überwachen
  kompetenzen:
  - nr: 1
    hz: 7,8
    grundlagen: Ich kann die Zusammenhänge einer containerisierten Infrastruktur und erforderliche Massnahmen für eine zuverlässige Überwachung beschreiben
    fortgeschritten: Ich kann die Ressourcenverwendung von Services nachvollziehen und überwachen
    erweitert: Ich kann den Ressourcenbedarf für containerisierte Services mit konkreten Annahmen bestimmen, diesen mit dem effektiven Bedarf vergleichen und Massnahmen zur Ressourcenoptimierung definieren
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann zwischen Containern und virtuellen… | 2 | Verstehen | unterscheiden, aufzählen |
| A1F  | Ich kann bestehende Container einsetzen… | 3 | Anwenden | einsetzen, anpassen |
| A1E  | Ich kann eine Container-Umgebung mit… | 6 | Erschaffen | planen, aufsetzen |
| B1G  | Ich kann den Unterschied zwischen einer… | 2 | Verstehen | beschreiben |
| B1F  | Ich kann eine Microservice-Architektur mit… | 2 | Verstehen | erläutern |
| B1E  | Ich kann den Einfluss des Microservice-… | 4 | Analysieren | analysieren, vorschlagen |
| C1G  | Ich kann Eigenschaften von synchronen… | 2 | Verstehen | beschreiben, erläutern |
| C1F  | Ich kann Beispiele für synchrone und… | 2 | Verstehen | nennen, zuordnen |
| C1E  | Ich kann für einen gegebenen Anwendungsfall… | 5 | Bewerten | vorschlagen, erklären |
| D1G  | Ich kann Werkzeuge und Methoden zur… | 2 | Verstehen | beschreiben, erklären |
| D1F  | Ich kann den Ablauf zur Erstellung von… | 3 | Anwenden | beschreiben, verwenden |
| D1E  | Ich kann Service-Konfigurationen codebasiert… | 3 | Anwenden | bereitstellen, dokumentieren |
| E1G  | Ich kann Methoden zur Sicherstellung der… | 2 | Verstehen | beschreiben |
| E1F  | Ich kann den Nutzen und Einsatzzweck eines… | 2 | Verstehen | erläutern |
| E1E  | Ich kann ein Versionsverwaltungssystem zur… | 3 | Anwenden | anwenden |
| F1G  | Ich kann Massnahmen und Methoden zur… | 2 | Verstehen | beschreiben |
| F1F  | Ich kann Sicherheitsanforderungen umsetzen… | 3 | Anwenden | umsetzen, prüfen |
| F1E  | Ich kann bei unzureichenden Sicherheitsanforderungen… | 5 | Bewerten | definieren, umsetzen |
| G1G  | Ich kann bereits konfigurierte Datenverbindungen… | 2 | Verstehen | unterscheiden, zuordnen |
| G1F  | Ich kann Konfigurationen für Datenverbindungen… | 3 | Anwenden | umsetzen |
| G1E  | Ich kann eigene Datenverbindungen gemäss… | 3 | Anwenden | konfigurieren |
| H1G  | Ich kann vorgegebene Container bereitstellen… | 3 | Anwenden | bereitstellen, überprüfen |
| H1F  | Ich kann einen oder mehrere Services in… | 3 | Anwenden | bereitstellen, einsetzen |
| H1E  | Ich kann über eine Registry Container-Images… | 3 | Anwenden | wiederverwenden, verfügbar machen |
| I1G  | Ich kann die Zusammenhänge einer containerisierten… | 2 | Verstehen | beschreiben |
| I1F  | Ich kann die Ressourcenverwendung von Services… | 2 | Verstehen | nachvollziehen, überwachen |
| I1E  | Ich kann den Ressourcenbedarf für containerisierte… | 5 | Bewerten | bestimmen, vergleichen, definieren |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Tabellenheader | Tabellenheader und Separator normalisiert; alle Trailing-Punkte entfernt | Formatkonformität gemäss Vorgabe |
| A1F | "Eigenschaften beschreiben" (Duplikat der G-Stufe) → "bestehende Container einsetzen und deren Konfiguration anpassen" | Anwendungsorientiert, höher als G; klare Niveausteigerung |
| A1E | "erläutern" (nur K2) → "planen und aufsetzen" (K3/K4) | Eigenständiges Handeln auf Erweitertstufe |
| B1G | "Unterscheid" → "Unterschied", "monolytischen" → "monolithischen" | Tippfehler behoben |
| B1E | "abwägen" (nicht beobachtbar) → "analysieren und geeignete Massnahmen vorschlagen" | Beobachtbare Handlung gemäss Formulierungsprinzipien |
| B (Band) | "Micro-Service" vereinheitlicht zu "Microservice" | Korrekte Schreibweise |
| C1F | "Beispiele machen" → "Beispiele nennen" | Idiomatischere Formulierung |
| C1E | Zwei Sätze zu einem zusammengeführt | Selbstständigkeit jedes Deskriptors; sprachliche Straffung |
| D1G | "Tools" → "Werkzeuge" | Deutschsprachige Formulierung |
| E1F, E1E | Produktname "Git"/"GIT" → "Versionsverwaltungssystem" | Produktneutralität |
| F1F | "Ihre" → "ihre" | Grossschreibung korrigiert |
| F1E | "schwachen" → "unzureichenden"; Formulierung gestrafft | Präzisere Formulierung |
| G1E | "eigne" → "eigene" | Tippfehler behoben |
| H1F | "verwende" (Mischkonstruktion) → "Ich kann ... einsetzen" | "Ich kann"-Format |
| H1E | Zwei Sätze zusammengeführt; "beschreiben" (K2) durch aktives Handeln ersetzt | Aktive, beobachtbare Handlung auf Erweitertstufe |
| I1F | Formulierung gestrafft und verdeutlicht | Klarheit und Präzision |
| I1E | "Ressourcenbedarf" konkretisiert mit "für containerisierte Services"; zwei Sätze zusammengeführt; "Ressourcen zu managen" → "Ressourcenoptimierung definieren" | Konkretere, beobachtbare Formulierung |
| Bloom-Tabelle | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neu hinzugefügt gemäss Workflow |
| C1G | "aufführen" (Bloom L1) → "beschreiben und deren Unterschiede erläutern" (Bloom L2) | Bloom-Regel: G-Zellen müssen Bloom-Stufe 2 oder 3 erreichen |
| D1G | "aufführen" (Bloom L1) → "beschreiben und deren Einsatzzweck erklären" (Bloom L2) | Bloom-Regel: G-Zellen müssen Bloom-Stufe 2 oder 3 erreichen |
