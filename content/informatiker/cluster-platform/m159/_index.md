---
title: M159 Directoryservices konfigurieren und in Betrieb nehmen
modul: m159
cluster: cluster-platform
date: '2025-07-02T10:06:32Z'
draft: false
kompetenzbaender:
- id: A
  titel: Struktur und Objekte
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann die Datenstruktur und die Objekte eines Directory Services auslesen und dokumentieren.
    fortgeschritten: Ich kann die Datenstruktur und die Objekte eines Directory Services auslesen, dokumentieren und deren logischen Aufbau in einem Diagramm darstellen.
    erweitert: Ich kann die Datenstruktur und die Objekte eines Directory Services analysieren, dokumentieren und Optimierungsmöglichkeiten für den logischen Aufbau vorschlagen.
- id: B
  titel: Einsatz Directory Service
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann die Zusammenhänge zwischen Directory Service und angebundenen Systemen aufzeigen.
    fortgeschritten: Ich kann die Kommunikation zwischen Directory Service und angebundenen Systemen nachvollziehen und Fehler in der Anbindung identifizieren.
    erweitert: Ich kann die Zusammenhänge und die Kommunikation zwischen Directory Service und angebundenen Systemen analysieren und deren Zuverlässigkeit beurteilen.
- id: C
  titel: LDAP als Protokoll
  kompetenzen:
  - nr: 1
    hz: 2, 6
    grundlagen: Ich kann die Methoden des LDAP in der Praxis erläutern.
    fortgeschritten: Ich kann die Methoden des LDAP in Praxisanwendungen gezielt einsetzen und deren Abläufe nachvollziehbar aufzeigen.
    erweitert: Ich kann die Methoden des LDAP in Praxisanwendungen einsetzen, Risiken erkennen und geeignete Gegenmassnahmen vorschlagen.
- id: D
  titel: Suche im Directory
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann über eine LDAP-Suche einzelne Objekte finden.
    fortgeschritten: Ich kann über eine LDAP-Suche mit verschachtelten Suchfiltern gezielte Objekte finden.
    erweitert: Ich kann über eine LDAP-Suche mit verschachtelten Suchfiltern gezielte Objekte finden und komplexe Suchfilter in Anwendungen einpflegen, um bedingte Anmeldungen oder Synchronisierungen zu ermöglichen.
- id: E
  titel: Objektklassen und Attribute
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann Objektklassen benennen, deren Attribute erkennen und mögliche Werte erläutern.
    fortgeschritten: Ich kann Objektklassen einem Verwendungszweck zuweisen und deren Attribute mit ihren Eigenschaften (einwertig, mehrwertig, zwingend, optional, Typ) gezielt konfigurieren.
    erweitert: Ich kann Objektklassen einem Verwendungszweck zuweisen, deren Attribute mit ihren Eigenschaften konfigurieren und das Prinzip anwenden, um eine neue Objektklasse zu entwerfen.
- id: F
  titel: LDIF
  kompetenzen:
  - nr: 1
    hz: 2, 6
    grundlagen: Ich kann das LDIF-Format anwenden und vorhandene Dateien anpassen.
    fortgeschritten: Ich kann Dateien im LDIF verfassen, um Objekte zu erstellen, zu ändern oder zu löschen.
    erweitert: Ich kann Daten in LDIF-Dateien exportieren, LDIF-Dateien erstellen, um Objekte zu erstellen, zu ändern oder zu löschen. Zudem kann ich über LDIF-Dateien Directory Services migrieren.
- id: G
  titel: Datenaustausch
  kompetenzen:
  - nr: 1
    hz: 3, 4
    grundlagen: Ich kann den Datenaustausch zwischen verschiedenen Directory Service-Instanzen sowie zu anderen Diensten aufzeigen.
    fortgeschritten: Ich kann den Datenaustausch zwischen verschiedenen Directory Service-Instanzen sowie zu anderen Diensten einrichten und fachgerecht konfigurieren (Funktion, Sicherheit).
    erweitert: Ich kann den Datenaustausch zwischen verschiedenen Directory Service-Instanzen sowie zu anderen Diensten einrichten und konfigurieren. Für den Betrieb optimiere ich Synchronisation und Sicherheitseinstellungen.
- id: H
  titel: Testen
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann die Funktionalität des Directory Service und angebundener Systeme testen.
    fortgeschritten: Ich kann die Funktionalität des Directory Service und angebundener Systeme mit sinnvoll gewählten Tests belegen und Fehlverhalten beheben.
    erweitert: Ich kann die Funktionalität des Directory Service und angebundener Systeme mit sinnvoll gewählten Tests belegen. Ich erkenne Optimierungspotenzial und Fehlverhalten und kann Verbesserungen umsetzen.
- id: I
  titel: Dokumentation und Übergabe
  kompetenzen:
  - nr: 1
    hz: '7'
    grundlagen: Ich kann wesentliche Aspekte eines Directory Service inkl. Umsysteme dokumentieren.
    fortgeschritten: Ich kann eine vollständige Dokumentation der Directory Service-Umgebung erstellen, in der alle Systeme und Synchronisationen fachgerecht dokumentiert werden.
    erweitert: Ich kann eine vollständige und nachvollziehbare Dokumentation der Directory Service-Umgebung erstellen, in der alle Systeme, Synchronisationen, Konfigurationen, Funktionstests und Planungsüberlegungen abgebildet werden.
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann die Datenstruktur und die Objekte auslesen… | 3 | Anwenden | auslesen, dokumentieren |
| A1F  | Ich kann die Datenstruktur und die Objekte auslesen, dokumentieren… | 3 | Anwenden | auslesen, dokumentieren, darstellen |
| A1E  | Ich kann die Datenstruktur und die Objekte analysieren… | 5 | Bewerten | analysieren, dokumentieren, vorschlagen |
| B1G  | Ich kann die Zusammenhänge zwischen Directory Service aufzeigen… | 3 | Anwenden | aufzeigen |
| B1F  | Ich kann die Kommunikation zwischen Directory Service nachvollziehen… | 4 | Analysieren | nachvollziehen, identifizieren |
| B1E  | Ich kann die Zusammenhänge und die Kommunikation analysieren… | 5 | Bewerten | analysieren, beurteilen |
| C1G  | Ich kann die Methoden des LDAP in der Praxis erläutern… | 2 | Verstehen | erläutern |
| C1F  | Ich kann die Methoden des LDAP in Praxisanwendungen einsetzen… | 3 | Anwenden | einsetzen, aufzeigen |
| C1E  | Ich kann die Methoden des LDAP einsetzen, Risiken erkennen… | 5 | Bewerten | einsetzen, erkennen, vorschlagen |
| D1G  | Ich kann über eine LDAP-Suche einzelne Objekte finden… | 3 | Anwenden | finden |
| D1F  | Ich kann über eine LDAP-Suche mit verschachtelten Suchfiltern… | 3 | Anwenden | finden |
| D1E  | Ich kann über eine LDAP-Suche gezielte Objekte finden und einpflegen… | 3 | Anwenden | finden, einpflegen |
| E1G  | Ich kann Objektklassen benennen, deren Attribute erkennen… | 1 | Erinnern | benennen, erkennen, erläutern |
| E1F  | Ich kann Objektklassen einem Verwendungszweck zuweisen… | 3 | Anwenden | zuweisen, konfigurieren |
| E1E  | Ich kann Objektklassen zuweisen, Attribute konfigurieren und entwerfen… | 6 | Erschaffen | zuweisen, konfigurieren, anwenden, entwerfen |
| F1G  | Ich kann das LDIF-Format anwenden und Dateien anpassen… | 3 | Anwenden | anwenden, anpassen |
| F1F  | Ich kann Dateien im LDIF verfassen… | 3 | Anwenden | verfassen |
| F1E  | Ich kann Daten in LDIF-Dateien exportieren, LDIF-Dateien erstellen… | 3 | Anwenden | exportieren, erstellen, migrieren |
| G1G  | Ich kann den Datenaustausch zwischen Directory Service-Instanzen aufzeigen… | 3 | Anwenden | aufzeigen |
| G1F  | Ich kann den Datenaustausch einrichten und konfigurieren… | 3 | Anwenden | einrichten, konfigurieren |
| G1E  | Ich kann den Datenaustausch einrichten, konfigurieren und optimieren… | 5 | Bewerten | einrichten, konfigurieren, optimieren |
| H1G  | Ich kann die Funktionalität des Directory Service testen… | 3 | Anwenden | testen |
| H1F  | Ich kann die Funktionalität mit sinnvoll gewählten Tests belegen… | 3 | Anwenden | belegen, beheben |
| H1E  | Ich kann die Funktionalität mit sinnvoll gewählten Tests belegen… | 4 | Analysieren | belegen, erkennen, umsetzen |
| I1G  | Ich kann wesentliche Aspekte eines Directory Service dokumentieren… | 3 | Anwenden | dokumentieren |
| I1F  | Ich kann eine vollständige Dokumentation der Directory Service-Umgebung erstellen… | 3 | Anwenden | erstellen |
| I1E  | Ich kann eine vollständige und nachvollziehbare Dokumentation erstellen… | 3 | Anwenden | erstellen |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| --- | --- | --- |
| A1F | "deren logischen Aufbau erklären" ersetzt durch "deren logischen Aufbau in einem Diagramm darstellen" | Feedback: Zu viele "erklären" auf Stufe Fortgeschritten. Darstellung ist eine anwendungsbezogene, beobachtbare Tätigkeit. |
| A1E | Formulierung gestrafft und auf "analysieren" und "Optimierungsmöglichkeiten vorschlagen" fokussiert | Klarere Abgrenzung zu A1F; eigenständig lesbar gemacht. |
| B1F | "Zusammenhänge und Kommunikation erklären" ersetzt durch "Kommunikation nachvollziehen und Fehler in der Anbindung identifizieren" | Feedback: "erklären" durch anwendungsbezogene Handlung ersetzt. |
| C1F | "Methoden des LDAP erklären und Abläufe aufzeigen" ersetzt durch "Methoden des LDAP gezielt einsetzen und Abläufe nachvollziehbar aufzeigen" | Feedback: "erklären" durch aktives "einsetzen" ersetzt. |
| C1E | Formulierung gestrafft; "erklären" entfernt und auf "einsetzen, Risiken erkennen, Gegenmassnahmen vorschlagen" fokussiert | Eigenständige Formulierung sichergestellt; Redundanz zu C1F entfernt. |
| E1F | "Eigenschaften erklären" ersetzt durch "Attribute gezielt konfigurieren" | Feedback: "erklären" durch konkrete Anwendungshandlung ersetzt. |
| E1E | Formulierung eigenständig gemacht; "das Prinzip anwenden, um eine neue Objektklasse zu entwerfen" | Eigenständigkeit-Regel sichergestellt; kein Satzbezug auf E1F. |
| F1G | "LDIF erklären" ersetzt durch "LDIF-Format anwenden" | Audit: Grundlagen-Stufe soll beobachtbare Handlung beschreiben, nicht erklären. |
| Kompetenzband-Spalte | Bindestriche nach Buchstaben ergänzt (z.B. "A - Struktur und Objekte") | Audit: Einhaltung des Formats ("Letter + short thematic summary"). |
| H1G, H1F, H1E | "angebundenen Systemen" korrigiert zu "angebundener Systeme" | Audit: Grammatikkorrektur (Genitiv statt Dativ). |
| I1E | "Konfiguration" zu "Konfigurationen" (Plural), "Planung bzw. Überlegungen dazu" gestrafft zu "Planungsüberlegungen" | Audit: Konsistenz und Lesbarkeit verbessert. |
| Alle Zellen | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neue Anforderung: Bloom-Analyse pro Zelle |
