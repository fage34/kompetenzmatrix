---
aliases:
  - /cluster-platform/m122/handlungssituationen/
title: Handlungssituationen
weight: 20
draft: false
---

## Typische Handlungssituationen in diesem Modul

Eine Berufsfachschule erhält regelmässig über Nacht eine CSV-Datei mit den aktuellen Lernenden-Angaben. Toni erhält die Aufgabe, die Daten umzuformen und über eine bestehende ldap-Schnittstelle das Benutzerverwaltungssystem zu aktualisieren.

### 1. Zu automatisierende Funktion oder Ablaufstruktur grafisch darstellen

Toni analysiert den zu automatisierenden Ablauf und stellt den Progammablauf grafisch dar.

### 2. Ablaufstruktur mit Scriptsprache umsetzen

Den oben erwähnten Ablauf in Form eines Diagramms setzt Toni nun per Scriptsprache (z.B. bash) um.

### 3. Script in Systemumgebung integrieren

Das Script wird anschliessend in die Systemumgebung integriert. Dies kann zum Start eines Systems oder zu einem bestimmten Zeitpunkt umgesetzt werden. Dabei sind einheitliches Logging und Error Handling einzuhalten. Schliesslich muss jemand informiert werden, wenn Fehler passieren.

### 4. Ausführung und Funktion eines Scripts testen

Toni bestimmt konkrete Testfälle, überprüft das eigene Script auch mit ungeeigneten Parametern oder falschen Eingaben und versucht es zum Abbruch zu führen.

### 5. Dokumentation für den Einsatz eines Scripts erstellen

Für die  Dokumentation erstellt Toni innerhalb des Scripts nach geeigneten Richtlinien Kopfdaten und Blockbeschreibungen. Code-Lesbarkeit gewährt lange Wartbarkeit des Scripts (z.B. Abkürzungen vermeiden, Einrückungen, Blöcke gestalten). Die Dokumentation des Ablaufs ergänzt Toni im git, inklusive Historisierung der Erstellung/Weiterentwicklung.
