---
title: Handlungssituationen
weight: 20
draft: false
---

# Handlungsziele und Handlungssituationen – Modul 158

##### Ausgangslage

Andrea arbeitet für einen Systemintegratoren. Andreas Kundin, eine etwa vor zehn Jahren frisch entstandene Anwaltskanzlei, benötigte damals eine gemeinsame Datenablage. Ein Mitarbeiter der Anwaltskanzlei, ein Wirtschafsjurist, kannte NextCloud aus seinem privaten Umfeld und richtete für die Kanzlei auf einem lokal laufenden Server (NAS) eine NextCloud-Infrastruktur ein. Diese Umgebung läuft seitdem und die rund 10 Mitarbeitenden der Kanzlei benutzen die Funktionen (Datenablage, Agenda, Kontaktlisten) von NextCloud mittlerweile intensiv. Doch um die Wartung kümmerte sich niemand. Der Mitarbeiter verliess die Firma in der Zwischenzeit und man sucht eine zukunftsfähige Lösung. Mit NextCloud ist man aber grundsätzlich zufrieden.

##### 1. Auf Grund eines Auftrages die Migration für den Wechsel auf die neue Software-Version (Major Release) oder auf eine neue Software mit ähnlicher Funktionalität erarbeiten. Dokumentation mit Release Informationen sichten und relevante Punkte für die Migration erkennen und festhalten

Andrea erhält den Auftrag, sich für die Migration der Applikation alle notwenigen Informationen zu beschaffen: Dazu gehören die Übersicht zum Aufbau und die Datenhaltung der Applikation, notwendige Voraussetzungen, die Release Notes und nötige Aktualisierungs-Schritte. Andrea spricht in dieser Phase mit allen betroffenen Personen, um deren Bedürfnisse zu erfassen.

Damit die Applikation zukünftigen Anforderungen, wie bessere Wartbarkeit, Skalierbarkeit und häufigere Produktzyklen, gewappnet ist, analysiert Andrea die Möglichkeiten anderer Architekturen im Aufbau der einzelnen Dienste. Insbesondere kam auch der Wunsch auf, die Installation in einer Cloud-Umgebung zu vollziehen, damit das extra eingerichtete VPN nicht mehr benötigt werden.

##### 2. Neue Version oder neue Software auf einem Testsystem installieren und sich mit den wesentlichen Unterschieden / Neuerungen vertraut machen

Andrea stellt fest, dass NextCloud in verschiedenen Architekturen betrieben werden kann. Weil Andrea sich noch nicht so genau damit auskennt, probiert Andrea mehrere davon aus. Konkret wird snap, docker und native Installation getestet und die Vor- und Nachteile evaluiert. Für die Testumgebung sind die Datenbestände noch nicht relevant, es wird mit Testdaten gearbeitet. Andrea nutzt letztlich "Infrastructure as Code", um die Installation vorzunehmen. Konkret werden die Instanzen per Terraform und Ansible in Betrieb genommen.

Dabei merkt Andrea, dass NextCloud nicht aus einem Teil besteht, sondern die einzelnen Dienste auseinander genommen werden müssen. Andrea analysiert also die Applikation, um die Bestandteile und die Schnittstellen zu verstehen und in verschiedene Tiers aufzuteilen.

##### 3. Zu migrierende Datenbestände analysieren, identifizieren und Funktionalität auf dem Testsystem mit der neuen Version bzw. der neuen Software erproben. Relevante Punkte für die Migration erkennen und festhalten
##### 4. Bisherige Daten extrahieren, aufbereiten und ins neue System laden. Wo möglich die Vorgänge automatisieren

Nun führt Andrea in die Testinstallation auch bestehende Datenbestände ein. Dabei merkt Andrea, dass in der Zwischenzeit das Datenbankmodell geändert wurde und die Daten aufwändig migriert werden müssen. Andrea wird also die SQL-Scripts anpassen müssen, um keine Daten zu verlieren.

Bei den Konfigurationseinstellungen stellen sich Fragen, woher gewisse Werte übernommen werden sollen. Andrea möchte die Installation als Pilot verwenden, um später ähnliche Installationen zu beschleunigen.

Andrea exportiert alle Daten aus der bisherigen Lösung und führt diese möglichst automatisiert ins neue Datenformat, welches in die neue Lösung eingespielt werden können. Die Dokumentation der Migration ist für die Nachvollziehbarkeit notwendig.

##### 5. In einer Testumgebung die Funktionalität, Verfügbarkeit, Sicherheit und Vollständigkeit der Umstellung nachweisen und einen Freigabeantrag stellen

In einer Testumgebung installierte Andrea das neue System inkl. Import der produktiven Daten. Dank ausführlichem Testplan lässt sich dieses System ausgiebig testen. Darin sind Tests aufgeführt, welche die Funktionalität der Applikation prüfen. Weitere Tests stellen sicher, dass die Qualität der Applikation (Sicherheit, Verfügbarkeit, Performance, etc.) überprüft werden kann. Andrea spielt alle diese Testfälle durch und schreibt die Ergebnisse in ein Testprotokoll.

Im Freigabeantrag beschreibt Andrea die Resultate dieser Tests und gibt eine Empfehlung zur Einführung.

##### 6. User-, Betriebs- und Wartungsdokumentation anpassen, definitive Umstellung planen und bewilligen lassen

Die Einführung der neuen Applikation führt dazu, dass diverse Angaben in vorhandenen Anleitungen angepasst werden müssen. In der Benutzerdokumentation beschreibt Andrea die neuen Funktionen, integriert Screenshots der neuen Eingabemasken und beschreibt geänderte Abläufe. In der Betriebsdokumentation dokumentiert Andrea, wie die neue Applikation gestartet wird, wie ein Smoketest (in der Programmierung bezeichnet smoke-testing den ersten grundlegenden Probelauf einer Software) durchgeführt werden kann und wie die Backup-/Restore-Prozedur neu verläuft. In der Wartungsdokumentation aktualisiert Andrea Hinweise auf das Programm-Repository, die eingesetzte Version, die benötigten Rechte, etc.

Andrea überlegt sich, was alles zu tun ist, damit die neue Applikation produktiv eingesetzt werden kann. Bei der Planung berücksichtigt Andrea folgende Punkte:

- Migration der Software und der Daten
- Tests für die Sicherstellung der Übernahme
- festlegen, welche Person wofür verantwortlich ist
- wann welcher Task zu erledigen ist
- welche Ressourcen nötig sind.

Andrea bezieht die von der Umstellung betroffenen Personen mit ein (Schulung und Kommunikation). Für den Start der Übergabe in die Produktion holt Andrea das Einverständnis der auftraggebenden Person ein.

##### 7. Umstellung durchführen oder durchführen lassen

Vor der produktiven Einführung der neuen Applikation hat sich Andrea den Ablauf der Migration genau überlegt und aufgeschrieben: was ist wann zu tun und wer ist dafür zuständig. Nachdem die Freigabe durch die auftraggebende Person erfolgt ist, startet Andrea die Migration. Nach erfolgter Migration und einem reduzierten Test gibt Andrea in Absprache mit der auftraggebenden Stelle den produktiven Einsatz frei.
