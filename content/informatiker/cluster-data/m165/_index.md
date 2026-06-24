---
title: M165 NoSQL-Datenbanken einsetzen
modul: m165
cluster: cluster-data
date: '2025-07-02T10:05:20Z'
draft: false
kompetenzbaender:
- id: A
  titel: NoSQL Grundlagen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann Begriffe und Konzepte der NoSQL Datenbanken erläutern (z. B. CAP-Theorem, BASE, ACID, Indexing Strukturen, Caching, Datenanalyse, Datawarehouse, FullText Search, Netzwerke, Testing)
    fortgeschritten: Ich kann eine NoSQL Datenbank gezielt für eine spezifische Anwendung auswählen (z. B. Document Store für Videos)
    erweitert: Ich kann den Einsatz einer NoSQL Datenbank kritisch hinterfragen und Verbesserungen vorschlagen
- id: B
  titel: NoSQL Datenbank implementieren
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann ein Datenmodell für eine NoSQL Datenbank interpretieren und erläutern
    fortgeschritten: Ich kann ein vorgegebenes Datenmodell mit einer NoSQL Datenbank umsetzen
    erweitert: Ich kann ein Datenmodell für eine NoSQL Datenbank entwerfen
- id: C
  titel: Daten in NoSQL Datenbank eintragen
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann die Struktur von Daten in einer NoSQL Datenbank erläutern
    fortgeschritten: Ich kann Daten in eine NoSQL Datenbank übernehmen
    erweitert: Ich kann Probleme bei der Übernahme von Daten in eine NoSQL Datenbank erkennen und Lösungen aufzeigen
- id: D
  titel: Zugriffsberechtigungen anwenden
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann die Funktion von Zugriffsberechtigungen in einer NoSQL Datenbank erläutern (Benutzer, Rollen, Zugriffsrechte)
    fortgeschritten: Ich kann vordefinierte Zugriffsberechtigungen in einer NoSQL Datenbank umsetzen (z. B. Rollen)
    erweitert: Ich kann ein Konzept für Zugriffsberechtigungen einer NoSQL Datenbank entwerfen
- id: E
  titel: Backup erstellen und Restore durchführen
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann Konzepte für ein Backup einer NoSQL Datenbank erläutern (z. B. on-demand snapshots, continous cloud backups, legacy backups)
    fortgeschritten: Ich kann ein Backup und Restore bei einer NoSQL Datenbank anwenden
    erweitert: Ich kann ein Konzept für das Backup einer NoSQL Datenbank erstellen
- id: F
  titel: Skalierung und Replikation bei einer NoSQL Datenbank anwenden
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann das Prinzip der Skalierung und die unterschiedlichen Replikationsarten für eine NoSQL Datenbank erläutern (z. B. Multimaster, primary and replica, Aktiv-Passiv und horizontale Skalierung)
    fortgeschritten: Ich kann für eine NoSQL Datenbank eine Replikation anwenden
    erweitert: Ich kann ein Konzept für die Skalierung einer NoSQL Datenbank erstellen
- id: G
  titel: Anbindung an NoSQL Datenbank erstellen
  kompetenzen:
  - nr: 1
    hz: '6'
    grundlagen: Ich kann das Prinzip des Zugriffes bei einer NoSQL Datenbank erläutern (z. B. Queries, Projections)
    fortgeschritten: Ich kann eine Anbindung an eine NoSQL Datenbank implementieren (z. B. API)
    erweitert: Ich kann das Prinzip der parallelen Verarbeitung bei NoSQL Datenbanken anwenden (z. B. MapReduce Algorithmen)
---

---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann Begriffe und Konzepte der NoSQL… | 2 | Verstehen | erläutern |
| A1F  | Ich kann eine NoSQL Datenbank gezielt… | 5 | Bewerten | auswählen (gezielt) |
| A1E  | Ich kann den Einsatz einer NoSQL Datenbank… | 5 | Bewerten | hinterfragen, vorschlagen |
| B1G  | Ich kann ein Datenmodell für eine NoSQL… | 2 | Verstehen | interpretieren, erläutern |
| B1F  | Ich kann ein vorgegebenes Datenmodell… | 3 | Anwenden | umsetzen |
| B1E  | Ich kann ein Datenmodell für eine NoSQL… | 6 | Erschaffen | entwerfen |
| C1G  | Ich kann die Struktur von Daten… | 2 | Verstehen | erläutern |
| C1F  | Ich kann Daten in eine NoSQL Datenbank… | 3 | Anwenden | übernehmen |
| C1E  | Ich kann Probleme bei der Übernahme… | 5 | Bewerten | erkennen (Probleme), aufzeigen |
| D1G  | Ich kann die Funktion von Zugriffsberechtigungen… | 2 | Verstehen | erläutern |
| D1F  | Ich kann vordefinierte Zugriffsberechtigungen… | 3 | Anwenden | umsetzen |
| D1E  | Ich kann ein Konzept für Zugriffsberechtigungen… | 6 | Erschaffen | entwerfen |
| E1G  | Ich kann Konzepte für ein Backup… | 2 | Verstehen | erläutern |
| E1F  | Ich kann ein Backup und Restore… | 3 | Anwenden | anwenden |
| E1E  | Ich kann ein Konzept für das Backup… | 6 | Erschaffen | erstellen |
| F1G  | Ich kann das Prinzip der Skalierung… | 2 | Verstehen | erläutern |
| F1F  | Ich kann für eine NoSQL Datenbank… | 3 | Anwenden | anwenden |
| F1E  | Ich kann ein Konzept für die Skalierung… | 6 | Erschaffen | erstellen |
| G1G  | Ich kann das Prinzip des Zugriffes… | 2 | Verstehen | erläutern |
| G1F  | Ich kann eine Anbindung an eine NoSQL… | 3 | Anwenden | implementieren |
| G1E  | Ich kann das Prinzip der parallelen… | 3 | Anwenden | anwenden |

---

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Header | "Kompetenzband:" → "Kompetenzband" (Doppelpunkt entfernt) | Vorgabe Tabellenformat |
| Separator | Grundlagen-Spalte auf `:---` gesetzt | Linksbündige Ausrichtung gemäss Vorgabe |
| Alle Bänder | Buchstaben-Präfix ergänzt (A - ..., B - ..., C - ..., D - ..., E - ..., F - ..., G - ...) | Vorgabe |
| Kompetenzband E | "Backup erstellen Restore durchführen" → "Backup erstellen und Restore durchführen" | Fehlende Konjunktion ergänzt |
| A1G, A1F, A1E, B1G, B1F, B1E, C1G, C1F, D1F, D1E, E1F, E1E, F1F, F1E | Trailing Periods entfernt | Keine abschliessenden Punkte |
| A1G | ". (z. B." → " (z. B.)" | Punkt vor Klammer entfernt |
| Bloom-Tabelle | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neue Anforderung |
