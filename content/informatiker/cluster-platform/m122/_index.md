---
title: M122 Abläufe mit einer Scriptsprache automatisieren
modul: m122
cluster: cluster-platform
date: '2025-07-02T10:06:45Z'
draft: false
kompetenzbaender:
- id: A
  titel: Auftrag erkennen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann anhand einer Situationsanalyse das Potential einer Automatisierung mit Script erkennen
    fortgeschritten: Ich kann eine Situation mittels einer Methode erfassen und die Anforderungen für eine Automatisierung mit Script bestimmen
    erweitert: Ich kann eine Situationsanalyse vornehmen und mittels verschiedener Methoden die vollständigen Anforderungen für eine Automatisierung mit Script verfassen
- id: B
  titel: Grafische Darstellung
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann einen einfachen Ablauf korrekt grafisch darstellen
    fortgeschritten: Ich kann anspruchsvolle Abläufe korrekt grafisch darstellen
    erweitert: Ich kann komplexe Abläufe nachvollziehbar und korrekt grafisch darstellen
- id: C
  titel: Shell-Befehle und Variablen
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann grundlegende systemspezifische Befehle der vordefinierten Shell aufrufen und die Bedeutung von Variablen beschreiben und sie in einfachen Scripts einsetzen
    fortgeschritten: Ich kann grundlegende systemspezifische Befehle der Shell miteinander verknüpfen (z. B. grep oder findStr) sowie Variablen verändern und in Scripts einsetzen
    erweitert: Ich kann grundlegende systemspezifische Befehle der Shell miteinander verknüpfen und Ausgaben sinnvoll verwenden sowie Variablen anpassen, in Scripts einsetzen und exportieren
- id: D
  titel: Schleifen und Funktionen
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann verschiedene Schleifentypen unterscheiden und einfache Schleifen einsetzen sowie die Bedeutung von Funktionen beschreiben und diese einsetzen
    fortgeschritten: Ich kann Schleifen für die Verarbeitung von Systemaufgaben (Verzeichnisse/Dateien) anwenden und grössere Programm-Strukturen in Funktionen ausgliedern und einbinden
    erweitert: Ich kann Schleifen in Scripts für die Verarbeitung von Automatismen gezielt einsetzen und auch verschachtelte Programm-Strukturen in Funktionen nutzen
- id: E
  titel: Systemintegration
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann das Script mit den zweckmässigen Zugriffsberechtigungen im Home Verzeichnis speichern
    fortgeschritten: Ich kann das Script je nach Zweck in das entsprechende Systemverzeichnis speichern
    erweitert: Ich kann das Script zweckmässig ins entsprechende Systemverzeichnis speichern und es bei einem Systemereignis wie Boot automatisch starten lassen
- id: F
  titel: Zeitsteuerung
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann mein Script zu einem repetitiven Zeitpunkt starten lassen
    fortgeschritten: Ich kann das Script auch zu beliebigen Zeitpunkten wiederholt ausführen lassen
    erweitert: Ich kann das Script auch zu beliebigen Zeitpunkten wiederholt ausführen lassen und die Ausführung überwachen lassen
- id: G
  titel: Debugging
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann mit sinnvollen Ausgaben den Scriptablauf debuggen
    fortgeschritten: Ich kann mit eingefügten Kontrollstrukturen den Scriptablauf debuggen
    erweitert: Ich kann den Scriptablauf mit erweiterten Funktionen debuggen (z. B. DEBUG-Konstante setzen, eigene Debug-Funktion oder verschiedene Debug-Modi einsetzen)
- id: H
  titel: Test
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann einfache Testfälle (z. B. File vorhanden) beschreiben und ausführen
    fortgeschritten: Ich kann sinnvoll gewählte Testfälle (z. B. Sonderzeichen) beschreiben und durchführen
    erweitert: Ich kann sinnvoll gewählte Testfälle (z. B. Sonderzeichen) definieren, beschreiben und ausführen sowie konkrete Massnahmen aus den Resultaten ableiten
- id: I
  titel: Dokumentation und Kommentare
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann eine rudimentäre Dokumentation (Header) in meinem Script anwenden und die Bedeutung von Kommentaren im Code zur Erhaltung der Qualität und Wartbarkeit erläutern
    fortgeschritten: Ich kann eine ausführliche Dokumentation für allgemeine Angaben, Variablen und Funktionen im Script erstellen sowie Kommentare sinnvoll einsetzen, um die Wartbarkeit meines Codes zu erhalten
    erweitert: Ich kann das Script für verschiedene Zielgruppen (System, Administrator, Entwickler) in separater Form dokumentieren (z. B. Readme.md) und zusätzlich die Struktur meines Codes zur Erhaltung der Qualität und Wartbarkeit nutzen sowie Kommentare nachführen
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann anhand einer Situationsanalyse das Potential… | 1 | Erinnern | erkennen |
| A1F  | Ich kann eine Situation mittels einer Methode erfassen… | 3 | Anwenden | erfassen, bestimmen |
| A1E  | Ich kann eine Situationsanalyse vornehmen und mittels… | 3 | Anwenden | vornehmen, verfassen |
| B1G  | Ich kann einen einfachen Ablauf korrekt grafisch… | 3 | Anwenden | darstellen |
| B1F  | Ich kann anspruchsvolle Abläufe korrekt grafisch… | 3 | Anwenden | darstellen |
| B1E  | Ich kann komplexe Abläufe nachvollziehbar und korrekt… | 3 | Anwenden | darstellen |
| C1G  | Ich kann grundlegende systemspezifische Befehle… aufrufen… | 3 | Anwenden | aufrufen, einsetzen |
| C1F  | Ich kann grundlegende systemspezifische Befehle… verknüpfen… | 3 | Anwenden | verknüpfen, einsetzen |
| C1E  | Ich kann grundlegende systemspezifische Befehle… verknüpfen… | 3 | Anwenden | verknüpfen, verwenden, anpassen |
| D1G  | Ich kann verschiedene Schleifentypen unterscheiden… | 3 | Anwenden | unterscheiden, einsetzen |
| D1F  | Ich kann Schleifen für die Verarbeitung von Systemaufgaben… | 3 | Anwenden | anwenden, ausgliedern |
| D1E  | Ich kann Schleifen in Scripts für die Verarbeitung… | 3 | Anwenden | einsetzen, nutzen |
| E1G  | Ich kann das Script mit den zweckmässigen Zugriffsberechtigungen… | 3 | Anwenden | speichern |
| E1F  | Ich kann das Script je nach Zweck in das entsprechende… | 3 | Anwenden | speichern |
| E1E  | Ich kann das Script zweckmässig ins entsprechende Systemverzeichnis… | 3 | Anwenden | speichern, starten lassen |
| F1G  | Ich kann mein Script zu einem repetitiven Zeitpunkt… | 3 | Anwenden | starten lassen |
| F1F  | Ich kann das Script auch zu beliebigen Zeitpunkten… | 3 | Anwenden | ausführen lassen |
| F1E  | Ich kann das Script auch zu beliebigen Zeitpunkten… | 3 | Anwenden | ausführen lassen, überwachen lassen |
| G1G  | Ich kann mit sinnvollen Ausgaben den Scriptablauf… | 3 | Anwenden | debuggen |
| G1F  | Ich kann mit eingefügten Kontrollstrukturen den Scriptablauf… | 3 | Anwenden | debuggen |
| G1E  | Ich kann den Scriptablauf mit erweiterten Funktionen… | 3 | Anwenden | debuggen, einsetzen |
| H1G  | Ich kann einfache Testfälle beschreiben und ausführen… | 3 | Anwenden | beschreiben, ausführen |
| H1F  | Ich kann sinnvoll gewählte Testfälle beschreiben… | 3 | Anwenden | beschreiben, durchführen |
| H1E  | Ich kann sinnvoll gewählte Testfälle definieren, beschreiben… | 4 | Analysieren | definieren, ausführen, ableiten |
| I1G  | Ich kann eine rudimentäre Dokumentation anwenden… | 3 | Anwenden | anwenden, erläutern |
| I1F  | Ich kann eine ausführliche Dokumentation erstellen… | 3 | Anwenden | erstellen, einsetzen |
| I1E  | Ich kann das Script für verschiedene Zielgruppen dokumentieren… | 3 | Anwenden | dokumentieren, nutzen |

---

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| --- | --- | --- |
| Header | "Kompetenzband:" zu "Kompetenzband" (ohne Doppelpunkt) korrigiert | Tabellenformat |
| Header | Separator-Zeile an Qualitätsvorgaben-Standard angepasst | Tabellenformat |
| Alle Kompetenzbänder | Buchstaben-Präfix ergänzt (z. B. "Auftrag erkennen" zu "A - Auftrag erkennen") | Kompetenzband-Format: "Letter + short thematic summary" |
| B1G | "Ich kann einen einfachen Ablauf grafisch darstellen" zu "Ich kann einen einfachen Ablauf korrekt grafisch darstellen" | Spezifisches Feedback: Darstellung muss korrekt sein |
| B1E | "korrekt" ergänzt | Konsistenz: auch auf Erweitert-Stufe soll Korrektheit explizit gefordert sein |
| C1G | "Ich kenne grundlegende systemspezifische Befehle" zu "Ich kann grundlegende systemspezifische Befehle ... aufrufen" | "Ich kann..."-Regel: Alle Deskriptoren müssen mit "Ich kann" beginnen |
| D1G | "Ich kenne die Bedeutung" zu "Ich kann die Bedeutung ... beschreiben" | "Ich kann..."-Regel |
| E1G | "Ich kenne verschiedene Schleifentypen" zu "Ich kann verschiedene Schleifentypen unterscheiden" | "Ich kann..."-Regel |
| F1G | "Ich kenne die Bedeutung von Funktionen" zu "Ich kann die Bedeutung von Funktionen beschreiben" | "Ich kann..."-Regel |
| I1G | "mein Scriptablauf" zu "den Scriptablauf"; Anführungszeichen um "debuggen" entfernt | Grammatik und Konsistenz |
| I1F | "Kontrollstukturen" zu "Kontrollstrukturen"; Anführungszeichen um "debuggen" entfernt | Tippfehler korrigiert; Konsistenz |
| I1E | Anführungszeichen um "debuggen" entfernt; Satz umformuliert | Konsistenz |
| J1G, J1E | "z.B." zu "z. B." | Konsistente Abkürzungsschreibweise |
| K1G | "Ich wende rudimentäre Dokumentation (Header) an" zu "Ich kann eine rudimentäre Dokumentation (Header) in meinem Script anwenden" | "Ich kann..."-Regel |
| K1F | "Das Script beinhaltet ausführliche Dokumentation..." zu "Ich kann eine ausführliche Dokumentation ... erstellen" | "Ich kann..."-Regel: Deskriptor muss aus Sicht der lernenden Person formuliert sein |
| K1E | "Das Script ist ... dokumentiert" zu "Ich kann das Script ... dokumentieren" | "Ich kann..."-Regel |
| L1G | "Ich erkenne die Bedeutung" zu "Ich kann die Bedeutung ... erläutern" | "Ich kann..."-Regel |
| L1F | "Ich nutze die Möglichkeit für Kommentare sinnvoll" zu "Ich kann Kommentare sinnvoll einsetzen" | "Ich kann..."-Regel und klarere Formulierung |
| C (neu) | Ehemaliges Band C (Shell-Befehle) und Band D (System-/Variablen) zusammengeführt zu "C - Shell-Befehle und Variablen" | Beide Bänder gehören zu HZ 2 und behandeln verwandte Grundlagen der Scriptausführung (Befehle und Variablen). Konsolidierung von 12 auf 9 Zeilen. |
| D (neu) | Ehemaliges Band E (Schleifen) und Band F (Funktionen) zusammengeführt zu "D - Schleifen und Funktionen" | Beide Bänder gehören zu HZ 2 und behandeln Kontrollstrukturen und Modularisierung im Script. Konsolidierung von 12 auf 9 Zeilen. |
| I (neu) | Ehemaliges Band K (Dokumentation) und Band L (Kommentare) zusammengeführt zu "I - Dokumentation und Kommentare" | Beide Bänder gehören zu HZ 5 und behandeln die schriftliche Qualitätssicherung des Scripts (externe Doku und Code-Kommentare). Konsolidierung von 12 auf 9 Zeilen. |
| Alle Bänder (E–I) | Buchstaben-Präfixe neu vergeben nach Zusammenführung: G→E, H→F, I→G, J→H, K+L→I | Sequenzielle Neuvergabe nach Konsolidierung, damit Buchstabenfolge lückenlos bleibt. |
| Alle Zellen | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neue Anforderung: Bloom-Analyse pro Zelle |
| C1G, D1G, H1G, H1F, I1G | Bloom-Stufe in Analyse-Tabelle korrigiert: L2 → L3 (Anwenden), da dominante Verben (aufrufen, einsetzen, ausführen, durchführen, anwenden) Bloom-Stufe 3 entsprechen | Bloom-Analyse-Korrektur |
| H1E | Bloom-Stufe in Analyse-Tabelle korrigiert: L3 → L4 (Analysieren), da "ableiten aus den Resultaten" Bloom-Stufe 4 entspricht | Bloom-Analyse-Korrektur |
