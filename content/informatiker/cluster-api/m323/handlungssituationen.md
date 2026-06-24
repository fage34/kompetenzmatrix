---
aliases:
  - /cluster-api/m323/handlungssituationen/
title: Handlungssituationen
weight: 20
draft: false
---

# Handlungsziele und typische Handlungssituationen

Zu jedem Handlungsziel aus der Modulidentifikation (hier 
gekürzt wiedergegeben) werden keine, eine oder mehrere 
realistische, beispielhafte und konkrete Handlungssituationen 
beschrieben, die zeigen, wie die Kompetenzen in der Praxis 
angewandt werden.

## Handlungsziel 1 - Analyse und Beschreibung von Anforderungen

Andrea hat bereits Erfahrungen mit der imperativen Programmierung. 
Doch nun steht sie vor der Herausforderung die Deklarative 
Programmierung für die Lösung anzuwenden. Als Vorbereitung 
setzt sie sich mit der Deklarativen Programmierung auseinander 
und identifiziert Unterschiede zu Imperativen Programmierung. 
Sie formuliert die Anforderungen (Beschreibung des Endzustandes). 
Weiter entwirft sie für die Lösung ein Functional-Design 
(Anwenden der Elemente des Functionl-Design). 

## Handlungsziel 2 - Implementation von Algorithmen und Lösung von Problemen

a.) Andrea kann neue Anforderungen in bestehende Programme, insbesondere in
Funktionen einbinden, solche erweitern oder entsprechend umbauen.

b.) Andrea hat die Übersicht über die gängigen Entwurfsmuster (Design-Pattern, Builder-Pattern)
und weiss diese auf das aktuelle Problem anzuwenden.

c.) Es liegt vom Projekt-Team oder von den Business-Analysten, bzw. 
vom Projektowner und dem Entwicklerteam ein analysiertes Problem 
(user story) oder ein Algorithmus vor. Nun kann Andrea die Aufgabe 
in Teil-Probleme unterteilen und versucht geschlossene funktionelle 
Teile zu finden und als "Funktionen" (auch "Methoden") zu benennen. 
Bei den "Funktionen" bestimmt Andrea die Übergabeparameter und die 
Rückgabe-Daten oder Rückgabe-Strukturen.

## Handlungsziel 3 - Refactoring von bestehendem Code durch Anwendung funktionaler Programmierung

Andrea arbeitet in einem Team von Softwareentwickler:innen, das an einer Schulverwaltungssoftware arbeitet. Das Team hat einen Codeblock entwickelt, der für das Erstellen von Benutzerprofilen verant-wortlich ist. Allerdings wurde festgestellt, dass der Code ineffizient ist und die Erstellung der Profile zu lange dauert. Andrea erhält die Aufgabe, den Code zu analysieren, ein Refaktoring durchzuführen sowie den Code zu optimieren, um die Leistung in diesem Bereich zu verbessern.
Hierfür müssen ineffiziente Stellen identifiziert und der Code optimiert werden, um die Leistung bei der Erstellung der Profile zu verbessern. Gleichzeitig muss sichergestellt werden, dass das Refactoring keine unerwünschten Nebeneffekte hat und das Verhalten des Codes unverändert bleibt. Um dies zu gewähr-leisten, müssen vorgängig geeignete Tests geschrieben werden, die unerwünschtes Verhalten des ange-passten Codes unmittelbar erkennt.


## Handlungsziel 4 - Prüfung der Implementierung

Die Überprüfung einer Code-Refaktorisierung, wie sie von Andrea durchgeführt wird, ist ein wichtiger Schritt, um sicherzustellen, dass die Änderungen effektiv und sicher sind. Dieser Prozess umfasst mehrere Stufen.

Zunächst sollte Andrea, bevor sie mit der Refaktorisierung beginnt, umfangreiche Tests für den aktuellen Code schreiben. Diese Tests sollten alle Aspekte der Funktionalität abdecken, die der Codeblock derzeit bietet. Unit-Tests, Integrationstests und End-to-End-Tests sind in diesem Fall alle relevant. Die Unit-Tests konzentrieren sich auf einzelne Funktionen, während die Integrationstests sicherstellen, dass verschiedene Teile des Codes korrekt miteinander interagieren. End-to-End-Tests überprüfen, ob der gesamte Prozess, in diesem Fall die Erstellung eines Benutzerprofils, wie erwartet funktioniert.

Nachdem die Tests geschrieben und erfolgreich ausgeführt wurden, kann Andrea mit der Refaktorisierung beginnen. Sie sollte versuchen, die Ineffizienzen im Code zu identifizieren und entsprechend zu optimieren, wobei sie stets auf die Wartbarkeit und Lesbarkeit des Codes achtet.

Sobald die Refaktorisierung abgeschlossen ist, sollten die zuvor geschriebenen Tests erneut ausgeführt werden. Dies gewährleistet, dass das Verhalten des Codes trotz der Änderungen unverändert bleibt. Falls ein Test fehlschlägt, deutet dies auf ein Problem hin, das behoben werden muss. Andrea muss dann den Code überarbeiten, bis alle Tests wieder erfolgreich sind.

Zusätzlich zu diesen Tests könnte Andrea auch Leistungstests durchführen, um sicherzustellen, dass die Refaktorisierung tatsächlich die erwarteten Verbesserungen bringt. Sie kann den refaktorisierten Code mit dem ursprünglichen Code vergleichen, um festzustellen, ob die Änderungen die Geschwindigkeit und Effizienz der Profilerstellung verbessert haben.

Schließlich ist es auch wichtig, dass der refaktorisierte Code einer Code-Review unterzogen wird. Andere Mitglieder des Teams sollten den Code überprüfen, um sicherzustellen, dass er den Qualitätsstandards entspricht und keine offensichtlichen Fehler oder Probleme enthält. Dieser Prozess hilft auch dabei, sicherzustellen, dass der Code gut verständlich und wartbar ist.

Insgesamt ist die Überprüfung einer Code-Refaktorisierung ein mehrstufiger Prozess, der sowohl automatisierte Tests als auch manuelle Überprüfungen durch das Team beinhaltet. Dies gewährleistet, dass die Änderungen sowohl sicher als auch effektiv sind.
