---
title: Handlungssituationen
weight: 20
draft: false
---

# Handlungsziele und Handlungssituationen – Modul 169

## Kompetenz

Stellt lokale Services mit Containern bereit und administriert diese.

___

## Handlungsziele und typische Handlungssituationen

##### 1. Definiert die erforderliche Umgebung für die automatisierte Bereitstellung von Services

Andrea Banz wird beauftragt, mehrere Services mittels Virtualisierung bereitzustellen. Andrea kann aufgrund der Anforderungen eine Microservice-Architektur erkennen und entwickelt eine Lösung basierend auf Containern. Sie achtet dabei auf die Abhängigkeiten zwischen Client und Server. Andrea konfiguriert Container mit entsprechenden Services für die Verwendung in einer lokalen Infrastruktur.

##### 2. Dokumentiert den logischen und physischen Aufbau der Umgebung in einem Netzwerkschema mit servicespezifischen Angaben

Mit Hilfe der Anforderungen und Entscheide aus dem Lösungskonzept erstellt Andrea eine umfassende Dokumentation zur Beschreibung der Container Plattform. Sie beschreibt den Netzwerkaufbau unter Beachtung der logischen und physischen Darstellungsform und macht Angaben zur Netzkonfiguration. Neben einem Blockschaltbild zu den eingesetzten Services wählt Andrea das Schichtenmodell, um die Schnittstellen zwischen Backend und Frontend besser darstellen zu können.

##### 3. Erstellt und dokumentiert den für die Service-Breitstellung erforderlichen Code versioniert

Andrea erstellte die Services mit Konfigurationen, welche als versionierten Code in Dateien verwaltet werden. Bereits bei der Erstellung dieser Konfigurationen verwendet Andrea Kommentare, um die Einstellungen zu dokumentieren. Zusätzlich setzt Andrea Gitlab als Versionsverwaltungssystem ein, um den Code so mit ihrem Team transparent und nachvollziehbar zu teilen.

##### 4 . Plant und realisiert die servicespezifischen Sicherheitsanforderungen

Andrea berücksichtigt sicherheitsrelevante Anforderungen bei der Ausarbeitung der Services und wählt die richtigen Einstellungen für die Konfiguration der Services. Sie überprüft die Wirksamkeit der Sicherheitsmassnahmen mit einem Testkonzept.

##### 5. Erstellt die erforderlichen Datenverbindungen zwischen unterschiedlichen Services

Mit den architektonischen Vorgaben und den bereits ausgewählten Servicearten kann Andrea die notwendigen Konfigurationen zwischen den Services umsetzen. Bei der Erstellung der Datenverbindungen muss Andrea die sicherheitsrelevanten sowie die korrekten Einstellungen für Netzwerk und Authentisierung berücksichtigen. Andrea setzt eine verschlüsselte Verbindung zwischen Front- und Backend Komponente ein.

##### 6. Stellt die Services in der definierten Umgebung reproduzierbar bereit

Andrea benutzt bereits auf dem Entwicklungssystem die identischen Container, welche später für die produktive Umgebung ebenfalls eingesetzt werden können. Dazu pullt sich Andrea Images aus der Registry. Zusätzliche, spezifische Container Images, welche Andrea selber erstellen kann, werden in der Registry für weitere Anwendungen bereitgestellt.

##### 7. Administriert und überwacht die bereitgestellten Services

Andrea kann die Container verwalten, die Funktionsfähigkeit überprüfen und bei Fehlfunktionen in das System eingreifen. Für die Anpassung einer Konfiguration ändert Andrea die Container-Einstellung und führt am betroffenen Service einen restart durch. Im Anschluss prüft sie im Log, ob der Service sich ordnungsgemäss verhält.

##### 8. Versteht anhand der Dokumentation die Funktionalität der Services und unterstützt bei der Fehlersuche

Andreas Kollege Kurt kann mit Hilfe der Dokumentation die Funktionalität des Services Datenbank nachvollziehen. Kurt kennt die Möglichkeiten einen containerbasierten Service zu verwalten und kann dessen Funktionsfähigkeit beurteilen.
