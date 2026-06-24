---
title: Handlungssituationen
weight: 20
draft: false
---

# Handlungsziele und typische Handlungssituationen - Modul 165

**1. Wählt eine für den Anwendungsfall geeignete NoSQL-Datenbank aus (z.B. Document-Store, Graphen-basiert, Key-Value-Store, Wide-Column-Store, Objekt-orientiert, in-Memory).**

Die Firma Datasoft vertreibt verschiedene Produkte. Um den Umgang mit den Produkten zu visualisieren, ist geplant, eine grosse Anzahl von Schulungsvideos zu erstellen. Paul Muster erhält den Auftrag, diese Videos in einem flexiblen und sicheren Datensystem zu verwalten. Paul Muster recherchiert mögliche Datensysteme und klärt die Unterschiede zwischen NoSQL- und SQL-Datenbanken ab. Er entschliesst sich eine NoSQL Datenbank zu verwenden. Nun untersucht er die Möglichkeiten und Einsatzgebiete der verschiedenen NoSQL Formen (Document-Store, Graphen-orientiert...) und evaluiert eine NoSQL-Datenbank.
Paul Muster setzt auf eine dokumenten-orientierte NoSQL Datenbank, die ein einfaches Springen innerhalb des abgerufenen Videos unterstützt (z. B. MongoDB mit GridFS). 

**2. Implementiert eine NoSQL-Datenbank und befüllt sie mit Daten.**

Um sich ein Bild über das Datenmodell zu machen, klärt Paul Muster weitere Bedürfnisse des Auftraggebers ab (z. B. User Verwaltung, Zugriffs-History ...). Dann setzt sich Paul Muster mit dem Modellieren von Daten in einer NoSQL Datenbank auseinander und modelliert sein Datenmodell. Er validiert das Schema und überträgt das Schema in die Datenbank.

Dann lädt Paul Muster die ersten Daten (z. B. Videos) in die Datenbank.

**3. Definiert Zugriffsberechtigungen und setzt diese in der NoSQL-Datenbank um.**

Paul Muster klärt ab, welche Zugriffsberechtigungen notwendig sind. Er informiert sich über die Möglichkeiten der Datenbank. Er entschliesst sich, dass er den Zugriff rollen-basiert verwalten wird. Während die Rolle Besucher die Videos nur abrufen darf, können Personen mit der Rolle des Managers die Videos auch hochladen oder löschen. 
Paul Muster erstellt ein Konzept mit Rollen und setzt dieses in der Datenbank um.

**4. Sichert eine NoSQL-Datenbank in einem Backup und prüft die Wiederherstellung.**

Paul Muster setzt sich mit den verschiedenen Möglichkeiten eines Backups für die Datenbank auseinander (z. B. on-demand snapshots, continuous cloud backups, legacy backups). Er probiert Möglichkeiten aus, macht mit Testdaten ein Backup und eine Wiederherstellung. Damit kann er nun dem Plattformentwickler bei den Anforderungen an die Backuplösung helfen. Das effektive Backup wird vom Plattformentwickler in der Cloudlösung umgesetzt.

**5. Skaliert eine NoSQL-Datenbank, z. B. durch Replikation.**

Die Videos erfreuen sich einer grossen Beliebtheit. Der Daten-Traffic nimmt stark zu. Der Datentransfer mit nur einer Datenbank kommt an seine Leistungsgrenze. Paul Muster probiert Möglichkeiten zur Skalierung (Replikation, Cluster) mit Testdaten aus. Damit kann er nun dem Plattformentwickler bei den Anforderungen an die Skalierung helfen. Die effektive Lösung wird vom Plattformentwickler in der Cloudlösung umgesetzt.

**6. Nutzt die NoSQL-Datenbank lesend und schreibend aus einer Anwendung.**

Die Schulungsvideos müssen auf der Webseite der Firma Datasoft angeboten werden. Dazu braucht es eine Anbindung der Webapplikation an die NoSQL Datenbank. Paul Muster setzt sich mit dem Zugriff auf die Daten der Datenbank auseinander (z. B. GridFS, Queries, CRUD). Er kapselt die Zugriffe in einer neuen API-Komponente und vereinfacht so den Zugriff für andere Clients. Er definiert die Calls der API und setzt die Komponente um.
