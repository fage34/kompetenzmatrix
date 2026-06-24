---
title: Handlungssituationen
weight: 20
draft: false
---

# Handlungsziele und Handlungssituationen – Modul 159

Zu jedem einzelnen Handlungsziel aus der Modulidentifikation wird eine realistische, beispielhafte und konkrete Handlungssituation beschrieben, die zeigt, wie die Kompetenzen in der Praxis angewendet werden.

##### 1. **Kundenbedürfnisse, vorhandene Services, abzugleichende Verzeichnisse (Synchronisation) und Kommunikationsprozesse analysieren und dokumentieren.**

Hanna und Patrick analysieren bei ihrem Kunden, dem *Kurszentrum für berufliche Integration*, folgende Aspekte:

* die Datenhaltung im Kurssystem, mit Stammdaten, Anmeldungen
* die Benutzerdatenbank der IT-Systeme für den Zugang zu den Arbeitsplätzen und dem Netzwerk
* Schnittstelle zu externem Partner mit Kundendaten

Für das neue Kursmanagementsystem, das Hanna und Patrick implementieren werden, sollen möglichst die Daten aus den bestehenden Systemen (Directory-Services) übernommen werden. Dort wo nötig soll der Datenfluss angepasst und Synchronisierungen proaktiv, sowie automatisch angestossen werden.

##### 2. **Vorgaben und Ergebnisse auf Machbarkeit, Vollständigkeit und Funktionalität  überprüfen und in einem Directoryservices-Konzept abbilden.**

Für das Kursmanagementsystem und evtl. auch die interne IT soll ein Slave-Directoryservice installiert werden, der zeitnah die notwendigen Daten bereitstellt, die aus den anderen Systemen übernommen werden. Aus Datenschutzgründen (Datensparsamkeit) werden nur zwingend benötigte Felder abgebildet. Hanna und Patrick erstellen einen Überblick, wie der Aufbau dieses Systems aussieht und welche Synchronisationen zu welchen Zeitpunkten erfolgen sollen.

##### 3. **Directoryservice gemäss definiertem Konzept konfigurieren und implementieren.**

Hanna und Patrick installieren und konfigurieren einen passenden Service und setzen den entsprechenden Directoryservice mit auf.

##### 4. **Synchronisation der Directoryservices mit geeigneten Mitteln realisieren.**

Auf dem installierten Directory werden von den beiden die Synchronisationen eingerichtet, so dass die Daten gemäss Vorgabe im Directory vorhanden sind.

##### 5. **Funktionalität der Directoryservices gemäss Anforderungen testen und Ergebnisse im  Testprotokoll festhalten. Bei Bedarf, erforderliche Korrekturen  vornehmen.**

Hanna und Patrick überprüfen die Validität der Daten, überprüfen die Synchronisation gemäss der Vorgabe und beobachten die Prozesse: Änderung von Einträgen, Neueinträge und Löschung von Einträgen. Tritt ein fehlerhaftes Verhalten auf, wird dieses korrigiert.

##### 6. **Bestehende Daten, falls erforderlich automatisiert, in den Directoryservice  migrieren. Fehlerfreies Zusammenwirken mit anderen Diensten  sicherstellen und testen.**

Der Directoryservice wird nun an das neue Kursmanagementsystem verbunden. Hanna und Patrick prüfen die Funktionalität, wie beispielsweise die Anmeldung und Einschreibung.

##### 7. **Übergabe in den operativen Betrieb planen, Abnahme vorbereiten und durchführen. Betriebs- und Wartungsdokumentation nachführen.**

Nachdem der Testbetrieb während mehreren Synchronisationsphasen reibungslos funktioniert hat, wird die Dokumentation nachgeführt und der Service an den Kunden übergeben.
