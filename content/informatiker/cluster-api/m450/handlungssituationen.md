---
title: Handlungssituationen
weight: 20
draft: false
---

# Handlungssituationen - Modul 450

Zu jedem Handlungsziel aus der Modulidentifikation (hier gekürzt wiedergegeben) werden keine, eine oder mehrere realistische, beispielhafte und konkrete Handlungssituationen beschrieben, die zeigen, wie die Kompetenzen in der Praxis angewandt werden.

## Handlungsziele HZ

1. Testkonzept
2. Testumfeld
3. Definition von Tests und deren Testmittel
4. Verbesserungsvorschläge innerhalb von Code Reviews
5. Wiederholbare Testfälle definieren
6. Automatisierte Testfälle ausführen und Resultate dokumentieren
7. Korrekturmassnahmen umsetzen
8. Schnittstellen testen

## Handlungssituationen HS

| HZ       | HS |
| -------- | -- |
|  1, 2    | A  |
|  3, 5, 6 | B  |
|  5, 6, 7 | C  |
|  4, 7, 8 | D  |

### Handlungssituation A - Testkonzept

Handlungsziele: 1, 2

Andrea arbeitet als Softwareentwicklerin bei einem Unternehmen, das eine neue mobile Anwendung entwickelt. Die Anwendung soll es Nutzern ermöglichen, ihre täglichen Aufgaben besser zu organisieren und zu verwalten. 

Andrea wurde gebeten, ein Testkonzept unter Berücksichtigung der Anforderungen zu erstellen und das Testumfeld zu beschreiben, einschliesslich der Hard- und Softwareanforderungen sowie Netzwerkkonfiguration, Betriebssysteme und Datenbanken. Dabei muss sie die Testziele, Teststrategien, Testarten, Testlevel, Testdurchführung, Testabdeckung, Testergebnisse und Fehlermanagement berücksichtigen sowie die Verantwortungen festlegen. 

Die Anforderungen für die Anwendung wurden bereits von den Projektverantwortlichen und dem Team festgelegt.

### Handlungssituation B - Testdefinition

Handlungsziele: 3, 5, 6

Aufgrund des Testkonzepts macht sich Andrea Gedanken zur Testdurchführung. 

Sie erstellt eine Strategie für die Durchführung von Tests, einschliesslich der Auswahl der Testmethoden und -werkzeuge, die für die Durchführung der Tests erforderlich sind. Sie arbeitet eng mit ihrem Team zusammen, um Testpläne und -szenarien zu erstellen und sicherzustellen, dass sie alle Anforderungen des Kunden und des Produkts erfüllen.

### Handlungssituation C - Automatisierung

Handlungsziele: 5, 6, 7

Der Arbeitgeber von Andrea entwickelt eine neue Applikation, die aus einem Core und verschiedenen Add-ons besteht. Um die Qualität der Core-Funktionalität zu gewährleisten und um eine CI/CD-Pipeline etablieren zu können, erhält Andrea den Auftrag, das Testing zu planen und durchzuführen. Damit die CI/CD-Pipeline automatisiert durchlaufen kann, entschliesst sich Andrea, das Testing zu automatisieren.

Für die Schnittstellen zwischen dem Core und den Add-ons wurde durch das Entwicklerteam in der Planung bereits klar definiert, welche Methoden existieren und mit welchen Parametern diese Methoden aufgerufen werden müssen. Es existiert ebenfalls eine grobe Beschreibung, welche Funktionalitäten die Funktionen zur Verfügung stellen müssen.

Andrea nimmt diese vorhandenen Informationen aus der Planung und schreibt damit Unit-Tests, die in einer entsprechenden Unit-Test-Umgebung automatisiert ausgeführt werden können. Andrea achtet dabei darauf, sowohl den Funktionsaufruf mit den unterschiedlichen Parametern, als auch auf die Return-Werte, die die entsprechende Methode als Antwort liefert zu überprüfen. Andrea schaut ebenfalls darauf, dass sowohl gültige wie auch ungültige Parameter getestet werden. Dazu müssen Grenzwerte wie auch ganz normale, zufällig ausgewählte Werte als Parameter für das Testing verwendet werden. Dabei achtet Andrea darauf, dass ihre Testfälle (Unit-Tests) exakt mit den Anforderungen aus den Planungsdokumenten übereinstimmen. Sie verwendet Mockup-Objekte, um die einzelnen Unit-Tests unabhängig voneinander zu schreiben.

Die codierten Unit-Tests übergibt Andrea nun dem Entwicklerteam, welches den Code zu den Testfällen implementiert. Wenn Andrea an alle Testfälle gedacht hat und das Entwicklerteam die Applikation so entwickelt hat, dass alle Testfälle erfüllt / bestanden werden, dann ist die Entwicklung des Core's der Applikation abgeschlossen und kann so in den produktiven Betrieb übergehen.

Andrea stellt deshalb sicher, dass die CI/CD-Pipeline die Applikation nur dann deployed wenn auch alle Unit-Tests erfolgreich ausgeführt werden konnten und keiner der Tests fehlschlägt.

### Handlungssituation D - Review

Handlungsziele: 4, 7, 8

Andrea erhält den Auftrag, den Sourcecode bezgl dem Einhalten von Standards (Clean-Code Prinzipien etc.) zu überprüfen und Vorschläge zur Verbesserung zu machen.

In diesem Zusammenhang schaut Andrea auch die Unit-Tests an und macht Vorschläge, wie man diese verbessern kann. Sie überarbeitet die bestehenden Testfälle und erweitert diese, damit die Testabdeckung optimal ist.
Dabei achtet sie auch darauf, dass die Testfälle den Anforderungen (User Stories) entsprechen.

Die gemachten Anpassungen werden nach einem automatisierten Testdurchlauf ins Repository gemerged.

Somit ist der Review erfolgreich abgeschlossen und Andrea ist stolz darauf, dass ihr Testkonzept zum Erfolg des Projekts beigetragen hat.
