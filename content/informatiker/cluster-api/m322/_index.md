---
title: M322 Benutzerschnittstellen entwerfen und implementieren
modul: m322
cluster: cluster-api
date: '2025-07-02T10:05:05Z'
draft: false
kompetenzbaender:
- id: A
  titel: Nutzungsanalyse und Vorgehensmodell
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann die Bestandteile einer Anforderungsanalyse erklären und ein Vorgehensmodell zur Erhebung von Anforderungen beschreiben (z.B. Design Thinking, User Centered Design)
    fortgeschritten: Ich kann eine Methode zur Analyse von Nutzungsumfeld, Aufgaben und Benutzerverhalten anwenden und die Ergebnisse einer Anforderungsanalyse erläutern
    erweitert: Ich kann eine bestehende Anforderungsanalyse hinterfragen, ein iteratives Vorgehensmodell begründet auswählen und gewonnene Erkenntnisse in konkrete Anforderungen überführen
- id: A
  titel: Benutzerprofile und Anforderungsspezifikation
  kompetenzen:
  - nr: 2
    hz: '1'
    grundlagen: Ich kann den Zweck einer methodischen Erfassung von Benutzereigenschaften erklären und eine Methode zur Dokumentation von Nutzungsanforderungen beschreiben (z.B. Persona, Use Cases, User Stories)
    fortgeschritten: Ich kann Benutzerprofile methodisch erstellen (z.B. Persona, Empathy Map) und Nutzungsanforderungen dokumentieren und spezifizieren
    erweitert: Ich kann Benutzerprofile optimieren und Nutzungsanforderungen bewerten und priorisieren (z.B. Backlog)
- id: B
  titel: Usability-Grundsätze und Interaktionsprinzipien
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann das Konzept der Gebrauchstauglichkeit (Usability) erklären und verschiedene Interaktionselemente einer Benutzerschnittstelle identifizieren (z.B. Menu, Navigation, Orientierung)
    fortgeschritten: Ich kann die Interaktionsprinzipien einer bestehenden Benutzerschnittstelle erklären (z.B. nach ISO 9241-110) und passende Interaktionselemente nach Konventionen auswählen und anordnen
    erweitert: Ich kann Interaktionsprinzipien für eine neue Benutzerschnittstelle festlegen und eine bestehende Benutzerschnittstelle in Bezug auf Interaktionselemente analysieren und optimieren
- id: B
  titel: Benutzerschnittstelle entwerfen
  kompetenzen:
  - nr: 2
    hz: '2'
    grundlagen: Ich kann einzelne Dialoge (Screens, z.B. als Wireframe) skizzieren
    fortgeschritten: Ich kann eine Abfolge (Flow) von Dialogen (Screens) als Papierprototyp präsentieren
    erweitert: Ich kann eine Abfolge (Flow) einer Benutzerschnittstelle als Klickprototypen entwerfen
- id: B
  titel: Eingaben, Hilfe und Feedback
  kompetenzen:
  - nr: 3
    hz: '2'
    grundlagen: Ich kann Regeln zur Kennzeichnung von Pflichtfeldern und Eingabeformaten erklären und geeignete Hilfefunktionen für eine Benutzerschnittstelle beschreiben (z.B. Sternchen, Datumsformat)
    fortgeschritten: Ich kann Eingabeformate selbsterklärend kennzeichnen und geeignete Feedbackinformationen für eine Benutzerschnittstelle vorschlagen
    erweitert: Ich kann Pflichtfelder und Eingabeformate vollständig selbsterklärend kennzeichnen und die Vollständigkeit sämtlicher Hilfefunktionen sowie Feedbackinformationen einer Benutzerschnittstelle überprüfen und begründet optimieren
- id: C
  titel: Controls, Widgets und Prototyp
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann einfache Controls und Widgets benennen und erklären und die entworfenen Skizzen in einen klickbaren Prototyp umsetzen
    fortgeschritten: Ich kann Controls und Widgets für ein Interaktionsziel auswählen, sinnvoll platzieren und ein Vorhaben mit einem klickbaren Prototyp testen sowie mögliche Probleme identifizieren
    erweitert: Ich kann komplexere und zusammengesetzte Interaktionselemente entwerfen, Probleme im Prototyp analysieren, Verbesserungsvorschläge erarbeiten und den Prototypen überarbeiten
- id: C
  titel: Benutzerfreundlichkeit verbessern
  kompetenzen:
  - nr: 2
    hz: '3'
    grundlagen: Ich kann typische bezüglich der Benutzerfreundlichkeit schwierig umzusetzende Elemente erklären und deren häufige Probleme einordnen
    fortgeschritten: Ich kann Vorschläge zur Verbesserung der Benutzerfreundlichkeit unterbreiten
    erweitert: Ich kann aus einem Element bezüglich Benutzbarkeit eine bessere, einfachere und intuitive Lösung erarbeiten
- id: D
  titel: Usability testen und messen
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann einen Walkthrough einer Benutzerschnittstellen-Abfolge durchführen und einen standardisierten Fragebogen erklären (z.B. SUS, HEART)
    fortgeschritten: Ich kann einen Usability-Test bezüglich Benutzerfreundlichkeit durchführen und anhand eines standardisierten Fragebogens eine Nachbefragung auswerten
    erweitert: Ich kann einen Usability-Test bezüglich Benutzerfreundlichkeit und Business-Effizienz planen und durchführen sowie Ergebnisse analysieren und Verbesserungsvorschläge ableiten
- id: E
  titel: Barrierefreiheit umsetzen und prüfen
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann die Anforderungen an eine barrierefreie Benutzerschnittstelle beschreiben und Möglichkeiten zur Überprüfung der Barrierefreiheit erläutern (z.B. Checkliste)
    fortgeschritten: Ich kann Elemente einer Benutzerschnittstelle barrierefrei umsetzen (Labels, Tab-Navigation, Kontrast, Alternativtext usw.) und eine Benutzerschnittstelle gemäss Checkliste auf Barrierefreiheit prüfen
    erweitert: Ich kann geeignete Elemente für eine barrierefreie Benutzerschnittstelle vorschlagen und die Barrierefreiheit einer Benutzerschnittstelle vollständig nachweisen
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G | Ich kann die Bestandteile einer Anforderungsanalyse erklären… | 2 | Verstehen | erklären, beschreiben |
| A1F | Ich kann eine Methode zur Analyse von Nutzungsumfeld… anwenden… | 3 | Anwenden | anwenden, erläutern |
| A1E | Ich kann eine bestehende Anforderungsanalyse hinterfragen… | 5 | Bewerten | hinterfragen, begründet auswählen |
| A2G | Ich kann den Zweck einer methodischen Erfassung… erklären… | 2 | Verstehen | erklären, beschreiben |
| A2F | Ich kann Benutzerprofile methodisch erstellen… dokumentieren… | 3 | Anwenden | erstellen, dokumentieren |
| A2E | Ich kann Benutzerprofile optimieren und… bewerten und priorisieren… | 5 | Bewerten | bewerten, priorisieren |
| B1G | Ich kann das Konzept der Gebrauchstauglichkeit… erklären… | 2 | Verstehen | erklären, identifizieren |
| B1F | Ich kann die Interaktionsprinzipien einer bestehenden… erklären… | 2 | Verstehen | erklären, auswählen |
| B1E | Ich kann Interaktionsprinzipien für eine neue Benutzerschnittstelle… | 4 | Analysieren | festlegen, analysieren, optimieren |
| B2G | Ich kann einzelne Dialoge… skizzieren… | 3 | Anwenden | skizzieren |
| B2F | Ich kann eine Abfolge (Flow) von Dialogen… als Papierprototyp präsentieren… | 3 | Anwenden | präsentieren |
| B2E | Ich kann eine Abfolge (Flow) einer Benutzerschnittstelle… entwerfen… | 6 | Erschaffen | entwerfen |
| B3G | Ich kann Regeln zur Kennzeichnung von Pflichtfeldern… erklären… | 2 | Verstehen | erklären, beschreiben |
| B3F | Ich kann Eingabeformate selbsterklärend kennzeichnen… vorschlagen… | 5 | Bewerten | vorschlagen |
| B3E | Ich kann Pflichtfelder und Eingabeformate vollständig… überprüfen… | 5 | Bewerten | überprüfen, begründet optimieren |
| C1G | Ich kann einfache Controls und Widgets benennen und erklären… | 2 | Verstehen | benennen, erklären, umsetzen |
| C1F | Ich kann Controls und Widgets für ein Interaktionsziel auswählen… | 3 | Anwenden | auswählen, platzieren, testen |
| C1E | Ich kann komplexere und zusammengesetzte Interaktionselemente entwerfen… | 6 | Erschaffen | entwerfen, analysieren, erarbeiten |
| C2G | Ich kann typische… schwierig umzusetzende Elemente erklären… | 2 | Verstehen | erklären, einordnen |
| C2F | Ich kann Vorschläge zur Verbesserung der Benutzerfreundlichkeit… | 5 | Bewerten | vorschlagen |
| C2E | Ich kann aus einem Element bezüglich Benutzbarkeit… erarbeiten… | 6 | Erschaffen | erarbeiten |
| D1G | Ich kann einen Walkthrough einer Benutzerschnittstellen-Abfolge… | 3 | Anwenden | durchführen, erklären |
| D1F | Ich kann einen Usability-Test… durchführen und… auswerten… | 4 | Analysieren | durchführen, auswerten |
| D1E | Ich kann einen Usability-Test… planen und durchführen… analysieren… | 4 | Analysieren | planen, analysieren, ableiten |
| E1G | Ich kann die Anforderungen an eine barrierefreie Benutzerschnittstelle beschreiben… | 2 | Verstehen | beschreiben, erläutern |
| E1F | Ich kann Elemente einer Benutzerschnittstelle barrierefrei umsetzen… prüfen… | 5 | Bewerten | umsetzen, prüfen |
| E1E | Ich kann geeignete Elemente für eine barrierefreie Benutzerschnittstelle vorschlagen… | 5 | Bewerten | vorschlagen, nachweisen |

---

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Header | `Kompetenzband:` → `Kompetenzband` (Doppelpunkt entfernt) | Vorgabe Tabellenformat |
| Separator | → `| --- | --- | :--- | --- | --- |` | Vorgabe Tabellenformat |
| Alle Bänder | Buchstaben-Präfix A–E ergänzt | Vorgabe Tabellenformat |
| A4G | `A4G` → `A4G:` | Fehlender Doppelpunkt ergänzt |
| D2E | `D1E:` → `D2E:` | Falscher Zell-Identifier korrigiert |
| C1G | "Ich kenne einfache Controls..." → "Ich kann einfache Controls... benennen und erklären" | "Ich kann"-Format |
| C2G | "Ich setze die entworfenen Skizzen..." → "Ich kann die entworfenen Skizzen... umsetzen" | "Ich kann"-Format |
| C3G | "Bezüglich der Benutzerfreundlichkeit erkenne ich..." → "Ich kann bezüglich der Benutzerfreundlichkeit... erkennen" | "Ich kann"-Format |
| B3G (ehem.) | "identifzieren" → "identifizieren" | Tippfehler |
| C3F (ehem.) | "Benutzerferundlichkeit" → "Benutzerfreundlichkeit" | Tippfehler |
| D1G (ehem.) | "Walktrough" → "Walkthrough" | Tippfehler |
| A3E (ehem.) | "gewonnen" → "gewonnenen" | Tippfehler |
| D - Bandname (ehem.) | "Usablility" → "Usability" | Tippfehler |
| C3F (ehem.) | "zur Verbesserung Benutzerfreundlichkeit" → "zur Verbesserung der Benutzerfreundlichkeit" | Fehlender Artikel |
| Diverse Zellen | Trailing Periods entfernt | Keine abschliessenden Punkte |
| Diverse Zellen | Doppelte Leerzeichen entfernt | Formatbereinigung |
| A1+A2+A3 → A1 | Anforderungsanalyse, Vorgehensmodell und Nutzungskontext zu einer Zeile zusammengeführt | Alle drei adressieren den methodischen Analyseprozess (HZ 1) |
| A4+A5 → A2 | Benutzerprofile und Anforderungsspezifikation zu einer Zeile zusammengeführt | Beide befassen sich mit der Dokumentation von Nutzenden und ihren Anforderungen (HZ 1) |
| B1+B3 → B1 | Usability-Grundsätze und Interaktionsprinzipien zusammengeführt | Beides sind konzeptionelle Grundlagen der Dialoggestaltung (HZ 2) |
| B4+B5 → B3 | Eingabeformate und Hilfe/Feedback zusammengeführt | Beide betreffen konkrete UI-Elemente zur Nutzerführung (HZ 2) |
| C1+C2 → C1 | Controls/Widgets und Prototypimplementierung zusammengeführt | Untrennbar: Elemente kennen und direkt im Prototyp einsetzen (HZ 3) |
| C3 → C2 | Benutzerfreundlichkeit bleibt eigenständig, Identifier angepasst | Eigenständiges Thema (HZ 3) |
| D1+D2 → D1 | Usability-Testing und Messung (Fragebogen) zusammengeführt | Beide beschreiben den vollständigen Usability-Prüfprozess (HZ 4) |
| E1+E2 → E1 | Barrierefreiheit umsetzen und prüfen zusammengeführt | Untrennbar: Umsetzung und Verifikation gehören zusammen (HZ 5) |
| A2G | "begründen und … erklären" → "erklären und … beschreiben" | Bloom-Regel 1: G-Zelle enthielt "begründen" (Stufe 5); korrigiert auf Stufe 2 (Verstehen) |
| B3E | "vollständig kennzeichnen und sämtliche Hilfefunktionen abbilden" → "überprüfen und begründet optimieren" ergänzt | Bloom-Regel 2: B3F ist Stufe 5 (Bewerten), B3E muss ≥ Stufe 5 sein |
| C2G | "schwierig umzusetzende Elemente erkennen" → "benennen und deren häufige Probleme beschreiben" | Bloom-Regel 1: G-Zelle enthielt "erkennen" im Sinne von Muster erkennen (Stufe 4); korrigiert auf Stufe 1 (Erinnern) |
| Bloom-Tabelle | Neu hinzugefügt | Bloom-Taxonomie-Analyse für alle G/F/E-Zellen ergänzt |
| A1G | "nennen" → "erklären" | Bloom-Regel 1: G-Zelle war auf Stufe 1 (Erinnern); korrigiert auf Stufe 2 (Verstehen) |
| B3G | "nennen … identifizieren" → "erklären … beschreiben" | Bloom-Regel 1: G-Zelle war auf Stufe 1 (Erinnern); korrigiert auf Stufe 2 (Verstehen) |
| C2G | "benennen und deren häufige Probleme beschreiben" → "erklären und deren häufige Probleme einordnen" | Bloom-Regel 1: G-Zelle war auf Stufe 1 (Erinnern); korrigiert auf Stufe 2 (Verstehen) |
| E1G | "nennen" → "beschreiben" | Bloom-Regel 1: G-Zelle war auf Stufe 1 (Erinnern); korrigiert auf Stufe 2 (Verstehen) |
