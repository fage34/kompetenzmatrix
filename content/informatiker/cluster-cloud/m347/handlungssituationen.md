---
title: Handlungssituationen
weight: 20
draft: false
---

# Handlungssituationen- Modul 347 - Dienste mit Container anwenden

### Handlungsziele und typische Handlungssituationen
#### 1. Identifiziert Auswirkungen von Virtualisierung auf den beruflichen Alltag.
Der Lernende Hans Muster darf eine neue webbasierte Ticketverkaufs-Applikation für einen Theaterbetrieb mit einer Datenbank entwickeln und in Betrieb nehmen. Das Deployment zwischen den Bereichen *Development, Staging, Produktion* müssen einfach und reibungslos durchgeführt werden. Die neue Applikation muss den kurzfristigen Ansturm von sehr vielen Käufern (Fans) von Tickets innert kurzer Zeit standhalten können und keine Ausfälle/Unterbrüche erleiden. Ferner soll die Ticket-Applikation besser gegen Hacking-Angriffen und Leerverkäufen abgesichert sein.
Für die Version 1.0 sollen die Kosten im vorherein kalkulierbar und niedrig sein. Da der Lehrbetrieb kein Rechenzentrum selber betreibt, soll der Betrieb der Webapplikation extern gelöst werden. Bevor mit der Umsetzung begonnen werden kann, muss Hans die wichtigsten Anforderungen erheben und eine Entscheidungsmatrix soll die Vor- und Nachteile (Kosten, Qualität, Zeit, Bandbreite, Hardware, Instanzen, Skalierbarkeit, Wartung) veranschaulichen und quantifizieren.

#### 2.	Wählt eine geeignete Containerkomposition (Architektur) situationsbezogen aus.

Der Lernende Hans Muster überlegt sich einen sinnvollen Aufbau für die Ticket-Applikation. Von einem Kollegen hat er vernommen, dass eine Microservice-Architektur passend für sein Vorhaben ist. Er recherchiert deshalb über das Thema und überlegt sich, welche Services er für die TicketApp benötigt. 
Ferner muss die TicketApp gegen fremde Zugriffe geschützt werden und er überlegt sich, wie die TicketApp in der Produktion abgesichert werden soll. Zusätzlich muss Hans dem Systemadministrator im Lehrbetrieb darlegen, wie er sich das Deployment zwischen Bereichen vorstellt und es funktionieren soll. Hans weiss, je mehr er automatisieren kann, desto mehr wird der Systemadministrator das Projekt gegenüber der Geschäftsleitung unterstützen.

####  3. Wählt geeignete Containerdienstleister gemäss Anforderungen aus.

Der Lernende Hans Muster hat die verschiedenen Cloud-Anbieter kurz analysiert und jeder bietet mehr oder weniger dieselben Dienstleistungen an. Hans hat sich für den Cloudanbieter X (z.B. AWS) aufgrund der erstellen Entscheidungsmatrix entschieden. Nun folgt der praktische Teil: Er muss sich mit seiner Prepaid-Kreditkarte registrieren, welche vom Lehrbetrieb finanziert wird. Er wählt Stadt X als Region und eine *\*nix free tier instance* zum Starten. Bezüglich die Verfügbarkeitszonen (*Availability Zones*) wird er sich später näher befassen. Für Hans ist es zuerst wichtig, dass er bestehende Container auf der Instanz startet und diese Seite über das Internet abrufbar/erreichbar ist. Dazu muss er verschiedene Netzwerkeinstellungen vornehmen und testen (VPC, Subnet, Gateway, NAT, Bastion).

#### 4. Virtualisiert eine Applikation mit der gewählten Containerkomposition sowohl zu Entwicklungszwecken als auch für Auslieferung/Betrieb.

Der Lernende Hans Muster entscheidet sich in der ersten Iteration für eine Containerkomposition mit Microservices für Authentifizierung/Autorisierung (z.B. Java Web Tokens), Produktkatalog (Tickets und Gadgets als Produkte) und Basket/Checkout/Payservice. Die Microservices werden auf Basis von Containern erstellt, die einen Webclients, einen Webserver und eine Datenbank enthalten. Die Containerkomposition wird in dieser Iteration als Singlehost betrieben. Im Netzwerk kommunizieren die Container über eine one-to-one-Verbindung. Sämtliche Container werden anhand von Konfigurationsdateien (z.B. Docker Files) erstellt. Sämtliche Microservices werden über ihre Schnittstellen auf Funktionstüchtigkeit und Sicherheit überprüft.

#### 5. Plant Methoden zur Qualitätskontrolle und setzt diese um.

Der Geschäftsleitung (GL) ist es noch unklar, wie die Qualität der Ticket-Applikation nach der containerbasierten Virtualisierung überprüft werden soll. Deshalb beauftragt sie Hans mit einem Konzept zur Qualitätssicherung  der Ticket-Applikation. Das Konzept soll beschreiben, wie Funktionalität, Sicherheit und die Performance (z.B. bei Käufer-Ansturm) der containerisierten Ticket-App kontrolliert wird.
