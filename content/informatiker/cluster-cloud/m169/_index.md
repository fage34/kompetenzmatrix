---
aliases:
  - /cluster-cloud/m169/
  - /v2/cluster-cloud/m169/
title: M169 Dienste mit Containern bereitstellen
modul: m169
cluster: cluster-cloud
date: "2025-07-02T10:05:17Z"
draft: false
kompetenzbaender:
  - id: A
    titel: Container-Umgebung definieren
    kompetenzen:
      - nr: 1
        hz: 1,2,8
        grundlagen: Ich kann zwischen Containern und virtuellen Maschinen unterscheiden
          sowie deren Vor- und Nachteile aufzählen
        fortgeschritten: Ich kann bestehende Container einsetzen und deren Konfiguration
          anpassen
        erweitert: Ich kann eine Container-Umgebung mit einem oder mehreren Services
          planen und aufsetzen
  - id: B
    titel: Microservice-Architektur erläutern
    kompetenzen:
      - nr: 1
        hz: 1,2
        grundlagen: Ich kann den Unterschied zwischen einer monolithischen und einer
          Microservice-Architektur beschreiben
        fortgeschritten: Ich kann eine Microservice-Architektur mit Eigenschaften eines
          verteilten Systems, wie Schnittstellen und Vernetzung, erläutern
        erweitert: Ich kann den Einfluss des Microservice-Paradigmas auf eine
          Zielarchitektur analysieren und geeignete Massnahmen vorschlagen
  - id: C
    titel: Synchrone und asynchrone Services unterscheiden
    kompetenzen:
      - nr: 1
        hz: 1,2,5
        grundlagen: Ich kann Eigenschaften von synchronen und asynchronen Services
          beschreiben und deren Unterschiede erläutern
        fortgeschritten: Ich kann Beispiele für synchrone und asynchrone Anwendungsfälle
          nennen und diese einem Verwendungszweck zuordnen
        erweitert: Ich kann für einen gegebenen Anwendungsfall geeignete Schnittstellen
          vorschlagen und den Zusammenhang zwischen verteilten Systemen und
          asynchronen Services erklären
  - id: D
    titel: Codebasierten Serviceaufbau einsetzen
    kompetenzen:
      - nr: 1
        hz: "3"
        grundlagen: Ich kann Werkzeuge und Methoden zur Beschreibung von Services
          mittels Infrastructure as Code (IaC) beschreiben und deren
          Einsatzzweck erklären
        fortgeschritten: Ich kann den Ablauf zur Erstellung von codebasierten Services
          beschreiben und Werkzeuge mit Syntaxunterstützung sowie Prüfung der
          Codekonsistenz verwenden
        erweitert: Ich kann Service-Konfigurationen codebasiert in Containern
          bereitstellen und mit IaC dokumentieren
  - id: E
    titel: Qualität für codebasierte Service-Bereitstellung sicherstellen
    kompetenzen:
      - nr: 1
        hz: 3,4
        grundlagen: Ich kann Methoden zur Sicherstellung der Qualität bei der Verwendung
          von Code beschreiben
        fortgeschritten: Ich kann den Nutzen und Einsatzzweck eines
          Versionsverwaltungssystems erläutern, insbesondere hinsichtlich
          Qualität für codebasierte Service-Bereitstellung
        erweitert: Ich kann ein Versionsverwaltungssystem zur Verwaltung und Erstellung
          von versioniertem, kommentiertem Code anwenden
  - id: F
    titel: Sicherheitsanforderungen berücksichtigen
    kompetenzen:
      - nr: 1
        hz: "4"
        grundlagen: Ich kann Massnahmen und Methoden zur Umsetzung von
          Sicherheitsanforderungen beschreiben
        fortgeschritten: Ich kann Sicherheitsanforderungen umsetzen und auf ihre
          Wirksamkeit prüfen
        erweitert: Ich kann bei unzureichenden Sicherheitsanforderungen zusätzliche
          Massnahmen definieren und umsetzen, um die Sicherheit zu erhöhen
  - id: G
    titel: Datenverbindungen zwischen Services konfigurieren
    kompetenzen:
      - nr: 1
        hz: 4,5
        grundlagen: Ich kann bereits konfigurierte Datenverbindungen unterscheiden und
          ihrem Nutzen zuordnen
        fortgeschritten: Ich kann Konfigurationen für Datenverbindungen nach Vorgaben
          umsetzen, um einen sicheren Datenaustausch zwischen Services zu
          ermöglichen
        erweitert: Ich kann eigene Datenverbindungen gemäss Anforderungen zur Sicherheit
          und Persistenz konfigurieren
  - id: H
    titel: Services in Containern bereitstellen
    kompetenzen:
      - nr: 1
        hz: 6,7,8
        grundlagen: Ich kann vorgegebene Container bereitstellen und ihre
          Funktionsfähigkeit mit geeigneten Mitteln überprüfen
        fortgeschritten: Ich kann einen oder mehrere Services in Containern
          bereitstellen und geeignete Mittel zur Behebung von Fehlern einsetzen
        erweitert: Ich kann über eine Registry Container-Images wiederverwenden und
          eigene Images in der Registry verfügbar machen
  - id: I
    titel: Services administrieren und überwachen
    kompetenzen:
      - nr: 1
        hz: 7,8
        grundlagen: Ich kann die Zusammenhänge einer containerisierten Infrastruktur und
          erforderliche Massnahmen für eine zuverlässige Überwachung beschreiben
        fortgeschritten: Ich kann die Ressourcenverwendung von Services nachvollziehen
          und überwachen
        erweitert: Ich kann den Ressourcenbedarf für containerisierte Services mit
          konkreten Annahmen bestimmen, diesen mit dem effektiven Bedarf
          vergleichen und Massnahmen zur Ressourcenoptimierung definieren
---
